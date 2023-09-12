<script lang="ts">
  import '../../app.css'
  import '@allmaps/ui/css/fonts.css'

  import { Logo } from '@allmaps/ui'

  export let title = ''
  export let description = ''
  export let image = ''
</script>

<svelte:head>
  <title>{title}</title>
  <meta property="og:title" content={title} />
  <meta property="og:description" content={description} />
  <meta property="og:image" content={`https://allmaps.org/news/${image}`} />
</svelte:head>

<article class="prose lg:prose-xl container mx-auto mb-32 p-4">
  <div class="flex flex-row justify-center">
    <div class="w-20 inline-block">
      <Logo />
    </div>
  </div>
  <h1 class="text-center">{title}</h1>
  <slot />
</article>
