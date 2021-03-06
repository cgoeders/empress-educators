# **HTML and semantic tagging**

!!! Summary 
    Use HTML elements correctly.

Use HTML elements for the purposes they were designed for. For example, when you give the title of a standalone document (such as a book or a movie), mark it with a `<[cite](https://html.spec.whatwg.org/multipage/semantics.html#the-cite-element)>` element. For more information about semantic tagging, see the [Semantics, HTML, XHTML, and Structure](http://brainstormsandraves.com/articles/semantics/structure/) document on the Brainstorms & Raves site.

In situations where there are no semantically relevant HTML elements (such as italicizing thoughts or ship names), use `<[i](https://html.spec.whatwg.org/multipage/semantics.html#the-i-element)>` or `<[b](https://html.spec.whatwg.org/multipage/semantics.html#the-b-element)>` elements, as specified in the HTML spec.

The flip side of semantic tagging is that you shouldn't use semantic elements to achieve specific visual results. For example, don't use frames or tables for layout; instead, use your site's standard CSS stylesheet to lay out the page.

Similarly, don't use the heading elements (`<h1>`, `<h2>`, etc.) to visually style text; use those elements for hierarchically structured headings, and use CSS for visual style.

And the `<[em](https://html.spec.whatwg.org/multipage/semantics.html#the-em-element)>` element indicates emphasis, not italics per se. Don't use it to italicize something that isn't meant to be emphasized; use `<i>` for that. Similarly, the `<[strong](https://html.spec.whatwg.org/multipage/semantics.html#the-strong-element)>` element indicates strong importance, not boldface per se. To bold a word that doesn't merit strong importance, use the `<b>` element.

___

### **Use section elements**

Surround each section of a page with opening and closing `<section>` elements.