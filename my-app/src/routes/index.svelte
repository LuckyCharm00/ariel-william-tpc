<script>
    import ModuleCard from "../components/moduleCard.svelte";
</script>

<svelte:head>
    <title>Trial</title>
</svelte:head>

<h1>Ariel-William TPC</h1>

<div class="grid grid-cols-3 gap-3">
    <ModuleCard moduleCard={ModuleCard}/>
    <ModuleCard moduleCard={ModuleCard}/>
    <ModuleCard moduleCard={ModuleCard}/>
</div>


