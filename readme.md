1. Run App
flask --app flaskr --debug run

2. Install DB
flask --app flaskr init-db

3. Distribution Files: 
    - setup.py
    - MANIFEST.in : This tells Python to copy everything in the static and templates directories, and the schema.sql file, but to exclude all bytecode files.

4. Install App
pip install -e .

5. Testing
pytest

6. deploy -> liat di webnya