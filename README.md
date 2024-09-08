# IlyaBOT.space

Sources for ilyabot.space build with Material Docs (Markdown, CSS, Images etc)

## Installing Material Docs

#### Install on Linux:
```bash
python -m venv venv # Use only once, to create
                    # a virtual environment
source venv/Scripts/activate
venv/bin/pip install -r requirements.txt --break-system-packages
```
#### Install on Windows:
```bash
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
```

## Run Material Docs in live preview

```bash
mkdocs serve --watch-theme
```

## Build static site

```bash
mkdocs build
```
Then push `site/` folder to `pages` branch