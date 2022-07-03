# 1. Install Node.js

LTS https://nodejs.org/

> **System restart required**

# 2. Check Node instalation

```
node -v
npm -v
```

# 3. Install gulp-cli

```
npm install gulp-cli -g
```

> Required only at first instalation

For **mac** and **linux** users required **sudo**

# 4. Unzip archive and install modules

```
npm install
```

# 5. Check _gulp-cli_ and _gulp_ instlation

```
gulp -v
```

> Expected output:
> **CLI version x.x.x**  
> **Local version 4.x.x**

# 6. Start gulp watch

```
gulp watch
```

## Recomended structure

<pre>
project/
  | index.html
  | assets/
      | scss/
      |   | style.scss
      |   | _skin.scss
      |   | _variables.scss
      |   | _other-files.scss
      | css/
      |   | style.css
      | js
          | main.js
</pre>

# 7. Stop gulp

```
ctrl+c
```
