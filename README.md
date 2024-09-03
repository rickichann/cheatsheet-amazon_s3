# cheatsheet-amazon_s3



03/09/24

| Feature                      | S3 Glacier Instant Retrieval                          | S3 Glacier Flexible Retrieval                    | S3 Glacier Deep Archive                         |
|------------------------------|--------------------------------------------------------|--------------------------------------------------|------------------------------------------------|
| **Use Case**                 | Performance-sensitive, immediate access                | Backup, disaster recovery, occasional retrieval | Long-term archive, accessed less than once/year |
| **Access Frequency**         | Once per quarter                                       | 1-2 times per year                               | Less than once per year                         |
| **Retrieval Time**           | Milliseconds                                           | Minutes to hours                                 | Hours to 12 hours for bulk retrievals           |
| **Retrieval Options**        | Millisecond retrieval                                  | Flexible retrieval, incl. free bulk retrievals   | Asynchronous retrieval                          |
| **Storage Cost**             | Lower cost, higher retrieval cost                      | Lower cost                                       | Lowest cost, significantly less than others     |
| **Durability**               | 99.999999999% (11 9s)                                  | 99.999999999% (11 9s)                           | 99.999999999% (11 9s)                           |
| **Availability**             | 99.90%                                                 | 99.99%                                           | 99.99%                                          |
| **Ideal For**                | Image hosting, online file-sharing, medical imaging    | Backup, disaster recovery, offsite storage       | Long-term archive, regulatory compliance        |
| **AWS Availability Zones**   | Redundantly stored across multiple AZs                 | Redundantly stored across multiple AZs           | Redundantly stored across multiple AZs          |
| **Cost Benefit**             | Lower storage cost, higher retrieval cost              | Overall lower cost, free bulk retrieval         | Lowest storage cost, higher retrieval cost      |
| **Sector Usage**             | Various sectors needing immediate access, low latency  | Backup, disaster recovery, compliance needs     | Financial services, healthcare, long-term storage |
