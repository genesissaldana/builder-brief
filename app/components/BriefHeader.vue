<template>
  <header class="border-b border-slate-200 bg-white/95 backdrop-blur">
    <div class="mx-auto flex max-w-7xl items-center justify-between px-6 py-4 lg:px-8">
      <div class="flex items-center gap-3">
        <div class="flex h-10 w-10 items-center justify-center rounded-xl bg-slate-900 text-white shadow-sm">
          <svg viewBox="0 0 24 24" class="h-5 w-5 fill-current" aria-hidden="true">
            <path d="M4 5.5A2.5 2.5 0 0 1 6.5 3h5.25A2.5 2.5 0 0 1 14.25 5.5v1.25h1.5A2.5 2.5 0 0 1 18.25 9.25v7A2.5 2.5 0 0 1 15.75 18.75h-8A2.5 2.5 0 0 1 5.25 16.25v-10A2.5 2.5 0 0 1 4 5.5Zm2.5-.5a.5.5 0 0 0-.5.5v10c0 .28.22.5.5.5h8c.28 0 .5-.22.5-.5v-7c0-.28-.22-.5-.5-.5h-1.5V5.5a.5.5 0 0 0-.5-.5H6.5Z" />
          </svg>
        </div>
        <div>
          <p class="text-[15px] font-semibold text-slate-900">FinBrief <span class="text-blue-600">AI</span></p>
          <p class="text-xs text-slate-500">Brief generator para equipos B2B</p>
        </div>
      </div>

      <button class="inline-flex items-center gap-2 rounded-xl bg-slate-900 px-4 py-2 text-sm font-semibold text-white shadow-sm transition hover:bg-slate-800">
        <svg viewBox="0 0 24 24" class="h-4 w-4 fill-current" aria-hidden="true">
          <path d="M12 3a1 1 0 0 1 1 1v7h7a1 1 0 1 1 0 2h-7v7a1 1 0 1 1-2 0v-7H4a1 1 0 1 1 0-2h7V4a1 1 0 0 1 1-1Z" />
        </svg>
        Descargar Documento
      </button>
    </div>
  </header>
</template>
