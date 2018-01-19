# vsphere_patching

NOTE:
Program in development and some things are subject to change

This program will scan and patch esxi hosts within a defined environment. It employs Django REST API using a postgreSQL backend for tracking patch baseline metadata, host metadata, autodeploy metadata, patch groups, and patch group scheduling.

There are multiple parts to this project.
Scanning and reporting
Patching
Patch scheduler
Baseline builder
