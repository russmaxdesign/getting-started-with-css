![](Getting_Started_with_CSS_handouts/headings/BYFW Lesson 2.1.jpg)

# Introduction

Welcome to lesson two of this course! This lesson is all about **CSS rules**. CSS rules can also be called **rule sets**, or even **statements**.

CSS rules are written with five different parts:

- selector
- declaration block
- declaration
- property
- value

```css
p {color: red}
```

In this case, the selector is `p`, it is going to look for any `p` element inside that document.

The declaration bloc includes the start brace, and the end brace, and anything in between.

The declaration is `color: red`.

The property is `color`.

And lastly the value is `red`.

# Exercise

Let's do an exercise in writing some basic CSS rules. Open up HTML and CSS files provided for this lesson.

The first rule we're going to write is to target the `h1` element. Start with selector:

```css
h1
```

Now the declaration block. It starts and ends with a brace that sometimes is being called curly brackets. The property we're going to write is `font-size`:

```css
h1 {font-size: 3em;}
```

Let's talk about this `3em`. The default font size in most browsers is `16px`. And `1em` is the same size as the font. So if the font size is `16px` and we're writing `3em`, it's 3 times 16 which is equivalent to `48px`.

Next up, let's style the `h2`. The property is going to be `font-family` and for the value we're going to write a **font stack**, which is three options for browsers to choose from:

```css
h2 { font-family: Helvetica, Arial, sans-serif; } 
```

First of all, the browser will look for Helvetica font on user's device. If it doesn't have that, it'll look for Arial. And if it doesn't have that, it will use some sort of sans-serif font.

Now let's style the `h3` and set its color to red:

```css
h3 { color: red; }
```

As for the value, we could also use a hexadecimal or an RGB, or even an RGBA value.

Let's try that now for `h4` and define a property of `background-color`:

```css
h4 { background-color: #ffff00; } 
```

The value is `#ffff00` here. We could write this as the keyword `yellow`, which is the same. In some cases, when all three pairs of hexadecimal value are equal, we could write it as a three hexadecimal value instead. For example, this one could be written as `#ff0`.

Next up, style our `p` element. We want to use a new property called `line-height`.

```css
p { line-height: 1.5em; } 
```

This is going to add space between each line of text inside the paragraph. `1.5em` means 16 (basic font size) times 1.5, which is equivalent to about `24px`.

Next up, let's style the `ul`:

```css
ul { border: 1px solid red; }
```

This is going to put `1px` of red border all around the element.

Now style the ordered list:

```css
ol { font-style: italic; } 
```

We use the property of `font-style` and set it to `italic`. This sets text inside the ordered list to italic.

Now style every list item:

```css
li { font-weight: bold; }
```

The last selector we'll use is the `blockquote`:

```css
blockquote { width: 20em; }
```

`20em` means 16 times 20 which is about `320px`.
