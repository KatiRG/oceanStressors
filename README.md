This a web application designed to distribute derivated products described in 
http://www.biogeosciences.net/10/6225/2013/

This application is based on use of Flask, a python framework, and Gunicorn, a Python WSGI HTTP Server.

The tiles displayed on maps are generated by using pyferret for the rendering.
See https://github.com/PBrockmann/wms-pyferret for the original development of the Gunicorn-pyferretWMS code. The Flask integration was first developed here https://github.com/KatiRG/wms-pyferret.
