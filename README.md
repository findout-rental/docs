# FindOut - Project Documentation

[![Project](https://img.shields.io/badge/Project-FindOut-blue)](https://github.com/findout-rental)
[![Status](https://img.shields.io/badge/Status-In%20Development-yellow)]()

## 📚 Overview

This repository contains the complete documentation for **FindOut**, an apartment rental application that connects tenants with apartment owners through a seamless mobile and web experience.

## 📁 Documentation Files

| File | Description |
|------|-------------|
| **[SRS.md](SRS.md)** | Software Requirements Specification - Complete functional and non-functional requirements |
| **[ERD.md](ERD.md)** | Entity-Relationship Diagram - Database design and relationships |
| **[project-requirements.md](project-requirements.md)** | Original project requirements and grading criteria |
| **[database.sql](database.sql)** | MySQL database schema - Ready to execute SQL script |
| **[database.dbml](database.dbml)** | DBML format for [dbdiagram.io](https://dbdiagram.io/) visualization |
| **[findout-erd.pdf](findout-erd.pdf)** | Visual ERD diagram in PDF format |

## 🏗️ Project Architecture

FindOut consists of **4 main components**:

1. **📱 Customer Mobile App** (Flutter)
   - For Tenants and Apartment Owners
   - Android & iOS support
   - Repository: [findout-customer-app](https://github.com/findout-rental/findout-customer-app) *(Coming Soon)*

2. **🌐 Admin Web Application** (Flutter Web)
   - For System Administrators
   - Browser-based dashboard
   - Repository: [findout-admin-web](https://github.com/findout-rental/findout-admin-web) *(Coming Soon)*

3. **⚙️ Backend API** (Laravel)
   - RESTful API
   - MySQL Database
   - Repository: [findout-backend](https://github.com/findout-rental/findout-backend) *(Coming Soon)*

4. **📖 Documentation** (This Repository)
   - All project documentation
   - Database schemas
   - Requirements specifications

## 🎯 Key Features

### For Tenants
- ✅ Browse and search apartments with filters
- ✅ Book apartments for specific periods
- ✅ Rate and review apartments
- ✅ Favorites list
- ✅ In-app messaging with owners
- ✅ Booking management (modify/cancel)
- ✅ Multi-language support (Arabic/English)
- ✅ Dark/Light theme

### For Apartment Owners
- ✅ Add and manage apartments
- ✅ Approve/reject booking requests
- ✅ Communicate with tenants
- ✅ View booking statistics
- ✅ Multi-language support (Arabic/English)
- ✅ Dark/Light theme

### For Administrators
- ✅ Approve/reject user registrations
- ✅ Manage users (view/delete)
- ✅ View system statistics
- ✅ Dashboard with insights
- ✅ Multi-language support (Arabic/English)
- ✅ Dark/Light theme

## 🗄️ Database Schema

The application uses **MySQL** with the following main entities:

- **Users** - All user types (tenants, owners, admins)
- **Apartments** - Property listings with specifications
- **Bookings** - Rental bookings with status tracking
- **Ratings** - Apartment reviews and ratings
- **Favorites** - Tenant's saved apartments
- **Messages** - In-app messaging system
- **Notifications** - System notifications
- **OTP Verifications** - Authentication codes

View the complete schema in [database.sql](database.sql) or visualize it using [database.dbml](database.dbml) on [dbdiagram.io](https://dbdiagram.io/).

## 🛠️ Technology Stack

| Component | Technology |
|-----------|------------|
| Customer Mobile App | Flutter (Dart) |
| Admin Web App | Flutter Web (Dart) |
| Backend API | Laravel (PHP 8.1+) |
| Database | MySQL 8.0+ |
| Authentication | OTP via SMS |
| Notifications | Push Notifications (FCM/APNS) |

## 📖 How to Use This Documentation

1. **Start with** [project-requirements.md](project-requirements.md) for project overview
2. **Read** [SRS.md](SRS.md) for detailed requirements
3. **Review** [ERD.md](ERD.md) or [findout-erd.pdf](findout-erd.pdf) for database design
4. **Use** [database.sql](database.sql) to create the database
5. **Visualize** [database.dbml](database.dbml) on [dbdiagram.io](https://dbdiagram.io/)

## 📝 Documentation Standards

- All documents are written in **Markdown** format
- Database schemas follow **MySQL 8.0+** standards
- DBML files compatible with [dbdiagram.io](https://dbdiagram.io/)
- SQL files use **InnoDB** engine with **UTF8MB4** charset

## 🤝 Contributing

This is an academic project. For any questions or suggestions, please contact the project maintainer.

## 👨‍💻 Project Maintainer

**Abd Alazez Alboga**
- GitHub: [@abd-alazez-alboga](https://github.com/abd-alazez-alboga)
- Organization: [FindOut Rental](https://github.com/findout-rental)

## 📄 License

This project is part of an academic assignment. All rights reserved.

---

**Last Updated:** December 2024  
**Version:** 1.0

