# The Mechanism Collection

## Install

```
bundle install --path.bundle
```

## Run

```
bundle exec jekyll serve -w
```

## Generate Ebook

```
pandoc --standalone -f markdown -t epub index.md epub.yaml -o the-mechanism-collection.epub
```

