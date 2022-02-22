# Project Pedal

## Motivation
The currently used software is lacking in both functional and technical features:
- Hard to update price for service and parts of bikes
- One-sided system with no mobile interaction
- Customer and shop unable to effectively communicate
- Outdated codebase in Visual Basic
- Lack of exception handling
- Lack of documentation

## User Categories
The two user categories are customers of the campus bike shop and the employees of the bike shop.
These two groups of users drive what core features the software will provide.

## Core Features

### Customer Side
- Simple and clear UI
- Mobile-friendly website interface
- Provide status checking for service
- Simple and easy communication with am employee

### Bike Shop Employee Side
- Ticket handling interface
- Service handling interface
- Updatable prices and services interface
- Convenient communication with customer

##Example Scenario
A customer of the bike shop would enter with their bike for inspection.
Once the inspection has taken place, the bike shop would generate a ticket for the bike and owner.
The owner receives an email with a link, allowing them to access their ticket status on the website.
The bike shop then proceeds to work on the bike. The ticket status is updated as it goes through this process.
For each job that must be done, the system is informed of the work performed and fetches the cost of service and parts.
Should the customer wish to communicate with the shop, they do so through the site.
The ticket is completed and the customer is alerted to come and pay for the services done.


## Technical Details
While certain elements are still up in the air, the current plan is as follows:
- usage of a UA domain
- SQL database already is available for our use
- Previous data will not be transferred. This is a brand new system.
- Wordpress site, in order to be in-line with other UA sites
- Docker usage to deploy
---

### Team E-JYBT is:
Jonathan Erskine | Yichen Huang | Ben Floyd | Thomas Davidson 
