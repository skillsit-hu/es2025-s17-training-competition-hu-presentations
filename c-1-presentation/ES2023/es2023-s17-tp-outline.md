# CONTENTS

This Test Project proposal consists of the following documentation/files:

1\. ES2023_TP_Proposal_Web_Development_17.pdf

# INTRODUCTION PURPOSE

This document describes the Test Project Proposal of Skill 17, Web Development. It is circulated to the competitors and experts prior to the competition and contains only basic information. The actual Test Project will be created by external Test Project Developers using this document as a guide and it will be presented on C-2 to all experts.

# MODULES

The Test Project will consist of 6 modules with the following topics:

- Module **A**: Static Website Design (HTML/CSS)
- Module **B**: Dynamic website with server-side rendering
- Module **C**: Commercial Open API
- Module **D**: Interactive Frontend using an API
- Module **E**: Advanced Web Development
- Module **F**: Collaborative Challenge

These modules will be further described in this document.

# TIME MANAGEMENT

| **Day / Block** | **Module** | **Duration** |
| --- | --- | --- |
| **C1** |     |     |
| Morning | Module A | 3 hours |
| Afternoon | Module B | 4 hours |
| **C2** |     |     |
| Morning | Module C | 3 hours |
| Afternoon | Module D | 4 hours |
| **C3** |     |     |
| Morning | Module E | 3 hours |
| Afternoon | Module F | 2 hours |

# MARKING SCHEME

The following table shows the point distribution for all sections and modules.

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| **1** | **Work organization and management** | **5** |
|     | Module A - Static Website Design | 1   |
| Module B - Dynamic website with server-side rendering | 0   |
| Module C - Commercial Open API | 1   |
| Module D - Interactive Frontend using an API | 0   |
| Module E - Advanced Web Development | 2   |
| Module F - Collaborative Challenge | 1   |
| **2** | **Communication and interpersonal skills** | **5** |
|     | Module A - Static Website Design | 1   |
| Module B - Dynamic website with server-side rendering | 0   |
| Module C - Commercial Open API | 1   |
| Module D - Interactive Frontend using an API | 0   |
| Module E - Advanced Web Development | 1   |
| Module F - Collaborative Challenge | 2   |
| **3** | **Design Implementation** | **25** |
|     | Module A - Static Website Design | 15  |
| Module B - Dynamic website with server-side rendering | 5   |
| Module C - Commercial Open API | 0   |
| Module D - Interactive Frontend using an API | 5   |
| Module E - Advanced Web Development | 0   |
| Module F - Collaborative Challenge | 0   |
| **4** | **Front-End Development** | **25** |
|     | Module A - Static Website Design | 0   |
| Module B - Dynamic website with server-side rendering | 0   |
| Module C - Commercial Open API | 0   |
| Module D - Interactive Frontend using an API | 17  |
| Module E - Advanced Web Development | 8   |
| Module F - Collaborative Challenge | 0   |
| **5** | **Back-End Development** | **40** |
|     | Module A - Static Website Design | 0   |
| Module B - Dynamic website with server-side rendering | 18  |
| Module C - Commercial Open API | 15  |
| Module D - Interactive Frontend using an API | 0   |
| Module E - Advanced Web Development | 5   |
| Module F - Collaborative Challenge | 2   |
|     | **Total** | **100** |

# Module A Static Website Design (HTML/CSS)

**INTRODUCTION**

Module A will focus on the creation of a static website using HTML and CSS only.

## DESCRIPTION OF PROJECT AND TASKS

The competitors will be asked to create a static website for a specified client. The website will consist of subpages which should be reachable under separate paths. The design of all subpages should be aligned.

The website must conform with accessibility standards (WCAG) and implement SEO best practices, as it will be used to attract new users for a product of the client.

Responsiveness is also important, and the website should look good on three different viewports: mobile, tablet, and desktop.

The client will supply the competitors with a defined website structure and will therein define all the pages and sections of the website. The client will also provide all content for the website, such as text, images, and other media, as well as the exact definitions of the responsive breakpoints.

No server-side or client-side framework will be allowed for module A. CSS preprocessors may be used, but the generated code must still pass the W3C validations. Framework and library availability are limited to the ones listed in the Infrastructure List.

## ASSESSMENT

Module A will be assessed using the latest stable version of Google Chrome and Firefox.

HTML and CSS will be assessed using W3C validators. Accessibility will be tested using axe.

**COMPETITION TIME**

Competitors will have **3 hours** to complete module A.

## MARK DISTRIBUTION

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| 1   | Work organization and self-management | 1   |
| 2   | Communication and interpersonal skills | 1   |
| 3   | Design Implementation | 15  |
| 4   | Front-End Development | 0   |
| 5   | Back-End Development | 0   |
| **Total** |     | **17** |

# Module B - Dynamic website with server-side rendering

**INTRODUCTION**

Module B will focus on the creation of a dynamic website using a server-side framework.

## DESCRIPTION OF PROJECT AND TASKS

In this module, competitors will create a dynamically and server-side rendered website which the users of the product will use to manage their accounts and additional information.

Parts of the website are protected and only accessible after a successful login. As this website will be publicly exposed, it must implement the OWASP guidelines.

The client will provide a detailed description of all the required functionalities of this website. From that, competitors must come up with a database design and implement the website based on it. Some example data will be provided in the form of CSV files which competitors must use. However, this CSV data might not be normalized, and it is up to the competitors to import it into their database.

Module B must be implemented using a server-side framework. It is possible to use additional libraries in the frontend for interactivity, but rendering must be performed by the server-side framework, and not by a client-side framework calling an API. Framework and library availability are limited to the ones listed in the Infrastructure List.

## ASSESSMENT

Module B will be assessed using the latest stable version of Google Chrome. Different security aspects will be tested.

**COMPETITION TIME**

Competitors will have **4 hours** to complete module B.

## MARK DISTRIBUTION

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| 1   | Work organization and self-management | 0   |
| 2   | Communication and interpersonal skills | 0   |
| 3   | Design Implementation | 5   |
| 4   | Front-End Development | 0   |
| 5   | Back-End Development | 18  |
| **Total** |     | **23** |

# C Commercial Open API

**INTRODUCTION**

Module C will focus on the implementation of a REST API.

## DESCRIPTION OF PROJECT AND TASKS

The competitors will be asked to create a REST API that will be used commercially. The API must be built with features which allow it to be commercialized and made available publicly and openly. The functionality created by competitors in this module, builds on top of the functionality created in module B. Competitors will be given a working solution of Module B at the start of Module C, which they must use. Competitors are not allowed to build on top of their own Module B solution. This will include the database and the data that is stored in it.

The functionality of the API will be to provide external access to a number of functions, which will be run as separate services. Those services will all expose a REST API themselves, which however should not be publicly accessible, as they do not have any level of security and reliability as the commercial API. The code of the services will not be disclosed to competitors. Instead, a description of the API in the form of an OpenAPI specification and a generated documentation based on it will be provided. Competitors are supposed to build code which wraps these APIs and exposes them through a single API. The function services can expose different ways of accessing their features and how to pass and receive data.

There will also be a specification for the API that competitors are supposed to create. This specification will also be in the form of an OpenAPI specification and a generated documentation based on it. The specification will describe the endpoints that competitors are supposed to implement. The specification will also describe the authentication and other non-functional requirements of the API.

## ASSESSMENT

Module C will be assessed using tools which directly access the API created by competitors. The API will be tested for its functionality and its adherence to the specification. The API will also be tested for its security and reliability.

Any modifications in the provided backend of previous modules, including any changes to the database, will not be taken into account.

**COMPETITION TIME**

Competitors will have **3 hours** to complete module C.

## MARK DISTRIBUTION

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| 1   | Work organization and self-management | 1   |
| 2   | Communication and interpersonal skills | 1   |
| 3   | Design Implementation | 0   |
| 4   | Front-End Development | 0   |
| 5   | Back-End Development | 15  |
| **Total** |     | **17** |

# D Interactive Frontend using an API

**INTRODUCTION**

Module D will focus on the implementation of a frontend for a REST API.

## DESCRIPTION OF PROJECT AND TASKS

The competitors will be asked to create a frontend for a REST API. First, users of that frontend will need to log in. Using the authentication mechanism of the API, the frontend will then be able to access the API and send as well as retrieve data from it. The functionality created by competitors in this module, builds on top of the functionality created in module B and C. Competitors will be given a working solution of Module C at the start of Module D, which they must use. Competitors are not allowed to build on top of their own Module C solution.

The users of the frontend will be able to discover the available functions that the API provides. Each function is then exposed through a separate page which exhibits several interactive elements, each custom to the function. There will be complex data inputs and outputs, some of them potentially asynchronous. The goal of the frontend is to hide this complexity from the user. The frontend must also handle errors and display them to the user in a comprehensible way.

Module D must be implemented using a frontend framework. It is possible to use additional libraries. The application should be a Single Page Application (SPA). The routing should be handled by the framework. Page reloads should present the same content to the user as previously visible, except unsaved user driven inputs. Framework and library availability are limited to the ones listed in the Infrastructure List.

## ASSESSMENT

Module D will be assessed using the latest stable version of Google Chrome. The assessment will include functional tests, as well as user experience. Accessibility will be tested using axe.

Any modifications in the provided backend of previous modules, including any changes to the database, will not be taken into account.

**COMPETITION TIME**

Competitors will have **4 hours** to complete module D.

## MARK DISTRIBUTION

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| 1   | Work organization and self-management | 0   |
| 2   | Communication and interpersonal skills | 0   |
| 3   | Design Implementation | 5   |
| 4   | Front-End Development | 17  |
| 5   | Back-End Development | 0   |
| **Total** |     | **22** |

# E Advanced Web Development

## INTRODUCTION

Module E is not focusing on a single topic, but groups several skills that previously were not covered in the test project. The skills that will be tested in this module are:

1. Writing automated tests
2. Creating a Progressive Web App (PWA)
3. Creating a Web Component

## DESCRIPTION OF PROJECT AND TASKS

### 1\. Writing automated tests

The competitor will be given a JavaScript project that has no automated tests. The competitor will have to write automated unit tests for the project. A complete test set is expected which covers 100% of the provided code. A JavaScript testing framework must be used. Testing library availability is limited to the ones listed in the Infrastructure List.

### 2\. Creating a Progressive Web App (PWA)

The competitor will have to create a simple Progressive Web App (PWA), that can work offline, push notifications, and that is installable on the user's device. The competitor is not allowed to use any frameworks or libraries for this task. A simple backend along with a documentation will be provided to competitors.

### 3\. Creating a Web Component

The competitor will have to create one or more Web Components that can be used in any website. A specification for the Web Components will be provided. The competitor must also show how the Web Components can be used in a website by creating a simple website. The competitor is not allowed to use any frameworks or libraries for this task.

## ASSESSMENT

### 1\. Writing automated tests

It will be assessed if the created test set is grouped logically and if the tests are written in a way that they are easy to understand. The test must pass when running against the original code, and not pass any logically mutated version of that code (Mutation Testing).

### 2\. Creating a Progressive Web App (PWA)

The functionality of the PWA will be assessed using the latest stable version of Google Chrome on Desktop. It will be tested that the app can be installed on the user's device, that it can work offline by showing the last known data, and that it can receive push notifications.

### 3\. Creating a Web Component

The created component API will be checked against the specification. A test page that is not provided to competitors will integrate the created components and be used to test their functionality.

**COMPETITION TIME**

Competitors will have **3 hours** to complete module E.

## MARK DISTRIBUTION

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| 1   | Work organization and self-management | 2   |
| 2   | Communication and interpersonal skills | 1   |
| 3   | Design Implementation | 0   |
| 4   | Front-End Development | 8   |
| 5   | Back-End Development | 5   |
| **Total** |     | **16** |

# F Collaborative Challenge

**INTRODUCTION**

Module F focuses on having fun with other competitors and being creative.

## DESCRIPTION OF PROJECT AND TASKS

After having created most components for the client, the competitor is now asked to create their own creative function that can be integrated into the system. More details on what type of functions these should be, will be provided during the competition. Competitors can be as creative as they want, but the function should be fitting the overall theme. The functionality itself can be implemented in any way, and it can also be faked. However, the API must be implemented and working, so the function can actually be integrated into the system.

Competitors are then asked to present their function to the other competitors and the experts. The presentation should be short, include the explanation of what they created and how they came up with that idea. Also, it should be rounded off with a demo of the function.

## ASSESSMENT

The module will be assessed by checking the competitor’s participation in the module, that there is a function which can be integrated into the system, and that the presentation is done in a professional manner. Attendance is mandatory for all competitors to all presentations.

**COMPETITION TIME**

Competitors will have **2 hours** to complete module F.

## MARK DISTRIBUTION

| **WSOS Section** | **Description** | **Points** |
| --- | --- | --- |
| 1   | Work organization and self-management | 1   |
| 2   | Communication and interpersonal skills | 2   |
| 3   | Design Implementation | 0   |
| 4   | Front-End Development | 0   |
| 5   | Back-End Development | 2   |
| **Total** |     | **5** |

# Materials

## EQUIPMENT, MACHINERY, INSTALLATIONS AND MATERIALS REQUIRED

It is expected that all Test Projects can be done by competitors based on the equipment and materials specified in the Infrastructure Lists\*.

• URL to Infrastructure List: TBD

## MATERIALS, EQUIPMENT AND TOOLS SUPPLIED BY COMPETITORS IN THEIR TOOLBOX

Competitors may bring the following items: • Mouse with mousepad

- A maximum of one USB keyboard in the Competitors desired language.

Note: If the keyboard brought by the Competitor does not work then a standard keyboard will be provided by the Competition Organizer

- Language file for Microsoft OS or Ubuntu Linux to make the keyboard work correctly
- Headset and extension cable

Any device brought in by the Competitor may not have any internal memory storage. Assigned Experts and Workshop Manager have the right to disallow certain equipment brought by Competitors. Backup equipment is allowed in case of failure but should always be kept inside the Competitors locker.

## MATERIALS & EQUIPMENT AND TOOLS PROHIBITED IN THE SKILL AREA

The Skill area is the area outside the experts’ room within the Workshop Area.

- Extra software
- Mobile phones
- Tablet devices
- Smart watches
- Photography/Video devices
- USB Drives
- Any device brought into the workshop may not have any internal memory storage devices

The Chief Expert, Deputy Chief Expert and Workshop Manager have the right to disallow equipment brought by Competitors.