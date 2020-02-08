# Semantic HTML

*Semantics* - the study of the meanings of the words
*Semantic elements* - elements that describe their meanings to both the browser and the developer
*Non semantic elements*: `<div>`, `<span>`

## Benefits of using semantic elements:

1. it will influence the page's search rankings (SEO)
2. screen readers can use them
3. the code can be easier understood by developers


# `<main>`

Represents the dominant content of the `<body>` of a document.

A document should only have one `<main>` element that doesn't have the `hidden` attribute specified. 

The content of a `<main>` element should be unique to the document .
Content that is repeated (sidebars, copyright info, site logo...) should not be included.

`<main>` doesn't contribute to the document outline, it's strictly informative. 

*Not supported in IE*

# `<section>`

Represents a standalone section, which doesn't have a more specific semantic element to represent it.
Typically, but not always, sections have a heading.
The content inside of a section is grouped (relates to a single theme).

*It is not a generic container element. When an element is needed only for styling purposes or for scripting,
authors are encouraged to use the `<div>` element instead.*

# `<article>`

The `<article>` element identifies a self-contained piece of content which could theoretically be distributed to other websites and platforms as a stand-alone unit. The `<article>` element is a good choice to contain entire blog posts, news articles, user comments and similar content.

*If the content stands alone from the rest of the page, it should be contained in an article tag. This is in contrast with the section tag which contains elements
that are related, but they are not independent from the rest of the site.*

*An article an a section can have headers and footers.*

# `<figure>`

Specifies self-contained content, like illustrations, diagrams, photos, code listings etc.

# `<figcaption>`

Represents a caption describing the conents of its parent `<figure>` element.

# `<footer>`

Defines a footer for a document or section.
Should contain information about its containing parent.
You can have several `<footer>` elements in one document.

