<!-- section-title: Instalation -->

# Instalation

Make a new empty project with:

```sh
npm init -y
```

Add the following commands under the `scripts` section:

```json
  "scripts": {
    "init": "fusuma init",
    "start": "fusuma start",
    "start-prod": "npm run build && fusuma start-prod",
    "build": "fusuma build",
    "deploy": "npm run build && fusuma deploy",
    "export-pdf": "npm run build && fusuma pdf"
  }
```

Install the fusuma dev dependency with `npm install -D fusuma`.

And finally execute `npm run init`. You will get a basic Fusuma project with:

```sh
├── .fusumarc.yml
├── .github
│   └── workflows
│       └── fusuma.yml
├── package.json
├── slides
│   └── 0-slide.md
└── style.css
```

You can test it with `npm run start` and check the first slide `0-slide.md`.
