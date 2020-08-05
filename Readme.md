<!-- 
1. Headers 
2. Emphasis
3. write a text
4. Lists
5. Images
6. Links
7. Code
8. Blockquotes
9. Tables
10. Horizontal Rule
11. Inline HTML
12. Emojis
-->

# Heading1

## Heading2 ##

### Heading3

#### Heading4

##### Heading5

###### Heading6

Alternativ Heading with h1 sizes
================================

Alternativ Heading with h2 sizes
--------------------------------

<!-- 
Different levels of headings start lines with a # to create headings
Multiple `##` in a row denote smaller heading sizes.
You can use one `#` up to `######` six for different heading sizes.

NOTE: '# Heading1' and Alternativ Heading1 is already underlined as default.
-->

<!--
There are 3 different styles for Heading
1.    # ATX style H1

2.    ## Closed ATX style H2 ##

3.    Setext style H1
      ===============

It warns us to be consistent about styling.
NOTE : Consistent formatting makes it easier to understand a document.
-->





# Emphasis

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~





# Text

It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)





# Lists

Sometimes you want numbered lists, aka Ordered List:

1. One
2. Two
3. Three
    1. Three_1
    2. Three_2
    3. Three_3
4. Four
5. Five
    1. And if you have sub points, put four spaces before the number
    2. Like this

Sometimes you want bullet points, aka Unordered List:

* Start a line with a star
* Countries!
  * USA
  * England
  * Germany
    * NRW
    * Düsseldorf
    * Hamburg
      * Hamburg Bezirk 1
      * Hamburg Bezirk 2

Alternatively,

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or plus sign or star:
  - Like this
  - And this
  + And also this
  + this as well
+ another
  - item 1
  + item 2

<!--
It warns us to be consistent about styling.
NOTE : Consistent formatting makes it easier to understand a document.
-->



# Images

###### Inline Style

![Smile Logo](./smile.png "Title Text - Smile")

###### Reference Style

![great paris][paris]

[paris]: https://i.pinimg.com/564x/0c/f8/de/0cf8dec41dccd1ecde9e80f22032391a.jpg "Logo Title Text 2"


<!--
Inline- Style :

    ![Alt Text](url "title_text")

Reference-Style :

    ![Alt Text][logo]
    ******** dont forget line break here
    [logo]: https://..... "Title text here"
    
    
-->


# Links

###### Inline-Style Link

[Google Link](https://www.google.com)

[Google Link with Title](https://www.google.com "Google webpage")

[Markdown Guide](https://www.markdownguide.org/basic-syntax/)

<!--
- Exclamation mark is the difference from images
-->



# Code

If you have inline code blocks in a text, wrap them in backticks: 
* `var example = true`.  

* Let's add `<div>` element here.

If you've got a longer block of code, you can indent with four spaces:

    if (isAwesome){
    return true
    }

GitHub also supports something called code fencing, which allows for multiple lines without indentation:

```
if (isAwesome){
return true
}
```

And if you'd like to use syntax highlighting, include the language:

```javascript
if (isAwesome){
return true
}
```


# Blockquotes

As Sophocles said:
> Success is dependent on effort.

![Sophocles](https://psychologypedia.org/wp-content/uploads/2019/10/Sophocles-1068x583.jpg)

Sophocles was an ancient Greek dramatist who lived from about 496 to about 406 BCE. 

###### Nested Blockquotes

---

> Blockquotes can be nested. 
>
>> Add a >> in front of the paragraph you want to nest.



# Tables

| Tables        | Are           | Cool  |
| ------------- |---------------| ------|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


---

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

<!--
There must be at least 3 dashes separating each header cell. The outer pipes (|) are optional, You can also use inline Markdown.
-->



# Horizontal Rule 

--- 
***
___

<!--
Hyphens
Asterisks
Underscores
-->



# Inline HTML

You can also use raw HTML in your Markdown, and it'll mostly work pretty well.

<dl>
  <dt>Countires</dt>
    <dd>England</dd>
    <dd>Germany</dd>
    <dd>Belgium</dd>

  <dt>Cities in Germany</dt>
    <dd>Köln</dd>
    <dd>Hamburg</dd>
    <dd>Berlin</dd>
</dl>



<img src="https://im.haberturk.com/2018/05/03/ver1552558838/2366092_1024x576.jpg" alt="Düsseldorf"/>

_A photo from Düsseldorf_# Markdown_Example


# Emojis

:+1:

:dash:

:heart:
