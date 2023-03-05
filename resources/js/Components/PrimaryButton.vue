<script setup>
defineProps({
    type: {
        type: String,
        default: 'submit',
    },
});
</script>

<template>
    <button
        :type="type"
        class="bg-[#0095F6] hover:bg-[#2150fa] w-full rounded-lg p-1.5 text-white text-lg font-extrabold"
    >
        <slot />
    </button>
</template>
