# README

[![](https://raw.githubusercontent.com/corona-warn-app/cwa-documentation/main/images/CWA\_title.png)](https://www.coronawarn.app/en/)

***

[About this Project](<README (1).md#about-this-project>) • [Who We Are](<README (1).md#who-we-are>) • [Credits](<README (1).md#credits>) • [Data Privacy](<README (1).md#data-privacy>) • [Code of Conduct](<README (1).md#code-of-conduct>) • [Working Language](<README (1).md#working-language>) • [Our Documentation](<README (1).md#our-documentation>) • [Licensing](<README (1).md#licensing>) • [How to Contribute](<README (1).md#how-to-contribute>) • [Website](https://www.coronawarn.app/en/)

***

## Corona-Warn-App: Documentation

NOTE: This README is also available [in German](translations/readme.de/). Thank you for understanding that the German version might not always be up-to-date with the English one.

HINWEIS: Diese README ist ebenfalls [auf Deutsch](translations/readme.de/) verfügbar. Bitte haben Sie Verständnis, dass die deutsche Version nicht immer auf dem gleichen Stand wie die englische Version ist.

### About this Project

We are developing the official COVID-19 exposure notification app for Germany, called "[Corona-Warn-App](https://www.coronawarn.app/en/)". This project has the goal to develop an app based on technology with a decentralized approach - heavily inspired by the [DP-3T](https://github.com/DP-3T/documents) (Decentralized Privacy-Preserving Proximity Tracing, see [this comic](https://github.com/DP-3T/documents/tree/master/public\_engagement/cartoon) for concept explanation) and [TCN](https://tcn-coalition.org/) protocols and based on the [Privacy-Preserving Contact Tracing specifications](https://www.apple.com/covid19/contacttracing/) by Apple and Google. Like DP-3T and the TCN Protocol, the apps and backend infrastructure will be entirely open source - licensed under the [Apache 2.0 license](LICENSE/)! The apps (for iOS and Android) will collect pseudonymous data from nearby mobile phones using Bluetooth technology. The data will be stored locally on each device preventing access and control over data by authorities or anyone else. We will meet the applicable data protection standards and guarantee a high level of IT security. By doing so, we are addressing people's privacy concerns and thereby aiming to increase the adoption of the app.

### Who We Are

The German government has commissioned SAP and Deutsche Telekom to develop the Corona-Warn-App for Germany as open source software. Deutsche Telekom is providing the network and mobile technology and will operate and run the backend for the app in a safe, scalable and stable manner. SAP is responsible for the app development, its framework and the underlying platform. Therefore, development teams of SAP and Deutsche Telekom are contributing to this project. At the same time our commitment to open source means that we are enabling -in fact encouraging- all interested parties to contribute and become part of its developer community.

### Credits

We'd like to thank all the partners who have been involved in this enormous project from the beginning. The project would not be where it is today without all the exploration and great work that had already been done around the [PEPP-PT](https://github.com/pepp-pt/pepp-pt-documentation) approach by partners on a European and national level. We will build on top of some of these components and appreciate how everyone is dedicated to making this new approach successful. Moreover, we would like to thank GitHub for their great support.

### Data Privacy

In this project we are strictly observing the principles of the General Data Protection Regulation (GDPR) to protect the users’ privacy. We are processing necessary data only - exclusively for the purpose to let users know if they have come into close contact with other infected users, without revealing each other's identity. The compliance with these regulations is safeguarded by several procedures, e.g. by implementing technical and organizational measures adhering diligently to the high standards of the GDPR. Of course, the app will provide users with a comprehensive privacy statement to be as transparent and clear as possible. As we are developing the app as an open source project, the community can review it. We appreciate your feedback!

### Code of Conduct

This project has adopted the [Contributor Covenant](https://www.contributor-covenant.org/) in version 2.0 as our code of conduct. Please see the details in our [CODE\_OF\_CONDUCT.md](./). All contributors must abide by the code of conduct.

### Working Language

We are building this application for Germany. We want to be as open and transparent as possible, also to interested parties in the global developer community who do not speak German. Consequently, all content will be made available primarily in _English_. We also ask all interested people to use English as language to create issues, in their code (comments, documentation etc.) and when you send requests to us. The application itself, documentation and all end-user facing content has - of course - been made available in German. Apart from the initial release in English and German, other languages have been added over time including Bulgarian, Polish, Romanian and Turkish. See the [FAQ available languages](https://www.coronawarn.app/en/faq/#available\_languages) entry for more details. We also try to make developer documentation available in German, but please understand that focusing on the _Lingua Franca_ of the global developer community makes the development of this application as efficient as possible.

### Our Documentation

This repository contains the developer documentation and related content.

#### Project Scope

The project scope has been agreed on jointly by Deutsche Telekom AG and SAP SE as contractors and the German Federal Government and the Robert-Koch-Institut as clients. The project scope might change over time as new requirements need to be included or existing ones change. We appreciate feedback to all elements of this project scope document. However, additional features or any other content changes beyond fixes to grammatical issues or typos need to be aligned on by these partners before they can be included in the document. Thank you for your understanding!

* [Corona-Warn-App - Scoping Document](scoping\_document.md)
* [Corona-Warn-App - User Interface Screens](ui\_screens.md)

#### Technical Documentation

The technical documents are intended for a technical audience and represent the most recent state of the architecture. The solution architecture and concepts might change over time as external dependencies (e.g. the framework provided by Apple/Google) are still changing and new requirements need to be included or existing ones change. We appreciate feedback to all elements of these technical documents.

* [Corona-Warn-App - Solution Architecture](solution\_architecture.md)
* [Corona-Warn-App Server Architecture](https://github.com/corona-warn-app/cwa-server/blob/main/docs/ARCHITECTURE.md)
* [Corona-Warn-App Verification Server Software Design](https://github.com/corona-warn-app/cwa-verification-server/blob/master/docs/architecture-overview.md)
* [Corona-Warn-App Verification Portal Server Software Design](https://github.com/corona-warn-app/cwa-verification-portal/blob/master/docs/architecture-overview.md)
* [Corona-Warn-App Test Result Server Software Design](https://github.com/corona-warn-app/cwa-testresult-server/blob/master/docs/architecture-overview.md)
* [Corona-Warn-App Mobile Client (Android) Architecture](https://github.com/corona-warn-app/cwa-app-android/blob/main/docs/architecture-overview.md)
* [Corona-Warn-App Mobile Client (iOS) Architecture](https://github.com/corona-warn-app/cwa-app-ios/blob/main/docs/architecture-overview.md)
* [Criteria for the Evaluation of Contact Tracing Apps](pruefsteine.md)
* [Corona-Warn-App Security Overview](overview-security.md)
* [Corona-Warn-App Backend Infrastructure Architecture Overview](backend-infrastructure-architecture.pdf)
* [How does the Corona-Warn-App identify an increased risk?](solution\_architecture.md#mobile-applications)
* [Epidemiological Motivation of the Transmission Risk Level (PDF)](transmission\_risk.pdf), [(Rmd file)](transmission\_risk.Rmd), [(bib references)](transmission\_risk\_references.bib)
* [Corona-Warn-App Data Privacy Impact Assessment/DPIA (PDF, German)](https://www.coronawarn.app/assets/documents/cwa-datenschutz-folgenabschaetzung.pdf), [DPIA Annex 1a](https://www.coronawarn.app/assets/documents/cwa-datenschutz-folgenabschaetzung-anlage1a.pdf), [DPIA Annex 1b](https://www.coronawarn.app/assets/documents/cwa-datenschutz-folgenabschaetzung-anlage1b.pdf), [DPIA Annex 1c](https://www.coronawarn.app/assets/documents/cwa-datenschutz-folgenabschaetzung-anlage1c.pdf), [DPIA Annex 2](https://www.coronawarn.app/assets/documents/cwa-datenschutz-folgenabschaetzung-anlage2.pdf), [DPIA Annex 3](https://www.coronawarn.app/assets/documents/cwa-datenschutz-folgenabschaetzung-anlage3.pdf), [DPIA Annex 4](https://www.coronawarn.app/assets/documents/cwa-datenschutz-folgenabschaetzung-anlage4.pdf), [DPIA Annex 5](https://www.coronawarn.app/assets/documents/cwa-datenschutz-folgenabschaetzung-anlage5.pdf), [DPIA Annex 6](https://www.coronawarn.app/assets/documents/cwa-datenschutz-folgenabschaetzung-anlage6.pdf), [DPIA Annex 7](https://www.coronawarn.app/assets/documents/cwa-datenschutz-folgenabschaetzung-anlage7.pdf) and [DPIA Annex 8](https://www.coronawarn.app/assets/documents/cwa-datenschutz-folgenabschaetzung-anlage8.pdf)
* [Exposure Notification API Testing](2020\_06\_24\_Corona\_API\_measurements.pdf)
* [Event Registration](event\_registration.md)

To be published:

* System Operation

#### Glossary

For an easier understanding of the used acronyms and special terms in our documents please see our [glossary](glossary.md).

### Repositories

| Repository                                                                                   | Description                                                                                   |
| -------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| [cwa-app-android](https://github.com/corona-warn-app/cwa-app-android)                        | Native Android app using the Apple/Google exposure notification API.                          |
| [cwa-app-ccl](https://github.com/corona-warn-app/cwa-app-ccl)                                | Common Covid Logic (CCL) for Android and iOS.                                                 |
| [cwa-app-ios](https://github.com/corona-warn-app/cwa-app-ios)                                | Native iOS app using the Apple/Google exposure notification API.                              |
| [cwa-dcc-server](https://github.com/corona-warn-app/cwa-dcc-server)                          | Backend implementation of the process to issue EU Digital Covid Certificate CovidCertificate. |
| [cwa-documentation](https://github.com/corona-warn-app/cwa-documentation)                    | Project overview, general documentation and white papers.                                     |
| [cwa-event-landingpage](https://github.com/corona-warn-app/cwa-event-landingpage)            | Landing page for CWA which opens if the user does not have the app installed.                 |
| [cwa-event-qr-code](https://github.com/corona-warn-app/cwa-event-qr-code)                    | Utility to generate QR codes for Event Registration.                                          |
| [cwa-hotline](https://github.com/corona-warn-app/cwa-hotline)                                | Contains all issues reg. the hotlines of the CWA.                                             |
| [cwa-icao-transliteration](https://github.com/corona-warn-app/cwa-icao-transliteration)      | A simple transliteration of non-latin letters into latin for the CWA.                         |
|  [cwa-kotlin-jfn](https://github.com/corona-warn-app/cwa-kotlin-jfn)                         | JsonFunctions Engine - DCC Logic.                                                             |
| [cwa-log-upload](https://github.com/corona-warn-app/cwa-log-upload)                          | Counterpart of the log upload in the app.                                                     |
|  [cwa-parent](https://github.com/corona-warn-app/cwa-parent)                                 | Repository containing Maven files for parent project and dependency building blocks.          |
| [cwa-map-backend](https://github.com/corona-warn-app/cwa-map-backend)                        | Backend of map.schnelltestportal.de.                                                          |
|  [cwa-map-operators-frontend](https://github.com/corona-warn-app/cwa-map-operators-frontend) | Frontend for test center operators to manage their test centers in a simple way.              |
| [cwa-map-public-frontend](https://github.com/corona-warn-app/cwa-map-public-frontend)        | Public frontend of map.schnelltestportal.de.                                                  |
| [cwa-ppa-server](https://github.com/corona-warn-app/cwa-ppa-server)                          | Backend implementation for the privacy-preserving analytics server.                           |
| [cwa-quick-test-backend](https://github.com/corona-warn-app/cwa-quick-test-backend)          | Backend implementation of the rapid antigen test portal and API for participating partners.   |
| [cwa-quick-test-frontend](https://github.com/corona-warn-app/cwa-quick-test-frontend)        | Frontend implementation of the rapid antigen test portal for participating partners.          |
| [cwa-quicktest-onboarding](https://github.com/corona-warn-app/cwa-quicktest-onboarding)      | Documentation about onboarding procedure for rapid antigen test partners.                     |
| [cwa-registrierung](https://github.com/corona-warn-app/cwa-registrierung)                    | Registration portal for the rapid antigen test portal                                         |
| [cwa-server](https://github.com/corona-warn-app/cwa-server)                                  | Backend implementation for the Apple/Google exposure notification API.                        |
| [cwa-testresult-server](https://github.com/corona-warn-app/cwa-testresult-server)            | Receives PCR test results from connected laboratories.                                        |
| [cwa-verification-iam](https://github.com/corona-warn-app/cwa-verification-iam)              | The identity and access management to interact with the verification server.                  |
| [cwa-verification-portal](https://github.com/corona-warn-app/cwa-verification-portal)        | The portal to interact with the verification server.                                          |
| [cwa-verification-server](https://github.com/corona-warn-app/cwa-verification-server)        | Backend implementation of the verification process.                                           |
| [cwa-website](https://github.com/corona-warn-app/cwa-website)                                | The official website for the Corona-Warn-App.                                                 |
| [cwa-wishlist](https://github.com/corona-warn-app/cwa-wishlist)                              | Community feature requests.                                                                   |
| [dcc-rule-translation](https://github.com/corona-warn-app/dcc-rule-translation)              | Translations of Booster Notification Rules.                                                   |

### Licensing

Copyright (c) 2020-2022 Deutsche Telekom AG and SAP SE or an SAP affiliate company.

Licensed under the **Apache License, Version 2.0** (the "License"); you may not use this file except in compliance with the License.

You may obtain a copy of the License at https://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the [LICENSE](LICENSE/) for the specific language governing permissions and limitations under the License.

The "Corona-Warn-App" logo is a registered trademark of The Press and Information Office of the Federal Government. For more information please see [bundesregierung.de](https://www.bundesregierung.de/breg-en/federal-government/federal-press-office).

### How to Contribute

Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to contribute, our team setup, the project structure and additional details which you need to know to work with us.
