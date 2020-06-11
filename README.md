# jupyter_presentation_demo

Repository to demonstrate how to create presentations (html slides) using jupyter notebooks

## How to run jupyter-lab and create the presentation content
1. `pipenv install`
2. `pipenv run jupyter-lab`
3. Edit the `slide_demo.ipynb` jupyter notebook

## How to create the presentation
`pipenv run jupyter nbconvert slide_demo.ipynb --execute --to slides --post serve`
