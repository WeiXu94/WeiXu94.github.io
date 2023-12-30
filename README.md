# Personal Website

## 🧱 Template Structure

```bash
├── archetypes/    # A piece of content that's common to all of the content on your website.
│   └── default.md
├── content/    # Where you store all the content for your website.
│   ├── assets/    # Things from LogseqGraph/assets, used in posts.
│   │   └── test.png
│   ├── pages/    # Revised Logseq pages with metadata sections for Hugo.
│   │   └── random page from logseq.md
│   ├── archives.md
│   └── search.md
├── .github/    # Define GitHub action to help deploy in one click.
│   └── workflows/
│       └── publish.yml
├── layouts/    # Where you define your layout for your website.
│   ├── partials/
│   │   └── backlinks.html    # Simulate backlinks function in Hugo.
│   └── shortcodes/
│       ├── logseq/    # Translation between Logseq and Hugo.
│       │   ├── mark.html
│       │   ├── orgCAUTION.html
│       │   ├── orgEXAMPLE.html
│       │   ├── orgIMPORTANT.html
│       │   ├── orgNOTE.html
│       │   ├── orgPINNED.html
│       │   ├── orgQUOTE.html
│       │   ├── orgTIP.html
│       │   └── orgWARNING.html
│       ├── contact.html
│       ├── hint.html
│       └── search.html
├── themes/    # Where you can apply pre-build themes or your own theme.
│   └── random-theme/   # In this repo, PaperMod is the default theme.
├── config.yml    # The main settings page for your website.
└── .gitignore    # This is to prevent unwanted files be tracked by Git.
```