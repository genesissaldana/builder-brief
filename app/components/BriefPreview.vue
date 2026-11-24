<template>
  <aside class="rounded-3xl border border-slate-200 bg-white p-6 shadow-sm">
    <div class="mb-6 flex items-center justify-between">
      <div>
        <p class="text-xs uppercase tracking-[0.24em] text-slate-400">Vista previa</p>
        <h2 class="mt-2 text-xl font-semibold text-slate-900">Brief final listo para compartir</h2>
      </div>
      <span class="rounded-full bg-emerald-50 px-3 py-1 text-xs font-semibold text-emerald-700">AI ready</span>
    </div>

    <div class="space-y-4">
      <article class="rounded-2xl border border-slate-100 bg-slate-50 p-4">
        <p class="text-xs uppercase tracking-[0.24em] text-slate-400">Resumen ejecutivo</p>
        <p class="mt-2 text-sm text-slate-700">El documento combina contexto, objetivos, usuarios y KPIs para acelerar la aprobación del brief financiero.</p>
      </article>

      <article class="grid gap-3 md:grid-cols-2">
        <div class="rounded-2xl border border-slate-100 bg-white p-4 shadow-sm">
          <p class="text-xs uppercase tracking-[0.24em] text-slate-400">Cobertura</p>
          <p class="mt-2 text-2xl font-semibold text-slate-900">46 campos</p>
          <p class="text-sm text-slate-500">Con validación de campos requeridos y seguimiento visual.</p>
        </div>
        <div class="rounded-2xl border border-slate-100 bg-white p-4 shadow-sm">
          <p class="text-xs uppercase tracking-[0.24em] text-slate-400">Estado</p>
          <p class="mt-2 text-2xl font-semibold text-amber-500">10 pendientes</p>
          <p class="text-sm text-slate-500">Faltan datos clave para generar el brief final.</p>
        </div>
      </article>

      <article class="rounded-2xl border border-blue-100 bg-blue-50 p-4">
        <p class="text-sm font-semibold text-slate-900">Sugerencia IA</p>
        <p class="mt-1 text-sm text-slate-700">Recomendación: detalla el problema del cliente y su propuesta de valor para mejorar el briefing de venta B2B.</p>
      </article>
    </div>
  </aside>
</template>
