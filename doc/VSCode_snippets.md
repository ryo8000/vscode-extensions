# VSCode Snippets

This is the collection of snippets provided by VSCode.

---

### HTML

```html
<!-- Sample: -->
<!-- Type ! or html:5 -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
<!-- Type a -->
<a href=""></a>
<!-- Type a:blank -->
<a href="http://" target="_blank" rel="noopener noreferrer"></a>
<!-- Type a:link -->
<a href="http://"></a>
<!-- Type a:mail -->
<a href="mailto:"></a>
<!-- Type a:tel -->
<a href="tel:+"></a>

<!-- Type bq -->
<blockquote></blockquote>
<!-- Type btn -->
<button></button>
<!-- Type btn:d -->
<button disabled="disabled"></button>
<!-- Type btn:r -->
<button type="reset"></button>
<!-- Type btn:s -->
<button type="submit"></button>

<!-- Type cc:ie -->
<!--[if IE]><![endif]-->
<!-- Type cc:noie -->
<!--[if !IE]><!--><!--<![endif]-->

<!-- Type form -->
<form action=""></form>
<!-- Type form:get -->
<form action="" method="get"></form>
<!-- Type form:post -->
<form action="" method="post"></form>
<!-- Type fst:d -->
<fieldset disabled="disabled"></fieldset>

<!-- Type html:xml -->
<html xmlns="http://www.w3.org/1999/xhtml"></html>

<!-- Type ifr -->
<iframe src="" frameborder="0"></iframe>

<!-- Type img -->
<img src="" alt="">
<!-- Type img:s or ri:d -->
<img src="" alt="" srcset="">
<!-- Type img:z or ri:v -->
<img src="" alt="" sizes="" srcset="">

<!-- Type inp -->
<input type="text" name="" id="">
<!-- Type input -->
<input type="text">
<!-- Type input:b -->
<input type="button" value="">
<!-- Type input:c -->
<input type="checkbox" name="" id="">
<!-- Type input:color -->
<input type="color" name="" id="">
<!-- Type input:date -->
<input type="date" name="" id="">
<!-- Type input:datetime -->
<input type="datetime" name="" id="">
<!-- Type input:datetime-local -->
<input type="datetime-local" name="" id="">
<!-- Type input:email -->
<input type="email" name="" id="">
<!-- Type input:f -->
<input type="file" name="" id="">
<!-- Type input:h -->
<input type="hidden" name="">
<!-- Type input:i -->
<input type="image" src="" alt="">
<!-- Type input:month -->
<input type="month" name="" id="">
<!-- Type input:number -->
<input type="number" name="" id="">
<!-- Type input:p -->
<input type="password" name="" id="">
<!-- Type input:r -->
<input type="radio" name="" id="">
<!-- Type input:range -->
<input type="range" name="" id="">
<!-- Type input:reset -->
<input type="reset" value="">
<!-- Type input:s -->
<input type="submit" value="">
<!-- Type input:search -->
<input type="search" name="" id="">
<!-- Type input:t -->
<input type="text" name="" id="">
<!-- Type input:tel -->
<input type="tel" name="" id="">
<!-- Type input:time -->
<input type="time" name="" id="">
<!-- Type input:url -->
<input type="url" name="" id="">
<!-- Type input:week -->
<input type="week" name="" id="">

<!-- Type label -->
<label for=""></label>

<!-- Type link -->
<link rel="stylesheet" href="">
<!-- Type link:css -->
<link rel="stylesheet" href="style.css">
<!-- Type link:favicon -->
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
<!-- Type link:im -->
<link rel="import" href="component.html">
<!-- Type link:mf -->
<link rel="manifest" href="manifest.json">
<!-- Type link:print -->
<link rel="stylesheet" href="print.css" media="print">
<!-- Type link:rss -->
<link rel="alternate" href="rss.xml" type="application/rss+xml" title="RSS">
<!-- Type link:touch -->
<link rel="apple-touch-icon" href="favicon.png">

<!-- Type menu:c -->
<menu type="context"></menu>
<!-- Type menu:t -->
<menu type="toolbar"></menu>

<!-- Type meta:compat -->
<meta http-equiv="X-UA-Compatible" content="IE=7">
<!-- Type meta:desc -->
<meta name="description" content="">
<!-- Type meta:edge -->
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<!-- Type meta:kw -->
<meta name="keywords" content="">
<!-- Type meta:redirect -->
<meta http-equiv="refresh" content="0; url=http://example.com">
<!-- Type meta:utf -->
<meta http-equiv="Content-Type" content="text/html;charset=UTF-8">
<!-- Type meta:vp -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Type obj -->
<object data="" type=""></object>
<!-- Type opt -->
<option value=""></option>

<!-- Type param -->
<param name="" value="">

<!-- Type ri:a -->
<picture>
  <source media="(min-width: )" srcset="">
  <img src="" alt="">
</picture>
<!-- Type ri:t -->
<picture>
  <source srcset="" type="image/">
  <img src="" alt="">
</picture>

<!-- Type script:src -->
<script src=""></script>

<!-- Type select -->
<select name="" id=""></select>
<!-- Type select:d -->
<select name="" id="" disabled="disabled"></select>

<!-- Type src:m -->
<source media="(min-width: )" srcset="">
<!-- Type src:mt -->
<source media="(min-width: )" srcset="" type="image/">
<!-- Type src:mz -->
<source media="(min-width: )" srcset="" sizes="">
<!-- Type src:s -->
<source srcset="">
<!-- Type src:sc -->
<source src="" type="">
<!-- Type src:t -->
<source srcset="" type="image/">
<!-- Type src:z -->
<source sizes="" srcset="">
<!-- Type src:zt -->
<source sizes="" srcset="" type="image/">

<!-- Type tarea -->
<textarea name="" id="" cols="30" rows="10"></textarea>

<!-- Type video -->
<video src=""></video>
```

### JavaScript

```js
// Sample:
// Type e
console.error();

// Type foreach
array.forEach(element => {
});

// Type for
for (let index = 0; index < array.length; index++) {
  const element = array[index];

}

// Type forin
for (const key in object) {
  if (object.hasOwnProperty(key)) {
    const element = object[key];

  }
}

// Type forof
for (const iterator of object) {
}

// Type function
function name(params) {
}

// Type if
if (condition) {
}

// Type ifelse
if (condition) {

} else {

}

// Type import statement
import {  } from "module";

// Type log
console.log();

// Type new
const name = new type(arguments);

// Type setinterval
setInterval(() => {

}, interval);

// Type settimeout
setTimeout(() => {

}, timeout);

// Type switch
switch (key) {
  case value:

    break;

  default:
    break;
}

// Type trycatch
try {

} catch (error) {

}

// Type warn
console.warn();

// Type while
while (condition) {
}
```
