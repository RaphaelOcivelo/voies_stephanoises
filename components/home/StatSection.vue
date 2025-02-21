<template>
  <div class="bg-white pt-12 sm:pt-16">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="max-w-4xl mx-auto text-center">
        <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
          Les {{ getRevName() }}, c'est quoi ?
        </h2>
        <p class="mt-3 text-xl text-gray-500 sm:mt-4">
         Bienvenue sur l'Observatoire des Aménagements Cyclables!

Cet espace a été conçu pour vous offrir une vue d'ensemble complète des infrastructures cyclables sur notre territoire. Que vous soyez cycliste régulier, amateur de balades ou professionnel, notre objectif est de vous fournir des informations précises, actualisées et facilement accessibles sur l’état des aménagements, leur sécurité et leur évolution.
À travers cet observatoire, nous souhaitons faire un état des lieux des aménagements sur la pratie Sud Loire <br>

Pour Saint etienne Métropole
        </p>
      </div>
    </div>
    <div class="mt-10 bg-white">
      <div class="relative">
        <div class="absolute inset-0 h-1/2 bg-white" />
        <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="max-w-4xl mx-auto">
            <dl class="rounded-lg bg-white shadow-lg sm:grid sm:grid-cols-3">
              <div class="flex flex-col border-b border-gray-100 p-6 text-center sm:border-0 sm:border-r">
                <dt class="order-2 mt-2 text-lg leading-6 font-medium text-gray-500">
                  Lignes
                </dt>
                <dd class="order-1 text-5xl font-extrabold text-lvv-blue-600">
                  12
                </dd>
              </div>
              <div class="flex flex-col border-t border-b border-gray-100 p-6 text-center sm:border-0 sm:border-l sm:border-r">
                <dt class="order-2 mt-2 text-lg leading-6 font-medium text-gray-500">
                  Distance
                </dt>
                <dd class="order-1 text-5xl font-extrabold text-lvv-blue-600">
                  260km
                </dd>
              </div>
              <div class="flex flex-col border-t border-gray-100 p-6 text-center sm:border-0 sm:border-l">
                <dt class="order-2 mt-2 text-lg leading-6 font-medium text-gray-500">
                  Budget
                </dt>
                <dd class="order-1 text-5xl font-extrabold text-lvv-blue-600">
                  280M€
                </dd>
              </div>
            </dl>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
</p>
<p class="mt-3 text-xl text-gray-500 sm:mt-4">
         Bienvenue sur l'Observatoire des Aménagements Cyclables!<br>
      </div>
    </div>
    <div class="mt-10 bg-white">
      <div class="relative">
        <div class="absolute inset-0 h-1/2 bg-white" />
        <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="max-w-4xl mx-auto">
            <dl class="rounded-lg bg-white shadow-lg sm:grid sm:grid-cols-3">
              <div class="flex flex-col border-b border-gray-100 p-6 text-center sm:border-0 sm:border-r">
                <dt class="order-2 mt-2 text-lg leading-6 font-medium text-gray-500">
                  Lignes
                </dt>
                <dd class="order-1 text-5xl font-extrabold text-lvv-blue-600">
                  125
                </dd>
              </div>
              <div class="flex flex-col border-t border-b border-gray-100 p-6 text-center sm:border-0 sm:border-l sm:border-r">
                <dt class="order-2 mt-2 text-lg leading-6 font-medium text-gray-500">
                  Distance
                </dt>
                <dd class="order-1 text-5xl font-extrabold text-lvv-blue-600">
                  280km
                </dd>
              </div>
              <div class="flex flex-col border-t border-gray-100 p-6 text-center sm:border-0 sm:border-l">
                <dt class="order-2 mt-2 text-lg leading-6 font-medium text-gray-500">
                  Budget
                </dt>
                <dd class="order-1 text-5xl font-extrabold text-lvv-blue-600">
                  ?€
                </dd>
              </div>
            </dl>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup lang="ts">
const { getRevName } = useConfig();
</script>
