<template>
  <div class="min-h-80 bg-[#272727] py-10 flex justify-between w-full">
    <!-- <div class="flex justify-between gap-6 items-center mx-auto">
      <div v-for="(image, index) in images" :key="index">
        <img
          :src="image.url"
          alt="Carousel Image"
          :class="image.class"
          class=""
        />
      </div>
    </div> -->
    <div class="flex justify-between scrollLeft gap-16">
      <img
        src="../assets/Thumb1.jpg"
        class="rounded-xl object-cover transform thumbnail -rotate-3"
      />
      <img
        src="../assets/Thumb4.jpg"
        class="rounded-xl object-cover transform thumbnail rotate-3"
      />
      <img
        src="../assets/Thumb5.jpg"
        class="rounded-xl object-cover transform thumbnail -rotate-3"
      />
      <img
        src="../assets/Thumb2.jpg"
        class="rounded-xl object-cover transform thumbnail rotate-3"
      />
      <img
        src="../assets/Thumb3.jpg"
        class="rounded-xl object-cover transform thumbnail -rotate-3"
      />
      <img
        src="../assets/Thumb6.jpg"
        class="rounded-xl object-cover transform thumbnail rotate-3"
      />
    </div>
  </div>
</template>

<style scoped>
.thumbnail {
  width: 368px;
  height: auto;
}
.scrollLeft {
  display: flex;
  align-items: center;
  overflow-x: auto;
  overflow-y: none;
}
.scrollLeft::-webkit-scrollbar {
  display: none;
}
</style>
