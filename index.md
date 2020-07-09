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
With the myriad of code changes required in today's CICD environment developers are constantly pushing code that could unintentionally contain sensitive information. This potential sensitive data exposure represents a huge risk to organizations ([2017 OWASP Top Ten #3 - Sensitive Data Exposure](https://www.owasp.org/index.php/Top_10-2017_A3-Sensitive_Data_Exposure)). **SEDATED&#174;** addresses this issue by automatically reviewing all incoming code changes and providing instant feedback to the developer. If it identifies sensitive data it will prevent the commit(s) from being pushed to the Git server.

## What's New
[Version 1.2.0](https://github.com/OWASP/SEDATED/releases/tag/v1.2.0) is now available!

## Getting Involved
We are looking for community support with this project as there is a lot more we can do! Feel free to checkout the **[OWASP/SEDATED®](https://github.com/owasp/sedated)** repository and contribute any ideas you may have to make **SEDATED®** even better!

<!--
```
- layout: This is the layout used by project and chapter pages.  You should leave this value as col-sidebar
- title: This is the title of your project or chapter page, usually the name.  For example, OWASP Zed Attack Proxy or OWASP Baltimore
- tags: This is a space-delimited list of tags you associate with your project or chapter.  If you are using tabs, at least one of these tags should be unique in order to be used in the tabs files (an example tab is included in this repo) 
- region: This is the region you are in according to our data
```

{copy for this file (index.md)}
Replace the text above the commented area with your information in the format below:
```
## Welcome
Include some information here about your chapter

## Participation
The Open Web Application Security Project (OWASP) is a nonprofit foundation that works to improve the security of software. All of our projects ,tools, documents, forums, and chapters are free and open to anyone interested in improving application security. 

Chapters are led by local leaders in accordance with the [Chapter Leader Handbook](/www-policy/rules-of-procedure/chapter-handbook). Financial contributions should only be made online using the authorized online donation button. To be a SPEAKER at ANY OWASP Chapter in the world simply review the [speaker agreement](/www-policy/speaker-agreement) and then contact the local chapter leader with details of what OWASP Project, independent research, or related software security topic you would like to present.

Everyone is welcome and encouraged to participate in our [Projects](/projects), [Local Chapters](/chapters), [Events](/events), [Online Groups](https://groups.google.com/a/owasp.com/){:target='_blank'}, and [Community Slack Channel](https://owasp.slack.com/){:target='_blank'}. We especially encourage diversity in all our initiatives. OWASP is a fantastic place to learn about application security, to network, and even to build your reputation as an expert. We also encourage you to be [become a member](/membership) or consider a [donation](/donate) to support our ongoing work.

## Local News
- Meeting Location
- Everyone is welcome to join us at our chapter meetings.

```
{info.md}

This separate file is where you should place links to your Google Group and Meetup page. It will be automatically rendered in the column sidebar.

{leaders.md}

Another separate file that should simply include each leaders name with mailto link as a list. It will also be automatically rendered in the column sidebar.

-->
