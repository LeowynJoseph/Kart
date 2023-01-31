
# SCSS Snppet

**Write less, write better**

Overwiew

<br/>

<img src="https://uupload.ir/files/cuep_scss-ed.gif" alt="Css Snippet" width="667px"/>

<br/>
<br/>

> ## List of snippets
>
> Note: To avoid possible problems with the sign @ We use it at the beginning of all commands

```scss
/* Write $ */

$property: value;
```
```scss
/* Write @import  */

@import "Path";
```
```scss
/* Write @if  */

@if Condition{
	
}
```
```scss
/* Write @ifelse  */

@if  Condition{
	
} @else {
	
}
```
```scss
/* Write @ifelseif  */

@if  Condition {
	
} @else if Condition {
	
} @else {
	
}
```
```scss
/* Write @charset  */

@charset "UTF-8";
```
```scss
/* Write @for  */

@for $VarName from 1 through 3 {
		
	}
```
```scss
/* Write @each  */

@each $size in $sizes {
		
	}
```
```scss
/* Write @while  */

@while $value>$base {
	
}
```









```scss
/* Write @use  */

@use 'Path';
```
```scss
/* Write @forward  */

@forward "Path";
```
```scss
/* Write @mixin  */

@mixin name {
	
}
```
```scss
/* Write @mixmin-perfix  */
@mixin name($argument-name:default) {
	 -ms-name: $argument-name;
	 -o-name: $argument-name;
	 -moz-name: $argument-name;
	 -webkit-name: $argument-name;
		name: $argument-name;
}

```
```scss
/* Write @include  */
@include mixinName;
```
```scss
/* Write @function  */
@function Name(Arguments) {
	
}
```
```scss
/* Write @function-set-colr  */
@function set-color ($color){
		@if (lightness(color)>=50) {
				@return #fff
		}@else{
				@return #000
		}
}
```
```scss
/* Write @return  */
@return mix(returnVars);
```
```scss
/* Write @extend  */
 @extend classOrIdOrEl;
```
```scss
/* Write @error  */
  @error "Message With Vars e.g #{$property} ";
```
```scss
/* Write @warn  */
  @warn "Message With Vars e.g #{$property} ";
```
```scss
/* Write @debug  */
  @debug "Message With Vars e.g #{$property} ";
```

> ### If You Want Access To All Property Of Css, Please Install My Css Snippet https://marketplace.visualstudio.com/manage/publishers/miladfathy/extensions/css-snippet-complate/hub
> ### ! Color Theme Used: Placard

> If there is a problem, I will be happy to let you know; Because I am a novice 😄

**Enjoy!**
