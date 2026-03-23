# How to Justify Text Paragraphs in Plone

## Steps

1. **Go to edit mode** for the page or text tile
2. **Click anywhere within the text** to bring up the editing options
3. **Find "Source Code"** under the "Tools" menu
4. **Add this code** at the start of each paragraph you want to justify:
```html
<p style="text-align: justify;">
```

## Note

Repeat this for each paragraph you want to justify. Make sure the opening `<p>` tag matches with a closing `</p>` tag at the end of the paragraph.

![Screenshot](/plone-images/plone-justified.png)