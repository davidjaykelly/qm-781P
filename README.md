# QM 781P Project

A Transport for London status update webapp. Implemented for QM 781P mini project by David Kelly.

### Tech

The webapp uses:

* [Flask]
* [Twitter Bootstrap]

### Installation

Download or clone the repository. 
Install the requirements (note that this can take a few minutes):

```sh
$ cd foldername
$ pip3 install -U -r requirements.txt 
```

Obtain a TfL API key and API ID from: https://api-portal.tfl.gov.uk/login

Edit config.py to include the key and ID, save this file.

Start the flask app:

```sh
$ flask run
```

Navigate to http://127.0.0.1:5000/

   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [Flask]: <http://flask.pocoo.org>

