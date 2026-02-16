# Md_Quick_Reference



## Basic Syntax
---

- This is a basic markdown reference guide for quick reference.

---
## Heading IDs

# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6
---

## Paragraphs 

- I am watching Beauty and the Beast.

I think the movie is very entertaining and telling.
My next movie is 'I Am a Robot.' 
 * Notice line breaks use two or more spaces (commonly referred to as “trailing whitespace”) for line breaks in nearly every Markdown application.
---

## Bold 

> Add two asterisks or an underscore before or after the word or sentence.
>
- The word is **Emotions**.
>
---
## Italic

> Add one asterisk before and after a word or sentence.
- The word in *italic*.
  
---

## Bold and Italic

> Add three asterisks.
- This word ***terminal*** has both **bold** and *italic* asterisks.

---

## Blockquotes

> Add > infront of a paragraph.
> This applies to multiple paragraphs. 

## Nested Blockquotes

Add >> in front of a paragraph.
> Let us perform an example for nested blockquotes.
>> This sentence is nested.

## Blockquotes With Other Elements

> #### The quarterly results look great!
>
> - Revenue was off the charts.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

---

## Lists
- Items can be organized into ordered and unordered lists.
1. First item
2. Second item
3. Third item
4. Fourth item
5. 
### Indented

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

## Unordered Lists

- First item
- Second item
- Third item
- Fourth item
---
* First item
* Second item
* Third item
* Fourth item

---
+ First item
+ Second item
+ Third item
+ Fourth item

---

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

---

- 1968\. A great year!
- I think 1969 was the second best.

---
## Adding Elements in Lists
### Paragraphs

* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

---

## Blockquotes
* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.

* And here's the third list item.
  
---

## Code Blocks

1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

---
## Images
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](san_juan_maoutain.png)

3. Close the file.

---

## Horizontal Rules
To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.

***

---

---
## Links

- Search engine such as [Duck Duck go](https://duckduckgo.com)

---
## Adding Titles

You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in quotation marks after the URL.

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
The rendered output looks like this:

---

## URLs and Email Addresses

To quickly turn a URL or email address into a link, enclose it in angle brackets.

<https://www.markdownguide.org>
<fake@example.com>

---

## Formatting Links

To emphasize links, add asterisks before and after the brackets and parentheses. To denote links as code, add backticks in the brackets.

I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).

---

## Formatting Links

[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)

---

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.

---

## Images

+ Add an exclamation mark(!).
+ ![The San Juan Mountains are beautiful](/assets/images/san-juan-mountains.jpg "San Juan Mountains")
+ 

---

## Linking Images
To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

---

## Escaping Characters

To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.

\* Without the backslash, this would be a bullet in an unordered list.


## HTML

To use HTML, place the tags in the text of your Markdown-formatted file.

This **word** is bold. This <em>word</em> is italic.
