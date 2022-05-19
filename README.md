# Modern Redux with RTK (Redux Toolkit) and Typescript

## Set up and run the app

The app is generated with vite is divided into two small features:

- a counter feature
- a dog fetching API

To start the app run:

`npm run dev`

## Counter

The counter app uses the counter slice to manage the value of the counter.
It needs the store configuration inside the /app/store.ts and needs some ts set up inside the /app/hooks.ts

## Dogs

The second feature allows to fetch dogs through the RTK Query API.

A slice is created using the createApi method. That allows to generate a hook name useFetchBreedsQuery.
