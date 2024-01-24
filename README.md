# dijnet-bill-downloader

A no-brainer downloader for dijnet.hu. It simply logs in with your username/password and downloads all your invoices (PDF and XML) to the current folder organized by *service-provider/issue-date* (e.g. *BKM-Nonprofit-Zrt/2023-11-15.pdf* and *BKM-Nonprofit-Zrt/2023-11-15.xml*)

Compatible with Linux and (probably) every Linux-like system.
Dependencies:
- basic tools like head, grep, file, read, mktemp
- wget

If you wish to automate the download, you can set the DIJNET_USERNAME and DIJNET_PASSWORD environment variables; otherwise, the script will prompt you to enter them.

Tested on Arch Linux as of 2024-01-24.
