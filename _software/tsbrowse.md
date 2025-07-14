---
layout: software-page
title: tsbrowse
name: tsbrowse
#Uncomment to override automatic values
#description:
#repo_url:
gh_org: tskit-dev
docs_url: https://tskit.dev/tsbrowse/docs/
category: analyse
python_package: tsbrowse
priority: 13
code_snippet: |2
  python -m tsbrowse preprocess example.trees
  python -m tsbrowse serve example.tsbrowse
redirect_from:
  - /tsbrowse/
citation_url: https://doi.org/10.1101/2025.04.23.649987
---

tsbrowse is a Python package that creates a webapp for exploration of the data model
of a tree sequence.