<script setup>
import CategorySelect from '../components/CategorySelect.vue'
</script>
<template>
    <div class="p-8">
        <button
        type="button"
        class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Podcast to make you smarter
        </button>
    
        <div class="py-1.5"></div>
    
        <div class="grid xl:grid-cols-5 lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 gap-6">
           <CategorySelect category="Podcast" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="Live events" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="Made for you" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="New realeases" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="Rock" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="Cumbia" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="House" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="Gaming" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="Hip-Hop" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="Salsa" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="Latin" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="Pop" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="Podcast:" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="Workout" image="https://picsum.photos/id/40/300/300" />
           <CategorySelect category="Indie" image="https://picsum.photos/id/40/300/300" />

    
        </div>
      </div>
</template>


