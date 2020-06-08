# Basic Markdown

## Create a markdown file by saving as a .md file.

## Headings
To create a heading use a # at the start of a line. The number of #’s you use illustrates the size of the heading you want. The greater the number is #’s the smaller the heading.

Remember to include a space between the # and the heading.

## Bold
Use ** before and after a word of phrase to make it **bold**.

## Italic
Use * before and after a word or phrase to make it *italic*.

## Bold and Italic
Use *** before and after a word or phrase to make it ***bold and italic***.

Don’t include a space in between the *’s and the words otherwise it won’t pick it up.

## Blockquotes
Use > at the start of each line that you want to be included in a blockquote. 

To include a quote within a quote use >> at the start of the lines.

## Numbered Lists

Use 1. to start a numbered list. Followed by 2. on the next line and so on.

1. item one
2. item two

## Bullet List
Use - to start a bullet list.

* item a
* Item b
    
    Use four spaces or tab to include content under a list item.

## Code
To denote a word or phrase as code, enclose it in backticks (`).
If you want to use backticks as formatting and don't want the word of phrase to be converted to code, use double backticks (``) at the start and end of the word or sentence.

## Code Blocks
To create code blocks, indent every line of the block by at least four spaces or one tab.

## Section dividers
Use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.

## Links
To create a quick link use a < at the start of the link and > at the end.

To create a fancy link, enclose the link text in square brackets and then follow it immediately with the URL in round brackets.

You can also add a tooltip to the link by adding a sentence in double quotes after the link address within the round brackets. Just separate the link and the quote by a space.

## Images
To add an image, add an exclamation mark (!), followed by alt text in square brackets, and the path or URL to the image in round brackets.
You can also add a title after the URL in the parentheses.

Use an ! Followed by square brackets with a description of the image and then round brackets with the file path to the image.
For example “![smiley face] (smileyface.png)

Because the smiley face is in the same repo as this document, a full file name is not needed.

## Linking Images
To add a link to an image, enclose the Markdown for the image in square brackets, and then add the link in round brackets.

[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

## Escaping Characters
To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.

\- Without the backslash, this would be a bullet in an unordered list.
