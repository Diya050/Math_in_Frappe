## Math and Flowcharts in Frappe
This repository is about rendering maths formula and mermaid flowcharts in frappe/erpnext webpages through markdown.

## Steps To Follow:

- Open terminal.
- Go to `Utils` directory.
```bash
cd frappe-bench/apps/frappe/frappe/utils
```
- Edit `data.py` file.
```bash
vi data.py
```
- Add the following to `data.py`:
```python
    extras = {
        "fenced-code-blocks": None,
        "tables": None,
        "header-ids": None,
        "toc": None,
        "highlightjs-lang": None,
        "html-classes": {"table": "table table-bordered", "img": "screenshot"},
         "mermaid": None,
         "mathjax": None,
         "cuddled-lists": None,
         "code-friendly": None,
    }
```
