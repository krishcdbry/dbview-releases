# Changelog

All notable changes to DBView will be documented in this file.

## [1.0.1] - 2025-12-10

### Enhanced Export/Import

This release improves database export and import functionality with better support for database objects.

### Features

- **Export Checkboxes**: Choose to include/exclude views, procedures, functions, and triggers when exporting
- **MySQL DELIMITER Support**: Import procedures and functions with proper DELIMITER syntax handling
- **Dynamic Version**: App now uses Tauri getVersion() for accurate version reporting
- **Anonymous Telemetry**: Usage analytics to help improve the app

### Fixes

- Fixed import failing with MySQL DELIMITER syntax for procedures/functions
- Fixed escaped quotes (doubled quotes) not being handled correctly during import
- Fixed version hardcoding in updater service

### Download

- [DBView_1.0.1_aarch64.dmg](./v1.0.1/DBView_1.0.1_aarch64.dmg) - macOS Apple Silicon (M1/M2/M3/M4)
- [DBView_1.0.1_x64-setup.exe](./v1.0.1/DBView_1.0.1_x64-setup.exe) - Windows 64-bit Installer
- [DBView_1.0.1_x64_en-US.msi](./v1.0.1/DBView_1.0.1_x64_en-US.msi) - Windows 64-bit MSI

---

## [1.0.0] - 2025-12-10

### First Stable Release

DBView v1.0.0 is the first stable release of the native macOS database client.

### Features

- **Database Support**: MySQL, PostgreSQL, SQLite
- **SQL Editor**: Monaco editor with syntax highlighting, auto-completion
- **Query Results**: Virtual scrolling data grid with sorting, resizing, export
- **ERD Visualization**: Auto-generated schema diagrams with relationship highlighting
- **SQL Book**: Save and organize frequently used queries
- **Query History**: Track executed queries with timestamps
- **Workbook Dashboards**: Create dashboards with tables, charts, and metrics
- **AI Assistant**: Multi-provider support (OpenAI, Anthropic, Google, Ollama)
- **SSH Tunnel**: Secure connections with password/key authentication
- **Themes**: Dark and Light themes
- **Safe Mode**: Block destructive SQL operations

### Technical

- Built with Tauri 2.0 + React 19
- Code signed with Apple Developer ID
- macOS 12.0+ required
- Apple Silicon (ARM64) native

### Download

- [DBView_1.0.0_aarch64.dmg](./v1.0.0/DBView_1.0.0_aarch64.dmg) - Apple Silicon (M1/M2/M3/M4)

---

## [1.0.0-beta.1] - 2025-12-09

### Added
- Initial beta release
- Multi-database support (MySQL, PostgreSQL, SQLite)
- SQL editor with syntax highlighting and auto-completion
- Query results with sorting and export (CSV, JSON, SQL)
- ERD visualization for database schema
- SQL Book for saving and organizing queries
- Workbook dashboards with custom layouts
- AI Assistant with multiple providers (OpenAI, Gemini, Claude)
- SSH Tunnel support for secure connections
- Connection management with secure keychain password storage
- Multiple themes (Light, Dark, System)
- Native macOS app with Tauri 2.0
