# INTRODUCTION

The proposed test project aims to provide a comprehensive challenge in web development by covering six distinct modules. Each module focuses on different aspects of web design and development, ranging from static website design to advanced techniques and collaboration. This project aims to challenge competitors with a well-rounded skill set that encompasses both front-end and back-end development, as well as integration with external services through APIs.

This outline only describes the basic information of the module. The actual test project modules will be created by external Test Project Developers using this outline as a guide. The module description will be presented on C-2 to all experts. The marking scheme will not be presented or supplied to competitors or experts during the competition.

# DESCRIPTION OF PROJECT AND TASKS

The Test Project will consist of 6 modules with the following topics:

- Module **A**: Static Website Design (HTML/CSS)
- Module **B**: Dynamic website with server-side rendering
- Module **C**: REST API
- Module **D**: Interactive Frontend using an API
- Module **E**: Advanced Web Development
- Module **F**: Collaborative Challenge

These modules will be further described in this document.

# COMPETITION WEEK

There are 3 competition days.

C1: Sep 10th (WED): Module A & Module B

C2: Sep 11th (THU): Module C & Module D

C3: Sep 12th (FRI): Module E & Module F

# OUTLINE OF THE MODULES

## Module A – Static Website Design

**Introduction**

Module A will focus on the creation of a static website using HTML and CSS only.

### Description of project and tasks

The competitors will be asked to create a static website for a specified client. The website will consist of subpages which should be reachable under separate paths. The design of all subpages should be aligned.

The website must conform with accessibility standards (WCAG, at least level AA) and implement SEO best practices, as it will be used to attract new users for a product or service of the client.

Responsiveness is also important, and the website should look good on three different viewports: mobile, tablet, and desktop.

The client will supply the competitors with a defined website structure and will therein define all the pages and sections of the website. The client will also provide all content for the website, such as text, images, and other media, as well as the exact definitions of the responsive breakpoints.

No server-side or client-side framework will be allowed for module A. CSS preprocessors may be used, but the generated code must still pass the W3C validations. Framework and library availability will be limited and will be decided by all experts using the EuroSkills forums.

### Assessment

Module A will be assessed using the latest stable version of Google Chrome and Firefox. HTML and CSS will be assessed using W3C validators. Accessibility will be tested using axe.

**Competition time**

Competitors will have **3 hours** to complete module A.

### Mark distribution

The table below outlines how marks are broken down and how they align with the WorldSkills Occupation Standards (WSOS). Please read the Technical Description for a full explanation of the WorldSkills Occupation Standards.

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| 1   | Work organization and self-management | 1.5 |
| 2   | Communication and interpersonal skills | 0   |
| 3   | Design Implementation | 15  |
| 4   | Front-End Development | 0   |
| 5   | Back-End Development | 0   |
| **Total** |     | **16.5** |

## Module B Dynamic website with server-side rendering

**Introduction**

Module B will focus on the creation of a dynamic website using a server-side framework.

### Description of project and tasks

In this module, competitors will create a dynamically and server-side rendered website which the users of the product will use to manage their accounts and additional information.

Parts of the website are protected and only accessible after a successful login. As this website will be publicly exposed, it must implement the OWASP guidelines.

The client will provide a detailed description of all the required functionalities of this website. From that, competitors must come up with a database design and implement the website based on it. Some example data will be provided which competitors must use. However, this data might not be normalized, and it is up to the competitors to import it into their database schema.

Module B must be implemented using a server-side framework. It is possible to use additional libraries in the frontend for interactivity, but rendering must be performed by the server-side framework, and _not_ by a client-side framework calling an API. Framework and library availability will be limited and will be decided by all experts using the EuroSkills forums.

### Assessment

Module B will be assessed using the latest stable version of Google Chrome.

Different security aspects will be tested.

**Competition time**

Competitors will have **4 hours** to complete module B.

### Mark distribution

The table below outlines how marks are broken down and how they align with the WorldSkills Occupation Standards (WSOS). Please read the Technical Description for a full explanation of the WorldSkills Occupation Standards.

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| 1   | Work organization and self-management | 0   |
| 2   | Communication and interpersonal skills | 0   |
| 3   | Design Implementation | 4.75 |
| 4   | Front-End Development | 0   |
| 5   | Back-End Development | 18.25 |
| **Total** |     | **23** |

## Module C REST API

**Introduction**

Module C will focus on the implementation of a REST API.

### Description of project and tasks

In this module, competitors will develop a secure, database-backed REST API. The backend must fetch and interpret data from an external API resiliently. The API to implement serves a clean, frontend-ready API. The API must be secured and support role-based access control.

Public endpoints provide basic data, while protected ones expose control features. A relational database is to be used for storing data. An OpenAPI specification must be followed, including defined error responses. **Assessment**

Module C will be assessed using tools which directly access the API created by competitors. The API will be tested for its functionality and its adherence to the specification. The API will also be tested for its security and reliability.

Any modifications in the provided backend of previous modules, including any changes to the database, will not be taken into account.

**Competition time**

Competitors will have **3 hours** to complete module C.

### Mark distribution

The table below outlines how marks are broken down and how they align with the WorldSkills Occupation Standards (WSOS). Please read the Technical Description for a full explanation of the WorldSkills Occupation Standards.

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| 1   | Work organization and self-management | 1   |
| 2   | Communication and interpersonal skills | 0.75 |
| 3   | Design Implementation | 0   |
| 4   | Front-End Development | 0   |
| 5   | Back-End Development | 15  |
| **Total** |     | **16.75** |

## Module D Interactive Frontend using an API

**Introduction**

Module D will focus on the implementation of a frontend for a REST API.

### Description of project and tasks

The competitors will be asked to create a frontend for a REST API. Some endpoints of the REST API require authentications and users to log in.

The functionality created by competitors in this module builds on top of the functionality created in module C. Competitors will be given a working solution of module C at the start of module D, which they must use. Competitors are not allowed to build on their own module C solution.

The frontend consumes the API, displays pages based on its response, and sends actions triggered by user interactions back to the API.

The frontend additionally features data polling, visualization of data in different ways, and integration of third-party scripts.

Module D can be implemented using a frontend framework and other available libraries. The application must be a Single Page Application (SPA). Page reloads must present the same content to the user as previously visible, except unsaved user-driven inputs. Framework and library availability will be limited and will be decided by all experts using the EuroSkills forums.

### Assessment

Module D will be assessed using the latest stable version of Google Chrome. The assessment will include functional tests, as well as user experience.

Any modifications in the provided backend of previous modules, including any changes to the database, will not be taken into account.

**Competition time**

Competitors will have **4 hours** to complete module D.

### Mark distribution

The table below outlines how marks are broken down and how they align with the WorldSkills Occupation Standards (WSOS). Please read the Technical Description for a full explanation of the WorldSkills Occupation Standards.

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| 1   | Work organization and self-management | 0   |
| 2   | Communication and interpersonal skills | 0   |
| 3   | Design Implementation | 5   |
| 4   | Front-End Development | 17  |
| 5   | Back-End Development | 0   |
| **Total** |     | **22** |

## Module E Advanced Web Development

### Introduction

Module E is not focusing on a single topic, but groups several skills that previously were not covered in the test project. The skills that will be tested in this module are:

1. Writing automated tests
2. OWASP Top 10 Security Vulnerabilities
3. Visual Appearance Preferences

### Description of project and tasks

1. Writing automated tests

The competitor will be given a JavaScript project that has no automated tests. The competitor will have to write automated unit tests for the project. A complete test set is expected which covers 100% of the provided code. A provided JavaScript testing framework must be used.

1. OWASP Top 10 Security Vulnerabilities

The competitor will be given a JavaScript project that has code security issues. The competitor must find and document these issues and suggest improvements in an issue tracker.

1. Visual Appearance Preferences

The competitors must implement different visual appearances for a website while storing a user's preference. The implementation must follow industry best practices and may also require the use of various CSS features, such as variables or media queries.

### Assessment

1. Writing automated tests

It will be assessed if the created test set is grouped logically and if the tests are written in a way that they are easy to understand. The test must pass when running against the original code and not pass any logically mutated version of that code (Mutation Testing). Each test file must be submitted in a separate Pull Request with a clear title and description.

1. OWASP Top 10 Security Vulnerabilities

It will be assessed if the issues are documented in a way that they can be understood by a developer with basic knowledge of security issues. Completeness of the issues will be assessed. False positives will not get points and not subtracted from the total score.

1. Visual Appearance Preferences

It will be assessed if the implemented website and styling follows all listed requirements. The axe browser extension will be used to assess certain accessibility requirements.

**Competition time**

Competitors will have **3 hours** to complete module E.

### Mark distribution

The table below outlines how marks are broken down and how they align with the WorldSkills Occupation Standards (WSOS). Please read the Technical Description for a full explanation of the WorldSkills Occupation Standards.

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| 1   | Work organization and self-management | 0.5 |
| 2   | Communication and interpersonal skills | 3.5 |
| 3   | Design Implementation | 0   |
| 4   | Front-End Development | 5.75 |
| 5   | Back-End Development | 7   |
| **Total** |     | **16.75** |

## Module F – Collaborative Challenge

**Introduction**

Module F focuses on having fun with other competitors and being creative.

### Description of project and tasks

Competitors form groups and create a small web experience.

Competitors are then asked to present their result to the other competitors and the experts. The presentation should be short, include the explanation of what they created and how they came up with that idea. Also, it should be rounded off with a demo.

### Assessment

Competitors will be assessed by their presence and participation in the module, that there is a worked out idea, and that the presentation is done in a professional manner. Attendance is mandatory for all competitors to all presentations.

**Competition time**

Competitors will have **2 hours** to complete module F.

### Mark distribution

The table below outlines how marks are broken down and how they align with the WorldSkills Occupation Standards (WSOS). Please read the Technical Description for a full explanation of the WorldSkills Occupation Standards.

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| 1   | Work organization and self-management | 2   |
| 2   | Communication and interpersonal skills | 1   |
| 3   | Design Implementation | 0   |
| 4   | Front-End Development | 2   |
| 5   | Back-End Development | 0   |
| **Total** |     | **5** |

# EQUIPMENT, MACHINERY, INSTALLATIONS AND MATERIALS REQUIRED

It is expected that all Test Projects can be done by competitors based on the equipment and materials specified in the Infrastructure Lists\*.

URL to Infrastructure List: <https://il.worldskills.org/#/events/612/lists/1525/public>

# MATERIALS, EQUIPMENT AND TOOLS SUPPLIED BY COMPETITORS IN THEIR TOOLBOX

Competitors may bring the following items: • Mouse with mousepad

- A maximum of one USB keyboard in the Competitors desired language.

Note: If the keyboard brought by the Competitor does not work then a standard keyboard will be provided by the Competition Organizer

- Language file for the operating system to make the keyboard work correctly
- Headset and extension cable

Any device brought in by the Competitor may not have any internal memory storage. Assigned Experts and Workshop Manager have the right to disallow certain equipment brought by Competitors. Backup equipment is allowed in case of failure but should always be kept inside the Competitors locker.

# MATERIALS & EQUIPMENT AND TOOLS PROHIBITED IN THE SKILL AREA

The Skill area is the area outside the experts’ room within the Workshop Area.

- Extra software
- Mobile phones
- Tablet devices
- Smart watches
- Photography/Video devices
- USB Drives
- Any device brought into the workshop may not have any internal memory storage devices

The Chief Expert, Deputy Chief Expert and Workshop Manager have the right to disallow equipment brought by Competitors.