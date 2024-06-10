# .github
Displays a public GitHub organization profile page based on [./profile/README.md](https://github.com/getlantern/.github/profile/README.md).

## structure
```
.
├── README.md          // this document
├── profile            // public profile pages are listed here
├── resources          // static assets (images, icons, etc.)
└── updater            // app and source info for updating public links and pages
    ├── README.md      // instructions and maintenance info for the updater
    ├── links.yml      // social media links
    ├── releases.yml   // release notes
    ├── outputs        // outputs for external use, like helpdesk footers
    ├── templates      // go templates for building outputs and profile pages
    ├── translations   // internationalization and common text
    ├── main.go        // application that updates READMEs and footers
    ├── main_test.go   // tests for the application
    ├── go.mod         // application support files
    └── go.sum         // application support files
```

## Making Updates
Read the [instructions](./updater/README.md) for the updater. Any changes to source information should automatically trigger an update using a GitHub action.