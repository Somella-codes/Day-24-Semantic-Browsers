# Day-24-Semantic-Browsers 🌐

## List of Major Web Browsers 

**Challenge:** Responsive Web Design - Semantic HTML  
**Platform:** freeCodeCamp  
**Status:** ✅ Completed


### What I Did Today
Built a structured "List of Major Web Browsers" using semantic HTML description lists. 
This was the final step of the challenge where I had to add the `Arc` browser with proper `<dt>` and `<dd>` tags.

### Key Concepts Learned
**Semantic HTML matters.**
- `<dl>` = Description List container
- `<dt>` = Description Term. This is the "title" or "name"
- `<dd>` = Description Details. This is the explanation

Why not just use `<ul>` and `<li>`?  
Because semantic tags tell browsers and screen readers *what* the content means, not just how it looks. 
This improves:
1.  **Accessibility** - Screen readers can navigate it better
2.  **SEO** - Search engines understand the structure
3.  **Maintainability** - Other devs can read your code easily

Real world use cases: FAQs, glossaries, product specs, dictionaries.

### The Code
```html
<dl>
  <dt>Google Chrome</dt>
  <dd>This is a free web browser developed by Google and first released in 2008.</dd>

  <dt>Firefox</dt>
  <dd>This is a free web browser developed by the Mozilla Corporation and first created in 2004.</dd>

  <dt>Safari</dt>
  <dd>This browser was developed by Apple and is the default browser for iPhone, iPad and Mac devices.</dd>

  <dt>Brave</dt>
  <dd>This is a free web browser first released in 2016 that is based on the Chromium web browser.</dd>

  <dt>Arc</dt>
  <dd>This is a free Chromium based web browser first released in 2023 by The Browser Company.</dd>
</dl>
