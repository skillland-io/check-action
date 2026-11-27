---
name: good-skill
description: Extracts text and tables from PDF files and merges documents. Use when the user mentions PDFs, forms or document extraction.
---

# PDF processing

## Steps

1. Read the file with `pdftotext`.
2. Check the output is not empty before you continue.

## Example

```bash
pdftotext input.pdf out.txt
```

See the [pdftotext manual](https://www.xpdfreader.com/pdftotext-man.html).
