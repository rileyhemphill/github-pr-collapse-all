# github-pr-collapse-all

Collapse all files in a GitHub Pull Request by pasting the following command into your browser console:

```javascript
document.querySelectorAll(".PRIVATE_TreeView-item-toggle").forEach(el => el.click())
```

> **Note:** This relies on a GitHub internal CSS class (`PRIVATE_TreeView-item-toggle`) that may change without notice in future GitHub updates.