# AWS-Route53
Route 53
Amazon Route 53 is a highly available and scalable Domain Name System (DNS) web service offered by AWS. It’s primarily used to translate domain names (like example.com) into IP addresses (like 192.0.2.1) so computers can connect to each other. 

✅ Purpose of Route 53
1.	DNS Management: Converts human-readable domain names into machine-readable IP addresses.
2.	Domain Registration: Allows you to register new domain names directly through AWS.
3.	Health Checking & Failover: Continuously monitors endpoints and routes traffic away from unhealthy instances.
4.	Traffic Routing: Routes traffic to different AWS regions, endpoints, or services using advanced routing policies.
5.	Highly Available & Scalable: Designed to provide fast and reliable DNS resolution with global infrastructure.

Use Case	Description
Web Application Hosting	Manage DNS for websites hosted on AWS (e.g., EC2, S3 static site).
Multi-region Failover	Route traffic to a healthy endpoint in another region if one becomes unreachable.
Latency-based Routing	Send users to the region with the lowest latency from their location.
Weighted Routing	Distribute traffic across multiple resources (e.g., blue/green deployments).
Geolocation Routing	Direct users based on their geographic location.
Domain Registration	Purchase and manage domain names directly from AWS.
Hybrid Cloud DNS	Integrate on-prem DNS with cloud resources using Route 53 Resolver.
