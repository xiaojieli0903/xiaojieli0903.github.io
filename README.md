# Xiaojie Li — Academic Homepage

A compact, zero-dependency academic homepage for Xiaojie Li. The site is plain HTML and CSS and is ready for GitHub Pages.

## Preview locally

Open `index.html` directly, or run:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

## Publish at xiaojieli0903.github.io

GitHub reserves the root user-site URL `https://xiaojieli0903.github.io/` for the repository named exactly `xiaojieli0903.github.io` under the `xiaojieli0903` account.

To replace the current site while preserving that URL:

1. Back up or archive the existing repository if desired.
2. Push the files in this project to the root of `xiaojieli0903/xiaojieli0903.github.io`.
3. In **Settings → Pages**, choose **Deploy from a branch**, then select the publishing branch and `/ (root)`.

A differently named repository can host this source, but its default Pages URL will include the repository name. To keep the root URL while maintaining a separate source repository, use the separate repository for development and sync the finished static files to `xiaojieli0903.github.io` as the publishing repository.
