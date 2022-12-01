# Generating the Webpages

The current working directory must be the root folder of this repository, to work properly.

```bash
cd ~/dev/necrominis.github.io
python3 .builder/main.py
```

## Arguments

### Verbose

The following are identical syntaxes for the verbose argument.

```bash
python3 .builder/main.py -v
python3 .builder/main.py -verbose
python3 .builder/main.py --verbose
```

Prints out the website URL and the absolute filepath of every page's `index.html` during generation, in addition to the page's relative path.

### Silent

The following are identical syntaxes for the silent argument.

```bash
python3 .builder/main.py -s
python3 .builder/main.py -silent
python3 .builder/main.py --silent
```

Hides the printing of every page during generation, leaving only a starting and finished print-out.

### Clean

**_This argument is planned but not implemented yet!_**

The following are identical syntaxes for the clean argument.

```bash
python3 .builder/main.py -c
python3 .builder/main.py -clean
python3 .builder/main.py --clean
```

Deletes all nonessential files, before generating the new website files, in order to clear out any files that would no longer exist when rebuilding.

### Directory

**_This argument is planned but not implemented yet!_**

The following are identical syntaxes for the directory argument.

```bash
python3 /path/to/nectominis.github.io/.builder/main.py -d "/path/to/nectominis.github.io/"
python3 /path/to/nectominis.github.io/.builder/main.py -dir "/path/to/nectominis.github.io/"
python3 /path/to/nectominis.github.io/.builder/main.py -directory "/path/to/nectominis.github.io/"
python3 /path/to/nectominis.github.io/.builder/main.py --dir "/path/to/nectominis.github.io/"
python3 /path/to/nectominis.github.io/.builder/main.py --directory "/path/to/nectominis.github.io/"
```

Changes the current working directory within the script to the given path. The path must lead to this repository's root folder in order to work.

# To-Do

## Features

* Add page footer.
* Create and add icons for the properties: created, tags, manufacturers, and modelsS.
* Implement the clean argument's functionality.
* Implement the directory argument's functionality.

## Code

* `build_paints_used_html()`
* `build_paints_article_content_html()`
* `build_paint_article_content_html()`
* `build_supplies_article_content_html()`
* `build_supply_article_content_html()`
* `build_gallery_article_content_html()`
* `build_home_article_content_html()`