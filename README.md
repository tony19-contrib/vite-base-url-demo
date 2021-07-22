> Demonstrates `vite`'s base URL configuration

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

 4. Serve the app in production mode:
 
    ```sh
    yarn serve
    ```

 5. Browse to the app, inspect the Vue logo on the home page, and verify that the URL is prefixed with `./` instead of `/`.

 6. Serve the app in development mode:

    ```sh
    yarn dev
    ```

 7. Browse to the app, inspect the Vue logo on the home page, and verify that the URL is prefixed with `/` instead of `./`.
