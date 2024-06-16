<script>
  import Github from '../svg/tech/github.svelte'
  import Technologies from './Technologies.svelte'
  import I18n from './i18n.svelte'
</script>

<div class="md:flex-center flex-col pt-24">
  <div id="#" class="flex flex-col items-start justify-center p-4 font-semibold">
    <div class="space-y-8">
      <h1 class="text-3xl md:text-5xl">Hello!</h1>

      <p>
        I'm a self-taught JavaScript developer focused in back-end development and a Linux
        enthusiastic.
      </p>

      <I18n />

      <p>
        I started studying programming back in 2017 when I was 11 years old! Since then I've been
        creating a few projects to improve my skills.
      </p>

      <div>
        <Technologies />
      </div>

      <div class="flex-center">
        <div
          class="flex-center max-w-sm rounded-xl bg-neutral-800 p-3 text-sm transition ease-in hover:bg-neutral-900 md:p-4 md:text-base"
        >
          <a class="flex-center" href="https://github.com/hknsh/portfolio/">
            <div class="pr-2">
              <Github />
            </div>
            Check this portfolio on GitHub
          </a>
        </div>
      </div>
    </div>
  </div>
</div>
