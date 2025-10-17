---
title: "cv.md"
draft: false
weight: 0
toc: true
keywords:
- dre
- oorschot
- software
- developer
- programming
- cv
- curriculum
- vitae
description: CV of Dré van Oorschot
---

<script>
    const tags = [".sql", ".csv", ".json", ".so", ".sh", ".dll", ".exe", ".py", ".java", ".class",
        ".jar", ".cpp", ".c", ".o", ".ll", ".xml", ".yaml", ".toml", ".txt", ".js", ".html", ".css",
        ".log", ".zip", ".tar.gz", ".hs", ".cs"]
        .map(value => ({ value, sort: Math.random() }))
        .sort((a, b) => a.sort - b.sort)
        .map(({ value }) => value);

    document.addEventListener("DOMContentLoaded", _ => {
        let headings = document.querySelectorAll("h2");
        headings.forEach(elem => {
            elem.innerHTML = elem.innerHTML + tags.pop();
        });
    });
</script>


## personal
===============

|                 |                  |
|-----------------|------------------|
| **Name**        | Dré van Oorschot |
| **Nationality** | 🇳🇱 Dutch         |

## education
================
|               |                                                         |
| ---           | ---                                                     |
| 2020 - 2023   | **MSc Computer Science (Software Technology)**          |
|               | University of Twente, 🇳🇱 Enschede                       |
|               | [Thesis](https://essay.utwente.nl/96536/) \| [Paper](https://link.springer.com/chapter/10.1007/978-3-031-57259-3_15)              |
|---------------|
| 2016 - 2020   | **BSc Technical Computer Science**                      |
|               | University of Twente, 🇳🇱 Enschede                       |
|               | [Thesis](https://essay.utwente.nl/80589/)               |
|---------------|
| 2010 - 2016   | **Bilingual Pre-university education (VWO)**            |
|               | Farel College, 🇳🇱 Amersfoort                            |
|               | <u>Certificates</u>:                                    |
|               | [2013 - 2016] **IB English** *Language A: Higher Level* |
|               | [2010 - 2013] **Cambridge English** *Advanced (CAE)*    |

## work-experience
=======================
|               |                                                               |
| ---           | ---                                                           |
| 2023 -        | **Software Engineer**                                         |
|               | Technolution B.V., 🇳🇱 Gouda                                   |
|               | <u>Functions:</u>                                             |
|               | - [2023 - 2025]                     Junior Software Engineer  |
|               | - [2025 - &nbsp;&nbsp;&nbsp;&nbsp;] Medior Software Engineer  |
|---------------|                                                               |
| 2017 - 2021   | **Student Assistent**                                         |
|               | <u>Courses:</u>                                               |
|               | - *Pearls of Computer Science*                                |
|               | - *Software Systems*                                          |
|               | - *Data & Information*                                        |
|               | - *Programming Paradigms*                                     |


## skills
=============
### Languages

|            |        |
|------------|--------|
| 🇳🇱 Dutch   | Native |
| 🇬🇧 English | C1/C2  |

### Programming
{{< overflow-x-box >}}
| Languages                                  | Frameworks/Standards                               | Databases                                  | Tools                                               | Methodology |
|--------------------------------------------|----------------------------------------------------|--------------------------------------------|-----------------------------------------------------|-------------|
| {{< tc/good >}} Python {{< /tc/good >}}    | {{< tc/good >}} Django {{< /tc/good >}}            | {{< tc/good >}} SQLite {{< /tc/good >}}    | {{< tc/good >}} Linux {{< /tc/good >}}              | OOP         |
| {{< tc/good >}} Java {{< /tc/good >}}      | {{< tc/good >}} Bootstrap {{< /tc/good >}}         | {{< tc/good >}} Postgres {{< /tc/good >}}  | {{< tc/good >}} git {{< /tc/good >}}                | TDD         |
| {{< tc/medium >}} C++ {{< /tc/medium >}}   | {{< tc/good >}} JUnit {{< /tc/good >}}             | {{< tc/good >}} MySQL {{< /tc/good >}}     | {{< tc/good >}} pip {{< /tc/good >}}                | CI/CD       |
| {{< tc/medium >}} Scala {{< /tc/medium >}} | {{< tc/good >}} Mockito {{< /tc/good >}}           | {{< tc/good >}} MariaDB {{< /tc/good >}}   | {{< tc/good >}} Maven {{< /tc/good >}}              | RESTful     |
| {{< tc/bad >}} C#/.NET {{< /tc/bad >}}     | {{< tc/good >}} Jersey/JAX-RS {{< /tc/good >}}     | {{< tc/medium >}} Redis {{< /tc/medium >}} | {{< tc/good >}} Docker {{< /tc/good >}}             | Agile/Scrum |
| {{< tc/bad >}} JavaScript {{< /tc/bad >}}  | {{< tc/medium >}} Hibernate/JPA {{< /tc/medium >}} | {{< tc/bad >}} MongoDB {{< /tc/bad >}}     | {{< tc/good >}} LLVM {{< /tc/good >}}               |             |
| {{< tc/bad >}} TypeScript {{< /tc/bad >}}  | {{< tc/medium >}} JQuery {{< /tc/medium >}}        |                                            | {{< tc/good >}} OpenAPI {{< /tc/good >}}            |             |
| {{< tc/bad >}} Bash {{< /tc/bad >}}        | {{< tc/medium >}} PKCS #11 {{< /tc/medium >}}      |                                            | {{< tc/good >}} nginx {{< /tc/good >}}              |             |
| {{< tc/bad >}} Haskell {{< /tc/bad >}}     | {{< tc/medium >}} ASN.1 {{< /tc/medium >}}         |                                            | {{< tc/good >}} Jupyter {{< /tc/good >}}            |             |
|                                            | {{< tc/medium >}} TLS/SSL {{< /tc/medium >}}       |                                            | {{< tc/good >}} Gradle {{< /tc/good >}}             |             |
|                                            | {{< tc/bad >}} Hugo {{< /tc/bad >}}                |                                            | {{< tc/good >}} GitLab CI/CD {{< /tc/good >}}       |             |
|                                            | {{< tc/bad >}} DropWizard {{< /tc/bad >}}          |                                            | {{< tc/good >}} cURL {{< /tc/good >}}               |             |
|                                            | {{< tc/bad >}} GRPC/Protobuf {{< /tc/bad >}}       |                                            | {{< tc/medium >}} Jira {{< /tc/medium >}}           |             |
|                                            | {{< tc/bad >}} AngularJS (1.x) {{< /tc/bad >}}     |                                            | {{< tc/medium >}} OpenSSL {{< /tc/medium >}}        |             |
|                                            |                                                    |                                            | {{< tc/medium >}} Pipenv {{< /tc/medium >}}         |             |
|                                            |                                                    |                                            | {{< tc/medium >}} RabbitMQ {{< /tc/medium >}}       |             |
|                                            |                                                    |                                            | {{< tc/medium >}} Antlr4 {{< /tc/medium >}}         |             |
|                                            |                                                    |                                            | {{< tc/medium >}} npm {{< /tc/medium >}}            |             |
|                                            |                                                    |                                            | {{< tc/medium >}} GitHub Actions {{< /tc/medium >}} |             |
|                                            |                                                    |                                            | {{< tc/medium >}} SonarQube {{< /tc/medium >}}      |             |
|                                            |                                                    |                                            | {{< tc/medium >}} CMake {{< /tc/medium >}}          |             |
|                                            |                                                    |                                            | {{< tc/bad >}} AndroidSDK {{< /tc/bad >}}           |             |
|                                            |                                                    |                                            | {{< tc/bad >}} Kubernetes {{< /tc/bad >}}           |             |
|                                            |                                                    |                                            | {{< tc/bad >}} Portainer {{< /tc/bad >}}            |             |
{{< /overflow-x-box >}}

## other-activities

|               |                                                           |
| ---           | ---                                                       |
| 2019 - 2021   | **Board D.T.T.V. Thibats**                                |
|               | *Official table tennis association University of Twente*  |
|               | [2019 - 2021] Chairman                                    |
|               | [2021 - 2021] Treasurer                                   |
|---------------|
| 2017 - 2022   | **Various Committees D.T.T.V. Thibats**                   |
|               | - *Website committee*                                     |
|               | - *Bar committee*                                         |
|               | - *Promotion committee*                                   |
|               | - *Event committee*                                       |
|               | - *Tournament committee*                                  |
|---------------|
| 2017 - 2018   | **Treasurer *Vereniging Campus Kabel***                   |
|               | *Student association that provided TV signal on campus*   |
|---------------|
| 2016 - 2018   | **Various committees Inter-Actief**                       |
|               | *Study association computer science University of Twente* |
|               | - *Website committee*                                     |
|               | - *Education committee*                                   |
|               | - *Event committee*                                       |
|               | - *Game Jam committee*                                    |
