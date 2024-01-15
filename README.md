# ResOutput Extension For Quarto

ResOutput provides users with a custom ejs template for listing research output (publications, data, software, talsk, etc) in a quarto website.

## Installing


```bash
quarto add stefanocoretta/resoutput
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

Two dependencies (extensions) will also be installed (they are needed for the icons):

- https://github.com/stefanocoretta/osi-font
- https://github.com/mcanouil/quarto-iconify

## Using

Use `_extensions/stefanocoretta/resoutput/pubs.ejs` as the template in a document listing.

The supported fields are:

- `year`
- `open`
- `rr`
- `title`
- `author`
- `institution`
- `journal`
- `version`
- `location`
- `doi`
- `manuscript`
- `submitted`
- `accepted`
- `published`
- `registration`
- `url`
- `download`
- `github`
- `video`
- `abstract`
- `compendium`

## Example

Here is the source code for a minimal example: [index.qmd](index.qmd).

You can see the rendered HTML [here](stefanocoretta.github.io/resoutput/).

