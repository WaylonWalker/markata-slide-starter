---
date: 2022-11-12 18:38:11
templateKey: blog-post
title: About Markata Slides
published: True

---

## slide zero

slides use normal markdown syntax.

``` markdown

### subheading

description

```

!!! Note

    You can make use of admonitions to make content stand out.

    ``` markdown

    !!! Note

        you can make notes, warnings, info

    ```
??? "👉 pymdown-extensions"
    you can even use pymdown-extensions

    ``` markdown
    ??? "👉 pymdown-extensions"
        you can even use pymdown-extensions
    ```

## slide one

* slides are split on h2 (##)
* slides numbers get appended to the articles slug `presentation-1/slide-1`
* slide numbers are zero indexed.

## slide two

### Get Started

Use the `markata new` command to generate a new template.

``` bash
pipx run markata new slides
```

## hotkeys

when you are on a route with `slide-#`, you can use `j` and `k` to navigate between slides.

## The presentation is still a page

[[presentation-1]] is rendered entirely on its own page just as any normal post would be.


