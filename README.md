## markdown test

# Table of contents sample

1. [Header](#header)
2. [Inline code](#inlinecode)
3. [Code block](#codeblock)
4. HTML, javascript, etc...
	1. [HTML](#html)
	2. [javascript](#javascript)
5. [Image](#image)
6. [Table](#table)
	1. [Table aligned](#tableaglined)

<a name="header"></a>
# H1 header
## H2 header
### H3 header
#### H4 header
##### H5 header
###### H6 header

# Line
-------------


<a name="inlinecode"></a>
# Inline code

`$ npm install marked`

<a name="codeblock"></a>
# code block 

text `<some tag>` text

<a name="html"></a>
# HTML

```HTML
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <title>Hello world!</title>
    </head>
    <body>
        <h1>Hello world!</h1>
    </body>
</html>
```

<a name="javascript"></a>
# javascript

```javascript
function test(){
	console.log("Hello world!");
}
```

<a name="image"></a>
# Image

Default
```
![](https://github.com/zackcho/zack-test/blob/master/eos_logo.svg)
```
![](https://github.com/zackcho/zack-test/blob/master/eos_logo.svg)
> Image desc

width / height
```
<img src="https://github.com/zackcho/zack-test/blob/master/eos_logo.svg" width="144" height="144">
```
<img src="https://github.com/zackcho/zack-test/blob/master/eos_logo.svg" width="144" height="144">
> Image desc

<a name="table"></a>
# Table

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

<a name="tableaglined"></a>
### Table aligned

| Left-Aligned  | Center Aligned  | Right Aligned |
| ------------- |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |



