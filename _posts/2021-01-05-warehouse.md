---
title: Python - PyDepot
layout: post
post-image: "https://cdn.discordapp.com/attachments/683692219345010761/928501551012663378/unknown.png"
description: Python Warehouse Application built using PySide6, QtDesigner, and MongoDB
tags:
- Python
- MongoDB
- PySide6
- PyQt
- QtDesigner
- Warehouse
---

Final project of Software Engineering course taken in Fall 2021, chose to create a warehouse management application. Course was degined to model a Software Engineering team using the Scrum method. Due to group member participation issues I functioned as Product Owner, Scrum Master, and Developer :)

---

# Overview

This application is designed to strictly model the management of a warehouse. Application is written in Python using the MVC model, QtDesigner was used to create GUI elements, and MongoDB is used to store user and warehouse information.

### Functions

Supports three user roles
* User - Warehouse workers/stockers/pickers
* Supervisor - Warehouse Supervisors
* Administrator - System Administrators

Each role has access to all priviledges of above roles.

Administrators can create and manage users, as well as create and use database backups.
Supervisors can create new warehouse item types, items, and orders (incoming and outgoing).
Users can view warehouse items and orders, and process orders.

Items are added to the warehouse via incoming orders and removed via outgoing orders.

### Contribution

* Application Architecture
* Data Modelling
* Item Management (GUI and Functions)
* User Management (GUI and Functions)
* Password Security
* Team Management

### Technologies Used
* Python
* MongoDB (pymongo)
* PySide6 (CSS)
* QtDesigner