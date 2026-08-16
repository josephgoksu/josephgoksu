# CLAUDE.md

Public GitHub profile README for `josephgoksu`. Must stay public so the profile page renders.

Resume, cover letter, signatures, and bio live in the private repo `josephgoksu/personal` (`../personal`). Do not add them back here.

## Layout

```
josephgoksu/
├── README.md              # GitHub profile README
├── dynamic-images/        # Images for the profile
└── .github/workflows/     # Blog-post list updater
```

## GitHub Actions

- Runs every Monday at 1 PM UTC (also manual)
- Reads https://josephgoksu.com/feed.xml
- Writes the 4 most recent posts into README.md between the `BLOG-POST-LIST` markers

## Content updates

1. Profile copy: edit README.md
2. Blog posts: automatic, do not hand-edit the list
