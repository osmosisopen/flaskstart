# Start working with flask
This is a simple step-by-step tutorial to start working with a simple flask application

To understand how to install flask 

Read [Flask Installation Official Doc](https://flask.palletsprojects.com/en/3.0.x/installation/)

In simple steps, they say


* Flask is a lightweight web application framework.
* Flask is a python library

----

So, the pre-requisite to start working with flask

* Install python (if not already installed)

----
  
* To install flask, execute

  `pip install flask`

----
* Once flask is installed, copy the contents of the app.py (or type them 😊) into a file named app.py

* To run the application, (be in the same folder as the app.py) and execute

`flask run`

A sample command execution and its expected output (almost all of the time) is shown below

```
  $ flask run
   * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:5000
Press CTRL+C to quit
```

Ignore the warning for now.

You can see that it says

`Running on http://127.0.0.1:5000`

This means that now we have a web server running on 127.0.0.1 (localhost) IP, listening on port 5000.
(If you don't know what it means, don't worry for now. Let's proceed)

----

Open your (favourite) web browser and paste the address `http://127.0.0.1:5000` in the address bar

Your browser may be showing the text `Hello World`
