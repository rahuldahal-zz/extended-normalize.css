# extended-normalize.css

> CSS normalize with basic additional styles

[![GitHub license](https://img.shields.io/badge/license-MIT-green)](https://github.com/rahuldahal/extended-normalize.css/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/badge/release-v2.1.0-blue)](https://www.npmjs.com/package/extended-normalize.css)

## Why extended-normalize.css ?

- While writing CSS, a general convention is to "normalize" the default browser's stylesheet.
- This helps in maintaining style consistency across variety of devices and browsers.

### After normalizing, we be like,

Okay, now everything is "normalized". 

*But...*

- The button looks kinda boring.
- The typography is inconsistent among various HTML tags; including input-fields, tables, buttons, select-options, etc.
- The form-fields are dull.

The point is, *there still remains some inconsistency.*<br />
Plus, the default style on buttons, form-fields, etc. are not "neat".

## We can improvise upon this.

### So, What does it actually do?

- Inherits everything from [normailze.css](http://necolas.github.io/normalize.css/) by [Necolas Gallagher](http://nicolasgallagher.com/), i.e. normalizes default browser styles.
- Makes the typography consistent among various HTML tags including input-fields, tables, buttons, select-options, etc.
- Improves the appearance of form-fields, buttons, tables, and lists.
- Makes other subtle style modifications on different tags to make them look neat.
- Explains what code does using detailed comments.

## A quick demo...

[HTML file with and without extended-normalize.css applied](https://raw.githubusercontent.com/rahuldahal/extended-normalize.css/master/extended-normalize-demo.gif);

## How to use ?

**Either, use NPM**

```sh
npm install --save extended-normalize.css
```

_Then, in your "main" js file,_

```javascript
import "extended-normalize.css";
```

**Or, include this inside the "html" file, on the "head" tag**

```html
<link
  rel="stylesheet"
  href="https://unpkg.com/extended-normalize.css@2.1.0/extended-normalize.css"
/>
```

**Or, import in your "main" css file**

```css
@import url("https://unpkg.com/extended-normalize.css@2.1.0/extended-normalize.css");
```

**Or, view [Raw](https://unpkg.com/extended-normalize.css@2.1.0/extended-normalize.css)**



**Author**
[Rahul Dahal](http://rahuldahal.com.np)
