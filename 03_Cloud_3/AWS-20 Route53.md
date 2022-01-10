# Route53
Amazon Route 53 is a highly available and scalable Domain Name System (DNS) web service. 

You can choose Route 53 for the following 3 functions:

- Register domain names

Your website needs a name, such as example.com. Route 53 lets you register a name for your website or web application, known as a domain name.

- Route internet traffic to the resources for your domain

When a user opens a web browser and enters your domain name (example.com) or subdomain name (acme.example.com) in the address bar, Route 53 helps connect the browser with your website or web application.

- Check the health of your resources

Route 53 sends automated requests over the internet to a resource, such as a web server, to verify that it's reachable, available, and functional. You also can choose to receive notifications when a resource becomes unavailable and choose to route internet traffic away from unhealthy resources.

## Key-terms
- routing policy - 
A setting for records that determines how Route 53 responds to DNS queries. 

- Simple routing policy – Use to route internet traffic to a single resource that performs a given
function for your domain, for example, a web server that serves content for the example.com
website.
- Failover routing policy – Use when you want to configure active-passive failover.
- Geolocation routing policy – Use when you want to route internet traffic to your resources based
on the location of your users.
- Geoproximity routing policy – Use when you want to route traffic based on the location of your
resources and, optionally, shift traffic from resources in one location to resources in another.
- Latency routing policy – Use when you have resources in multiple locations and you want to route
traffic to the resource that provides the best latency.
- Multivalue answer routing policy – Use when you want Route 53 to respond to DNS queries with
up to eight healthy records selected at random.
- Weighted routing policy – Use to route traffic to multiple resources in proportions that you
specify
## Opdracht
Bestudeer:

- Route53
### Gebruikte bronnen
- https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html

### Ervaren problemen

### Resultaat
