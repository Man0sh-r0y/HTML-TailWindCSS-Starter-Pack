# HTML-TailWindCSS-Starter-Pack
**Step 1:** Download this repo as a zip

**Step 2:** To run:

```bash
npm install
npm run start
```

**Step 3:** Go to [http://localhost:5173](http://localhost:5173)

Facing any issue: [Documentation](https://tailwindcss.com/docs/installation/using-postcss)

## You can also install TailwindCSS by following below methods:

Here are the steps to install TailwindCSS

## Installation

1. Initialize the project:
    ```bash
    npm init
    ```
1. Install Vite:
    ```bash
    npm install vite
    ```
1. Install Tailwind CSS, PostCSS, and Autoprefixer:
    ```bash
    npm install -D tailwindcss postcss autoprefixer
    ```
1. Generate Tailwind CSS configuration:
    ```bash
    npx tailwindcss init
    ```

1. Create a `postcss.config.js` file:
    ```bash
    touch postcss.config.js
    echo "module.exports = {
    plugins: {
        tailwindcss: {},
        autoprefixer: {},
    }
    }" > postcss.config.js
    ```
1. Edit `tailwind.config.js`:

    Open the file using your preferred text editor and paste the following configuration:
    ```bash
    /** @type {import('tailwindcss').Config} */
    module.exports = {
    content: ["*"],
    theme: {
        extend: {},
    },
    plugins: [],
    }
    ```
1. Add a start script to `package.json`:

    Edit the following line to your `package.json` file:
    ```bash
    "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "vite"
    },
    ```
1. Create and edit main.css:
    ```bash
    touch main.css
    nano main.css
    ```
    Paste the following code and save the file:
    ```bash
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```
    Once you're done, press `Ctrl + O` to save the file, then press `Enter`. To exit `nano`, press `Ctrl + X`

1. Create and edit `index.html`:
    ```bash
    touch index.html
    nano index.html
    ```
    Paste the following code and save the file:
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <link rel="stylesheet" href="./main.css">
    </head>
    <body>
        
    </body>
    </html>
    ```

1. To run:

    ```bash
    npm run start
    ```

1. Then Go to [http://localhost:5173](http://localhost:5173)


