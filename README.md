# Recipes & Diet

Hugo site. Needs [Hugo extended](https://gohugo.io/installation/) 0.158 or newer.

```bash
git clone --recurse-submodules https://github.com/OpenSourceKyle/diet.git
cd diet
hugo server
```

If the theme folder is empty after a plain clone:

```bash
git submodule update --init --recursive
```

Build the static site into `public/`:

```bash
hugo --minify
```
