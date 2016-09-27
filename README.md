Name: Nessus 6 Report Downloader
Author: Travis Lee - forked from https://github.com/eelsivart/nessus-report-downloader
Version: 1.1
Last Updated: 2016-09-27

Description:  Interactive script that connects to a specified Nessus 6 server using the
Nessus REST API to automate mass report downloads. It has the ability to download
multiple or all reports/file types/chapters and save them to a folder of
your choosing. This has been tested with Nessus 6.5.5 and *should* work with
Nessus 6+, YMMV.

File types include: NESSUS, HTML, PDF, CSV, and DB. 

Chapter types include: Vulnerabilities By Plugin, Vulnerabilities By Host, 
Hosts Summary (Executive), Suggested Remediations, Compliance Check (Executive), 
and Compliance Check.

Usage: ruby ./nessus6-report-downloader.rb

