# Edubuk LMS

**Edubuk LMS** is a powerful and flexible Learning Management System (LMS) developed by **Eduprovince Technologies Private Limited**. Designed to streamline the educational process, Edubuk LMS offers a comprehensive set of features for managing courses, students, and educators efficiently.

## Table of Contents

- [Edubuk LMS](#edubuk-lms)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [1. Download Edubuk LMS](#1-download-edubuk-lms)
    - [2. Upload Files](#2-upload-files)
    - [3. Create a Database](#3-create-a-database)
    - [4. Configure Database Connection](#4-configure-database-connection)
    - [5. Run the Installer](#5-run-the-installer)
  - [Configuration](#configuration)
  - [Usage](#usage)
    - [Logging In](#logging-in)
    - [Admin Features](#admin-features)
    - [Student Features](#student-features)
  - [API Documentation](#api-documentation)
  - [Contributing](#contributing)
  - [License](#license)
  - [Support](#support)

---

## Introduction

**Edubuk LMS** is an open-source PHP-based platform designed to provide a user-friendly and robust environment for online education. It offers tools for course management, student engagement, and administrative tasks, catering to educational institutions and corporate training programs.

## Features

- **Course Management**: Create, manage, and organize courses with ease.
- **User Management**: Administer student and instructor accounts, roles, and permissions.
- **Interactive Content**: Upload and manage multimedia content, quizzes, and assignments.
- **Progress Tracking**: Monitor student progress and performance through detailed reports and analytics.
- **Communication Tools**: Enable discussions and messaging between students and instructors.
- **Customizable Templates**: Choose from various templates to tailor the look and feel of your LMS.
- **Integration Capabilities**: Integrate with other systems such as payment gateways, email services, and analytics tools.

## System Requirements

To install and run Edubuk LMS, ensure your server meets the following requirements:

- **PHP**: 7.4 or higher
- **Web Server**: Apache 2.4 or higher, Nginx 1.18 or higher
- **Database**: MySQL 5.7 or higher, MariaDB 10.3 or higher
- **Extensions**: PDO, mysqli, mbstring, fileinfo, zip, curl
- **Memory Limit**: 256 MB (recommended)
- **Disk Space**: Minimum 500 MB

## Installation

### 1. Download Edubuk LMS

Download the latest version of Edubuk LMS from the [official repository](https://github.com/eduprovince/edubuk-lms).

### 2. Upload Files

Upload the downloaded files to your web server's root directory.

### 3. Create a Database

Create a new MySQL or MariaDB database and user for Edubuk LMS.

### 4. Configure Database Connection

Rename the `config.example.php` file to `config.php` in the `config` directory. Open `config.php` and update the database connection settings:

```php
<?php
return [
    'db' => [
        'host' => 'localhost',
        'username' => 'your_db_user',
        'password' => 'your_db_password',
        'database' => 'edubuk_lms',
    ],
    'app' => [
        'url' => 'http://www.edubuklms.com',
    ],
];
?>
```

### 5. Run the Installer

Access the installation script via your web browser at `http://edubuklms.com/install`. Follow the on-screen instructions to complete the installation process.

## Configuration

After installation, you can configure Edubuk LMS through the admin dashboard:

- **Admin Dashboard**: Access the dashboard at `http://edubuklms.com/admin` and configure settings such as site preferences, user roles, and course categories.
- **Email Settings**: Set up email configurations for notifications and communication.
- **Payment Gateways**: Configure payment gateways if your LMS supports paid courses.

## Usage

### Logging In

1. Access the login page at `http://edubuklms.com/login`.
2. Enter your credentials and click **Login**.

### Admin Features

- **Manage Courses**: Create and edit courses, modules, and lessons.
- **User Management**: Add and manage students and instructors.
- **Reports**: Generate and view performance reports.

### Student Features

- **Enroll in Courses**: Browse and enroll in available courses.
- **Access Course Material**: View and download course content.
- **Submit Assignments**: Complete and submit assignments for evaluation.

## API Documentation

For developers, Edubuk LMS provides an API for integration with other systems. Access the API documentation at `http://edubuklms.com/api-docs` for details on endpoints, request methods, and usage examples.

## Contributing

We welcome contributions from the community. To contribute:

1. Fork the repository on GitHub.
2. Create a new branch for your changes.
3. Commit your changes and push to your fork.
4. Submit a pull request with a clear description of the changes.

For detailed contributing guidelines, refer to the [CONTRIBUTING.md](https://github.com/eduprovince/edubuk-lms/blob/main/CONTRIBUTING.md) file in the repository.

## License

Edubuk LMS is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the [LICENSE](https://github.com/eduprovince/edubuk-lms/blob/main/LICENSE) file for more information.

## Support

For support and troubleshooting:

- **Documentation**: Visit the [official documentation](http://edubuklms.com/docs).
- **Community Forum**: Join the [Edubuk LMS Community Forum](https://github.com/eduprovince/edubuk-lms/issues) for discussions and support.
- **Contact Us**: Reach out to us at [support@edubukeseal.org](mailto:support@edubukeseal.org) for direct assistance.
# LMS-CETA
# LMS-CETA
