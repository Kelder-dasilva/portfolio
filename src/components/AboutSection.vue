<template>
    <section class="relative w-full bg-gray-900 text-white px-4 font-mono">
        <div class="flex flex-col gap-8 max-w-6xl mx-auto">
            <div class="w-full max-w-6xl bg-gray-700 rounded-2xl overflow-hidden shadow-2xl">
                <p class="prose prose-sm whitespace-pre-line text-gray-200 sm:prose-base p-6">
                    Meu nome é Kelder da Silva, sou formado em Análise e Desenvolvimento de Sistemas e atuo
                    como Desenvolvedor Full Stack.
                    Tenho experiência com <strong class="text-white">Java, Spring Boot, Vue.js e OracleSQL</strong>.
                    Atualmente, também sou gestor de equipe, coordenando tarefas, projetos e
                    treinamentos, além de integrar APIs e gerenciar infraestrutura na Oracle Cloud Infrastructure
                    (OCI).
                    <br>
                    <br>
                    Fora do trabalho gosto de fazer trilhas, jogar alguns games, estudar sobre Programação, ver eventos
                    de carros, etc. Atualmente estou me dedicando para
                    pós-graduação em <strong class="text-white">Engenharia de Software</strong> e buscando novos
                    desafios
                    para adquirir mais conhecimentos e experiência na área.
                </p>

                <ul class="grid grid-cols-1 gap-4 sm:grid-cols-2 p-8">
                    <li class="col-span-1 flex items-start gap-x-2">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" aria-hidden="true" data-slot="icon" class="size-5 text-white">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M9 6.75V15m6-6v8.25m.503 3.498 4.875-2.437c.381-.19.622-.58.622-1.006V4.82c0-.836-.88-1.38-1.628-1.006l-3.869 1.934c-.317.159-.69.159-1.006 0L9.503 3.252a1.125 1.125 0 0 0-1.006 0L3.622 5.689C3.24 5.88 3 6.27 3 6.695V19.18c0 .836.88 1.38 1.628 1.006l3.869-1.934c.317-.159.69-.159 1.006 0l4.994 2.497c.317.158.69.158 1.006 0Z">
                            </path>
                        </svg>
                        <span class="text-xs font-bold text-white sm:text-sm">Localidade:</span>
                        <span class=" text-xs text-gray-200 sm:text-sm">Brasília, DF</span>
                    </li>

                    <li class="col-span-1 flex items-start gap-x-2">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" aria-hidden="true" data-slot="icon" class="size-5 text-white">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 0 1 2.25-2.25h13.5A2.25 2.25 0 0 1 21 7.5v11.25m-18 0A2.25 2.25 0 0 0 5.25 21h13.5A2.25 2.25 0 0 0 21 18.75m-18 0v-7.5A2.25 2.25 0 0 1 5.25 9h13.5A2.25 2.25 0 0 1 21 11.25v7.5">
                            </path>
                        </svg>
                        <span class="text-xs font-bold text-white sm:text-sm">Idade:</span>
                        <span class=" text-xs text-gray-200 sm:text-sm">24</span>
                    </li>

                    <li class="col-span-1 flex items-start gap-x-2">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" aria-hidden="true" data-slot="icon" class="size-5 text-white">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M3 3v1.5M3 21v-6m0 0 2.77-.693a9 9 0 0 1 6.208.682l.108.054a9 9 0 0 0 6.086.71l3.114-.732a48.524 48.524 0 0 1-.005-10.499l-3.11.732a9 9 0 0 1-6.085-.711l-.108-.054a9 9 0 0 0-6.208-.682L3 4.5M3 15V4.5">
                            </path>
                        </svg>
                        <span class="text-xs font-bold text-white sm:text-sm">Nacionalidade:</span>
                        <span class=" text-xs text-gray-200 sm:text-sm">Brasileiro</span>
                    </li>

                    <li class="col-span-1 flex items-start gap-x-2">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" aria-hidden="true" data-slot="icon" class="size-5 text-white">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M9.813 15.904 9 18.75l-.813-2.846a4.5 4.5 0 0 0-3.09-3.09L2.25 12l2.846-.813a4.5 4.5 0 0 0 3.09-3.09L9 5.25l.813 2.846a4.5 4.5 0 0 0 3.09 3.09L15.75 12l-2.846.813a4.5 4.5 0 0 0-3.09 3.09ZM18.259 8.715 18 9.75l-.259-1.035a3.375 3.375 0 0 0-2.455-2.456L14.25 6l1.036-.259a3.375 3.375 0 0 0 2.455-2.456L18 2.25l.259 1.035a3.375 3.375 0 0 0 2.456 2.456L21.75 6l-1.035.259a3.375 3.375 0 0 0-2.456 2.456ZM16.894 20.567 16.5 21.75l-.394-1.183a2.25 2.25 0 0 0-1.423-1.423L13.5 18.75l1.183-.394a2.25 2.25 0 0 0 1.423-1.423l.394-1.183.394 1.183a2.25 2.25 0 0 0 1.423 1.423l1.183.394-1.183.394a2.25 2.25 0 0 0-1.423 1.423Z">
                            </path>
                        </svg>
                        <span class="text-xs font-bold text-white sm:text-sm">Interesses:</span>
                        <span class=" text-xs text-gray-200 sm:text-sm">Games, Carros, Séries</span>
                    </li>

                    <li class="col-span-1 flex items-start gap-x-2">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" aria-hidden="true" data-slot="icon" class="size-5 text-white">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M4.26 10.147a60.438 60.438 0 0 0-.491 6.347A48.62 48.62 0 0 1 12 20.904a48.62 48.62 0 0 1 8.232-4.41 60.46 60.46 0 0 0-.491-6.347m-15.482 0a50.636 50.636 0 0 0-2.658-.813A59.906 59.906 0 0 1 12 3.493a59.903 59.903 0 0 1 10.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.717 50.717 0 0 1 12 13.489a50.702 50.702 0 0 1 7.74-3.342M6.75 15a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5Zm0 0v-3.675A55.378 55.378 0 0 1 12 8.443m-7.007 11.55A5.981 5.981 0 0 0 6.75 15.75v-1.5">
                            </path>
                        </svg>
                        <span class="text-xs font-bold text-white sm:text-sm">Ensino:</span>
                        <span class=" text-xs text-gray-200 sm:text-sm">Superior em Análise e Des. de Sistemas</span>
                    </li>

                    <li class="col-span-1 flex items-start gap-x-2">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" aria-hidden="true" data-slot="icon" class="size-5 text-white">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M2.25 21h19.5m-18-18v18m10.5-18v18m6-13.5V21M6.75 6.75h.75m-.75 3h.75m-.75 3h.75m3-6h.75m-.75 3h.75m-.75 3h.75M6.75 21v-3.375c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21M3 3h12m-.75 4.5H21m-3.75 3.75h.008v.008h-.008v-.008Zm0 3h.008v.008h-.008v-.008Zm0 3h.008v.008h-.008v-.008Z">
                            </path>
                        </svg>
                        <span class="text-xs font-bold text-white sm:text-sm">Trabalho:</span>
                        <span class=" text-xs text-gray-200 sm:text-sm">Lake Side Apart</span>
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'AboutSection'
}
</script>