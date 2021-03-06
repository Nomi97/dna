---
title: Spinner
url: /docs/components/feedback/spinner
category: component
primaryKeywords: ys-spinner css feedback loading
secondaryKeywords: indicator spin interaction rotate
---

<nav class="element-navigation">
  <dl class="element-navigation__list">
    <dt class="element-navigation__title">Table of contents</dt>
    <dd class="element-navigation__item">[Examples](#examples)</dd>
    <dd class="element-navigation__item">[HTML Guidelines](#html-guidelines)</dd>
    <dd class="element-navigation__item">[UX and Design Guidelines](#ux-and-design-guidelines)</dd>
  </dl>
</nav>

# Example
## Spinner
<div class="element-preview">
  <div class="element-preview__inner">{{render '@spinner'}}</div>
</div>

```html
{{render '@spinner'}}
```

# HTML Guidelines

# UX and Design Guidelines
Try to always keep spinners in page and not in overlays.
If a spinner is triggered by a button, place the spinner in the button, and disable the button while the spinner is visible.

If only a portion of a page is displaying new content or being updated, place the spinner in that part of the page.

If you are unsure where to place the spinner, place it where you want the user's attention to be when loading is finished.
Only show a spinner if the expected wait time is more than a second.

