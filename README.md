# homework-01

# Calculator App — Changelog

## [1.0.0] – 2025-10-17

### Release summary

Релиз приложения-калькулятора, оформленного с использованием React + TypeScript + Vite + Ant Design.
В релиз вошли основные функциональные модули, интерфейс, тема и фиксы, добавленные через патчи.

### Features

- calc: initial calculator component
- calc: add history panel
- ui: add Ant Design theme
- ui: add layout
- core: extract calculator core
- build: add @ant-design/icons dependency
- build(tsconfig): add path alias support

### Refactoring

- theme: add configTheme setup
- calc: restructure template with Card and Ribbon (патч #1)

### Fixes

- calc: show result via Badge.Ribbon and layout tweaks (патч #2)
- calc: correct onChange and add onAddNumber (патч #3)

### Build & Config

- deps: install Ant Design
- fix: package.json
- chore: merge development into main
- chore: bump version to 1.0.0

### Technical stack

- React 18, TypeScript, Vite
- Ant Design UI library
- Support for path aliases, ESLint, SWC transpilation
