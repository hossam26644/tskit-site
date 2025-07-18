---
layout: software-page
title: tsinfer
name: tsinfer
gh_org: tskit-dev
docs_url: https://tskit.dev/tsinfer/docs/
publication: https://doi.org/10.1038/s41588-019-0483-y
logo: https://raw.githubusercontent.com/tskit-dev/administrative/main/logos/svg/tsinfer/Tskit_tsinfer_logo_on_black_no_background.eps.svg
category: infer
python_package: tsinfer
priority: 3
code_snippet: |2
  sample_data = tsinfer.load(
      "phased_sequence_data.samples"
  )
  ts = tsinfer.infer(sample_data)
redirect_from:
  - /tsinfer/
citation_url: https://tskit.dev/tsinfer/docs/stable/CITATION.html
citation_md: https://raw.githubusercontent.com/tskit-dev/tsinfer/refs/heads/main/CITATION.md

---
``Tsinfer`` is a Python package to infer a tree sequence from large
quantities of phased DNA sequence data, for example in a VCF file
(see the [tutorial](https://tsinfer.readthedocs.io/en/latest/tutorial.html#reading-a-vcf)
for how to convert data from a VCF into a suitable input format).
