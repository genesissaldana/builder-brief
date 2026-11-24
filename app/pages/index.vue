<script setup lang="ts">
const sections = [
  { number: 1, title: 'Información General', subtitle: 'campos requeridos', count: '0/8' },
  { number: 2, title: 'Problema y Contexto', subtitle: 'campos requeridos', count: '0/4' },
  { number: 3, title: 'Objetivos', subtitle: 'campos requeridos', count: '0/4' },
  { number: 4, title: 'Usuario Objetivo', subtitle: 'campos requeridos', count: '0/5' },
];
</script>

<template>
  <main class="min-h-screen bg-slate-50 text-slate-900">
    <BriefHeader />

    <section class="mx-auto grid max-w-7xl gap-6 px-6 py-6 lg:grid-cols-[1.05fr_0.95fr] lg:px-8">
      <article class="rounded-3xl border border-slate-200 bg-white shadow-sm">
        <div class="border-b border-slate-100 p-6">
          <div class="flex items-start justify-between gap-4">
            <div>
              <p class="text-xs uppercase tracking-[0.28em] text-slate-400">Completitud del Brief</p>
              <h1 class="mt-2 text-2xl font-semibold text-slate-900">Genera tu brief financiero paso a paso</h1>
            </div>
            <span class="rounded-full bg-amber-50 px-3 py-1 text-sm font-semibold text-amber-600">0%</span>
          </div>

          <div class="mt-5 space-y-2">
            <div class="h-2 w-full rounded-full bg-slate-100">
              <div class="h-2 w-0 rounded-full bg-slate-300" />
            </div>
            <div class="flex items-center justify-between text-xs text-slate-400">
              <span>0 de 46 campos completados</span>
              <span>10 requeridos pendientes</span>
            </div>
          </div>
        </div>

        <div class="divide-y divide-slate-100">
          <SectionCard
            v-for="item in sections"
            :key="item.number"
            :number="item.number"
            :title="item.title"
            :subtitle="item.subtitle"
            :count="item.count"
          />
        </div>
      </article>

      <BriefPreview />
    </section>
  </main>
</template>
