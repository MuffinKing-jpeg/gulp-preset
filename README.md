# Instalation guide

## 1. Install Node.js

LTS <https://nodejs.org/>

> **System restart required**

## 2. Check Node instalation

```sh
node -v
npm -v
```

## 3. Install gulp-cli

```sh
npm install gulp-cli -g
```

> Required only at first instalation

For **mac** and **linux** users required **sudo**

## 4. Unzip archive and install modules

```sh
npm install
```

## 5. Check _gulp-cli_ and _gulp_ instlation

```sh
gulp -v
```

> Expected output:  
> **CLI version x.x.x**  
> **Local version 4.x.x**

## 6. Start gulp watch

```sh
gulp watch
```

### Recomended structure

```html
project/
  | index.html
  | assets/
      | scss/
      |   | style.scss
      |   | _skin.scss
      |   |_variables.scss
      |   | _other-files.scss
      | css/
      |   | style.css
      | js
          | main.js
```

## 7. Stop gulp

```sh
ctrl+c
```
