# python-api-challenge

NOTE:  This project uses a forked version of Citipy.

Citipy, but design, only returns the nearest city and country code.  If you are trying to return cities and joining them with your input coordinates, you will return a city name with coordinatate that could be off by pretty great distances.  The forked version returns the nearest city, coutry and the coordinates of that city.  This way coordinates match the actual city.

This may run form the include src files but it may conflict if you already have citipy installed in your environment.  See below:

If citipy is already installed, run 'pip uninstall citypy' and then run 'pip install git+https://github.com/Enestvedt/citipy.git@master#egg=citipy'. All else remains the same.

Configs:
Create a config file and and Online Weather Maps API key and Google Maps API. key.  You will need one config file for each sub-project directory.

