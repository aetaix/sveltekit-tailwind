# SvelteKit + Tailwind CSS + Docker

This is a template for [SvelteKit](https://kit.svelte.dev) apps, blend with [Tailwind CSS](https://tailwindcss.com/), and ready to be deployed with [Docker](https://www.docker.com/).

## Docker

To build a Docker image, we use Makefile to simplify the process. 

### Development

If you don't have an image yet, you can build it with:
```bash
make build
```

To run the image, you can use:
```bash
make run
```

### Production

To build a production image, you can use:
```bash
make build-prod
```

To run the production image, you can use:
```bash
make run-prod
```

### Clean

To clean the images, you can use:
```bash
make down
```
or
```bash
make down-prod
```

## Developing

Once you've pulled the project, install all dependencies with 

```bash 
npm install
```

Then start [Vite](https://vitejs.dev) and [SvelteKit](https://kit.svelte.dev) in development mode:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

