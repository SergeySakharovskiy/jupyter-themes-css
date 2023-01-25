# jupyter-themes-css

**Overview**

This repository contains custom jupyter css themes forked from
[arv-anshul repo.](https://github.com/arv-anshul/modified-jupyterthemes)

**Prerequisites**

jupyter notebook

**Getting Started**

```python from IPython.display import HTML
with open('compiled/gruvboxll.css', 'r') as file:
    custom_css = file.read()

custom_css = f'<style>{custom_css}</style>'
HTML(custom_css)
```
![image](https://user-images.githubusercontent.com/71666496/214673506-6c477476-d7d3-4044-82fa-ae2dae4f9e9c.png)
