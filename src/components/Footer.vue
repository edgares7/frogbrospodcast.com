<template>
  <div
    class="footer flex md:flex-row flex-col items-center justify-between md:mx-10 my-5 py-5 md:my-6 md:py-6 md:px-10"
  >
    <div class="copyright">
      <em>Copyright &copy; {{ currentYear }} The Frog Bros. Podcast</em>
    </div>
    <div class="social md:flex md:flex-row flex-row flex">
      <a
        href="https://twitter.com/frogbrospodcast"
        class="w-6 mx-2"
        target="_blank"
      >
        <font-awesome-icon
          class="fill-current cursor-pointer text-gray-500 hover:text-gray-400"
          :icon="['fab', 'twitter']"
          size="xl"
        />
      </a>
      <a
        href="https://www.youtube.com/channel/UCJWVWIs4f4gxKP3rBfChmLQ"
        class="w-6 mx-2"
        target="_blank"
      >
        <font-awesome-icon
          class="fill-current cursor-pointer text-gray-500 hover:text-gray-400"
          :icon="['fab', 'youtube']"
          size="xl"
        />
      </a>
      <a
        href="https://www.facebook.com/FrogBrosPodcast/"
        class="w-6 mx-2"
        target="_blank"
      >
        <font-awesome-icon
          class="fill-current cursor-pointer text-gray-500 hover:text-gray-400"
          :icon="['fab', 'facebook']"
          size="xl"
        />
      </a>
      <a
        href="https://www.instagram.com/frogbrospodcast/"
        class="w-6 mx-2"
        target="_blank"
      >
        <font-awesome-icon
          class="fill-current cursor-pointer text-gray-500 hover:text-gray-400"
          :icon="['fab', 'instagram']"
          size="xl"
        />
      </a>
      <a
        href="https://www.etsy.com/shop/frogbros"
        class="w-6 mx-2"
        target="_blank"
      >
        <font-awesome-icon
          class="fill-current cursor-pointer text-gray-500 hover:text-gray-400"
          :icon="['fab', 'etsy']"
          size="xl"
        />
      </a>
      <a
        href="https://www.tiktok.com/@frogbrospodcast"
        class="w-6 mx-2"
        target="_blank"
      >
        <font-awesome-icon
          class="fill-current cursor-pointer text-gray-500 hover:text-gray-400"
          :icon="['fab', 'tiktok']"
          size="xl"
        />
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
  computed: {
    currentYear() {
      const year = new Date().getFullYear();
      return year;
    }
  }
};
</script>

<style lang="scss" scoped></style>
