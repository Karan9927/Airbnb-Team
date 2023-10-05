# Airbnb-Team

## [Hosted Link](https://rajakhan017.github.io/Airbnb-Team/Karan/index.html)

### Table of Contents

The screenshots take a lot of space. Click on the links to navigate easily

- [Airbnb Clone]
  - [Hosted Link]
    - [Table of Contents]
    - [Features]
    - [Screenshots]
    - [Tools used to build the project]
    - [Tailwind Custom Plugins]
    - [Building / package.json scripts]
    - [Contributors]

### Features

- Fully responsive
- Hard to distinguish from the real webpage
- High quality carousels
- Auto-playing videos to catch attention even in desktop version
- Interactive footer and menu buttons

### Screenshots
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/8283000c-c10a-40b9-b773-f6584d63920f)
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/472d8190-5078-4b87-acf1-e7b639011cba)
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/b4403c37-11dd-44ce-8a8e-97fb92674f8f)
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/de93848b-3995-43aa-a900-ed55711ed6a1)
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/ba0b0283-bf21-4ea8-9b00-da9b3e00629b)
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/314c3520-4586-4af7-b072-dde3669b11a9)
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/97235ecd-d019-44c6-993d-83af1db9d04f)
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/a37d6595-5f9d-41d4-bda8-a1a997414d2c)
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/ef0529ea-f65c-41b6-8dcc-ff8ed32647e1)
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/8a77d0c8-0037-408b-a517-1ebd1c53e0b1)
## Play-Section Screenshot
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/d1428b47-a30e-4566-a3c2-d7f86c80a064)
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/585be628-2c4e-4f3e-b7de-e4c66b3c8f5f)
![image](https://github.com/rajakhan017/Airbnb-Team/assets/135150598/cae45b45-8970-459c-a6fa-d917f44d38c5)








`

``

### Tools used to build the project

| Tool           | Purpose                                                            | Link                                        |
| -------------- | ------------------------------------------------------------------ | ------------------------------------------- |
| HTML           | Markup language                                                    | —                                           |
| CSS            | Scripting language for styling webpages                            | —                                           |
| TailwindCSS    | CSS Framework                                                      | [Link](https://tailwindcss.com/)            |
| slick carousel | For carousel                                                       | [Link](https://kenwheeler.github.io/slick/) |
| jQuery         | For slick to function properly and for some click and hover events | [Link](https://jquery.com/)                 |
| JavaScript     | Logic for the webpage in some elements                             | —                                           |
| FontAwesome    | Adds custom icons                                                  | [Link](https://fontawesome.com/)            |

### Tailwind Custom Plugins

`input.css`: Extra base layers to make a font family from external font files for easy use
![Tailwind Base Layer](./assets/readme/base%20layer.png)

`tailwind.config.js`: Custom colors, media breakpoints, line heights, search bar background
![Tailwind Plugins](./assets/readme/tailwind%20plugins.png)

### Building / package.json scripts

After cloning the files into your local machine, run

`npm install`

to install the dev dependencies

`npm run buildcss`

which is defined in `package.json` to run

`npx tailwindcss -i input.css -o style.css --watch`

And you should be good to go to edit the files using your own tailwindcss.

To make the CSS file as small and efficient as possible, a script for that is also present for production.

`npm run minify`

which is defined in the `package,json` to run

`npx tailwindcss -o style.css --minify`

### Contributors

- Imamul Haque Khan
- Shikha Sharma
- Karan
- Divyansh

---

Imamul Haque Khan or any of the other members working on the project are not affiliated with Airbnb.

All images, fonts are trademarks and copyrights of Airbnb and they are not used for commercial use.
