# heygrid
=======


####**Useful Responsive Grid**


A responsive grid developed in [`SASS`](http://sass-lang.com/) for use as a base in web projects. Ready for all devices (computers, laptops, tablets and smartphones) and any kind of display.

##Documentation
---------------
[See documentation in English](http://heygrid.com/)

[Ver documentación en Español](http://es.heygrid.com/)

**Step 1**: Download  hey grid  files by using any of the methods below.


Git:
```git
git clone git@github.com:siancore/heygrid.git
```

Bower: 
```bower
bower install --save heygrid
```


##Include files
-----------------

**Step 2**:  Include  hey grid files.

Inside of  `<head>`  of the HTML document

```html
<link type="text/css" rel="stylesheet" href="css/hey-grid.css">
```

or inside style sheets

```css
@import url("css/hey-grid.css");
```


##Configuration

**Step 3**:  Compress HTML , this grid is made using  css  potential and goods. It is important to compress the HTML document and remove any whitespace between tags.

You can do this in several ways, depending on the language you use.

Django, Twig Symfony

```django
{% spaceless %}
<body>
	# Code 	
</body>
{% endspaceless %}
```

PHP:
```php
function spaceless($buf){
	return str_replace(array("\n","\r","\t"),'',$buf);
}
```

html - Javascript: After tag body
```html
<script>document.body.innerHTML = document.body.innerHTML.replace(/>\s+</g, "><");</script>
```

##Quick test

**Step 4**: Testing everything is ok.

If you did the steps above and want to know quickly if the  Grid  is correctly configured, simply paste the following HTML code after tag. is well configured, I just hit the following html after  <body>  tag.

HTML
```html
<section class="grid-columns" heygrid-debug>
	<div class="cols-4"></div>
	<div class="cols-8"></div>
</section>
```

##Using Columns
---------------

####Two Columns:

```html
<section class="grid-columns" heygrid-debug>
	<div class="cols-3"></div>
	<div class="cols-9"></div>
</section>

<section class="grid-columns" heygrid-debug>
	<div class="cols-6"></div>
	<div class="cols-6"></div>
</section>
```

####Three Columns:

```html
<div class="grid-columns" heygrid-debug>
	<div class="cols-9"></div>
	<div class="cols-2"></div>
	<div class="cols-1"></div>
</div>

<div class="grid-columns" heygrid-debug>
	<div class="cols-7"></div>
	<div class="cols-3"></div>
	<div class="cols-2"></div>
</div>
```

####Four Columns:

```html
<div class="grid-columns" heygrid-debug>
	<div class="cols-3"></div>
	<div class="cols-5"></div>
	<div class="cols-2"></div>
	<div class="cols-2"></div>
</div>

<div class="grid-columns">
	<div class="cols-5"></div>
	<div class="cols-4"></div>
	<div class="cols-2"></div>
	<div class="cols-1"></div>
</div>
```

##Using layouts


```html
<div class="grid-layout" heygrid-debug>
	<div class="layout-70"></div>
	<div class="layout-30"></div>
</div>
```

##Using Boxes


```html
<div class="grid-for-5" heygrid-debug>
	<div class="grid-box"></div>
	<div class="grid-box"></div>
	<div class="grid-box"></div>
	<div class="grid-box"></div>
	<div class="grid-box"></div>
	<div class="grid-box"></div>
	<div class="grid-box"></div>
	<div class="grid-box"></div>
	<div class="grid-box"></div>
	<div class="grid-box"></div>
</div>
```








