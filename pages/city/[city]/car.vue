<script setup lang="ts">
import { NuxtPage } from '#components';
const { toTitleCase } = useUtilities();
const route = useRoute();

definePageMeta({
    layout: "custom"
})

useHead({
    title: `${route.params.make ? toTitleCase(route.params.make) : 'Cars'} in ${toTitleCase(route.params.city)}`,
})
</script>

<template>
    <div>

        <div class="mt-32 flex">
            <carSideBar />
            <NuxtPage />
        </div>
    </div>
</template>