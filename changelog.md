# Changelog

## Version 2.3.0 - 2024-10-03

### Added

* Introduced Dark Mode toggle in user settings.
* Added Search functionality to the Help section.
* Implemented 2FA support for login using TOTP.

### Changed

* Updated the dashboard UI for better accessibility and usability.
* Improved performance of the data export feature for large datasets.
* Updated API documentation to include new endpoints for user management.

### Fixed

* Fixed an issue where user sessions would occasionally expire prematurely.
* Corrected 404 errors when navigating to archived projects.
* Fixed a bug causing the file upload progress bar to not display correctly in some browsers.

## Version 2.2.1 - 2024-09-15

### Fixed

* Hotfix for security vulnerability in the user authentication module.
* Addressed a critical bug where certain forms were not submitting correctly on mobile devices.

## Version 2.2.0 - 2024-09-12

### Added

* New Analytics Dashboard: Provides insights on user activity, engagement, and system performance.
* Role-based access control (RBAC) for managing user permissions at a granular level.
* Added support for additional languages: French, Spanish, and German.

### Changed

* Refined the notification system to reduce noise by categorizing alerts.
* Revamped the user profile page layout for improved clarity and navigation.

### Fixed

* Fixed a memory leak that caused performance degradation over time.
* Resolved an issue where password reset emails were not sent correctly for some users.

## Version 2.1.0 - 2024-08-30

### Added

* Introduced bulk actions for managing multiple records at once in the admin panel.
* Added new filters for searching through the user database.

### Changed

* Updated the email templates for a more consistent look across all communications.
* Enhanced logging to provide more detailed information in case of errors.

### Fixed

* Fixed a CSS issue causing elements to overlap in the mobile view.
* Corrected time zone display issues on the event scheduling page.