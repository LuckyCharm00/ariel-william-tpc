<script>
    import ModuleCard from "../components/moduleCard.svelte";
import ModuleCircleButton from "../components/moduleCircleButton.svelte";
</script>

<svelte:head>
    <title>Trial</title>
</svelte:head>

<h1>Ariel-William TPC</h1>


<div class="grid grid-cols-10 gap-3 w-full">
    <div class="col-span-3"><ModuleCard moduleCard = {ModuleCard}/></div>
    <div class="col-span-3"><ModuleCard moduleCard = {ModuleCard}/></div>
    <div class="col-span-3"><ModuleCard moduleCard = {ModuleCard}/></div>
    <div class="col-span-1 self-center"><ModuleCircleButton moduleCircleButton = {ModuleCircleButton}/></div>
</div>

    

