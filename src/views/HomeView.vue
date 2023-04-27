<script setup>
import HomeCard from '@/components/HomeCard.vue';

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

    <div class="flex items-center">
       <HomeCard image="https://picsum.photos/id/30/300/300" title="Here is the title" subTitle="Here is the subtitle"/>
       <HomeCard image="https://picsum.photos/id/45/300/300" title="Here is the title" subTitle="Here is the subtitle"/>
       <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Here is the title" subTitle="Here is the subtitle"/>
       <HomeCard class="lg:block hidden"  image="https://picsum.photos/id/67/300/300" title="Here is the title" subTitle="Here is the subtitle"/>
       <HomeCard class="xl:block hidden"  image="https://picsum.photos/id/100/300/300" title="Here is the title" subTitle="Here is the subtitle"/>

    </div>
  </div>

  <div class="p-8">
    <button
    type="button"
    class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
        Recommended Radio
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
       <HomeCard image="https://picsum.photos/id/30/300/300" title="Here is the title" subTitle="Here is the subtitle"/>
       <HomeCard image="https://picsum.photos/id/45/300/300" title="Here is the title" subTitle="Here is the subtitle"/>
       <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Here is the title" subTitle="Here is the subtitle"/>
       <HomeCard class="lg:block hidden"  image="https://picsum.photos/id/67/300/300" title="Here is the title" subTitle="Here is the subtitle"/>
       <HomeCard class="xl:block hidden"  image="https://picsum.photos/id/100/300/300" title="Here is the title" subTitle="Here is the subtitle"/>

    </div>
  </div>

  <div class="p-8">
    <button
    type="button"
    class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
        Recommended songs
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
       <HomeCard image="https://picsum.photos/id/30/300/300" title="Here is the title" subTitle="Here is the subtitle"/>
       <HomeCard image="https://picsum.photos/id/45/300/300" title="Here is the title" subTitle="Here is the subtitle"/>
       <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Here is the title" subTitle="Here is the subtitle"/>
       <HomeCard class="lg:block hidden"  image="https://picsum.photos/id/67/300/300" title="Here is the title" subTitle="Here is the subtitle"/>
       <HomeCard class="xl:block hidden"  image="https://picsum.photos/id/100/300/300" title="Here is the title" subTitle="Here is the subtitle"/>

    </div>
  </div>
</template>
