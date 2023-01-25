# jupyter-themes-css

**Overview**

This repository contains custom jupyter css themes forked from
[arv-anshul repo.](https://github.com/arv-anshul/modified-jupyterthemes)

**Prerequisites**

jupyter notebook

**Getting Started**

Download the compiled folder and run the following code:
```python from IPython.display import HTML
with open('compiled/gruvboxll.css', 'r') as file:
    custom_css = file.read()

custom_css = f'<style>{custom_css}</style>'
HTML(custom_css)
```

**gruvboxll**
![image](https://user-images.githubusercontent.com/71666496/214673506-6c477476-d7d3-4044-82fa-ae2dae4f9e9c.png)


[**darkula**](https://github.com/asvrvs/jupyter-darkula-theme):
![image](https://user-images.githubusercontent.com/71666496/214675618-ee63e92d-cb13-4394-8c0e-0cd2916435fb.png)
