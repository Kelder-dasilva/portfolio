<template>
    <section class="relative w-full bg-gray-900 text-white overflow-hidden px-4 font-mono">
        <div class="flex flex-col md:flex-row items-center justify-center gap-8 max-w-6xl mx-auto">

            <div class="max-w-xl h-120 bg-gray-900 rounded-2xl overflow-hidden shadow-2xl">
                <img src="https://i.ytimg.com/vi/Cqv67O9toHo/hq720.jpg?sqp=-oaymwEhCK4FEIIDSFryq4qpAxMIARUAAAAAGAElAADIQj0AgKJD&rs=AOn4CLAJ_hVwPUGuazLSw2gt-h9eGnDidg"
                    alt="Foto de perfil" class="w-full h-full object-cover" />
            </div>

            <div class="bg-gray-700 p-8 rounded-2xl shadow-2xl md:ml-[-60px] max-w-md w-full md:mt-0">
                <div class="mb-2 flex w-full flex-wrap items-center gap-y-2">
                    <h1 class="mr-4 w-max text-3xl font-black text-white">Kelder da Silva</h1>
                    <div class="flex gap-x-6 sm:gap-x-3">
                        <a aria-label="Github"
                            class="-m-2 rounded-md p-2 text-gray-200 hover:text-white focus:outline-none focus:ring-2 focus:ring-white sm:-m-1.5 sm:p-1.5"
                            href="https://github.com/Kelder-dasilva">
                            <svg class="size-5 align-baseline" fill="currentColor" viewBox="0 0 128 128" width="128"
                                xmlns="http://www.w3.org/2000/svg">
                                <path clip-rule="evenodd"
                                    d="M64 5.103c-33.347 0-60.388 27.035-60.388 60.388 0 26.682 17.303 49.317 41.297 57.303 3.017.56 4.125-1.31 4.125-2.905 0-1.44-.056-6.197-.082-11.243-16.8 3.653-20.345-7.125-20.345-7.125-2.747-6.98-6.705-8.836-6.705-8.836-5.48-3.748.413-3.67.413-3.67 6.063.425 9.257 6.223 9.257 6.223 5.386 9.23 14.127 6.562 17.573 5.02.542-3.903 2.107-6.568 3.834-8.076-13.413-1.525-27.514-6.704-27.514-29.843 0-6.593 2.36-11.98 6.223-16.21-.628-1.52-2.695-7.662.584-15.98 0 0 5.07-1.623 16.61 6.19C53.7 35 58.867 34.327 64 34.304c5.13.023 10.3.694 15.127 2.033 11.526-7.813 16.59-6.19 16.59-6.19 3.287 8.317 1.22 14.46.593 15.98 3.872 4.23 6.215 9.617 6.215 16.21 0 23.194-14.127 28.3-27.574 29.796 2.167 1.874 4.097 5.55 4.097 11.183 0 8.08-.07 14.583-.07 16.572 0 1.607 1.088 3.49 4.148 2.897 23.98-7.994 41.263-30.622 41.263-57.294C124.388 32.14 97.35 5.104 64 5.104z"
                                    fill-rule="evenodd">
                                </path>
                            </svg>
                        </a>
                        <a aria-label="LinkedIn"
                            class="-m-2 rounded-md p-2 text-gray-200 hover:text-white focus:outline-none focus:ring-2 focus:ring-white sm:-m-1.5 sm:p-1.5"
                            href="https://www.linkedin.com/in/kelder-dasilva/">
                            <svg class="size-5 align-baseline" fill="currentColor" viewBox="0 0 48 48" width="118"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M44.4469 0H3.54375C1.58437 0 0 1.54688 0 3.45938V44.5312C0 46.4437 1.58437 48 3.54375 48H44.4469C46.4062 48 48 46.4438 48 44.5406V3.45938C48 1.54688 46.4062 0 44.4469 0ZM14.2406 40.9031H7.11563V17.9906H14.2406V40.9031ZM10.6781 14.8688C8.39062 14.8688 6.54375 13.0219 6.54375 10.7437C6.54375 8.46562 8.39062 6.61875 10.6781 6.61875C12.9563 6.61875 14.8031 8.46562 14.8031 10.7437C14.8031 13.0125 12.9563 14.8688 10.6781 14.8688ZM40.9031 40.9031H33.7875V29.7656C33.7875 27.1125 33.7406 23.6906 30.0844 23.6906C26.3812 23.6906 25.8187 26.5875 25.8187 29.5781V40.9031H18.7125V17.9906H25.5375V21.1219H25.6312C26.5781 19.3219 28.9031 17.4188 32.3625 17.4188C39.5719 17.4188 40.9031 22.1625 40.9031 28.3313V40.9031Z"
                                    fill="currentColor">
                                </path>
                            </svg>
                        </a>
                    </div>
                </div>

                <p class="prose mb-4 text-gray-200">
                    Eu sou um <strong class="text-white">Desenvolvedor Full Stack</strong>,
                    atualmente trabalho no <strong class="text-white">Lake Side Apart</strong> atuando como gestor de
                    equipe, coordenando tarefas, projetos e treinamentos,
                    além de integrar APIs e gerenciar infraestrutura na <strong class="text-white">Oracle Cloud
                        Infrastructure (OCI) </strong>.
                </p>

                <p class="prose mb-4 text-gray-200">No meu tempo livre, gosto de jogar <strong
                        class="text-white">RPGs</strong>,
                    me atualizar sobre a área de <strong class="text-white">Programação</strong>, ler alguns livros,
                    etc.
                </p>

                <div class="flex space-x-2">
                    <a class="flex rounded-full border-2  bg-stone-900 px-4 py-2 text-sm font-medium text-white shadow-md outline-none hover:bg-stone-800 focus:ring-2  focus:ring-offset-2 focus:ring-offset-stone-800 border-green-800 focus:ring-green-800"
                        href="/assets/Curriculo.pdf" download="Curriculo-Kelder.pdf">
                        Currículo
                    </a>

                    <a class="flex rounded-full border-2  bg-stone-900 px-4 py-2 text-sm font-medium text-white shadow-md outline-none hover:bg-stone-800 focus:ring-2  focus:ring-offset-2 focus:ring-offset-stone-800 border-stone-300 focus:ring-stone-300"
                        href="#contact">
                        Contato
                    </a>
                </div>
            </div>

        </div>
    </section>
</template>


<script>
export default {
    name: 'HeroSection'
}
</script>

<style scoped></style>