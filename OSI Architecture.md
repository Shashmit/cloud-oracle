### OCI Architecture

  - Regions
  - Availability Domain
    > Connected within a region | Fault tolerant | Low Latency network
  - Fault Domain
    > hardware and software combination

`lets talk about how to choose region`
  - Location : Coose a region closer to keep the latency and highest performance
  - Data Residency & compliance : Many countries have strict rules
  - Service Availability : Newer services are mae available based on the demand, regulatory compliance, resource availability and few more factors

`Availability Domains`
 - Isolated from one another, hence making it safe from any other Domains failing.

`Fault Domains`
  - Each region has multiple Availability Zones in which every `AD has 3 fault Domains in it` which runs isolated and doesn't impact one another.
  

