How to develop and test an asynchronous API with FastAPI, sqlite3 and Pytest using Test-Driven Development (TDD). We'll also use the Databases package for interacting with sqlite3 asynchronously.

Dependencies:

FastAPI v0.46.0

Docker v19.03.5

Python v3.8.1

Pytest v5.3.2

Databases v0.2.6

Steps:
====
1. clone this repo
2. cd src
3. pip install -r requirements.txt

Run API Server:
=====
uvicorn app.main:app --reload --workers 1 --host 0.0.0.0 --port 8000

Run Unit test
======
 pytest . -s  (to get print message, optional)



For more reference: https://testdriven.io/blog/fastapi-crud/ 
