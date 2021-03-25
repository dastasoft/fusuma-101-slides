<!-- section-title: Distribute -->

# Distribute

Apart from running the project on your localhost, which can be valid in some cases with `npm run start-prod` script. You can distribute your slides in two ways.

---

## Make a PDF

If you want to share your slides without hosting you can export them as a PDF. (Be careful with your React Components because they will stop working).

To make the export to PDF first install the dependency:

```sh
npm install -D @fusuma/task-pdf
```

Once installed, run the `npm run export-pdf` script.

In the root of your project you will get a `slide.pdf` file with your slides.

---

## Deploy

You can build the project as a regular React project with `npm run build` and this will create the static files like in any other React project, with that you can deploy to any service like [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/), you only need to configure those services to run the `build` script every time you perform a git push.

This option is very handy if you want to share your slides directly from the browser.
