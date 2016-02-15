# monitoring-scripts

# Description

This is a collection of monitoring scipts written or modified by myself. 

# Overview of scripts

# check_qnap
A bash script for checking qnap nas device. I changed calculation of ram, the routine for hddstatus and added support for 12 hdds. Please note some qnap devices don't support checking raidstatus und drive usage because the oids are missing.
So please test it before you use in production environment.
