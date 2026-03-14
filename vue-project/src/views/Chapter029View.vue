<template>
    <CoverTitle />
    <div class="h-32"></div>
    <div class="h-32"></div>
    <div class="text-black/80">
        XXIX
    </div>
    <div class="border-b-4 border-double">
    </div>
    <div class="h-16"></div>
    <div class="grid grid-cols-1 gap-8">
        <Chapter029 />
    </div>
    <div class="h-64"></div>
    <RouterLink to="/chapter030">
        <div class="p-8 m-8 border-2 rounded font-bold shadow text-center">
            <div class="text-lime-900">
                XXX
            </div>
        </div>
    </RouterLink>
</template>

<script setup>
import Chapter029 from '@/components/chapters/Chapter029.vue';
import CoverTitle from '@/components/CoverTitle.vue';

</script>