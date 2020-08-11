# What have I done?

This is a full list of my tasks in my previous jobs. It's a bit extensive. [Ask for my CV for a shorter list](mailto:fhielpos@gmail.com).

## Index

* `IT/Engineering` [Telefonia y Sistemas SRL](#telefonia-y-sistemas-srl)
* `IT/Support` [CTEC Patagonia IT](#ctec-patagonia-it)
* `IT/Engineering` [Freelancer](#freelance)
* `Retail/Support` [COTO CICSA](#coto-cicsa)

## Telefonia y Sistemas SRL

### Scripting

I embraced `Python` for my scripts. And I wrote a few:
* PyMon - Just to monitor when things go up or down. Now I'm trying to do this in Django. Still learning.
	* A report within PyMon. It sends a mail with what is up or down at that time. This was a special requirement. We needed something really simple and I already had PyMon so I just added that little function.
* PyPg - To "administer" PostgreSQL databases. For now, it just does backups.
* Backups. This is my "masterpiece". It makes a backup of PostgreSQL databases (with PyPg) and of all the dockerized apps and it sends it to BackBlaze B2. Nothing special but a personal achievement.

### Some systems customization

We have a lot of `Odoo ERP` running and from time to time we need to add or modify some functionality, so I do some Python programming there.

### Administration

As I said we have a lot of Odoos. The way it was running before I landed the job was: One VM per Odoo app + PostgreSQL, which leaded to bad resource management, so I ended up migrating everything to a `container environment`. In the future I plan to move everything to a `Rancher cluster`.

So, to have a list of some things I administer here:

* Odoo apps
* Docker containers
* Apache and NGINX (Currently dropping Apache for NGINX)
* PostgreSQL
* Linux hosting all the above
* Mikrotik and Ubiquiti networks (Or every network it comes across)
* Office 365 Suite
	* Azure AD and MS Teams

For this I decided to be always on-call. This was my personal decision as I am the only admin and I want my infrastructure to have at least downtime as it can. If I receive an alert (from the monitoring system), I answer it.

### Support

Of course, all the apps we run need someone who can help people to use them, so I tend to be always helping with usage questions or privileges problems.

From time to time I fight with a printer or two, just for fun (not really for fun).

### Security

We don't have a primary focus on `Security`, but I do, so I try to be as less permissive as I can.

To do this I:
* Do in depth hardening every time I can.
* Implemented a WAF with NGINX to reduce attack surface.
* Implemented SSL certificates in every domain.
* Redesigned the network with a least-privilege approach.
* Restricted publicly open ports to only required ones.
	* Changed the port numbers of known ports.
	* Implemented public-key auth for SSH and other ports.

## CTEC Patagonia IT

### Purchaser

I started here buying things. Doing the cost and budget analysis.

### Translator and relationships

With the time we acquired an international client and I was the only one who spoke fluent English, so I was the one who managed the relation with that costumer.

### Consultant

I am (or was) a Microsoft Certified Professional, so I was in charge of all the Microsoft platform within the company and our customers.

That included:
* Office 365:
	* Whether if a plan was suitable for a client or not.
	* Azure AD.
	* Office Suite.
* Microsoft Licensing.
* Windows Server Administration:
	* Active Directory.
	* File Server.
	* Work folders and Direct Access.
	* Other things related.

And also provided guidance with:

* Networking.
* Cloud.
* Hardware.
* Other Software.

### Support

Mainly with all the Microsoft or Server related products we had, to clients and internal-clients from 10 to 300 users.

### Project management

I provided guidance and management in a `Cisco` related project where we installed and cabled near 150 public schools networks. My main tasks where:

* Coordinate the schedule within a group of +10 people.
* Stock management.
* Conflicts resolution.
* Guidance and decision making.
* Reports and technical documentation of every site.
* Troubleshooting of Cisco products.

### Other things

As it was a startup, the tasks where changing all the time. I did things like:

* Sales.
* Post-sales.
* Some design.
* Others.

## Freelance

### Support, Systems and Networking

I have been a contractor doing Systems and Network Administration for various clients the last years. Mainly with `Linux` or `Windows Server` and `Cisco Networks`.

## COTO CICSA

### Customer Support
Client Support for one of the biggest retailers. Some of the tasks where:
* First line of Customer Suppoort.
* Problems resolution with a client-first approach.
* Team leader for 20+ people team.
  * Task scheduling.
  * New members onboarding.
