# responsive-css-grid 
This is a simple responsive grid script. You can divide your page into twelve equal parts. The smallest block, class name is `one-block`. And the next one is `two-block`. Other names are inclemently changing till the `twelve-block`. You can use different combination of these blocks to fill each rows as your prefer and the requirement. You will make a good sense after doing the following steps. Try it. It is quite simple. :)  

### Available class names(Blocks)
```sh
<div class="block one-block">
<div class="block two-block">
<div class="block three-block">
<div class="block four-block">
...
...
<div class="block twelve-block">
```

### How to use

Include the `responsive-css-grid.css` file in the header part of your HTML page.
```sh
<link rel="stylesheet" type="text/css" href="parth/to/css-responsive-grid.css"/>
```

Add the html into the `body` section. 
```sh
<div class="wrapper">
	<div class="row">
		<div class="block one-block">Your content ...</div>
		<div class="block one-block">Your content ...</div>
		<div class="block one-block">Your content ...</div>
		......
		.....
		<div class="block one-block">Your content ...</div>
	</div>
</div>
```

> Please make sure that the total of the blocks need to be eaqual to twelve.


**Thats all. Let's see the code in discreptive view.**

Open a `wrapper` class first. 
```sh
<div class="wrapper"></div>
```
> The default max-width(Maximum width) is 1200px. You can change this value or overwrite using css, if you want to change max > width of your site. And next,


Add a `row` class inside the `wrapper`
```sh
<div class="wrapper">
	<div class="row"></div>
</div>
```


Now you can add your preferred grid structure in to the `row`. The total of the blocks needs to be equal to twelve(12).  
```sh
<div class="wrapper">
	<div class="row">
		<div class="block one-block">Your content ...</div>
		<div class="block one-block">Your content ...</div>
		<div class="block one-block">Your content ...</div>
		......
		.....
		<div class="block one-block">Your content ...</div>
	</div>
</div>
```

**Enjoy it (y)**


### License 
This projected is licensed under the terms of the MIT license
