<template>
  <div
    id="home"
    class="min-h-screen px-28 w-full text-white bg-gray-100 flex items-center justify-center"
  >
    <div class="flex justify-between gap-0 w-full items-center mx-16">
      <div class="text-2xl mb-4 w-full flex flex-col gap-6">
        <h1 class="text-5xl font-bold text-left">Hi! I’m Jeric Eduarte</h1>
        <p class="text-xl font-normal text-left">
          Web and Mobile UI UX Designer
        </p>
        <div class="flex flex-row gap-10 font-normal text-sm mt-4">
          <a href="https://www.figma.com/@jericeduarte" target="_blank"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon-tabler icon-tabler-brand-figma"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="#ffffff"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" fill="none" />
              <path d="M15 12m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0" />
              <path
                d="M6 3m0 3a3 3 0 0 1 3 -3h6a3 3 0 0 1 3 3v0a3 3 0 0 1 -3 3h-6a3 3 0 0 1 -3 -3z"
              />
              <path d="M9 9a3 3 0 0 0 0 6h3m-3 0a3 3 0 1 0 3 3v-15" /></svg
          ></a>
          <a href="https://www.behance.net/jjericeduarte" target="_blank"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon-tabler icon-tabler-brand-behance"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="#ffffff"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" fill="none" />
              <path d="M3 18v-12h4.5a3 3 0 0 1 0 6a3 3 0 0 1 0 6h-4.5" />
              <path d="M3 12l4.5 0" />
              <path d="M14 13h7a3.5 3.5 0 0 0 -7 0v2a3.5 3.5 0 0 0 6.64 1" />
              <path d="M16 6l3 0" /></svg
          ></a>
          <a href="https://www.instagram.com/jeric.eduarte/" target="_blank"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon-tabler icon-tabler-brand-instagram"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="#ffffff"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" fill="none" />
              <path
                d="M4 4m0 4a4 4 0 0 1 4 -4h8a4 4 0 0 1 4 4v8a4 4 0 0 1 -4 4h-8a4 4 0 0 1 -4 -4z"
              />
              <path d="M12 12m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0" />
              <path d="M16.5 7.5l0 .01" /></svg
          ></a>
          <a href="https://www.facebook.com/Jeric.Eduarte.JE" target="_blank"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon-tabler icon-tabler-brand-facebook"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="#ffffff"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" fill="none" />
              <path
                d="M7 10v4h3v7h4v-7h3l1 -4h-4v-2a1 1 0 0 1 1 -1h3v-4h-3a5 5 0 0 0 -5 5v2h-3"
              /></svg
          ></a>
        </div>
        <div class="flex flex-row gap-6 font-bold text-base mt-4">
          <a
            href="https://drive.google.com/file/d/1XRyMRgpKMxS3rSX1LFjMFW_05kcIwnwe/view?usp=sharing"
            target="_blank"
          >
            <button class="bg-mainGreen py-2 px-5 rounded-full text-white">
              Download CV
            </button>
          </a>
          <a
            href="https://drive.google.com/file/d/1XRyMRgpKMxS3rSX1LFjMFW_05kcIwnwe/view?usp=sharing"
            target="_blank"
          >
            <button
              class="border border-mainGreen text-mainGreen hover:bg-mainGreen hover:text-white py-2 px-10 rounded-full"
            >
              Hire me
            </button>
          </a>
        </div>
      </div>
      <div class="flex w-full justify-end mr-14">
        <img
          src="../assets/user1.png"
          class="user rounded-full border-8 border-[#252529]"
        />
      </div>
    </div>
  </div>
</template>

<script>
import About from "@/components/About.vue";

export default {
  name: "HomeView",
  components: {
    About,
  },
};
</script>

<style scoped>
.user {
  width: 358px;
  height: 351px;
}

.greetings {
  line-height: 56.35px;
  font-weight: 700;
}

.profession {
  font-size: 16px;
  font-weight: 400;
  line-height: 18.78px;
}

#home {
  background-image: url("../assets/bg1.png");
  background-size: cover;
  background-repeat: no-repeat;
}
</style>
