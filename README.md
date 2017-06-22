<p align="right">
English description | <a href="README_RU.md">Описание на русском</a>
</p>

[Ecommerce homepage](http://arnwald.ru/portfolio/petz/)

# File structure

**File structure is generated automatically. You do not need to create anything yourself.**

Builder has the following file structure:

```
├── gulpfile.js             # gulpfile of builder
├── tars.json               # System file with info about builder
├── tars-config.js          # Config file
├── package.json            # Basic dependencies
├── .babelrc                # Config for Babel
├── .eslintrc               # Config for eslint
├── user-package.json       # User dependencies
└── tars/                   # Tasks and helpers for gulp
    └── helpers/            # Helpers
    └── tasks/              # System tasks
    └── user-tasks/         # User's tasks
    └── watchers/           # System watchers
    └── user-watchers/      # User's watchers
    └── tars.js             # Main file of the builder
└── markup/                 # The main project folder
    └── components/         # Components
    └── pages/              # Page's templates
    └── static/             # Static-files (css, js and so on)
└── docs/                   # Documentation
```

SCSS,
Handlebars

You can run this project using [TARS-CLI](https://github.com/tars/tars-cli)
