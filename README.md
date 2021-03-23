# 🥞 Pancake UIkit

[![Version](https://img.shields.io/npm/v/@pancakeswap-libs/uikit)](https://www.npmjs.com/package/@pancakeswap-libs/uikit) [![Size](https://img.shields.io/bundlephobia/min/@pancakeswap-libs/uikit)](https://www.npmjs.com/package/@pancakeswap-libs/uikit)

Pancake UIkit is a set of React components and hooks used to build pages on Pancake's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @pancakeswap-libs/uikit`

## Setup

### Theme

Before using Pancake UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@pancakeswap-libs/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@pancakeswap-libs/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://pancakeswap.github.io/pancake-uikit/)

## How to change logo, spinner and footer nav pic

for LOGO go to /src/widgets/Menu/icons/Logo.tsx line 16 change the filepath of logo

for MOBILE Logo go to /src/components/Svg/icons/Logo.tsx in line 8 change mobile logo path 

for SPINNER got to /src/components/Spinner/Spinner.tsx line 18 change the filepath of spinner

for FOOTER NAV PIC go to /src/components/Svg/icons/PancakeRound.tsx in line 8 change the filepath of footer nav pic