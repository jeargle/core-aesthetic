core-aesthetic
==============

2-player group battle game


How to Run
----------

core-aesthetic runs in web browsers and needs to be hosted by a webserver.  To host it, start up a webserver that gives access to the index.html file within the core-aesthetic top-level directory.  For example, if you have python (>=3) installed, navigate to the core-aesthetic directory and run

```
> python -m http.server 8000
```

This will start a server exposing that directory on port 8000.  You can then access the program by pointing your web browser to the URL `http://localhost:8000`.
