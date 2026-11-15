# DataTalks.Club Academy Build Log

I'm building DataTalks.Club Academy for experienced developers. This log records the decisions and the reasons behind them.

[Read the build log](https://alexeygrigorev.com/academy-build-log/).

Entries are in reverse chronological order, newest first:

- [15 November 2026: Simple Signup Emails and a Home for the Academy](entries/2026-11-15.md)
- [14 November 2026: Finding the Audience and Testing Two Tracks](entries/2026-11-14.md)
- [13 November 2026: Why I'm Starting an Academy](entries/2026-11-13.md)

## Site

GitHub Pages builds this site with Jekyll from the root of `main`. Each daily Markdown file has its own title, description and permanent URL. The shared layout supplies social preview tags and a default image.

To add a day, create `entries/YYYY-MM-DD.md` with `title`, `description`, `log_date` (quoted) and `permalink` in its front matter. The site index and previous/next links update automatically. Keep this README index newest first.

Every entry should link the public artifacts it mentions and include relevant, privacy-safe images. Verify links return 200 or a normal public page without authentication; confirm repositories are public before linking PRs. Use the live canonical academy URL. Do not link private repositories, internal hosts or tools, Hub, or Grok Bot.

Inspect every image before publishing. Exclude other people's faces, names, avatars, contact details, chats and identifying survey answers; skip interview chats entirely. Aggregate charts are fine. Exclude prices, budgets and internal tools. Crop or blur uncertain areas, and skip anything still in doubt. Capture live pages with a clean headless browser, without reading browser profiles or cookies. Keep raw exports and source screenshots outside the repo. Save approved images as WebP (quality about 80, maximum width 1400) under `assets/images/YYYY-MM-DD/`, with meaningful alt text and captions stating the capture date when it differs from the entry date.

Keep the text privacy filter too: no private identifiers, machine names, emails, tokens, internal URLs, prices or budgets.
