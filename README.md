# Starting template: React + Typescript + TailwindCSS + DaisyUI

This is a quick starting template ready to start working on, which includes React, Typescript and TailwindCSS + DaisyUI.

## Things done to create this project

1. Run `npx create-react-app <project_name> --template typescript`.
This will create all the code needed to use React + Typescript.
2. Remove unneeded code like dummy tests and logo.
3. Run `npm install -D tailwindcss`.
This will add tailwindcss as a dev dependency.
4. Run `npx tailwindcss init`.
This will setup tailwindcss for you, creating the tailwind.config.js file.
5. Modified the `contents` array in `tailwding.config.js` file to `['./src/**/*.{js,ts,jsx,tsx}']`.
6. Added @tailwind directives for each layer to `./src/index.css`.
    ```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```
7. Run `npm i daisyui`.
This will install the `daisyui` dependency.
8. Added `daisyui` to `tailwind.config.js` file.
    ```
    module.exports = {
    //...
    plugins: [require("daisyui")],
    }
    ```

## How to run this project

Just run `yarn start` or `npm start`.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
