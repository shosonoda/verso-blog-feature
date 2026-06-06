# Blog - Advanced Features

This directory contains a blog that uses the features of the Verso static site generator more
extensively. It includes:
 1. A customized JavaScript-based animated front page
 2. Custom CSS
 3. Blog posts that include Lean code that is built with both the current and prior versions of
    Lean, with [one post](blog/Blog/Posts/Comparison.lean) including code from two separate versions

The [`blog`](blog/) directory contains the actual site, while [`blog-examples`](blog-examples)
contains example code in other Lean versions. 

---

- `blog/` 配下が root に相当する
- build
  ```bash
  cd ./blog
  lake build
  lake exe generate-blog
  ```
- 手動で追加したもの
  - serve.py
  - .gitignore
  - prepare-pages.sh
