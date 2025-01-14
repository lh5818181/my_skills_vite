<template>
  <div class="icons">
    <div class="icon-container" v-for="icon in icons" :key="icon.name">
      <a :href="icon.link" target="_blank" rel="noopener noreferrer">
        <button class="icon-button">
          <img :src="icon.src" :alt="icon.name" />
        </button>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      icons: [
        { name: 'WhatsApp', src: '/icons/Whatsapp.png', link: 'https://wa.me/5581999429143' },
        { name: 'Instagram', src: '/icons/instagram.png', link: 'https://www.instagram.com/devriqueoliver/?next=%2F' },
        { name: 'Gmail', src: '/icons/Gmail.png', link: 'mailto:lh5818181@gmail.com' },
        { name: 'LinkedIn', src: '/icons/Linkedin.png', link: 'https://www.linkedin.com/in/luis-henrique-76245231a/' },
        { name: 'GitHub', src: '/icons/Github.png', link: 'https://github.com/lh5818181' }
      ]
    };
  }
};
</script>

<style>
.icons {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 10px;
}
.icon-container {
  margin: 5px;
}
.icon-button {
  background-color: transparent;
  border: none;
  cursor: pointer;
}
.icon-button img {
  width: 60px;
  height: 60px;
}

/* Responsividade */
@media (max-width: 1024px) {
  .icons {
    flex-wrap: wrap;
    justify-content: center;
  }
  .icon-button img {
    width: 40px;
    height: 40px;
  }
}
</style>
