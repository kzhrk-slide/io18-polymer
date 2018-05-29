Web Components and the Polymer Project: Polymer 3.0 and beyond (Google I/O '18)
===

https://www.youtube.com/watch?v=7CUO7PyD5zA

## Polymer 3.0

- bower.js => npm
- HTML Import => ESM
- polymer-cliをESM向けにアップデート（テスト環境やデプロイなど）
- v3の開発環境（starter kit, app, element）をcliに追加

### npm install polymer-element

```
# sample
npm i -d @polymer/paper-checkbox
```

https://www.webcomponents.org/author/PolymerElements

### polymer-cli

```
npm i -g polymer-cli
poymer-cli init

? Which starter template would you like to use?
? Application name polymer
? Main element name polymer-app
? Brief description of the application 
```

## Library

- [lit-html](https://github.com/Polymer/lit-html)のアップデート

## Toolbox

- [PWA Starter Kit](https://github.com/Polymer/pwa-starter-kit)のアップデート
  - reduxの追加
