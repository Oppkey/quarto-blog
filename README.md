# Quarto Project hosted with Netlify

## Project Setup

The .gitignore of this project is setup to ignore `_site/` and `.quarto/`

![gitignore](image.png)

- `_site/` is also known as `docs/` in other quarto projects

- `_site` was specified as netlify publish directory on the website 


## Notable findings

- Only the freeze directory is needed when hosting on netlify using the [plugin](https://github.com/quarto-dev/netlify-plugin-quarto)

- Can use the "local only" ignoring files strategy. Each person adds `_freeze/` to the exclude file and only have one person who is reponsible for rendering and uploading to netlify

![exclude](image-1.png)

- When adding a new post these are the files that are added and the ones that are modified, I *manually* modified README.md and _quarto.yml

![modified](image-2.png)