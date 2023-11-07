<script setup>
import TextInput from "@/Components/TextInput.vue";
import {useForm} from "@inertiajs/vue3";

const form = useForm({
    search: ''
})
</script>

<template>
    <div class="w-[600px] h-[80px] flex items-center">
        <TextInput model-value="" type="text"
                   class="block w-full mr-2"
                   v-model="search"
                   autocomplete
                   placeholder="Search for files and folders"/>
    </div>
</template>

<style scoped>

</style>
