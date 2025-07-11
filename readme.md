## Privacy Risk Expansion Factor, Privacy Exposure Index and Vulnerability Score

#### This repository contains support material for the article *Privacy conducive data ecosystem architecture: by-design
vulnerability assessment using Privacy Risk Expansion Factor
and Privacy Exposure Index*

### Use Case: Video-On-Demand Data Ecosystem Vulnerability Scores Calculation  

### Multi-layered Ecosystem Architecture 

### Streaming Service Layer Vulnerability Score  

| Field Name                          | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS   |
|------------------------------------|------|------|------|------|-----|-----|-----|-----|------|
| user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| user login                         | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| user password                      | 2.0  | 1.2  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 10.8 |
| user email                         | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| user birthdate                     | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| user gender                        | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 0.0 | 0.0 | 13.0 |
| user address                       | 2.0  | 2.0  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 14.0 |
| user city                          | 2.0  | 2.0  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 14.0 |
| user country                       | 2.0  | 2.0  | 2.0  | 1.8  | 0.5 | 0.0 | 0.0 | 0.0 | 10.7 |
| user postcode                      | 2.0  | 2.0  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 14.0 |
| subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| subscription plan                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 |  9.2 |
| subscription startdate             | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| subscription status                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 |  9.2 |
| **Total VSs**                      |      |      |      |      |     |     |     |     | **212.4** |


### Subscription Management System Layer Vulnerability Score

| Field Name                        | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS   |
|----------------------------------|------|------|------|------|-----|-----|-----|-----|------|
| subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| subscription user identifier     | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| subscription plan                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 |  9.2 |
| subscription startdate          | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| subscription status             | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 |  9.2 |
| subscription last login         | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 |  9.8 |
| subscription app access         | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 |  9.8 |
| profile identifier              | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| profile name                    | 2.0  | 2.0  | 2.0  | 1.5  | 0.5 | 0.0 | 0.0 | 0.0 | 10.3 |
| user (internal) identifier      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| user login                      | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| user email                      | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| user name                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| user surname                    | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| user nickname                   | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| **Total VSs**                   |      |      |      |      |     |     |     |     | **164.0** |


### Backend Video System Layer Vulnerability Score

| Field Name                             | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS   |
|---------------------------------------|------|------|------|------|-----|-----|-----|-----|------|
| user (internal) identifier            | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| user email                            | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| user name                             | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| user surname                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| user nickname                         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| user birthdate                        | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| user gender                           | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 0.0 | 0.0 | 13.0 |
| profile identifier                    | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| profile kids                          | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 0.0 | 0.0 | 13.0 |
| subscription (internal) identifier    | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| subscription user identifier          | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| metadata identifier                   | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 |  9.2 |
| stream start                          | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| stream end                            | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 |  9.2 |
| **Total VSs**                         |      |      |      |      |     |     |     |     | **159.5** |


### Landing Layer Vulnerability Score

| Source              | Field Name                              | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS   |
|---------------------|------------------------------------------|------|------|------|------|-----|-----|-----|-----|------|
| Streaming Service   | user (internal) identifier               | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service   | user login                               | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Streaming Service   | user password                            | 2.0  | 1.2  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 10.8 |
| Streaming Service   | user email                               | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Streaming Service   | user name                                | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Streaming Service   | user surname                             | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Streaming Service   | user nickname                            | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service   | user birthdate                           | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Streaming Service   | user gender                              | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 0.0 | 0.0 | 13.0 |
| Streaming Service   | user address                             | 2.0  | 2.0  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 14.0 |
| Streaming Service   | user city                                | 2.0  | 2.0  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 14.0 |
| Streaming Service   | user country                             | 2.0  | 2.0  | 2.0  | 1.8  | 0.5 | 0.0 | 0.0 | 0.0 | 10.7 |
| Streaming Service   | user postcode                            | 2.0  | 2.0  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 14.0 |
| Streaming Service   | subscription (internal) identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service   | subscription user identifier             | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service   | subscription plan                        | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 1.0 | 0.0 | 10.4 |
| Streaming Service   | subscription startdate                   | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 1.0 | 0.0 | 11.5 |
| Streaming Service   | subscription status                      | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 1.0 | 0.0 | 10.4 |
| Subscription Mgmt   | subscription (internal) identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Subscription Mgmt   | subscription user identifier             | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Subscription Mgmt   | subscription plan                        | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 |  9.2 |
| Subscription Mgmt   | subscription startdate                   | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Subscription Mgmt   | subscription status                      | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 |  9.2 |
| Subscription Mgmt   | subscription last login                  | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 |  9.8 |
| Subscription Mgmt   | subscription app access                  | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 |  9.8 |
| Subscription Mgmt   | profile identifier                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 1.0 | 0.0 | 13.4 |
| Subscription Mgmt   | profile name                             | 2.0  | 2.0  | 2.0  | 1.5  | 0.5 | 0.0 | 1.0 | 0.0 | 11.8 |
| Subscription Mgmt   | user (internal) identifier               | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Subscription Mgmt   | user login                               | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 1.0 | 0.0 | 15.2 |
| Subscription Mgmt   | user email                               | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 1.0 | 0.0 | 15.2 |
| Subscription Mgmt   | user name                                | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 1.0 | 0.0 | 13.4 |
| Subscription Mgmt   | user surname                             | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 1.0 | 0.0 | 13.4 |
| Subscription Mgmt   | user nickname                            | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Backend Streaming   | user (internal) identifier               | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming   | user email                               | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Backend Streaming   | user name                                | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Backend Streaming   | user surname                             | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Backend Streaming   | user nickname                            | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming   | user birthdate                           | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Backend Streaming   | user gender                              | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 0.0 | 0.0 | 13.0 |
| Backend Streaming   | profile identifier                       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Backend Streaming   | profile kids                             | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 1.0 | 0.0 | 15.0 |
| Backend Streaming   | subscription (internal) identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Backend Streaming   | subscription user identifier             | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Backend Streaming   | metadata identifier                      | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 |  9.2 |
| Backend Streaming   | stream start                              | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Backend Streaming   | stream end                                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 |  9.2 |
|                     | **Total VSs**                             |      |      |      |      |     |     |     |     | **559.7** |


### Staging Layer Vulnerability Score

| Source              | Field Name                              | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS  |
|---------------------|----------------------------------------|------|------|------|------|-----|-----|-----|-----|-----|
| Streaming Service  | user (internal) identifier            | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | user login                            | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Streaming Service  | user password                         | 2.0  | 1.2  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 10.8 |
| Streaming Service  | user email                            | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Streaming Service  | user name                             | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Streaming Service  | user surname                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Streaming Service  | user nickname                         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | user birthdate                        | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Streaming Service  | user gender                           | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 0.0 | 0.0 | 13.0 |
| Streaming Service  | user address                          | 2.0  | 2.0  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 14.0 |
| Streaming Service  | user city                             | 2.0  | 2.0  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 14.0 |
| Streaming Service  | user country                          | 2.0  | 2.0  | 2.0  | 1.8  | 0.5 | 0.0 | 0.0 | 0.0 | 10.7 |
| Streaming Service  | user postcode                         | 2.0  | 2.0  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 14.0 |
| Streaming Service  | subscription (internal) identifier    | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | subscription user identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | subscription plan                    | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Streaming Service  | subscription startdate               | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Streaming Service  | subscription status                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Backend Streaming | user (internal) identifier           | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming | user email                           | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Backend Streaming | user name                            | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Backend Streaming | user surname                         | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Backend Streaming | user nickname                        | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming | user birthdate                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Backend Streaming | user gender                          | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 0.0 | 0.0 | 13.0 |
| Backend Streaming | profile identifier                   | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming | profile kids                         | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 0.0 | 0.0 | 13.0 |
| Backend Streaming | subscription (internal) identifier   | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming | subscription user identifier        | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming | metadata identifier                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Backend Streaming | stream start                         | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Backend Streaming | stream end                           | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| **Total VSs**     |                                      |      |      |      |      |     |     |     |     | **535.9** |

### Historical Layer Vulnerability Score

| Source               | Field Name                          | ENCD | ENCR | MASK | EXPL | HPI  | HSI  | HNS  | HUS  | VS   |
|----------------------|-----------------------------------|------|------|------|------|------|------|------|------|------|
| Streaming Service   | user (internal) identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0  | 0.0  | 0.0  | 0.0  | 11.0  |
| Streaming Service   | user login                      | 2.0  | 2.0  | 1.5  | 1.8  | 1.0  | 1.0  | 0.0  | 0.0  | 11.4  |
| Streaming Service   | user password                   | 2.0  | 1.2  | 1.5  | 2.0  | 1.0  | 1.0  | 0.0  | 0.0  | 9.6   |
| Streaming Service   | user email                      | 2.0  | 2.0  | 1.5  | 1.8  | 1.0  | 1.0  | 0.0  | 0.0  | 11.4  |
| Streaming Service   | user name                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0  | 0.0  | 0.0  | 0.0  | 11.6  |
| Streaming Service   | user surname                    | 2.0  | 2.0  | 2.0  | 1.8  | 1.0  | 0.0  | 0.0  | 0.0  | 11.6  |
| Streaming Service   | user nickname                   | 2.0  | 2.0  | 2.0  | 1.5  | 1.0  | 0.0  | 0.0  | 0.0  | 11.0  |
| Streaming Service   | user birthdate                  | 2.0  | 2.0  | 2.0  | 1.8  | 1.0  | 1.0  | 0.0  | 0.0  | 13.4  |
| Streaming Service   | user gender                     | 2.0  | 2.0  | 2.0  | 2.0  | 0.5  | 1.0  | 0.0  | 0.0  | 13.0  |
| Streaming Service   | user address                    | 2.0  | 2.0  | 2.0  | 2.0  | 1.0  | 1.0  | 0.0  | 0.0  | 14.0  |
| Streaming Service   | user city                       | 2.0  | 2.0  | 2.0  | 2.0  | 1.0  | 1.0  | 0.0  | 0.0  | 14.0  |
| Streaming Service   | user country                    | 2.0  | 2.0  | 2.0  | 1.8  | 0.5  | 0.0  | 0.0  | 0.0  | 10.7  |
| Streaming Service   | user postcode                   | 2.0  | 2.0  | 2.0  | 2.0  | 1.0  | 1.0  | 0.0  | 0.0  | 14.0  |
| Subscription Mgmt   | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0  | 0.0  | 0.0  | 0.0  | 11.0  |
| Subscription Mgmt   | subscription user identifier     | 2.0  | 2.0  | 2.0  | 1.5  | 1.0  | 0.0  | 0.0  | 0.0  | 11.0  |
| Subscription Mgmt   | subscription plan               | 2.0  | 2.0  | 2.0  | 1.2  | 0.0  | 0.0  | 0.0  | 0.0  | 9.2   |
| Subscription Mgmt   | subscription startdate          | 2.0  | 2.0  | 2.0  | 1.4  | 0.5  | 0.0  | 0.0  | 0.0  | 10.1  |
| Subscription Mgmt   | subscription status             | 2.0  | 2.0  | 2.0  | 1.2  | 0.0  | 0.0  | 0.0  | 0.0  | 9.2   |
| Backend Streaming   | user (internal) identifier      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0  | 0.0  | 0.0  | 0.0  | 11.0  |
| Backend Streaming   | user email                      | 2.0  | 2.0  | 1.5  | 1.8  | 1.0  | 1.0  | 0.0  | 0.0  | 11.4  |
| Backend Streaming   | user name                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0  | 0.0  | 0.0  | 0.0  | 11.6  |
| Backend Streaming   | user surname                    | 2.0  | 2.0  | 2.0  | 1.8  | 1.0  | 0.0  | 0.0  | 0.0  | 11.6  |
| Backend Streaming   | user nickname                   | 2.0  | 2.0  | 2.0  | 1.5  | 1.0  | 0.0  | 0.0  | 0.0  | 11.0  |
| Backend Streaming   | user birthdate                  | 2.0  | 2.0  | 2.0  | 1.8  | 1.0  | 1.0  | 0.0  | 0.0  | 13.4  |
| Backend Streaming   | user gender                     | 2.0  | 2.0  | 2.0  | 2.0  | 0.5  | 1.0  | 0.0  | 0.0  | 13.0  |
| Backend Streaming   | profile identifier              | 2.0  | 2.0  | 2.0  | 1.5  | 1.0  | 0.0  | 0.0  | 0.0  | 11.0  |
| Backend Streaming   | profile kids                    | 2.0  | 2.0  | 2.0  | 2.0  | 0.5  | 1.0  | 0.0  | 0.0  | 13.0  |
| Backend Streaming   | metadata identifier             | 2.0  | 2.0  | 2.0  | 1.2  | 0.0  | 0.0  | 0.0  | 0.0  | 9.2   |
| Backend Streaming   | stream start                    | 2.0  | 2.0  | 2.0  | 1.4  | 0.5  | 0.0  | 0.0  | 0.0  | 10.1  |
| Backend Streaming   | stream end                      | 2.0  | 2.0  | 2.0  | 1.2  | 0.0  | 0.0  | 0.0  | 0.0  | 9.2   |
| **Total VSs**       |                                  |      |      |      |      |      |      |      |      | **524.7** |

### Analytical Layer Vulnerability Score

| Source       | Field Name                         | ENCD | ENCR | MASK | EXPL | HPI  | HSI  | HNS  | HUS  | VS   |
|-------------|-----------------------------------|------|------|------|------|------|------|------|------|------|
| Centralized | user (internal) identifier       | 2,0  | 2,0  | 2,0  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 11,0 |
| Centralized | user login                       | 2,0  | 2,0  | 1,5  | 1,8  | 1,0  | 1,0  | 0,0  | 0,0  | 11,4 |
| Centralized | user password                    | 2,0  | 1,2  | 1,5  | 2,0  | 1,0  | 1,0  | 0,0  | 0,0  | 9,6  |
| Centralized | user email                       | 2,0  | 2,0  | 1,5  | 1,8  | 1,0  | 1,0  | 0,0  | 0,0  | 11,4 |
| Centralized | user name                        | 2,0  | 2,0  | 1,5  | 1,8  | 1,0  | 0,0  | 0,0  | 0,0  | 9,6  |
| Centralized | user surname                     | 2,0  | 2,0  | 1,5  | 1,8  | 1,0  | 0,0  | 0,0  | 0,0  | 9,6  |
| Centralized | user nickname                    | 2,0  | 2,0  | 1,5  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 9,0  |
| Centralized | user birthdate                   | 2,0  | 2,0  | 1,5  | 1,8  | 1,0  | 1,0  | 0,0  | 0,0  | 11,4 |
| Centralized | user gender                      | 2,0  | 2,0  | 1,5  | 2,0  | 0,5  | 1,0  | 0,0  | 0,0  | 11,0 |
| Centralized | user address                     | 2,0  | 2,0  | 1,5  | 2,0  | 1,0  | 1,0  | 0,0  | 0,0  | 12,0 |
| Centralized | user city                        | 2,0  | 2,0  | 1,5  | 2,0  | 1,0  | 1,0  | 0,0  | 0,0  | 12,0 |
| Centralized | user country                     | 2,0  | 2,0  | 2,0  | 1,8  | 0,5  | 0,0  | 0,0  | 0,0  | 10,7 |
| Centralized | user postcode                    | 2,0  | 2,0  | 1,5  | 2,0  | 1,0  | 1,0  | 0,0  | 0,0  | 12,0 |
| Centralized | subscription (internal) identifier | 2,0  | 2,0  | 2,0  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 11,0 |
| Centralized | subscription user identifier     | 2,0  | 2,0  | 2,0  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 11,0 |
| Centralized | subscription plan                | 2,0  | 2,0  | 2,0  | 1,2  | 0,0  | 0,0  | 0,0  | 0,0  | 9,2  |
| Centralized | subscription startdate           | 2,0  | 2,0  | 2,0  | 1,4  | 0,5  | 0,0  | 0,0  | 0,0  | 10,1 |
| Centralized | subscription status              | 2,0  | 2,0  | 2,0  | 1,2  | 0,0  | 0,0  | 0,0  | 0,0  | 9,2  |
| Centralized | subscription last login          | 2,0  | 2,0  | 2,0  | 1,8  | 0,0  | 0,0  | 0,0  | 0,0  | 9,8  |
| Centralized | subscription app access          | 2,0  | 2,0  | 2,0  | 1,8  | 0,0  | 0,0  | 0,0  | 0,0  | 9,8  |
| Centralized | profile identifier               | 2,0  | 2,0  | 2,0  | 1,8  | 1,0  | 0,0  | 0,0  | 0,0  | 11,6 |
| Centralized | profile name                     | 2,0  | 2,0  | 2,0  | 1,5  | 0,5  | 0,0  | 0,0  | 0,0  | 10,3 |
| Centralized | profile identifier               | 2,0  | 2,0  | 2,0  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 11,0 |
| Centralized | profile kids                     | 2,0  | 2,0  | 2,0  | 2,0  | 0,5  | 1,0  | 0,0  | 0,0  | 13,0 |
| Centralized | metadata identifier              | 2,0  | 2,0  | 2,0  | 1,2  | 0,0  | 0,0  | 0,0  | 0,0  | 9,2  |
| Centralized | stream start                     | 2,0  | 2,0  | 2,0  | 1,4  | 0,5  | 0,0  | 0,0  | 0,0  | 10,1 |
| Centralized | stream end                       | 2,0  | 2,0  | 2,0  | 1,2  | 0,0  | 0,0  | 0,0  | 0,0  | 9,2  |
| **Total VSs**       |                                  |      |      |      |      |      |      |      |      | **285,2** |


### Data Sharing Layer Vulnerability Score

| Source       | Field Name                         | ENCD | ENCR | MASK | EXPL | HPI  | HSI  | HNS  | HUS  | VS   |
|-------------|-----------------------------------|------|------|------|------|------|------|------|------|------|
| Centralized | user (internal) identifier       | 2,0  | 2,0  | 2,0  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 11,0 |
| Centralized | user email                       | 2,0  | 2,0  | 1,5  | 1,8  | 1,0  | 1,0  | 0,0  | 0,0  | 11,4 |
| Centralized | user name                        | 2,0  | 2,0  | 1,5  | 1,8  | 1,0  | 0,0  | 0,0  | 0,0  | 9,6  |
| Centralized | user surname                     | 2,0  | 2,0  | 1,5  | 1,8  | 1,0  | 0,0  | 0,0  | 0,0  | 9,6  |
| Centralized | user nickname                    | 2,0  | 2,0  | 1,5  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 9,0  |
| Centralized | user birthdate                   | 2,0  | 2,0  | 1,5  | 1,8  | 1,0  | 1,0  | 0,0  | 0,0  | 11,4 |
| Centralized | user gender                      | 2,0  | 2,0  | 1,5  | 2,0  | 0,5  | 1,0  | 0,0  | 0,0  | 11,0 |
| Centralized | subscription (internal) identifier | 2,0  | 2,0  | 2,0  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 11,0 |
| Centralized | subscription plan                | 2,0  | 2,0  | 2,0  | 1,2  | 0,0  | 0,0  | 0,0  | 0,0  | 9,2  |
| Centralized | subscription startdate           | 2,0  | 2,0  | 2,0  | 1,4  | 0,5  | 0,0  | 0,0  | 0,0  | 10,1 |
| Centralized | subscription status              | 2,0  | 2,0  | 2,0  | 1,2  | 0,0  | 0,0  | 0,0  | 0,0  | 9,2  |
| Centralized | subscription last login          | 2,0  | 2,0  | 2,0  | 1,8  | 0,0  | 0,0  | 0,0  | 0,0  | 9,8  |
| Centralized | subscription app access          | 2,0  | 2,0  | 2,0  | 1,8  | 0,0  | 0,0  | 0,0  | 0,0  | 9,8  |
| Centralized | profile identifier               | 2,0  | 2,0  | 2,0  | 1,8  | 1,0  | 0,0  | 0,0  | 0,0  | 11,6 |
| Centralized | profile name                     | 2,0  | 2,0  | 2,0  | 1,5  | 0,5  | 0,0  | 0,0  | 0,0  | 10,3 |
| Centralized | profile identifier               | 2,0  | 2,0  | 2,0  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 11,0 |
| Centralized | profile kids                     | 2,0  | 2,0  | 2,0  | 2,0  | 0,5  | 1,0  | 0,0  | 0,0  | 13,0 |
| Centralized | metadata identifier              | 2,0  | 2,0  | 2,0  | 1,2  | 0,0  | 0,0  | 0,0  | 0,0  | 9,2  |
| Centralized | stream start                     | 2,0  | 2,0  | 2,0  | 1,4  | 0,5  | 0,0  | 0,0  | 0,0  | 10,1 |
| Centralized | stream end                       | 2,0  | 2,0  | 2,0  | 1,2  | 0,0  | 0,0  | 0,0  | 0,0  | 9,2  |
| **Total VSs**       |                                  |      |      |      |      |      |      |      |      | **206,5** |


### Streaming Service Privacy Risk Expansion Factor

| Copy Type               | G   | A   | R   | D   | L   | PREF |
|------------------------|-----|-----|-----|-----|-----|------|
| Main Copy              | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3.00 |
| Secondary Copy         | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3.00 |
| Disaster Recovery Copy | 2.00 | 1.00 | 0.00 | 0.50 | 1.00 | 5.00 |
| Daily Backup           | 1.00 | 1.50 | 0.00 | 0.00 | 0.00 | 1.50 |
| **Total PREF**         |      |      |      |      |      | **12.50** |


### Subscription Management Service Privacy Risk Expansion Factor

| Copy Type               | G   | A   | R   | D   | L   | PREF |
|------------------------|-----|-----|-----|-----|-----|------|
| Main Copy              | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3.00 |
| Secondary Copy         | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3.00 |
| Disaster Recovery Copy | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3.00 |
| Daily Backup           | 1.00 | 1.50 | 0.00 | 0.00 | 0.00 | 1.50 |
| **Total PREF**         |      |      |      |      |      | **10.50** |


### Backend Streaming Hosting Service Privacy Risk Expansion Factor

| Copy Type               | G   | A   | R   | D   | L   | PREF |
|------------------------|-----|-----|-----|-----|-----|------|
| Main Copy              | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3.00 |
| Secondary Copy         | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3.00 |
| Disaster Recovery Copy | 1.00 | 1.00 | 0.00 | 0.50 | 1.00 | 2.50 |
| Daily Backup           | 1.00 | 1.50 | 0.00 | 0.00 | 0.00 | 1.50 |
| **Total PREF**         |      |      |      |      |      | **10.00** |


### Landing Privacy Risk Expansion Factor

| Copy Type      | G   | A   | R   | D   | L   | PREF |
|----------------|-----|-----|-----|-----|-----|------|
| Main Copy      | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2.00 |
| Secondary Copy | 1.00 | 1.00 | 0.00 | 0.50 | 0.00 | 1.50 |
| Weekly Backup  | 1.00 | 1.50 | 0.50 | 0.00 | 0.00 | 2.25 |
| **Total PREF** |      |      |      |      |      | **5.75** |


### Staging Privacy Risk Expansion Factor

| Copy Type      | G   | A   | R   | D   | L   | PREF |
|----------------|-----|-----|-----|-----|-----|------|
| Main Copy      | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2.00 |
| Secondary Copy | 1.00 | 1.00 | 0.00 | 0.00 | 0.00 | 1.00 |
| Weekly Backup  | 1.00 | 1.50 | 0.00 | 0.00 | 0.00 | 1.50 |
| **Total PREF** |      |      |      |      |      | **4.50** |


### Historical Privacy Risk Expansion Factor

| Copy Type      | G   | A   | R   | D   | L   | PREF |
|----------------|-----|-----|-----|-----|-----|------|
| Main Copy      | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2.00 |
| Secondary Copy | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2.00 |
| Weekly Backup  | 1.00 | 1.50 | 0.00 | 0.00 | 0.00 | 1.50 |
| **Total PREF** |      |      |      |      |      | **5.50** |


### Analytical Privacy Risk Expansion Factor

| Copy Type      | G   | A   | R   | D   | L   | PREF |
|----------------|-----|-----|-----|-----|-----|------|
| Main Copy      | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2.00 |
| Secondary Copy | 1.00 | 1.00 | 0.00 | 0.00 | 0.00 | 1.00 |
| Weekly Backup  | 1.00 | 1.50 | 0.00 | 0.00 | 0.00 | 1.50 |
| **Total PREF** |      |      |      |      |      | **4.50** |

### Sharing Privacy Risk Expansion Factor

| Copy Type      | G   | A   | R   | D   | L   | PREF |
|----------------|-----|-----|-----|-----|-----|------|
| Main Copy      | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2.00 |
| Secondary Copy | 1.00 | 1.00 | 0.00 | 0.00 | 0.00 | 1.00 |
| Manual Backup  | 1.00 | 1.50 | 0.50 | 0.00 | 0.00 | 2.25 |
| **Total PREF** |      |      |      |      |      | **5.25** |

### Privacy-Aware Ecosystem Architecture 

### Streaming Service Layer Vulnerability Score  

| Field Name                         | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS   |
|-----------------------------------|------|------|------|------|-----|-----|-----|-----|------|
| user (internal) identifier        | 2,0  | 2,0  | 2,0  | 1,5  | 1,0 | 0,0 | 0,0 | 0,0 | 11,0 |
| user login                        | 2,0  | 2,0  | 2,0  | 1,8  | 1,0 | 1,0 | 0,0 | 0,0 | 13,4 |
| user password                     | 2,0  | 1,2  | 2,0  | 2,0  | 1,0 | 1,0 | 0,0 | 0,0 | 10,8 |
| user email                        | 2,0  | 2,0  | 2,0  | 1,8  | 1,0 | 1,0 | 0,0 | 0,0 | 13,4 |
| user name                         | 2,0  | 2,0  | 2,0  | 1,8  | 1,0 | 0,0 | 0,0 | 0,0 | 11,6 |
| user surname                      | 2,0  | 2,0  | 2,0  | 1,8  | 1,0 | 0,0 | 0,0 | 0,0 | 11,6 |
| user nickname                     | 2,0  | 2,0  | 2,0  | 1,5  | 1,0 | 0,0 | 0,0 | 0,0 | 11,0 |
| user birthdate                    | 2,0  | 2,0  | 2,0  | 1,8  | 1,0 | 1,0 | 0,0 | 0,0 | 13,4 |
| user gender                       | 2,0  | 2,0  | 2,0  | 2,0  | 0,5 | 1,0 | 0,0 | 0,0 | 13,0 |
| user address                      | 2,0  | 2,0  | 2,0  | 2,0  | 1,0 | 1,0 | 0,0 | 0,0 | 14,0 |
| user city                         | 2,0  | 2,0  | 2,0  | 2,0  | 1,0 | 1,0 | 0,0 | 0,0 | 14,0 |
| user country                      | 2,0  | 2,0  | 2,0  | 1,8  | 0,5 | 0,0 | 0,0 | 0,0 | 10,7 |
| user postcode                     | 2,0  | 2,0  | 2,0  | 2,0  | 1,0 | 1,0 | 0,0 | 0,0 | 14,0 |
| subscription (internal) identifier| 2,0  | 2,0  | 2,0  | 1,5  | 1,0 | 0,0 | 0,0 | 0,0 | 11,0 |
| subscription user identifier      | 2,0  | 2,0  | 2,0  | 1,5  | 1,0 | 0,0 | 0,0 | 0,0 | 11,0 |
| subscription plan                 | 2,0  | 2,0  | 2,0  | 1,2  | 0,0 | 0,0 | 0,0 | 0,0 | 9,2  |
| subscription startdate           | 2,0  | 2,0  | 2,0  | 1,4  | 0,5 | 0,0 | 0,0 | 0,0 | 10,1 |
| subscription status               | 2,0  | 2,0  | 2,0  | 1,2  | 0,0 | 0,0 | 0,0 | 0,0 | 9,2  |
| **Total VSs**                      |      |      |      |      |     |     |     |     | **212.4** |


### Subscription Management Service Layer Vulnerability Score  

| Field Name                         | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS   |
|-----------------------------------|------|------|------|------|-----|-----|-----|-----|------|
| subscription (internal) identifier| 2,0  | 2,0  | 2,0  | 1,5  | 1,0 | 0,0 | 0,0 | 0,0 | 11,0 |
| subscription user identifier      | 2,0  | 2,0  | 2,0  | 1,5  | 1,0 | 0,0 | 0,0 | 0,0 | 11,0 |
| subscription plan                 | 2,0  | 2,0  | 2,0  | 1,2  | 0,0 | 0,0 | 0,0 | 0,0 | 9,2  |
| subscription startdate           | 2,0  | 2,0  | 2,0  | 1,4  | 0,5 | 0,0 | 0,0 | 0,0 | 10,1 |
| subscription status               | 2,0  | 2,0  | 2,0  | 1,2  | 0,0 | 0,0 | 0,0 | 0,0 | 9,2  |
| subscription last login           | 2,0  | 2,0  | 2,0  | 1,8  | 0,0 | 0,0 | 0,0 | 0,0 | 9,8  |
| subscription app access           | 2,0  | 2,0  | 2,0  | 1,8  | 0,0 | 0,0 | 0,0 | 0,0 | 9,8  |
| profile identifier                | 2,0  | 2,0  | 2,0  | 1,8  | 1,0 | 0,0 | 0,0 | 0,0 | 11,6 |
| profile name                      | 2,0  | 2,0  | 2,0  | 1,5  | 0,5 | 0,0 | 0,0 | 0,0 | 10,3 |
| user (internal) identifier        | 2,0  | 2,0  | 2,0  | 1,5  | 1,0 | 0,0 | 0,0 | 0,0 | 11,0 |
| user login                        | 2,0  | 2,0  | 2,0  | 1,8  | 1,0 | 1,0 | 0,0 | 0,0 | 13,4 |
| user email                        | 2,0  | 2,0  | 2,0  | 1,8  | 1,0 | 1,0 | 0,0 | 0,0 | 13,4 |
| user name                         | 2,0  | 2,0  | 2,0  | 1,8  | 1,0 | 0,0 | 0,0 | 0,0 | 11,6 |
| user surname                      | 2,0  | 2,0  | 2,0  | 1,8  | 1,0 | 0,0 | 0,0 | 0,0 | 11,6 |
| user nickname                     | 2,0  | 2,0  | 2,0  | 1,5  | 1,0 | 0,0 | 0,0 | 0,0 | 11,0 |
| **Total VSs**                      |      |      |      |      |     |     |     |     | **164,0** |

### Backend Streaming Hosting Service Layer Vulnerability Score  

| Source            | Field Name                            | ENCD | ENCR | MASK | EXPL | HPI  | HSI  | HNS  | HUS  | VS   |
|------------------|----------------------------------------|------|------|------|------|------|------|------|------|------|
| Backend Streaming | user (internal) identifier             | 2,0  | 2,0  | 2,0  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 11,0 |
| Backend Streaming | user email                             | 2,0  | 2,0  | 2,0  | 1,8  | 1,0  | 1,0  | 0,0  | 0,0  | 13,4 |
| Backend Streaming | user name                              | 2,0  | 2,0  | 2,0  | 1,8  | 1,0  | 0,0  | 0,0  | 0,0  | 11,6 |
| Backend Streaming | user surname                           | 2,0  | 2,0  | 2,0  | 1,8  | 1,0  | 0,0  | 0,0  | 0,0  | 11,6 |
| Backend Streaming | user nickname                          | 2,0  | 2,0  | 2,0  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 11,0 |
| Backend Streaming | user birthdate                         | 2,0  | 2,0  | 2,0  | 1,8  | 1,0  | 1,0  | 0,0  | 0,0  | 13,4 |
| Backend Streaming | user gender                            | 2,0  | 2,0  | 2,0  | 2,0  | 0,5  | 1,0  | 0,0  | 0,0  | 13,0 |
| Backend Streaming | profile identifier                     | 2,0  | 2,0  | 2,0  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 11,0 |
| Backend Streaming | profile kids                           | 2,0  | 2,0  | 2,0  | 2,0  | 0,5  | 1,0  | 0,0  | 0,0  | 13,0 |
| Backend Streaming | subscription (internal) identifier     | 2,0  | 2,0  | 2,0  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 11,0 |
| Backend Streaming | subscription user identifier           | 2,0  | 2,0  | 2,0  | 1,5  | 1,0  | 0,0  | 0,0  | 0,0  | 11,0 |
| Backend Streaming | metadata identifier                    | 2,0  | 2,0  | 2,0  | 1,2  | 0,0  | 0,0  | 0,0  | 0,0  | 9,2  |
| Backend Streaming | stream start                           | 2,0  | 2,0  | 2,0  | 1,4  | 0,5  | 0,0  | 0,0  | 0,0  | 10,1 |
| Backend Streaming | stream end                             | 2,0  | 2,0  | 2,0  | 1,2  | 0,0  | 0,0  | 0,0  | 0,0  | 9,2  |
| **Total VSs**                      |      |      |      |      |     |     |     |     |      | **159,5** |


### Landing Sensitive Vulnerability Score  

| Source             | Field Name                         | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS   |
|--------------------|------------------------------------|------|------|------|------|-----|-----|-----|-----|------|
| Streaming Service  | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | user login                         | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Streaming Service  | user password                      | 2.0  | 1.2  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 10.8 |
| Streaming Service  | user email                         | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Streaming Service  | user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Streaming Service  | user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Streaming Service  | user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | user birthdate                     | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Streaming Service  | user gender                        | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 0.0 | 0.0 | 13.0 |
| Streaming Service  | user address                       | 2.0  | 2.0  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 14.0 |
| Streaming Service  | user city                          | 2.0  | 2.0  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 14.0 |
| Streaming Service  | user country                       | 2.0  | 2.0  | 2.0  | 1.8  | 0.5 | 0.0 | 0.0 | 0.0 | 10.7 |
| Streaming Service  | user postcode                      | 2.0  | 2.0  | 2.0  | 2.0  | 1.0 | 1.0 | 0.0 | 0.0 | 14.0 |
| Streaming Service  | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | subscription plan                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 1.0 | 0.0 | 10.4 |
| Streaming Service  | subscription startdate             | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 1.0 | 0.0 | 11.5 |
| Streaming Service  | subscription status                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 1.0 | 0.0 | 10.4 |
| Subscription Mgmt  | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Subscription Mgmt  | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Subscription Mgmt  | subscription plan                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Subscription Mgmt  | subscription startdate             | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Subscription Mgmt  | subscription status                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Subscription Mgmt  | subscription last login            | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 | 9.8  |
| Subscription Mgmt  | subscription app access            | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 | 9.8  |
| Subscription Mgmt  | profile identifier                 | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 1.0 | 0.0 | 13.4 |
| Subscription Mgmt  | profile name                       | 2.0  | 2.0  | 2.0  | 1.5  | 0.5 | 0.0 | 1.0 | 0.0 | 11.8 |
| Subscription Mgmt  | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Subscription Mgmt  | user login                         | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 1.0 | 0.0 | 15.2 |
| Subscription Mgmt  | user email                         | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 1.0 | 0.0 | 15.2 |
| Subscription Mgmt  | user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 1.0 | 0.0 | 13.4 |
| Subscription Mgmt  | user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 1.0 | 0.0 | 13.4 |
| Subscription Mgmt  | user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Backend Streaming  | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 11.5 |
| Backend Streaming  | user email                         | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Backend Streaming  | user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Backend Streaming  | user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Backend Streaming  | user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | user birthdate                     | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 13.4 |
| Backend Streaming  | user gender                        | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 0.0 | 0.0 | 13.0 |
| Backend Streaming  | profile identifier                 | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Backend Streaming  | profile kids                       | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 1.0 | 0.0 | 15.0 |
| Backend Streaming  | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Backend Streaming  | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Backend Streaming  | metadata identifier                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Backend Streaming  | stream start                       | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Backend Streaming  | stream end                         | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| **Total VSs**      |                                    |      |      |      |      |     |     |     |     | **559.7** |


### Landing Clean Vulnerability Score  

| Source             | Field Name                         | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS   |
|--------------------|------------------------------------|------|------|------|------|-----|-----|-----|-----|------|
| Streaming Service  | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Streaming Service  | user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Streaming Service  | user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | user country                       | 2.0  | 2.0  | 2.0  | 1.8  | 0.5 | 0.0 | 0.0 | 0.0 | 10.7 |
| Streaming Service  | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | subscription plan                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 1.0 | 0.0 | 10.4 |
| Streaming Service  | subscription startdate             | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 1.0 | 0.0 | 11.5 |
| Streaming Service  | subscription status                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 1.0 | 0.0 | 10.4 |
| Subscription Mgmt  | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Subscription Mgmt  | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Subscription Mgmt  | subscription plan                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Subscription Mgmt  | subscription startdate             | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Subscription Mgmt  | subscription status                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Subscription Mgmt  | subscription last login            | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 | 9.8  |
| Subscription Mgmt  | subscription app access            | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 | 9.8  |
| Subscription Mgmt  | profile identifier                 | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 1.0 | 0.0 | 13.4 |
| Subscription Mgmt  | profile name                       | 2.0  | 2.0  | 2.0  | 1.5  | 0.5 | 0.0 | 1.0 | 0.0 | 11.8 |
| Subscription Mgmt  | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Subscription Mgmt  | user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 1.0 | 0.0 | 13.4 |
| Subscription Mgmt  | user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 1.0 | 0.0 | 13.4 |
| Subscription Mgmt  | user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Backend Streaming  | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Backend Streaming  | user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Backend Streaming  | user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | profile identifier                 | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Backend Streaming  | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Backend Streaming  | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 1.0 | 0.0 | 12.5 |
| Backend Streaming  | metadata identifier                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Backend Streaming  | stream start                       | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Backend Streaming  | stream end                         | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| **Total VSs**      |                                    |      |      |      |      |     |     |     |     | **368,5** |


### Staging Clean Vulnerability Score  

| Source             | Field Name                         | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS   |
|--------------------|------------------------------------|------|------|------|------|-----|-----|-----|-----|------|
| Streaming Service  | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Streaming Service  | user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Streaming Service  | user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | user country                       | 2.0  | 2.0  | 2.0  | 1.8  | 0.5 | 0.0 | 0.0 | 0.0 | 10.7 |
| Streaming Service  | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | subscription plan                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Streaming Service  | subscription startdate             | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Streaming Service  | subscription status                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Subscription Mgmt  | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Subscription Mgmt  | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Subscription Mgmt  | subscription plan                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Subscription Mgmt  | subscription startdate             | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Subscription Mgmt  | subscription status                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Subscription Mgmt  | subscription last login            | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 | 9.8  |
| Subscription Mgmt  | subscription app access            | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 | 9.8  |
| Subscription Mgmt  | profile identifier                 | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Subscription Mgmt  | profile name                       | 2.0  | 2.0  | 2.0  | 1.5  | 0.5 | 0.0 | 0.0 | 0.0 | 10.3 |
| Subscription Mgmt  | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Subscription Mgmt  | user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Subscription Mgmt  | user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Subscription Mgmt  | user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Backend Streaming  | user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Backend Streaming  | user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | profile identifier                 | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | metadata identifier                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Backend Streaming  | stream start                       | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Backend Streaming  | stream end                         | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| **Total VSs**      |                                    |      |      |      |      |     |     |     |     | **350.3** |


### Historical Layer Clean Vulnerability Score  

| Source             | Field Name                         | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS   |
|--------------------|------------------------------------|------|------|------|------|-----|-----|-----|-----|------|
| Streaming Service  | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Streaming Service  | user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Streaming Service  | user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | user country                       | 2.0  | 2.0  | 2.0  | 1.8  | 0.5 | 0.0 | 0.0 | 0.0 | 10.7 |
| Streaming Service  | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Streaming Service  | subscription plan                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Streaming Service  | subscription startdate             | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Streaming Service  | subscription status                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Subscription Mgmt  | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Subscription Mgmt  | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Subscription Mgmt  | subscription plan                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Subscription Mgmt  | subscription startdate             | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Subscription Mgmt  | subscription status                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Subscription Mgmt  | subscription last login            | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 | 9.8  |
| Subscription Mgmt  | subscription app access            | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 | 9.8  |
| Subscription Mgmt  | profile identifier                 | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Subscription Mgmt  | profile name                       | 2.0  | 2.0  | 2.0  | 1.5  | 0.5 | 0.0 | 0.0 | 0.0 | 10.3 |
| Subscription Mgmt  | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Subscription Mgmt  | user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Subscription Mgmt  | user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Subscription Mgmt  | user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | user name                          | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Backend Streaming  | user surname                       | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Backend Streaming  | user nickname                      | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | profile identifier                 | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Backend Streaming  | metadata identifier                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Backend Streaming  | stream start                       | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Backend Streaming  | stream end                         | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| **Total VSs**      |                                    |      |      |      |      |     |     |     |     | **350.3** |


### Analytical Layer Clean Vulnerability Score  

| Source             | Field Name                         | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS   |
|--------------------|------------------------------------|------|------|------|------|-----|-----|-----|-----|------|
| Centralized        | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Centralized        | user name                          | 2.0  | 2.0  | 1.5  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 9.6  |
| Centralized        | user surname                       | 2.0  | 2.0  | 1.5  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 9.6  |
| Centralized        | user nickname                      | 2.0  | 2.0  | 1.5  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 9.0  |
| Centralized        | user country                       | 2.0  | 2.0  | 2.0  | 1.8  | 0.5 | 0.0 | 0.0 | 0.0 | 10.7 |
| Centralized        | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Centralized        | subscription user identifier       | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Centralized        | subscription plan                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Centralized        | subscription startdate             | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Centralized        | subscription status                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Centralized        | subscription last login            | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 | 9.8  |
| Centralized        | subscription app access            | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 | 9.8  |
| Centralized        | profile identifier                 | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Centralized        | profile name                       | 2.0  | 2.0  | 2.0  | 1.5  | 0.5 | 0.0 | 0.0 | 0.0 | 10.3 |
| Centralized        | profile identifier                 | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Centralized        | metadata identifier                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Centralized        | stream start                       | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Centralized        | stream end                         | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| **Total VSs**      |                                    |      |      |      |      |     |     |     |     | **181.4** |


### Data Sharing Vulnerability Score  

| Source             | Field Name                         | ENCD | ENCR | MASK | EXPL | HPI | HSI | HNS | HUS | VS   |
|--------------------|------------------------------------|------|------|------|------|-----|-----|-----|-----|------|
| Centralized        | user (internal) identifier         | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Centralized        | user email                         | 2.0  | 2.0  | 1.5  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 11.4 |
| Centralized        | user name                          | 2.0  | 2.0  | 1.5  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 9.6  |
| Centralized        | user surname                       | 2.0  | 2.0  | 1.5  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 9.6  |
| Centralized        | user nickname                      | 2.0  | 2.0  | 1.5  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 9.0  |
| Centralized        | user birthdate                     | 2.0  | 2.0  | 1.5  | 1.8  | 1.0 | 1.0 | 0.0 | 0.0 | 11.4 |
| Centralized        | user gender                        | 2.0  | 2.0  | 1.5  | 2.0  | 0.5 | 1.0 | 0.0 | 0.0 | 11.0 |
| Centralized        | subscription (internal) identifier | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Centralized        | subscription plan                  | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Centralized        | subscription startdate             | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Centralized        | subscription status                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Centralized        | subscription last login            | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 | 9.8  |
| Centralized        | subscription app access            | 2.0  | 2.0  | 2.0  | 1.8  | 0.0 | 0.0 | 0.0 | 0.0 | 9.8  |
| Centralized        | profile identifier                 | 2.0  | 2.0  | 2.0  | 1.8  | 1.0 | 0.0 | 0.0 | 0.0 | 11.6 |
| Centralized        | profile name                       | 2.0  | 2.0  | 2.0  | 1.5  | 0.5 | 0.0 | 0.0 | 0.0 | 10.3 |
| Centralized        | profile identifier                 | 2.0  | 2.0  | 2.0  | 1.5  | 1.0 | 0.0 | 0.0 | 0.0 | 11.0 |
| Centralized        | profile kids                       | 2.0  | 2.0  | 2.0  | 2.0  | 0.5 | 1.0 | 0.0 | 0.0 | 13.0 |
| Centralized        | metadata identifier                | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| Centralized        | stream start                       | 2.0  | 2.0  | 2.0  | 1.4  | 0.5 | 0.0 | 0.0 | 0.0 | 10.1 |
| Centralized        | stream end                         | 2.0  | 2.0  | 2.0  | 1.2  | 0.0 | 0.0 | 0.0 | 0.0 | 9.2  |
| **Total VSs**      |                                    |      |      |      |      |     |     |     |     | **206.5** |


### Streaming Service Privacy Risk Expansion Factor

| Source             | G    | A    | R    | D    | L    | PREF |
|--------------------|------|------|------|------|------|------|
| Main Copy          | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3    |
| Secondary Copy     | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3    |
| Disaster Recovery Copy | 2.00 | 1.00 | 0.00 | 0.50 | 1.00 | 5    |
| Daily Backup       | 1.00 | 1.50 | 0.00 | 0.00 | 0.00 | 1.5  |
| **Total PREF** |      |      |      |      |      | **12.5** |

### Subscription Management Service Privacy Risk Expansion Factor

| Source             | G    | A    | R    | D    | L    | PREF |
|--------------------|------|------|------|------|------|------|
| Main Copy          | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3    |
| Secondary Copy     | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3    |
| Disaster Recovery Copy | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3    |
| Daily Backup       | 1.00 | 1.50 | 0.00 | 0.00 | 0.00 | 1.5  |
| **Total PREF** |      |      |      |      |      | **10.5** |

### Backend Streaming Hosting Service Privacy Risk Expansion Factor

| Source             | G    | A    | R    | D    | L    | PREF |
|--------------------|------|------|------|------|------|------|
| Main Copy          | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3    |
| Secondary Copy     | 1.00 | 1.00 | 0.00 | 1.00 | 1.00 | 3    |
| Disaster Recovery Copy | 1.00 | 1.00 | 0.00 | 0.50 | 1.00 | 2.5  |
| Daily Backup       | 1.00 | 1.50 | 0.00 | 0.00 | 0.00 | 1.5  |
| **Total PREF** |      |      |      |      |      | **10.0** |

### Landing Sensitive Privacy Risk Expansion Factor

| Source             | G    | A    | R    | D    | L    | PREF |
|--------------------|------|------|------|------|------|------|
| Main Copy          | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2    |
| Secondary Copy     | 1.00 | 1.00 | 0.00 | 0.50 | 0.00 | 1.5  |
| Weekly Backup      | 1.00 | 1.50 | 0.50 | 0.00 | 0.00 | 2.25 |
| **Total PREF** |      |      |      |      |      | **5.75** |

### Landing Clean Privacy Risk Expansion Factor

| Source             | G    | A    | R    | D    | L    | PREF |
|--------------------|------|------|------|------|------|------|
| Main Copy          | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2    |
| Secondary Copy     | 1.00 | 1.00 | 0.00 | 0.50 | 0.00 | 1.5  |
| Weekly Backup      | 1.00 | 1.50 | 0.50 | 0.00 | 0.00 | 2.25 |
| **Total PREF** |      |      |      |      |      | **5.75** |

### Staging Clean Privacy Risk Expansion Factor

| Source             | G    | A    | R    | D    | L    | PREF |
|--------------------|------|------|------|------|------|------|
| Main Copy          | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2    |
| Secondary Copy     | 1.00 | 1.00 | 0.00 | 0.00 | 0.00 | 1    |
| Weekly Backup      | 1.00 | 1.50 | 0.00 | 0.00 | 0.00 | 1.5  |
| **Total PREF** |      |      |      |      |      | **4.5** |

### Historical Clean Privacy Risk Expansion Factor

| Source             | G    | A    | R    | D    | L    | PREF |
|--------------------|------|------|------|------|------|------|
| Main Copy          | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2    |
| Secondary Copy     | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2    |
| Weekly Backup      | 1.00 | 1.50 | 0.00 | 0.00 | 0.00 | 1.5  |
| **Total PREF** |      |      |      |      |      | **5.5** |

### Analytical Clean Privacy Risk Expansion Factor

| Source             | G    | A    | R    | D    | L    | PREF |
|--------------------|------|------|------|------|------|------|
| Main Copy          | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2    |
| Secondary Copy     | 1.00 | 1.00 | 0.00 | 0.00 | 0.00 | 1    |
| Weekly Backup      | 1.00 | 1.50 | 0.00 | 0.00 | 0.00 | 1.5  |
| **Total PREF** |      |      |      |      |      | **4.5** |

### Sharing Privacy Risk Expansion Factor

| Source             | G    | A    | R    | D    | L    | PREF |
|--------------------|------|------|------|------|------|------|
| Main Copy          | 1.00 | 1.00 | 0.00 | 1.00 | 0.00 | 2    |
| Secondary Copy     | 1.00 | 1.00 | 0.00 | 0.00 | 0.00 | 1    |
| Manual Backup      | 1.00 | 1.50 | 0.50 | 0.00 | 0.00 | 2.25 |
| **Total PREF** |      |      |      |      |      | **5.25** |
