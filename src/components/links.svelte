
<script>
    import Icon from "@iconify/svelte";
</script>
<span>

    <span class="flex max-md:justify-center">
        Follow me on:
    </span>
    
    <nav class="flex max-md:grid grid-cols-3 grid-rows-0 gap-4 ">
        
        <a 
        href="https://www.tiktok.com/@ocopio.l" 
        class="m-2
        ease-in
        duration-100
        text-white
        hover:bg-[#010101]
        hover:text-white">

            <Icon icon="ic:baseline-tiktok" width="24" height="24" />
        </a>
        
        
        <a 
        href="https://www.youtube.com/@ocopio.L" 
        class="m-2
        ease-in
        duration-100
        text-white
        hover:bg-[#c3352e]
        hover:text-white">
            <Icon icon="mdi:youtube" width="24" height="24" />
        </a>
        
        <a 
        href="https://www.youtube.com/channel/UCc-4slVBbE0VLWGma8qG3LQ" 
        class="m-2 
        ease-in
        duration-100
        text-white
        hover:bg-[#c3352e]
        hover:text-white">

            <Icon icon="simple-icons:youtubemusic" width="24" height="24" />

        </a>
    
        <a 
        href="https://open.spotify.com/artist/73XRM28zMr2I76wCvvXU9J" 
        class="m-2
        ease-in
        duration-100
        text-white
        hover:bg-[#1ed760]
        hover:text-white">

            <Icon icon="mdi:spotify" width="24" height="24" />

        </a>
        <a 
        href="https://music.apple.com/us/artist/l-a-ocopio/1817982283" 
        class="m-2
        ease-in
        duration-100
        text-white
        hover:bg-[#FC3C44]
        hover:text-white">

            <Icon icon="simple-icons:applemusic" width="24" height="24" />

        </a>
        <a 
        href="https://www.deezer.com/en/artist/328382701"
        class="m-2
       
        ease-in
        duration-100
        text-white
        hover:bg-[#8956FB]
        hover:text-white">

            <Icon icon="cbi:deezer-logo" width="24" height="24" />

        </a>
    </nav>
    
    
</span>

<span>
    <a id="discord" class="m-2
    ease-in
    flex flex-row
    align-center
    duration-100
    text-white
    hover:bg-[#7289DA]
    hover:text-white" 
    
    href="https://discord.gg/uGAV3bQ8xj" target="_blank">

        <Icon icon="ic:baseline-discord" width="24" height="24" /> <p class="px-1"> Join our Discord Server</p>

    </a>
</span>

<style>
    a{
        border-style:solid;
        border-width: 1px;
        border-radius: 50%;
        padding: 1rem;


    }
    #discord{
            border-radius: 1.5rem;
        }
</style>
