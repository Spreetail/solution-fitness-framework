## Service Discovery

AKA "Consul"

Service Discovery is used when integrating multiple applications together in a microservices implementation.  Service Discovery (and registry) is handled by Consul, and all applicable applications should be listed in the Consul service registry. The goal is to have a dynamic, always accurate and up-to-date dashboard that shows where every single piece of software is running, as well as the current state of its health. Doing so will provide developers an at-a-glance summary of system-wide availability.

*Acceptance Criteria* - Codebase is integrated with Consul either manually or using the Spreetail.ServiceRegistration NuGet package