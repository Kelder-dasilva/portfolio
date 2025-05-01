<template>
  <section class="relative w-full bg-gray-900 text-white overflow-hidden px-4 font-mono bg-striped-background bg-neutral-800 bg-gray-800 bg-cover bg-no-repeat">
    <div class="grid grid-cols-1 gap-4 md:grid-cols-2 md:gap-8 gap-8 max-w-6xl mx-auto">

      <div class="col-span-1 bg-gray-900 overflow-hidden bg-striped-background bg-neutral-800 bg-gray-800 bg-cover bg-no-repeat">
        <p class="text-gray-300">
          Deseja fazer algum projeto? Dúvidas sobre algo que desenvolvi? Me manda por e-mail
          ou use o formulário
          se desejar entrar em contato comigo.
        </p>

        <ul class="grid grid-cols-1 gap-4 lg:grid-cols-2 py-8">
          <li class="col-span-2 flex items-start gap-x-2">
            <a href="mailto:kelderdasilva10@gmail.com">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" aria-hidden="true" data-slot="icon" class="size-4 shrink-0 text-white sm:size-5">
                <path stroke-linecap="round" stroke-linejoin="round"
                  d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75">
                </path>
              </svg> kelderdasilva10@gmail.com
            </a>
          </li>

          <li class="col-span-1 flex items-start gap-x-2">
            <a aria-label="Github"
              class="-m-2 rounded-md p-2 text-gray-200 hover:text-white focus:outline-none focus:ring-2 focus:ring-white sm:-m-1.5 sm:p-1.5"
              href="https://github.com/Kelder-dasilva">
              <svg class="size-5 align-baseline" fill="currentColor" viewBox="0 0 128 128" width="128"
                xmlns="http://www.w3.org/2000/svg">
                <path clip-rule="evenodd"
                  d="M64 5.103c-33.347 0-60.388 27.035-60.388 60.388 0 26.682 17.303 49.317 41.297 57.303 3.017.56 4.125-1.31 4.125-2.905 0-1.44-.056-6.197-.082-11.243-16.8 3.653-20.345-7.125-20.345-7.125-2.747-6.98-6.705-8.836-6.705-8.836-5.48-3.748.413-3.67.413-3.67 6.063.425 9.257 6.223 9.257 6.223 5.386 9.23 14.127 6.562 17.573 5.02.542-3.903 2.107-6.568 3.834-8.076-13.413-1.525-27.514-6.704-27.514-29.843 0-6.593 2.36-11.98 6.223-16.21-.628-1.52-2.695-7.662.584-15.98 0 0 5.07-1.623 16.61 6.19C53.7 35 58.867 34.327 64 34.304c5.13.023 10.3.694 15.127 2.033 11.526-7.813 16.59-6.19 16.59-6.19 3.287 8.317 1.22 14.46.593 15.98 3.872 4.23 6.215 9.617 6.215 16.21 0 23.194-14.127 28.3-27.574 29.796 2.167 1.874 4.097 5.55 4.097 11.183 0 8.08-.07 14.583-.07 16.572 0 1.607 1.088 3.49 4.148 2.897 23.98-7.994 41.263-30.622 41.263-57.294C124.388 32.14 97.35 5.104 64 5.104z"
                  fill-rule="evenodd">
                </path>
              </svg> Kelder-dasilva
            </a>
          </li>
        </ul>
      </div>

      <div class="col-span-1 bg-gray-900 rounded-2xl overflow-hidden shadow-2xl bg-striped-background bg-neutral-800 bg-gray-800 bg-cover bg-no-repeat">
        <form class="grid min-h-[320px] grid-cols-1 gap-y-4" method="POST" @submit="sendEmail">
          <label class="sr-only" for="name">Nome</label>
          <div class="relative mt-1 rounded-md">
            <input
              class="block w-full rounded-md border-none bg-gray-700 px-3 py-2 text-white shadow-xl shadow-black/30 focus:outline-none disabled:cursor-not-allowed disabled:opacity-70 sm:text-sm placeholder-gray-400 focus:border-gray-500 focus:ring-gray-500"
              name="name" placeholder="Nome" required="" type="text">
          </div>
          <label class="sr-only" for="email">E-mail</label>
          <div class="relative mt-1 rounded-md">
            <input
              class="block w-full rounded-md border-none bg-gray-700 px-3 py-2 text-white shadow-xl shadow-black/30 focus:outline-none disabled:cursor-not-allowed disabled:opacity-70 sm:text-sm placeholder-gray-400 focus:border-gray-500 focus:ring-gray-500"
              autocomplete="email" name="email" placeholder="Email" required="" type="email">
          </div>
          <label class="sr-only" for="message">Mensagem</label>
          <div class="relative mt-1 rounded-md">
            <textarea
              class="block w-full rounded-md border-none bg-gray-700 px-3 py-2 text-white shadow-xl shadow-black/30 focus:outline-none disabled:cursor-not-allowed disabled:opacity-70 sm:text-sm placeholder-gray-400 focus:border-gray-500 focus:ring-gray-500"
              maxlength="250" name="message" placeholder="Mensagem" required rows="6" type="text"></textarea>
          </div>
          <button aria-label="Submit contact form"
            class="w-max rounded-full border-2 border-green-700 bg-gray-900 px-4 py-2 text-sm font-medium text-white shadow-md outline-none hover:bg-gray-900 focus:ring-2 focus:ring-green-800 focus:ring-offset-2 focus:ring-offset-gray-950"
            type="submit">
            Enviar Mensagem
          </button>
        </form>
      </div>

    </div>
  </section>
</template>

<script>
import emailjs from 'emailjs-com';

export default {
  name: "ContactSecion",
  created() { },
  data() {
    return {};
  },
  methods: {
    async sendEmail(e) {
      console.log(e.target);
      
      e.preventDefault();
      await emailjs.sendForm('service_b5n2q2y', 'template_18ds6o7', e.target, 'fLQL4J1_WW362RbY1')
        .then((result) => {
          console.log('Mensagem enviada!', result.text);
          e.target.reset(); // opcional: limpa o form
          alert('Mensagem enviada com sucesso!');
        }, (error) => {
          console.log('Erro ao enviar', error.text);
        });
    }
  },
};
</script>