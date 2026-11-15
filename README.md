# DataTalks.Club Academy Build Log

I'm building DataTalks.Club Academy for experienced developers. This log records the decisions and the reasons behind them.

[Read the build log](https://alexeygrigorev.github.io/academy-build-log/).

Entries are in chronological order, newest last:

- [13 November 2026: Why I'm Starting an Academy](entries/2026-11-13.md)
- [14 November 2026: Finding the Audience and Testing Two Tracks](entries/2026-11-14.md)
- [15 November 2026: Simple Signup Emails and a Home for the Academy](entries/2026-11-15.md)

## Site

GitHub Pages builds this site with Jekyll from the root of `main`. Each daily Markdown file has its own title, description and permanent URL. The shared layout supplies social preview tags and a default image.

To add a day, create `entries/YYYY-MM-DD.md` with `title`, `description`, `log_date` (quoted) and `permalink` in its front matter. The site index and previous/next links update automatically. Keep this README index in the same chronological order.
