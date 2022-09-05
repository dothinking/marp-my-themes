# My Marp Templates


VS Code Setting:

```
{
    "markdown.marp.themes": [
        "https://raw.githubusercontent.com/dothinking/marp-my-themes/master/se.css"
    ]
}
```

markdown template:


```
---
marp: true
theme: se
paginate: true
footer: Siemens Energy is a registered trademark licensed by Siemens AG.
---

<!-- _class: cover -->

# Subject: Short Description of Your Topic

## Sub Title

<!-- _paginate: false -->

---

## Use ``##`` to define title in normal page

- h1 title can be used only in cover page
- only **ONE** h2 title could be used in normal page
```