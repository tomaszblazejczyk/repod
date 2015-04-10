
Installing RepOD
===============

RepOD comes as modular software with CKAN as main engine and extensions

Installation Steps
==================

MOAI is a normal python package. 
I recommend creating a virtualenv to install the package in.

http://pypi.python.org/pypi/virtualenv/

This makes development and deployment easier.
Instructions below are for unix, but MOAI should also work on Windows

Download from Github:

git clone https://github.com/tomaszblazejczyk/repod.git
cd repod

Create and activate virtual environment

virtualenv .
. bin/activate

Install development software

python setup.py develop
pip install -r requirements.txt

Install CKAN as described http://docs.ckan.org/en/latest/maintaining/installing/install-from-source.html

Install ckanext-ceon https://github.com/mateuszneumann/ckanext-ceon

Install MOAI branch for RepOD with CKAN data factory https://github.com/tomaszblazejczyk/moai


