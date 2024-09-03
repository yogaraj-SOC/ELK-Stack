# ELK-Stack

## Introduction to ELK Stack
 - ELK = E - ElasticSearch <br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;L - Logstash <br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K - Kibana <br>

 - The ELK stack gives you the ability to aggregate logs from all your systems and applications, analyze these logs, and create visualizations for application and infrastructure monitoring, faster troubleshooting, security analytics, and more.

 - E = Elasticsearch:
    - It is a database Used to store logs such as windows event logs, syslogs, firewall logs and anything.
    - It provides you with the capability to search across your data and is built by the folks over at elastic elastic search does use a query language called ESQL which stands for elastic search query language.
    - elastic search also uses restful APIs and Json what this means is that you can use various applications to interact with your elastic search database in a programmable way to retrieve information as required.

 - L = Logstash:
    - Introducing a pipeline that collects Telemetry from various sources it also transforms filters and outputs it into your elastic search
    - When it comes to collecting Telemetry there are many ways to do this however two popular ways are Beats and elastic agent.
    - There are six different types of Beats <br>
      1. file beat for logs <br>
      2. metric beat for metrics <br>
      3. packet beat for network data <br>
      4. wind log beat for Windows event logs <br>
      5. audit beat for audit data <br>
      6. heartbeat for uptime monitoring <br>
   - elastic agent which essentially can collect all different types of data using one unified agent per host.
   -  log stash has the capability to filter logs that meet a certain criteria making it extremely customizable to fit your environment.
 - K = Kibana:
    - kibana comes with many features built in such as Cabana lens AKA visualizations where you can drag and drop elements to help build your dashboards 
    - Exploration specifically the Discover tab which will allow you to query for your logs using ESQL there's also machine learning for anomaly detection elastic mats for geospatial information metrics alerting and many more. <br>

  - Benifits of Using ELK stack:
     1. Centralized Logging. <br>
     2. flexibility <br>
     3. visualization <br>
     4. scalability <br>
     5. ecosystem <br>
      

## Objective

To implement and configure the ELK Stack (Elasticsearch, Logstash, and Kibana) for enhanced security monitoring and threat detection. The project involves setting up the ELK Stack, detecting and investigating security attacks, and integrating the system with a ticketing solution to streamline incident response and management.

### Tools Used

- VULTR
- ELK stack
- 


