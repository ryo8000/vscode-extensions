# VSCode スニペット集

VSCode に最初から用意されているスニペット集です。

---

### HTML

```html
<!-- 例） -->
<!-- ! or html:5 と入力 -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
<!-- a と入力 -->
<a href=""></a>
<!-- a:blank と入力 -->
<a href="http://" target="_blank" rel="noopener noreferrer"></a>
<!-- a:link と入力 -->
<a href="http://"></a>
<!-- a:mail と入力 -->
<a href="mailto:"></a>
<!-- a:tel と入力 -->
<a href="tel:+"></a>

<!-- bq と入力 -->
<blockquote></blockquote>
<!-- btn と入力 -->
<button></button>
<!-- btn:d と入力 -->
<button disabled="disabled"></button>
<!-- btn:r と入力 -->
<button type="reset"></button>
<!-- btn:s と入力 -->
<button type="submit"></button>

<!-- cc:ie と入力 -->
<!--[if IE]><![endif]-->
<!-- cc:noie と入力 -->
<!--[if !IE]><!--><!--<![endif]-->

<!-- form と入力 -->
<form action=""></form>
<!-- form:get と入力 -->
<form action="" method="get"></form>
<!-- form:post と入力 -->
<form action="" method="post"></form>
<!-- fst:d と入力 -->
<fieldset disabled="disabled"></fieldset>

<!-- html:xml と入力 -->
<html xmlns="http://www.w3.org/1999/xhtml"></html>

<!-- ifr と入力 -->
<iframe src="" frameborder="0"></iframe>

<!-- img と入力 -->
<img src="" alt="">
<!-- img:s or ri:d と入力 -->
<img src="" alt="" srcset="">
<!-- img:z or ri:v と入力 -->
<img src="" alt="" sizes="" srcset="">

<!-- inp と入力 -->
<input type="text" name="" id="">
<!-- input と入力 -->
<input type="text">
<!-- input:b と入力 -->
<input type="button" value="">
<!-- input:c と入力 -->
<input type="checkbox" name="" id="">
<!-- input:color と入力 -->
<input type="color" name="" id="">
<!-- input:date と入力 -->
<input type="date" name="" id="">
<!-- input:datetime と入力 -->
<input type="datetime" name="" id="">
<!-- input:datetime-local と入力 -->
<input type="datetime-local" name="" id="">
<!-- input:email と入力 -->
<input type="email" name="" id="">
<!-- input:f と入力 -->
<input type="file" name="" id="">
<!-- input:h と入力 -->
<input type="hidden" name="">
<!-- input:i と入力 -->
<input type="image" src="" alt="">
<!-- input:month と入力 -->
<input type="month" name="" id="">
<!-- input:number と入力 -->
<input type="number" name="" id="">
<!-- input:p と入力 -->
<input type="password" name="" id="">
<!-- input:r と入力 -->
<input type="radio" name="" id="">
<!-- input:range と入力 -->
<input type="range" name="" id="">
<!-- input:reset と入力 -->
<input type="reset" value="">
<!-- input:s と入力 -->
<input type="submit" value="">
<!-- input:search と入力 -->
<input type="search" name="" id="">
<!-- input:t と入力 -->
<input type="text" name="" id="">
<!-- input:tel と入力 -->
<input type="tel" name="" id="">
<!-- input:time と入力 -->
<input type="time" name="" id="">
<!-- input:url と入力 -->
<input type="url" name="" id="">
<!-- input:week と入力 -->
<input type="week" name="" id="">

<!-- label と入力 -->
<label for=""></label>

<!-- link と入力 -->
<link rel="stylesheet" href="">
<!-- link:css と入力 -->
<link rel="stylesheet" href="style.css">
<!-- link:favicon と入力 -->
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
<!-- link:im と入力 -->
<link rel="import" href="component.html">
<!-- link:mf と入力 -->
<link rel="manifest" href="manifest.json">
<!-- link:print と入力 -->
<link rel="stylesheet" href="print.css" media="print">
<!-- link:rss と入力 -->
<link rel="alternate" href="rss.xml" type="application/rss+xml" title="RSS">
<!-- link:touch と入力 -->
<link rel="apple-touch-icon" href="favicon.png">

<!-- menu:c と入力 -->
<menu type="context"></menu>
<!-- menu:t と入力 -->
<menu type="toolbar"></menu>

<!-- meta:compat と入力 -->
<meta http-equiv="X-UA-Compatible" content="IE=7">
<!-- meta:desc と入力 -->
<meta name="description" content="">
<!-- meta:edge と入力 -->
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<!-- meta:kw と入力 -->
<meta name="keywords" content="">
<!-- meta:redirect と入力 -->
<meta http-equiv="refresh" content="0; url=http://example.com">
<!-- meta:utf と入力 -->
<meta http-equiv="Content-Type" content="text/html;charset=UTF-8">
<!-- meta:vp と入力 -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- obj と入力 -->
<object data="" type=""></object>
<!-- opt と入力 -->
<option value=""></option>

<!-- param と入力 -->
<param name="" value="">

<!-- ri:a と入力 -->
<picture>
  <source media="(min-width: )" srcset="">
  <img src="" alt="">
</picture>
<!-- ri:t と入力 -->
<picture>
  <source srcset="" type="image/">
  <img src="" alt="">
</picture>

<!-- script:src と入力 -->
<script src=""></script>

<!-- select と入力 -->
<select name="" id=""></select>
<!-- select:d と入力 -->
<select name="" id="" disabled="disabled"></select>

<!-- src:m と入力 -->
<source media="(min-width: )" srcset="">
<!-- src:mt と入力 -->
<source media="(min-width: )" srcset="" type="image/">
<!-- src:mz と入力 -->
<source media="(min-width: )" srcset="" sizes="">
<!-- src:s と入力 -->
<source srcset="">
<!-- src:sc と入力 -->
<source src="" type="">
<!-- src:t と入力 -->
<source srcset="" type="image/">
<!-- src:z と入力 -->
<source sizes="" srcset="">
<!-- src:zt と入力 -->
<source sizes="" srcset="" type="image/">

<!-- tarea と入力 -->
<textarea name="" id="" cols="30" rows="10"></textarea>

<!-- video と入力 -->
<video src=""></video>
```

### JavaScript

```js
// 例）
// e と入力
console.error();

// foreach と入力
array.forEach(element => {
});

// for と入力
for (let index = 0; index < array.length; index++) {
  const element = array[index];

}

// forin と入力
for (const key in object) {
  if (object.hasOwnProperty(key)) {
    const element = object[key];

  }
}

// forof と入力
for (const iterator of object) {
}

// function と入力
function name(params) {
}

// if と入力
if (condition) {
}

// ifelse と入力
if (condition) {

} else {

}

// import statement と入力
import {  } from "module";

// log と入力
console.log();

// new と入力
const name = new type(arguments);

// setinterval と入力
setInterval(() => {

}, interval);

// settimeout と入力
setTimeout(() => {

}, timeout);

// switch と入力
switch (key) {
  case value:

    break;

  default:
    break;
}

// trycatch と入力
try {

} catch (error) {

}

// warn と入力
console.warn();

// while と入力
while (condition) {
}
```
