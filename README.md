# people2
The second iteration of the Fedora People generation script.

### Running
- Install dependencies: `pip install -r requirements.txt`
- Run script: `python make_people_page.py`
- Copy CSS/JS/font dependecies and generated `index.html` to appropriate location (e.g `/var/www/`)


Tip: Edit `make_people_page.py` and change line 156's `grep` statement, line 183's email template to conform to the pattern in your own system, if not running on Fedora's infrastructure.

### Hacking

people2 is written with Python, Bash, Jinja, and JS with DataTables and jQuery.
