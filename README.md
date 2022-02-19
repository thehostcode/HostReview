# HostReview
DigitalOcean Hosting is a cloud computing web service that provides virtual servers (called droplets), solid-state drives (SSD), and block storage. It was founded by Ben Uretsky, Moisey Uretsky, Mitch Wainer, and Jeff Carr. The first beta version of the DigitalOcean product was released in 2011. The company is based in New York City, United States.

DigitalOcean services are available only in datacenters in the United States (specifically, in New York City and Newark). As of January 2016, they are running over 690+ web-scale data centers across 12 countries with 16 data centers located within NYC alone. It offers Linux virtual servers only. 

In May 2018, DigitalOcean expanded its offerings to include Virtual Private Cloud (VPC), which allows users to create private hosted zones for their infrastructure that can encompass multiple droplets in a single region or spread out over different regions. Digital Ocean has reported more than half a million registered customers as of December 2017.

DigitalOcean provides a RESTful API and all droplets and objects in the DigitalOcean controlled data center are accessible via HTTP or HTTPS with Developer's Guide for API Development. Developers also have the option of using the APIs in cURL. The company is planning to add SSH support in June 2012. 

Droplet management is available by command line (SSH) and through a web-based console that was released on April 8, 2013. This graphical interface allows Droplets to be created, copied, deleted, Snapshot / Restored, rebooted etc.

In January 2011, five months after starting work on DigitalOcean, its founders raised US$12,000 from family and friends. In May 2012 it gained another US$3.2 million in funding from the venture capital firms Andreessen Horowitz and Union Square Ventures. On September 9, 2013, the company took in US$37 million in Series A funding led by Andreessen Horowitz with participation from Kenneth Lin of Trustbridge Partners; Scott Banister; Bullpen Capital; Ron Conway, David Lee, Josh Steelman, and Yasir Al-Rumayyan (through AngelList). On March 4, 2014, DigitalOcean raised US$50 million in Series B funding led by Access Industries with participation also from DAG Ventures and existing investors including Andreessen Horowitz.

On October 14, 2014, DigitalOcean announced that they would be expanding to new data center locations within the United States as well as around the world. In the same release, they also announced a new SSD storage option, as well as a service level for those who require greater availability and uptime from their services.

In February 2015, DigitalOcean opened a data center in Frankfurt, Germany under its European region to better serve customers within that geographic region. On May 29, 2015, DigitalOcean started listing London data center "2" ("LDN 2") as part of its United Kingdom region. That day it began listing Mumbai data center “5” under its India/Middle East region.. On November 1st, 2016, DigitalOcean expanded into Bangalore with one additional location at BLR1. In January 2017 DigitalOcean added two locations in Paris – ORLY1 and ORLY2. In early February 2017, DigitalOcean opened three new locations in the United States: FRA1 in Frankfurt, NJR1 in New Jersey, and BLR2 in Bangalore.

In late March 2017, DigitalOcean introduced a location in Chennai, India called INW1. The following month on April 27 they opened a data center in Istanbul "Istanbul 1" under its Istanbul region. On August 3rd, 2018 TWD1 was added as a facility within Taiwan's capital city Taipei. Four days later on August 7th, it has been announced that another Taiwanese data center is to be launched TPE2 located 500 meters away from the first data center (TPE1). 

On September 6th, 2018, DigitalOcean opened SEA1 in Singapore under its Asia-Pacific region. On October 10th, 2018 they announced that GBL1 will be opening within Tokyo's central district on November 1st.

On November 21st, 2018 the company announced all three data centers (LAX1, NYC3, and SFO2) are to go offline for maintenance between the hours of 9 am-5 pm PST. The next day many users across all regions began reporting issues with APIs resulting in failed Droplet creation requests due to the lack of available IP addresses. 

##DigitalOcean Features Review

DigitalOcean provides both SSD-based and legacy (SATA, formerly known as Elastic) server hosting. The legacy servers are accessible in all available regions except Mumbai. The SSD cloud servers come in two types: the standard computes droplet and the larger high memory droplets. There is a third type called an application Droplet which allows the user to run "software with all the benefits of a standard cloud server". The application Droplet type was launched on August 3rd, 2018, and is currently only available in San Francisco (SFO2). These Droplets allow for custom machine images to be deployed.

DigitalOcean provides block storage through two products: Spaces (formerly known as volumes) and Block Storage (formerly known as the "droplet volume" product) which was launched on March 4, 2014. Spaces have a 5GB size limit while Block Storage has a 1TB limit. On September 9, 2013, DigitalOcean announced a 512 MB RAM tier to their service offering with prices starting at US$10 per month for an attached SSD with 1 GB of RAM. The 512 MB droplet was re-enabled on April 2, 2014, after being unavailable for seven months due to a high failure rate in 2012. It was disabled again on Feb 26, 2016, because it "was not meeting [the] needs" of DigitalOcean customers. On May 12th, 2015 DigitalOcean began offering customized Droplets that allowed users to choose between two operating systems (Ubuntu or CentOS).

On February 27, 2018, the Low Memory option became available. The low memory Droplet has 768 megabytes of RAM instead of 1GB like other types of Droplets have. This is only available in San Francisco at this time but will soon be made available in Amsterdam by April 1st. On July 24th, 2018 a 1 GB RAM option was made available in Bangalore.

DigitalOcean provides DNS hosting through its Spaces product. Users are able to set up their own custom subdomain or utilize an existing third-party domain name that is already hosted elsewhere. DigitalOcean's DNS service has three different modes: Active, Passive, or Active/Passive. Each DNS zone has its own TTL (time-to-live), which dictates the expiration time of records set within that zone.

By default, DigitalOcean nameservers are used to resolve DNS queries originating from within DigitalOcean's network. Customers may also opt to use customer nameservers if supplied by the customer.

