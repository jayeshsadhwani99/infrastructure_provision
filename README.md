# An infrastructure provisioning project

This app uses flask as a backend server along with pulumi to allocate resources to AWS

## To run the app

`FLASK_RUN_PORT=1337 FLASK_ENV=development PULUMI_ORG=jayeshsadhwani99 venv/bin/flask run`

## To generate a PEM key pair

`ssh-keygen -m PEM`

After this, change the name to pem file (in the directory the file is saved),

For MacOS,

`mv id_rsa id_ra.pem`

For Windows,

`rename id_rsa id_ra.pem`

## How to use the interface

While creating, it would ask for an SSH key, either you can paste it in, or it can find it automatically
