<template>
  <div class="bg-white pt-12 sm:pt-16">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="max-w-4xl mx-auto text-center">
        <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
          {{ getRevName() }}, c'est quoi ?
        </h2>
        <p class="mt-3 text-xl text-gray-500 sm:mt-4">
          C'est le nom donné au projet qui a pour objectif de suivre le développement des infrastructures dédiées au vélo sur la métropole de Saint-Étienne et ses environs. 
          
          Ce site permet de visualiser l’état des lieux des aménagements existants, d’analyser les linéaires réalisés et de mesurer l’évolution du réseau cyclable jusqu’à 2026 et 2030, dans le cadre du plan vélo. 
          
          Grâce à cet outil, chaque citoyens peuvent accéder à des données actualisées, cartographiées et détaillées sur les pistes cyclables, bandes cyclables, voies vertes et autres infrastructures en faveur de la mobilité douce.<br>
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
                  15
                </dd>
              </div>
              <div class="flex flex-col border-t border-b border-gray-100 p-6 text-center sm:border-0 sm:border-l sm:border-r">
                <dt class="order-2 mt-2 text-lg leading-6 font-medium text-gray-500">
                  Distance
                </dt>
                <dd class="order-1 text-5xl font-extrabold text-lvv-blue-600">
                  160 km
                </dd>
              </div>
              <div class="flex flex-col border-t border-gray-100 p-6 text-center sm:border-0 sm:border-l">
                <dt class="order-2 mt-2 text-lg leading-6 font-medium text-gray-500">
                  Budget
                </dt>
                <dd class="order-1 text-5xl font-extrabold text-lvv-blue-600">
                  31M€
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
