<template>
  <div
    class="flex min-h-screen w-screen justify-center bg-striped-background bg-neutral-950 bg-cover bg-no-repeat p-0 sm:p-6">
    <div
      class="flex min-h-full w-full max-w-screen-xl grow flex-col items-start overflow-hidden border border-stone-900 bg-gray-900 shadow-strong sm:rounded-3xl animate-page-in">

      <div class="flex w-full items-center justify-between p-4 md:p-8">
        <a class="inline-flex items-center rounded-md text-xl text-white focus:outline-none focus:ring-2 focus:ring-green-600 sm:text-3xl"
          href="/">
          <span class="mr-2 font-brand-primary">Kelder</span>
          <span class="font-brand-primary font-bold">da Silva</span>
        </a>
      </div>

      <div class="w-full grow pb-6 ">
        <section class="py-6" id="hero">
          <HeroSection></HeroSection>
        </section>

        <section class="py-6" id="about">
          <div class="px-8">
            <h2 class="mb-4 font-brand-primary text-2xl font-extrabold tracking-tight text-stone-200 sm:text-3xl"
              style="text-shadow: rgba(0, 0, 0, 0.5) 10px 10px 10px, rgba(0, 0, 0, 0.4) 20px 20px 20px, rgba(0, 0, 0, 0.1) 30px 30px 30px;">
              <span class="font-brand-primary text-green-700">Abo</span>ut me
            </h2>
          </div>

          <AboutSection></AboutSection>
        </section>

        <section class="py-6" id="techStack">
          <div class="px-8">
            <h2 class="mb-4 font-brand-primary text-2xl font-extrabold tracking-tight text-stone-200 sm:text-3xl"
              style="text-shadow: rgba(0, 0, 0, 0.5) 10px 10px 10px, rgba(0, 0, 0, 0.4) 20px 20px 20px, rgba(0, 0, 0, 0.1) 30px 30px 30px;">
              <span class="font-brand-primary text-green-700">Tec</span>h stack
            </h2>
          </div>

          <TechStackSection></TechStackSection>
        </section>

        <section class="py-6" id="work">
          <div class="px-8">
            <h2 class="mb-4 font-brand-primary text-2xl font-extrabold tracking-tight text-stone-200 sm:text-3xl"
              style="text-shadow: rgba(0, 0, 0, 0.5) 10px 10px 10px, rgba(0, 0, 0, 0.4) 20px 20px 20px, rgba(0, 0, 0, 0.1) 30px 30px 30px;">
              <span class="font-brand-primary text-green-700">Wor</span>k
            </h2>
          </div>

          <WorkSection></WorkSection>
        </section>

        <section class="py-6 bg-striped-background bg-neutral-800 bg-cover bg-no-repeat" id="education">
          <EducationAndExperienceSection></EducationAndExperienceSection>
        </section>

        <section class="py-6 bg-striped-background bg-neutral-800 bg-cover bg-no-repeat" id="contact">
          <div class="px-8">
            <h2 class="mb-4 font-brand-primary text-2xl font-extrabold tracking-tight text-stone-200 sm:text-3xl"
              style="text-shadow: rgba(0, 0, 0, 0.5) 10px 10px 10px, rgba(0, 0, 0, 0.4) 20px 20px 20px, rgba(0, 0, 0, 0.1) 30px 30px 30px;">
              <span class="font-brand-primary text-green-700">Con</span>tato
            </h2>
          </div>

          <ContactSection></ContactSection>
        </section>
      </div>
    </div>
  </div>
</template>

<script>
import HeroSection from './components/HeroSection.vue';
import AboutSection from './components/AboutSection.vue';
import TechStackSection from './components/TechStackSection.vue';
import WorkSection from './components/WorkSection.vue';
import EducationAndExperienceSection from './components/EducationAndExperienceSection.vue';
import ContactSection from './components/ContactSection.vue';

export default {
  components: {
    HeroSection, AboutSection, TechStackSection, WorkSection, EducationAndExperienceSection, ContactSection
  }
}
</script>