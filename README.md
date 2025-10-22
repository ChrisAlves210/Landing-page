# Launch Page

A simple landing page built with Bootstrap 5 and the Bootswatch "Flatly" theme.

## Local preview

You can use Python's built-in HTTP server to preview locally:

```bash
python3 -m http.server 8000
```

Then open:

- http://127.0.0.1:8000/launch%20page/

## Theme & assets
- CSS: `css/bootstrap.min.css` (Bootswatch Flatly v5.3.8)
- Custom styles: `styles.css`
- Hero background: add your image to `img/tokyo-street.jpg` and ensure the hero `<section>` has `hero-background-img` class.

## Structure
```
launch page/
  ├─ index.html
  ├─ css/
  │   └─ bootstrap.min.css
  ├─ styles.css
  ├─ img/
  │   └─ tokyo-street.jpg (add your photo here)
  └─ README.md
```

## GitHub
Create a new repo on GitHub, then run:

```bash
git remote add origin <YOUR_REPO_URL>
git push -u origin main
```
