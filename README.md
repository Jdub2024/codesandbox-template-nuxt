# Nuxt

This is a [Nuxt](https://nuxtjs.org/) project bootstrapped by [`create-nuxt-app`](https://github.com/nuxt/create-nuxt-app).

[Configuration](https://codesandbox.io/docs/projects/learn/setting-up/tasks) has been added to optimize it for [CodeSandbox Projects](https://codesandbox.io/p/dashboard).

[![Edit in CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/github/codesandbox/codesandbox-template-nuxt/main)

## Resources

- [CodeSandbox Projects — Docs](https://docs.codesandbox.io)
- [CodeSandbox — Discord](https://discord.gg/Ggarp3pX5H)
- [Nuxt — GitHub](https://github.com/nuxt/framework)
- [Nuxt — Docs](https://nuxtjs.org/docs)
        {#each Object.values(obj.document) as v}
      {#if isFieldArray(v)}
          {#each v as _, index}
              <input bind:value={v[index]} />
          {/each}
      {:else}
          <Attribute bind:value={v} />
      {/if}
{/each}
Huh, that actually makes sense. Thank you!