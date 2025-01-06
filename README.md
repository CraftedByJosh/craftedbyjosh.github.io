# craftedbyjosh.github.io

Repository for my personal website/blog thing hosted on GitHub Pages at [craftedbyjosh.github.io](https://craftedbyjosh.github.io).

## Commands

Add a new post with the following command:

```bash
cat <<EOF > content/posts/POST_NAME.md
---
title: POST_TITLE
description: POST_DESCRIPTION
date: $(date +%F) # (optional)
# tldr: # (optional)
draft: false # (optional) true/false
tags: [EXAMPLE TAG] # (optional)
# toc: # Optional - Comment out to disable table of contents
---
EOF
```

Run the hugo server:

```bash
hugo server

# To include drafts
hugo server -D
```
