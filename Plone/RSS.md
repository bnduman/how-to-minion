# Using RSS in Plone

## What is RSS?

**RSS** stands for "Really Simple Syndication." It's a way to automatically pull content from other websites and display it in your Plone site.

## How It Works

RSS reads items from a web link and displays them in a clickable format; one item per row. Each item links back to its original source.

**Example:** If you add an RSS feed from a blog, Plone will automatically list every new article as a clickable item, linking directly to the full article on the original blog.

---

## Steps

### 1. Find the RSS URL

Locate the RSS feed URL for the website you want to link to.

- **Built-in RSS:** Many websites have an RSS function built-in (look for an RSS icon or "Subscribe" button)
- **No built-in RSS:** Some websites require a third-party RSS generator tool
- Usually, it is as simple as googling "Deutsche Welle RSS" to find what you are looking for

The URL should end in `.xml` format (example: `https://rss.dw.com/xml/rss-en-all`)

### 2. Add RSS to Plone

1. In Plone, select the **RSS** option
2. Paste the RSS URL into the designated field
3. Save

Plone will now automatically pull and display the latest items from that RSS feed.

---
![Screenshot](/plone-images/howto%20rss1.png)
![Screenshot](/plone-images/howto%20rss2.png)
![Screenshot](/plone-images/howto%20rss3.png)
## Tips

- Always verify the RSS URL ends with `.xml`
- Test the feed after adding it to make sure items are displaying correctly
- As of 24.03.26 Hashnode RSS is still not working