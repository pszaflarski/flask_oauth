# flask_oauth
Flask Google OAuth using Flask-Dance

based on this quickstart:
https://pythonhosted.org/Flask-Dance/quickstarts/sqla-multiuser.html
but modified for Google

required:
set environment variables:
GOOGLE_OAUTH_CLIENT_ID
GOOGLE_OAUTH_CLIENT_SECRET
OAUTHLIB_RELAX_TOKEN_SCOPE
OAUTHLIB_INSECURE_TRANSPORT

set up a virtual environment for yourself:
virtualenv venv
source venv/bin/activate

set up the database:
python multi.py --setup

then run:
python multi.py
