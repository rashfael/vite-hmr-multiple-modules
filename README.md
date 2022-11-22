# Vite HMR repro

0. `npm ci`
1. `npm run dev`
2. open `localhost:5173`
3. change both script and template in App.vue and save at the same time
4. Get `Property "foo" was accessed during render but is not defined on instance.` in the browser console
