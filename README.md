> Demonstrates [`vite`'s base URL configuration](https://vitejs.dev/config/#base)

https://stackoverflow.com/q/68380194/6277151

This project uses `./` as the base URL in production mode (when built), and `/` in development mode.

#### Verification steps:

 1. Install dependencies:

    ```sh
    yarn
    ```

 2. Build the app:

    ```sh
    yarn build
    ```

 3. Open `dist/index.html`, and verify that the URLs are prefixed with `./` instead of `/`.

    <img width="554" alt="Screen Shot 2021-07-22 at 4 40 24 PM" src="https://user-images.githubusercontent.com/26580/126713020-774e1c64-aaf1-4d69-b3e9-fd6481f84888.png">

 4. Serve the app in production mode:
 
    ```sh
    yarn serve
    ```

 5. Browse to the app, inspect the Vue logo on the home page, and verify that the URL is prefixed with `./` instead of `/`.

     <img width="533" alt="Screen Shot 2021-07-22 at 4 34 20 PM" src="https://user-images.githubusercontent.com/26580/126712847-e8b65c67-b289-412c-8b1a-badf3c055468.png">

 6. Serve the app in development mode:

    ```sh
    yarn dev
    ```

 7. Browse to the app, inspect the Vue logo on the home page, and verify that the URL is prefixed with `/` instead of `./`.

    <img width="480" alt="Screen Shot 2021-07-22 at 4 34 05 PM" src="https://user-images.githubusercontent.com/26580/126712903-fd342732-1049-47ae-bd8a-ce4ffd6250bd.png">
