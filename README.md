# Example Package

This is a simple example package. You can use
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.


Install / Update Packaging Tools:

`python3 -m pip install --upgrade build`

`python3 -m pip install --user --upgrade twine`



Build project:

`python3 -m build`

`python3 -m twine upload --repository testpypi dist/*`



