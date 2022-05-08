<script>
  export let ModuleCard;
  import ModuleProgress from "./moduleProgress.svelte";
</script>

<a class ="h-40 w-40" href="">
    <img src="https://api.lorem.space/image/shoes?w=400&h=225" alt="Random Picture">
    <div><ModuleProgress moduleProgress={ModuleProgress}/></div>
</a>