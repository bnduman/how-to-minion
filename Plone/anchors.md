# Using Anchors in Plone

## What are Anchors?

Anchors are links that automatically scroll to a specific section of a page when clicked. They're useful for long pages with multiple sections—readers can jump directly to the content they need.

**Example:** We make heavy use of it on this page: [International Partners of the BCDSS](https://www.dependency.uni-bonn.de/en/research/strategic-partners/international-institutional-cooperation-partners)
---

## How Anchors Work

1. **Create an anchor point** on the section you want to link to
2. **Create a link** that points to that anchor
3. When someone clicks the link, the page automatically scrolls to that section

---

## Steps

### 1. Create an Anchor Point

1. In Plone edit mode, click on the heading or text where you want the anchor
2. Click the **anchor icon** in the toolbar (looks like a link/chain symbol)
3. Give the anchor a **name** (no spaces, use hyphens: `section-one`, `introduction`, etc.)
4. Click **OK**
[screenshot](plone-images/anchor1)
### 2. Create a Link to the Anchor

1. Select the text you want to make clickable
2. Click the **link icon** in the toolbar
3. On the right hand side, find "Show Anchors"
4. If you have succesfully created anchor/s, they will appear here as a list
[screenshot](plone-images/anchor2)
[screenshot](plone-images/anchor3)

### 3. Save

Save your page. The link will now scroll to the anchored section when clicked.

---

## Tips

- Anchor names best be **lowercase** and use **hyphens** instead of spaces
- Test your links after saving to ensure they scroll correctly
- You can directly link an anchor buy adding a hashtag and the anchor ID to the link. For example, the link is normally https://www.dependency.uni-bonn.de/en/research/strategic-partners/international-institutional-cooperation-partners. If you want the user auto-scrolled to Beniba Centre for Slavery Studies, the link becomes https://www.dependency.uni-bonn.de/en/research/strategic-partners/international-institutional-cooperation-partners#Beniba. we added #Beniba, which was the anchor ID that I had set.