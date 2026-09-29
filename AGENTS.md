# Agent standing orders

Public GitHub profile README for `josephgoksu`. Must stay public so the profile page renders. Durable learnings: `context/`.

Resume, cover letter, signatures, and bio are **not** in this repo. They live in `../personal` (`josephgoksu/personal`, private). Do not add them back.

## Layout

```
josephgoksu/
├── README.md              # GitHub profile README
├── dynamic-images/        # Images for the profile
├── context/               # durable repo learnings
└── .github/workflows/     # Blog-post list updater
```

Git remote is `josephgoksu/josephgoksu`. The old `joeygoksu/joeygoksu` URL still redirects; do not use it in new remotes.

## Content updates

| What | How |
|---|---|
| Profile copy | Edit `README.md` |
| Blog post list | Automatic. Do not hand-edit the `BLOG-POST-LIST` block |

## GitHub Actions (blog-post list)

- Runs every Monday at 1 PM UTC (also manual)
- Reads https://josephgoksu.com/feed.xml
- Writes the 4 most recent posts into README.md between the `BLOG-POST-LIST` markers
