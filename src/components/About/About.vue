<script setup>
let props = defineProps({
    name : String,
    button: String
})
</script>
<template>
    <div class="w-full h-screen flex  items-center justify-between px-[8%]">
        <div class="">
            <h1 class="text-5xl font-semibold mb-5 max-w-[600px] font-customFont text-[#333]">{{ name }}</h1>
            <p class="text-sm max-w-[500px] font-customFont text-[#333]">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus voluptatum deleniti expedita quaerat necessitatibus libero?</p>
            <p class="text-sm max-w-[500px] font-customFont text-[#333]">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Accusamus, esse.</p>
            <button class="py-2 px-5 bg-white text-gray-600 rounded-sm mt-10 mr-5 font-customFont text-[#333]">Iklan disini</button>
            <button class="py-2 px-5 bg-blue-600 text-white rounded-sm mt-10 font-customFont">{{ button }}</button>
        </div>
        <div class="flex">
            <div class="flex justify-between">
                <div class="w-[350px] h-[350px] rounded-full bg-blue-600 relative border">
                    <img src="../../assets/hp.png" alt="" class="absolute top-[-0px] left-[-0px] w-[500px] h-[500px]">
                </div>
            </div>
        </div>
    </div>
</template>