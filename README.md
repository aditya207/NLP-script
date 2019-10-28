# NLP-script
Project on NLP
Acmeservices is a company with multiple websites and all those websites
have many referrals (link ins) from various search engines and third party
websites. Acmeservices invests on the ads on search engines like google,
baidu, naver and more. The links that are clicked on the ads from the search
engines have detailed information in the url query of the landing page. The
business wants to learn about various statistics that can be generated from
the data from the URL query parameters

The file data.csv contains sample of the website logs that are generated
when any user visits the website. The description of the columns is as below:
Column Description
1)Session id: A unique id that identifies user 
session. It regenerates on every page 
load
2)uuid A: unique id that identifies user across 
his/her lifetime
timestamp Timestamp of the request
3)location: TLD of the requested website
3-1)Location path: Page location of the requested 
website where the user lands
4)Location query: Query paramters that contain 
information about the referrer
5)Referral location :TLD of the referrer website (where 
the link has originated from)
6)UA string: User agent string of the client 
browser 
7)geo_ip: client ip address
Task
My task was to create a python script or jupyter notebook that accepts an
input file with the data in the format as it is in the sample data file and
outputs a report in the format mentioned in the “output” block below.
Output:
1. The “location query" has url variables which contain rich data on
keywords, campaigns, creatives and more. Provide statistics on those
variables by “location” “timestamp”, “referral location” and more.
Example of sample report that your script should output
◦ eg: A table with top 10 keywords, creative, media, adgroup, etc
2. UA string identifies the browser, OS and device. Integrate with any
open source, local run, UA string library and provide statistics on
browser, OS and device.
3. Geo_ip identifies city, country and much more. Integrate with any open
source, local run, geolocation library and provide statistics on city,
country and any other geo data.
