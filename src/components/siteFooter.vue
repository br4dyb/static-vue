<script setup> 

 defineProps({
    siteVersion : String
 })

</script>


<template> 
    <footer class="bg-black/30 text-white/40 fill-white/45 text-xs flex flex-col justify-center items-center content-center flex-wrap gap-1 p-2 w-full h-fit">
        
        <!-- <div class="w-[95%] h-[1.5px] bg-white"></div> -->

        <div class="flex flex-wrap justify-center items-center content-center text-center gap-1 p-1">
            <svg class="opacity-80 mr-0.5 fill-inherit w-3.5 h-3.5" xmlns="http://www.w3.org/2000/svg" height="24px" viewBox="0 -960 960 960" width="24px" fill="#FFFFFF"><path d="M440-280h80v-240h-80v240Zm40-320q17 0 28.5-11.5T520-640q0-17-11.5-28.5T480-680q-17 0-28.5 11.5T440-640q0 17 11.5 28.5T480-600Zm0 520q-83 0-156-31.5T197-197q-54-54-85.5-127T80-480q0-83 31.5-156T197-763q54-54 127-85.5T480-880q83 0 156 31.5T763-763q54 54 85.5 127T880-480q0 83-31.5 156T763-197q-54 54-127 85.5T480-80Zm0-80q134 0 227-93t93-227q0-134-93-227t-227-93q-134 0-227 93t-93 227q0 134 93 227t227 93Zm0-320Z"/></svg>
            
            <p class="text-[11px] relative bottom-[0.45px]"> {{ 'Running Version: ' + $props.siteVersion }} </p>
        </div>
        
    </footer>
</template>


<style lang="less" scoped> 
    
</style>