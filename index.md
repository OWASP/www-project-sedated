---

layout: col-sidebar
title: OWASP SEDATED®
tags: sensitive-data-exposure git
level: 0
type: code
auto-migrated: 0
pitch: The SEDATED® Project (Sensitive Enterprise Data Analyzer To Eliminate Disclosure) focuses on preventing sensitive data such as user credentials and tokens from being pushed to Git.

---

![SEDATED_logo_full](https://raw.githubusercontent.com/OWASP/www-project-sedated/master/assets/images/SEDATED_logo_full.png)

<!-- Standard Chapter Page Template
This is an example of a Project or Chapter page.
Please change these items to indicate the actual information you wish to present. In addition to this information, the 'front-matter' above the text should be modified to reflect your actual information.  An explanation of each of the front-matter items is below: -->

The **SEDATED&#174;** Project (Sensitive Enterprise Data Analyzer To Eliminate Disclosure) focuses in on preventing sensitive data such as user credentials and tokens from being pushed to Git. Developers are constantly pushing changes to GitHub and will most likely eventually try pushing a commit that contains sensitive information and we want to help catch and prevent that. The **SEDATED&#174;** application will run on the Git server and review all incoming code changes. If it identifies sensitive data it will reject the push otherwise it will allow it.

## Purpose
With the myriad of code changes required in today's CICD environment developers are constantly pushing code that could unintentionally contain sensitive information. This potential sensitive data exposure represents a huge risk to organizations ([2021 OWASP Top Ten #2 - Cryptographic Failures](https://owasp.org/Top10/A02_2021-Cryptographic_Failures)). **SEDATED&#174;** addresses this issue by automatically reviewing all incoming code changes and providing instant feedback to the developer. If it identifies sensitive data it will prevent the commit(s) from being pushed to the Git server.

## Latest Version
[Version 1.2.0](https://github.com/OWASP/SEDATED/releases/tag/v1.2.0) is the latest version!

## Getting Involved
We are looking for community support with this project as there is a lot more we can do! Feel free to checkout the **[OWASP/SEDATED®](https://github.com/owasp/sedated)** repository and contribute any ideas you may have to make **SEDATED®** even better!

