# HDE_Recon_Tools
								Tutorial 
							-------------------------
					System purpose - reconesense

System classes 
---------------

# rd:
	- Main // Classes operating file
	- Controller // All the functions that related to database management (insert, remove, update, delete, etc.)

	- Facebook // Login, company search & extract company contacts
	- Linkedin // Login, company search & extract company contacts
	- WebCr // Find emails in google & by pattern according to the user choise that related to the domain
	- WebCrPhones // Find phones in google according to the domain

	- Robots // Search for the disallow websites in the robot.txt
	- GoogleDorking // search for vulnerable websites
	- AdminPanel // search the admin panel

	- MetadataFiles // Search relevant files that related to the domain, download them & extract relevant details to database 

	- Netcraft // Access the DNS servers and search for subdomains
	- SubDomain // Search subdomains from prior list
	- GeoLocation // Find the geographical location of the subdomain servers


System Tables
--------------

# web_vul_t:
	["ID","url","moudle"]

# hosts_t:
	["ID","host","ip","city","region","country","lat","long","zip_code","port","service","moudle"]

# metadata_t: 		
	["ID","name","type","size","creator","author","title","createdDate","modifyDate","software,"producer","compObjUserType"
	,"application","moudle"]

# contacts_t:
	["ID","name","jobs","emails","phones","linkedin_url","facebook_url","address","birthday","pic","geolocation","moudle"]


Future Developments
--------------------

# Scapy

# System files optimization - multi processing & multi trading

# GUI - web interface

# Summary table for the comapany



