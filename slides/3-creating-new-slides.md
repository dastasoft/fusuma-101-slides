<!-- section-title: Creating new slides -->

# Creating new slides

It's as easy as creating a new markdown file in the `slides` folder. The order of the slides will be numerical and then alphabetical.

---

## Modifying the first slide

Inside the `0-slide.md` you can see the following content:

```md
<!-- classes: title -->

# Hello😃

<!-- block-start: grid -->
<!-- account: twitter, your-account-name -->
<!-- block-end -->

---

<!-- section-title: Bye👋 -->

## Bye👋
```

Let's look at some of the syntax on that slide:

- **classes** allows you to include CSS classes that you will declare in the `style.css` file.
- **block-start** / **block-end** allows you to include CSS classes to that block.
- **account** generates a class name (in that example `account-twitter`) an icon and the link for that social network.
- **---** you can divide slides with that, the content after that will become a new slide.
- **section-title** declares a title for your file, it will be placed in the sidebar and in the table of contents.

There are also other tags available to you.
