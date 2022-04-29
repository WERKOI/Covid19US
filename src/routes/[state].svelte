<script context="module">//скрипт выполняется в контексте нашей страницы
    export async function preload(page){//экспортируем асинхронную функцию
        console.log(page);
        return{ state: page.params['state'] };   
    }
</script>

<script>
    import CovidStat from "../components/CovidStat.svelte";//импортируем CovidStat.svelte
    
    import CovidChart from "../components/CovidChart.svelte";//импортируем CovidChart.svelte
    
    import TableContainer from "../components/TableContainer.svelte";//импортируем TableContainer.svelte
    
    export let state;
 </script>

<h1>{state}</h1>

<CovidStat /><!--вызов CovidStat-->

<CovidChart /><!--вызов CovidChart-->