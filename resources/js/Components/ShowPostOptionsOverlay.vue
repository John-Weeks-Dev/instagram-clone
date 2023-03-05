<script setup>
import { toRefs } from 'vue'

defineEmits(['close', 'deleteSelected'])
const props = defineProps({ deleteType: String, id: Number })

const { deleteType, id } = toRefs(props)
</script>

<template>
    <div
        id="ShowPostOptionsOverlay"
        class="fixed flex items-center z-50 top-0 left-0 w-full h-screen bg-[#000000] bg-opacity-60 p-3"
    >
        <div class="max-w-sm w-full mx-auto mt-10 bg-white rounded-xl text-center">
            <button
                @click="$emit('deleteSelected', { deleteType, id });"
                class="font-extrabold w-full text-red-600 p-3 text-lg border-b border-b-gray-300 cursor-pointer"
            >
                Delete {{ deleteType }}
            </button>
            <div class="p-3 text-lg cursor-pointer" @click="$emit('close')">Cancel</div>
        </div>
    </div>
</template>
