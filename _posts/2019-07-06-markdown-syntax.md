---
layout: post
title: "Markdown syntax"
comments: true
---

# HEADERS
```
# This is an h1 tag
## This is an h2 tag
###### This is an h6 tag
```
# This is an h1 tag
## This is an h2 tag
###### This is an h6 tag

# LISTS
## Unordered
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b

## Ordered
```
1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b
```
1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b

# IMAGES
```
![Screenshot home page](/images/screenshot-homepage.png)
Format: ![Alt Text](url)
```

![Screenshot home page](https://raw.githubusercontent.com/qndev/jekyll-theme/master/images/screenshot.png)

# EMPHASIS
```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

# LINKS
```
http://github.com - automatic!
[GitHub](http://github.com)
```
http://github.com - automatic!
[GitHub](http://github.com)

# Blockquotes
```
As Grace Hopper said:

> I’ve always been more interested
> in the future than in the past.
```
As Grace Hopper said:

> I’ve always been more interested
> in the future than in the past.

# Syntax highlighting

###### Rouge
```javascript
function test() {
console.log("look ma’, no spaces");
}
```

```java
class HelloWorldApp {
    public static void main(String[] args) {
        System.out.println("Hello World!"); // Display the string.
    }
}
```

###### Gist

{% gist e8ef18051d1b0277f2d7cf78c3fd96fe test.js %}

{% gist 4914f8921f09863f7c3ea2ebbb02206a HelloWorld.java %}

# Task Lists
```
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
```
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)

# EMOJI
```
GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:
```
GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:
