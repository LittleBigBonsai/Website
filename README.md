# Bonsai Website
This project is a web frontend for various community-maintained LBP gameservers. While most
gameservers have built-in web UIs, this project aims to remove the need for them with the goal of
being more visually pleasing and easier to use. It is made using Sveltekit.

### Finding your way around / other notes
This section assumes you have basic familiarity with how to use Svelte, if you don't
then [here's the documentation](https://svelte.dev/docs/kit/introduction).

 - Static assets, like the site's icon, live in `static/`.
 - Everything to do with layout and pages is in `src/routes/`.
 - Drivers for communicating with LBP gameservers live in `src/lib`.

This project uses TypeScript.

Styling is done with Tailwind CSS.

Unit tests are done using vitest.

Browser tests are done using Playwright.

Package management is done with pnpm.
