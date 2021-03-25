<!-- section-title: Themes -->

# Themes

You can modify the whole look and feel with CSS, but by default Fusuma comes with five different themes.

Open the `style.css` file and import the css for the theme you want, the possibilities are:

```css
@import "@fusuma/client/assets/style/themes/babel.css";
@import "@fusuma/client/assets/style/themes/default.css";
@import "@fusuma/client/assets/style/themes/node.css";
@import "@fusuma/client/assets/style/themes/pop.css";
@import "@fusuma/client/assets/style/themes/webpack.css";
```

Test the different themes and if you need some fine tuning add the classes you need in the `style.css` to modify the theme or create a new one.

If you want to create a new one, change the colors of the following css variables:

```css
:root {
  --color-title: #e53498;
  --color-base: #1c1235;
  --color-background: #e5e5e5;
  --color-link: #6f4dca;
}
```
