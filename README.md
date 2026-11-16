# react-typescript-materialui-overmind-boilerplate

A React + TypeScript starter (Create React App) with Material-UI and Overmind state already wired together, plus a working counter so you can see the wiring before you delete it.

## What's included

1. **React** via Create React App, in TypeScript
2. **Material-UI** with a theme file you can edit in one place
3. **Overmind** state — state, actions and a typed helper, provided in `index.tsx`
4. **A working counter component** showing how to read and mutate state
5. **Testing Library + Jest** already configured by CRA

## Project layout

```
src/index.tsx               Overmind provider + MUI theme
src/App.tsx                 the app shell
src/Components/Counter.tsx  reads and mutates Overmind state
src/Overmind/               OvermindState / OvermindActions / helper
src/Others/Theme.ts         MUI theme
```

## Getting started

```bash
git clone https://github.com/p32929/react-typescript-materialui-overmind-boilerplate.git
cd react-typescript-materialui-overmind-boilerplate
npm install
npm start          # http://localhost:3000

npm run build
npm test
```

## Related boilerplates

1. [react_typescript_materialui_usm_boilerplate](https://github.com/p32929/react_typescript_materialui_usm_boilerplate) — same stack, usm-redux instead of Overmind
2. [react_shadcn_ts_usm_boilerplate](https://github.com/p32929/react_shadcn_ts_usm_boilerplate) — Vite + shadcn/ui + usm-redux
3. [nextjs-typescript-materialui-overmind-boilerplate](https://github.com/p32929/nextjs-typescript-materialui-overmind-boilerplate) — the Next.js version

## Contributing

Contributions are very welcome, thank you! Before you start on a pull request, please open an issue and tell me what you would like to add or change. That way we can agree on it first, and your time is not wasted on something that might not fit. Thanks for helping make react-typescript-materialui-overmind-boilerplate better.

## Share

<a href="https://p32929.github.io/share/?repo=react-typescript-materialui-overmind-boilerplate"><img src="https://p32929.github.io/readme/share.svg" alt="Share this with your friends in just a click" width="420"></a>

## Support

<a href="https://p32929.github.io/support/"><img src="https://p32929.github.io/readme/support.svg" alt="If you like my works and want to support me, feel free to support" width="420"></a>
