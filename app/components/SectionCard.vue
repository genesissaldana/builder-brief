<script setup lang="ts">
interface Props {
  number: number;
  title: string;
  subtitle: string;
  count: string;
  required?: boolean;
}

const props = withDefaults(defineProps<Props>(), {
  required: true,
});
</script>

<template>
  <article class="border-b border-slate-100 px-6 py-4 last:border-b-0 hover:bg-slate-50/70">
    <div class="flex items-center gap-4">
      <div class="flex h-9 w-9 items-center justify-center rounded-2xl bg-slate-100 text-xs font-bold text-slate-600">
        {{ props.number }}
      </div>

      <div class="flex min-w-0 flex-1 items-start gap-3">
        <div class="mt-1 flex h-5 w-5 items-center justify-center rounded-md bg-slate-100 text-slate-500">
          <svg viewBox="0 0 24 24" class="h-3.5 w-3.5 fill-current" aria-hidden="true">
            <path d="M12 2 3 6v6c0 4.42 2.94 8.53 9 10 6.06-1.47 9-5.58 9-10V6l-9-4Zm0 2.18 6 2.67v4.62c0 3.15-1.88 6.17-6 7.6-4.12-1.43-6-4.45-6-7.6V6.85l6-2.67Z" />
          </svg>
        </div>
        <div class="min-w-0 flex-1">
          <p class="text-sm font-semibold text-slate-900">{{ props.title }}</p>
          <p class="text-xs text-rose-500">{{ props.subtitle }}</p>
        </div>
      </div>

      <div class="flex items-center gap-3">
        <span class="rounded-md border border-slate-200 px-2.5 py-1 text-[11px] font-semibold text-slate-400">
          {{ props.count }}
        </span>
        <svg viewBox="0 0 24 24" class="h-4 w-4 fill-current text-slate-400" aria-hidden="true">
          <path d="M8.47 4.47a.75.75 0 0 1 1.06 0L15 9.94l-5.47 5.47a.75.75 0 1 1-1.06-1.06L12.88 10 8.47 5.59a.75.75 0 0 1 0-1.12Z" />
        </svg>
      </div>
    </div>
  </article>
</template>
