# Fast API server

A super simple Pythonic server that servers up a mysterious random number on port 8000

Has some basic requirements that need to be installed.

## Setup
Basic setup instructions. Use Python 3

    pip install -r requirements.txt

    uvicorn main:app --host 0.0.0.0

## Access via

    http://127.0.0.1:8000/

    http://127.0.0.1:8000/docs


# Simple GoLang redirector

## The "client" side 

Sends out a request to the server, receives a JSON number as a response, and redirects the user accordingly. If running locally adjust the http://server:8000 URL accordingly.

## Running the client
To build and run the client change directory to where your code is and run

    go env -w GO111MODULE=auto
    go build -o klijent
    ./klijent

If the server is up and running you should be able to go to http://127.0.0.1:8090 and enjoy a relaxing web-comic.
