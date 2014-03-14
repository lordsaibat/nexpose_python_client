nexpose_python_client
=====================

Nexpose Python Client 

Builds a site with the IP/IPs and scans the site create.
After the scan completes an ad hoc report is generated and save to the directory in a PDF format.
Only tested with Nexpose commercial edition. 


nexpose.py -i <IP> -x <Nexpose IP> -u <Nexpose username> -p <Nexpose password> 
or 
nexpose.py -l <file with IPs> -x <Nexpose IP> -u <Nexpose username> -p <Nexpose password>
                               
-i or --ip                  IP to scan. REQUIRED

-l or --list                List of IPs to scan. REQUIRED

-x or --nexpose_ip          IP address of Nexpose scanner. REQUIRED

-u or --nexpose_user        Username for Nexpose user. REQUIRED

-p or --nexpose_password    Password for Nexpose user. REQUIRED

-v or --verbose   Turn on verbose output. Must be set to on.
-o or --out       Output File. Default results will be written to output.pdf.
