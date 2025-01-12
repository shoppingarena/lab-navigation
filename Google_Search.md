# How Google Search Works

Source:

- [Google Search Central](https://youtu.be/5MIAugQ17ks?si=A0xIXe7NbEa0D0bw)

- [Internationalized Resource Identifiers (IRIs)]](<https://www.rfc-editor.org/rfc/rfc3987>)
    -

- [Uniform Resource Identifiers (URI): Generic Syntax](https://www.rfc-editor.org/rfc/rfc2396)

## Crawling

## Indexing

- ## Canonicalization

**Canonical  element** is used in head section.

```html
<link rel="canonical" href="https://benesjiri.com/services/seo"/>
```

if (page has mobile version e.g. m.benesjiri.com/services/seo)
then ( add rel='alternate' link to mobile version)

```html
<link rel="alternate" media="only scree and (max-width: 640pxh)" href="https://m.benesjiri.com/services/seo"/>
```

### Use rel="canonical" [HTTP header](https://www.rfc-editor.org/rfc/rfc5988.html#section-5.1) rather then html elements

## Serving

## Anatomy of search result
