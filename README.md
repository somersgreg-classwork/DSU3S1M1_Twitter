# dspt13-unit3

Set-ExecutionPolicy unrestricted

. venv/Scripts/activate.bat

python setup.py sdist bdist_wheel

twine upload --repository-url https://test.pypi.org/legacy/ dist/*