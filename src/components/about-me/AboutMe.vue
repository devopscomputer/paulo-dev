<template>
  <BackgroundBlue class="first-bg-blue">
    <div class="about-me-text">
      <h1 class="about-me-title">Olá! Sou Paulo Silas de Campos Filho, Engenheiro de Software.</h1>
      <h2 class="about-me-subtitle">
        tenho o prazer de compartilhar minha jornada de 7 anos na área de Tecnologia da Informação.
        Ao longo da minha carreira, desenvolvi uma sólida experiência como desenvolvedor full stack, 
        trabalhando com um conjunto diverso de tecnologias modernas que me permitiram construir soluções robustas e escaláveis. 
        Sou apaixonado por criar aplicações que vão além das expectativas, transformando ideias em realidade através de código eficiente e design funcional.
      </h2>
    </div>
  </BackgroundBlue>
</template>

<script>
import BackgroundBlue from "../shared/BackgroundBlue.vue";

export default {
  components: {
    BackgroundBlue,
  },
};
</script>

<style scoped>
.first-bg-blue {
  @apply mt-6;
}

.about-me-text {
  @apply text-gray-blue mt-36
  w-[18.75rem]
  2xs:w-[21.8rem]
  xs:w-[22.5rem]
  sm:w-[30rem]
  md:w-[40rem]
  lg:w-[55rem]
  xl:w-[60rem]
  2xl:w-[65rem];
}
.about-me-title {
  @apply text-center font-bold tracking-wide
  text-[0.8rem]
  2xs:text-[0.85rem]
  xs:text-[0.9rem]
  sm:text-[1.1rem]
  md:text-[1.3rem] md:tracking-wider
  lg:text-[1.4rem]
  xl:text-[1.5rem] xl:tracking-widest
  2xl:text-[1.6rem];
}

.about-me-subtitle {
  @apply text-justify leading-snug tracking-normal 
  text-xs py-1
  2xs:text-[0.8rem]
  xs:text-[0.83rem]
  sm:text-[0.9rem]
  md:text-[1.1rem] md:py-2 md:tracking-wider md:leading-normal
  lg:text-[1.2rem] lg:py-3
  xl:text-[1.3rem] xl:py-4 xl:tracking-wider xl:leading-relaxed
  2xl:text-[1.4rem] 2xl:py-6;
}
</style>
