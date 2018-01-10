# TinyWorld

SAP Web IDE for SAP HANA (herein: Web IDE) is available with HANA SPS11 and later, for use with XS Advanced. It is an adaption of the SAP Web IDE Full-Stack (available on SAP Cloud Platform), and is specially designed for developing entire business applications on SAP HANA on-premise.

To illustrate the use of the Web IDE and of programming in the SAP HANA XS Advanced environment, we are going to develop a small application called “TinyWorld”.

TinyWorld is an example of such a three-tier multi-module application. Users use it to create and view a simplified model of the world, merely consisting of continents and their countries.

TinyWorld comprises the following modules:

* tinyui: A UI app module, written with HTLM/JS
* tinyjs: A business logic module, written with Node.js
* tinydb: An SAP HANA database module

As you may have inferred, it is intentionally a really small application, so that you will not be distracted by unnecessary details, and can focus on the development experience of working with SAP HANA and XS Advanced.

