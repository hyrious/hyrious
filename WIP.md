
**Issues**

- `markdown-viewer#136`
  Markdown Viewer: refactor update logic
- `prism#2715`
  PrismJS: rewrite with typescript (esm)

**My Own Work**

```
remake blog: take notes, write articles
   fast local editor, less repeating
      new post format, or maybe markdown it
   fetch posts from the cdn (note that cdn may be down, check that)
   is it an app?
   find some way to do syntax highlighting
      [pending] PrismJS, need an esm version, otherwise vite won't allow it
      do we need calc syntax highlight locally or in frontend?
         PrismJS is about 20kb, is it a good choice?
      if we do locally, we can use sublime-text (manually, since
      there's no way to programmatically control sublime text) or
      post github markdown api (which has github-markdown-css so we don't
      need another highlight.css)
         the local syntax cache file format can be (offset,type) tuples
```

```
changelog tracker: like rsshub?
   learn something in frontend from devdocs

rssiew: rsshub + devdocs
   try to read subscriptions quickly
```

```
github-readme-stats - text only, and ~~abuse~~ github actions
   copy some code from anuraghazra/github-readme-stats...
```

```
notes: yet another note app, web/electron
   markdown is not enough for note, make new editor to do that
   consider the Notes on mac and OneNote
```

```
vanilla: a library which does everything (new age jquery)
   and rollup does tree shaking
```

```
ewe: experimental web game engine
   since I have some frontend tools, maybe put them together?
   webgl2(shader) is also good thing
```

```
hyrush: cross platform "ruby on shells"
   ruby does very well on cross-platform works, maybe its also good to make shell?
   yeah I know some bash.exe or pwsh or elves/elvish, but ruby is so powerful...
```
