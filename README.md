# sqlfluff-plugin-example

## installation
virtualenv venv

pip install setuptools
pip install wheel 
pip install twine

python setup.py sdist bdist_wheel
python -m twine upload --skip-existing --repository testpypi dist/*

setuptools = ">=49.6.0"
wheel = ">=0.35.1"
twine = ">=3.2.0"