<template>
   <div class="text-white mb-8">
       <div class="places-input text-grey-800">
        <input type="text" class="w-full">
       </div>
       <div class="weather-container font-sans w-128 max-w-lg overflow-hidden bg-grey-900 shadow-lg mt-4">
        <div class="current-weather">
            
        </div>
       </div> <!-- end weather container -->
   </div>
</template>

<script>
    export default {
    mounted() {
    console.log('Component mounted.')
    }
}
</script>
