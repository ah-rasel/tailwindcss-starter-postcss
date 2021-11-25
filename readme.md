# Install the required dependencies with `npm`:

```sh
npm install
```

Then start the dev server:

```sh
npm run dev
```

## New Project Initial Commands:

>Initializing package.json
```sh
npm init -y
```
>Install Tailwind and vite
```sh
npm install -D tailwindcss postcss autoprefixer vite
```
>tailwind config and postcss.config.js
```sh
npx tailwindcss init -p
```
>create css/tailwind.css
```sh
@tailwind base;
@tailwind components;
@tailwind utilities;
```
>create index.html and link to /css/tailwind.css