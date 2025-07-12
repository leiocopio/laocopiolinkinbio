<script>
    import Links from "../components/links.svelte";
    import Brands from "../components/brands.svelte";
</script>

<div class="flex flex-row 
justify-around h-[100vh]
items-center 
max-md:flex-col 
max-md:justify-center
align-center
mx-[3rem]
max-md:mx-[2.5rem]
">
    <span class="my-2">
        <Brands class="m-[1rem]"/>
    </span>
    <br>
    <span class="my-2">
        <Links class="m-[1rem]" />
    </span>
    

</div>


