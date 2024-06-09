<template>
    <div class="p-2 justify-between flex">
        <div class="flex">
            <img src="https://i.pinimg.com/originals/8a/b6/d7/8ab6d70f03197bf092b242083cc1c4d6.png" alt="Logo" class="h-12"/>
            <hi class="mt-2 font-sans font-black p-1">Açai no Pote</hi>
        </div>
        <div>
            Home | About | Contact
        </div>
    </div>
</template>

<script>
export default {
    name: 'Header',
    mounted() {
        document.title = 'Header';
    }
}
</script>