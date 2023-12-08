<script setup>
import { ref, onMounted } from "vue";
import axios from "axios";

const user = ref();
onMounted(async ()=> {
    const data = await axios.post("/api/user");
    console.log(data);
});
</script>
<template>

</template>