# Connecting a Custom Domain to the Blog

> **The short version:** We own the domain `dependency.blog` through Strato. We need to "introduce" it to whatever blog platform we use, so that when someone types `dependency.blog` into their browser, they land on our blog.

---

## What We Have

| What | Where | Cost |
|---|---|---|
| Domain `dependency.blog` | [Strato](https://www.strato.de) (Domain Management) | ~60€/year |
| Domain `dependencybonn.de` | Strato (used for Bluesky) | included above |
| Blog platform | Currently [Hashnode](https://hashnode.com) | Free |

---

## How the Connection Works

Think of it like giving two people each other's phone numbers so they can talk:

1. **Tell the blog provider your domain address**
   Go to **Strato → Domains → Domain Management** and copy the domain name (`dependency.blog`). Then paste it into your blog provider's settings — on Hashnode, that's **Settings → Domain → Custom Domain**.

2. **Tell Strato how to find the blog**
   The blog provider will give you DNS settings (a short code or address). Copy those from the blog provider and paste them into Strato's DNS configuration for `dependency.blog`.

That's it. Once both sides have each other's info, the connection is live — usually within a few minutes to a few hours.

> 💡 Every blog provider has slightly different instructions for step 2, but the idea is always the same: swap contact info between Strato and the provider.

---

## Why We Might Switch from Hashnode

Hashnode is **free**, which is why we started there. But it has a big drawback: it's built for software developers. The public feed is wall-to-wall programming tutorials and AI posts — not exactly the neighbourhood for a humanities research centre.

When visitors browse Hashnode's main feed, our posts sit next to content that has nothing to do with us. There's no way around this.

---

## Alternatives Worth Considering

### 1. Medium  ~50€/year

The biggest name in blogging. Clean design, familiar interface, and a huge built-in audience. Several universities already have profiles here, though most post infrequently. Blog posts can appear in other people's feeds, which means **more eyes on our work**.

**Heads up:** Medium uses a paywall. Some readers without accounts may hit a limit on how many articles they can read.

---

### 2. WordPress.com  ~100€/year

Think of it as a simpler cousin of Plone. The layout options are limited — you can't redesign everything from scratch — but it's straightforward to learn. **Dani is our biggest asset here**, since she already has hands-on experience with WordPress.com.

---

### 3. WordPress.org  100€–400€/year

The industry standard. Unlike WordPress.com, this version gives us **complete control** over design, layout, and functionality. The trade-off is complexity: the software is free, but it needs to be installed on a server, which means arranging hosting and handling updates and maintenance ourselves.

Dani's WordPress.com experience helps to some extent, but even for her this would involve a significant learning curve. This is the opposite of a "less is more" approach — it's a big commitment, but could be a very rewarding one.

---

### 4. Ghost  ~150€/year

Similar philosophy to WordPress.org, but with a more modern feel and some attractive minimalist templates out of the box. A good middle ground between control and simplicity.

---

## Quick Comparison

| Platform | Yearly Cost | Ease of Use | Design Control | Built-in Audience | Good Fit for Academia? |
|---|---|---|---|---|---|
| **Hashnode** | Free | ✅ Easy | ⚠️ Limited | ❌ Tech/dev only | ❌ |
| **Medium** | ~50€ | ✅ Easy | ⚠️ Limited | ✅ Large & diverse | ⚠️ Paywall issue |
| **WordPress.com** | ~100€ | ✅ Moderate | ⚠️ Moderate | ❌ None | ✅ |
| **WordPress.org** | 100–400€ | ❌ Hard | ✅ Full | ❌ None | ✅ |
| **Ghost** | ~150€ | ⚠️ Moderate | ✅ High | ❌ Small | ✅ |

> **Remember:** Whichever platform we choose, the domain connection process (Strato ↔ provider) works the same way. We just follow the new provider's DNS instructions.