<div align="center"><img src="/src/assets/fav/ori_3630096_tnzxpmp639exin3dc7kb2fecfkmmb4naa04kipkz_sf-monogram-logo-design.png" width="150px"></div>
<br />
<div align="center">
  <h2 align="center">Samuele Furnari | Shoot</h2>

  <p align="center">
    <br />
    <a href="https://samuelefrni.netlify.app/"><strong>View Demo</strong></a>
  </p>
</div>

## About the project

This project is all about the creation of my personal website, showcasing my passion for travel and photography. As you can see, my love for exploring new places and capturing moments is at the heart of it all. My website serves as a dedicated space to share these experiences.

## Installation

1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install` (or relevant command).

## Usage

1. Run the app with `npm start`.
2. Access the app at [localhost:3000](http://localhost:3000).

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT)

## Creator

- **Samuele Furnari**
  - Email: samuelefurnari9@gmail.com
  - GitHub: [samuelefrni](https://github.com/samuelefrni)
  - LinkedIn: [Samuele Furnari](https://www.linkedin.com/in/samuele-furnari-a37567220/)

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
    project: ["./tsconfig.json", "./tsconfig.node.json"],
    tsconfigRootDir: __dirname,
  },
};
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
