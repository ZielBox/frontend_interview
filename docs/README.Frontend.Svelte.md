

# Svelte Installation & Configuration
Svelte is Frontend web development language and you can read more about on this at ->
[Why Svelte?](https://www.zielbox.com/a-concise-introduction-to-svelte-javascript)
# Frontend
This repository code contains the frontend code developed in Svelte Javascript Framework that is 20X Faster than ReactJS or AngularJS.


# Code Structure
```
# After installation of svelte you will find folder structure like this:

frontend/
  |-- public/
  |-- src/
      |-- components/
      |     |-- FrontPage.svelte         # The main front page component
      |     |-- ...
      |-- routes/
      |     |-- Home.svelte              # Home route, can import FrontPage.svelte
      |     |-- ...
      |-- stores/
      |     |-- app.js                   # Centralized store for managing app-level state
      |     |-- ...
      |-- utils/
      |     |-- api.js                   # Utility functions for interacting with the backend API
      |     |-- ...
      |-- App.svelte                    # The main Svelte app component
      |-- main.js                       # Entry point of the Svelte app
  |-- package.json
  |-- rollup.config.js
```
# How to create new Svelte Project
- Read -> https://svelte.dev/blog/svelte-for-new-developers

- Make sure first you install and [download NodeJS](https://nodejs.org/en/download) as that is pre-requieste for your testing.

Either just directly create frontend project using vite/svelte project or follow below steps
```
C:\repos\flyfast> npm create vite@latest frontend -- --template svelte
```
```
# cd frontend
C:\repos\flyfast\frontend> npm install

added 37 packages, and audited 38 packages in 2m

  run `npm fund` for details

found 0 vulnerabilities
```
Start Your App for testing
```
C:\repos\flyfast\frontend> npm run dev

> frontend@0.0.0 dev
> vite

Forced re-optimization of dependencies

  VITE v4.4.6  ready in 4475 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help
```
OR

Step 1:
```
mkdir frontend-project
cd frontend-project
```

Step 2:
* Initialize a new npm package:
Initialize a new npm package in the project directory by running the following command and answering the prompts:
```
npm init
```
Step 3: 
* Install Svelte and other required dependencies:
* Install Svelte and other required dependencies by running the following command:
```
npm install svelte svelte-routing
```
Step 4: Create folders
```
mkdir src
mkdir src/components
mkdir src/routes
mkdir src/stores
mkdir src/utils
```
Step 5:

* Create the Svelte components:
Create the necessary Svelte components in the src/components and src/routes directories. For example, you can create FrontPage.svelte in the src/components directory and Home.svelte in the src/routes director

* Configure the main app component:
Create the App.svelte file in the src directory. Configure it to use routing and render the appropriate components based on the URL:
* Add below content to src/App.svelte:
```
<script>
  import { Router, Route } from 'svelte-routing';
  import Home from './routes/Home.svelte';

  // You can add more routes here if needed
</script>

<main>
  <Router>
    <Route path="/" component={Home} />
  </Router>
</main>
```

Step 6:

* Start the development server:
In the terminal, run the following command to start the development server and view your Svelte application in the browse
```
PS C:\repos\flyfast\frontend> npm run dev

> frontend@0.0.0 dev
> vite

Forced re-optimization of dependencies

  VITE v4.4.6  ready in 4475 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help

```

Step 7:

Your Svelte application should now be running, and you can access it in your browser at the provided URL.

```
curl http://localhost:5000
```

Step 8: Build your code for distribution

```
C:\repos\flyfast\frontend> npm run build

> frontend@0.0.0 build
> vite build

vite v4.4.6 building for production...
✓ 31 modules transformed.
dist/index.html                  0.45 kB │ gzip: 0.29 kB
dist/assets/svelte-a39f39b7.svg  1.95 kB │ gzip: 0.91 kB
dist/assets/index-9ea02431.css   1.30 kB │ gzip: 0.65 kB
dist/assets/index-5ed9bce5.js    5.69 kB │ gzip: 2.60 kB
✓ built in 657ms

C:\repos\flyfast\frontend>
```

Step 9: Preview for your testing
```
C:\repos\flyfast\frontend> npm run preview

> frontend@0.0.0 preview
> vite preview

  ➜  Local:   http://localhost:4173/
  ➜  Network: use --host to expose
  ➜  press h to show help
```
You should see page like [Svelte Working Page](../references/svelte-working-page.PNG)

STEP 10: After this step you can customize your project like Tailwind CSS adoption , Layout designing etc.