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
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-300-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/fkromer/best-of-django/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/fkromer/best-of-django?color=green&label=updated"></a>
</p>

This curated list contains 300 awesome open-source projects with a total of 740K stars grouped into 74 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/fkromer/best-of-django/issues/new/choose), submit a [pull request](https://github.com/fkromer/best-of-django/pulls), or directly edit the [projects.yaml](https://github.com/fkromer/best-of-django/edit/main/projects.yaml). Contributions are very welcome!

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Admin Interface](#admin-interface) _8 projects_
- [Admin Interface Actions](#admin-interface-actions) _4 projects_
- [Admin Interface Filters](#admin-interface-filters) _1 projects_
- [Management Commands](#management-commands) _5 projects_
- [Caching](#caching) _2 projects_
- [Configuration](#configuration) _6 projects_
- [Dependency Injection](#dependency-injection) _18 projects_
- [Debugging](#debugging) _1 projects_
- [Development](#development) _4 projects_
- [Kubernetes CI/CD](#kubernetes-cicd) _1 projects_
- [Kubernetes CI/CD SaaS](#kubernetes-cicd-saas) _2 projects_
- [Type stubs](#type-stubs) _2 projects_
- [Logging](#logging) _5 projects_
- [Application Monitoring (Platforms)](#application-monitoring-platforms) _4 projects_
- [Application Monitoring SaaS](#application-monitoring-saas) _9 projects_
- [Authentication and Authorization](#authentication-and-authorization) _17 projects_
- [Authorization](#authorization) _1 projects_
- [Task Queues](#task-queues) _6 projects_
- [Finite State Machine](#finite-state-machine) _7 projects_
- [RESTful API (Django Rest Framework)](#restful-api-django-rest-framework) _5 projects_
- [RESTful API (Django Ninja)](#restful-api-django-ninja) _6 projects_
- [Pydantic integration](#pydantic-integration) _4 projects_
- [Pandas integration](#pandas-integration) _1 projects_
- [GraphQL API](#graphql-api) _8 projects_
- [Feature Flipper](#feature-flipper) _1 projects_
- [Statistics](#statistics) _1 projects_
- [Testing](#testing) _5 projects_
- [Architecture Testing](#architecture-testing) _4 projects_
- [Static Code Analysis](#static-code-analysis) _2 projects_
- [Vulnerability databases based on Django](#vulnerability-databases-based-on-django) _1 projects_
- [CMS frameworks based on Django](#cms-frameworks-based-on-django) _3 projects_
- [E-Commerce frameworks based on Django](#e-commerce-frameworks-based-on-django) _4 projects_
- [Analytics frameworks based on Django](#analytics-frameworks-based-on-django) _1 projects_
- [Project management frameworks based on Django](#project-management-frameworks-based-on-django) _2 projects_
- [Monitoring frameworks based on Django](#monitoring-frameworks-based-on-django) _1 projects_
- [Security frameworks based on Django](#security-frameworks-based-on-django) _3 projects_
- [Governance, Risk and Compliance frameworks based on Django](#governance-risk-and-compliance-frameworks-based-on-django) _1 projects_
- [Privileged Access Management frameworks based on Django](#privileged-access-management-frameworks-based-on-django) _1 projects_
- [Photo management frameworks based on Django](#photo-management-frameworks-based-on-django) _1 projects_
- [Recipe management frameworks based on Django](#recipe-management-frameworks-based-on-django) _1 projects_
- [Document management frameworks based on Django](#document-management-frameworks-based-on-django) _1 projects_
- [Education frameworks based on Django](#education-frameworks-based-on-django) _1 projects_
- [Inventory management system based on Django](#inventory-management-system-based-on-django) _1 projects_
- [Crawler management system based on Django](#crawler-management-system-based-on-django) _1 projects_
- [Network automation system based on Django](#network-automation-system-based-on-django) _1 projects_
- [Test automation systems based on Django](#test-automation-systems-based-on-django) _5 projects_
- [Fields (encrypted)](#fields-encrypted) _6 projects_
- [Fields (phone numbers)](#fields-phone-numbers) _2 projects_
- [Fields (addresses)](#fields-addresses) _5 projects_
- [Fields (versioning)](#fields-versioning) _7 projects_
- [Messaging](#messaging) _5 projects_
- [Storage](#storage) _3 projects_
- [Event Bus](#event-bus) _1 projects_
- [Event Sourcing](#event-sourcing) _5 projects_
- [Event Streaming](#event-streaming) _1 projects_
- [Locking](#locking) _3 projects_
- [Example data](#example-data) _4 projects_
- [Fake data](#fake-data) _2 projects_
- [Bootstrap CSS Framework Integration (Django MVT application)](#bootstrap-css-framework-integration-django-mvt-application) _4 projects_
- [Bulma CSS Framework Integration (Django MVT application)](#bulma-css-framework-integration-django-mvt-application) _1 projects_
- [TailwindCSS CSS Framework Integration (Django MVT application)](#tailwindcss-css-framework-integration-django-mvt-application) _3 projects_
- [Data exploration](#data-exploration) _1 projects_
- [Multiple tenants](#multiple-tenants) _4 projects_
- [Notifications](#notifications) _1 projects_
- [Value-as-a-Service frameworks based on Django](#value-as-a-service-frameworks-based-on-django) _1 projects_
- [Payment and Subscription (Stripe, etc.)](#payment-and-subscription-stripe-etc) _19 projects_
- [Emails](#emails) _5 projects_
- [Templates](#templates) _6 projects_
- [Reusable app templates](#reusable-app-templates) _11 projects_
- [Project templates](#project-templates) _18 projects_
- [Static file serving](#static-file-serving) _1 projects_
- [Custom user](#custom-user) _5 projects_
- [MQTT](#mqtt) _1 projects_
- [HTTP server](#http-server) _1 projects_
- [Others](#others) _1 projects_

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

<details><summary><b><a href="https://github.com/fabiocaccamo/django-admin-interface">django-admin-interface</a></b> (🥇33 ·  ⭐ 2K) - djangos default admin interface with superpowers - customizable themes, popup windows replaced by modals and many.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fabiocaccamo/django-admin-interface) (👨‍💻 41 · 🔀 180 · 📦 5.2K · 📋 220 - 5% open · ⏱️ 10.11.2025):

	```
	git clone https://github.com/fabiocaccamo/django-admin-interface
	```
- [PyPi](https://pypi.org/project/django-admin-interface) (📥 190K / month):
	```
	pip install django-admin-interface
	```
</details>
<details><summary><b><a href="https://github.com/farridav/django-jazzmin">django-jazzmin</a></b> (🥇33 ·  ⭐ 1.8K) - Jazzy theme for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/farridav/django-jazzmin) (👨‍💻 76 · 🔀 300 · 📦 18K · 📋 300 - 43% open · ⏱️ 11.01.2025):

	```
	git clone https://github.com/farridav/django-jazzmin
	```
- [PyPi](https://pypi.org/project/django-jazzmin) (📥 450K / month):
	```
	pip install django-jazzmin
	```
</details>
<details><summary><b><a href="https://github.com/sehmaschine/django-grappelli">django-grappelli</a></b> (🥈28 ·  ⭐ 3.9K) - A jazzy skin for the Django Admin-Interface (official repository). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sehmaschine/django-grappelli) (👨‍💻 91 · 🔀 640 · 📦 6.9K · 📋 740 - 1% open · ⏱️ 27.11.2025):

	```
	git clone https://github.com/sehmaschine/django-grappelli
	```
- [PyPi](https://pypi.org/project/django-grappelli) (📥 290K / month):
	```
	pip install django-grappelli
	```
</details>
<details><summary><b><a href="https://github.com/viewflow/django-material">django-material</a></b> (🥉27 ·  ⭐ 2.5K) - Material Design for Django. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/viewflow/django-material) (👨‍💻 4 · 🔀 410 · 📦 1.9K · 📋 420 - 4% open · ⏱️ 30.06.2025):

	```
	git clone https://github.com/viewflow/django-material
	```
- [PyPi](https://pypi.org/project/django-material) (📥 17K / month):
	```
	pip install django-material
	```
</details>
<details><summary><b><a href="https://github.com/geex-arts/django-jet">django-jet</a></b> (🥉26 ·  ⭐ 3.6K) - Modern responsive template for the Django admin interface with improved functionality. We are proud to announce.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/geex-arts/django-jet) (👨‍💻 29 · 🔀 670 · 📦 3.4K · 📋 350 - 61% open · ⏱️ 26.11.2025):

	```
	git clone https://github.com/geex-arts/django-jet
	```
- [PyPi](https://pypi.org/project/django-jet) (📥 13K / month):
	```
	pip install django-jet
	```
</details>
<details><summary><b><a href="https://github.com/otto-torino/django-baton">django-baton</a></b> (🥉26 ·  ⭐ 980) - A cool, modern and responsive django admin application based on bootstrap 5 that brings AI to the Django admin -.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/otto-torino/django-baton) (👨‍💻 18 · 🔀 98 · 📦 470 · 📋 190 - 0% open · ⏱️ 03.11.2025):

	```
	git clone https://github.com/otto-torino/django-baton
	```
- [PyPi](https://pypi.org/project/django-baton) (📥 11K / month):
	```
	pip install django-baton
	```
</details>
<details><summary><b><a href="https://github.com/django-admin-tools/django-admin-tools">django-admin-tools</a></b> (🥉24 ·  ⭐ 890 · 💤) - Extends the Django Admin to include a extensible dashboard and navigation menu. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-admin-tools/django-admin-tools) (👨‍💻 82 · 🔀 110 · 📦 1.6K · 📋 80 - 23% open · ⏱️ 10.08.2023):

	```
	git clone https://github.com/django-admin-tools/django-admin-tools
	```
- [PyPi](https://pypi.org/project/django-admin-tools) (📥 120K / month):
	```
	pip install django-admin-tools
	```
</details>
<details><summary><b><a href="https://github.com/byashimov/django-controlcenter">django-controlcenter</a></b> (🥉20 ·  ⭐ 1K) - Set of widgets to build dashboards for Django projects. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/byashimov/django-controlcenter) (👨‍💻 19 · 🔀 82 · 📦 93 · 📋 34 - 29% open · ⏱️ 25.03.2025):

	```
	git clone https://github.com/byashimov/django-controlcenter
	```
- [PyPi](https://pypi.org/project/django-controlcenter) (📥 9K / month):
	```
	pip install django-controlcenter
	```
</details>
<br>

## Admin Interface Actions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-import-export/django-import-export">django-import-export</a></b> (🥇40 ·  ⭐ 3.3K) - Django application and library for importing and exporting data with admin integration. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/django-import-export/django-import-export) (👨‍💻 240 · 🔀 780 · 📦 130K · 📋 1.1K - 2% open · ⏱️ 20.11.2025):

	```
	git clone https://github.com/django-import-export/django-import-export
	```
- [PyPi](https://pypi.org/project/django-import-export) (📥 2.2M / month):
	```
	pip install django-import-export
	```
</details>
<details><summary><b><a href="https://github.com/jrief/django-admin-sortable2">django-admin-sortable2</a></b> (🥈28 ·  ⭐ 860) - Generic drag-and-drop ordering for objects in the Django admin interface. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jrief/django-admin-sortable2) (👨‍💻 90 · 🔀 180 · 📦 2.9K · 📋 240 - 17% open · ⏱️ 26.11.2025):

	```
	git clone https://github.com/jrief/django-admin-sortable2
	```
- [PyPi](https://pypi.org/project/django-admin-sortable2) (📥 860K / month):
	```
	pip install django-admin-sortable2
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-admin-sortable">django-admin-sortable</a></b> (🥉19 ·  ⭐ 570 · 💤) - Generic drag-and-drop ordering for objects and tabular inlines in Django Admin. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jazzband/django-admin-sortable) (👨‍💻 81 · 🔀 130 · 📦 750 · 📋 140 - 7% open · ⏱️ 13.03.2022):

	```
	git clone https://github.com/jazzband/django-admin-sortable
	```
- [PyPi](https://pypi.org/project/django-admin-sortable) (📥 44K / month):
	```
	pip install django-admin-sortable
	```
</details>
<details><summary><b><a href="https://github.com/TrangPham/django-admin-confirm">django-admin-confirm</a></b> (🥉13 ·  ⭐ 140) - AdminConfirmMixin is a mixin for ModelAdmin that adds confirmations to changes, additions and actions. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/TrangPham/django-admin-confirm) (👨‍💻 10 · 🔀 17 · 📥 5 · 📋 36 - 33% open · ⏱️ 06.05.2025):

	```
	git clone https://github.com/trangpham/django-admin-confirm
	```
- [PyPi](https://pypi.org/project/django-admin-confirm) (📥 31K / month):
	```
	pip install django-admin-confirm
	```
</details>
<br>

## Admin Interface Filters

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/lukasvinclav/django-admin-numeric-filter">django-admin-numeric-filter</a></b> (🥇19 ·  ⭐ 80 · 💤) - Numeric filters for Django admin. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lukasvinclav/django-admin-numeric-filter) (👨‍💻 14 · 🔀 35 · 📦 210 · 📋 19 - 26% open · ⏱️ 16.02.2023):

	```
	git clone https://github.com/lukasvinclav/django-admin-numeric-filter
	```
- [PyPi](https://pypi.org/project/django-admin-numeric-filter) (📥 18K / month):
	```
	pip install django-admin-numeric-filter
	```
</details>
<br>

## Management Commands

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which add or help working with management commands._

<details><summary><b><a href="https://github.com/django-extensions/django-extensions">django-extensions</a></b> (🥇37 ·  ⭐ 6.8K) - This is a repository for collecting global custom management extensions for the Django Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-extensions/django-extensions) (👨‍💻 600 · 🔀 1.1K · 📦 270K · 📋 930 - 18% open · ⏱️ 03.10.2025):

	```
	git clone https://github.com/django-extensions/django-extensions
	```
- [PyPi](https://pypi.org/project/django-extensions) (📥 8.2M / month):
	```
	pip install django-extensions
	```
</details>
<details><summary><b><a href="https://github.com/Archmonger/django-dbbackup">django-dbbackup</a></b> (🥈28 ·  ⭐ 1.1K · 📉) - Backup and restore your Django database and media. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Archmonger/django-dbbackup) (👨‍💻 81 · 🔀 200 · 📥 9 · 📦 2.6K · 📋 310 - 2% open · ⏱️ 07.11.2025):

	```
	git clone https://github.com/jazzband/django-dbbackup
	```
- [PyPi](https://pypi.org/project/django-dbbackup) (📥 200K / month):
	```
	pip install django-dbbackup
	```
</details>
<details><summary><b><a href="https://github.com/django-commons/django-typer">django-typer</a></b> (🥉26 ·  ⭐ 240) - Use Typer (type hints) to define the interface for your Django management commands. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-commons/django-typer) (👨‍💻 8 · 🔀 4 · 📥 13 · 📦 74 · 📋 160 - 10% open · ⏱️ 21.11.2025):

	```
	git clone https://github.com/bckohan/django-typer
	```
- [PyPi](https://pypi.org/project/django-typer) (📥 65K / month):
	```
	pip install django-typer
	```
</details>
<details><summary><b><a href="https://github.com/django-commons/django-click">django-click</a></b> (🥉24 ·  ⭐ 290 · 📈) - Write Django management command using the click CLI library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-commons/django-click) (👨‍💻 13 · 🔀 21 · 📦 360 · 📋 20 - 50% open · ⏱️ 10.11.2025):

	```
	git clone https://github.com/GaretJax/django-click
	```
- [PyPi](https://pypi.org/project/django-click) (📥 65K / month):
	```
	pip install django-click
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/django-rich">django-rich</a></b> (🥉20 ·  ⭐ 150) - Extensions for using Rich with Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/adamchainz/django-rich) (👨‍💻 6 · 🔀 12 · 📦 200 · 📋 13 - 23% open · ⏱️ 17.11.2025):

	```
	git clone https://github.com/adamchainz/django-rich
	```
- [PyPi](https://pypi.org/project/django-rich) (📥 130K / month):
	```
	pip install django-rich
	```
</details>
<br>

## Caching

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/Suor/django-cacheops">django-cacheops</a></b> (🥇29 ·  ⭐ 2.3K) - A slick ORM cache with automatic granular event-driven invalidation. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Suor/django-cacheops) (👨‍💻 72 · 🔀 220 · 📦 1.6K · 📋 350 - 5% open · ⏱️ 15.10.2025):

	```
	git clone https://github.com/Suor/django-cacheops
	```
- [PyPi](https://pypi.org/project/django-cacheops) (📥 350K / month):
	```
	pip install django-cacheops
	```
</details>
<details><summary><b><a href="https://github.com/noripyt/django-cachalot">django-cachalot</a></b> (🥉28 ·  ⭐ 1.4K) - No effort, no worry, maximum performance. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/noripyt/django-cachalot) (👨‍💻 39 · 🔀 150 · 📦 1K · 📋 170 - 17% open · ⏱️ 17.04.2025):

	```
	git clone https://github.com/noripyt/django-cachalot
	```
- [PyPi](https://pypi.org/project/django-cachalot) (📥 140K / month):
	```
	pip install django-cachalot
	```
</details>
<br>

## Configuration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/joke2k/django-environ">django-environ</a></b> (🥇34 ·  ⭐ 3.1K) - Django-environ allows you to utilize 12factor inspired environment variables to configure your Django application. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joke2k/django-environ) (👨‍💻 97 · 🔀 320 · 📥 160 · 📦 280K · 📋 260 - 27% open · ⏱️ 13.01.2025):

	```
	git clone https://github.com/joke2k/django-environ
	```
- [PyPi](https://pypi.org/project/django-environ) (📥 4.2M / month):
	```
	pip install django-environ
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-constance">django-constance</a></b> (🥇34 ·  ⭐ 1.8K) - Dynamic Django settings. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-constance) (👨‍💻 160 · 🔀 300 · 📦 2.4K · 📋 320 - 7% open · ⏱️ 24.11.2025):

	```
	git clone https://github.com/jazzband/django-constance
	```
- [PyPi](https://pypi.org/project/django-constance) (📥 620K / month):
	```
	pip install django-constance
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/dj-database-url">dj-database-url</a></b> (🥇34 ·  ⭐ 1.5K) - Use Database URLs in your Django Application. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/dj-database-url) (👨‍💻 73 · 🔀 200 · 📦 310K · 📋 100 - 4% open · ⏱️ 22.09.2025):

	```
	git clone https://github.com/jazzband/dj-database-url
	```
- [PyPi](https://pypi.org/project/dj-database-url) (📥 4M / month):
	```
	pip install dj-database-url
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-configurations">django-configurations</a></b> (🥉27 ·  ⭐ 1.1K · 💤) - A helper for organizing Django project settings by relying on well established programming patterns. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-configurations) (👨‍💻 74 · 🔀 140 · 📦 3.4K · 📋 210 - 26% open · ⏱️ 18.11.2024):

	```
	git clone https://github.com/jazzband/django-configurations
	```
- [PyPi](https://pypi.org/project/django-configurations) (📥 380K / month):
	```
	pip install django-configurations
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/django-split-settings">django-split-settings</a></b> (🥉26 ·  ⭐ 1.2K) - Organize Django settings into multiple files and directories. Easily override and modify settings. Use wildcards and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wemake-services/django-split-settings) (👨‍💻 28 · 🔀 71 · 📦 3.5K · 📋 48 - 10% open · ⏱️ 21.11.2025):

	```
	git clone https://github.com/wemake-services/django-split-settings
	```
- [PyPi](https://pypi.org/project/django-split-settings) (📥 230K / month):
	```
	pip install django-split-settings
	```
</details>
<details><summary><b><a href="https://github.com/fabiocaccamo/django-extra-settings">django-extra-settings</a></b> (🥉23 ·  ⭐ 610) - config and manage typed extra settings using just the django admin. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fabiocaccamo/django-extra-settings) (👨‍💻 13 · 🔀 32 · 📦 110 · 📋 41 - 12% open · ⏱️ 30.09.2025):

	```
	git clone https://github.com/fabiocaccamo/django-extra-settings
	```
- [PyPi](https://pypi.org/project/django-extra-settings) (📥 35K / month):
	```
	pip install django-extra-settings
	```
</details>
<br>

## Dependency Injection

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/ets-labs/python-dependency-injector">Dependency Injector</a></b> (🥇35 ·  ⭐ 4.7K) - Dependency injection framework for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ets-labs/python-dependency-injector) (👨‍💻 39 · 🔀 330 · 📦 5.3K · 📋 630 - 31% open · ⏱️ 19.09.2025):

	```
	git clone https://github.com/ets-labs/python-dependency-injector
	```
- [PyPi](https://pypi.org/project/dependency-injector) (📥 3.4M / month):
	```
	pip install dependency-injector
	```
</details>
<details><summary><b><a href="https://github.com/python-injector/injector">injector</a></b> (🥇29 ·  ⭐ 1.5K · 📈) - Python dependency injection framework, inspired by Guice. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/python-injector/injector) (👨‍💻 34 · 🔀 93 · 📦 3K · 📋 150 - 29% open · ⏱️ 28.11.2025):

	```
	git clone https://github.com/python-injector/injector
	```
- [PyPi](https://pypi.org/project/injector) (📥 2.7M / month):
	```
	pip install injector
	```
</details>
<details><summary><b><a href="https://github.com/reagento/dishka">dishka</a></b> (🥇29 ·  ⭐ 940) - Cute dependency injection (DI) framework for Python with agreeable API and everything you need. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/reagento/dishka) (👨‍💻 70 · 🔀 96 · 📦 670 · 📋 170 - 26% open · ⏱️ 30.11.2025):

	```
	git clone https://github.com/reagento/dishka
	```
- [PyPi](https://pypi.org/project/dishka) (📥 310K / month):
	```
	pip install dishka
	```
</details>
<details><summary><b><a href="https://github.com/Lancetnik/FastDepends">FastDepends</a></b> (🥈27 ·  ⭐ 470) - FastDepends - FastAPI Dependency Injection system extracted from FastAPI and cleared of all HTTP logic. Async and sync.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Lancetnik/FastDepends) (👨‍💻 20 · 🔀 33 · 📦 680 · 📋 45 - 22% open · ⏱️ 30.11.2025):

	```
	git clone https://github.com/lancetnik/FastDepends
	```
- [PyPi](https://pypi.org/project/fast-depends) (📥 670K / month):
	```
	pip install fast-depends
	```
</details>
<details><summary><b><a href="https://github.com/hynek/svcs">svcs</a></b> (🥈26 ·  ⭐ 390) - A Flexible Service Locator for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hynek/svcs) (👨‍💻 10 · 🔀 22 · 📦 320 · 📋 21 - 4% open · ⏱️ 03.11.2025):

	```
	git clone https://github.com/hynek/svcs
	```
- [PyPi](https://pypi.org/project/svcs) (📥 4.9M / month):
	```
	pip install svcs
	```
</details>
<details><summary><b><a href="https://github.com/ivankorobkov/python-inject">python-inject</a></b> (🥈24 ·  ⭐ 750) - Python dependency injection. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ivankorobkov/python-inject) (👨‍💻 35 · 🔀 81 · 📦 950 · 📋 72 - 33% open · ⏱️ 10.11.2025):

	```
	git clone https://github.com/ivankorobkov/python-inject
	```
- [PyPi](https://pypi.org/project/inject) (📥 800K / month):
	```
	pip install inject
	```
</details>
<details><summary><b><a href="https://github.com/meadsteve/lagom">lagom</a></b> (🥈23 ·  ⭐ 340) - Autowiring dependency injection container for python 3. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/meadsteve/lagom) (👨‍💻 13 · 🔀 20 · 📦 480 · 📋 140 - 19% open · ⏱️ 28.07.2025):

	```
	git clone https://github.com/meadsteve/lagom
	```
- [PyPi](https://pypi.org/project/lagom) (📥 220K / month):
	```
	pip install lagom
	```
</details>
<details><summary><b><a href="https://github.com/kodemore/kink">kink</a></b> (🥉22 ·  ⭐ 440) - Dependency injection container made for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kodemore/kink) (👨‍💻 15 · 🔀 28 · 📦 270 · 📋 28 - 25% open · ⏱️ 18.10.2025):

	```
	git clone https://github.com/kodemore/kink
	```
- [PyPi](https://pypi.org/project/kink) (📥 130K / month):
	```
	pip install kink
	```
</details>
<details><summary><b><a href="https://github.com/maldoinc/wireup">wireup</a></b> (🥉22 ·  ⭐ 330) - Performant, concise, and easy-to-use dependency injection container for Python 3.8+. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maldoinc/wireup) (👨‍💻 10 · 🔀 17 · 📦 25 · 📋 62 - 22% open · ⏱️ 12.11.2025):

	```
	git clone https://github.com/maldoinc/wireup
	```
- [PyPi](https://pypi.org/project/wireup) (📥 22K / month):
	```
	pip install wireup
	```
</details>
<details><summary><b><a href="https://github.com/modern-python/that-depends">that-depends</a></b> (🥉22 ·  ⭐ 230) - Simple Dependency injection framework for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/modern-python/that-depends) (👨‍💻 15 · 🔀 14 · 📥 230 · 📦 16 · 📋 75 - 5% open · ⏱️ 17.11.2025):

	```
	git clone https://github.com/modern-python/that-depends
	```
- [PyPi](https://pypi.org/project/that-depends) (📥 24K / month):
	```
	pip install that-depends
	```
</details>
<details><summary><b><a href="https://github.com/bobthemighty/punq">punq</a></b> (🥉21 ·  ⭐ 410) - An IoC container for Python 3.8+. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bobthemighty/punq) (👨‍💻 12 · 🔀 18 · 📦 390 · 📋 47 - 31% open · ⏱️ 06.08.2025):

	```
	git clone https://github.com/bobthemighty/punq
	```
- [PyPi](https://pypi.org/project/punq) (📥 80K / month):
	```
	pip install punq
	```
</details>
<details><summary><b><a href="https://github.com/adriangb/di">di</a></b> (🥉20 ·  ⭐ 330 · 💤) - Pythonic dependency injection. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/adriangb/di) (👨‍💻 9 · 🔀 14 · 📦 170 · 📋 49 - 18% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/adriangb/di
	```
- [PyPi](https://pypi.org/project/di) (📥 44K / month):
	```
	pip install di
	```
</details>
<details><summary><b><a href="https://github.com/Neoteroi/rodi">rodi</a></b> (🥉20 ·  ⭐ 230) - Implementation of dependency injection for Python 3. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Neoteroi/rodi) (👨‍💻 10 · 🔀 17 · 📦 310 · 📋 22 - 18% open · ⏱️ 12.04.2025):

	```
	git clone https://github.com/Neoteroi/rodi
	```
- [PyPi](https://pypi.org/project/rodi) (📥 57K / month):
	```
	pip install rodi
	```
</details>
<details><summary><b><a href="https://github.com/illuin-tech/opyoid">opyoid</a></b> (🥉18 ·  ⭐ 75) - Dependency injection library for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/illuin-tech/opyoid) (👨‍💻 6 · 🔀 6 · 📦 30 · ⏱️ 25.11.2025):

	```
	git clone https://github.com/illuin-tech/opyoid
	```
- [PyPi](https://pypi.org/project/opyoid) (📥 4.7K / month):
	```
	pip install opyoid
	```
</details>
<details><summary><b><a href="https://github.com/modern-python/modern-di">modern-di</a></b> (🥉18 ·  ⭐ 43) - Powerful DI-framework with scopes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/modern-python/modern-di) (👨‍💻 6 · 🔀 4 · 📦 5 · 📋 35 - 8% open · ⏱️ 28.11.2025):

	```
	git clone https://github.com/modern-python/modern-di
	```
- [PyPi](https://pypi.org/project/modern-di) (📥 3.2K / month):
	```
	pip install modern-di
	```
</details>
<details><summary><b><a href="https://github.com/roo-oliv/injectable">injectable</a></b> (🥉16 ·  ⭐ 120 · 💤) - Python Dependency Injection for Humans. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/roo-oliv/injectable) (👨‍💻 6 · 🔀 12 · 📦 32 · 📋 21 - 23% open · ⏱️ 05.08.2024):

	```
	git clone https://github.com/roo-oliv/injectable
	```
- [PyPi](https://pypi.org/project/injectable) (📥 3.9K / month):
	```
	pip install injectable
	```
</details>
<details><summary><b><a href="https://github.com/blubber/django_injector">django_injector</a></b> (🥉10 ·  ⭐ 55 · 💤) - Dependency injection in Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/blubber/django_injector) (👨‍💻 7 · 🔀 7 · ⏱️ 09.04.2024):

	```
	git clone https://github.com/blubber/django_injector
	```
- [PyPi](https://pypi.org/project/django_injector) (📥 2.9K / month):
	```
	pip install django_injector
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/django-svcs/django-svcs">django-svc</a></b> (🥉7 ·  ⭐ 12) - A Django integration for SVCS. <code>❗Unlicensed</code>
</details>
<br>

## Debugging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-commons/django-debug-toolbar">django-debug-toolbar</a></b> (🥇41 ·  ⭐ 8.3K) - A configurable set of panels that display various debug information about the current request/response. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-commons/django-debug-toolbar) (👨‍💻 320 · 🔀 960 · 📥 330 · 📦 110K · 📋 990 - 6% open · ⏱️ 27.11.2025):

	```
	git clone https://github.com/jazzband/django-debug-toolbar
	```
- [PyPi](https://pypi.org/project/django-debug-toolbar) (📥 5.6M / month):
	```
	pip install django-debug-toolbar
	```
</details>
<br>

## Development

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/tach-org/tach">tach</a></b> (🥇30 ·  ⭐ 2.6K · 📈) - A Python tool to visualize + enforce dependencies, using modular architecture Open source Installable via pip Able to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tach-org/tach) (👨‍💻 22 · 🔀 73 · 📦 79 · 📋 150 - 22% open · ⏱️ 29.11.2025):

	```
	git clone https://github.com/gauge-sh/tach
	```
- [PyPi](https://pypi.org/project/tach) (📥 970K / month):
	```
	pip install tach
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/django-browser-reload">django-browser-reload</a></b> (🥈25 ·  ⭐ 640) - Automatically reload your browser in development. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/adamchainz/django-browser-reload) (👨‍💻 7 · 🔀 34 · 📦 6.8K · 📋 43 - 32% open · ⏱️ 17.11.2025):

	```
	git clone https://github.com/adamchainz/django-browser-reload
	```
- [PyPi](https://pypi.org/project/django-browser-reload) (📥 260K / month):
	```
	pip install django-browser-reload
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/django-harlequin">django-harlequin</a></b> (🥉13 ·  ⭐ 82) - Launch Harlequin, the SQL IDE for your Terminal, with your Django database configuration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/adamchainz/django-harlequin) (👨‍💻 5 · 🔀 4 · 📦 8 · ⏱️ 17.11.2025):

	```
	git clone https://github.com/adamchainz/django-harlequin
	```
- [PyPi](https://pypi.org/project/django-harlequin) (📥 2.1K / month):
	```
	pip install django-harlequin
	```
</details>
<details><summary><b><a href="https://github.com/boxed/django-fastdev">django-fastdev</a></b> (🥉12 ·  ⭐ 200) - An app to make it safer, faster and more fun to develop in Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/boxed/django-fastdev) (👨‍💻 11 · 🔀 15 · 📋 34 - 47% open · ⏱️ 15.05.2025):

	```
	git clone https://github.com/boxed/django-fastdev
	```
- [PyPi](https://pypi.org/project/django-fastdev) (📥 6.8K / month):
	```
	pip install django-fastdev
	```
</details>
<br>

## Kubernetes CI/CD

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/garden-io/garden">Garden</a></b> (🥇31 ·  ⭐ 3.5K) - Automation for Kubernetes development and testing. Spin up production-like environments for development, testing, and.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/garden-io/garden) (👨‍💻 120 · 🔀 290 · 📥 4.2M · 📦 3 · 📋 1.7K - 12% open · ⏱️ 28.11.2025):

	```
	git clone https://github.com/garden-io/garden
	```
</details>
<br>

## Kubernetes CI/CD SaaS

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://codefresh.io/">Codefresh GitOps Platform</a></b>  

🔗&nbsp;<b><a href="https://app.garden.io/login">Garden Cloud</a></b>  

<br>

## Type stubs

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/typeddjango/django-stubs">django-stubs</a></b> (🥇37 ·  ⭐ 1.8K) - PEP-484 stubs for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/typeddjango/django-stubs) (👨‍💻 320 · 🔀 430 · 📦 14K · 📋 840 - 21% open · ⏱️ 29.11.2025):

	```
	git clone https://github.com/typeddjango/django-stubs
	```
- [PyPi](https://pypi.org/project/django-stubs) (📥 4.2M / month):
	```
	pip install django-stubs
	```
</details>
<details><summary><b><a href="https://github.com/typeddjango/djangorestframework-stubs">djangorestframework-stubs</a></b> (🥉31 ·  ⭐ 520) - PEP-484 stubs for django-rest-framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/typeddjango/djangorestframework-stubs) (👨‍💻 88 · 🔀 120 · 📦 3.9K · 📋 160 - 33% open · ⏱️ 29.11.2025):

	```
	git clone https://github.com/typeddjango/djangorestframework-stubs
	```
- [PyPi](https://pypi.org/project/djangorestframework-stubs) (📥 2.3M / month):
	```
	pip install djangorestframework-stubs
	```
</details>
<br>

## Logging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which improve logging and debugging._

<details><summary><b><a href="https://github.com/Delgan/loguru">loguru</a></b> (🥇38 ·  ⭐ 23K) - Python logging made (stupidly) simple. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Delgan/loguru) (👨‍💻 69 · 🔀 750 · 📦 140K · 📋 1.1K - 20% open · ⏱️ 08.11.2025):

	```
	git clone https://github.com/Delgan/loguru
	```
- [PyPi](https://pypi.org/project/loguru) (📥 46M / month):
	```
	pip install loguru
	```
</details>
<details><summary><b><a href="https://github.com/hynek/structlog">structlog</a></b> (🥈37 ·  ⭐ 4.4K) - Simple, powerful, and fast logging for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/hynek/structlog) (👨‍💻 140 · 🔀 260 · 📦 27K · 📋 380 - 8% open · ⏱️ 03.11.2025):

	```
	git clone https://github.com/hynek/structlog
	```
- [PyPi](https://pypi.org/project/structlog) (📥 39M / month):
	```
	pip install structlog
	```
</details>
<details><summary><b><a href="https://github.com/jrobichaud/django-structlog">django-structlog</a></b> (🥉28 ·  ⭐ 500) - Structured Logging for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jrobichaud/django-structlog) (👨‍💻 25 · 🔀 38 · 📦 980 · 📋 73 - 1% open · ⏱️ 24.11.2025):

	```
	git clone https://github.com/jrobichaud/django-structlog
	```
- [PyPi](https://pypi.org/project/django-structlog) (📥 1.4M / month):
	```
	pip install django-structlog
	```
</details>
<details><summary><b><a href="https://github.com/snok/django-guid">django-guid</a></b> (🥉25 ·  ⭐ 480) - Inject an ID into every log message from a Django request. ASGI compatible, integrates with Sentry, and works with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snok/django-guid) (👨‍💻 15 · 🔀 28 · 📦 310 · 📋 31 - 16% open · ⏱️ 22.07.2025):

	```
	git clone https://github.com/snok/django-guid
	```
- [PyPi](https://pypi.org/project/django-guid) (📥 160K / month):
	```
	pip install django-guid
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/tarsil/django-loguru">django-loguru</a></b> (🥉8 ·  ⭐ 11 · 💤) - A middleware to log the requests and responses using loguru. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Application Monitoring (Platforms)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pydantic/logfire">logfire</a></b> (🥇36 ·  ⭐ 3.8K) - Uncomplicated Observability for Python and beyond!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydantic/logfire) (👨‍💻 75 · 🔀 180 · 📦 1.9K · 📋 490 - 30% open · ⏱️ 27.11.2025):

	```
	git clone https://github.com/pydantic/logfire
	```
- [PyPi](https://pypi.org/project/logfire) (📥 3.8M / month):
	```
	pip install logfire
	```
</details>
<details><summary><b><a href="https://github.com/django-commons/django-prometheus">django-prometheus</a></b> (🥈31 ·  ⭐ 1.6K) - Export Django monitoring metrics for Prometheus.io. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/django-commons/django-prometheus) (👨‍💻 62 · 🔀 240 · 📦 4.3K · 📋 170 - 41% open · ⏱️ 14.10.2025):

	```
	git clone https://github.com/korfuri/django-prometheus
	```
- [PyPi](https://pypi.org/project/django-prometheus) (📥 2M / month):
	```
	pip install django-prometheus
	```
</details>
<details><summary><b><a href="https://github.com/highlight/highlight">highlight</a></b> (🥉26 ·  ⭐ 9K) - highlight.io: The open source, full-stack monitoring platform. Error monitoring, session replay, logging, distributed.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/highlight/highlight) (👨‍💻 85 · 🔀 460 · 📦 420 · 📋 2.8K - 9% open · ⏱️ 13.11.2025):

	```
	git clone https://github.com/highlight/highlight
	```
</details>
<details><summary><b><a href="https://github.com/Checkmk/checkmk">CheckMK</a></b> (🥉24 ·  ⭐ 2.1K) - Checkmk - Best-in-class infrastructure & application monitoring. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/Checkmk/checkmk) (👨‍💻 390 · 🔀 510 · ⏱️ 30.11.2025):

	```
	git clone https://github.com/Checkmk/checkmk
	```
</details>
<br>

## Application Monitoring SaaS

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://www.atatus.com/application-monitoring/">atatus APM</a></b>  

🔗&nbsp;<b><a href="https://checkmk.com/product/checkmk-cloud-saas">CheckMK Cloud SaaS</a></b>  

🔗&nbsp;<b><a href="https://www.datadoghq.com/product/apm/">DataDog APM</a></b>  

🔗&nbsp;<b><a href="https://www.honeycomb.io/platform">Honeycomb Observability Platform</a></b>  

🔗&nbsp;<b><a href="https://pydantic.dev/logfire">Pydantic Logfire</a></b>  

🔗&nbsp;<b><a href="https://www.paessler.com/application-monitoring">Paessler Application Monitoring</a></b>  

🔗&nbsp;<b><a href="https://www.scoutapm.com/">Scout APM</a></b>  

🔗&nbsp;<b><a href="https://sentry.io/for/performance/">Sentry APM</a></b>  

🔗&nbsp;<b><a href="https://www.solarwinds.com/solarwinds-observability">Solarwinds Observability SaaS</a></b>  

<br>

## Authentication and Authorization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pennersr/django-allauth">django-allauth</a></b> (🥇40 ·  ⭐ 10K) - Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pennersr/django-allauth) (👨‍💻 790 · 🔀 3K · 📦 270K · 📋 2.4K - 0% open · ⏱️ 20.11.2025):

	```
	git clone https://github.com/pennersr/django-allauth
	```
- [PyPi](https://pypi.org/project/django-allauth) (📥 2.1M / month):
	```
	pip install django-allauth
	```
</details>
<details><summary><b><a href="https://github.com/django-guardian/django-guardian">django-guardian</a></b> (🥇35 ·  ⭐ 3.8K) - Per object permissions for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-guardian/django-guardian) (👨‍💻 180 · 🔀 560 · 📦 7.6K · 📋 500 - 6% open · ⏱️ 28.11.2025):

	```
	git clone https://github.com/django-guardian/django-guardian
	```
- [PyPi](https://pypi.org/project/django-guardian) (📥 750K / month):
	```
	pip install django-guardian
	```
</details>
<details><summary><b><a href="https://github.com/django-oauth/django-oauth-toolkit">django-oauth-toolkit</a></b> (🥈34 ·  ⭐ 3.3K · 📈) - OAuth2 goodies for the Djangonauts!. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-oauth/django-oauth-toolkit) (👨‍💻 280 · 🔀 780 · 📦 12K · 📋 880 - 13% open · ⏱️ 14.11.2025):

	```
	git clone https://github.com/jazzband/django-oauth-toolkit
	```
- [PyPi](https://pypi.org/project/django-oauth-toolkit) (📥 2.6M / month):
	```
	pip install django-oauth-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-two-factor-auth">django-two-factor-auth</a></b> (🥈33 ·  ⭐ 1.8K) - Complete Two-Factor Authentication for Django providing the easiest integration into most Django projects. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-two-factor-auth) (👨‍💻 110 · 🔀 440 · 📦 2.4K · 📋 390 - 22% open · ⏱️ 05.11.2025):

	```
	git clone https://github.com/jazzband/django-two-factor-auth
	```
- [PyPi](https://pypi.org/project/django-two-factor-auth) (📥 990K / month):
	```
	pip install django-two-factor-auth
	```
</details>
<details><summary><b><a href="https://github.com/python-social-auth/social-app-django">social-app-django</a></b> (🥈32 ·  ⭐ 2.1K) - Python Social Auth - Application - Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/python-social-auth/social-app-django) (👨‍💻 340 · 🔀 380 · 📦 52K · 📋 270 - 9% open · ⏱️ 29.11.2025):

	```
	git clone https://github.com/python-social-auth/social-app-django
	```
- [PyPi](https://pypi.org/project/social-app-django):
	```
	pip install social-app-django
	```
</details>
<details><summary><b><a href="https://github.com/juanifioren/django-oidc-provider">django-oidc-provider</a></b> (🥈28 ·  ⭐ 450) - OpenID Connect and OAuth2 provider implementation for the Django framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/juanifioren/django-oidc-provider) (👨‍💻 76 · 🔀 220 · 📦 440 · 📋 210 - 24% open · ⏱️ 23.09.2025):

	```
	git clone https://github.com/juanifioren/django-oidc-provider
	```
- [PyPi](https://pypi.org/project/django-oidc-provider) (📥 20K / month):
	```
	pip install django-oidc-provider
	```
</details>
<details><summary><b><a href="https://github.com/django-cas-ng/django-cas-ng">django-cas-ng</a></b> (🥈28 ·  ⭐ 390) - Django CAS 1.0/2.0/3.0 client authentication library, supporting Django 4.2+ and Python 3.8+. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-cas-ng/django-cas-ng) (👨‍💻 89 · 🔀 160 · 📥 770 · 📦 640 · 📋 160 - 1% open · ⏱️ 18.11.2025):

	```
	git clone https://github.com/django-cas-ng/django-cas-ng
	```
- [PyPi](https://pypi.org/project/django-cas-ng) (📥 37K / month):
	```
	pip install django-cas-ng
	```
</details>
<details><summary><b><a href="https://github.com/bennylope/django-organizations">django-organizations</a></b> (🥉27 ·  ⭐ 1.3K) - Multi-user accounts for Django projects. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/bennylope/django-organizations) (👨‍💻 49 · 🔀 210 · 📦 320 · 📋 160 - 10% open · ⏱️ 10.06.2025):

	```
	git clone https://github.com/bennylope/django-organizations
	```
- [PyPi](https://pypi.org/project/django-organizations) (📥 110K / month):
	```
	pip install django-organizations
	```
</details>
<details><summary><b><a href="https://github.com/jsocol/django-ratelimit">django-ratelimit</a></b> (🥉27 ·  ⭐ 1.1K · 💤) - Cache-based rate-limiting for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jsocol/django-ratelimit) (👨‍💻 51 · 🔀 180 · 📦 4.5K · 📋 150 - 17% open · ⏱️ 05.12.2023):

	```
	git clone https://github.com/jsocol/django-ratelimit
	```
- [PyPi](https://pypi.org/project/django-ratelimit) (📥 2.1M / month):
	```
	pip install django-ratelimit
	```
</details>
<details><summary><b><a href="https://github.com/django-otp/django-otp">django-otp</a></b> (🥉26 ·  ⭐ 610) - A pluggable framework for adding two-factor authentication to Django using one-time passwords. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/django-otp/django-otp) (👨‍💻 52 · 🔀 120 · 📦 4.4K · 📋 89 - 14% open · ⏱️ 25.10.2025):

	```
	git clone https://github.com/django-otp/django-otp
	```
- [PyPi](https://pypi.org/project/django-otp) (📥 2M / month):
	```
	pip install django-otp
	```
</details>
<details><summary><b><a href="https://github.com/snok/django-auth-adfs">django-auth-adfs</a></b> (🥉26 ·  ⭐ 290) - A Django authentication backend for Microsoft ADFS and AzureAD. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/snok/django-auth-adfs) (👨‍💻 49 · 🔀 100 · 📦 180 · 📋 220 - 16% open · ⏱️ 23.10.2025):

	```
	git clone https://github.com/snok/django-auth-adfs
	```
- [PyPi](https://pypi.org/project/django-auth-adfs) (📥 90K / month):
	```
	pip install django-auth-adfs
	```
</details>
<details><summary><b><a href="https://github.com/valohai/django-allauth-2fa">django-allauth-2fa</a></b> (🥉22 ·  ⭐ 220) - Two-factor authentication for Django Allauth. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/valohai/django-allauth-2fa) (👨‍💻 34 · 🔀 51 · 📥 30 · 📦 250 · 📋 74 - 17% open · ⏱️ 11.08.2025):

	```
	git clone https://github.com/valohai/django-allauth-2fa
	```
- [PyPi](https://pypi.org/project/django-allauth-2fa) (📥 42K / month):
	```
	pip install django-allauth-2fa
	```
</details>
<details><summary><b><a href="https://github.com/caffeinehit/django-oauth2-provider">django-oauth2-provider</a></b> (🥉20 ·  ⭐ 340 · 💤) - Provide OAuth2 access to your app. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/caffeinehit/django-oauth2-provider) (👨‍💻 16 · 🔀 180 · 📦 34 · 📋 65 - 61% open · ⏱️ 03.02.2023):

	```
	git clone https://github.com/caffeinehit/django-oauth2-provider
	```
- [PyPi](https://pypi.org/project/django-oauth2-provider) (📥 9K / month):
	```
	pip install django-oauth2-provider
	```
</details>
<details><summary><b><a href="https://github.com/idlesign/django-oauthost">django-oauthost</a></b> (🥉6 ·  ⭐ 25 · 💤) - Reusable application for Django, introducing OAuth2 server functionality. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/idlesign/django-oauthost) (👨‍💻 2 · 📦 5 · 📋 3 - 33% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/idlesign/django-oauthost
	```
- [PyPi](https://pypi.org/project/django-oauthost) (📥 71 / month):
	```
	pip install django-oauthost
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/dimagi/django-prbac">django-prbac</a></b> (🥉16 ·  ⭐ 150) -  <code>❗Unlicensed</code>
- <b><a href="https://github.com/jrd/django-oauth2-authcodeflow">django-oauth2-authcodeflow</a></b> (🥉9 ·  ⭐ 17) - Authenticate with any OpenId Connect/Oauth2 provider through authorization code flow. PKCE is also supported. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dropseed/django-oauth-login">django-oauth-login</a></b> (🥉9 ·  ⭐ 17 · 💤) - A minimal app that adds OAuth login support to your Django project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Authorization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/dfunckt/django-rules">django-rules</a></b> (🥇20 ·  ⭐ 2K) - Awesome Django authorization, without the database. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dfunckt/django-rules) (👨‍💻 33 · 🔀 150 · 📋 120 - 25% open · ⏱️ 11.10.2025):

	```
	git clone https://github.com/dfunckt/django-rules
	```
- [PyPi](https://pypi.org/project/django-rules) (📥 270 / month):
	```
	pip install django-rules
	```
</details>
<br>

## Task Queues

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/celery/celery">celery</a></b> (🥇45 ·  ⭐ 28K) - Distributed Task Queue (development branch). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/celery/celery) (👨‍💻 1.4K · 🔀 4.8K · 📦 180K · 📋 5.2K - 13% open · ⏱️ 30.11.2025):

	```
	git clone https://github.com/celery/celery
	```
- [PyPi](https://pypi.org/project/celery) (📥 30M / month):
	```
	pip install celery
	```
</details>
<details><summary><b><a href="https://github.com/rq/rq">rq</a></b> (🥈39 ·  ⭐ 10K) - Simple job queues for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rq/rq) (👨‍💻 350 · 🔀 1.4K · 📦 21K · 📋 1.2K - 18% open · ⏱️ 30.11.2025):

	```
	git clone https://github.com/rq/rq
	```
- [PyPi](https://pypi.org/project/rq) (📥 3.5M / month):
	```
	pip install rq
	```
</details>
<details><summary><b><a href="https://github.com/Bogdanp/dramatiq">dramatiq</a></b> (🥈34 ·  ⭐ 5K) - A fast and reliable background task processing library for Python 3. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/Bogdanp/dramatiq) (👨‍💻 130 · 🔀 340 · 📥 56 · 📦 1.6K · 📋 430 - 10% open · ⏱️ 18.11.2025):

	```
	git clone https://github.com/Bogdanp/dramatiq
	```
- [PyPi](https://pypi.org/project/dramatiq) (📥 750K / month):
	```
	pip install dramatiq
	```
</details>
<details><summary><b><a href="https://github.com/rq/django-rq">django-rq</a></b> (🥈34 ·  ⭐ 1.9K) - A simple app that provides django integration for RQ (Redis Queue). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rq/django-rq) (👨‍💻 140 · 🔀 290 · 📦 4.3K · 📋 370 - 25% open · ⏱️ 29.11.2025):

	```
	git clone https://github.com/rq/django-rq
	```
- [PyPi](https://pypi.org/project/django-rq) (📥 570K / month):
	```
	pip install django-rq
	```
</details>
<details><summary><b><a href="https://github.com/celery/django-celery-beat">django-celery-beat</a></b> (🥉33 ·  ⭐ 1.9K) - Celery Periodic Tasks backed by the Django ORM. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/celery/django-celery-beat) (👨‍💻 140 · 🔀 460 · 📥 16 · 📦 29K · 📋 470 - 23% open · ⏱️ 24.11.2025):

	```
	git clone https://github.com/celery/django-celery-beat
	```
- [PyPi](https://pypi.org/project/django-celery-beat) (📥 3.9M / month):
	```
	pip install django-celery-beat
	```
</details>
<details><summary><b><a href="https://github.com/Koed00/django-q">django-q</a></b> (🥉30 ·  ⭐ 1.9K · 💤) - A multiprocessing distributed task queue for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Koed00/django-q) (👨‍💻 62 · 🔀 240 · 📦 2K · 📋 430 - 64% open · ⏱️ 26.06.2021):

	```
	git clone https://github.com/Koed00/django-q
	```
- [PyPi](https://pypi.org/project/django-q) (📥 67K / month):
	```
	pip install django-q
	```
</details>
<br>

## Finite State Machine

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement Finite State Machines (e.g. to implement workflows)._

<details><summary><b><a href="https://github.com/pytransitions/transitions">transitions</a></b> (🥇32 ·  ⭐ 6.3K) - A lightweight, object-oriented finite state machine implementation in Python with many extensions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pytransitions/transitions) (👨‍💻 81 · 🔀 540 · 📦 4.2K · 📋 470 - 2% open · ⏱️ 09.09.2025):

	```
	git clone https://github.com/pytransitions/transitions
	```
- [PyPi](https://pypi.org/project/transitions) (📥 1.9M / month):
	```
	pip install transitions
	```
</details>
<details><summary><b><a href="https://github.com/viewflow/django-fsm">django-fsm</a></b> (🥈25 ·  ⭐ 2.3K) - Django friendly finite state machine support. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/viewflow/django-fsm) (👨‍💻 70 · 🔀 280 · 📋 160 - 0% open · ⏱️ 07.10.2025):

	```
	git clone https://github.com/viewflow/django-fsm
	```
- [PyPi](https://pypi.org/project/django-fsm) (📥 530K / month):
	```
	pip install django-fsm
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-fsm-log">django-fsm-log</a></b> (🥈24 ·  ⭐ 250) - Automatic logging for Django FSM. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-fsm-log) (👨‍💻 28 · 🔀 76 · 📦 160 · 📋 49 - 24% open · ⏱️ 11.06.2025):

	```
	git clone https://github.com/jazzband/django-fsm-log
	```
- [PyPi](https://pypi.org/project/django-fsm-log) (📥 77K / month):
	```
	pip install django-fsm-log
	```
</details>
<details><summary><b><a href="https://github.com/viewflow/viewflow">viewflow</a></b> (🥉23 ·  ⭐ 2.8K) - Reusable workflow library for Django. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/viewflow/viewflow) (👨‍💻 2 · 🔀 410 · 📦 360 · 📋 360 - 5% open · ⏱️ 24.11.2025):

	```
	git clone https://github.com/viewflow/viewflow
	```
- [PyPi](https://pypi.org/project/viewflow) (📥 350 / month):
	```
	pip install viewflow
	```
</details>
<details><summary><b><a href="https://github.com/gadventures/django-fsm-admin">django-fsm-admin</a></b> (🥉18 ·  ⭐ 200 · 💤) - Mixin and template tags to integrate django-fsm transitions into the django admin. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gadventures/django-fsm-admin) (👨‍💻 33 · 🔀 93 · 📦 380 · 📋 39 - 48% open · ⏱️ 25.10.2022):

	```
	git clone https://github.com/gadventures/django-fsm-admin
	```
- [PyPi](https://pypi.org/project/django-fsm-admin) (📥 13K / month):
	```
	pip install django-fsm-admin
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/27medkamal/djangorestframework-fsm">djangorestframework-fsm</a></b> (🥉10 ·  ⭐ 19 · 💤) - Automatically hook your Django-FSM transitions up to Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ming-tung/django-fsm-freeze">django-fsm-freeze</a></b> (🥉7 ·  ⭐ 3 · 💤) - django-fsm data immutability support. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## RESTful API (Django Rest Framework)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/encode/django-rest-framework">django-rest-framework</a></b> (🥇42 ·  ⭐ 30K) - Web APIs for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/encode/django-rest-framework) (👨‍💻 1.5K · 🔀 6.9K · 📦 850K · 📋 3.9K - 1% open · ⏱️ 29.11.2025):

	```
	git clone https://github.com/encode/django-rest-framework
	```
- [PyPi](https://pypi.org/project/django-rest-framework) (📥 140K / month):
	```
	pip install django-rest-framework
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/djangorestframework-simplejwt">djangorestframework-simplejwt</a></b> (🥈28 ·  ⭐ 4.3K) - A JSON Web Token authentication plugin for the Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/djangorestframework-simplejwt) (👨‍💻 140 · 🔀 640 · 📋 510 - 21% open · ⏱️ 16.11.2025):

	```
	git clone https://github.com/jazzband/djangorestframework-simplejwt
	```
- [PyPi](https://pypi.org/project/djangorestframework-simplejwt) (📥 4.8M / month):
	```
	pip install djangorestframework-simplejwt
	```
</details>
<details><summary><b><a href="https://github.com/anexia-it/django-rest-passwordreset">django-rest-passwordreset</a></b> (🥉27 ·  ⭐ 440 · 💤) - An extension of django rest framework, providing a configurable password reset strategy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anexia-it/django-rest-passwordreset) (👨‍💻 40 · 🔀 140 · 📦 4.4K · 📋 110 - 25% open · ⏱️ 13.11.2024):

	```
	git clone https://github.com/anexia-it/django-rest-passwordreset
	```
- [PyPi](https://pypi.org/project/django-rest-passwordreset) (📥 280K / month):
	```
	pip install django-rest-passwordreset
	```
</details>
<details><summary><b><a href="https://github.com/yezyilomo/django-restql">django-restql</a></b> (🥉23 ·  ⭐ 630) - Turn your API made with Django REST Framework(DRF) into a GraphQL like API. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/yezyilomo/django-restql) (👨‍💻 6 · 🔀 44 · 📦 330 · 📋 110 - 21% open · ⏱️ 13.08.2025):

	```
	git clone https://github.com/yezyilomo/django-restql
	```
- [PyPi](https://pypi.org/project/django-restql) (📥 38K / month):
	```
	pip install django-restql
	```
</details>
<details><summary><b><a href="https://github.com/wq/django-rest-pandas">django-rest-pandas</a></b> (🥉16 ·  ⭐ 1.3K · 💤) - Serves up Pandas dataframes via the Django REST Framework for use in client-side (i.e. d3.js) visualizations and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

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

<details><summary><b><a href="https://github.com/vitalik/django-ninja">django-ninja</a></b> (🥇32 ·  ⭐ 8.7K) - Fast, Async-ready, Openapi, type hints based framework for building APIs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vitalik/django-ninja) (👨‍💻 170 · 🔀 540 · 📋 980 - 11% open · ⏱️ 14.11.2025):

	```
	git clone https://github.com/vitalik/django-ninja
	```
- [PyPi](https://pypi.org/project/django-ninja) (📥 990K / month):
	```
	pip install django-ninja
	```
</details>
<details><summary><b><a href="https://github.com/eadwinCode/django-ninja-jwt">django-ninja-jwt</a></b> (🥈27 ·  ⭐ 220) - A JSON Web Token authentication plugin for the Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eadwinCode/django-ninja-jwt) (👨‍💻 88 · 🔀 31 · 📦 500 · 📋 42 - 42% open · ⏱️ 22.11.2025):

	```
	git clone https://github.com/eadwinCode/django-ninja-jwt
	```
- [PyPi](https://pypi.org/project/django-ninja-jwt) (📥 91K / month):
	```
	pip install django-ninja-jwt
	```
</details>
<details><summary><b><a href="https://github.com/eadwinCode/django-ninja-extra">django-ninja-extra</a></b> (🥈23 ·  ⭐ 540) - Django Ninja Extra - Class-Based Utility and more for Django Ninja(Fast Django REST framework). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eadwinCode/django-ninja-extra) (👨‍💻 27 · 🔀 48 · 📋 100 - 17% open · ⏱️ 22.11.2025):

	```
	git clone https://github.com/eadwinCode/django-ninja-extra
	```
- [PyPi](https://pypi.org/project/django-ninja-extra) (📥 180K / month):
	```
	pip install django-ninja-extra
	```
</details>
<details><summary><b><a href="https://github.com/mawassk/django-ninja-apikey">django-ninja-apikey</a></b> (🥉12 ·  ⭐ 43 · 💤) - Easy to use API key authentication for Django Ninja REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mawassk/django-ninja-apikey) (🔀 11 · 📦 7 · 📋 3 - 66% open · ⏱️ 27.08.2021):

	```
	git clone https://github.com/mawassk/django-ninja-apikey
	```
- [PyPi](https://pypi.org/project/django-ninja-apikey) (📥 1.5K / month):
	```
	pip install django-ninja-apikey
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/eadwinCode/django-ninja-passwordreset">django-ninja-passwordreset</a></b> (🥉14 ·  ⭐ 5 · 💤) - An extension of django rest framework, providing a configurable password reset strategy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mugartec/django-ninja-auth">django-ninja-auth</a></b> (🥉6 ·  ⭐ 34 · 💤) -  <code><a href="https://tldrlegal.com/search?q=WTFPL">❗️WTFPL</a></code>
</details>
<br>

## Pydantic integration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pydantic/pydantic">pydantic</a></b> (🥇47 ·  ⭐ 26K) - Data validation using Python type hints. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydantic/pydantic) (👨‍💻 710 · 🔀 2.3K · 📦 930K · 📋 5.5K - 9% open · ⏱️ 30.11.2025):

	```
	git clone https://github.com/pydantic/pydantic
	```
- [PyPi](https://pypi.org/project/pydantic) (📥 560M / month):
	```
	pip install pydantic
	```
</details>
<details><summary><b><a href="https://github.com/jordaneremieff/djantic">djantic</a></b> (🥈19 ·  ⭐ 470 · 💤) - Pydantic model support for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jordaneremieff/djantic) (👨‍💻 4 · 🔀 33 · 📦 86 · 📋 41 - 31% open · ⏱️ 13.02.2023):

	```
	git clone https://github.com/jordaneremieff/djantic
	```
- [PyPi](https://pypi.org/project/djantic) (📥 7.3K / month):
	```
	pip install djantic
	```
</details>
<details><summary><b><a href="https://github.com/yezz123/pyngo">pyngo</a></b> (🥉18 ·  ⭐ 89) - Pydantic model support for Django & Django-Rest-Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/yezz123/pyngo) (👨‍💻 8 · 🔀 8 · 📦 30 · ⏱️ 08.09.2025):

	```
	git clone https://github.com/yezz123/pyngo
	```
- [PyPi](https://pypi.org/project/pyngo) (📥 21K / month):
	```
	pip install pyngo
	```
</details>
<details><summary><b><a href="https://github.com/jonathan-s/djantic2">djantic2</a></b> (🥉15 ·  ⭐ 91) - Pydantic model support for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jonathan-s/djantic2) (👨‍💻 9 · 🔀 11 · 📦 5 · 📋 16 - 37% open · ⏱️ 27.05.2025):

	```
	git clone https://github.com/jonathan-s/djantic2
	```
- [PyPi](https://pypi.org/project/djantic) (📥 7.3K / month):
	```
	pip install djantic
	```
</details>
<br>

## Pandas integration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/chrisdev/django-pandas">django-pandas</a></b> (🥇24 ·  ⭐ 810) - Tools for working with pandas in your Django projects. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/chrisdev/django-pandas) (👨‍💻 36 · 🔀 120 · 📦 2.6K · 📋 86 - 17% open · ⏱️ 30.05.2025):

	```
	git clone https://github.com/chrisdev/django-pandas
	```
- [PyPi](https://pypi.org/project/django-pandas) (📥 170K / month):
	```
	pip install django-pandas
	```
</details>
<br>

## GraphQL API

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement GraphQL API._

<details><summary><b><a href="https://github.com/graphql-python/graphene">graphene</a></b> (🥇37 ·  ⭐ 8.2K · 💤) - GraphQL framework for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene) (👨‍💻 210 · 🔀 800 · 📦 30K · 📋 1K - 8% open · ⏱️ 09.11.2024):

	```
	git clone https://github.com/graphql-python/graphene
	```
- [PyPi](https://pypi.org/project/graphene) (📥 25M / month):
	```
	pip install graphene
	```
</details>
<details><summary><b><a href="https://github.com/mirumee/ariadne">ariadne</a></b> (🥈34 ·  ⭐ 2.3K) - Python library for implementing GraphQL servers using schema-first approach. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mirumee/ariadne) (👨‍💻 85 · 🔀 190 · 📥 67 · 📦 2K · 📋 330 - 11% open · ⏱️ 13.10.2025):

	```
	git clone https://github.com/mirumee/ariadne
	```
- [PyPi](https://pypi.org/project/ariadne) (📥 1.8M / month):
	```
	pip install ariadne
	```
</details>
<details><summary><b><a href="https://github.com/graphql-python/graphene-django">graphene-django</a></b> (🥈33 ·  ⭐ 4.4K) - Build powerful, efficient, and flexible GraphQL APIs with seamless Django integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene-django) (👨‍💻 220 · 🔀 740 · 📦 16K · 📋 830 - 17% open · ⏱️ 23.06.2025):

	```
	git clone https://github.com/graphql-python/graphene-django
	```
- [PyPi](https://pypi.org/project/graphene-django) (📥 930K / month):
	```
	pip install graphene-django
	```
</details>
<details><summary><b><a href="https://github.com/flavors/django-graphql-jwt">django-graphql-jwt</a></b> (🥉28 ·  ⭐ 830 · 💤) - JSON Web Token (JWT) authentication for Graphene Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/flavors/django-graphql-jwt) (👨‍💻 26 · 🔀 160 · 📦 5.6K · 📋 230 - 26% open · ⏱️ 04.08.2023):

	```
	git clone https://github.com/flavors/django-graphql-jwt
	```
- [PyPi](https://pypi.org/project/django-graphql-jwt) (📥 150K / month):
	```
	pip install django-graphql-jwt
	```
</details>
<details><summary><b><a href="https://github.com/strawberry-graphql/strawberry">strawberry</a></b> (🥉27 ·  ⭐ 4.6K) - A GraphQL library for Python that leverages type annotations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/strawberry-graphql/strawberry) (👨‍💻 300 · 🔀 590 · 📥 520 · 📋 1.1K - 34% open · ⏱️ 24.11.2025):

	```
	git clone https://github.com/strawberry-graphql/strawberry
	```
- [PyPi](https://pypi.org/project/strawberry) (📥 550 / month):
	```
	pip install strawberry
	```
</details>
<details><summary><b><a href="https://github.com/strawberry-graphql/strawberry-django">strawberry-graphql-django</a></b> (🥉25 ·  ⭐ 480) - Strawberry GraphQL Django extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/strawberry-graphql/strawberry-django) (👨‍💻 100 · 🔀 150 · 📋 390 - 23% open · ⏱️ 23.11.2025):

	```
	git clone https://github.com/strawberry-graphql/strawberry-graphql-django
	```
- [PyPi](https://pypi.org/project/strawberry-graphql-django) (📥 750K / month):
	```
	pip install strawberry-graphql-django
	```
</details>
<details><summary><b><a href="https://github.com/PedroBern/django-graphql-auth">django-graphql-auth</a></b> (🥉19 ·  ⭐ 330 · 💤) - Django registration and authentication with GraphQL. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PedroBern/django-graphql-auth) (👨‍💻 16 · 🔀 100 · 📦 750 · 📋 100 - 58% open · ⏱️ 17.06.2022):

	```
	git clone https://github.com/PedroBern/django-graphql-auth
	```
- [PyPi](https://pypi.org/project/django-graphql-auth) (📥 6.8K / month):
	```
	pip install django-graphql-auth
	```
</details>
<details><summary><b><a href="https://github.com/mirumee/ariadne-django">ariadne-django</a></b> (🥉14 ·  ⭐ 67 · 💤) - ariadne_django makes integrating ariadne and django together easier. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mirumee/ariadne-django) (👨‍💻 9 · 🔀 10 · 📋 27 - 40% open · ⏱️ 23.08.2022):

	```
	git clone https://github.com/mirumee/ariadne-django
	```
- [PyPi](https://pypi.org/project/ariadne-django) (📥 17K / month):
	```
	pip install ariadne-django
	```
</details>
<br>

## Feature Flipper

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-waffle/django-waffle">django-waffle</a></b> (🥇31 ·  ⭐ 1.2K) - A feature flipper for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-waffle/django-waffle) (👨‍💻 120 · 🔀 240 · 📦 1.7K · 📋 220 - 18% open · ⏱️ 02.10.2025):

	```
	git clone https://github.com/django-waffle/django-waffle
	```
- [PyPi](https://pypi.org/project/django-waffle) (📥 1.2M / month):
	```
	pip install django-waffle
	```
</details>
<br>

## Statistics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which add application layer statistic functionality._

<details><summary><b><a href="https://github.com/pennersr/django-trackstats">django-trackstats</a></b> (🥇15 ·  ⭐ 450 · 💤) - Keep track of your statistics. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pennersr/django-trackstats) (👨‍💻 9 · 🔀 39 · 📦 28 · 📋 12 - 33% open · ⏱️ 04.08.2023):

	```
	git clone https://github.com/pennersr/django-trackstats
	```
- [PyPi](https://pypi.org/project/django-trackstats) (📥 2.1K / month):
	```
	pip install django-trackstats
	```
</details>
<br>

## Testing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pytest-dev/pytest-django">pytest-django</a></b> (🥇35 ·  ⭐ 1.5K) - A Django plugin for pytest. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-django) (👨‍💻 150 · 🔀 340 · 📦 95K · 📋 560 - 28% open · ⏱️ 04.11.2025):

	```
	git clone https://github.com/pytest-dev/pytest-django
	```
- [PyPi](https://pypi.org/project/pytest-django) (📥 9M / month):
	```
	pip install pytest-django
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/django-test-migrations">django-test-migrations</a></b> (🥈26 ·  ⭐ 560) - Test django schema and data migrations, including migrations order and best practices. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/django-test-migrations) (👨‍💻 20 · 🔀 33 · 📦 1K · 📋 68 - 22% open · ⏱️ 24.11.2025):

	```
	git clone https://github.com/wemake-services/django-test-migrations
	```
- [PyPi](https://pypi.org/project/django-test-migrations) (📥 340K / month):
	```
	pip install django-test-migrations
	```
</details>
<details><summary><b><a href="https://github.com/FactoryBoy/factory_boy">factory_boy</a></b> (🥉25 ·  ⭐ 3.7K) - A test fixtures replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/FactoryBoy/factory_boy) (👨‍💻 130 · 🔀 400 · 📋 600 - 26% open · ⏱️ 31.08.2025):

	```
	git clone https://github.com/FactoryBoy/factory_boy
	```
- [PyPi](https://pypi.org/project/factory_boy) (📥 12M / month):
	```
	pip install factory_boy
	```
</details>
<details><summary><b><a href="https://github.com/model-bakers/model_bakery">model_bakery</a></b> (🥉21 ·  ⭐ 950) - Object factory for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/model-bakers/model_bakery) (👨‍💻 63 · 🔀 97 · 📋 160 - 17% open · ⏱️ 31.10.2025):

	```
	git clone https://github.com/model-bakers/model_bakery
	```
- [PyPi](https://pypi.org/project/model_bakery) (📥 1.3M / month):
	```
	pip install model_bakery
	```
</details>
<details><summary><b><a href="https://github.com/revsys/django-test-plus">django-test-plus</a></b> (🥉18 ·  ⭐ 630) - Useful additions to Djangos default TestCase. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/revsys/django-test-plus) (👨‍💻 36 · 🔀 63 · 📋 60 - 11% open · ⏱️ 02.07.2025):

	```
	git clone https://github.com/revsys/django-test-plus
	```
- [PyPi](https://pypi.org/project/django-test-plus) (📥 100K / month):
	```
	pip install django-test-plus
	```
</details>
<br>

## Architecture Testing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/zyskarch/pytestarch">PyTestArch</a></b> (🥇18 ·  ⭐ 140) - Test framework for software architecture based on imports between modules. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/zyskarch/pytestarch) (👨‍💻 11 · 🔀 9 · 📋 49 - 22% open · ⏱️ 22.08.2025):

	```
	git clone https://github.com/zyskarch/pytestarch
	```
- [PyPi](https://pypi.org/project/pytestarch) (📥 55K / month):
	```
	pip install pytestarch
	```
</details>
<details><summary><b><a href="https://github.com/jwbargsten/pytest-archon">pytest-archon</a></b> (🥈16 ·  ⭐ 70) - Rule your architecture like a real developer. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jwbargsten/pytest-archon) (👨‍💻 3 · 🔀 2 · 📦 43 · 📋 9 - 22% open · ⏱️ 19.09.2025):

	```
	git clone https://github.com/jwbargsten/pytest-archon
	```
- [PyPi](https://pypi.org/project/pytest-archon) (📥 680K / month):
	```
	pip install pytest-archon
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/nwilbert/pytest-arch">pytest-arch</a></b> (🥉5 ·  ⭐ 13 · 💤) - A pythonic derivative of ArchUnit, in the form of a pytest plugin. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/pcah/pca-archunit">pca-archunit</a></b> (🥉4 · 💤) - A DSL & analysis library for testing architecture of your application. Part of the python-clean-architecture project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Static Code Analysis

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/astral-sh/ruff">ruff</a></b> (🥇47 ·  ⭐ 44K · 📈) - An extremely fast Python linter and code formatter, written in Rust. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/astral-sh/ruff) (👨‍💻 760 · 🔀 1.6K · 📥 3M · 📦 130K · 📋 7.5K - 21% open · ⏱️ 30.11.2025):

	```
	git clone https://github.com/astral-sh/ruff
	```
- [PyPi](https://pypi.org/project/ruff) (📥 100M / month):
	```
	pip install ruff
	```
</details>
<details><summary><b><a href="https://github.com/fpgmaas/deptry">deptry</a></b> (🥉32 ·  ⭐ 1.2K) - Find unused, missing and transitive dependencies in a Python project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fpgmaas/deptry) (👨‍💻 14 · 🔀 28 · 📦 1.7K · 📋 190 - 18% open · ⏱️ 29.11.2025):

	```
	git clone https://github.com/fpgmaas/deptry
	```
- [PyPi](https://pypi.org/project/deptry) (📥 2.8M / month):
	```
	pip install deptry
	```
</details>
<br>

## Vulnerability databases based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/aboutcode-org/vulnerablecode">vulnerablecode</a></b> (🥇22 ·  ⭐ 640) - A free and open vulnerabilities database and the packages they impact. And the tools to aggregate and correlate these.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aboutcode-org/vulnerablecode) (👨‍💻 51 · 🔀 240 · 📥 530 · 📋 1.2K - 57% open · ⏱️ 25.11.2025):

	```
	git clone https://github.com/aboutcode-org/vulnerablecode
	```
- [PyPi](https://pypi.org/project/vulnerablecode) (📥 82 / month):
	```
	pip install vulnerablecode
	```
</details>
<br>

## CMS frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Content Management Systems which use Django under the hood._

<details><summary><b><a href="https://github.com/wagtail/wagtail">wagtail</a></b> (🥇43 ·  ⭐ 20K) - A Django content management system focused on flexibility and user experience. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wagtail/wagtail) (👨‍💻 1K · 🔀 4.2K · 📦 12K · 📋 5.4K - 15% open · ⏱️ 28.11.2025):

	```
	git clone https://github.com/wagtail/wagtail
	```
- [PyPi](https://pypi.org/project/wagtail) (📥 480K / month):
	```
	pip install wagtail
	```
</details>
<details><summary><b><a href="https://github.com/django-cms/django-cms">django-cms</a></b> (🥉38 ·  ⭐ 11K · 📉) - The easy-to-use and developer-friendly enterprise CMS powered by Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-cms/django-cms) (👨‍💻 590 · 🔀 3.1K · 📦 5.5K · 📋 3.6K - 0% open · ⏱️ 26.11.2025):

	```
	git clone https://github.com/django-cms/django-cms
	```
- [PyPi](https://pypi.org/project/django-cms) (📥 130K / month):
	```
	pip install django-cms
	```
</details>
<details><summary><b><a href="https://github.com/stephenmcd/mezzanine">mezzanine</a></b> (🥉32 ·  ⭐ 4.8K) - CMS framework for Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/stephenmcd/mezzanine) (👨‍💻 330 · 🔀 1.6K · 📦 2.5K · 📋 1.1K - 4% open · ⏱️ 06.04.2025):

	```
	git clone https://github.com/stephenmcd/mezzanine
	```
- [PyPi](https://pypi.org/project/mezzanine) (📥 24K / month):
	```
	pip install mezzanine
	```
</details>
<br>

## E-Commerce frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_E-Commerce frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/django-oscar/django-oscar">django-oscar</a></b> (🥇36 ·  ⭐ 6.5K) - Domain-driven e-commerce for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-oscar/django-oscar) (👨‍💻 380 · 🔀 2.2K · 📦 1.2K · 📋 1.5K - 6% open · ⏱️ 19.11.2025):

	```
	git clone https://github.com/django-oscar/django-oscar
	```
- [PyPi](https://pypi.org/project/django-oscar) (📥 59K / month):
	```
	pip install django-oscar
	```
</details>
<details><summary><b><a href="https://github.com/saleor/saleor">saleor</a></b> (🥈32 ·  ⭐ 22K) - Saleor Core: the high performance, composable, headless commerce API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/saleor/saleor) (👨‍💻 320 · 🔀 5.7K · 📥 780 · 📦 8 · 📋 4.4K - 4% open · ⏱️ 28.11.2025):

	```
	git clone https://github.com/saleor/saleor
	```
- [PyPi](https://pypi.org/project/saleor) (📥 22 / month):
	```
	pip install saleor
	```
</details>
<details><summary><b><a href="https://github.com/awesto/django-shop">django-shop</a></b> (🥉25 ·  ⭐ 3.3K · 💤) - A Django based shop system. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/awesto/django-shop) (👨‍💻 96 · 🔀 1K · 📦 230 · 📋 380 - 23% open · ⏱️ 28.02.2021):

	```
	git clone https://github.com/awesto/django-shop
	```
- [PyPi](https://pypi.org/project/django-shop) (📥 710 / month):
	```
	pip install django-shop
	```
</details>
<details><summary><b><a href="https://github.com/shuup/shuup">shuup</a></b> (🥉25 ·  ⭐ 2.3K · 💤) - E-Commerce Platform. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/shuup/shuup) (👨‍💻 67 · 🔀 1.1K · 📥 710 · 📦 190 · 📋 440 - 33% open · ⏱️ 18.08.2021):

	```
	git clone https://github.com/shuup/shuup
	```
- [PyPi](https://pypi.org/project/shuup) (📥 5.4K / month):
	```
	pip install shuup
	```
</details>
<br>

## Analytics frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Analytics frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/milesmcc/shynet">shynet</a></b> (🥇18 ·  ⭐ 3.1K) - Modern, privacy-friendly, and detailed web analytics that works without cookies or JS. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/milesmcc/shynet) (👨‍💻 38 · 🔀 200 · 📋 190 - 26% open · ⏱️ 19.12.2024):

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

<details><summary><b><a href="https://github.com/makeplane/plane">plane</a></b> (🥇29 ·  ⭐ 40K) - Open Source JIRA, Linear, Monday, and Asana Alternative. Plane helps you track your issues, epics, and cycles the.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/makeplane/plane) (👨‍💻 130 · 🔀 2.9K · 📥 100K · 📋 1.4K - 37% open · ⏱️ 28.11.2025):

	```
	git clone https://github.com/makeplane/plane
	```
</details>
<details><summary><b><a href="https://github.com/kaleidos-ventures/taiga">taiga</a></b> (🥉12 ·  ⭐ 530 · 💤) - Taiga is a free and open-source project management for cross-functional agile teams. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/kaleidos-ventures/taiga) (👨‍💻 11 · 🔀 75 · ⏱️ 13.12.2023):

	```
	git clone https://github.com/kaleidos-ventures/taiga
	```
</details>
<br>

## Monitoring frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Monitoring frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/getsentry/sentry">sentry</a></b> (🥇38 ·  ⭐ 43K) - Developer-first error tracking and performance monitoring. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/getsentry/sentry) (👨‍💻 1K · 🔀 4.5K · 📥 6.1K · 📦 580 · 📋 16K - 10% open · ⏱️ 28.11.2025):

	```
	git clone https://github.com/getsentry/sentry
	```
</details>
<br>

## Security frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Security frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/DefectDojo/django-DefectDojo">DefectDojo</a></b> (🥇34 ·  ⭐ 4.4K) - Open-Source Unified Vulnerability Management, DevSecOps & ASPM. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/DefectDojo/django-DefectDojo) (👨‍💻 540 · 🔀 1.8K · 📥 740K · 📋 3.1K - 7% open · ⏱️ 24.11.2025):

	```
	git clone https://github.com/DefectDojo/django-DefectDojo
	```
</details>
<details><summary><b><a href="https://github.com/MobSF/Mobile-Security-Framework-MobSF">Mobile Security Framework (MobSF)</a></b> (🥉26 ·  ⭐ 20K) - Mobile Security Framework (MobSF) is an automated, all-in-one mobile application (Android/iOS/Windows) pen-testing,.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/MobSF/Mobile-Security-Framework-MobSF) (👨‍💻 100 · 🔀 3.4K · 📦 5 · 📋 1.5K - 1% open · ⏱️ 04.10.2025):

	```
	git clone https://github.com/MobSF/Mobile-Security-Framework-MobSF
	```
</details>
<details><summary><b><a href="https://github.com/intelowlproject/IntelOwl">Intel owl</a></b> (🥉20 ·  ⭐ 4.4K) - IntelOwl: manage your Threat Intelligence at scale. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/intelowlproject/IntelOwl) (👨‍💻 70 · 🔀 510 · 📋 640 - 7% open · ⏱️ 20.05.2025):

	```
	git clone https://github.com/intelowlproject/IntelOwl
	```
</details>
<br>

## Governance, Risk and Compliance frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/intuitem/ciso-assistant-community">CISO Assistant (Community Edition)</a></b> (🥇23 ·  ⭐ 3.4K) - CISO Assistant is a one-stop-shop for GRC, covering Risk, AppSec, Compliance/Audit Management, Privacy and supporting.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/intuitem/ciso-assistant-community) (👨‍💻 76 · 🔀 530 · 📋 530 - 16% open · ⏱️ 29.11.2025):

	```
	git clone https://github.com/intuitem/ciso-assistant-community
	```
</details>
<br>

## Privileged Access Management frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jumpserver/jumpserver">JumpServer (Community Edition)</a></b> (🥇34 ·  ⭐ 29K) - JumpServer is an open-source Privileged Access Management (PAM) platform that provides DevOps and IT teams with on-.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/jumpserver/jumpserver) (👨‍💻 180 · 🔀 5.5K · 📥 90K · 📦 21 · 📋 7.5K - 0% open · ⏱️ 28.11.2025):

	```
	git clone https://github.com/jumpserver/jumpserver
	```
</details>
<br>

## Photo management frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Photo management frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/LibrePhotos/librephotos">librephotos</a></b> (🥇21 ·  ⭐ 7.9K) - A self-hosted open source photo management service. This is the repository of the backend. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/LibrePhotos/librephotos) (👨‍💻 79 · 🔀 370 · 📋 900 - 28% open · ⏱️ 23.11.2025):

	```
	git clone https://github.com/LibrePhotos/librephotos
	```
</details>
<br>

## Recipe management frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Recipe management frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/TandoorRecipes/recipes">Tandoor Recipes</a></b> (🥇25 ·  ⭐ 7.7K) - Application for managing recipes, planning meals, building shopping lists and much much more!. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/TandoorRecipes/recipes) (👨‍💻 450 · 🔀 730 · 📋 2.3K - 14% open · ⏱️ 30.11.2025):

	```
	git clone https://github.com/TandoorRecipes/recipes
	```
</details>
<br>

## Document management frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Document management frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/paperless-ngx/paperless-ngx">Paperless-ngx</a></b> (🥇32 ·  ⭐ 35K) - A community-supported supercharged document management system: scan, index and archive all your documents. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/paperless-ngx/paperless-ngx) (👨‍💻 420 · 🔀 2.2K · 📥 220K · ⏱️ 30.11.2025):

	```
	git clone https://github.com/paperless-ngx/paperless-ngx
	```
</details>
<br>

## Education frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Education frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/openedx/edx-platform">Open edX</a></b> (🥇29 ·  ⭐ 7.9K) - The Open edX LMS & Studio, powering education sites around the world!. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/openedx/edx-platform) (👨‍💻 1.5K · 🔀 3.9K · 📦 3 · 📋 920 - 32% open · ⏱️ 30.11.2025):

	```
	git clone https://github.com/openedx/edx-platform
	```
</details>
<br>

## Inventory management system based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Inventory management systems which use Django under the hood._

<details><summary><b><a href="https://github.com/inventree/InvenTree">InvenTree</a></b> (🥇30 ·  ⭐ 6.1K) - Open Source Inventory Management System. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inventree/InvenTree) (👨‍💻 120 · 🔀 1.2K · 📥 2.5K · 📦 8 · 📋 3.2K - 4% open · ⏱️ 30.11.2025):

	```
	git clone https://github.com/inventree/InvenTree
	```
</details>
<br>

## Crawler management system based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Web crawler management systems which use Django under the hood._

<details><summary><b><a href="https://github.com/Gerapy/Gerapy">Gerapy</a></b> (🥇21 ·  ⭐ 3.5K · 💤) - Distributed Crawler Management Framework Based on Scrapy, Scrapyd, Django and Vue.js. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Gerapy/Gerapy) (👨‍💻 17 · 🔀 650 · 📦 150 · 📋 220 - 30% open · ⏱️ 07.09.2024):

	```
	git clone https://github.com/Gerapy/Gerapy
	```
</details>
<br>

## Network automation system based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Network automation systems which use Django under the hood._

<details><summary><b><a href="https://github.com/netbox-community/netbox">netbox</a></b> (🥇32 ·  ⭐ 19K) - The premier source of truth powering network automation. Open source under Apache 2. Try NetBox Cloud free:.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/netbox-community/netbox) (👨‍💻 440 · 🔀 2.9K · 📋 12K - 2% open · ⏱️ 26.11.2025):

	```
	git clone https://github.com/netbox-community/netbox
	```
</details>
<br>

## Test automation systems based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/autotest/autotest">Autotest (fully automated testing primarily designed to test the Linux kernel) dashboard backend.</a></b> (🥇18 ·  ⭐ 720 · 💤) - Autotest - Fully automated tests on Linux. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/autotest/autotest) (👨‍💻 300 · 🔀 340 · 📦 42 · 📋 400 - 28% open · ⏱️ 01.12.2023):

	```
	git clone https://github.com/autotest/autotest
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/kernelci/dashboard">KernelCI (distributed test automation system focused on upstream kernel development) dashboard backend.</a></b> (🥈16 ·  ⭐ 6) - KernelCI web dashboard. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/lava/lava">Linaro Automated Validation Architecture (LAVA)</a></b> (🥉7 ·  ⭐ 15 · 💤) - LAVA is a continuous integration system for deploying operating systems onto physical and virtual hardware for running.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/avocado-framework/avocado-server">Avocado (fully automated testing primarily designed to test the Linux kernel) server backend.</a></b> (🥉6 ·  ⭐ 3 · 💀) - REST based interface for applications to interact with an avocado server. <code>❗Unlicensed</code>
- <b><a href="https://gitlab.com/Linaro/squad/squad">Squad (Software Quality Dashboard for LAVA) backend.</a></b> ( ⭐ 1 · 💤) -  <code>❗Unlicensed</code>
</details>
<br>

## Fields (encrypted)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/georgemarshall/django-cryptography">django-cryptography</a></b> (🥇18 ·  ⭐ 410 · 💤) - Easily encrypt data in Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/georgemarshall/django-cryptography) (👨‍💻 4 · 🔀 78 · 📋 75 - 57% open · ⏱️ 16.02.2024):

	```
	git clone https://github.com/georgemarshall/django-cryptography
	```
- [PyPi](https://pypi.org/project/django-cryptography) (📥 210K / month):
	```
	pip install django-cryptography
	```
</details>
<details><summary><b><a href="https://github.com/luojilab/django-mirage-field">django-mirage-field</a></b> (🥈17 ·  ⭐ 93 · 💤) - Django model field encrypt/decrypt your data, keep secret in database. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/luojilab/django-mirage-field) (👨‍💻 9 · 🔀 12 · 📦 140 · 📋 14 - 14% open · ⏱️ 19.04.2022):

	```
	git clone https://github.com/luojilab/django-mirage-field
	```
- [PyPi](https://pypi.org/project/django-mirage-field) (📥 19K / month):
	```
	pip install django-mirage-field
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/orcasgit/django-fernet-fields">django-fernet-fields</a></b> (🥇18 ·  ⭐ 200 · 💀) - Fernet symmetric encryption for Django model fields. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/foundertherapy/django-cryptographic-fields">django-cryptographic-fields</a></b> (🥉14 ·  ⭐ 32 · 💀) - A set of fields that wrap standard Django fields with encryption provided by the python cryptography library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/lansharkconsulting/django/django-encrypted-model-fields">django-encrypted-model-fields</a></b> (🥉11 ·  ⭐ 33 · 💀) - A set of fields that wrap standard Django fields with encryption provided by the python cryptography library. <code>❗Unlicensed</code>
- <b><a href="https://gitlab.com/guywillett/django-searchable-encrypted-fields">django-searchable-encrypted-fields</a></b> (🥉6 ·  ⭐ 9 · 💀) -  <code>❗Unlicensed</code>
</details>
<br>

## Fields (phone numbers)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/stefanfoulis/django-phonenumber-field">django-phonenumber-field</a></b> (🥇34 ·  ⭐ 1.5K) - A django model and form field for normalised phone numbers using python-phonenumbers. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stefanfoulis/django-phonenumber-field) (👨‍💻 120 · 🔀 300 · 📥 43 · 📦 32K · 📋 230 - 3% open · ⏱️ 24.11.2025):

	```
	git clone https://github.com/stefanfoulis/django-phonenumber-field
	```
- [PyPi](https://pypi.org/project/django-phonenumber-field) (📥 3.1M / month):
	```
	pip install django-phonenumber-field
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/VeryApt/django-phone-field">django-phone-field</a></b> (🥉18 ·  ⭐ 50 · 💀) - Lightweight model and form field for phone numbers in Django. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Fields (addresses)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/furious-luke/django-address">django-address</a></b> (🥇24 ·  ⭐ 440 · 💤) - A Django address model and field. Addresses may be specified by address components or by performing an automatic.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/furious-luke/django-address) (👨‍💻 22 · 🔀 160 · 📦 480 · 📋 130 - 32% open · ⏱️ 05.05.2022):

	```
	git clone https://github.com/furious-luke/django-address
	```
- [PyPi](https://pypi.org/project/django-address) (📥 11K / month):
	```
	pip install django-address
	```
</details>
<details><summary><b><a href="https://github.com/openwisp/django-loci">django-loci</a></b> (🥈23 ·  ⭐ 190) - Reusable Django app for storing geographic and indoor coordinates. Maintained by the OpenWISP Project. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/openwisp/django-loci) (👨‍💻 32 · 🔀 45 · 📦 15 · 📋 46 - 4% open · ⏱️ 30.10.2025):

	```
	git clone https://github.com/openwisp/django-loci
	```
- [PyPi](https://pypi.org/project/django-loci) (📥 4.6K / month):
	```
	pip install django-loci
	```
</details>
<details><summary><b><a href="https://github.com/madisona/django-google-maps">django-google-maps</a></b> (🥉22 ·  ⭐ 280) - Using the Google Maps API with django model admin. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/madisona/django-google-maps) (👨‍💻 20 · 🔀 96 · 📦 690 · 📋 47 - 25% open · ⏱️ 21.09.2025):

	```
	git clone https://github.com/madisona/django-google-maps
	```
- [PyPi](https://pypi.org/project/django-google-maps) (📥 25K / month):
	```
	pip install django-google-maps
	```
</details>
<details><summary><b><a href="https://github.com/simon-the-shark/django-mapbox-location-field">django-mapbox-location-field</a></b> (🥉20 ·  ⭐ 70 · 💤) - Simple in use location model and form field with MapInput widget for picking some location. Uses mapbox gl js,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/simon-the-shark/django-mapbox-location-field) (👨‍💻 8 · 🔀 22 · 📦 600 · 📋 28 - 17% open · ⏱️ 20.06.2024):

	```
	git clone https://github.com/Simon-the-Shark/django-mapbox-location-field
	```
- [PyPi](https://pypi.org/project/django-mapbox-location-field) (📥 2.4K / month):
	```
	pip install django-mapbox-location-field
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/agusmakmun/django-address-model">django-address-model</a></b> (🥉8 ·  ⭐ 14 · 💀) - django abstract model that provide the complete address, eg: no, na/rt, ca/rw, village/desa, sub district/kecamatan,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Fields (versioning)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/etianen/django-reversion">django-reversion</a></b> (🥇35 ·  ⭐ 3.1K · 📉) - django-reversion is an extension to the Django web framework that provides version control for model instances. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/etianen/django-reversion) (👨‍💻 190 · 🔀 460 · 📦 7.8K · 📋 660 - 3% open · ⏱️ 21.09.2025):

	```
	git clone https://github.com/etianen/django-reversion
	```
- [PyPi](https://pypi.org/project/django-reversion) (📥 1.1M / month):
	```
	pip install django-reversion
	```
</details>
<details><summary><b><a href="https://github.com/django-commons/django-simple-history">django-simple-history</a></b> (🥇35 ·  ⭐ 2.4K) - Store model history and view/revert changes from admin site. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-commons/django-simple-history) (👨‍💻 190 · 🔀 470 · 📥 10 · 📦 7K · 📋 620 - 24% open · ⏱️ 28.11.2025):

	```
	git clone https://github.com/jazzband/django-simple-history
	```
- [PyPi](https://pypi.org/project/django-simple-history) (📥 2.3M / month):
	```
	pip install django-simple-history
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-auditlog">django-auditlog</a></b> (🥈33 ·  ⭐ 1.3K) - A Django app that keeps a log of changes made to an object. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-auditlog) (👨‍💻 99 · 🔀 400 · 📥 510 · 📦 1.7K · 📋 320 - 25% open · ⏱️ 25.11.2025):

	```
	git clone https://github.com/jazzband/django-auditlog
	```
- [PyPi](https://pypi.org/project/django-auditlog) (📥 730K / month):
	```
	pip install django-auditlog
	```
</details>
<details><summary><b><a href="https://github.com/soynatan/django-easy-audit">django-easy-audit</a></b> (🥉24 ·  ⭐ 830) - Yet another Django audit log app, hopefully the simplest one. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/soynatan/django-easy-audit) (👨‍💻 52 · 🔀 180 · 📦 370 · 📋 160 - 50% open · ⏱️ 18.10.2025):

	```
	git clone https://github.com/soynatan/django-easy-audit
	```
- [PyPi](https://pypi.org/project/django-easy-audit) (📥 77K / month):
	```
	pip install django-easy-audit
	```
</details>
<details><summary><b><a href="https://github.com/romgar/django-dirtyfields">django-dirtyfields</a></b> (🥉24 ·  ⭐ 650) - Tracking dirty fields on a Django model. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/romgar/django-dirtyfields) (👨‍💻 44 · 🔀 95 · 📦 690 · 📋 74 - 14% open · ⏱️ 17.11.2025):

	```
	git clone https://github.com/romgar/django-dirtyfields
	```
- [PyPi](https://pypi.org/project/django-dirtyfields) (📥 490K / month):
	```
	pip install django-dirtyfields
	```
</details>
<details><summary><b><a href="https://github.com/craigds/django-fieldsignals">django-fieldsignals</a></b> (🥉16 ·  ⭐ 110 · 💤) - Django signals for changed fields. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/craigds/django-fieldsignals) (👨‍💻 5 · 🔀 11 · 📦 360 · 📋 17 - 17% open · ⏱️ 08.10.2022):

	```
	git clone https://github.com/craigds/django-fieldsignals
	```
- [PyPi](https://pypi.org/project/django-fieldsignals) (📥 43K / month):
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

- [GitHub](https://github.com/lamby/django-slack) (👨‍💻 30 · 🔀 56 · 📦 460 · 📋 63 - 14% open · ⏱️ 11.07.2025):

	```
	git clone https://github.com/lamby/django-slack
	```
- [PyPi](https://pypi.org/project/django-slack) (📥 130K / month):
	```
	pip install django-slack
	```
</details>
<details><summary><b><a href="https://github.com/stefanfoulis/django-sendsms">django-sendsms</a></b> (🥈17 ·  ⭐ 260 · 💤) - A simple API to send SMS messages. It is modeled after the django email api. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stefanfoulis/django-sendsms) (👨‍💻 19 · 🔀 87 · 📦 390 · 📋 24 - 20% open · ⏱️ 27.12.2021):

	```
	git clone https://github.com/stefanfoulis/django-sendsms
	```
- [PyPi](https://pypi.org/project/django-sendsms) (📥 7K / month):
	```
	pip install django-sendsms
	```
</details>
<details><summary><b><a href="https://github.com/roaldnefs/django-sms">django-sms</a></b> (🥉13 ·  ⭐ 58 · 💤) - A Django app for sending SMS with interchangeable backends. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/roaldnefs/django-sms) (👨‍💻 3 · 🔀 13 · 📋 16 - 43% open · ⏱️ 07.01.2024):

	```
	git clone https://github.com/roaldnefs/django-sms
	```
- [PyPi](https://pypi.org/project/django-sms) (📥 18K / month):
	```
	pip install django-sms
	```
</details>
<details><summary><b><a href="https://github.com/Ninjaclasher/django-discord-integration">django-discord-integration</a></b> (🥉8 ·  ⭐ 23 · 💤) - Discord integration for Django, supporting error reporting via webhooks. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/Ninjaclasher/django-discord-integration) (👨‍💻 2 · 🔀 1 · 📦 7 · 📋 3 - 33% open · ⏱️ 28.05.2024):

	```
	git clone https://github.com/Ninjaclasher/django-discord-integration
	```
- [PyPi](https://pypi.org/project/django-discord-integration) (📥 890 / month):
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

<details><summary><b><a href="https://github.com/jschneier/django-storages">django-storages</a></b> (🥇34 ·  ⭐ 2.9K) - https://django-storages.readthedocs.io/. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jschneier/django-storages) (👨‍💻 280 · 🔀 840 · 📦 220K · 📋 750 - 15% open · ⏱️ 18.06.2025):

	```
	git clone https://github.com/jschneier/django-storages
	```
- [PyPi](https://pypi.org/project/django-storages) (📥 6.6M / month):
	```
	pip install django-storages
	```
</details>
<details><summary><b><a href="https://github.com/py-pa/django-minio-storage">django-minio-storage</a></b> (🥉24 ·  ⭐ 160) - A django storage driver for minio. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/py-pa/django-minio-storage) (👨‍💻 18 · 🔀 55 · 📦 390 · 📋 86 - 11% open · ⏱️ 24.11.2025):

	```
	git clone https://github.com/py-pa/django-minio-storage
	```
- [PyPi](https://pypi.org/project/django-minio-storage) (📥 30K / month):
	```
	pip install django-minio-storage
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/maddevsio/django_minio">django-minio</a></b> (🥉7 ·  ⭐ 65 · 💀) - Django app to use Minio Server as file storage. <code>❗Unlicensed</code>
</details>
<br>

## Event Bus

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/openedx/event-bus-kafka">edx-event-bus-kafka</a></b> (🥇17 ·  ⭐ 7) - Kafka implementation for Open edX event bus. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
</details>
<br>

## Event Sourcing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pyeventsourcing/eventsourcing">eventsourcing</a></b> (🥇25 ·  ⭐ 1.6K) - A library for event sourcing in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyeventsourcing/eventsourcing) (👨‍💻 28 · 🔀 140 · 📦 200 · 📋 100 - 2% open · ⏱️ 05.06.2025):

	```
	git clone https://github.com/pyeventsourcing/eventsourcing
	```
- [PyPi](https://pypi.org/project/eventsourcing) (📥 63K / month):
	```
	pip install eventsourcing
	```
</details>
<details><summary><b><a href="https://github.com/pyeventsourcing/eventsourcing-django">eventsourcing-django</a></b> (🥈13 ·  ⭐ 54) - Python package for eventsourcing with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyeventsourcing/eventsourcing-django) (👨‍💻 7 · 🔀 13 · 📦 10 · 📋 5 - 60% open · ⏱️ 09.06.2025):

	```
	git clone https://github.com/pyeventsourcing/eventsourcing-django
	```
- [PyPi](https://pypi.org/project/eventsourcing-django) (📥 2.7K / month):
	```
	pip install eventsourcing-django
	```
</details>
<details><summary><b><a href="https://github.com/pyeventsourcing/eventsourcing-kurrentdb">eventsourcing-eventstoredb</a></b> (🥉6 ·  ⭐ 20) - Python package for eventsourcing with KurrentDB. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyeventsourcing/eventsourcing-kurrentdb) (👨‍💻 2 · 🔀 1 · ⏱️ 14.05.2025):

	```
	git clone https://github.com/pyeventsourcing/eventsourcing-eventstoredb
	```
- [PyPi](https://pypi.org/project/eventsourcing-eventstoredb) (📥 200 / month):
	```
	pip install eventsourcing-eventstoredb
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/pyeventsourcing/eventsourcing-dynamodb">eventsourcing-dynamodb</a></b> (🥉5 ·  ⭐ 8) - Python package for eventsourcing with DynamoDB. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pyeventsourcing/eventsourcing-axonserver">eventsourcing-axonserver</a></b> (🥉4 ·  ⭐ 3 · 💤) - Python package for eventsourcing with Axon Server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Event Streaming

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/ag2ai/faststream">FastStream</a></b> (🥇35 ·  ⭐ 4.8K) - FastStream is a powerful and easy-to-use asynchronous Python framework for building asynchronous services interacting.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ag2ai/faststream) (👨‍💻 130 · 🔀 310 · 📦 770 · 📋 880 - 10% open · ⏱️ 26.11.2025):

	```
	git clone https://github.com/ag2ai/faststream
	```
- [PyPi](https://pypi.org/project/faststream) (📥 540K / month):
	```
	pip install faststream
	```
</details>
<br>

## Locking

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/saxix/django-concurrency">django-concurrency</a></b> (🥇23 ·  ⭐ 460) - Optimistic lock implementation for Django. Prevents users from doing concurrent editing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/saxix/django-concurrency) (👨‍💻 27 · 🔀 51 · 📦 210 · 📋 77 - 1% open · ⏱️ 20.07.2025):

	```
	git clone https://github.com/saxix/django-concurrency
	```
- [PyPi](https://pypi.org/project/django-concurrency) (📥 110K / month):
	```
	pip install django-concurrency
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/gavinwahl/django-optimistic-lock">django-optimistic-lock</a></b> (🥉13 ·  ⭐ 120 · 💀) - Offline optimistic locking for Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/debrouwere/django-locking">django-locking</a></b> (🥉8 ·  ⭐ 140 · 💀) - Prevents users from doing concurrent editing in Django. Works out of the box in the admin interface, or you can.. <code>❗Unlicensed</code>
</details>
<br>

## Example data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/Brobin/django-seed">django-seed</a></b> (🥇25 ·  ⭐ 710 · 💤) - Seed your Django database with fake data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Brobin/django-seed) (👨‍💻 23 · 🔀 82 · 📦 5.3K · 📋 62 - 32% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/brobin/django-seed
	```
- [PyPi](https://pypi.org/project/django-seed) (📥 27K / month):
	```
	pip install django-seed
	```
</details>
<details><summary><b><a href="https://github.com/davedash/django-fixture-magic">django-fixture-magic</a></b> (🥉19 ·  ⭐ 390 · 💤) - Utilities to extract and manipulate Django Fixtures. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/davedash/django-fixture-magic) (👨‍💻 36 · 🔀 90 · 📦 180 · 📋 35 - 34% open · ⏱️ 26.10.2023):

	```
	git clone https://github.com/davedash/django-fixture-magic
	```
- [PyPi](https://pypi.org/project/django-fixture-magic) (📥 21K / month):
	```
	pip install django-fixture-magic
	```
</details>
<details><summary><b><a href="https://github.com/klen/mixer">mixer</a></b> (🥉16 ·  ⭐ 950 · 💤) - Mixer -- Is a fixtures replacement. Supported Django, Flask, SqlAlchemy and custom python objects. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/klen/mixer) (👨‍💻 43 · 🔀 92 · 📋 87 - 43% open · ⏱️ 23.03.2022):

	```
	git clone https://github.com/klen/mixer
	```
- [PyPi](https://pypi.org/project/mixer) (📥 200K / month):
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

<details><summary><b><a href="https://github.com/model-bakers/model_bakery">model-bakery</a></b> (🥇21 ·  ⭐ 950) - Object factory for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/model-bakers/model_bakery) (👨‍💻 63 · 🔀 97 · 📋 160 - 17% open · ⏱️ 31.10.2025):

	```
	git clone https://github.com/model-bakers/model_bakery
	```
- [PyPi](https://pypi.org/project/model-bakery/) (📥 1.3M / month):
	```
	pip install model-bakery/
	```
</details>
<details><summary><b><a href="https://github.com/paulocheque/django-dynamic-fixture">django-dynamic-fixture</a></b> (🥇21 ·  ⭐ 390 · 💤) - A complete library to create dynamic model instances for testing purposes. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/paulocheque/django-dynamic-fixture) (👨‍💻 37 · 🔀 63 · 📦 1.3K · 📋 71 - 9% open · ⏱️ 10.10.2024):

	```
	git clone https://github.com/paulocheque/django-dynamic-fixture
	```
- [PyPi](https://pypi.org/project/django-dynamic-fixture) (📥 97K / month):
	```
	pip install django-dynamic-fixture
	```
</details>
<br>

## Bootstrap CSS Framework Integration (Django MVT application)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/zostera/django-bootstrap4">django-bootstrap4</a></b> (🥇33 ·  ⭐ 1K) - Bootstrap 4 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap4) (👨‍💻 140 · 🔀 220 · 📦 190K · 📋 160 - 10% open · ⏱️ 17.11.2025):

	```
	git clone https://github.com/zostera/django-bootstrap4
	```
- [PyPi](https://pypi.org/project/django-bootstrap4) (📥 380K / month):
	```
	pip install django-bootstrap4
	```
</details>
<details><summary><b><a href="https://github.com/zostera/django-bootstrap3">django-bootstrap3</a></b> (🥈32 ·  ⭐ 2.3K) - Bootstrap 3 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap3) (👨‍💻 100 · 🔀 670 · 📦 19K · ⏱️ 17.11.2025):

	```
	git clone https://github.com/zostera/django-bootstrap3
	```
- [PyPi](https://pypi.org/project/django-bootstrap3) (📥 370K / month):
	```
	pip install django-bootstrap3
	```
</details>
<details><summary><b><a href="https://github.com/zostera/django-bootstrap5">django-bootstrap5</a></b> (🥉28 ·  ⭐ 440) - Bootstrap 5 for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap5) (👨‍💻 150 · 🔀 90 · 📦 10K · 📋 110 - 35% open · ⏱️ 17.11.2025):

	```
	git clone https://github.com/zostera/django-bootstrap5
	```
- [PyPi](https://pypi.org/project/django-bootstrap5) (📥 310K / month):
	```
	pip install django-bootstrap5
	```
</details>
<details><summary><b><a href="https://github.com/zelenij/django-bootstrap-v5">django-bootstrap-v5</a></b> (🥉21 ·  ⭐ 100 · 💤) - Bootstrap 5 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zelenij/django-bootstrap-v5) (👨‍💻 140 · 🔀 41 · 📦 10K · 📋 24 - 33% open · ⏱️ 07.01.2024):

	```
	git clone https://github.com/zelenij/django-bootstrap-v5
	```
- [PyPi](https://pypi.org/project/django-bootstrap-v5) (📥 59K / month):
	```
	pip install django-bootstrap-v5
	```
</details>
<br>

## Bulma CSS Framework Integration (Django MVT application)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/timonweb/django-bulma">django-bulma</a></b> (🥇18 ·  ⭐ 350) - Bulma theme for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timonweb/django-bulma) (👨‍💻 15 · 🔀 56 · 📦 540 · 📋 44 - 6% open · ⏱️ 05.11.2025):

	```
	git clone https://github.com/timonweb/django-bulma
	```
- [PyPi](https://pypi.org/project/django-bulma) (📥 5.1K / month):
	```
	pip install django-bulma
	```
</details>
<br>

## TailwindCSS CSS Framework Integration (Django MVT application)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/timonweb/django-tailwind">django-tailwind</a></b> (🥇28 ·  ⭐ 1.7K) - Django + Tailwind CSS =. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timonweb/django-tailwind) (👨‍💻 25 · 🔀 110 · 📦 7K · 📋 180 - 1% open · ⏱️ 13.11.2025):

	```
	git clone https://github.com/timonweb/django-tailwind
	```
- [PyPi](https://pypi.org/project/django-tailwind) (📥 210K / month):
	```
	pip install django-tailwind
	```
</details>
<details><summary><b><a href="https://github.com/django-commons/django-tailwind-cli">django-tailwind-cli</a></b> (🥉23 ·  ⭐ 180) - Django and Tailwind integration based on the prebuilt Tailwind CSS CLI. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-commons/django-tailwind-cli) (👨‍💻 16 · 🔀 18 · 📥 120 · 📦 75 · 📋 42 - 4% open · ⏱️ 16.11.2025):

	```
	git clone https://github.com/oliverandrich/django-tailwind-cli
	```
- [PyPi](https://pypi.org/project/django-tailwind-cli) (📥 9.3K / month):
	```
	pip install django-tailwind-cli
	```
</details>
<details><summary><b><a href="https://github.com/timonweb/pytailwindcss">pytailwindcss</a></b> (🥉18 ·  ⭐ 340) - Skip Node.js use Tailwind CSS installed directly via PyPI. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timonweb/pytailwindcss) (👨‍💻 3 · 🔀 10 · 📦 470 · 📋 13 - 7% open · ⏱️ 29.10.2025):

	```
	git clone https://github.com/timonweb/pytailwindcss
	```
- [PyPi](https://pypi.org/project/pytailwindcss) (📥 52K / month):
	```
	pip install pytailwindcss
	```
</details>
<br>

## Data exploration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/tolomea/django-data-browser">django-data-browser</a></b> (🥇18 ·  ⭐ 370) - Django app for user friendly querying of Django models. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/tolomea/django-data-browser) (👨‍💻 10 · 🔀 27 · 📦 42 · 📋 39 - 17% open · ⏱️ 30.11.2025):

	```
	git clone https://github.com/tolomea/django-data-browser
	```
- [PyPi](https://pypi.org/project/django-data-browser) (📥 4.6K / month):
	```
	pip install django-data-browser
	```
</details>
<br>

## Multiple tenants

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-tenants/django-tenants">django-tenants</a></b> (🥇33 ·  ⭐ 1.8K) - Django tenants using PostgreSQL Schemas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-tenants/django-tenants) (👨‍💻 120 · 🔀 380 · 📦 1.3K · 📋 710 - 35% open · ⏱️ 19.10.2025):

	```
	git clone https://github.com/django-tenants/django-tenants
	```
- [PyPi](https://pypi.org/project/django-tenants) (📥 360K / month):
	```
	pip install django-tenants
	```
</details>
<details><summary><b><a href="https://github.com/bernardopires/django-tenant-schemas">django-tenant-schemas</a></b> (🥈28 ·  ⭐ 1.5K) - Tenant support for Django using PostgreSQL schemas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bernardopires/django-tenant-schemas) (👨‍💻 76 · 🔀 400 · 📦 480 · 📋 480 - 25% open · ⏱️ 26.09.2025):

	```
	git clone https://github.com/bernardopires/django-tenant-schemas
	```
- [PyPi](https://pypi.org/project/django-tenant-schemas) (📥 25K / month):
	```
	pip install django-tenant-schemas
	```
</details>
<details><summary><b><a href="https://github.com/citusdata/django-multitenant">django-multitenant</a></b> (🥉26 ·  ⭐ 800) - Python/Django support for distributed multi-tenant databases like Postgres+Citus. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/citusdata/django-multitenant) (👨‍💻 28 · 🔀 120 · 📦 85 · 📋 99 - 43% open · ⏱️ 17.11.2025):

	```
	git clone https://github.com/citusdata/django-multitenant
	```
- [PyPi](https://pypi.org/project/django-multitenant) (📥 68K / month):
	```
	pip install django-multitenant
	```
</details>
<details><summary><b><a href="https://github.com/raphaelm/django-scopes">django-scopes</a></b> (🥉16 ·  ⭐ 250) - Safely separate multiple tenants in a Django database. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/raphaelm/django-scopes) (👨‍💻 6 · 🔀 15 · 📦 120 · 📋 20 - 65% open · ⏱️ 31.10.2025):

	```
	git clone https://github.com/raphaelm/django-scopes
	```
- [PyPi](https://pypi.org/project/django-scopes) (📥 19K / month):
	```
	pip install django-scopes
	```
</details>
<br>

## Notifications

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-notifications/django-notifications">django-notifications</a></b> (🥇29 ·  ⭐ 1.9K) - GitHub notifications alike app for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-notifications/django-notifications) (👨‍💻 76 · 🔀 440 · 📦 3.1K · 📋 220 - 9% open · ⏱️ 17.07.2025):

	```
	git clone https://github.com/django-notifications/django-notifications
	```
- [PyPi](https://pypi.org/project/django-notifications-hq) (📥 65K / month):
	```
	pip install django-notifications-hq
	```
</details>
<br>

## Value-as-a-Service frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_SaaS frameworks, subscription-based tutorials etc. which use Django under the hood._

<details><summary><b><a href="https://github.com/djaodjin/djaodjin-saas">djaodjin-saas</a></b> (🥇18 ·  ⭐ 600) - Django application for software-as-service and subscription businesses. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/djaodjin/djaodjin-saas) (👨‍💻 14 · 🔀 130 · 📦 12 · 📋 110 - 12% open · ⏱️ 26.11.2025):

	```
	git clone https://github.com/djaodjin/djaodjin-saas
	```
- [PyPi](https://pypi.org/project/djaodjin-saas) (📥 580 / month):
	```
	pip install djaodjin-saas
	```
</details>
<br>

## Payment and Subscription (Stripe, etc.)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/dj-stripe/dj-stripe">dj-stripe</a></b> (🥇33 ·  ⭐ 1.8K) - dj-stripe automatically syncs your Stripe Data to your local database as pre-implemented Django Models allowing you to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dj-stripe/dj-stripe) (👨‍💻 130 · 🔀 490 · 📦 1.2K · 📋 1.1K - 6% open · ⏱️ 15.10.2025):

	```
	git clone https://github.com/dj-stripe/dj-stripe
	```
- [PyPi](https://pypi.org/project/dj-stripe) (📥 160K / month):
	```
	pip install dj-stripe
	```
</details>
<details><summary><b><a href="https://github.com/spookylukey/django-paypal">django-paypal</a></b> (🥇27 ·  ⭐ 730 · 💤) - A pluggable Django application for integrating PayPal Payments Standard or Payments Pro. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/spookylukey/django-paypal) (👨‍💻 73 · 🔀 200 · 📦 4.2K · 📋 170 - 8% open · ⏱️ 18.11.2024):

	```
	git clone https://github.com/spookylukey/django-paypal
	```
- [PyPi](https://pypi.org/project/django-paypal) (📥 34K / month):
	```
	pip install django-paypal
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-payments">django-payments</a></b> (🥈26 ·  ⭐ 1.2K) - Universal payment handling for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jazzband/django-payments) (👨‍💻 71 · 🔀 290 · 📥 33 · 📦 660 · 📋 190 - 37% open · ⏱️ 23.10.2025):

	```
	git clone https://github.com/jazzband/django-payments
	```
- [PyPi](https://pypi.org/project/django-payments) (📥 12K / month):
	```
	pip install django-payments
	```
</details>
<details><summary><b><a href="https://github.com/django-getpaid/django-getpaid">django-getpaid</a></b> (🥈21 ·  ⭐ 450) - Django payments processor. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-getpaid/django-getpaid) (👨‍💻 31 · 🔀 100 · 📦 49 · 📋 62 - 6% open · ⏱️ 12.03.2025):

	```
	git clone https://github.com/django-getpaid/django-getpaid
	```
- [PyPi](https://pypi.org/project/django-getpaid) (📥 6.8K / month):
	```
	pip install django-getpaid
	```
</details>
<details><summary><b><a href="https://github.com/django-oscar/django-oscar-paypal">django-oscar-paypal</a></b> (🥈21 ·  ⭐ 160) - PayPal integration for django-oscar. Can be used without Oscar too. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-oscar/django-oscar-paypal) (👨‍💻 51 · 🔀 200 · 📦 160 · 📋 93 - 25% open · ⏱️ 01.09.2025):

	```
	git clone https://github.com/django-oscar/django-oscar-paypal
	```
- [PyPi](https://pypi.org/project/django-oscar-paypal) (📥 1.8K / month):
	```
	pip install django-oscar-paypal
	```
</details>
<details><summary><b><a href="https://github.com/pinax/pinax-stripe-light">pinax-stripe-light</a></b> (🥈20 ·  ⭐ 690 · 💤) - a payments Django app for Stripe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pinax/pinax-stripe-light) (👨‍💻 72 · 🔀 270 · 📋 300 - 22% open · ⏱️ 28.11.2021):

	```
	git clone https://github.com/pinax/pinax-stripe-light
	```
- [PyPi](https://pypi.org/project/pinax-stripe-light) (📥 60 / month):
	```
	pip install pinax-stripe-light
	```
</details>
<details><summary><b><a href="https://github.com/silverapp/silver">silver</a></b> (🥈16 ·  ⭐ 310) - Automated billing and payments for Django with a REST API. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/silverapp/silver) (👨‍💻 24 · 🔀 80 · 📦 11 · 📋 390 - 13% open · ⏱️ 04.08.2025):

	```
	git clone https://github.com/silverapp/silver
	```
- [PyPi](https://pypi.org/project/silver) (📥 58 / month):
	```
	pip install silver
	```
</details>
<details><summary><b><a href="https://github.com/kogan/django-subscriptions">django-subscriptions</a></b> (🥈16 ·  ⭐ 74 · 💤) - A django package for managing subscription states. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/kogan/django-subscriptions) (👨‍💻 2 · 🔀 9 · 📦 19 · ⏱️ 29.12.2020):

	```
	git clone https://github.com/kogan/django-subscriptions
	```
- [PyPi](https://pypi.org/project/django-subscriptions) (📥 15K / month):
	```
	pip install django-subscriptions
	```
</details>
<details><summary><b><a href="https://github.com/HearthSim/dj-paypal">dj-paypal</a></b> (🥉15 ·  ⭐ 89) - Paypal integration for Django - Inspired by dj-Stripe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HearthSim/dj-paypal) (👨‍💻 3 · 🔀 20 · 📦 28 · 📋 9 - 44% open · ⏱️ 10.03.2025):

	```
	git clone https://github.com/HearthSim/dj-paypal
	```
- [PyPi](https://pypi.org/project/dj-paypal) (📥 150 / month):
	```
	pip install dj-paypal
	```
</details>
<details><summary><b><a href="https://github.com/bdelate/django-flutterwave">django-flutterwave</a></b> (🥉13 ·  ⭐ 23 · 💤) - Django integration for Flutterwave Rave payments and subscriptions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bdelate/django-flutterwave) (🔀 12 · 📦 54 · ⏱️ 29.12.2020):

	```
	git clone https://github.com/bdelate/django-flutterwave
	```
- [PyPi](https://pypi.org/project/django-flutterwave):
	```
	pip install django-flutterwave
	```
</details>
<details><summary><b><a href="https://github.com/oscarychen/drf-stripe-subscription">drf-stripe-subscription</a></b> (🥉12 ·  ⭐ 120) - An out-of-box Django REST framework solution for payment and subscription management using Stripe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oscarychen/drf-stripe-subscription) (👨‍💻 7 · 🔀 19 · 📋 25 - 20% open · ⏱️ 20.08.2025):

	```
	git clone https://github.com/oscarychen/drf-stripe-subscription
	```
- [PyPi](https://pypi.org/project/drf-stripe-subscription) (📥 790 / month):
	```
	pip install drf-stripe-subscription
	```
</details>
<details><summary><b><a href="https://github.com/paddle-python/dj-paddle">dj-paddle</a></b> (🥉12 ·  ⭐ 84 · 💤) - Django + Paddle made Easy!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/paddle-python/dj-paddle) (👨‍💻 7 · 🔀 33 · 📋 25 - 56% open · ⏱️ 26.03.2021):

	```
	git clone https://github.com/paddle-python/dj-paddle
	```
- [PyPi](https://pypi.org/project/dj-paddle) (📥 47 / month):
	```
	pip install dj-paddle
	```
</details>
<details><summary><b><a href="https://github.com/duplxey/django-stripe-subscriptions">django-stripe-subscriptions</a></b> (🥉7 ·  ⭐ 34 · 💤) - How to handle subscription payments with Django and Stripe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/duplxey/django-stripe-subscriptions) (👨‍💻 3 · 🔀 12 · 📋 4 - 75% open · ⏱️ 20.07.2022):

	```
	git clone https://github.com/duplxey/django-stripe-subscriptions
	```
- [PyPi](https://pypi.org/project/django-stripe-subscriptions):
	```
	pip install django-stripe-subscriptions
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/agiliq/merchant">merchant</a></b> (🥈18 ·  ⭐ 1K · 💀) - A Django app to accept payments from various payment processors via Pluggable backends. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/studybuffalo/django-flexible-subscriptions">django-flexible-subscriptions</a></b> (🥉15 ·  ⭐ 250 · 💀) - A subscription and recurrent billing application for Django. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/kangasbros/django-bitcoin">django-bitcoin</a></b> (🥉15 ·  ⭐ 180 · 💀) - bitcoin payment management for django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/andrew-kurin/django-authorizenet">django-authorizenet</a></b> (🥉12 ·  ⭐ 86 · 💀) - Django and Authorize.NET payment gateway integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/zhaque/django-subscription">django-subscription</a></b> (🥉9 ·  ⭐ 190 · 💀) - Subscriptions or Recurring Billing App for django. <code>❗Unlicensed</code>
- <b><a href="https://github.com/vporton/django-payee">django-payee</a></b> (🥉3 ·  ⭐ 2) - Accept (regular and subscription) payments in Internet (currently supports PayPal). Advanced support for subscription.. <code>❗Unlicensed</code>
</details>
<br>

## Emails

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/anymail/django-anymail">django-anymail</a></b> (🥇29 ·  ⭐ 1.8K) - Django email backends and webhooks for Amazon SES, Brevo (Sendinblue), MailerSend, Mailgun, Mailjet, Postmark, Postal,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anymail/django-anymail) (👨‍💻 69 · 🔀 140 · 📥 230 · 📦 7.9K · 📋 240 - 2% open · ⏱️ 03.09.2025):

	```
	git clone https://github.com/anymail/django-anymail
	```
- [PyPi](https://pypi.org/project/django-anymail) (📥 1.3M / month):
	```
	pip install django-anymail
	```
</details>
<details><summary><b><a href="https://github.com/django-ses/django-ses">django-ses</a></b> (🥈28 ·  ⭐ 1.1K) - A Django email backend for Amazons Simple Email Service. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-ses/django-ses) (👨‍💻 85 · 🔀 220 · 📦 3.6K · 📋 150 - 33% open · ⏱️ 06.11.2025):

	```
	git clone https://github.com/django-ses/django-ses
	```
- [PyPi](https://pypi.org/project/django-ses) (📥 880K / month):
	```
	pip install django-ses
	```
</details>
<details><summary><b><a href="https://github.com/ui/django-post_office">django-post-office</a></b> (🥉27 ·  ⭐ 1.1K) - A Django app that allows you to send email asynchronously in Django. Supports HTML email, database backed templates.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ui/django-post_office) (👨‍💻 86 · 🔀 250 · 📦 110 · 📋 260 - 35% open · ⏱️ 30.11.2025):

	```
	git clone https://github.com/ui/django-post_office
	```
- [PyPi](https://pypi.org/project/django-post-office) (📥 85K / month):
	```
	pip install django-post-office
	```
</details>
<details><summary><b><a href="https://github.com/coddingtonbear/django-mailbox">django-mailbox</a></b> (🥉23 ·  ⭐ 380) - Import mail from POP3, IMAP, local email mailboxes or directly from Postfix or Exim4 into your Django application.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coddingtonbear/django-mailbox) (👨‍💻 55 · 🔀 160 · 📦 230 · 📋 160 - 12% open · ⏱️ 20.06.2025):

	```
	git clone https://github.com/coddingtonbear/django-mailbox
	```
- [PyPi](https://pypi.org/project/django-mailbox) (📥 18K / month):
	```
	pip install django-mailbox
	```
</details>
<details><summary><b><a href="https://github.com/aio-libs/aiosmtpd">aiosmtpd</a></b> (🥉21 ·  ⭐ 360) - A reimplementation of the Python stdlib smtpd.py based on asyncio. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aio-libs/aiosmtpd) (👨‍💻 45 · 🔀 97 · 📥 630 · 📋 180 - 38% open · ⏱️ 18.06.2025):

	```
	git clone https://github.com/aio-libs/aiosmtpd
	```
- [PyPi](https://pypi.org/project/aiosmtpd) (📥 470K / month):
	```
	pip install aiosmtpd
	```
</details>
<br>

## Templates

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-components/django-components">django-components</a></b> (🥇27 ·  ⭐ 1.5K) - Create simple reusable template components in Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-components/django-components) (👨‍💻 55 · 🔀 100 · 📋 350 - 23% open · ⏱️ 25.11.2025):

	```
	git clone https://github.com/django-components/django-components
	```
- [PyPi](https://pypi.org/project/django-components) (📥 64K / month):
	```
	pip install django-components
	```
</details>
<details><summary><b><a href="https://github.com/wrabit/django-cotton">wrabit/django-cotton</a></b> (🥇27 ·  ⭐ 1K) - Enabling Modern UI Composition in Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wrabit/django-cotton) (👨‍💻 14 · 🔀 47 · 📦 290 · 📋 110 - 0% open · ⏱️ 20.11.2025):

	```
	git clone https://github.com/wrabit/django-cotton
	```
- [PyPi](https://pypi.org/project/django-cotton) (📥 92K / month):
	```
	pip install django-cotton
	```
</details>
<details><summary><b><a href="https://github.com/django-compressor/django-compressor">django-compressor</a></b> (🥈25 ·  ⭐ 2.9K) - Compresses linked and inline javascript or CSS into a single cached file. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-compressor/django-compressor) (👨‍💻 220 · 🔀 570 · 📋 670 - 17% open · ⏱️ 10.11.2025):

	```
	git clone https://github.com/django-compressor/django-compressor
	```
- [PyPi](https://pypi.org/project/django-compressor) (📥 1.4M / month):
	```
	pip install django-compressor
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/django-htmx">django-htmx</a></b> (🥉24 ·  ⭐ 1.9K) - Extensions for using Django with htmx. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/adamchainz/django-htmx) (👨‍💻 25 · 🔀 150 · 📋 92 - 6% open · ⏱️ 28.11.2025):

	```
	git clone https://github.com/adamchainz/django-htmx
	```
- [PyPi](https://pypi.org/project/django-htmx) (📥 600K / month):
	```
	pip install django-htmx
	```
</details>
<details><summary><b><a href="https://github.com/carltongibson/django-template-partials">django-template-partials</a></b> (🥉21 ·  ⭐ 640) - Reusable named inline partials for the Django Template Language. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carltongibson/django-template-partials) (👨‍💻 19 · 🔀 33 · 📦 370 · ⏱️ 14.11.2025):

	```
	git clone https://github.com/carltongibson/django-template-partials
	```
- [PyPi](https://pypi.org/project/django-template-partials) (📥 110K / month):
	```
	pip install django-template-partials
	```
</details>
<details><summary><b><a href="https://github.com/inertiajs/inertia-django">inertia-django</a></b> (🥉19 ·  ⭐ 510) - The Django adapter for Inertia.js. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inertiajs/inertia-django) (👨‍💻 17 · 🔀 47 · 📦 150 · 📋 43 - 11% open · ⏱️ 05.10.2025):

	```
	git clone https://github.com/inertiajs/inertia-django
	```
- [PyPi](https://pypi.org/project/inertia-django) (📥 20K / month):
	```
	pip install inertia-django
	```
</details>
<br>

## Reusable app templates

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/wemake-services/wemake-django-template">wemake-django-template</a></b> (🥇22 ·  ⭐ 2.2K) - Bleeding edge django template focused on code quality and security. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/wemake-django-template) (👨‍💻 56 · 🔀 220 · 📋 550 - 4% open · ⏱️ 24.11.2025):

	```
	git clone https://github.com/wemake-services/wemake-django-template
	```
</details>
<details><summary><b><a href="https://github.com/wq/wq-django-template">wq-django-template</a></b> (🥈10 ·  ⭐ 28 · 💤) - Django + NPM (Create React App) template for building REST-ful web & hybrid apps with the wq framework. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/wq/wq-django-template) (👨‍💻 4 · 🔀 7 · ⏱️ 27.03.2024):

	```
	git clone https://github.com/wq/wq-django-template
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/pydanny/cookiecutter-djangopackage">cookiecutter-djangopackage</a></b> (🥇13 ·  ⭐ 440 · 💀) - A cookiecutter template for creating reusable Django packages quickly. <code>❗Unlicensed</code>
- <b><a href="https://github.com/wildfish/cookiecutter-django-crud">cookiecutter-django-crud</a></b> (🥈9 ·  ⭐ 68 · 💀) - A cookiecutter template to create a Django app around a model with CRUD views using django-vanilla-views, a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/edx/cookiecutter-django-app">cookiecutter-django-app</a></b> (🥈9 ·  ⭐ 16 · 💀) - A cookiecutter template for creating reusable Django packages (installable apps) quickly. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mlavin/django-app-template">django-app-template</a></b> (🥉7 ·  ⭐ 54 · 💀) - A handy template for creating a new reusable Django application. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/bitlabstudio/django-reusable-app-template">django-reusable-app-template</a></b> (🥉6 ·  ⭐ 97 · 💀) - A template for kickstarting reusable Django apps, ready to be published on pypi.python.org, ready for test driven.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/AmbitionEng/python-library-template">python-library-template</a></b> (🥉5 ·  ⭐ 5) - The template for all public libraries by Ambition. <code>❗Unlicensed</code>
- <b><a href="https://github.com/AndreGuerra123/django-reusable-app">django-reusable-app</a></b> (🥉4 ·  ⭐ 3 · 💀) - A cookiecutter template to package Django Reusable Apps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/KryptedGaming/django-package-template">django-package-template</a></b> (🥉4 ·  ⭐ 1 · 💤) - Template for creating packages. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/sveetch/cookiecutter-sveetch-djangoapp">cookiecutter-sveetch-djangoapp</a></b> (🥉3 ·  ⭐ 3) - Yet another Cookiecutter template to produce a repository to start a Django application package with Python3. <code>❗Unlicensed</code>
</details>
<br>

## Project templates

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/vintasoftware/django-react-boilerplate">django-react-boilerplate</a></b> (🥇20 ·  ⭐ 2.2K) - Django 5, React, Tailwind 4 with Python 3 and Webpack project boilerplate. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vintasoftware/django-react-boilerplate) (👨‍💻 54 · 🔀 540 · 📋 300 - 7% open · ⏱️ 20.10.2025):

	```
	git clone https://github.com/vintasoftware/django-react-boilerplate
	```
</details>
<details><summary><b><a href="https://github.com/apptension/saas-boilerplate">saas-boilerplate</a></b> (🥇19 ·  ⭐ 2.7K) - SaaS Boilerplate - Open Source and free SaaS stack that lets you build SaaS products faster in React, Django and AWS... <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/apptension/saas-boilerplate) (👨‍💻 41 · 🔀 380 · 📋 200 - 23% open · ⏱️ 09.03.2025):

	```
	git clone https://github.com/apptension/saas-boilerplate
	```
</details>
<details><summary><b><a href="https://github.com/wsvincent/lithium">Lithium</a></b> (🥈14 ·  ⭐ 2.4K) - Django starter project with. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/wsvincent/lithium) (👨‍💻 24 · 🔀 430 · 📋 47 - 8% open · ⏱️ 19.09.2025):

	```
	git clone https://github.com/wsvincent/lithium
	```
</details>
<details><summary><b><a href="https://github.com/falcopackages/falco-cli">falco</a></b> (🥈14 ·  ⭐ 390) - Enhance your Django developer experience: CLI and Guides for the Modern Django Developer. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/falcopackages/falco-cli) (👨‍💻 8 · 🔀 20 · 📦 16 · 📋 70 - 10% open · ⏱️ 31.12.2024):

	```
	git clone https://github.com/Tobi-De/falco
	```
- [PyPi](https://pypi.org/project/falco) (📥 93 / month):
	```
	pip install falco
	```
</details>
<details><summary><b><a href="https://github.com/Healthlane-Technologies/Zango">Zango</a></b> (🥈13 ·  ⭐ 340) - Django meta-framework for building enterprise-ready custom business applications. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Healthlane-Technologies/Zango) (👨‍💻 15 · 🔀 64 · 📦 6 · 📋 53 - 47% open · ⏱️ 05.11.2025):

	```
	git clone https://github.com/Healthlane-Technologies/Zango
	```
</details>
<details><summary><b><a href="https://github.com/jefftriplett/django-startproject">django-startproject</a></b> (🥈13 ·  ⭐ 270) - Django Start Project template with batteries. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jefftriplett/django-startproject) (👨‍💻 3 · 🔀 24 · 📋 4 - 25% open · ⏱️ 06.11.2025):

	```
	git clone https://github.com/jefftriplett/django-startproject
	```
</details>
<details><summary><b><a href="https://github.com/ilikerobots/cookiecutter-vue-django">cookiecutter-vue-django</a></b> (🥈13 ·  ⭐ 230 · 💤) - Vue 3 + Vite + Django with no compromises. Use Vue SFCs directly in Django Templates, DRF not required. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ilikerobots/cookiecutter-vue-django) (👨‍💻 400 · 🔀 25 · 📋 15 - 26% open · ⏱️ 20.11.2023):

	```
	git clone https://github.com/ilikerobots/cookiecutter-vue-django
	```
</details>
<details><summary><b><a href="https://github.com/thorgate/django-project-template">django-project-template</a></b> (🥉11 ·  ⭐ 130) - Thorgates Django project template - Django, React, Sass, optional Docker and more. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/thorgate/django-project-template) (👨‍💻 34 · 🔀 16 · 📋 5 - 40% open · ⏱️ 17.04.2025):

	```
	git clone https://github.com/thorgate/django-project-template
	```
</details>
<details><summary><b><a href="https://github.com/jayfk/launchr">launchr</a></b> (🥉10 ·  ⭐ 240 · 💤) - Launchr is an open source SaaS starter kit, based on Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jayfk/launchr) (🔀 41 · 📋 25 - 8% open · ⏱️ 23.01.2021):

	```
	git clone https://github.com/jayfk/launchr
	```
</details>
<details><summary><b><a href="https://github.com/stribny/sidewinder">sidewinder</a></b> (🥉10 ·  ⭐ 230 · 📉) - Django starter kit that focuses on good defaults, developer experience, and deployment. Updated for Django 5.2. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stribny/sidewinder) (🔀 17 · 📋 30 - 16% open · ⏱️ 04.09.2025):

	```
	git clone https://github.com/stribny/sidewinder
	```
</details>
<details><summary><b><a href="https://github.com/amerkurev/django-docker-template">django-docker-template</a></b> (🥉10 ·  ⭐ 220) - Dockerized Django with Postgres, Gunicorn, and Traefik or Caddy (with auto renew Lets Encrypt). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amerkurev/django-docker-template) (👨‍💻 6 · 🔀 43 · 📋 12 - 25% open · ⏱️ 01.04.2025):

	```
	git clone https://github.com/amerkurev/django-docker-template
	```
</details>
<details><summary><b><a href="https://github.com/gone/django-hydra">django-hydra</a></b> (🥉9 ·  ⭐ 97) - A django/htmx/alpine/tailwind project template. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gone/django-hydra) (👨‍💻 39 · 🔀 10 · 📋 16 - 18% open · ⏱️ 28.01.2025):

	```
	git clone https://github.com/Lightmatter/django-hydra
	```
</details>
<details><summary><b><a href="https://github.com/Alex-CodeLab/django-base-template">django-base-template</a></b> (🥉6 ·  ⭐ 70 · 💤) - Project Template for Django + Bootstrap3 + pre-configured apps (like Allauth, django_compressor ). Probably the.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Alex-CodeLab/django-base-template) (👨‍💻 3 · 🔀 19 · ⏱️ 30.06.2023):

	```
	git clone https://github.com/Alex-CodeLab/django-base-template
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/jpbruinsslot/docker-django">docker-django</a></b> (🥉10 ·  ⭐ 180 · 💀) - A project to get you started with Docker and Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/erayerdin/sos-django-template">sos-django-template</a></b> (🥉8 ·  ⭐ 24 · 💤) - SOS Django Template is a starter template for new Django projects with modern defaults, power cable included. <code><a href="https://tldrlegal.com/search?q=WTFPL">❗️WTFPL</a></code>
- <b><a href="https://github.com/khadegd/django-webpack-starter">django-webpack-starter</a></b> (🥉7 ·  ⭐ 59 · 💀) - Django Webpack starter template for using Webpack 5 with Django 3.1 & Bootstrap 4. Yes, it can hot-reload. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/bfirsh/django-docker-heroku-template">django-docker-heroku-template</a></b> (🥉2 ·  ⭐ 36 · 💤) - Get a Django app up and running in dev, test, and production with best practices in 10 minutes. <code>❗Unlicensed</code>
- <b><a href="https://github.com/digipodium/django-bootstrap-htmx-template-2023">django-bootstrap-htmx-template-2023</a></b> ( ⭐ 2 · 💤) - Django Website Template 2023 is a ready-to-use template for building websites using Django, Bootstrap 5, and Htmx. <code>❗Unlicensed</code>
</details>
<br>

## Static file serving

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/evansd/whitenoise">whitenoise</a></b> (🥇34 ·  ⭐ 2.7K) - Radically simplified static file serving for Python web apps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/evansd/whitenoise) (👨‍💻 70 · 🔀 150 · 📦 530K · 📋 250 - 10% open · ⏱️ 26.11.2025):

	```
	git clone https://github.com/evansd/whitenoise
	```
- [PyPi](https://pypi.org/project/whitenoise) (📥 6.5M / month):
	```
	pip install whitenoise
	```
</details>
<br>

## Custom user

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/fusionbox/django-authtools">django-authtools</a></b> (🥇23 ·  ⭐ 370) - A custom User model for everybody!. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/fusionbox/django-authtools) (👨‍💻 33 · 🔀 94 · 📦 1K · 📋 55 - 14% open · ⏱️ 29.09.2025):

	```
	git clone https://github.com/fusionbox/django-authtools
	```
- [PyPi](https://pypi.org/project/django-authtools) (📥 18K / month):
	```
	pip install django-authtools
	```
</details>
<details><summary><b><a href="https://github.com/jcugat/django-custom-user">django-custom-user</a></b> (🥈19 ·  ⭐ 320 · 💤) - Custom user model for Django with the same behaviour as the default User class but with email instead of username. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jcugat/django-custom-user) (👨‍💻 12 · 🔀 59 · 📦 290 · 📋 24 - 4% open · ⏱️ 09.12.2022):

	```
	git clone https://github.com/jcugat/django-custom-user
	```
- [PyPi](https://pypi.org/project/django-custom-user) (📥 32K / month):
	```
	pip install django-custom-user
	```
</details>
<details><summary><b><a href="https://github.com/jambonrose/django-improved-user">django-improved-user</a></b> (🥉17 ·  ⭐ 160 · 💤) - A custom Django user that authenticates via email. Follows identity and authentication best practices. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jambonrose/django-improved-user) (👨‍💻 8 · 🔀 14 · 📦 44 · 📋 11 - 9% open · ⏱️ 08.08.2024):

	```
	git clone https://github.com/jambonsw/django-improved-user
	```
- [PyPi](https://pypi.org/project/django-improved-user) (📥 1.8K / month):
	```
	pip install django-improved-user
	```
</details>
<details><summary><b><a href="https://github.com/jmfederico/django-use-email-as-username">django-use-email-as-username</a></b> (🥉15 ·  ⭐ 72) - A Django app to use email as username for user authentication. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jmfederico/django-use-email-as-username) (👨‍💻 3 · 🔀 11 · 📦 320 · ⏱️ 08.04.2025):

	```
	git clone https://github.com/jmfederico/django-use-email-as-username
	```
- [PyPi](https://pypi.org/project/django-use-email-as-username) (📥 2.7K / month):
	```
	pip install django-use-email-as-username
	```
</details>
<details><summary><b><a href="https://github.com/carltongibson/django-unique-user-email">django-unique-user-email</a></b> (🥉12 ·  ⭐ 150 · 💤) - Enable login-by-email with the default User model for your Django project by making auth.User.email unique. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carltongibson/django-unique-user-email) (👨‍💻 4 · 🔀 6 · 📦 17 · 📋 10 - 60% open · ⏱️ 09.10.2024):

	```
	git clone https://github.com/carltongibson/django-unique-user-email
	```
- [PyPi](https://pypi.org/project/django-unique-user-email) (📥 2.4K / month):
	```
	pip install django-unique-user-email
	```
</details>
<br>

## MQTT

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/tomvictor/iotcore">iotcore</a></b> (🥇13 ·  ⭐ 52 · 💤) - MQTT Broker and IoT Capabilities written in Rust for Python, Django and FastAPI. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tomvictor/iotcore) (👨‍💻 2 · 🔀 6 · 📦 4 · 📋 4 - 25% open · ⏱️ 01.02.2024):

	```
	git clone https://github.com/tomvictor/iotcore
	```
- [PyPi](https://pypi.org/project/iotcore) (📥 1.3K / month):
	```
	pip install iotcore
	```
</details>
<br>

## HTTP server

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/emmett-framework/granian">granian</a></b> (🥇31 ·  ⭐ 4.7K) - A Rust HTTP server for Python applications. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/emmett-framework/granian) (👨‍💻 39 · 🔀 130 · 📦 840 · 📋 310 - 10% open · ⏱️ 17.11.2025):

	```
	git clone https://github.com/emmett-framework/granian
	```
- [PyPi](https://pypi.org/project/granian) (📥 1.1M / month):
	```
	pip install granian
	```
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/openwisp/openwisp-monitoring">openwisp-monitoring</a></b> (🥇19 ·  ⭐ 200) - Network monitoring system written in Python and Django, designed to be extensible, programmable, scalable and easy to.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/openwisp/openwisp-monitoring) (👨‍💻 27 · 🔀 150 · 📦 5 · 📋 310 - 14% open · ⏱️ 30.10.2025):

	```
	git clone https://github.com/openwisp/openwisp-monitoring
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
