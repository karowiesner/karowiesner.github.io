# karowiesner.org

Personal academic website of Karoline Wiesner, built with Jekyll for GitHub Pages.

## Editing content
Most updates are small edits to text files in `_data/`, made directly on github.com (pencil icon):

| What | File |
|---|---|
| News (newest first; home page shows the top 5) | `_data/news.yml` |
| Group members and alumni | `_data/group.yml` |
| Interviews, podcasts, talks | `_data/media.yml` |
| Positions, education, editorial roles | `_data/cv.yml` |
| Menu | `_data/navigation.yml` |
| Email, photo, book cover, reading sample | `_config.yml` |

Page texts are in the `.html` files in the top folder (index, research, publications, group, teaching, what-is-a-complex-system, media, about).

Images go in `assets/img/`, PDFs in `assets/files/`.

## Publishing
GitHub Pages builds the site automatically on every commit to the main branch
(Settings → Pages → Deploy from a branch → main / root).

## Custom domain (later, not yet)
When the site is approved: add a `CNAME` file containing `www.karowiesner.org`,
set the custom domain in Settings → Pages, and update DNS at the domain registrar.
