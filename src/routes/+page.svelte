<script lang="ts">
  import { SignIn } from "@auth/sveltekit/components"
</script>

<main>
    <h1>SvelteKit Auth Example</h1>
    <p>
      This is an example site to demonstrate how to use <a
        href="https://kit.svelte.dev/">SvelteKit</a
      >
      with <a href="https://sveltekit.authjs.dev">SvelteKit Auth</a> for authentication.
    </p>
    <div>
      <SignIn provider="github" signInPage="signin" />
    </div> 
  </main>
  
  <style>
    main {
      flex: 1;
    }
  </style>
