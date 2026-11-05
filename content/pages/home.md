---
title: Chai Corner
slug: home
url: /
order: 50
description: Chai Corner is a small tea stall pouring masala chai, ginger tea and iced lemon tea, with snacks to go alongside.
---

<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700;12..96,800&display=swap">
<style>
  .p-home .steam span { display:block; width:6px; border-radius:999px; background:linear-gradient(to top, rgba(255,255,255,0), rgba(255,255,255,.55)); }
  @media (prefers-reduced-motion: no-preference) {
    .p-home .steam span { animation: p-home-rise 3.2s ease-in-out infinite; }
    .p-home .steam span:nth-child(2) { animation-delay: .6s; }
    .p-home .steam span:nth-child(3) { animation-delay: 1.2s; }
    .p-home .fade-up { animation: p-home-up .8s cubic-bezier(.2,.7,.2,1) both; }
    .p-home .fade-up-2 { animation: p-home-up .8s .15s cubic-bezier(.2,.7,.2,1) both; }
  }
  @keyframes p-home-rise { 0% { transform: translateY(8px) scaleY(.8); opacity:0 } 40% { opacity:1 } 100% { transform: translateY(-14px) scaleY(1.1); opacity:0 } }
  @keyframes p-home-up { from { transform: translateY(14px); opacity:0 } to { transform:none; opacity:1 } }
  .p-home .dots { background-image: radial-gradient(rgba(15,118,110,.18) 1px, transparent 1px); background-size: 18px 18px; }
</style>

<div class="p-home">

<section class="relative isolate overflow-hidden bg-zinc-950">
  <img src="/assets/img/generated/homepage-mw3c0hdl.webp" alt="A hand pouring steaming milky chai from an aluminium kettle into a glass at a wooden tea stall counter, with blue shelves of jars behind and green fields outside" width="1536" height="1024" class="absolute inset-0 -z-20 h-full w-full object-cover object-[72%_center]">
  <div class="absolute inset-0 -z-10 bg-linear-to-t from-zinc-950 via-zinc-950/70 to-zinc-950/20 md:bg-linear-to-r md:from-zinc-950/90 md:via-zinc-950/55 md:to-transparent"></div>
  <div class="mx-auto flex min-h-[86svh] max-w-7xl flex-col justify-end px-5 pb-14 pt-32 sm:px-8 md:justify-center md:pb-24">
    <div class="max-w-xl fade-up">
      <p class="flex items-center gap-3 text-sm font-semibold uppercase tracking-[0.2em] text-teal-200">
        <span class="h-px w-10 bg-teal-300"></span>Tea stall
      </p>
      <h1 class="mt-5 font-['Bricolage_Grotesque'] text-[clamp(3rem,10vw,6.5rem)] font-extrabold leading-[0.92] tracking-tight text-white">
        <span class="mb-2 block text-[0.34em] font-bold leading-none tracking-normal text-teal-200">Welcome to</span>
        {{ page.title }}
      </h1>
      <p class="mt-6 max-w-md text-lg leading-relaxed text-zinc-200 sm:text-xl">Masala chai and snacks, poured hot from the kettle at a small corner stall.</p>
    </div>
    <div class="mt-9 flex flex-wrap gap-3 fade-up-2">
      <a href="#menu" class="inline-flex min-h-12 items-center gap-2 rounded-full bg-brand px-7 py-3 text-base font-semibold text-white shadow-lg shadow-brand/40 transition hover:-translate-y-0.5 hover:bg-teal-600 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-teal-300">
        View menu
        <svg class="h-4 w-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M5 12h14M13 6l6 6-6 6"/></svg>
      </a>
      <a href="#visit" class="inline-flex min-h-12 items-center rounded-full bg-white/10 px-7 py-3 text-base font-semibold text-white ring-1 ring-white/30 backdrop-blur transition hover:-translate-y-0.5 hover:bg-white/20 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white">Find the stall</a>
    </div>
    {{# if site.contact.hours }}
    <div class="mt-10 inline-flex w-fit items-center gap-3 rounded-2xl bg-white/10 px-4 py-3 text-sm text-white ring-1 ring-white/20 backdrop-blur-md fade-up-2">
      <svg class="h-5 w-5 text-teal-300" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.75" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 2"/></svg>
      <span>Open {{ site.contact.hours }}</span>
    </div>
    {{/ if }}
  </div>
</section>

<section id="about" class="relative scroll-mt-20 overflow-hidden bg-linear-to-b from-teal-50/70 via-white to-white">
  <div class="pointer-events-none absolute -right-24 -top-28 h-72 w-72 rounded-full bg-brand/10 blur-3xl" aria-hidden="true"></div>
  <div class="relative mx-auto max-w-7xl px-5 py-16 sm:px-8 md:py-24">
    <div class="grid gap-8 md:grid-cols-[0.8fr_1.2fr] md:items-start md:gap-16 lg:gap-24">
      <div>
        <h2 class="font-['Bricolage_Grotesque'] text-3xl font-bold tracking-tight text-zinc-950 sm:text-4xl">Our story</h2>
        <p class="mt-5 inline-flex items-center gap-3 rounded-2xl bg-white px-4 py-3 text-sm font-semibold uppercase tracking-[0.16em] text-brand ring-1 ring-teal-200">
          <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.75" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="5" width="18" height="16" rx="2"/><path d="M8 3v4M16 3v4M3 11h18"/></svg>
          Since 2020
        </p>
      </div>
      <div class="max-w-2xl">
        <p class="text-xl leading-relaxed text-zinc-700 sm:text-2xl sm:leading-relaxed">Chai Corner is a fictional tea stall. We have served masala chai since 2020. It is still the cup we pour first.</p>
      </div>
    </div>
  </div>
</section>

<section id="menu" class="relative scroll-mt-20 overflow-hidden bg-white">
  <div class="dots absolute inset-x-0 top-0 h-64 [mask-image:linear-gradient(to_bottom,black,transparent)]" aria-hidden="true"></div>
  <div class="relative mx-auto max-w-7xl px-5 py-20 sm:px-8 md:py-28">
    <div class="grid gap-12 lg:grid-cols-[0.8fr_1.2fr] lg:gap-16">
      <div class="lg:sticky lg:top-24 lg:self-start">
        <h2 class="font-['Bricolage_Grotesque'] text-4xl font-bold tracking-tight text-zinc-950 sm:text-5xl">Three drinks, made to order</h2>
        <p class="mt-5 max-w-md text-lg leading-relaxed text-zinc-600">A short menu, poured fresh for every cup. Hot, spiced or cold and sharp.</p>
      </div>

      <div class="grid gap-5 md:grid-cols-2">
        <article class="group relative overflow-hidden rounded-3xl bg-brand p-8 text-white shadow-xl shadow-brand/25 transition hover:-translate-y-1 hover:shadow-2xl hover:shadow-brand/30 md:row-span-2 md:flex md:flex-col md:justify-between">
          <div class="absolute -right-16 -top-16 h-56 w-56 rounded-full bg-teal-400/30 blur-3xl" aria-hidden="true"></div>
          <div class="relative">
            <div class="steam flex h-8 items-end gap-2 pl-3" aria-hidden="true"><span class="h-6"></span><span class="h-8"></span><span class="h-5"></span></div>
            <svg class="mt-1 h-14 w-14 text-teal-100" viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M8 18h26v10a12 12 0 0 1-12 12h-2A12 12 0 0 1 8 28V18Z"/><path d="M34 21h3a5 5 0 0 1 0 10h-3"/></svg>
            <p class="mt-6 text-sm font-semibold uppercase tracking-[0.18em] text-teal-100">The house cup</p>
          </div>
          <div class="relative mt-10">
            <div class="flex items-end justify-between gap-4">
              <h3 class="font-['Bricolage_Grotesque'] text-3xl font-bold sm:text-4xl">Masala Chai</h3>
              <p class="font-['Bricolage_Grotesque'] text-4xl font-extrabold">$3</p>
            </div>
            <p class="mt-3 text-lg text-teal-50">Spiced milk tea</p>
          </div>
        </article>

        <article class="group rounded-3xl bg-white p-7 ring-1 ring-zinc-200 shadow-sm transition hover:-translate-y-1 hover:shadow-lg hover:ring-brand/40">
          <div class="flex items-start justify-between gap-4">
            <span class="grid h-12 w-12 place-items-center rounded-2xl bg-amber-50 text-amber-700 ring-1 ring-amber-200">
              <svg class="h-6 w-6" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.75" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M7 14c-2-3 0-7 3-8 1 2 4 2 5 0 3 1 4 5 2 8-1.5 2.5-4 4-5 4s-3.5-1.5-5-4Z"/><path d="M12 10v8"/></svg>
            </span>
            <p class="font-['Bricolage_Grotesque'] text-3xl font-extrabold text-zinc-950">$3</p>
          </div>
          <h3 class="mt-6 font-['Bricolage_Grotesque'] text-2xl font-bold text-zinc-950">Ginger Tea</h3>
          <p class="mt-2 text-base text-zinc-600">Fresh ginger and tea</p>
        </article>

        <article class="group rounded-3xl bg-linear-to-br from-teal-50 to-white p-7 ring-1 ring-teal-100 shadow-sm transition hover:-translate-y-1 hover:shadow-lg hover:ring-brand/40">
          <div class="flex items-start justify-between gap-4">
            <span class="grid h-12 w-12 place-items-center rounded-2xl bg-white text-brand ring-1 ring-teal-200">
              <svg class="h-6 w-6" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.75" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M6 4h12l-1.5 16h-9L6 4Z"/><path d="M6.5 9h11"/><circle cx="15" cy="4" r="2.5"/></svg>
            </span>
            <p class="font-['Bricolage_Grotesque'] text-3xl font-extrabold text-zinc-950">$4</p>
          </div>
          <h3 class="mt-6 font-['Bricolage_Grotesque'] text-2xl font-bold text-zinc-950">Iced Lemon Tea</h3>
          <p class="mt-2 text-base text-zinc-600">Cold and sharp</p>
        </article>
      </div>
    </div>

    <div class="mt-16 rounded-3xl bg-zinc-50 p-6 ring-1 ring-zinc-200 sm:p-8">
      <h3 class="font-['Bricolage_Grotesque'] text-xl font-bold text-zinc-950">Something to go with it</h3>
      <div class="mt-5 grid gap-3 sm:grid-cols-3">
        <div data-sample class="flex min-h-14 items-center gap-3 rounded-2xl bg-white px-4 py-3 ring-1 ring-zinc-200 transition hover:-translate-y-0.5 hover:ring-brand/40">
          <span class="h-2.5 w-2.5 shrink-0 rounded-full bg-brand" aria-hidden="true"></span>
          <span class="text-base font-medium text-zinc-800">Vegetable samosa</span>
        </div>
        <div data-sample class="flex min-h-14 items-center gap-3 rounded-2xl bg-white px-4 py-3 ring-1 ring-zinc-200 transition hover:-translate-y-0.5 hover:ring-brand/40">
          <span class="h-2.5 w-2.5 shrink-0 rounded-full bg-amber-500" aria-hidden="true"></span>
          <span class="text-base font-medium text-zinc-800">Butter biscuits</span>
        </div>
        <div data-sample class="flex min-h-14 items-center gap-3 rounded-2xl bg-white px-4 py-3 ring-1 ring-zinc-200 transition hover:-translate-y-0.5 hover:ring-brand/40">
          <span class="h-2.5 w-2.5 shrink-0 rounded-full bg-teal-400" aria-hidden="true"></span>
          <span class="text-base font-medium text-zinc-800">Onion pakora</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="stall" class="scroll-mt-20 bg-zinc-950 text-white">
  <div class="mx-auto grid max-w-7xl items-center gap-12 px-5 py-20 sm:px-8 md:py-28 lg:grid-cols-[1.15fr_0.85fr] lg:gap-20">
    <div class="relative">
      <div class="absolute -inset-4 rounded-[2.5rem] bg-brand/30 blur-2xl" aria-hidden="true"></div>
      <div class="relative aspect-[4/3] overflow-hidden rounded-[2rem] ring-1 ring-white/10 shadow-2xl">
        <img src="/assets/img/generated/homepage-mw3c0hdl.webp" alt="Blue wooden shelves of glass jars and steel cups behind the stall counter, with a glass of chai being filled" width="1536" height="1024" class="h-full w-full object-cover object-[85%_center] scale-125">
      </div>
    </div>
    <div>
      <h2 class="font-['Bricolage_Grotesque'] text-4xl font-bold tracking-tight sm:text-5xl">A small stall on the corner</h2>
      <p class="mt-6 text-lg leading-relaxed text-zinc-300">Chai Corner is a small tea stall. We keep the kettle on, pour masala chai the way it should be, spiced and milky, and keep a few snacks by the counter.</p>
      <p class="mt-4 text-lg leading-relaxed text-zinc-300">Pull up a seat on the bench, or take your cup with you.</p>
      <a href="#visit" class="mt-8 inline-flex min-h-12 items-center gap-2 text-base font-semibold text-teal-300 underline-offset-4 transition hover:text-teal-200 hover:underline focus-visible:outline-2 focus-visible:outline-offset-4 focus-visible:outline-teal-300">
        When to find us
        <svg class="h-4 w-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M5 12h14M13 6l6 6-6 6"/></svg>
      </a>
    </div>
  </div>
</section>

<section id="visit" class="scroll-mt-20 bg-teal-50/60">
  <div class="mx-auto max-w-7xl px-5 py-20 sm:px-8 md:py-28">
    <div class="max-w-2xl">
      <h2 class="font-['Bricolage_Grotesque'] text-4xl font-bold tracking-tight text-zinc-950 sm:text-5xl">Visit the stall</h2>
      <p class="mt-5 text-lg leading-relaxed text-zinc-600">Walk up, order at the counter and we'll pour it fresh.</p>
    </div>
    <div class="mt-12 grid gap-5 md:grid-cols-3">
      {{# if site.contact.hours }}
      <div class="rounded-3xl bg-white p-7 shadow-sm ring-1 ring-teal-100 transition hover:-translate-y-1 hover:shadow-lg">
        <svg class="h-7 w-7 text-brand" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.75" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 2"/></svg>
        <h3 class="mt-5 text-sm font-semibold uppercase tracking-[0.16em] text-zinc-500">Opening hours</h3>
        <p class="mt-2 font-['Bricolage_Grotesque'] text-2xl font-bold text-zinc-950">{{ site.contact.hours }}</p>
      </div>
      {{/ if }}
      {{# if site.contact.address }}
      <div class="rounded-3xl bg-white p-7 shadow-sm ring-1 ring-teal-100 transition hover:-translate-y-1 hover:shadow-lg">
        <svg class="h-7 w-7 text-brand" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.75" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 21s-7-6.5-7-12a7 7 0 0 1 14 0c0 5.5-7 12-7 12Z"/><circle cx="12" cy="9" r="2.5"/></svg>
        <h3 class="mt-5 text-sm font-semibold uppercase tracking-[0.16em] text-zinc-500">Where</h3>
        <p class="mt-2 text-lg font-medium text-zinc-950 wrap-break-word">{{ site.contact.address }}</p>
      </div>
      {{/ if }}
      {{# if site.contact.email }}
      <a href="mailto:{{ site.contact.email }}" class="group rounded-3xl bg-white p-7 shadow-sm ring-1 ring-teal-100 transition hover:-translate-y-1 hover:shadow-lg hover:ring-brand/40 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-brand">
        <svg class="h-7 w-7 text-brand" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.75" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="5" width="18" height="14" rx="2"/><path d="m4 7 8 6 8-6"/></svg>
        <h3 class="mt-5 text-sm font-semibold uppercase tracking-[0.16em] text-zinc-500">Email</h3>
        <p class="mt-2 text-lg font-medium text-zinc-950 wrap-break-word group-hover:text-brand">{{ site.contact.email }}</p>
      </a>
      {{/ if }}
      {{# if site.contact.phone }}
      <a href="tel:{{ site.contact.phone }}" class="group rounded-3xl bg-white p-7 shadow-sm ring-1 ring-teal-100 transition hover:-translate-y-1 hover:shadow-lg hover:ring-brand/40 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-brand">
        <svg class="h-7 w-7 text-brand" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.75" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M5 4h4l2 5-2.5 1.5a11 11 0 0 0 5 5L15 13l5 2v4a2 2 0 0 1-2 2A16 16 0 0 1 3 6a2 2 0 0 1 2-2Z"/></svg>
        <h3 class="mt-5 text-sm font-semibold uppercase tracking-[0.16em] text-zinc-500">Phone</h3>
        <p class="mt-2 text-lg font-medium text-zinc-950 group-hover:text-brand">{{ site.contact.phone }}</p>
      </a>
      {{/ if }}
    </div>
  </div>
</section>

<section class="relative overflow-hidden bg-brand">
  <div class="absolute -left-24 top-1/2 h-80 w-80 -translate-y-1/2 rounded-full bg-teal-400/30 blur-3xl" aria-hidden="true"></div>
  <div class="absolute -right-20 -bottom-24 h-72 w-72 rounded-full bg-zinc-950/30 blur-3xl" aria-hidden="true"></div>
  <div class="relative mx-auto flex max-w-7xl flex-col items-start gap-8 px-5 py-16 sm:px-8 md:flex-row md:items-center md:justify-between md:py-20">
    <div class="max-w-xl">
      <h2 class="font-['Bricolage_Grotesque'] text-4xl font-bold tracking-tight text-white sm:text-5xl">The kettle's on</h2>
      <p class="mt-4 text-lg text-teal-50">Come by for a cup of masala chai.</p>
    </div>
    <div class="flex flex-wrap gap-3">
      {{# if site.contact.email }}
      <a href="mailto:{{ site.contact.email }}" class="inline-flex min-h-12 items-center rounded-full bg-white px-7 py-3 text-base font-semibold text-brand shadow-lg shadow-zinc-950/20 transition hover:-translate-y-0.5 hover:bg-teal-50 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white">Get in touch</a>
      {{/ if }}
      <a href="#menu" class="inline-flex min-h-12 items-center rounded-full px-7 py-3 text-base font-semibold text-white ring-1 ring-white/50 transition hover:-translate-y-0.5 hover:bg-white/10 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white">Back to the menu</a>
    </div>
  </div>
</section>

</div>
