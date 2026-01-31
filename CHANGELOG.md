# Changelog

All notable changes to the Qoliber Core module will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [1.0.7] - 2025-05-27

### Changed
- Updated author information from individual developer email to generic Qoliber team email across all XML files
- Standardized author attribution in module.xml, acl.xml, adminhtml menu.xml, and system.xml files
- Updated registration.php author information for consistency

## [1.0.6] - 2025-04-16

### Added
- Added new "Manage" submenu item to Qoliber admin menu with sortOrder 10
- Submenu provides dedicated section for managing Qoliber extensions under the main Qoliber menu

## [1.0.5] - 2024-10-10

### Added
- Added adminhtml LESS module file (_module.less) with Qoliber logo as base64 encoded PNG image for menu branding
- Custom styling for Qoliber menu items in admin panel

### Changed
- Changed Qoliber admin menu sortOrder from 10 to 60 to reposition menu in admin sidebar
- Updated Qoliber configuration tab sortOrder from 10 to 950 for better positioning in system configuration
- Added CSS class "qoliber-tab" to system configuration tab for custom styling

## [1.0.4] - 2024-10-10

### Changed
- Migrated repository from GitLab to GitHub (git@github.com:qoliber/core.git)
- Changed license from proprietary Qoliber license to MIT open source license
- Updated LICENSE.md from custom Qoliber EULA to standard OSL 3.0 (Open Software License)
- Updated composer.json license field to reflect MIT license

## [1.0.3] - 2024-08-01

### Added
- Added "Configuration" submenu item to Qoliber admin menu
- Submenu positioned with sortOrder 100 under the main Qoliber menu item

## [1.0.2] - 2024-08-01

### Added
- Added source repository information to composer.json (GitLab)
- Added git reference field set to "master" branch

### Changed
- Updated license URL from store.qoliber.com to qoliber.com domain

## [1.0.1] - 2024-08-01

### Added
- Added comprehensive LICENSE.md file with Qoliber Extensions User License Agreement
- License defines usage terms, ownership, refund policy, and breach conditions
- Includes terms for yearly support subscriptions and multi-year support packages

### Changed
- Updated composer.json with license reference to LICENSE.md
- Set license field to point to https://store.qoliber.com/license/

## [1.0.0] - 2024-08-01

### Added
- Initial release of Qoliber Core module
- Created base module structure with module.xml, registration.php, and composer.json
- Added ACL configuration (etc/acl.xml) with "Qoliber_Core::menu" resource
- Created admin menu structure with main "Qoliber" menu item positioned at sortOrder 10
- Added system configuration tab "qoliber" for all Qoliber modules
- Added English translations (i18n/en_US.csv)
- Set module dependency on magento/module-backend
