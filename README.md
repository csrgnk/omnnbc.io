# Omnnbc.io Website

This is the Omnnbc.io website repository.

---

## How to Add Social Share Buttons to Posts

To enable share buttons on posts, follow these steps:

### 1. Add share buttons HTML inside each post container (`.post-box`):

```html
<div class="share-buttons">
  <span>Share:</span>
  <a href="#" onclick="shareFacebook(event)">Facebook</a> |
  <a href="#" onclick="shareTwitter(event)">Twitter</a> |
  <a href="#" onclick="shareWhatsApp(event)">WhatsApp</a>
</div>
