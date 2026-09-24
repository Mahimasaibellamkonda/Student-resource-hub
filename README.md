# Student Resource Hub

## Project Description

Student Resource Hub is a cloud-based web application designed to help students organize and access academic resources from one place.

Students can add, search, filter, edit, delete, and open study resources such as notes, videos, articles, books, and practice materials. The project uses **Firebase Realtime Database** to store and retrieve resource information in the cloud.

---

## Features

- Add new study resources
- Edit existing resources
- Delete resources
- Search resources by title, subject, or description
- Filter resources by category
- Open resource links directly
- View total number of resources
- View number of subjects
- View number of resource categories
- Real-time cloud data storage
- Responsive and professional user interface

---

##  Technologies Used

- HTML5
- CSS3
- JavaScript
- Firebase
- Firebase Realtime Database

---

##  Cloud Technology

### Firebase Realtime Database

Firebase Realtime Database is used to store the student resource information in the cloud.

The database stores details such as:

- Resource title
- Subject
- Category
- Description
- Resource link
- Creation timestamp

Whenever a resource is added, updated, or deleted, the changes are reflected through Firebase Realtime Database.

---

## System Architecture

```text
Student
   ↓
Web Browser
   ↓
index.html
(HTML + CSS + JavaScript)
   ↓
Firebase Web SDK
   ↓
Firebase Realtime Database
