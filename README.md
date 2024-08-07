<a href="https://ignite-timer-rocket-seat-ashy.vercel.app/">Clique aqui para ter acesso a este projeto!</a>

#Ignite Timer 


<p>Este projeto foi desenvolvido nas aulas de Aprondando em Hooks no REACT da Rocket Seat, por Diego Fernandes.</p>

<p>Neste projeto foi utilizado TypeScript e styled-components in js e junto a isso utilização do LocalStorage para armazenamento dos dados dessa aplicação no navegador.</p>


![image](https://github.com/user-attachments/assets/d4f6c167-956f-4853-ad33-fb982e48b527)


![image](https://github.com/user-attachments/assets/30bbe47e-a22e-4a63-8f17-14816e0e633e)


<p>This project was developed in the Aprondando em Hooks classes at Rocket Seat's REACT, by Diego Fernandes.</p>


<p>In this project, TypeScript and styled-components in js were used and along with this, LocalStorage was used to store the data from this application in the browser.</p>





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
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json', './tsconfig.app.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
