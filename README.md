# Exchange-Monitoring-Scripts

This code has been heavily modified to remove any pertinent details about machine names and pertinent details from things at UMIACS.

As such, this code can not be run as is (nor should it) but instead should serve as an example of my Powershell scripting abilities. 

This code was mostly written by me and was created to run every day on a scheduled event to identify problems with our Exchange servers. Not all of the functions were written by me, and as such those parts are not included in this repository. 

The script creates a log file as well as sends an email to all pertinent staff. It checks the database copy status, backups, and cluster status. 
