<!-- markdownlint-disable -->
<h1 align="center">
    best-of-django
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome projects. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-230-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/fkromer/best-of-django/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/fkromer/best-of-django?color=green&label=updated"></a>
</p>

This curated list contains 230 awesome open-source projects with a total of 520K stars grouped into 58 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/fkromer/best-of-django/issues/new/choose), submit a [pull request](https://github.com/fkromer/best-of-django/pulls), or directly edit the [projects.yaml](https://github.com/fkromer/best-of-django/edit/main/projects.yaml). Contributions are very welcome!

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Admin Interface](#admin-interface) _8 projects_
- [Admin Interface Actions](#admin-interface-actions) _4 projects_
- [Admin Interface Filters](#admin-interface-filters) _1 projects_
- [Management Commands](#management-commands) _5 projects_
- [Caching](#caching) _2 projects_
- [Configuration](#configuration) _6 projects_
- [Dependency Injection](#dependency-injection) _3 projects_
- [Debugging](#debugging) _1 projects_
- [Development](#development) _2 projects_
- [Logging](#logging) _5 projects_
- [Application Monitoring (Platforms)](#application-monitoring-platforms) _2 projects_
- [Authentication and Authorization](#authentication-and-authorization) _17 projects_
- [Authorization](#authorization) _1 projects_
- [Task Queues](#task-queues) _5 projects_
- [Finite State Machine](#finite-state-machine) _7 projects_
- [RESTful API (Django Rest Framework)](#restful-api-django-rest-framework) _5 projects_
- [RESTful API (Django Ninja)](#restful-api-django-ninja) _6 projects_
- [Pydantic integration](#pydantic-integration) _4 projects_
- [Pandas integration](#pandas-integration) _1 projects_
- [GraphQL API](#graphql-api) _8 projects_
- [Feature Flipper](#feature-flipper) _1 projects_
- [Statistics](#statistics) _1 projects_
- [Testing](#testing) _5 projects_
- [CMS frameworks based on Django](#cms-frameworks-based-on-django) _3 projects_
- [E-Commerce frameworks based on Django](#e-commerce-frameworks-based-on-django) _4 projects_
- [Analytics frameworks based on Django](#analytics-frameworks-based-on-django) _1 projects_
- [Project management frameworks based on Django](#project-management-frameworks-based-on-django) _2 projects_
- [Monitoring frameworks based on Django](#monitoring-frameworks-based-on-django) _0 projects_
- [Photo management frameworks based on Django](#photo-management-frameworks-based-on-django) _1 projects_
- [Recipe management frameworks based on Django](#recipe-management-frameworks-based-on-django) _1 projects_
- [Document management frameworks based on Django](#document-management-frameworks-based-on-django) _1 projects_
- [Education frameworks based on Django](#education-frameworks-based-on-django) _1 projects_
- [Inventory management system based on Django](#inventory-management-system-based-on-django) _1 projects_
- [Crawler management system based on Django](#crawler-management-system-based-on-django) _0 projects_
- [Network automation system based on Django](#network-automation-system-based-on-django) _1 projects_
- [Fields (encrypted)](#fields-encrypted) _6 projects_
- [Fields (phone numbers)](#fields-phone-numbers) _2 projects_
- [Fields (addresses)](#fields-addresses) _5 projects_
- [Fields (versioning)](#fields-versioning) _7 projects_
- [Messaging](#messaging) _5 projects_
- [Storage](#storage) _3 projects_
- [Event Sourcing](#event-sourcing) _5 projects_
- [Locking](#locking) _3 projects_
- [Example data](#example-data) _4 projects_
- [Fake data](#fake-data) _2 projects_
- [Bootstrap CSS Framework Integration (Django MVT application)](#bootstrap-css-framework-integration-django-mvt-application) _4 projects_
- [Bulma CSS Framework Integration (Django MVT application)](#bulma-css-framework-integration-django-mvt-application) _1 projects_
- [TailwindCSS CSS Framework Integration (Django MVT application)](#tailwindcss-css-framework-integration-django-mvt-application) _3 projects_
- [Data exploration](#data-exploration) _1 projects_
- [Multiple tenants](#multiple-tenants) _4 projects_
- [Value-as-a-Service frameworks based on Django](#value-as-a-service-frameworks-based-on-django) _1 projects_
- [Payment and Subscription (Stripe, etc.)](#payment-and-subscription-stripe-etc) _19 projects_
- [Emails](#emails) _5 projects_
- [Templates](#templates) _4 projects_
- [Reusable app templates](#reusable-app-templates) _11 projects_
- [Project templates](#project-templates) _16 projects_
- [Static file serving](#static-file-serving) _1 projects_
- [Custom user](#custom-user) _5 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(12 months no activity)_
- 💀&nbsp; Dead project _(60 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects

<br>

## Admin Interface

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to replace or improve the default Django admin interface._

<details><summary><b><a href="https://github.com/farridav/django-jazzmin">django-jazzmin</a></b> (🥇34 ·  ⭐ 1.7K) - Jazzy theme for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/farridav/django-jazzmin) (👨‍💻 76 · 🔀 290 · 📦 14K · 📋 280 - 40% open · ⏱️ 11.01.2025):

	```
	git clone https://github.com/farridav/django-jazzmin
	```
- [PyPi](https://pypi.org/project/django-jazzmin) (📥 230K / month):
	```
	pip install django-jazzmin
	```
</details>
<details><summary><b><a href="https://github.com/fabiocaccamo/django-admin-interface">django-admin-interface</a></b> (🥈33 ·  ⭐ 1.9K) - djangos default admin interface with superpowers - customizable themes, popup windows replaced by modals and many.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fabiocaccamo/django-admin-interface) (👨‍💻 39 · 🔀 170 · 📦 4.8K · 📋 210 - 4% open · ⏱️ 16.01.2025):

	```
	git clone https://github.com/fabiocaccamo/django-admin-interface
	```
- [PyPi](https://pypi.org/project/django-admin-interface) (📥 130K / month):
	```
	pip install django-admin-interface
	```
</details>
<details><summary><b><a href="https://github.com/viewflow/django-material">django-material</a></b> (🥈28 ·  ⭐ 2.5K) - Material Design for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/viewflow/django-material) (👨‍💻 41 · 🔀 410 · 📦 1.8K · 📋 410 - 4% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/viewflow/django-material
	```
- [PyPi](https://pypi.org/project/django-material) (📥 12K / month):
	```
	pip install django-material
	```
</details>
<details><summary><b><a href="https://github.com/sehmaschine/django-grappelli">django-grappelli</a></b> (🥉27 ·  ⭐ 3.8K) - A jazzy skin for the Django Admin-Interface (official repository). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sehmaschine/django-grappelli) (👨‍💻 91 · 🔀 640 · 📦 6.6K · 📋 720 - 0% open · ⏱️ 22.08.2024):

	```
	git clone https://github.com/sehmaschine/django-grappelli
	```
- [PyPi](https://pypi.org/project/django-grappelli) (📥 170K / month):
	```
	pip install django-grappelli
	```
</details>
<details><summary><b><a href="https://github.com/otto-torino/django-baton">django-baton</a></b> (🥉27 ·  ⭐ 920) - A cool, modern and responsive django admin application based on bootstrap 5 that brings AI to the Django admin -.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/otto-torino/django-baton) (👨‍💻 17 · 🔀 96 · 📦 430 · 📋 190 - 1% open · ⏱️ 12.12.2024):

	```
	git clone https://github.com/otto-torino/django-baton
	```
- [PyPi](https://pypi.org/project/django-baton) (📥 12K / month):
	```
	pip install django-baton
	```
</details>
<details><summary><b><a href="https://github.com/django-admin-tools/django-admin-tools">django-admin-tools</a></b> (🥉23 ·  ⭐ 870 · 💤) - Extends the Django Admin to include a extensible dashboard and navigation menu. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-admin-tools/django-admin-tools) (👨‍💻 82 · 🔀 110 · 📦 1.6K · 📋 80 - 23% open · ⏱️ 10.08.2023):

	```
	git clone https://github.com/django-admin-tools/django-admin-tools
	```
- [PyPi](https://pypi.org/project/django-admin-tools) (📥 47K / month):
	```
	pip install django-admin-tools
	```
</details>
<details><summary><b><a href="https://github.com/byashimov/django-controlcenter">django-controlcenter</a></b> (🥉19 ·  ⭐ 990 · 💤) - Set of widgets to build dashboards for Django projects. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/byashimov/django-controlcenter) (👨‍💻 18 · 🔀 84 · 📦 89 · 📋 34 - 29% open · ⏱️ 06.08.2023):

	```
	git clone https://github.com/byashimov/django-controlcenter
	```
- [PyPi](https://pypi.org/project/django-controlcenter) (📥 6.3K / month):
	```
	pip install django-controlcenter
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/geex-arts/django-jet">django-jet</a></b> (🥉25 ·  ⭐ 3.6K · 💀) - Modern responsive template for the Django admin interface with improved functionality. We are proud to announce.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
</details>
<br>

## Admin Interface Actions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-import-export/django-import-export">django-import-export</a></b> (🥇38 ·  ⭐ 3.1K) - Django application and library for importing and exporting data with admin integration. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/django-import-export/django-import-export) (👨‍💻 230 · 🔀 750 · 📦 100K · 📋 1.1K - 1% open · ⏱️ 15.01.2025):

	```
	git clone https://github.com/django-import-export/django-import-export
	```
- [PyPi](https://pypi.org/project/django-import-export) (📥 1M / month):
	```
	pip install django-import-export
	```
</details>
<details><summary><b><a href="https://github.com/jrief/django-admin-sortable2">django-admin-sortable2</a></b> (🥈27 ·  ⭐ 790) - Generic drag-and-drop ordering for objects in the Django admin interface. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jrief/django-admin-sortable2) (👨‍💻 88 · 🔀 170 · 📦 2.7K · 📋 230 - 19% open · ⏱️ 25.11.2024):

	```
	git clone https://github.com/jrief/django-admin-sortable2
	```
- [PyPi](https://pypi.org/project/django-admin-sortable2) (📥 180K / month):
	```
	pip install django-admin-sortable2
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-admin-sortable">django-admin-sortable</a></b> (🥉19 ·  ⭐ 570 · 💤) - Generic drag-and-drop ordering for objects and tabular inlines in Django Admin. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jazzband/django-admin-sortable) (👨‍💻 80 · 🔀 130 · 📦 730 · 📋 140 - 7% open · ⏱️ 13.03.2022):

	```
	git clone https://github.com/jazzband/django-admin-sortable
	```
- [PyPi](https://pypi.org/project/django-admin-sortable) (📥 26K / month):
	```
	pip install django-admin-sortable
	```
</details>
<details><summary><b><a href="https://github.com/TrangPham/django-admin-confirm">django-admin-confirm</a></b> (🥉15 ·  ⭐ 130) - AdminConfirmMixin is a mixin for ModelAdmin that adds confirmations to changes, additions and actions. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/TrangPham/django-admin-confirm) (👨‍💻 6 · 🔀 15 · 📦 94 · 📋 31 - 41% open · ⏱️ 27.01.2024):

	```
	git clone https://github.com/trangpham/django-admin-confirm
	```
- [PyPi](https://pypi.org/project/django-admin-confirm) (📥 37K / month):
	```
	pip install django-admin-confirm
	```
</details>
<br>

## Admin Interface Filters

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/lukasvinclav/django-admin-numeric-filter">django-admin-numeric-filter</a></b> (🥇19 ·  ⭐ 79 · 💤) - Numeric filters for Django admin. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lukasvinclav/django-admin-numeric-filter) (👨‍💻 14 · 🔀 33 · 📦 200 · 📋 18 - 22% open · ⏱️ 16.02.2023):

	```
	git clone https://github.com/lukasvinclav/django-admin-numeric-filter
	```
- [PyPi](https://pypi.org/project/django-admin-numeric-filter) (📥 15K / month):
	```
	pip install django-admin-numeric-filter
	```
</details>
<br>

## Management Commands

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which add or help working with management commands._

<details><summary><b><a href="https://github.com/django-extensions/django-extensions">django-extensions</a></b> (🥇38 ·  ⭐ 6.6K) - This is a repository for collecting global custom management extensions for the Django Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-extensions/django-extensions) (👨‍💻 580 · 🔀 1.1K · 📦 240K · 📋 900 - 19% open · ⏱️ 13.01.2025):

	```
	git clone https://github.com/django-extensions/django-extensions
	```
- [PyPi](https://pypi.org/project/django-extensions) (📥 3.7M / month):
	```
	pip install django-extensions
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-dbbackup">django-dbbackup</a></b> (🥈30 ·  ⭐ 1K) - Management commands to help backup and restore your project database and media files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-dbbackup) (👨‍💻 77 · 🔀 200 · 📦 2.2K · 📋 290 - 22% open · ⏱️ 06.01.2025):

	```
	git clone https://github.com/jazzband/django-dbbackup
	```
- [PyPi](https://pypi.org/project/django-dbbackup) (📥 130K / month):
	```
	pip install django-dbbackup
	```
</details>
<details><summary><b><a href="https://github.com/GaretJax/django-click">django-click</a></b> (🥉20 ·  ⭐ 250) - Write Django management command using the click CLI library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/GaretJax/django-click) (👨‍💻 13 · 🔀 20 · 📦 330 · 📋 18 - 44% open · ⏱️ 26.09.2024):

	```
	git clone https://github.com/GaretJax/django-click
	```
- [PyPi](https://pypi.org/project/django-click) (📥 40K / month):
	```
	pip install django-click
	```
</details>
<details><summary><b><a href="https://github.com/django-commons/django-typer">django-typer</a></b> (🥉20 ·  ⭐ 100) - Use Typer (type hints) to define the interface for your Django management commands. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-commons/django-typer) (👨‍💻 6 · 🔀 2 · 📥 1 · 📦 48 · 📋 100 - 27% open · ⏱️ 07.01.2025):

	```
	git clone https://github.com/bckohan/django-typer
	```
- [PyPi](https://pypi.org/project/django-typer) (📥 8.5K / month):
	```
	pip install django-typer
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/django-rich">django-rich</a></b> (🥉19 ·  ⭐ 120) - Extensions for using Rich with Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/adamchainz/django-rich) (👨‍💻 6 · 🔀 10 · 📦 170 · 📋 13 - 30% open · ⏱️ 07.01.2025):

	```
	git clone https://github.com/adamchainz/django-rich
	```
- [PyPi](https://pypi.org/project/django-rich) (📥 75K / month):
	```
	pip install django-rich
	```
</details>
<br>

## Caching

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/Suor/django-cacheops">django-cacheops</a></b> (🥇29 ·  ⭐ 2.1K) - A slick ORM cache with automatic granular event-driven invalidation. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Suor/django-cacheops) (👨‍💻 69 · 🔀 220 · 📦 1.4K · 📋 340 - 4% open · ⏱️ 10.01.2025):

	```
	git clone https://github.com/Suor/django-cacheops
	```
- [PyPi](https://pypi.org/project/django-cacheops) (📥 170K / month):
	```
	pip install django-cacheops
	```
</details>
<details><summary><b><a href="https://github.com/noripyt/django-cachalot">django-cachalot</a></b> (🥇29 ·  ⭐ 1.3K) - No effort, no worry, maximum performance. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/noripyt/django-cachalot) (👨‍💻 38 · 🔀 140 · 📦 870 · 📋 170 - 18% open · ⏱️ 16.01.2025):

	```
	git clone https://github.com/noripyt/django-cachalot
	```
- [PyPi](https://pypi.org/project/django-cachalot) (📥 97K / month):
	```
	pip install django-cachalot
	```
</details>
<br>

## Configuration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/joke2k/django-environ">django-environ</a></b> (🥇36 ·  ⭐ 3K · 📈) - Django-environ allows you to utilize 12factor inspired environment variables to configure your Django application. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joke2k/django-environ) (👨‍💻 97 · 🔀 310 · 📥 140 · 📦 240K · 📋 250 - 25% open · ⏱️ 13.01.2025):

	```
	git clone https://github.com/joke2k/django-environ
	```
- [PyPi](https://pypi.org/project/django-environ) (📥 2.4M / month):
	```
	pip install django-environ
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/dj-database-url">dj-database-url</a></b> (🥈34 ·  ⭐ 1.5K) - Use Database URLs in your Django Application. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/dj-database-url) (👨‍💻 73 · 🔀 200 · 📦 290K · 📋 96 - 3% open · ⏱️ 22.11.2024):

	```
	git clone https://github.com/jazzband/dj-database-url
	```
- [PyPi](https://pypi.org/project/dj-database-url) (📥 1.6M / month):
	```
	pip install dj-database-url
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-constance">django-constance</a></b> (🥈33 ·  ⭐ 1.7K · 📈) - Dynamic Django settings. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-constance) (👨‍💻 150 · 🔀 290 · 📦 2.2K · 📋 300 - 3% open · ⏱️ 14.01.2025):

	```
	git clone https://github.com/jazzband/django-constance
	```
- [PyPi](https://pypi.org/project/django-constance) (📥 280K / month):
	```
	pip install django-constance
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-configurations">django-configurations</a></b> (🥉30 ·  ⭐ 1.1K) - A helper for organizing Django project settings by relying on well established programming patterns. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-configurations) (👨‍💻 74 · 🔀 140 · 📦 3.2K · 📋 210 - 24% open · ⏱️ 18.11.2024):

	```
	git clone https://github.com/jazzband/django-configurations
	```
- [PyPi](https://pypi.org/project/django-configurations) (📥 190K / month):
	```
	pip install django-configurations
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/django-split-settings">django-split-settings</a></b> (🥉28 ·  ⭐ 1.1K) - Organize Django settings into multiple files and directories. Easily override and modify settings. Use wildcards and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wemake-services/django-split-settings) (👨‍💻 25 · 🔀 69 · 📦 3.2K · 📋 48 - 10% open · ⏱️ 13.01.2025):

	```
	git clone https://github.com/wemake-services/django-split-settings
	```
- [PyPi](https://pypi.org/project/django-split-settings) (📥 130K / month):
	```
	pip install django-split-settings
	```
</details>
<details><summary><b><a href="https://github.com/fabiocaccamo/django-extra-settings">django-extra-settings</a></b> (🥉21 ·  ⭐ 570) - config and manage typed extra settings using just the django admin. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fabiocaccamo/django-extra-settings) (👨‍💻 12 · 🔀 30 · 📦 100 · 📋 37 - 8% open · ⏱️ 11.01.2025):

	```
	git clone https://github.com/fabiocaccamo/django-extra-settings
	```
- [PyPi](https://pypi.org/project/django-extra-settings) (📥 15K / month):
	```
	pip install django-extra-settings
	```
</details>
<br>

## Dependency Injection

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/python-injector/injector">injector</a></b> (🥇25 ·  ⭐ 1.4K) - Python dependency injection framework, inspired by Guice. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/python-injector/injector) (👨‍💻 30 · 🔀 80 · 📦 2.5K · 📋 140 - 31% open · ⏱️ 07.07.2024):

	```
	git clone https://github.com/python-injector/injector
	```
- [PyPi](https://pypi.org/project/injector) (📥 1.8M / month):
	```
	pip install injector
	```
</details>
<details><summary><b><a href="https://github.com/maldoinc/wireup">wireup</a></b> (🥉20 ·  ⭐ 110) - Performant, concise, and easy-to-use dependency injection container for Python 3.8+. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maldoinc/wireup) (👨‍💻 4 · 🔀 8 · 📦 9 · 📋 41 - 41% open · ⏱️ 04.01.2025):

	```
	git clone https://github.com/maldoinc/wireup
	```
- [PyPi](https://pypi.org/project/wireup) (📥 2.1K / month):
	```
	pip install wireup
	```
</details>
<details><summary><b><a href="https://github.com/blubber/django_injector">django_injector</a></b> (🥉11 ·  ⭐ 51) - Dependency injection in Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/blubber/django_injector) (👨‍💻 7 · 🔀 7 · ⏱️ 09.04.2024):

	```
	git clone https://github.com/blubber/django_injector
	```
- [PyPi](https://pypi.org/project/django_injector) (📥 2.3K / month):
	```
	pip install django_injector
	```
</details>
<br>

## Debugging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-commons/django-debug-toolbar">django-debug-toolbar</a></b> (🥇39 ·  ⭐ 8.1K) - A configurable set of panels that display various debug information about the current request/response. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-commons/django-debug-toolbar) (👨‍💻 300 · 🔀 940 · 📥 250 · 📦 98K · 📋 930 - 6% open · ⏱️ 14.01.2025):

	```
	git clone https://github.com/jazzband/django-debug-toolbar
	```
- [PyPi](https://pypi.org/project/django-debug-toolbar) (📥 2.6M / month):
	```
	pip install django-debug-toolbar
	```
</details>
<br>

## Development

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/gauge-sh/tach">tach</a></b> (🥇28 ·  ⭐ 1.3K) - A Python tool to enforce dependencies, using modular architecture Open source Installable via pip Able to be adopted.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gauge-sh/tach) (👨‍💻 17 · 🔀 39 · 📦 33 · 📋 87 - 16% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/gauge-sh/tach
	```
- [PyPi](https://pypi.org/project/tach) (📥 220K / month):
	```
	pip install tach
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/django-browser-reload">django-browser-reload</a></b> (🥉25 ·  ⭐ 540) - Automatically reload your browser in development. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/adamchainz/django-browser-reload) (👨‍💻 6 · 🔀 29 · 📦 5.4K · 📋 41 - 34% open · ⏱️ 07.01.2025):

	```
	git clone https://github.com/adamchainz/django-browser-reload
	```
- [PyPi](https://pypi.org/project/django-browser-reload) (📥 130K / month):
	```
	pip install django-browser-reload
	```
</details>
<br>

## Logging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which improve logging and debugging._

<details><summary><b><a href="https://github.com/Delgan/loguru">loguru</a></b> (🥇40 ·  ⭐ 21K) - Python logging made (stupidly) simple. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Delgan/loguru) (👨‍💻 63 · 🔀 710 · 📦 110K · 📋 1K - 18% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/Delgan/loguru
	```
- [PyPi](https://pypi.org/project/loguru) (📥 37M / month):
	```
	pip install loguru
	```
</details>
<details><summary><b><a href="https://github.com/hynek/structlog">structlog</a></b> (🥈36 ·  ⭐ 3.7K · 📈) - Simple, powerful, and fast logging for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/hynek/structlog) (👨‍💻 120 · 🔀 230 · 📦 16K · 📋 350 - 8% open · ⏱️ 16.01.2025):

	```
	git clone https://github.com/hynek/structlog
	```
- [PyPi](https://pypi.org/project/structlog) (📥 26M / month):
	```
	pip install structlog
	```
</details>
<details><summary><b><a href="https://github.com/jrobichaud/django-structlog">django-structlog</a></b> (🥉26 ·  ⭐ 450 · 📉) - Structured Logging for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jrobichaud/django-structlog) (👨‍💻 21 · 🔀 33 · 📦 720 · 📋 67 - 2% open · ⏱️ 13.01.2025):

	```
	git clone https://github.com/jrobichaud/django-structlog
	```
- [PyPi](https://pypi.org/project/django-structlog) (📥 410K / month):
	```
	pip install django-structlog
	```
</details>
<details><summary><b><a href="https://github.com/snok/django-guid">django-guid</a></b> (🥉24 ·  ⭐ 460) - Inject an ID into every log message from a Django request. ASGI compatible, integrates with Sentry, and works with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snok/django-guid) (👨‍💻 12 · 🔀 26 · 📦 200 · 📋 29 - 17% open · ⏱️ 13.01.2025):

	```
	git clone https://github.com/snok/django-guid
	```
- [PyPi](https://pypi.org/project/django-guid) (📥 110K / month):
	```
	pip install django-guid
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/tarsil/django-loguru">django-loguru</a></b> (🥉8 ·  ⭐ 10 · 💤) - A middleware to log the requests and responses using loguru. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Application Monitoring (Platforms)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/getsentry/sentry">sentry</a></b> (🥇40 ·  ⭐ 40K) - Developer-first error tracking and performance monitoring. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/getsentry/sentry) (👨‍💻 900 · 🔀 4.2K · 📥 41K · 📦 510 · 📋 14K - 13% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/getsentry/sentry
	```
- [PyPi](https://pypi.org/project/sentry) (📥 9.8K / month):
	```
	pip install sentry
	```
</details>
<details><summary><b><a href="https://github.com/pydantic/logfire">logfire</a></b> (🥉31 ·  ⭐ 2.6K) - Uncomplicated Observability for Python and beyond!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydantic/logfire) (👨‍💻 44 · 🔀 83 · 📦 450 · 📋 230 - 27% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/pydantic/logfire
	```
- [PyPi](https://pypi.org/project/logfire) (📥 190K / month):
	```
	pip install logfire
	```
</details>
<br>

## Authentication and Authorization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pennersr/django-allauth">django-allauth</a></b> (🥇40 ·  ⭐ 9.7K) - Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pennersr/django-allauth) (👨‍💻 750 · 🔀 3K · 📦 240K · 📋 2.4K - 0% open · ⏱️ 27.12.2024):

	```
	git clone https://github.com/pennersr/django-allauth
	```
- [PyPi](https://pypi.org/project/django-allauth) (📥 910K / month):
	```
	pip install django-allauth
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-oauth-toolkit">django-oauth-toolkit</a></b> (🥇34 ·  ⭐ 3.2K) - OAuth2 goodies for the Djangonauts!. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jazzband/django-oauth-toolkit) (👨‍💻 270 · 🔀 760 · 📦 11K · 📋 860 - 20% open · ⏱️ 13.01.2025):

	```
	git clone https://github.com/jazzband/django-oauth-toolkit
	```
- [PyPi](https://pypi.org/project/django-oauth-toolkit) (📥 690K / month):
	```
	pip install django-oauth-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/python-social-auth/social-app-django">social-app-django</a></b> (🥈30 ·  ⭐ 2K) - Python Social Auth - Application - Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/python-social-auth/social-app-django) (👨‍💻 330 · 🔀 370 · 📦 48K · 📋 300 - 43% open · ⏱️ 16.01.2025):

	```
	git clone https://github.com/python-social-auth/social-app-django
	```
- [PyPi](https://pypi.org/project/social-app-django):
	```
	pip install social-app-django
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-two-factor-auth">django-two-factor-auth</a></b> (🥈30 ·  ⭐ 1.7K) - Complete Two-Factor Authentication for Django providing the easiest integration into most Django projects. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-two-factor-auth) (👨‍💻 100 · 🔀 420 · 📦 1.8K · 📋 370 - 23% open · ⏱️ 10.01.2025):

	```
	git clone https://github.com/jazzband/django-two-factor-auth
	```
- [PyPi](https://pypi.org/project/django-two-factor-auth) (📥 330K / month):
	```
	pip install django-two-factor-auth
	```
</details>
<details><summary><b><a href="https://github.com/django-guardian/django-guardian">django-guardian</a></b> (🥈28 ·  ⭐ 3.7K) - Per object permissions for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-guardian/django-guardian) (👨‍💻 160 · 🔀 550 · 📦 7.1K · 📋 460 - 27% open · ⏱️ 22.10.2024):

	```
	git clone https://github.com/django-guardian/django-guardian
	```
- [PyPi](https://pypi.org/project/django-guardian) (📥 270K / month):
	```
	pip install django-guardian
	```
</details>
<details><summary><b><a href="https://github.com/juanifioren/django-oidc-provider">django-oidc-provider</a></b> (🥈28 ·  ⭐ 430) - OpenID Connect and OAuth2 provider implementation for Djangonauts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/juanifioren/django-oidc-provider) (👨‍💻 74 · 🔀 220 · 📦 380 · 📋 200 - 23% open · ⏱️ 06.12.2024):

	```
	git clone https://github.com/juanifioren/django-oidc-provider
	```
- [PyPi](https://pypi.org/project/django-oidc-provider) (📥 11K / month):
	```
	pip install django-oidc-provider
	```
</details>
<details><summary><b><a href="https://github.com/bennylope/django-organizations">django-organizations</a></b> (🥈26 ·  ⭐ 1.3K) - Multi-user accounts for Django projects. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/bennylope/django-organizations) (👨‍💻 49 · 🔀 200 · 📦 300 · 📋 150 - 8% open · ⏱️ 28.10.2024):

	```
	git clone https://github.com/bennylope/django-organizations
	```
- [PyPi](https://pypi.org/project/django-organizations) (📥 36K / month):
	```
	pip install django-organizations
	```
</details>
<details><summary><b><a href="https://github.com/django-cas-ng/django-cas-ng">django-cas-ng</a></b> (🥈26 ·  ⭐ 380) - Django CAS 1.0/2.0/3.0 client authentication library, supporting Django 4.2+ and Python 3.8+. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-cas-ng/django-cas-ng) (👨‍💻 87 · 🔀 160 · 📥 700 · 📦 580 · 📋 160 - 4% open · ⏱️ 18.12.2024):

	```
	git clone https://github.com/django-cas-ng/django-cas-ng
	```
- [PyPi](https://pypi.org/project/django-cas-ng) (📥 26K / month):
	```
	pip install django-cas-ng
	```
</details>
<details><summary><b><a href="https://github.com/snok/django-auth-adfs">django-auth-adfs</a></b> (🥉25 ·  ⭐ 280) - A Django authentication backend for Microsoft ADFS and AzureAD. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/snok/django-auth-adfs) (👨‍💻 48 · 🔀 98 · 📦 160 · 📋 210 - 14% open · ⏱️ 15.01.2025):

	```
	git clone https://github.com/snok/django-auth-adfs
	```
- [PyPi](https://pypi.org/project/django-auth-adfs) (📥 59K / month):
	```
	pip install django-auth-adfs
	```
</details>
<details><summary><b><a href="https://github.com/jsocol/django-ratelimit">django-ratelimit</a></b> (🥉24 ·  ⭐ 1.1K · 💤) - Cache-based rate-limiting for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jsocol/django-ratelimit) (👨‍💻 51 · 🔀 180 · 📦 3.2K · 📋 150 - 16% open · ⏱️ 05.12.2023):

	```
	git clone https://github.com/jsocol/django-ratelimit
	```
- [PyPi](https://pypi.org/project/django-ratelimit) (📥 420K / month):
	```
	pip install django-ratelimit
	```
</details>
<details><summary><b><a href="https://github.com/django-otp/django-otp">django-otp</a></b> (🥉24 ·  ⭐ 560) - A pluggable framework for adding two-factor authentication to Django using one-time passwords. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/django-otp/django-otp) (👨‍💻 48 · 🔀 100 · 📦 3.6K · 📋 84 - 14% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/django-otp/django-otp
	```
- [PyPi](https://pypi.org/project/django-otp) (📥 800K / month):
	```
	pip install django-otp
	```
</details>
<details><summary><b><a href="https://github.com/valohai/django-allauth-2fa">django-allauth-2fa</a></b> (🥉22 ·  ⭐ 220) - Two-factor authentication for Django Allauth. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/valohai/django-allauth-2fa) (👨‍💻 32 · 🔀 49 · 📥 28 · 📦 240 · 📋 74 - 17% open · ⏱️ 16.01.2025):

	```
	git clone https://github.com/valohai/django-allauth-2fa
	```
- [PyPi](https://pypi.org/project/django-allauth-2fa) (📥 42K / month):
	```
	pip install django-allauth-2fa
	```
</details>
<details><summary><b><a href="https://github.com/caffeinehit/django-oauth2-provider">django-oauth2-provider</a></b> (🥉17 ·  ⭐ 340 · 💤) - Provide OAuth2 access to your app. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/caffeinehit/django-oauth2-provider) (👨‍💻 16 · 🔀 180 · 📋 65 - 61% open · ⏱️ 03.02.2023):

	```
	git clone https://github.com/caffeinehit/django-oauth2-provider
	```
- [PyPi](https://pypi.org/project/django-oauth2-provider) (📥 5.8K / month):
	```
	pip install django-oauth2-provider
	```
</details>
<details><summary><b><a href="https://github.com/idlesign/django-oauthost">django-oauthost</a></b> (🥉8 ·  ⭐ 25 · 💤) - Reusable application for Django, introducing OAuth2 server functionality. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/idlesign/django-oauthost) (👨‍💻 2 · 📦 5 · 📋 3 - 33% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/idlesign/django-oauthost
	```
- [PyPi](https://pypi.org/project/django-oauthost) (📥 430 / month):
	```
	pip install django-oauthost
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/dimagi/django-prbac">django-prbac</a></b> (🥉15 ·  ⭐ 140 · 💤) -  <code>❗Unlicensed</code>
- <b><a href="https://github.com/jrd/django-oauth2-authcodeflow">django-oauth2-authcodeflow</a></b> (🥉12 ·  ⭐ 14) - Authenticate with any OpenId Connect/Oauth2 provider through authorization code flow. PKCE is also supported. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dropseed/django-oauth-login">django-oauth-login</a></b> (🥉10 ·  ⭐ 15) - A minimal app that adds OAuth login support to your Django project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Authorization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/dfunckt/django-rules">django-rules</a></b> (🥇20 ·  ⭐ 1.9K) - Awesome Django authorization, without the database. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dfunckt/django-rules) (👨‍💻 32 · 🔀 140 · 📋 110 - 23% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/dfunckt/django-rules
	```
- [PyPi](https://pypi.org/project/django-rules) (📥 160 / month):
	```
	pip install django-rules
	```
</details>
<br>

## Task Queues

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/celery/celery">celery</a></b> (🥇43 ·  ⭐ 25K) - Distributed Task Queue (development branch). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/celery/celery) (👨‍💻 1.4K · 🔀 4.6K · 📦 160K · 📋 5.1K - 12% open · ⏱️ 14.01.2025):

	```
	git clone https://github.com/celery/celery
	```
- [PyPi](https://pypi.org/project/celery) (📥 12M / month):
	```
	pip install celery
	```
</details>
<details><summary><b><a href="https://github.com/rq/rq">rq</a></b> (🥈37 ·  ⭐ 10K) - Simple job queues for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rq/rq) (👨‍💻 330 · 🔀 1.4K · 📦 18K · 📋 1.2K - 16% open · ⏱️ 13.01.2025):

	```
	git clone https://github.com/rq/rq
	```
- [PyPi](https://pypi.org/project/rq) (📥 1.4M / month):
	```
	pip install rq
	```
</details>
<details><summary><b><a href="https://github.com/rq/django-rq">django-rq</a></b> (🥉31 ·  ⭐ 1.9K) - A simple app that provides django integration for RQ (Redis Queue). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rq/django-rq) (👨‍💻 130 · 🔀 280 · 📦 3.8K · 📋 360 - 27% open · ⏱️ 04.01.2025):

	```
	git clone https://github.com/rq/django-rq
	```
- [PyPi](https://pypi.org/project/django-rq) (📥 260K / month):
	```
	pip install django-rq
	```
</details>
<details><summary><b><a href="https://github.com/Koed00/django-q">django-q</a></b> (🥉30 ·  ⭐ 1.8K · 💤) - A multiprocessing distributed task queue for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Koed00/django-q) (👨‍💻 62 · 🔀 240 · 📦 1.8K · 📋 430 - 64% open · ⏱️ 26.06.2021):

	```
	git clone https://github.com/Koed00/django-q
	```
- [PyPi](https://pypi.org/project/django-q) (📥 66K / month):
	```
	pip install django-q
	```
</details>
<details><summary><b><a href="https://github.com/celery/django-celery-beat">django-celery-beat</a></b> (🥉26 ·  ⭐ 1.7K) - Celery Periodic Tasks backed by the Django ORM. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/celery/django-celery-beat) (👨‍💻 130 · 🔀 420 · 📋 420 - 24% open · ⏱️ 13.01.2025):

	```
	git clone https://github.com/celery/django-celery-beat
	```
- [PyPi](https://pypi.org/project/django-celery-beat) (📥 1.7M / month):
	```
	pip install django-celery-beat
	```
</details>
<br>

## Finite State Machine

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement Finite State Machines (e.g. to implement workflows)._

<details><summary><b><a href="https://github.com/pytransitions/transitions">transitions</a></b> (🥇33 ·  ⭐ 5.9K) - A lightweight, object-oriented finite state machine implementation in Python with many extensions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pytransitions/transitions) (👨‍💻 77 · 🔀 520 · 📦 3.8K · 📋 440 - 2% open · ⏱️ 13.08.2024):

	```
	git clone https://github.com/pytransitions/transitions
	```
- [PyPi](https://pypi.org/project/transitions) (📥 570K / month):
	```
	pip install transitions
	```
</details>
<details><summary><b><a href="https://github.com/viewflow/django-fsm">django-fsm</a></b> (🥈29 ·  ⭐ 2.3K) - Django friendly finite state machine support. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/viewflow/django-fsm) (👨‍💻 70 · 🔀 280 · 📦 1.8K · 📋 160 - 0% open · ⏱️ 16.04.2024):

	```
	git clone https://github.com/viewflow/django-fsm
	```
- [PyPi](https://pypi.org/project/django-fsm) (📥 260K / month):
	```
	pip install django-fsm
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-fsm-log">django-fsm-log</a></b> (🥈25 ·  ⭐ 240) - Automatic logging for Django FSM. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-fsm-log) (👨‍💻 28 · 🔀 74 · 📦 150 · 📋 47 - 23% open · ⏱️ 08.01.2025):

	```
	git clone https://github.com/jazzband/django-fsm-log
	```
- [PyPi](https://pypi.org/project/django-fsm-log) (📥 37K / month):
	```
	pip install django-fsm-log
	```
</details>
<details><summary><b><a href="https://github.com/viewflow/viewflow">viewflow</a></b> (🥉23 ·  ⭐ 2.7K) - Reusable workflow library for Django. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/viewflow/viewflow) (👨‍💻 2 · 🔀 400 · 📦 340 · 📋 350 - 4% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/viewflow/viewflow
	```
- [PyPi](https://pypi.org/project/viewflow) (📥 210 / month):
	```
	pip install viewflow
	```
</details>
<details><summary><b><a href="https://github.com/gadventures/django-fsm-admin">django-fsm-admin</a></b> (🥉18 ·  ⭐ 200 · 💤) - Mixin and template tags to integrate django-fsm transitions into the django admin. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gadventures/django-fsm-admin) (👨‍💻 32 · 🔀 94 · 📦 370 · 📋 39 - 48% open · ⏱️ 25.10.2022):

	```
	git clone https://github.com/gadventures/django-fsm-admin
	```
- [PyPi](https://pypi.org/project/django-fsm-admin) (📥 15K / month):
	```
	pip install django-fsm-admin
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/27medkamal/djangorestframework-fsm">djangorestframework-fsm</a></b> (🥉10 ·  ⭐ 19 · 💤) - Automatically hook your Django-FSM transitions up to Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ming-tung/django-fsm-freeze">django-fsm-freeze</a></b> (🥉9 ·  ⭐ 4) - django-fsm data immutability support. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## RESTful API (Django Rest Framework)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/encode/django-rest-framework">django-rest-framework</a></b> (🥇41 ·  ⭐ 29K) - Web APIs for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/encode/django-rest-framework) (👨‍💻 1.4K · 🔀 6.7K · 📦 760K · 📋 3.9K - 1% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/encode/django-rest-framework
	```
- [PyPi](https://pypi.org/project/django-rest-framework) (📥 97K / month):
	```
	pip install django-rest-framework
	```
</details>
<details><summary><b><a href="https://github.com/anexia-it/django-rest-passwordreset">django-rest-passwordreset</a></b> (🥈29 ·  ⭐ 430) - An extension of django rest framework, providing a configurable password reset strategy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anexia-it/django-rest-passwordreset) (👨‍💻 40 · 🔀 140 · 📦 4.1K · 📋 100 - 24% open · ⏱️ 13.11.2024):

	```
	git clone https://github.com/anexia-it/django-rest-passwordreset
	```
- [PyPi](https://pypi.org/project/django-rest-passwordreset) (📥 130K / month):
	```
	pip install django-rest-passwordreset
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/djangorestframework-simplejwt">djangorestframework-simplejwt</a></b> (🥉28 ·  ⭐ 4.1K · 📈) - A JSON Web Token authentication plugin for the Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/djangorestframework-simplejwt) (👨‍💻 120 · 🔀 620 · 📋 480 - 25% open · ⏱️ 13.01.2025):

	```
	git clone https://github.com/jazzband/djangorestframework-simplejwt
	```
- [PyPi](https://pypi.org/project/djangorestframework-simplejwt) (📥 2.8M / month):
	```
	pip install djangorestframework-simplejwt
	```
</details>
<details><summary><b><a href="https://github.com/yezyilomo/django-restql">django-restql</a></b> (🥉23 ·  ⭐ 620) - Turn your API made with Django REST Framework(DRF) into a GraphQL like API. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/yezyilomo/django-restql) (👨‍💻 7 · 🔀 43 · 📦 300 · 📋 110 - 23% open · ⏱️ 31.12.2024):

	```
	git clone https://github.com/yezyilomo/django-restql
	```
- [PyPi](https://pypi.org/project/django-restql) (📥 31K / month):
	```
	pip install django-restql
	```
</details>
<details><summary><b><a href="https://github.com/wq/django-rest-pandas">django-rest-pandas</a></b> (🥉16 ·  ⭐ 1.3K) - Serves up Pandas dataframes via the Django REST Framework for use in client-side (i.e. d3.js) visualizations and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wq/django-rest-pandas) (👨‍💻 3 · 🔀 120 · 📋 40 - 20% open · ⏱️ 04.04.2024):

	```
	git clone https://github.com/wq/django-rest-pandas
	```
- [PyPi](https://pypi.org/project/django-rest-pandas):
	```
	pip install django-rest-pandas
	```
</details>
<br>

## RESTful API (Django Ninja)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/vitalik/django-ninja">django-ninja</a></b> (🥇30 ·  ⭐ 7.6K) - Fast, Async-ready, Openapi, type hints based framework for building APIs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vitalik/django-ninja) (👨‍💻 150 · 🔀 450 · 📋 870 - 37% open · ⏱️ 12.01.2025):

	```
	git clone https://github.com/vitalik/django-ninja
	```
- [PyPi](https://pypi.org/project/django-ninja) (📥 470K / month):
	```
	pip install django-ninja
	```
</details>
<details><summary><b><a href="https://github.com/eadwinCode/django-ninja-jwt">django-ninja-jwt</a></b> (🥈25 ·  ⭐ 160) - A JSON Web Token authentication plugin for the Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eadwinCode/django-ninja-jwt) (👨‍💻 85 · 🔀 24 · 📦 350 · 📋 28 - 35% open · ⏱️ 09.01.2025):

	```
	git clone https://github.com/eadwinCode/django-ninja-jwt
	```
- [PyPi](https://pypi.org/project/django-ninja-jwt) (📥 46K / month):
	```
	pip install django-ninja-jwt
	```
</details>
<details><summary><b><a href="https://github.com/eadwinCode/django-ninja-extra">django-ninja-extra</a></b> (🥈23 ·  ⭐ 420) - Django Ninja Extra - Class-Based Utility and more for Django Ninja(Fast Django REST framework). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eadwinCode/django-ninja-extra) (👨‍💻 20 · 🔀 33 · 📋 75 - 18% open · ⏱️ 16.01.2025):

	```
	git clone https://github.com/eadwinCode/django-ninja-extra
	```
- [PyPi](https://pypi.org/project/django-ninja-extra) (📥 81K / month):
	```
	pip install django-ninja-extra
	```
</details>
<details><summary><b><a href="https://github.com/mawassk/django-ninja-apikey">django-ninja-apikey</a></b> (🥉12 ·  ⭐ 40 · 💤) - Easy to use API key authentication for Django Ninja REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mawassk/django-ninja-apikey) (🔀 10 · 📦 6 · 📋 3 - 66% open · ⏱️ 27.08.2021):

	```
	git clone https://github.com/mawassk/django-ninja-apikey
	```
- [PyPi](https://pypi.org/project/django-ninja-apikey) (📥 1.9K / month):
	```
	pip install django-ninja-apikey
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/eadwinCode/django-ninja-passwordreset">django-ninja-passwordreset</a></b> (🥉12 ·  ⭐ 5 · 💤) - An extension of django rest framework, providing a configurable password reset strategy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mugartec/django-ninja-auth">django-ninja-auth</a></b> (🥉7 ·  ⭐ 33 · 💤) -  <code><a href="https://tldrlegal.com/search?q=WTFPL">❗️WTFPL</a></code>
</details>
<br>

## Pydantic integration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pydantic/pydantic">pydantic</a></b> (🥇46 ·  ⭐ 22K) - Data validation using Python type hints. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydantic/pydantic) (👨‍💻 600 · 🔀 1.9K · 📦 620K · 📋 4.9K - 9% open · ⏱️ 16.01.2025):

	```
	git clone https://github.com/pydantic/pydantic
	```
- [PyPi](https://pypi.org/project/pydantic) (📥 260M / month):
	```
	pip install pydantic
	```
</details>
<details><summary><b><a href="https://github.com/jordaneremieff/djantic">djantic</a></b> (🥈19 ·  ⭐ 460 · 💤) - Pydantic model support for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jordaneremieff/djantic) (👨‍💻 4 · 🔀 34 · 📦 78 · 📋 41 - 31% open · ⏱️ 13.02.2023):

	```
	git clone https://github.com/jordaneremieff/djantic
	```
- [PyPi](https://pypi.org/project/djantic) (📥 6.1K / month):
	```
	pip install djantic
	```
</details>
<details><summary><b><a href="https://github.com/yezz123/pyngo">pyngo</a></b> (🥈19 ·  ⭐ 86) - Pydantic model support for Django & Django-Rest-Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/yezz123/pyngo) (👨‍💻 8 · 🔀 7 · 📦 19 · ⏱️ 13.01.2025):

	```
	git clone https://github.com/yezz123/pyngo
	```
- [PyPi](https://pypi.org/project/pyngo) (📥 5K / month):
	```
	pip install pyngo
	```
</details>
<details><summary><b><a href="https://github.com/jonathan-s/djantic2">djantic2</a></b> (🥉16 ·  ⭐ 62) - Pydantic model support for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jonathan-s/djantic2) (👨‍💻 8 · 🔀 6 · 📦 5 · 📋 9 - 22% open · ⏱️ 08.12.2024):

	```
	git clone https://github.com/jonathan-s/djantic2
	```
- [PyPi](https://pypi.org/project/djantic) (📥 6.1K / month):
	```
	pip install djantic
	```
</details>
<br>

## Pandas integration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/chrisdev/django-pandas">django-pandas</a></b> (🥇24 ·  ⭐ 800) - Tools for working with pandas in your Django projects. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/chrisdev/django-pandas) (👨‍💻 35 · 🔀 120 · 📦 2.5K · 📋 86 - 17% open · ⏱️ 03.04.2024):

	```
	git clone https://github.com/chrisdev/django-pandas
	```
- [PyPi](https://pypi.org/project/django-pandas) (📥 94K / month):
	```
	pip install django-pandas
	```
</details>
<br>

## GraphQL API

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement GraphQL API._

<details><summary><b><a href="https://github.com/graphql-python/graphene">graphene</a></b> (🥇38 ·  ⭐ 8.1K) - GraphQL framework for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene) (👨‍💻 210 · 🔀 810 · 📦 25K · 📋 1K - 8% open · ⏱️ 09.11.2024):

	```
	git clone https://github.com/graphql-python/graphene
	```
- [PyPi](https://pypi.org/project/graphene) (📥 9.7M / month):
	```
	pip install graphene
	```
</details>
<details><summary><b><a href="https://github.com/mirumee/ariadne">ariadne</a></b> (🥈33 ·  ⭐ 2.2K) - Python library for implementing GraphQL servers using schema-first approach. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mirumee/ariadne) (👨‍💻 78 · 🔀 180 · 📦 1.8K · 📋 320 - 10% open · ⏱️ 19.12.2024):

	```
	git clone https://github.com/mirumee/ariadne
	```
- [PyPi](https://pypi.org/project/ariadne) (📥 540K / month):
	```
	pip install ariadne
	```
</details>
<details><summary><b><a href="https://github.com/graphql-python/graphene-django">graphene-django</a></b> (🥈31 ·  ⭐ 4.3K) - Build powerful, efficient, and flexible GraphQL APIs with seamless Django integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene-django) (👨‍💻 220 · 🔀 740 · 📦 16K · 📋 830 - 17% open · ⏱️ 27.12.2024):

	```
	git clone https://github.com/graphql-python/graphene-django
	```
- [PyPi](https://pypi.org/project/graphene-django) (📥 410K / month):
	```
	pip install graphene-django
	```
</details>
<details><summary><b><a href="https://github.com/flavors/django-graphql-jwt">django-graphql-jwt</a></b> (🥉28 ·  ⭐ 820 · 💤) - JSON Web Token (JWT) authentication for Graphene Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/flavors/django-graphql-jwt) (👨‍💻 26 · 🔀 160 · 📦 5.4K · 📋 230 - 26% open · ⏱️ 04.08.2023):

	```
	git clone https://github.com/flavors/django-graphql-jwt
	```
- [PyPi](https://pypi.org/project/django-graphql-jwt) (📥 84K / month):
	```
	pip install django-graphql-jwt
	```
</details>
<details><summary><b><a href="https://github.com/strawberry-graphql/strawberry-django">strawberry-graphql-django</a></b> (🥉28 ·  ⭐ 430) - Strawberry GraphQL Django extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/strawberry-graphql/strawberry-django) (👨‍💻 97 · 🔀 130 · 📦 540 · 📋 340 - 23% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/strawberry-graphql/strawberry-graphql-django
	```
- [PyPi](https://pypi.org/project/strawberry-graphql-django) (📥 110K / month):
	```
	pip install strawberry-graphql-django
	```
</details>
<details><summary><b><a href="https://github.com/strawberry-graphql/strawberry">strawberry</a></b> (🥉27 ·  ⭐ 4.1K) - A GraphQL library for Python that leverages type annotations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/strawberry-graphql/strawberry) (👨‍💻 270 · 🔀 540 · 📥 680 · 📋 1K - 37% open · ⏱️ 15.01.2025):

	```
	git clone https://github.com/strawberry-graphql/strawberry
	```
- [PyPi](https://pypi.org/project/strawberry) (📥 610 / month):
	```
	pip install strawberry
	```
</details>
<details><summary><b><a href="https://github.com/PedroBern/django-graphql-auth">django-graphql-auth</a></b> (🥉20 ·  ⭐ 330 · 💤) - Django registration and authentication with GraphQL. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PedroBern/django-graphql-auth) (👨‍💻 16 · 🔀 100 · 📦 730 · 📋 100 - 58% open · ⏱️ 17.06.2022):

	```
	git clone https://github.com/PedroBern/django-graphql-auth
	```
- [PyPi](https://pypi.org/project/django-graphql-auth) (📥 7.1K / month):
	```
	pip install django-graphql-auth
	```
</details>
<details><summary><b><a href="https://github.com/mirumee/ariadne-django">ariadne-django</a></b> (🥉14 ·  ⭐ 67 · 💤) - ariadne_django makes integrating ariadne and django together easier. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mirumee/ariadne-django) (👨‍💻 9 · 🔀 11 · 📋 27 - 40% open · ⏱️ 23.08.2022):

	```
	git clone https://github.com/mirumee/ariadne-django
	```
- [PyPi](https://pypi.org/project/ariadne-django) (📥 11K / month):
	```
	pip install ariadne-django
	```
</details>
<br>

## Feature Flipper

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jazzband/django-waffle">django-waffle</a></b> (🥇33 ·  ⭐ 1.1K) - A feature flipper for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-waffle) (👨‍💻 120 · 🔀 240 · 📦 1.5K · 📋 220 - 18% open · ⏱️ 31.12.2024):

	```
	git clone https://github.com/django-waffle/django-waffle
	```
- [PyPi](https://pypi.org/project/django-waffle) (📥 480K / month):
	```
	pip install django-waffle
	```
</details>
<br>

## Statistics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which add application layer statistic functionality._

<details><summary><b><a href="https://github.com/pennersr/django-trackstats">django-trackstats</a></b> (🥇14 ·  ⭐ 440 · 💤) - Keep track of your statistics. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pennersr/django-trackstats) (👨‍💻 9 · 🔀 39 · 📦 28 · 📋 12 - 33% open · ⏱️ 04.08.2023):

	```
	git clone https://github.com/pennersr/django-trackstats
	```
- [PyPi](https://pypi.org/project/django-trackstats) (📥 1K / month):
	```
	pip install django-trackstats
	```
</details>
<br>

## Testing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pytest-dev/pytest-django">pytest-django</a></b> (🥇36 ·  ⭐ 1.4K) - A Django plugin for pytest. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-django) (👨‍💻 150 · 🔀 340 · 📦 85K · 📋 540 - 28% open · ⏱️ 29.09.2024):

	```
	git clone https://github.com/pytest-dev/pytest-django
	```
- [PyPi](https://pypi.org/project/pytest-django) (📥 3.6M / month):
	```
	pip install pytest-django
	```
</details>
<details><summary><b><a href="https://github.com/model-bakers/model_bakery">model_bakery</a></b> (🥈27 ·  ⭐ 860 · 📈) - Object factory for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/model-bakers/model_bakery) (👨‍💻 58 · 🔀 87 · 📦 4.7K · 📋 150 - 18% open · ⏱️ 06.01.2025):

	```
	git clone https://github.com/model-bakers/model_bakery
	```
- [PyPi](https://pypi.org/project/model_bakery) (📥 580K / month):
	```
	pip install model_bakery
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/django-test-migrations">django-test-migrations</a></b> (🥉26 ·  ⭐ 540) - Test django schema and data migrations, including migrations order and best practices. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/django-test-migrations) (👨‍💻 18 · 🔀 30 · 📦 860 · 📋 65 - 23% open · ⏱️ 15.01.2025):

	```
	git clone https://github.com/wemake-services/django-test-migrations
	```
- [PyPi](https://pypi.org/project/django-test-migrations) (📥 160K / month):
	```
	pip install django-test-migrations
	```
</details>
<details><summary><b><a href="https://github.com/FactoryBoy/factory_boy">factory_boy</a></b> (🥉24 ·  ⭐ 3.6K) - A test fixtures replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/FactoryBoy/factory_boy) (👨‍💻 130 · 🔀 390 · 📋 580 - 26% open · ⏱️ 27.11.2024):

	```
	git clone https://github.com/FactoryBoy/factory_boy
	```
- [PyPi](https://pypi.org/project/factory_boy) (📥 4.2M / month):
	```
	pip install factory_boy
	```
</details>
<details><summary><b><a href="https://github.com/revsys/django-test-plus">django-test-plus</a></b> (🥉18 ·  ⭐ 620) - Useful additions to Djangos default TestCase. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/revsys/django-test-plus) (👨‍💻 35 · 🔀 61 · 📋 57 - 10% open · ⏱️ 11.08.2024):

	```
	git clone https://github.com/revsys/django-test-plus
	```
- [PyPi](https://pypi.org/project/django-test-plus) (📥 61K / month):
	```
	pip install django-test-plus
	```
</details>
<br>

## CMS frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Content Management Systems which use Django under the hood._

<details><summary><b><a href="https://github.com/wagtail/wagtail">wagtail</a></b> (🥇42 ·  ⭐ 19K) - A Django content management system focused on flexibility and user experience. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wagtail/wagtail) (👨‍💻 970 · 🔀 3.9K · 📦 11K · 📋 5.2K - 16% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/wagtail/wagtail
	```
- [PyPi](https://pypi.org/project/wagtail) (📥 210K / month):
	```
	pip install wagtail
	```
</details>
<details><summary><b><a href="https://github.com/django-cms/django-cms">django-cms</a></b> (🥉40 ·  ⭐ 10K) - The easy-to-use and developer-friendly enterprise CMS powered by Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-cms/django-cms) (👨‍💻 580 · 🔀 3.1K · 📦 5.4K · 📋 3.6K - 3% open · ⏱️ 07.01.2025):

	```
	git clone https://github.com/django-cms/django-cms
	```
- [PyPi](https://pypi.org/project/django-cms) (📥 80K / month):
	```
	pip install django-cms
	```
</details>
<details><summary><b><a href="https://github.com/stephenmcd/mezzanine">mezzanine</a></b> (🥉26 ·  ⭐ 4.8K · 💤) - CMS framework for Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/stephenmcd/mezzanine) (👨‍💻 330 · 🔀 1.6K · 📋 1.1K - 4% open · ⏱️ 02.11.2022):

	```
	git clone https://github.com/stephenmcd/mezzanine
	```
- [PyPi](https://pypi.org/project/mezzanine) (📥 6.8K / month):
	```
	pip install mezzanine
	```
</details>
<br>

## E-Commerce frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_E-Commerce frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/django-oscar/django-oscar">django-oscar</a></b> (🥇37 ·  ⭐ 6.3K) - Domain-driven e-commerce for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-oscar/django-oscar) (👨‍💻 370 · 🔀 2.2K · 📦 1.1K · 📋 1.5K - 6% open · ⏱️ 10.01.2025):

	```
	git clone https://github.com/django-oscar/django-oscar
	```
- [PyPi](https://pypi.org/project/django-oscar) (📥 22K / month):
	```
	pip install django-oscar
	```
</details>
<details><summary><b><a href="https://github.com/saleor/saleor">saleor</a></b> (🥈33 ·  ⭐ 21K) - Saleor Core: the high performance, composable, headless commerce API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/saleor/saleor) (👨‍💻 300 · 🔀 5.4K · 📥 680 · 📦 6 · 📋 4.3K - 6% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/saleor/saleor
	```
- [PyPi](https://pypi.org/project/saleor) (📥 80 / month):
	```
	pip install saleor
	```
</details>
<details><summary><b><a href="https://github.com/awesto/django-shop">django-shop</a></b> (🥉26 ·  ⭐ 3.2K · 💤) - A Django based shop system. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/awesto/django-shop) (👨‍💻 96 · 🔀 1K · 📦 230 · 📋 380 - 23% open · ⏱️ 28.02.2021):

	```
	git clone https://github.com/awesto/django-shop
	```
- [PyPi](https://pypi.org/project/django-shop) (📥 5.1K / month):
	```
	pip install django-shop
	```
</details>
<details><summary><b><a href="https://github.com/shuup/shuup">shuup</a></b> (🥉24 ·  ⭐ 2.3K · 💤) - E-Commerce Platform. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/shuup/shuup) (👨‍💻 67 · 🔀 1.1K · 📥 710 · 📦 180 · 📋 440 - 33% open · ⏱️ 18.08.2021):

	```
	git clone https://github.com/shuup/shuup
	```
- [PyPi](https://pypi.org/project/shuup) (📥 4.3K / month):
	```
	pip install shuup
	```
</details>
<br>

## Analytics frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Analytics frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/milesmcc/shynet">shynet</a></b> (🥇18 ·  ⭐ 3K) - Modern, privacy-friendly, and detailed web analytics that works without cookies or JS. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/milesmcc/shynet) (👨‍💻 38 · 🔀 200 · 📋 190 - 24% open · ⏱️ 19.12.2024):

	```
	git clone https://github.com/milesmcc/shynet
	```
- [PyPi](https://pypi.org/project/shynet):
	```
	pip install shynet
	```
</details>
<br>

## Project management frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Project management frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/makeplane/plane">plane</a></b> (🥇26 ·  ⭐ 32K) - Open Source JIRA, Linear, Monday, and Asana Alternative. Plane helps you track your issues, epics, and product.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/makeplane/plane) (👨‍💻 100 · 🔀 1.8K · 📥 480 · 📋 1.1K - 37% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/makeplane/plane
	```
</details>
<details><summary><b><a href="https://github.com/kaleidos-ventures/taiga">taiga</a></b> (🥉12 ·  ⭐ 470 · 💤) - Taiga is a free and open-source project management for cross-functional agile teams. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/kaleidos-ventures/taiga) (👨‍💻 11 · 🔀 61 · ⏱️ 13.12.2023):

	```
	git clone https://github.com/kaleidos-ventures/taiga
	```
</details>
<br>

## Monitoring frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Monitoring frameworks which use Django under the hood._

<br>

## Photo management frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Photo management frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/LibrePhotos/librephotos">librephotos</a></b> (🥇21 ·  ⭐ 7.1K) - A self-hosted open source photo management service. This is the repository of the backend. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/LibrePhotos/librephotos) (👨‍💻 76 · 🔀 310 · 📋 880 - 30% open · ⏱️ 30.12.2024):

	```
	git clone https://github.com/LibrePhotos/librephotos
	```
</details>
<br>

## Recipe management frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Recipe management frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/TandoorRecipes/recipes">Tandoor Recipes</a></b> (🥇24 ·  ⭐ 5.8K) - Application for managing recipes, planning meals, building shopping lists and much much more!. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/TandoorRecipes/recipes) (👨‍💻 390 · 🔀 600 · 📋 1.8K - 16% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/TandoorRecipes/recipes
	```
</details>
<br>

## Document management frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Document management frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/paperless-ngx/paperless-ngx">Paperless-ngx</a></b> (🥇32 ·  ⭐ 24K) - A community-supported supercharged version of paperless: scan, index and archive all your physical documents. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/paperless-ngx/paperless-ngx) (👨‍💻 380 · 🔀 1.4K · 📥 130K · ⏱️ 16.01.2025):

	```
	git clone https://github.com/paperless-ngx/paperless-ngx
	```
</details>
<br>

## Education frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Education frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/openedx/edx-platform">Open edX</a></b> (🥇29 ·  ⭐ 7.5K) - The Open edX LMS & Studio, powering education sites around the world!. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/openedx/edx-platform) (👨‍💻 1.4K · 🔀 3.6K · 📦 3 · 📋 650 - 33% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/openedx/edx-platform
	```
</details>
<br>

## Inventory management system based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Inventory management systems which use Django under the hood._

<details><summary><b><a href="https://github.com/inventree/InvenTree">InvenTree</a></b> (🥇27 ·  ⭐ 4.6K) - Open Source Inventory Management System. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inventree/InvenTree) (👨‍💻 99 · 🔀 800 · 📥 980 · 📋 2.8K - 7% open · ⏱️ 16.01.2025):

	```
	git clone https://github.com/inventree/InvenTree
	```
</details>
<br>

## Crawler management system based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Web crawler management systems which use Django under the hood._

<br>

## Network automation system based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Network automation systems which use Django under the hood._

<details><summary><b><a href="https://github.com/netbox-community/netbox">netbox</a></b> (🥇31 ·  ⭐ 17K) - The premier source of truth powering network automation. Open source under Apache 2. Try NetBox Cloud free:.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/netbox-community/netbox) (👨‍💻 390 · 🔀 2.6K · 📋 11K - 3% open · ⏱️ 17.01.2025):

	```
	git clone https://github.com/netbox-community/netbox
	```
</details>
<br>

## Fields (encrypted)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/georgemarshall/django-cryptography">django-cryptography</a></b> (🥇19 ·  ⭐ 380) - Easily encrypt data in Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/georgemarshall/django-cryptography) (👨‍💻 4 · 🔀 73 · 📋 73 - 56% open · ⏱️ 16.02.2024):

	```
	git clone https://github.com/georgemarshall/django-cryptography
	```
- [PyPi](https://pypi.org/project/django-cryptography) (📥 130K / month):
	```
	pip install django-cryptography
	```
</details>
<details><summary><b><a href="https://github.com/luojilab/django-mirage-field">django-mirage-field</a></b> (🥈17 ·  ⭐ 93 · 💤) - Django model field encrypt/decrypt your data, keep secret in database. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/luojilab/django-mirage-field) (👨‍💻 9 · 🔀 13 · 📦 98 · 📋 13 - 7% open · ⏱️ 19.04.2022):

	```
	git clone https://github.com/luojilab/django-mirage-field
	```
- [PyPi](https://pypi.org/project/django-mirage-field) (📥 12K / month):
	```
	pip install django-mirage-field
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/orcasgit/django-fernet-fields">django-fernet-fields</a></b> (🥈18 ·  ⭐ 190 · 💀) - Fernet symmetric encryption for Django model fields. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/foundertherapy/django-cryptographic-fields">django-cryptographic-fields</a></b> (🥉14 ·  ⭐ 31 · 💀) - A set of fields that wrap standard Django fields with encryption provided by the python cryptography library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/lansharkconsulting/django/django-encrypted-model-fields">django-encrypted-model-fields</a></b> (🥉11 ·  ⭐ 33 · 💀) - A set of fields that wrap standard Django fields with encryption provided by the python cryptography library. <code>❗Unlicensed</code>
- <b><a href="https://gitlab.com/guywillett/django-searchable-encrypted-fields">django-searchable-encrypted-fields</a></b> (🥉6 ·  ⭐ 9 · 💀) -  <code>❗Unlicensed</code>
</details>
<br>

## Fields (phone numbers)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/stefanfoulis/django-phonenumber-field">django-phonenumber-field</a></b> (🥇32 ·  ⭐ 1.5K) - A django model and form field for normalised phone numbers using python-phonenumbers. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stefanfoulis/django-phonenumber-field) (👨‍💻 110 · 🔀 300 · 📥 33 · 📦 29K · 📋 230 - 3% open · ⏱️ 19.07.2024):

	```
	git clone https://github.com/stefanfoulis/django-phonenumber-field
	```
- [PyPi](https://pypi.org/project/django-phonenumber-field) (📥 1.2M / month):
	```
	pip install django-phonenumber-field
	```
</details>
<details><summary><b><a href="https://github.com/VeryApt/django-phone-field">django-phone-field</a></b> (🥉18 ·  ⭐ 52 · 💤) - Lightweight model and form field for phone numbers in Django. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/VeryApt/django-phone-field) (👨‍💻 4 · 🔀 13 · 📦 3.2K · 📋 15 - 26% open · ⏱️ 10.06.2020):

	```
	git clone https://github.com/VeryApt/django-phone-field
	```
- [PyPi](https://pypi.org/project/django-phone-field) (📥 36K / month):
	```
	pip install django-phone-field
	```
</details>
<br>

## Fields (addresses)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/furious-luke/django-address">django-address</a></b> (🥇24 ·  ⭐ 430 · 💤) - A Django address model and field. Addresses may be specified by address components or by performing an automatic.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/furious-luke/django-address) (👨‍💻 22 · 🔀 160 · 📦 460 · 📋 130 - 32% open · ⏱️ 05.05.2022):

	```
	git clone https://github.com/furious-luke/django-address
	```
- [PyPi](https://pypi.org/project/django-address) (📥 9.6K / month):
	```
	pip install django-address
	```
</details>
<details><summary><b><a href="https://github.com/openwisp/django-loci">django-loci</a></b> (🥈23 ·  ⭐ 180) - Reusable Django app for storing geographic and indoor coordinates. Maintained by the OpenWISP Project. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/openwisp/django-loci) (👨‍💻 30 · 🔀 42 · 📦 15 · 📋 41 - 4% open · ⏱️ 08.01.2025):

	```
	git clone https://github.com/openwisp/django-loci
	```
- [PyPi](https://pypi.org/project/django-loci) (📥 1.8K / month):
	```
	pip install django-loci
	```
</details>
<details><summary><b><a href="https://github.com/madisona/django-google-maps">django-google-maps</a></b> (🥉21 ·  ⭐ 280 · 💤) - Using the Google Maps API with django model admin. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/madisona/django-google-maps) (👨‍💻 19 · 🔀 95 · 📦 680 · 📋 47 - 25% open · ⏱️ 22.03.2022):

	```
	git clone https://github.com/madisona/django-google-maps
	```
- [PyPi](https://pypi.org/project/django-google-maps) (📥 9.8K / month):
	```
	pip install django-google-maps
	```
</details>
<details><summary><b><a href="https://github.com/simon-the-shark/django-mapbox-location-field">django-mapbox-location-field</a></b> (🥉20 ·  ⭐ 67) - Simple in use location model and form field with MapInput widget for picking some location. Uses mapbox gl js,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/simon-the-shark/django-mapbox-location-field) (👨‍💻 8 · 🔀 22 · 📦 410 · 📋 28 - 17% open · ⏱️ 20.06.2024):

	```
	git clone https://github.com/Simon-the-Shark/django-mapbox-location-field
	```
- [PyPi](https://pypi.org/project/django-mapbox-location-field) (📥 1.6K / month):
	```
	pip install django-mapbox-location-field
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/agusmakmun/django-address-model">django-address-model</a></b> (🥉9 ·  ⭐ 14 · 💤) - django abstract model that provide the complete address, eg: no, na/rt, ca/rw, village/desa, sub district/kecamatan,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Fields (versioning)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jazzband/django-simple-history">django-simple-history</a></b> (🥇35 ·  ⭐ 2.3K) - Store model history and view/revert changes from admin site. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-simple-history) (👨‍💻 190 · 🔀 460 · 📦 6.2K · 📋 600 - 23% open · ⏱️ 10.12.2024):

	```
	git clone https://github.com/jazzband/django-simple-history
	```
- [PyPi](https://pypi.org/project/django-simple-history) (📥 1.1M / month):
	```
	pip install django-simple-history
	```
</details>
<details><summary><b><a href="https://github.com/etianen/django-reversion">django-reversion</a></b> (🥈33 ·  ⭐ 3.1K) - django-reversion is an extension to the Django web framework that provides version control for model instances. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/etianen/django-reversion) (👨‍💻 190 · 🔀 460 · 📦 7.6K · 📋 650 - 2% open · ⏱️ 09.08.2024):

	```
	git clone https://github.com/etianen/django-reversion
	```
- [PyPi](https://pypi.org/project/django-reversion) (📥 360K / month):
	```
	pip install django-reversion
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-auditlog">django-auditlog</a></b> (🥈30 ·  ⭐ 1.2K · 📉) - A Django app that keeps a log of changes made to an object. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-auditlog) (👨‍💻 86 · 🔀 380 · 📥 480 · 📦 1.3K · 📋 290 - 24% open · ⏱️ 03.12.2024):

	```
	git clone https://github.com/jazzband/django-auditlog
	```
- [PyPi](https://pypi.org/project/django-auditlog) (📥 310K / month):
	```
	pip install django-auditlog
	```
</details>
<details><summary><b><a href="https://github.com/soynatan/django-easy-audit">django-easy-audit</a></b> (🥉24 ·  ⭐ 760 · 📉) - Yet another Django audit log app, hopefully the simplest one. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/soynatan/django-easy-audit) (👨‍💻 50 · 🔀 180 · 📦 320 · 📋 160 - 49% open · ⏱️ 26.11.2024):

	```
	git clone https://github.com/soynatan/django-easy-audit
	```
- [PyPi](https://pypi.org/project/django-easy-audit) (📥 49K / month):
	```
	pip install django-easy-audit
	```
</details>
<details><summary><b><a href="https://github.com/romgar/django-dirtyfields">django-dirtyfields</a></b> (🥉23 ·  ⭐ 630) - Tracking dirty fields on a Django model. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/romgar/django-dirtyfields) (👨‍💻 42 · 🔀 96 · 📦 620 · 📋 72 - 16% open · ⏱️ 09.11.2024):

	```
	git clone https://github.com/romgar/django-dirtyfields
	```
- [PyPi](https://pypi.org/project/django-dirtyfields) (📥 190K / month):
	```
	pip install django-dirtyfields
	```
</details>
<details><summary><b><a href="https://github.com/craigds/django-fieldsignals">django-fieldsignals</a></b> (🥉16 ·  ⭐ 110 · 💤) - Django signals for changed fields. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/craigds/django-fieldsignals) (👨‍💻 5 · 🔀 10 · 📦 310 · 📋 17 - 17% open · ⏱️ 08.10.2022):

	```
	git clone https://github.com/craigds/django-fieldsignals
	```
- [PyPi](https://pypi.org/project/django-fieldsignals) (📥 26K / month):
	```
	pip install django-fieldsignals
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/vvangelovski/django-audit-log">django-audit-log</a></b> (🥉17 ·  ⭐ 230 · 💀) - Audit log for your Django models. <code>❗Unlicensed</code>
</details>
<br>

## Messaging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/lamby/django-slack">django-slack</a></b> (🥇22 ·  ⭐ 240) - Slack integration for Django, using the templating engine to generate messages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lamby/django-slack) (👨‍💻 29 · 🔀 55 · 📦 430 · 📋 63 - 14% open · ⏱️ 10.05.2024):

	```
	git clone https://github.com/lamby/django-slack
	```
- [PyPi](https://pypi.org/project/django-slack) (📥 67K / month):
	```
	pip install django-slack
	```
</details>
<details><summary><b><a href="https://github.com/stefanfoulis/django-sendsms">django-sendsms</a></b> (🥈17 ·  ⭐ 260 · 💤) - A simple API to send SMS messages. It is modeled after the django email api. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stefanfoulis/django-sendsms) (👨‍💻 19 · 🔀 90 · 📦 380 · 📋 24 - 20% open · ⏱️ 27.12.2021):

	```
	git clone https://github.com/stefanfoulis/django-sendsms
	```
- [PyPi](https://pypi.org/project/django-sendsms) (📥 3.5K / month):
	```
	pip install django-sendsms
	```
</details>
<details><summary><b><a href="https://github.com/roaldnefs/django-sms">django-sms</a></b> (🥉13 ·  ⭐ 55) - A Django app for sending SMS with interchangeable backends. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/roaldnefs/django-sms) (👨‍💻 3 · 🔀 13 · 📋 15 - 40% open · ⏱️ 07.01.2024):

	```
	git clone https://github.com/roaldnefs/django-sms
	```
- [PyPi](https://pypi.org/project/django-sms) (📥 11K / month):
	```
	pip install django-sms
	```
</details>
<details><summary><b><a href="https://github.com/Ninjaclasher/django-discord-integration">django-discord-integration</a></b> (🥉10 ·  ⭐ 22) - Discord integration for Django, supporting error reporting via webhooks. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/Ninjaclasher/django-discord-integration) (👨‍💻 2 · 🔀 1 · 📦 7 · 📋 3 - 33% open · ⏱️ 28.05.2024):

	```
	git clone https://github.com/Ninjaclasher/django-discord-integration
	```
- [PyPi](https://pypi.org/project/django-discord-integration) (📥 1.5K / month):
	```
	pip install django-discord-integration
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/AdvocatesInc/django-channels-discord">django-channels-discord</a></b> (🥉5 ·  ⭐ 12 · 💤) - An interface server connecting Djangos Channels and Discord. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Storage

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jschneier/django-storages">django-storages</a></b> (🥇35 ·  ⭐ 2.8K) - https://django-storages.readthedocs.io/. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jschneier/django-storages) (👨‍💻 280 · 🔀 820 · 📦 190K · 📋 730 - 14% open · ⏱️ 11.01.2025):

	```
	git clone https://github.com/jschneier/django-storages
	```
- [PyPi](https://pypi.org/project/django-storages) (📥 3.4M / month):
	```
	pip install django-storages
	```
</details>
<details><summary><b><a href="https://github.com/py-pa/django-minio-storage">django-minio-storage</a></b> (🥉22 ·  ⭐ 160 · 💤) - A django storage driver for minio. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/py-pa/django-minio-storage) (👨‍💻 18 · 🔀 54 · 📦 320 · 📋 83 - 14% open · ⏱️ 19.12.2023):

	```
	git clone https://github.com/py-pa/django-minio-storage
	```
- [PyPi](https://pypi.org/project/django-minio-storage) (📥 19K / month):
	```
	pip install django-minio-storage
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/maddevsio/django_minio">django-minio</a></b> (🥉8 ·  ⭐ 65 · 💀) - Django app to use Minio Server as file storage. <code>❗Unlicensed</code>
</details>
<br>

## Event Sourcing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pyeventsourcing/eventsourcing">eventsourcing</a></b> (🥇25 ·  ⭐ 1.5K) - A library for event sourcing in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyeventsourcing/eventsourcing) (👨‍💻 27 · 🔀 130 · 📦 170 · 📋 93 - 1% open · ⏱️ 08.11.2024):

	```
	git clone https://github.com/pyeventsourcing/eventsourcing
	```
- [PyPi](https://pypi.org/project/eventsourcing) (📥 13K / month):
	```
	pip install eventsourcing
	```
</details>
<details><summary><b><a href="https://github.com/pyeventsourcing/eventsourcing-django">eventsourcing-django</a></b> (🥈14 ·  ⭐ 46) - Python package for eventsourcing with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyeventsourcing/eventsourcing-django) (👨‍💻 6 · 🔀 10 · 📦 9 · 📋 4 - 50% open · ⏱️ 09.11.2024):

	```
	git clone https://github.com/pyeventsourcing/eventsourcing-django
	```
- [PyPi](https://pypi.org/project/eventsourcing-django) (📥 1.2K / month):
	```
	pip install eventsourcing-django
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/pyeventsourcing/eventsourcing-eventstoredb">eventsourcing-eventstoredb</a></b> (🥉7 ·  ⭐ 17) - Python package for eventsourcing with EventStoreDB. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pyeventsourcing/eventsourcing-axonserver">eventsourcing-axonserver</a></b> (🥉5 ·  ⭐ 2 · 💤) - Python package for eventsourcing with Axon Server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pyeventsourcing/eventsourcing-dynamodb">eventsourcing-dynamodb</a></b> (🥉4 ·  ⭐ 6 · 💤) - Python package for eventsourcing with DynamoDB. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Locking

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/saxix/django-concurrency">django-concurrency</a></b> (🥇22 ·  ⭐ 440) - Optimistic lock implementation for Django. Prevents users from doing concurrent editing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/saxix/django-concurrency) (👨‍💻 25 · 🔀 49 · 📦 200 · 📋 73 - 6% open · ⏱️ 28.09.2024):

	```
	git clone https://github.com/saxix/django-concurrency
	```
- [PyPi](https://pypi.org/project/django-concurrency) (📥 56K / month):
	```
	pip install django-concurrency
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/gavinwahl/django-optimistic-lock">django-optimistic-lock</a></b> (🥉14 ·  ⭐ 120 · 💀) - Offline optimistic locking for Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/debrouwere/django-locking">django-locking</a></b> (🥉8 ·  ⭐ 130 · 💀) - Prevents users from doing concurrent editing in Django. Works out of the box in the admin interface, or you can.. <code>❗Unlicensed</code>
</details>
<br>

## Example data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/Brobin/django-seed">django-seed</a></b> (🥇25 ·  ⭐ 690 · 💤) - Seed your Django database with fake data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Brobin/django-seed) (👨‍💻 23 · 🔀 82 · 📦 5K · 📋 61 - 31% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/brobin/django-seed
	```
- [PyPi](https://pypi.org/project/django-seed) (📥 23K / month):
	```
	pip install django-seed
	```
</details>
<details><summary><b><a href="https://github.com/davedash/django-fixture-magic">django-fixture-magic</a></b> (🥉19 ·  ⭐ 390 · 💤) - Utilities to extract and manipulate Django Fixtures. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/davedash/django-fixture-magic) (👨‍💻 36 · 🔀 89 · 📦 170 · 📋 35 - 34% open · ⏱️ 26.10.2023):

	```
	git clone https://github.com/davedash/django-fixture-magic
	```
- [PyPi](https://pypi.org/project/django-fixture-magic) (📥 19K / month):
	```
	pip install django-fixture-magic
	```
</details>
<details><summary><b><a href="https://github.com/klen/mixer">mixer</a></b> (🥉16 ·  ⭐ 940 · 💤) - Mixer -- Is a fixtures replacement. Supported Django, Flask, SqlAlchemy and custom python objects. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/klen/mixer) (👨‍💻 43 · 🔀 93 · 📋 87 - 43% open · ⏱️ 23.03.2022):

	```
	git clone https://github.com/klen/mixer
	```
- [PyPi](https://pypi.org/project/mixer) (📥 120K / month):
	```
	pip install mixer
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/gregmuellegger/django-autofixture">django-autofixture</a></b> (🥈21 ·  ⭐ 460 · 💀) - Can create auto-generated test data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Fake data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/model-bakers/model_bakery">model-bakery</a></b> (🥇27 ·  ⭐ 860) - Object factory for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/model-bakers/model_bakery) (👨‍💻 58 · 🔀 87 · 📦 4.7K · 📋 150 - 18% open · ⏱️ 06.01.2025):

	```
	git clone https://github.com/model-bakers/model_bakery
	```
- [PyPi](https://pypi.org/project/model-bakery/) (📥 580K / month):
	```
	pip install model-bakery/
	```
</details>
<details><summary><b><a href="https://github.com/paulocheque/django-dynamic-fixture">django-dynamic-fixture</a></b> (🥉20 ·  ⭐ 390) - A complete library to create dynamic model instances for testing purposes. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/paulocheque/django-dynamic-fixture) (👨‍💻 37 · 🔀 62 · 📦 1.2K · 📋 70 - 8% open · ⏱️ 10.10.2024):

	```
	git clone https://github.com/paulocheque/django-dynamic-fixture
	```
- [PyPi](https://pypi.org/project/django-dynamic-fixture) (📥 52K / month):
	```
	pip install django-dynamic-fixture
	```
</details>
<br>

## Bootstrap CSS Framework Integration (Django MVT application)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/zostera/django-bootstrap4">django-bootstrap4</a></b> (🥇33 ·  ⭐ 1K) - Bootstrap 4 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap4) (👨‍💻 140 · 🔀 220 · 📦 170K · 📋 160 - 10% open · ⏱️ 11.12.2024):

	```
	git clone https://github.com/zostera/django-bootstrap4
	```
- [PyPi](https://pypi.org/project/django-bootstrap4) (📥 140K / month):
	```
	pip install django-bootstrap4
	```
</details>
<details><summary><b><a href="https://github.com/zostera/django-bootstrap3">django-bootstrap3</a></b> (🥈32 ·  ⭐ 2.3K) - Bootstrap 3 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap3) (👨‍💻 100 · 🔀 670 · 📦 19K · ⏱️ 11.12.2024):

	```
	git clone https://github.com/zostera/django-bootstrap3
	```
- [PyPi](https://pypi.org/project/django-bootstrap3) (📥 91K / month):
	```
	pip install django-bootstrap3
	```
</details>
<details><summary><b><a href="https://github.com/zostera/django-bootstrap5">django-bootstrap5</a></b> (🥉28 ·  ⭐ 410) - Bootstrap 5 for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap5) (👨‍💻 150 · 🔀 84 · 📦 8.3K · 📋 100 - 33% open · ⏱️ 16.12.2024):

	```
	git clone https://github.com/zostera/django-bootstrap5
	```
- [PyPi](https://pypi.org/project/django-bootstrap5) (📥 130K / month):
	```
	pip install django-bootstrap5
	```
</details>
<details><summary><b><a href="https://github.com/zelenij/django-bootstrap-v5">django-bootstrap-v5</a></b> (🥉21 ·  ⭐ 100) - Bootstrap 5 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zelenij/django-bootstrap-v5) (👨‍💻 140 · 🔀 43 · 📦 9.4K · 📋 24 - 33% open · ⏱️ 07.01.2024):

	```
	git clone https://github.com/zelenij/django-bootstrap-v5
	```
- [PyPi](https://pypi.org/project/django-bootstrap-v5) (📥 46K / month):
	```
	pip install django-bootstrap-v5
	```
</details>
<br>

## Bulma CSS Framework Integration (Django MVT application)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/timonweb/django-bulma">django-bulma</a></b> (🥇18 ·  ⭐ 340) - Bulma theme for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timonweb/django-bulma) (👨‍💻 15 · 🔀 55 · 📦 520 · 📋 43 - 11% open · ⏱️ 26.06.2024):

	```
	git clone https://github.com/timonweb/django-bulma
	```
- [PyPi](https://pypi.org/project/django-bulma) (📥 4.2K / month):
	```
	pip install django-bulma
	```
</details>
<br>

## TailwindCSS CSS Framework Integration (Django MVT application)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/timonweb/django-tailwind">django-tailwind</a></b> (🥇24 ·  ⭐ 1.5K · 💤) - Django + Tailwind CSS =. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timonweb/django-tailwind) (👨‍💻 19 · 🔀 91 · 📦 5.2K · 📋 160 - 14% open · ⏱️ 22.12.2023):

	```
	git clone https://github.com/timonweb/django-tailwind
	```
- [PyPi](https://pypi.org/project/django-tailwind) (📥 88K / month):
	```
	pip install django-tailwind
	```
</details>
<details><summary><b><a href="https://github.com/django-commons/django-tailwind-cli">django-tailwind-cli</a></b> (🥉21 ·  ⭐ 110) - Django and Tailwind integration based on the prebuilt Tailwind CSS CLI. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-commons/django-tailwind-cli) (👨‍💻 12 · 🔀 12 · 📥 23 · 📦 48 · 📋 25 - 8% open · ⏱️ 14.01.2025):

	```
	git clone https://github.com/oliverandrich/django-tailwind-cli
	```
- [PyPi](https://pypi.org/project/django-tailwind-cli) (📥 8K / month):
	```
	pip install django-tailwind-cli
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/timonweb/pytailwindcss">pytailwindcss</a></b> (🥉15 ·  ⭐ 330 · 💤) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Data exploration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/tolomea/django-data-browser">django-data-browser</a></b> (🥇18 ·  ⭐ 360) - Django app for user friendly querying of Django models. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/tolomea/django-data-browser) (👨‍💻 10 · 🔀 28 · 📦 36 · 📋 38 - 15% open · ⏱️ 09.04.2024):

	```
	git clone https://github.com/tolomea/django-data-browser
	```
- [PyPi](https://pypi.org/project/django-data-browser) (📥 7K / month):
	```
	pip install django-data-browser
	```
</details>
<br>

## Multiple tenants

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-tenants/django-tenants">django-tenants</a></b> (🥇32 ·  ⭐ 1.6K) - Django tenants using PostgreSQL Schemas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-tenants/django-tenants) (👨‍💻 110 · 🔀 340 · 📦 1K · 📋 670 - 34% open · ⏱️ 24.12.2024):

	```
	git clone https://github.com/django-tenants/django-tenants
	```
- [PyPi](https://pypi.org/project/django-tenants) (📥 98K / month):
	```
	pip install django-tenants
	```
</details>
<details><summary><b><a href="https://github.com/bernardopires/django-tenant-schemas">django-tenant-schemas</a></b> (🥈27 ·  ⭐ 1.5K · 💤) - Tenant support for Django using PostgreSQL schemas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bernardopires/django-tenant-schemas) (👨‍💻 75 · 🔀 390 · 📦 440 · 📋 480 - 30% open · ⏱️ 02.07.2023):

	```
	git clone https://github.com/bernardopires/django-tenant-schemas
	```
- [PyPi](https://pypi.org/project/django-tenant-schemas) (📥 23K / month):
	```
	pip install django-tenant-schemas
	```
</details>
<details><summary><b><a href="https://github.com/citusdata/django-multitenant">django-multitenant</a></b> (🥉23 ·  ⭐ 750) - Python/Django support for distributed multi-tenant databases like Postgres+Citus. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/citusdata/django-multitenant) (👨‍💻 25 · 🔀 120 · 📦 69 · 📋 98 - 42% open · ⏱️ 30.04.2024):

	```
	git clone https://github.com/citusdata/django-multitenant
	```
- [PyPi](https://pypi.org/project/django-multitenant) (📥 19K / month):
	```
	pip install django-multitenant
	```
</details>
<details><summary><b><a href="https://github.com/raphaelm/django-scopes">django-scopes</a></b> (🥉16 ·  ⭐ 240 · 💤) - Safely separate multiple tenants in a Django database. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/raphaelm/django-scopes) (👨‍💻 6 · 🔀 15 · 📦 110 · 📋 19 - 63% open · ⏱️ 12.06.2023):

	```
	git clone https://github.com/raphaelm/django-scopes
	```
- [PyPi](https://pypi.org/project/django-scopes) (📥 9K / month):
	```
	pip install django-scopes
	```
</details>
<br>

## Value-as-a-Service frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_SaaS frameworks, subscription-based tutorials etc. which use Django under the hood._

<details><summary><b><a href="https://github.com/djaodjin/djaodjin-saas">djaodjin-saas</a></b> (🥇19 ·  ⭐ 580) - Django application for software-as-service and subscription businesses. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/djaodjin/djaodjin-saas) (👨‍💻 12 · 🔀 130 · 📦 11 · 📋 110 - 15% open · ⏱️ 14.01.2025):

	```
	git clone https://github.com/djaodjin/djaodjin-saas
	```
- [PyPi](https://pypi.org/project/djaodjin-saas) (📥 2K / month):
	```
	pip install djaodjin-saas
	```
</details>
<br>

## Payment and Subscription (Stripe, etc.)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/dj-stripe/dj-stripe">dj-stripe</a></b> (🥇33 ·  ⭐ 1.7K) - dj-stripe automatically syncs your Stripe Data to your local database as pre-implemented Django Models allowing you to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dj-stripe/dj-stripe) (👨‍💻 130 · 🔀 480 · 📦 1.1K · 📋 1K - 5% open · ⏱️ 07.01.2025):

	```
	git clone https://github.com/dj-stripe/dj-stripe
	```
- [PyPi](https://pypi.org/project/dj-stripe) (📥 110K / month):
	```
	pip install dj-stripe
	```
</details>
<details><summary><b><a href="https://github.com/spookylukey/django-paypal">django-paypal</a></b> (🥇26 ·  ⭐ 730) - A pluggable Django application for integrating PayPal Payments Standard or Payments Pro. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/spookylukey/django-paypal) (👨‍💻 73 · 🔀 200 · 📦 3.9K · 📋 160 - 7% open · ⏱️ 18.11.2024):

	```
	git clone https://github.com/spookylukey/django-paypal
	```
- [PyPi](https://pypi.org/project/django-paypal) (📥 28K / month):
	```
	pip install django-paypal
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-payments">django-payments</a></b> (🥈23 ·  ⭐ 1.1K) - Universal payment handling for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jazzband/django-payments) (👨‍💻 66 · 🔀 270 · 📥 30 · 📦 590 · 📋 180 - 36% open · ⏱️ 19.12.2024):

	```
	git clone https://github.com/jazzband/django-payments
	```
- [PyPi](https://pypi.org/project/django-payments) (📥 7.9K / month):
	```
	pip install django-payments
	```
</details>
<details><summary><b><a href="https://github.com/django-getpaid/django-getpaid">django-getpaid</a></b> (🥈22 ·  ⭐ 440 · 💤) - Django payments processor. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-getpaid/django-getpaid) (👨‍💻 30 · 🔀 110 · 📦 49 · 📋 61 - 4% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/django-getpaid/django-getpaid
	```
- [PyPi](https://pypi.org/project/django-getpaid) (📥 3.6K / month):
	```
	pip install django-getpaid
	```
</details>
<details><summary><b><a href="https://github.com/pinax/pinax-stripe-light">pinax-stripe-light</a></b> (🥈21 ·  ⭐ 690 · 💤) - a payments Django app for Stripe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pinax/pinax-stripe-light) (👨‍💻 72 · 🔀 270 · 📋 300 - 22% open · ⏱️ 28.11.2021):

	```
	git clone https://github.com/pinax/pinax-stripe-light
	```
- [PyPi](https://pypi.org/project/pinax-stripe-light) (📥 500 / month):
	```
	pip install pinax-stripe-light
	```
</details>
<details><summary><b><a href="https://github.com/django-oscar/django-oscar-paypal">django-oscar-paypal</a></b> (🥈21 ·  ⭐ 160 · 💤) - PayPal integration for django-oscar. Can be used without Oscar too. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-oscar/django-oscar-paypal) (👨‍💻 51 · 🔀 200 · 📦 160 · 📋 92 - 25% open · ⏱️ 01.09.2023):

	```
	git clone https://github.com/django-oscar/django-oscar-paypal
	```
- [PyPi](https://pypi.org/project/django-oscar-paypal) (📥 1.1K / month):
	```
	pip install django-oscar-paypal
	```
</details>
<details><summary><b><a href="https://github.com/silverapp/silver">silver</a></b> (🥈19 ·  ⭐ 300) - Automated billing and payments for Django with a REST API. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/silverapp/silver) (👨‍💻 24 · 🔀 76 · 📦 11 · 📋 390 - 13% open · ⏱️ 14.01.2025):

	```
	git clone https://github.com/silverapp/silver
	```
- [PyPi](https://pypi.org/project/silver) (📥 230 / month):
	```
	pip install silver
	```
</details>
<details><summary><b><a href="https://github.com/studybuffalo/django-flexible-subscriptions">django-flexible-subscriptions</a></b> (🥉16 ·  ⭐ 250 · 💤) - A subscription and recurrent billing application for Django. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/studybuffalo/django-flexible-subscriptions) (👨‍💻 14 · 🔀 52 · 📦 29 · 📋 50 - 54% open · ⏱️ 11.09.2020):

	```
	git clone https://github.com/studybuffalo/django-flexible-subscriptions
	```
- [PyPi](https://pypi.org/project/django-flexible-subscriptions) (📥 1.3K / month):
	```
	pip install django-flexible-subscriptions
	```
</details>
<details><summary><b><a href="https://github.com/HearthSim/dj-paypal">dj-paypal</a></b> (🥉16 ·  ⭐ 88) - Paypal integration for Django - Inspired by dj-Stripe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HearthSim/dj-paypal) (👨‍💻 3 · 🔀 20 · 📦 28 · 📋 9 - 44% open · ⏱️ 29.02.2024):

	```
	git clone https://github.com/HearthSim/dj-paypal
	```
- [PyPi](https://pypi.org/project/dj-paypal) (📥 1.3K / month):
	```
	pip install dj-paypal
	```
</details>
<details><summary><b><a href="https://github.com/kogan/django-subscriptions">django-subscriptions</a></b> (🥉15 ·  ⭐ 74 · 💤) - A django package for managing subscription states. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/kogan/django-subscriptions) (👨‍💻 2 · 🔀 9 · 📦 17 · ⏱️ 29.12.2020):

	```
	git clone https://github.com/kogan/django-subscriptions
	```
- [PyPi](https://pypi.org/project/django-subscriptions) (📥 1.9K / month):
	```
	pip install django-subscriptions
	```
</details>
<details><summary><b><a href="https://github.com/oscarychen/drf-stripe-subscription">drf-stripe-subscription</a></b> (🥉14 ·  ⭐ 110) - An out-of-box Django REST framework solution for payment and subscription management using Stripe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oscarychen/drf-stripe-subscription) (👨‍💻 6 · 🔀 19 · 📋 23 - 13% open · ⏱️ 16.11.2024):

	```
	git clone https://github.com/oscarychen/drf-stripe-subscription
	```
- [PyPi](https://pypi.org/project/drf-stripe-subscription) (📥 1.5K / month):
	```
	pip install drf-stripe-subscription
	```
</details>
<details><summary><b><a href="https://github.com/paddle-python/dj-paddle">dj-paddle</a></b> (🥉13 ·  ⭐ 83 · 💤) - Django + Paddle made Easy!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/paddle-python/dj-paddle) (👨‍💻 7 · 🔀 32 · 📋 25 - 56% open · ⏱️ 26.03.2021):

	```
	git clone https://github.com/paddle-python/dj-paddle
	```
- [PyPi](https://pypi.org/project/dj-paddle) (📥 460 / month):
	```
	pip install dj-paddle
	```
</details>
<details><summary><b><a href="https://github.com/bdelate/django-flutterwave">django-flutterwave</a></b> (🥉13 ·  ⭐ 23 · 💤) - Django integration for Flutterwave Rave payments and subscriptions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bdelate/django-flutterwave) (🔀 12 · 📦 49 · ⏱️ 29.12.2020):

	```
	git clone https://github.com/bdelate/django-flutterwave
	```
- [PyPi](https://pypi.org/project/django-flutterwave):
	```
	pip install django-flutterwave
	```
</details>
<details><summary><b><a href="https://github.com/duplxey/django-stripe-subscriptions">django-stripe-subscriptions</a></b> (🥉7 ·  ⭐ 35 · 💤) - How to handle subscription payments with Django and Stripe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/duplxey/django-stripe-subscriptions) (👨‍💻 3 · 🔀 11 · 📋 4 - 75% open · ⏱️ 20.07.2022):

	```
	git clone https://github.com/duplxey/django-stripe-subscriptions
	```
- [PyPi](https://pypi.org/project/django-stripe-subscriptions):
	```
	pip install django-stripe-subscriptions
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/agiliq/merchant">merchant</a></b> (🥈18 ·  ⭐ 1K · 💀) - A Django app to accept payments from various payment processors via Pluggable backends. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/kangasbros/django-bitcoin">django-bitcoin</a></b> (🥉15 ·  ⭐ 180 · 💀) - bitcoin payment management for django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/zen4ever/django-authorizenet">django-authorizenet</a></b> (🥉12 ·  ⭐ 87 · 💀) - Django and Authorize.NET payment gateway integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/zhaque/django-subscription">django-subscription</a></b> (🥉10 ·  ⭐ 180 · 💀) - Subscriptions or Recurring Billing App for django. <code>❗Unlicensed</code>
- <b><a href="https://github.com/vporton/django-payee">django-payee</a></b> (🥉4 ·  ⭐ 2 · 💤) - Accept (regular and subscription) payments in Internet (currently supports PayPal). Advanced support for subscription.. <code>❗Unlicensed</code>
</details>
<br>

## Emails

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/anymail/django-anymail">django-anymail</a></b> (🥇31 ·  ⭐ 1.7K) - Django email backends and webhooks for Amazon SES, Brevo (Sendinblue), MailerSend, Mailgun, Mailjet, Postmark, Postal,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anymail/django-anymail) (👨‍💻 66 · 🔀 130 · 📥 160 · 📦 7.1K · 📋 230 - 2% open · ⏱️ 11.12.2024):

	```
	git clone https://github.com/anymail/django-anymail
	```
- [PyPi](https://pypi.org/project/django-anymail) (📥 650K / month):
	```
	pip install django-anymail
	```
</details>
<details><summary><b><a href="https://github.com/django-ses/django-ses">django-ses</a></b> (🥈30 ·  ⭐ 1K) - A Django email backend for Amazons Simple Email Service. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-ses/django-ses) (👨‍💻 84 · 🔀 220 · 📦 3.2K · 📋 150 - 33% open · ⏱️ 14.01.2025):

	```
	git clone https://github.com/django-ses/django-ses
	```
- [PyPi](https://pypi.org/project/django-ses) (📥 540K / month):
	```
	pip install django-ses
	```
</details>
<details><summary><b><a href="https://github.com/ui/django-post_office">django-post-office</a></b> (🥉26 ·  ⭐ 1K) - A Django app that allows you to send email asynchronously in Django. Supports HTML email, database backed templates.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ui/django-post_office) (👨‍💻 82 · 🔀 250 · 📦 100 · 📋 250 - 37% open · ⏱️ 22.11.2024):

	```
	git clone https://github.com/ui/django-post_office
	```
- [PyPi](https://pypi.org/project/django-post-office) (📥 49K / month):
	```
	pip install django-post-office
	```
</details>
<details><summary><b><a href="https://github.com/coddingtonbear/django-mailbox">django-mailbox</a></b> (🥉23 ·  ⭐ 360) - Import mail from POP3, IMAP, local email mailboxes or directly from Postfix or Exim4 into your Django application.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coddingtonbear/django-mailbox) (👨‍💻 55 · 🔀 160 · 📦 210 · 📋 160 - 13% open · ⏱️ 11.01.2025):

	```
	git clone https://github.com/coddingtonbear/django-mailbox
	```
- [PyPi](https://pypi.org/project/django-mailbox) (📥 8.9K / month):
	```
	pip install django-mailbox
	```
</details>
<details><summary><b><a href="https://github.com/aio-libs/aiosmtpd">aiosmtpd</a></b> (🥉20 ·  ⭐ 330) - A reimplementation of the Python stdlib smtpd.py based on asyncio. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aio-libs/aiosmtpd) (👨‍💻 43 · 🔀 93 · 📥 550 · 📋 180 - 35% open · ⏱️ 01.12.2024):

	```
	git clone https://github.com/aio-libs/aiosmtpd
	```
- [PyPi](https://pypi.org/project/aiosmtpd) (📥 330K / month):
	```
	pip install aiosmtpd
	```
</details>
<br>

## Templates

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/adamchainz/django-htmx">django-htmx</a></b> (🥇27 ·  ⭐ 1.7K) - Extensions for using Django with htmx. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/adamchainz/django-htmx) (👨‍💻 24 · 🔀 140 · 📦 3.6K · 📋 79 - 5% open · ⏱️ 07.01.2025):

	```
	git clone https://github.com/adamchainz/django-htmx
	```
- [PyPi](https://pypi.org/project/django-htmx) (📥 230K / month):
	```
	pip install django-htmx
	```
</details>
<details><summary><b><a href="https://github.com/django-compressor/django-compressor">django-compressor</a></b> (🥈23 ·  ⭐ 2.8K) - Compresses linked and inline javascript or CSS into a single cached file. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-compressor/django-compressor) (👨‍💻 220 · 🔀 560 · 📋 660 - 17% open · ⏱️ 24.12.2024):

	```
	git clone https://github.com/django-compressor/django-compressor
	```
- [PyPi](https://pypi.org/project/django-compressor) (📥 510K / month):
	```
	pip install django-compressor
	```
</details>
<details><summary><b><a href="https://github.com/inertiajs/inertia-django">inertia-django</a></b> (🥉19 ·  ⭐ 370) - The Django adapter for Inertia.js. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inertiajs/inertia-django) (👨‍💻 12 · 🔀 36 · 📦 120 · 📋 35 - 22% open · ⏱️ 14.01.2025):

	```
	git clone https://github.com/inertiajs/inertia-django
	```
- [PyPi](https://pypi.org/project/inertia-django) (📥 4.2K / month):
	```
	pip install inertia-django
	```
</details>
<details><summary><b><a href="https://github.com/carltongibson/django-template-partials">django-template-partials</a></b> (🥉17 ·  ⭐ 500) - Reusable named inline partials for the Django Template Language. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carltongibson/django-template-partials) (👨‍💻 14 · 🔀 18 · 📦 240 · 📋 26 - 30% open · ⏱️ 10.09.2024):

	```
	git clone https://github.com/carltongibson/django-template-partials
	```
- [PyPi](https://pypi.org/project/django-template-partials) (📥 32K / month):
	```
	pip install django-template-partials
	```
</details>
<br>

## Reusable app templates

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/wemake-services/wemake-django-template">wemake-django-template</a></b> (🥇22 ·  ⭐ 2K) - Bleeding edge django template focused on code quality and security. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/wemake-django-template) (👨‍💻 49 · 🔀 220 · 📋 540 - 4% open · ⏱️ 14.01.2025):

	```
	git clone https://github.com/wemake-services/wemake-django-template
	```
</details>
<details><summary><b><a href="https://github.com/pydanny/cookiecutter-djangopackage">cookiecutter-djangopackage</a></b> (🥇13 ·  ⭐ 440 · 💤) - A cookiecutter template for creating reusable Django packages quickly. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pydanny/cookiecutter-djangopackage) (👨‍💻 55 · 🔀 140 · 📋 72 - 38% open · ⏱️ 29.10.2020):

	```
	git clone https://github.com/pydanny/cookiecutter-djangopackage
	```
- [PyPi](https://pypi.org/project/cookiecutter-djangopackage):
	```
	pip install cookiecutter-djangopackage
	```
</details>
<details><summary><b><a href="https://github.com/wq/wq-django-template">wq-django-template</a></b> (🥈10 ·  ⭐ 27) - Django + NPM (Create React App) template for building REST-ful web & hybrid apps with the wq framework. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/wq/wq-django-template) (👨‍💻 4 · 🔀 7 · ⏱️ 27.03.2024):

	```
	git clone https://github.com/wq/wq-django-template
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/wildfish/cookiecutter-django-crud">cookiecutter-django-crud</a></b> (🥈9 ·  ⭐ 68 · 💀) - A cookiecutter template to create a Django app around a model with CRUD views using django-vanilla-views, a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/edx/cookiecutter-django-app">cookiecutter-django-app</a></b> (🥈9 ·  ⭐ 16 · 💤) - A cookiecutter template for creating reusable Django packages (installable apps) quickly. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mlavin/django-app-template">django-app-template</a></b> (🥉7 ·  ⭐ 54 · 💀) - A handy template for creating a new reusable Django application. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/bitlabstudio/django-reusable-app-template">django-reusable-app-template</a></b> (🥉6 ·  ⭐ 96 · 💀) - A template for kickstarting reusable Django apps, ready to be published on pypi.python.org, ready for test driven.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/AmbitionEng/python-library-template">python-library-template</a></b> (🥉6 ·  ⭐ 5) - The template for all public libraries by Ambition. <code>❗Unlicensed</code>
- <b><a href="https://github.com/AndreGuerra123/django-reusable-app">django-reusable-app</a></b> (🥉4 ·  ⭐ 3 · 💀) - A cookiecutter template to package Django Reusable Apps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/sveetch/cookiecutter-sveetch-djangoapp">cookiecutter-sveetch-djangoapp</a></b> (🥉4 ·  ⭐ 3) - Yet another Cookiecutter template to produce a repository to start a Django application package with Python3. <code>❗Unlicensed</code>
- <b><a href="https://github.com/KryptedGaming/django-package-template">django-package-template</a></b> (🥉4 ·  ⭐ 1 · 💤) - Template for creating packages. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Project templates

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/apptension/saas-boilerplate">saas-boilerplate</a></b> (🥇18 ·  ⭐ 2.4K) - SaaS Boilerplate - Open Source and free SaaS stack that lets you build SaaS products faster in React, Django and AWS... <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/apptension/saas-boilerplate) (👨‍💻 40 · 🔀 290 · 📋 180 - 23% open · ⏱️ 11.12.2024):

	```
	git clone https://github.com/apptension/saas-boilerplate
	```
</details>
<details><summary><b><a href="https://github.com/vintasoftware/django-react-boilerplate">django-react-boilerplate</a></b> (🥇18 ·  ⭐ 2K) - Django 5, React, Bootstrap 5 with Python 3 and Webpack project boilerplate. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vintasoftware/django-react-boilerplate) (👨‍💻 51 · 🔀 490 · 📋 300 - 8% open · ⏱️ 02.08.2024):

	```
	git clone https://github.com/vintasoftware/django-react-boilerplate
	```
</details>
<details><summary><b><a href="https://github.com/falcopackages/falco-cli">falco</a></b> (🥈17 ·  ⭐ 380) - Enhance your Django developer experience: CLI and Guides for the Modern Django Developer. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/falcopackages/falco-cli) (👨‍💻 8 · 🔀 19 · 📦 16 · 📋 66 - 6% open · ⏱️ 31.12.2024):

	```
	git clone https://github.com/Tobi-De/falco
	```
- [PyPi](https://pypi.org/project/falco) (📥 140 / month):
	```
	pip install falco
	```
</details>
<details><summary><b><a href="https://github.com/ilikerobots/cookiecutter-vue-django">cookiecutter-vue-django</a></b> (🥈14 ·  ⭐ 220 · 💤) - Vue 3 + Vite + Django with no compromises. Use Vue SFCs directly in Django Templates, DRF not required. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ilikerobots/cookiecutter-vue-django) (👨‍💻 400 · 🔀 25 · 📋 15 - 26% open · ⏱️ 20.11.2023):

	```
	git clone https://github.com/ilikerobots/cookiecutter-vue-django
	```
</details>
<details><summary><b><a href="https://github.com/gone/django-hydra">django-hydra</a></b> (🥈12 ·  ⭐ 88) - A django/htmx/alpine/tailwind project template. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gone/django-hydra) (👨‍💻 39 · 🔀 9 · 📋 15 - 60% open · ⏱️ 17.12.2024):

	```
	git clone https://github.com/Lightmatter/django-hydra
	```
</details>
<details><summary><b><a href="https://github.com/jayfk/launchr">launchr</a></b> (🥈10 ·  ⭐ 230 · 💤) - Launchr is an open source SaaS starter kit, based on Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jayfk/launchr) (🔀 41 · 📋 25 - 8% open · ⏱️ 23.01.2021):

	```
	git clone https://github.com/jayfk/launchr
	```
</details>
<details><summary><b><a href="https://github.com/jefftriplett/django-startproject">django-startproject</a></b> (🥈10 ·  ⭐ 230) - Django Start Project template with batteries. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jefftriplett/django-startproject) (👨‍💻 3 · 🔀 18 · ⏱️ 09.12.2024):

	```
	git clone https://github.com/jefftriplett/django-startproject
	```
</details>
<details><summary><b><a href="https://github.com/stribny/sidewinder">sidewinder</a></b> (🥈10 ·  ⭐ 200) - Django starter kit that focuses on good defaults, developer experience, and deployment. Updated for Django 5. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stribny/sidewinder) (🔀 13 · 📋 29 - 13% open · ⏱️ 27.04.2024):

	```
	git clone https://github.com/stribny/sidewinder
	```
</details>
<details><summary><b><a href="https://github.com/amerkurev/django-docker-template">django-docker-template</a></b> (🥈10 ·  ⭐ 200) - Dockerized Django with Postgres, Gunicorn, and Traefik or Caddy (with auto renew Lets Encrypt). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amerkurev/django-docker-template) (👨‍💻 6 · 🔀 37 · 📋 12 - 25% open · ⏱️ 25.09.2024):

	```
	git clone https://github.com/amerkurev/django-docker-template
	```
</details>
<details><summary><b><a href="https://github.com/thorgate/django-project-template">django-project-template</a></b> (🥈10 ·  ⭐ 120) - Thorgates Django project template - Django, React, Sass, optional Docker and more. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/thorgate/django-project-template) (👨‍💻 34 · 🔀 16 · 📋 5 - 40% open · ⏱️ 14.05.2024):

	```
	git clone https://github.com/thorgate/django-project-template
	```
</details>
<details><summary><b><a href="https://github.com/khadegd/django-webpack-starter">django-webpack-starter</a></b> (🥉7 ·  ⭐ 59 · 💤) - Django Webpack starter template for using Webpack 5 with Django 3.1 & Bootstrap 4. Yes, it can hot-reload. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/khadegd/django-webpack-starter) (🔀 2 · 📋 3 - 33% open · ⏱️ 05.11.2020):

	```
	git clone https://github.com/khadegd/django-webpack-starter
	```
</details>
<details><summary><b><a href="https://github.com/Alex-CodeLab/django-base-template">django-base-template</a></b> (🥉6 ·  ⭐ 71 · 💤) - Project Template for Django + Bootstrap3 + pre-configured apps (like Allauth, django_compressor ). Probably the.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Alex-CodeLab/django-base-template) (👨‍💻 3 · 🔀 19 · ⏱️ 30.06.2023):

	```
	git clone https://github.com/Alex-CodeLab/django-base-template
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/jpbruinsslot/docker-django">docker-django</a></b> (🥈10 ·  ⭐ 180 · 💀) - A project to get you started with Docker and Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/erayerdin/sos-django-template">sos-django-template</a></b> (🥉9 ·  ⭐ 23 · 💤) - SOS Django Template is a starter template for new Django projects with modern defaults, power cable included. <code><a href="https://tldrlegal.com/search?q=WTFPL">❗️WTFPL</a></code>
- <b><a href="https://github.com/bfirsh/django-docker-heroku-template">django-docker-heroku-template</a></b> (🥉3 ·  ⭐ 36 · 💤) - Get a Django app up and running in dev, test, and production with best practices in 10 minutes. <code>❗Unlicensed</code>
- <b><a href="https://github.com/digipodium/django-bootstrap-htmx-template-2023">django-bootstrap-htmx-template-2023</a></b> ( ⭐ 2 · 💤) - Django Website Template 2023 is a ready-to-use template for building websites using Django, Bootstrap 5, and Htmx. <code>❗Unlicensed</code>
</details>
<br>

## Static file serving

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/evansd/whitenoise">whitenoise</a></b> (🥇33 ·  ⭐ 2.6K) - Radically simplified static file serving for Python web apps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/evansd/whitenoise) (👨‍💻 68 · 🔀 150 · 📦 470K · 📋 240 - 10% open · ⏱️ 07.01.2025):

	```
	git clone https://github.com/evansd/whitenoise
	```
- [PyPi](https://pypi.org/project/whitenoise) (📥 3M / month):
	```
	pip install whitenoise
	```
</details>
<br>

## Custom user

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/fusionbox/django-authtools">django-authtools</a></b> (🥇23 ·  ⭐ 370) - A custom User model for everybody!. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/fusionbox/django-authtools) (👨‍💻 31 · 🔀 95 · 📦 990 · 📋 54 - 16% open · ⏱️ 19.03.2024):

	```
	git clone https://github.com/fusionbox/django-authtools
	```
- [PyPi](https://pypi.org/project/django-authtools) (📥 8.3K / month):
	```
	pip install django-authtools
	```
</details>
<details><summary><b><a href="https://github.com/jambonrose/django-improved-user">django-improved-user</a></b> (🥈19 ·  ⭐ 150) - A custom Django user that authenticates via email. Follows identity and authentication best practices. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jambonrose/django-improved-user) (👨‍💻 8 · 🔀 14 · 📦 44 · ⏱️ 08.08.2024):

	```
	git clone https://github.com/jambonsw/django-improved-user
	```
- [PyPi](https://pypi.org/project/django-improved-user) (📥 1.2K / month):
	```
	pip install django-improved-user
	```
</details>
<details><summary><b><a href="https://github.com/jcugat/django-custom-user">django-custom-user</a></b> (🥉18 ·  ⭐ 320 · 💤) - Custom user model for Django with the same behaviour as the default User class but with email instead of username. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jcugat/django-custom-user) (👨‍💻 12 · 🔀 60 · 📦 280 · 📋 24 - 4% open · ⏱️ 09.12.2022):

	```
	git clone https://github.com/jcugat/django-custom-user
	```
- [PyPi](https://pypi.org/project/django-custom-user) (📥 6.6K / month):
	```
	pip install django-custom-user
	```
</details>
<details><summary><b><a href="https://github.com/jmfederico/django-use-email-as-username">django-use-email-as-username</a></b> (🥉15 ·  ⭐ 71) - A Django app to use email as username for user authentication. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jmfederico/django-use-email-as-username) (👨‍💻 3 · 🔀 11 · 📦 290 · ⏱️ 09.09.2024):

	```
	git clone https://github.com/jmfederico/django-use-email-as-username
	```
- [PyPi](https://pypi.org/project/django-use-email-as-username) (📥 2.6K / month):
	```
	pip install django-use-email-as-username
	```
</details>
<details><summary><b><a href="https://github.com/carltongibson/django-unique-user-email">django-unique-user-email</a></b> (🥉12 ·  ⭐ 140) - Enable login-by-email with the default User model for your Django project by making auth.User.email unique. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carltongibson/django-unique-user-email) (👨‍💻 4 · 🔀 6 · 📦 15 · 📋 10 - 60% open · ⏱️ 09.10.2024):

	```
	git clone https://github.com/carltongibson/django-unique-user-email
	```
- [PyPi](https://pypi.org/project/django-unique-user-email) (📥 2K / month):
	```
	pip install django-unique-user-email
	```
</details>

---

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/fkromer/best-of-django/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/fkromer/best-of-django/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/fkromer/best-of-django/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/fkromer/best-of-django/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/fkromer/best-of-django/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
