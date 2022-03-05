# OASIS demo data

This repo contains demo data to populate the OASIS database for development purposes.

Once you have cloned this repo on your machine you can use the convenience scripts in the ```scripts``` folder in the [OASIS server](https://github.com/oasis-art-project/oasis-server) to upload this data to the server. From the root folder of the oasis server, you can populate a local deployment using the following command:

`python scripts/populate.py -u http://127.0.0.1:5000 -f <path to demo data repo> -d` 

Notice the ```-d``` flag, it updates the dates in the demo data so there are current and future events.