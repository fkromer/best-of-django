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
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-89-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/fkromer/best-of-django/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/fkromer/best-of-django?color=green&label=updated"></a>
</p>

This curated list contains 89 awesome open-source projects with a total of 210K stars grouped into 27 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/fkromer/best-of-django/issues/new/choose), submit a [pull request](https://github.com/fkromer/best-of-django/pulls), or directly edit the [projects.yaml](https://github.com/fkromer/best-of-django/edit/main/projects.yaml). Contributions are very welcome!

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Admin Interface](#admin-interface) _3 projects_
- [Management Commands](#management-commands) _3 projects_
- [Configuration](#configuration) _5 projects_
- [Debugging](#debugging) _1 projects_
- [Logging](#logging) _1 projects_
- [Authentication](#authentication) _2 projects_
- [Authorization](#authorization) _2 projects_
- [Concurrent Data Access](#concurrent-data-access) _0 projects_
- [Task Queues](#task-queues) _5 projects_
- [Finite State Machine](#finite-state-machine) _5 projects_
- [RESTful API (Django Rest Framework)](#restful-api-django-rest-framework) _3 projects_
- [RESTful API (Django Ninja)](#restful-api-django-ninja) _6 projects_
- [Pydantic integration](#pydantic-integration) _2 projects_
- [GraphQL API](#graphql-api) _6 projects_
- [Feature Flipper](#feature-flipper) _1 projects_
- [Statistics](#statistics) _1 projects_
- [Testing](#testing) _5 projects_
- [CMS frameworks based on Django](#cms-frameworks-based-on-django) _3 projects_
- [E-Commerce frameworks based on Django](#e-commerce-frameworks-based-on-django) _4 projects_
- [Fields (encrypted)](#fields-encrypted) _6 projects_
- [Fields (phone numbers)](#fields-phone-numbers) _2 projects_
- [Fields (addresses)](#fields-addresses) _2 projects_
- [Fields (versioning)](#fields-versioning) _7 projects_
- [Messaging](#messaging) _5 projects_
- [Storage](#storage) _1 projects_
- [Event Sourcing](#event-sourcing) _5 projects_
- [Locking](#locking) _3 projects_

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

<details><summary><b><a href="https://github.com/farridav/django-jazzmin">django-jazzmin</a></b> (🥇30 ·  ⭐ 1.2K) - Jazzy theme for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/farridav/django-jazzmin) (👨‍💻 61 · 🔀 190 · 📦 2.8K · 📋 210 - 35% open · ⏱️ 03.11.2022):

	```
	git clone https://github.com/farridav/django-jazzmin
	```
- [PyPi](https://pypi.org/project/django-jazzmin) (📥 54K / month):
	```
	pip install django-jazzmin
	```
</details>
<details><summary><b><a href="https://github.com/sehmaschine/django-grappelli">django-grappelli</a></b> (🥉28 ·  ⭐ 3.4K) - A jazzy skin for the Django Admin-Interface (official repository). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sehmaschine/django-grappelli) (👨‍💻 82 · 🔀 640 · 📦 5.2K · 📋 690 - 0% open · ⏱️ 22.11.2022):

	```
	git clone https://github.com/sehmaschine/django-grappelli
	```
- [PyPi](https://pypi.org/project/django-grappelli) (📥 120K / month):
	```
	pip install django-grappelli
	```
</details>
<details><summary><b><a href="https://github.com/fabiocaccamo/django-admin-interface">django-admin-interface</a></b> (🥉25 ·  ⭐ 1.3K) - djangos default admin interface with superpowers - customizable themes, popup windows replaced by modals and many.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fabiocaccamo/django-admin-interface) (👨‍💻 31 · 🔀 140 · 📋 150 - 7% open · ⏱️ 02.01.2023):

	```
	git clone https://github.com/fabiocaccamo/django-admin-interface
	```
- [PyPi](https://pypi.org/project/django-admin-interface) (📥 48K / month):
	```
	pip install django-admin-interface
	```
</details>
<br>

## Management Commands

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which add or help working with management commands._

<details><summary><b><a href="https://github.com/django-extensions/django-extensions">django-extensions</a></b> (🥇37 ·  ⭐ 6K) - This is a repository for collecting global custom management extensions for the Django Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-extensions/django-extensions) (👨‍💻 570 · 🔀 1.1K · 📦 130K · 📋 840 - 15% open · ⏱️ 27.12.2022):

	```
	git clone https://github.com/django-extensions/django-extensions
	```
- [PyPi](https://pypi.org/project/django-extensions) (📥 1.7M / month):
	```
	pip install django-extensions
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-dbbackup">django-dbbackup</a></b> (🥉29 ·  ⭐ 690) - Management commands to help backup and restore your project database and media files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-dbbackup) (👨‍💻 64 · 🔀 180 · 📦 1.2K · 📋 260 - 21% open · ⏱️ 12.12.2022):

	```
	git clone https://github.com/jazzband/django-dbbackup
	```
- [PyPi](https://pypi.org/project/django-dbbackup) (📥 56K / month):
	```
	pip install django-dbbackup
	```
</details>
<details><summary><b><a href="https://github.com/GaretJax/django-click">django-click</a></b> (🥉19 ·  ⭐ 220) - Write Django management command using the click CLI library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/GaretJax/django-click) (👨‍💻 11 · 🔀 17 · 📦 210 · 📋 17 - 52% open · ⏱️ 17.03.2022):

	```
	git clone https://github.com/GaretJax/django-click
	```
- [PyPi](https://pypi.org/project/django-click) (📥 25K / month):
	```
	pip install django-click
	```
</details>
<br>

## Configuration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which help w.r.t. configration topics._

<details><summary><b><a href="https://github.com/joke2k/django-environ">django-environ</a></b> (🥇34 ·  ⭐ 2.7K) - Django-environ allows you to utilize 12factor inspired environment variables to configure your Django application. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joke2k/django-environ) (👨‍💻 76 · 🔀 280 · 📥 7 · 📦 110K · 📋 210 - 27% open · ⏱️ 15.06.2022):

	```
	git clone https://github.com/joke2k/django-environ
	```
- [PyPi](https://pypi.org/project/django-environ) (📥 1M / month):
	```
	pip install django-environ
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-constance">django-constance</a></b> (🥈30 ·  ⭐ 1.5K) - Dynamic Django settings. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-constance) (👨‍💻 140 · 🔀 280 · 📦 1.2K · 📋 260 - 11% open · ⏱️ 13.10.2022):

	```
	git clone https://github.com/jazzband/django-constance
	```
- [PyPi](https://pypi.org/project/django-constance) (📥 150K / month):
	```
	pip install django-constance
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/django-split-settings">django-split-settings</a></b> (🥉26 ·  ⭐ 940 · 📈) - Organize Django settings into multiple files and directories. Easily override and modify settings. Use wildcards and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wemake-services/django-split-settings) (👨‍💻 21 · 🔀 59 · 📦 1.3K · 📋 42 - 9% open · ⏱️ 05.01.2023):

	```
	git clone https://github.com/wemake-services/django-split-settings
	```
- [PyPi](https://pypi.org/project/django-split-settings) (📥 67K / month):
	```
	pip install django-split-settings
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-configurations">django-configurations</a></b> (🥉25 ·  ⭐ 960) - A helper for organizing Django project settings by relying on well established programming patterns. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-configurations) (👨‍💻 63 · 🔀 120 · 📦 2.5K · 📋 180 - 21% open · ⏱️ 04.11.2022):

	```
	git clone https://github.com/jazzband/django-configurations
	```
- [PyPi](https://pypi.org/project/django-configurations) (📥 81K / month):
	```
	pip install django-configurations
	```
</details>
<details><summary><b><a href="https://github.com/fabiocaccamo/django-extra-settings">django-extra-settings</a></b> (🥉19 ·  ⭐ 280) - config and manage typed extra settings using just the django admin. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fabiocaccamo/django-extra-settings) (👨‍💻 9 · 🔀 17 · 📋 21 - 9% open · ⏱️ 03.01.2023):

	```
	git clone https://github.com/fabiocaccamo/django-extra-settings
	```
- [PyPi](https://pypi.org/project/django-extra-settings) (📥 4.7K / month):
	```
	pip install django-extra-settings
	```
</details>
<br>

## Debugging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jazzband/django-debug-toolbar">django-debug-toolbar</a></b> (🥇37 ·  ⭐ 7.3K) - A configurable set of panels that display various debug information about the current request/response. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-debug-toolbar) (👨‍💻 260 · 🔀 870 · 📥 180 · 📦 60K · 📋 820 - 9% open · ⏱️ 28.12.2022):

	```
	git clone https://github.com/jazzband/django-debug-toolbar
	```
- [PyPi](https://pypi.org/project/django-debug-toolbar) (📥 1.4M / month):
	```
	pip install django-debug-toolbar
	```
</details>
<br>

## Logging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which improve logging and debugging._

<details><summary><b><a href="https://github.com/snok/django-guid">django-guid</a></b> (🥇21 ·  ⭐ 300) - Inject an ID into every log message from a Django request. ASGI compatible, integrates with Sentry, and works with.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/snok/django-guid) (👨‍💻 8 · 🔀 15 · 📦 59 · 📋 20 - 5% open · ⏱️ 09.12.2022):

	```
	git clone https://github.com/snok/django-guid
	```
- [PyPi](https://pypi.org/project/django-guid) (📥 37K / month):
	```
	pip install django-guid
	```
</details>
<br>

## Authentication

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pennersr/django-allauth">django-allauth</a></b> (🥇38 ·  ⭐ 7.7K) - Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pennersr/django-allauth) (👨‍💻 620 · 🔀 2.6K · 📦 120K · 📋 1.9K - 14% open · ⏱️ 02.01.2023):

	```
	git clone https://github.com/pennersr/django-allauth
	```
- [PyPi](https://pypi.org/project/django-allauth) (📥 500K / month):
	```
	pip install django-allauth
	```
</details>
<details><summary><b><a href="https://github.com/django-cas-ng/django-cas-ng">django-cas-ng</a></b> (🥉26 ·  ⭐ 350) - Django CAS 1.0/2.0/3.0 client authentication library, support Django 2.0, 2.1, 2.2, 3.0 and Python 3.5+. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-cas-ng/django-cas-ng) (👨‍💻 83 · 🔀 160 · 📥 440 · 📦 380 · 📋 150 - 1% open · ⏱️ 18.11.2022):

	```
	git clone https://github.com/django-cas-ng/django-cas-ng
	```
- [PyPi](https://pypi.org/project/django-cas-ng) (📥 11K / month):
	```
	pip install django-cas-ng
	```
</details>
<br>

## Authorization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-guardian/django-guardian">django-guardian</a></b> (🥇27 ·  ⭐ 3.3K) - Per object permissions for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-guardian/django-guardian) (👨‍💻 160 · 🔀 530 · 📦 5.2K · 📋 440 - 27% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/django-guardian/django-guardian
	```
- [PyPi](https://pypi.org/project/django-guardian) (📥 330K / month):
	```
	pip install django-guardian
	```
</details>
<details><summary><b><a href="https://github.com/bennylope/django-organizations">django-organizations</a></b> (🥉24 ·  ⭐ 1.1K) - Multi-user accounts for Django projects. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/bennylope/django-organizations) (👨‍💻 46 · 🔀 180 · 📋 150 - 10% open · ⏱️ 29.11.2022):

	```
	git clone https://github.com/bennylope/django-organizations
	```
- [PyPi](https://pypi.org/project/django-organizations) (📥 22K / month):
	```
	pip install django-organizations
	```
</details>
<br>

## Concurrent Data Access

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to help providing issues w.r.t. concurrent data access._

<br>

## Task Queues

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/celery/celery">celery</a></b> (🥇43 ·  ⭐ 21K) - Distributed Task Queue (development branch). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/celery/celery) (👨‍💻 1.3K · 🔀 4.2K · 📦 82K · 📋 4.8K - 10% open · ⏱️ 04.01.2023):

	```
	git clone https://github.com/celery/celery
	```
- [PyPi](https://pypi.org/project/celery) (📥 5M / month):
	```
	pip install celery
	```
</details>
<details><summary><b><a href="https://github.com/rq/rq">rq</a></b> (🥈37 ·  ⭐ 8.7K) - Simple job queues for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rq/rq) (👨‍💻 280 · 🔀 1.3K · 📦 12K · 📋 990 - 19% open · ⏱️ 28.12.2022):

	```
	git clone https://github.com/rq/rq
	```
- [PyPi](https://pypi.org/project/rq) (📥 610K / month):
	```
	pip install rq
	```
</details>
<details><summary><b><a href="https://github.com/rq/django-rq">django-rq</a></b> (🥉32 ·  ⭐ 1.6K) - A simple app that provides django integration for RQ (Redis Queue). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rq/django-rq) (👨‍💻 110 · 🔀 250 · 📦 2.2K · 📋 300 - 23% open · ⏱️ 19.11.2022):

	```
	git clone https://github.com/rq/django-rq
	```
- [PyPi](https://pypi.org/project/django-rq) (📥 130K / month):
	```
	pip install django-rq
	```
</details>
<details><summary><b><a href="https://github.com/Koed00/django-q">django-q</a></b> (🥉30 ·  ⭐ 1.7K · 💤) - A multiprocessing distributed task queue for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Koed00/django-q) (👨‍💻 62 · 🔀 220 · 📦 1.1K · 📋 410 - 64% open · ⏱️ 26.06.2021):

	```
	git clone https://github.com/Koed00/django-q
	```
- [PyPi](https://pypi.org/project/django-q) (📥 63K / month):
	```
	pip install django-q
	```
</details>
<details><summary><b><a href="https://github.com/celery/django-celery-beat">django-celery-beat</a></b> (🥉26 ·  ⭐ 1.3K) - Celery Periodic Tasks backed by the Django ORM. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/celery/django-celery-beat) (👨‍💻 100 · 🔀 360 · 📋 350 - 18% open · ⏱️ 26.12.2022):

	```
	git clone https://github.com/celery/django-celery-beat
	```
- [PyPi](https://pypi.org/project/django-celery-beat) (📥 660K / month):
	```
	pip install django-celery-beat
	```
</details>
<br>

## Finite State Machine

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement Finite State Machines (e.g. to implement workflows)._

<details><summary><b><a href="https://github.com/viewflow/django-fsm">django-fsm</a></b> (🥇28 ·  ⭐ 2.1K) - Django friendly finite state machine support. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/viewflow/django-fsm) (👨‍💻 64 · 🔀 250 · 📦 1.2K · 📋 150 - 11% open · ⏱️ 15.08.2022):

	```
	git clone https://github.com/viewflow/django-fsm
	```
- [PyPi](https://pypi.org/project/django-fsm) (📥 180K / month):
	```
	pip install django-fsm
	```
</details>
<details><summary><b><a href="https://github.com/viewflow/viewflow">viewflow</a></b> (🥈23 ·  ⭐ 2.3K) - Reusable workflow library for Django. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/viewflow/viewflow) (👨‍💻 31 · 🔀 360 · 📦 250 · 📋 280 - 8% open · ⏱️ 02.12.2022):

	```
	git clone https://github.com/viewflow/viewflow
	```
- [PyPi](https://pypi.org/project/viewflow) (📥 46 / month):
	```
	pip install viewflow
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-fsm-log">django-fsm-log</a></b> (🥈23 ·  ⭐ 200) - Automatic logging for Django FSM. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-fsm-log) (👨‍💻 26 · 🔀 66 · 📦 110 · 📋 40 - 22% open · ⏱️ 20.12.2022):

	```
	git clone https://github.com/jazzband/django-fsm-log
	```
- [PyPi](https://pypi.org/project/django-fsm-log) (📥 20K / month):
	```
	pip install django-fsm-log
	```
</details>
<details><summary><b><a href="https://github.com/gadventures/django-fsm-admin">django-fsm-admin</a></b> (🥉17 ·  ⭐ 190) - Mixin and template tags to integrate django-fsm transitions into the django admin. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gadventures/django-fsm-admin) (👨‍💻 32 · 🔀 77 · 📦 280 · 📋 37 - 45% open · ⏱️ 25.10.2022):

	```
	git clone https://github.com/gadventures/django-fsm-admin
	```
- [PyPi](https://pypi.org/project/django-fsm-admin) (📥 31K / month):
	```
	pip install django-fsm-admin
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/ming-tung/django-fsm-freeze">django-fsm-freeze</a></b> (🥉10 ·  ⭐ 4) - django-fsm data immutability support. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## RESTful API (Django Rest Framework)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/encode/django-rest-framework">django-rest-framework</a></b> (🥇43 ·  ⭐ 25K) - Web APIs for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/encode/django-rest-framework) (👨‍💻 1.3K · 🔀 6.2K · 📦 410K · 📋 3.8K - 1% open · ⏱️ 04.01.2023):

	```
	git clone https://github.com/encode/django-rest-framework
	```
- [PyPi](https://pypi.org/project/django-rest-framework) (📥 71K / month):
	```
	pip install django-rest-framework
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/djangorestframework-simplejwt">djangorestframework-simplejwt</a></b> (🥉27 ·  ⭐ 3.3K) - A JSON Web Token authentication plugin for the Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/djangorestframework-simplejwt) (👨‍💻 92 · 🔀 520 · 📋 380 - 22% open · ⏱️ 20.12.2022):

	```
	git clone https://github.com/jazzband/djangorestframework-simplejwt
	```
- [PyPi](https://pypi.org/project/djangorestframework-simplejwt) (📥 840K / month):
	```
	pip install djangorestframework-simplejwt
	```
</details>
<details><summary><b><a href="https://github.com/anexia-it/django-rest-passwordreset">django-rest-passwordreset</a></b> (🥉27 ·  ⭐ 360) - An extension of django rest framework, providing a configurable password reset strategy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anexia-it/django-rest-passwordreset) (👨‍💻 33 · 🔀 120 · 📦 2.1K · 📋 95 - 24% open · ⏱️ 02.11.2022):

	```
	git clone https://github.com/anexia-it/django-rest-passwordreset
	```
- [PyPi](https://pypi.org/project/django-rest-passwordreset) (📥 230K / month):
	```
	pip install django-rest-passwordreset
	```
</details>
<br>

## RESTful API (Django Ninja)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/vitalik/django-ninja">django-ninja</a></b> (🥇31 ·  ⭐ 3.9K) - Fast, Async-ready, Openapi, type hints based framework for building APIs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vitalik/django-ninja) (👨‍💻 70 · 🔀 240 · 📦 940 · 📋 420 - 33% open · ⏱️ 04.01.2023):

	```
	git clone https://github.com/vitalik/django-ninja
	```
- [PyPi](https://pypi.org/project/django-ninja) (📥 57K / month):
	```
	pip install django-ninja
	```
</details>
<details><summary><b><a href="https://github.com/eadwinCode/django-ninja-extra">django-ninja-extra</a></b> (🥈17 ·  ⭐ 100) - Django Ninja Extra - Class-Based Utility and more for Django Ninja(Fast Django REST framework). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eadwinCode/django-ninja-extra) (👨‍💻 7 · 🔀 8 · 📋 11 - 9% open · ⏱️ 22.12.2022):

	```
	git clone https://github.com/eadwinCode/django-ninja-extra
	```
- [PyPi](https://pypi.org/project/django-ninja-extra) (📥 5.6K / month):
	```
	pip install django-ninja-extra
	```
</details>
<details><summary><b><a href="https://github.com/eadwinCode/django-ninja-jwt">django-ninja-jwt</a></b> (🥈17 ·  ⭐ 34) - A JSON Web Token authentication plugin for the Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eadwinCode/django-ninja-jwt) (👨‍💻 77 · 🔀 5 · ⏱️ 30.11.2022):

	```
	git clone https://github.com/eadwinCode/django-ninja-jwt
	```
- [PyPi](https://pypi.org/project/django-ninja-jwt) (📥 2.7K / month):
	```
	pip install django-ninja-jwt
	```
</details>
<details><summary><b><a href="https://github.com/eadwinCode/django-ninja-passwordreset">django-ninja-passwordreset</a></b> (🥉8 · 💤) - An extension of django rest framework, providing a configurable password reset strategy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/eadwinCode/django-ninja-passwordreset) (👨‍💻 33 · ⏱️ 22.11.2021):

	```
	git clone https://github.com/eadwinCode/django-ninja-passwordreset
	```
- [PyPi](https://pypi.org/project/django-ninja-passwordreset) (📥 19 / month):
	```
	pip install django-ninja-passwordreset
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/mawassk/django-ninja-apikey">django-ninja-apikey</a></b> (🥉7 ·  ⭐ 15 · 💤) - Easy to use API key authentication for Django Ninja REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mugartec/django-ninja-auth">django-ninja-auth</a></b> (🥉4 ·  ⭐ 12 · 💤) -  <code><a href="https://tldrlegal.com/search?q=WTFPL">❗️WTFPL</a></code>
</details>
<br>

## Pydantic integration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pydantic/pydantic">pydantic</a></b> (🥇44 ·  ⭐ 12K) - Data parsing and validation using Python type hints. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydantic/pydantic) (👨‍💻 340 · 🔀 1.1K · 📦 130K · 📋 2.1K - 25% open · ⏱️ 05.01.2023):

	```
	git clone https://github.com/pydantic/pydantic
	```
- [PyPi](https://pypi.org/project/pydantic) (📥 41M / month):
	```
	pip install pydantic
	```
</details>
<details><summary><b><a href="https://github.com/jordaneremieff/djantic">djantic</a></b> (🥉19 ·  ⭐ 320) - Pydantic model support for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jordaneremieff/djantic) (👨‍💻 4 · 🔀 25 · 📦 40 · 📋 35 - 22% open · ⏱️ 25.08.2022):

	```
	git clone https://github.com/jordaneremieff/djantic
	```
- [PyPi](https://pypi.org/project/djantic) (📥 3.6K / month):
	```
	pip install djantic
	```
</details>
<br>

## GraphQL API

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement GraphQL API._

<details><summary><b><a href="https://github.com/graphql-python/graphene">graphene</a></b> (🥇36 ·  ⭐ 7.5K) - GraphQL framework for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene) (👨‍💻 200 · 🔀 770 · 📦 15K · 📋 970 - 10% open · ⏱️ 25.12.2022):

	```
	git clone https://github.com/graphql-python/graphene
	```
- [PyPi](https://pypi.org/project/graphene) (📥 1.8M / month):
	```
	pip install graphene
	```
</details>
<details><summary><b><a href="https://github.com/graphql-python/graphene-django">graphene-django</a></b> (🥈33 ·  ⭐ 4K) - Integrate GraphQL into your Django project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene-django) (👨‍💻 200 · 🔀 690 · 📦 9.1K · 📋 760 - 17% open · ⏱️ 24.12.2022):

	```
	git clone https://github.com/graphql-python/graphene-django
	```
- [PyPi](https://pypi.org/project/graphene-django) (📥 270K / month):
	```
	pip install graphene-django
	```
</details>
<details><summary><b><a href="https://github.com/strawberry-graphql/strawberry">strawberry</a></b> (🥈32 ·  ⭐ 2.8K) - A GraphQL library for Python that leverages type annotations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/strawberry-graphql/strawberry) (👨‍💻 170 · 🔀 340 · 📥 390 · 📦 910 · 📋 620 - 38% open · ⏱️ 23.12.2022):

	```
	git clone https://github.com/strawberry-graphql/strawberry
	```
- [PyPi](https://pypi.org/project/strawberry) (📥 270 / month):
	```
	pip install strawberry
	```
</details>
<details><summary><b><a href="https://github.com/flavors/django-graphql-jwt">django-graphql-jwt</a></b> (🥉27 ·  ⭐ 780 · 💤) - JSON Web Token (JWT) authentication for Graphene Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/flavors/django-graphql-jwt) (👨‍💻 23 · 🔀 140 · 📦 3.3K · 📋 210 - 21% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/flavors/django-graphql-jwt
	```
- [PyPi](https://pypi.org/project/django-graphql-jwt) (📥 91K / month):
	```
	pip install django-graphql-jwt
	```
</details>
<details><summary><b><a href="https://github.com/strawberry-graphql/strawberry-graphql-django">strawberry-graphql-django</a></b> (🥉26 ·  ⭐ 220) - Strawberry GraphQL Django extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/strawberry-graphql/strawberry-graphql-django) (👨‍💻 38 · 🔀 48 · 📦 120 · 📋 120 - 45% open · ⏱️ 02.01.2023):

	```
	git clone https://github.com/strawberry-graphql/strawberry-graphql-django
	```
- [PyPi](https://pypi.org/project/strawberry-graphql-django) (📥 21K / month):
	```
	pip install strawberry-graphql-django
	```
</details>
<details><summary><b><a href="https://github.com/PedroBern/django-graphql-auth">django-graphql-auth</a></b> (🥉20 ·  ⭐ 300) - Django registration and authentication with GraphQL. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PedroBern/django-graphql-auth) (👨‍💻 16 · 🔀 81 · 📦 520 · 📋 100 - 57% open · ⏱️ 17.06.2022):

	```
	git clone https://github.com/PedroBern/django-graphql-auth
	```
- [PyPi](https://pypi.org/project/django-graphql-auth) (📥 10K / month):
	```
	pip install django-graphql-auth
	```
</details>
<br>

## Feature Flipper

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-waffle/django-waffle">django-waffle</a></b> (🥇25 ·  ⭐ 950) - A feature flipper for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-waffle/django-waffle) (👨‍💻 120 · 🔀 230 · 📋 200 - 18% open · ⏱️ 02.10.2022):

	```
	git clone https://github.com/django-waffle/django-waffle
	```
- [PyPi](https://pypi.org/project/django-waffle) (📥 210K / month):
	```
	pip install django-waffle
	```
</details>
<br>

## Statistics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which add application layer statistic functionality._

<details><summary><b><a href="https://github.com/pennersr/django-trackstats">django-trackstats</a></b> (🥇15 ·  ⭐ 380) - Keep track of your statistics. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pennersr/django-trackstats) (👨‍💻 6 · 🔀 32 · 📦 22 · 📋 11 - 27% open · ⏱️ 25.04.2022):

	```
	git clone https://github.com/pennersr/django-trackstats
	```
- [PyPi](https://pypi.org/project/django-trackstats) (📥 540 / month):
	```
	pip install django-trackstats
	```
</details>
<br>

## Testing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pytest-dev/pytest-django">pytest-django</a></b> (🥇25 ·  ⭐ 1.1K) - A Django plugin for pytest. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-django) (👨‍💻 140 · 🔀 300 · 📋 490 - 27% open · ⏱️ 08.11.2022):

	```
	git clone https://github.com/pytest-dev/pytest-django
	```
- [PyPi](https://pypi.org/project/pytest-django) (📥 1.5M / month):
	```
	pip install pytest-django
	```
</details>
<details><summary><b><a href="https://github.com/FactoryBoy/factory_boy">factory_boy</a></b> (🥈24 ·  ⭐ 3K) - A test fixtures replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/FactoryBoy/factory_boy) (👨‍💻 130 · 🔀 350 · 📋 540 - 29% open · ⏱️ 07.12.2022):

	```
	git clone https://github.com/FactoryBoy/factory_boy
	```
- [PyPi](https://pypi.org/project/factory_boy) (📥 1.9M / month):
	```
	pip install factory_boy
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/django-test-migrations">django-test-migrations</a></b> (🥉23 ·  ⭐ 380) - Test django schema and data migrations, including migrations order and best practices. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/django-test-migrations) (👨‍💻 17 · 🔀 24 · 📦 320 · 📋 54 - 14% open · ⏱️ 27.12.2022):

	```
	git clone https://github.com/wemake-services/django-test-migrations
	```
- [PyPi](https://pypi.org/project/django-test-migrations) (📥 59K / month):
	```
	pip install django-test-migrations
	```
</details>
<details><summary><b><a href="https://github.com/model-bakers/model_bakery">model_bakery</a></b> (🥉21 ·  ⭐ 630) - Object factory for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/model-bakers/model_bakery) (👨‍💻 42 · 🔀 71 · 📋 110 - 18% open · ⏱️ 02.01.2023):

	```
	git clone https://github.com/model-bakers/model_bakery
	```
- [PyPi](https://pypi.org/project/model_bakery) (📥 230K / month):
	```
	pip install model_bakery
	```
</details>
<details><summary><b><a href="https://github.com/revsys/django-test-plus">django-test-plus</a></b> (🥉18 ·  ⭐ 550) - Useful additions to Djangos default TestCase. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/revsys/django-test-plus) (👨‍💻 30 · 🔀 55 · 📋 49 - 10% open · ⏱️ 08.10.2022):

	```
	git clone https://github.com/revsys/django-test-plus
	```
- [PyPi](https://pypi.org/project/django-test-plus) (📥 31K / month):
	```
	pip install django-test-plus
	```
</details>
<br>

## CMS frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Content Management Systems which use Django under the hood._

<details><summary><b><a href="https://github.com/wagtail/wagtail">wagtail</a></b> (🥇42 ·  ⭐ 14K) - A Django content management system focused on flexibility and user experience. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wagtail/wagtail) (👨‍💻 770 · 🔀 2.9K · 📦 7.6K · 📋 4.2K - 19% open · ⏱️ 05.01.2023):

	```
	git clone https://github.com/wagtail/wagtail
	```
- [PyPi](https://pypi.org/project/wagtail) (📥 100K / month):
	```
	pip install wagtail
	```
</details>
<details><summary><b><a href="https://github.com/django-cms/django-cms">django-cms</a></b> (🥉39 ·  ⭐ 9.1K) - The easy-to-use and developer-friendly enterprise CMS powered by Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-cms/django-cms) (👨‍💻 620 · 🔀 2.8K · 📦 4.7K · 📋 3.4K - 3% open · ⏱️ 05.01.2023):

	```
	git clone https://github.com/django-cms/django-cms
	```
- [PyPi](https://pypi.org/project/django-cms) (📥 41K / month):
	```
	pip install django-cms
	```
</details>
<details><summary><b><a href="https://github.com/stephenmcd/mezzanine">mezzanine</a></b> (🥉26 ·  ⭐ 4.6K) - CMS framework for Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/stephenmcd/mezzanine) (👨‍💻 330 · 🔀 1.5K · 📋 1K - 3% open · ⏱️ 02.11.2022):

	```
	git clone https://github.com/stephenmcd/mezzanine
	```
- [PyPi](https://pypi.org/project/mezzanine) (📥 2.2K / month):
	```
	pip install mezzanine
	```
</details>
<br>

## E-Commerce frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_E-Commerce frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/django-oscar/django-oscar">django-oscar</a></b> (🥇36 ·  ⭐ 5.6K) - Domain-driven e-commerce for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-oscar/django-oscar) (👨‍💻 340 · 🔀 2K · 📦 950 · 📋 1.4K - 9% open · ⏱️ 23.12.2022):

	```
	git clone https://github.com/django-oscar/django-oscar
	```
- [PyPi](https://pypi.org/project/django-oscar) (📥 15K / month):
	```
	pip install django-oscar
	```
</details>
<details><summary><b><a href="https://github.com/saleor/saleor">saleor</a></b> (🥈30 ·  ⭐ 18K) - A modular, high performance, headless e-commerce platform built with Python, GraphQL, Django, and React. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/saleor/saleor) (👨‍💻 260 · 🔀 4.7K · 📦 2 · 📋 3.4K - 9% open · ⏱️ 05.01.2023):

	```
	git clone https://github.com/saleor/saleor
	```
- [PyPi](https://pypi.org/project/saleor) (📥 18 / month):
	```
	pip install saleor
	```
</details>
<details><summary><b><a href="https://github.com/awesto/django-shop">django-shop</a></b> (🥉26 ·  ⭐ 2.9K · 💤) - A Django based shop system. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/awesto/django-shop) (👨‍💻 96 · 🔀 940 · 📦 210 · 📋 380 - 22% open · ⏱️ 28.02.2021):

	```
	git clone https://github.com/awesto/django-shop
	```
- [PyPi](https://pypi.org/project/django-shop) (📥 6.4K / month):
	```
	pip install django-shop
	```
</details>
<details><summary><b><a href="https://github.com/shuup/shuup">shuup</a></b> (🥉25 ·  ⭐ 2K · 💤) - E-Commerce Platform. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/shuup/shuup) (👨‍💻 67 · 🔀 960 · 📥 510 · 📦 120 · 📋 430 - 32% open · ⏱️ 18.08.2021):

	```
	git clone https://github.com/shuup/shuup
	```
- [PyPi](https://pypi.org/project/shuup) (📥 1.1K / month):
	```
	pip install shuup
	```
</details>
<br>

## Fields (encrypted)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/orcasgit/django-fernet-fields">django-fernet-fields</a></b> (🥇19 ·  ⭐ 180 · 💤) - Fernet symmetric encryption for Django model fields. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/orcasgit/django-fernet-fields) (👨‍💻 9 · 🔀 48 · 📦 510 · 📋 15 - 60% open · ⏱️ 10.05.2019):

	```
	git clone https://github.com/orcasgit/django-fernet-fields
	```
- [PyPi](https://pypi.org/project/django-fernet-fields) (📥 59K / month):
	```
	pip install django-fernet-fields
	```
</details>
<details><summary><b><a href="https://github.com/georgemarshall/django-cryptography">django-cryptography</a></b> (🥈17 ·  ⭐ 300) - Easily encrypt data in Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/georgemarshall/django-cryptography) (👨‍💻 3 · 🔀 53 · 📋 65 - 52% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/georgemarshall/django-cryptography
	```
- [PyPi](https://pypi.org/project/django-cryptography) (📥 56K / month):
	```
	pip install django-cryptography
	```
</details>
<details><summary><b><a href="https://github.com/luojilab/django-mirage-field">django-mirage-field</a></b> (🥈17 ·  ⭐ 85) - Django model field encrypt/decrypt your data, keep secret in database. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/luojilab/django-mirage-field) (👨‍💻 9 · 🔀 13 · 📦 53 · ⏱️ 19.04.2022):

	```
	git clone https://github.com/luojilab/django-mirage-field
	```
- [PyPi](https://pypi.org/project/django-mirage-field) (📥 8.6K / month):
	```
	pip install django-mirage-field
	```
</details>
<details><summary><b><a href="https://gitlab.com/lansharkconsulting/django/django-encrypted-model-fields">django-encrypted-model-fields</a></b> (🥉10 ·  ⭐ 31 · 💤) - A set of fields that wrap standard Django fields with encryption provided by the python cryptography library. <code>❗Unlicensed</code></summary>

- [PyPi](https://pypi.org/project/django-encrypted-model-fields) (📥 46K / month):
	```
	pip install django-encrypted-model-fields
	```
- [GitLab](https://gitlab.com/lansharkconsulting/django/django-encrypted-model-fields) (🔀 23 · 📋 26 - 23% open · ⏱️ 05.06.2018):

	```
	git clone https://gitlab.com/lansharkconsulting/django/django-encrypted-model-fields
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/foundertherapy/django-cryptographic-fields">django-cryptographic-fields</a></b> (🥉15 ·  ⭐ 26 · 💀) - A set of fields that wrap standard Django fields with encryption provided by the python cryptography library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/guywillett/django-searchable-encrypted-fields">django-searchable-encrypted-fields</a></b> (🥉6 ·  ⭐ 7 · 💤) -  <code>❗Unlicensed</code>
</details>
<br>

## Fields (phone numbers)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/stefanfoulis/django-phonenumber-field">django-phonenumber-field</a></b> (🥇27 ·  ⭐ 1.3K) - A django model and form field for normalised phone numbers using python-phonenumbers. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stefanfoulis/django-phonenumber-field) (👨‍💻 110 · 🔀 280 · 📥 6 · 📋 200 - 3% open · ⏱️ 06.12.2022):

	```
	git clone https://github.com/stefanfoulis/django-phonenumber-field
	```
- [PyPi](https://pypi.org/project/django-phonenumber-field) (📥 480K / month):
	```
	pip install django-phonenumber-field
	```
</details>
<details><summary><b><a href="https://github.com/VeryApt/django-phone-field">django-phone-field</a></b> (🥉18 ·  ⭐ 48 · 💤) - Lightweight model and form field for phone numbers in Django. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/VeryApt/django-phone-field) (👨‍💻 4 · 🔀 14 · 📦 2.4K · 📋 14 - 21% open · ⏱️ 10.06.2020):

	```
	git clone https://github.com/VeryApt/django-phone-field
	```
- [PyPi](https://pypi.org/project/django-phone-field) (📥 12K / month):
	```
	pip install django-phone-field
	```
</details>
<br>

## Fields (addresses)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/furious-luke/django-address">django-address</a></b> (🥇23 ·  ⭐ 380) - A Django address model and field. Addresses may be specified by address components or by performing an automatic.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/furious-luke/django-address) (👨‍💻 22 · 🔀 150 · 📦 340 · 📋 120 - 31% open · ⏱️ 05.05.2022):

	```
	git clone https://github.com/furious-luke/django-address
	```
- [PyPi](https://pypi.org/project/django-address) (📥 9K / month):
	```
	pip install django-address
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/agusmakmun/django-address-model">django-address-model</a></b> (🥉8 ·  ⭐ 13 · 💤) - django abstract model that provide the complete address, eg: no, na/rt, ca/rw, village/desa, sub district/kecamatan,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Fields (versioning)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jazzband/django-simple-history">django-simple-history</a></b> (🥇35 ·  ⭐ 1.8K) - Store model history and view/revert changes from admin site. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-simple-history) (👨‍💻 170 · 🔀 390 · 📦 3.5K · 📋 490 - 21% open · ⏱️ 09.12.2022):

	```
	git clone https://github.com/jazzband/django-simple-history
	```
- [PyPi](https://pypi.org/project/django-simple-history) (📥 590K / month):
	```
	pip install django-simple-history
	```
</details>
<details><summary><b><a href="https://github.com/etianen/django-reversion">django-reversion</a></b> (🥈34 ·  ⭐ 2.8K) - django-reversion is an extension to the Django web framework that provides version control for model instances. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/etianen/django-reversion) (👨‍💻 180 · 🔀 440 · 📦 6.6K · 📋 630 - 2% open · ⏱️ 12.11.2022):

	```
	git clone https://github.com/etianen/django-reversion
	```
- [PyPi](https://pypi.org/project/django-reversion) (📥 190K / month):
	```
	pip install django-reversion
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-auditlog">django-auditlog</a></b> (🥈28 ·  ⭐ 710) - A Django app that keeps a log of changes made to an object. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-auditlog) (👨‍💻 63 · 🔀 310 · 📥 280 · 📦 560 · 📋 210 - 19% open · ⏱️ 04.01.2023):

	```
	git clone https://github.com/jazzband/django-auditlog
	```
- [PyPi](https://pypi.org/project/django-auditlog) (📥 65K / month):
	```
	pip install django-auditlog
	```
</details>
<details><summary><b><a href="https://github.com/soynatan/django-easy-audit">django-easy-audit</a></b> (🥉22 ·  ⭐ 510) - Yet another Django audit log app, hopefully the simplest one. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/soynatan/django-easy-audit) (👨‍💻 41 · 🔀 130 · 📦 160 · 📋 120 - 45% open · ⏱️ 04.09.2022):

	```
	git clone https://github.com/soynatan/django-easy-audit
	```
- [PyPi](https://pypi.org/project/django-easy-audit) (📥 25K / month):
	```
	pip install django-easy-audit
	```
</details>
<details><summary><b><a href="https://github.com/romgar/django-dirtyfields">django-dirtyfields</a></b> (🥉19 ·  ⭐ 570) - Tracking dirty fields on a Django model. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/romgar/django-dirtyfields) (👨‍💻 40 · 🔀 97 · 📋 69 - 17% open · ⏱️ 07.11.2022):

	```
	git clone https://github.com/romgar/django-dirtyfields
	```
- [PyPi](https://pypi.org/project/django-dirtyfields) (📥 94K / month):
	```
	pip install django-dirtyfields
	```
</details>
<details><summary><b><a href="https://github.com/vvangelovski/django-audit-log">django-audit-log</a></b> (🥉18 ·  ⭐ 230 · 💤) - Audit log for your Django models. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/vvangelovski/django-audit-log) (👨‍💻 10 · 🔀 81 · 📦 230 · 📋 43 - 62% open · ⏱️ 12.03.2018):

	```
	git clone https://github.com/vvangelovski/django-audit-log
	```
- [PyPi](https://pypi.org/project/django-audit-log) (📥 1.4K / month):
	```
	pip install django-audit-log
	```
</details>
<details><summary><b><a href="https://github.com/craigds/django-fieldsignals">django-fieldsignals</a></b> (🥉15 ·  ⭐ 100 · 📈) - Django signals for changed fields. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/craigds/django-fieldsignals) (👨‍💻 5 · 🔀 11 · 📦 140 · 📋 17 - 17% open · ⏱️ 08.10.2022):

	```
	git clone https://github.com/craigds/django-fieldsignals
	```
- [PyPi](https://pypi.org/project/django-fieldsignals) (📥 8.8K / month):
	```
	pip install django-fieldsignals
	```
</details>
<br>

## Messaging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/lamby/django-slack">django-slack</a></b> (🥇21 ·  ⭐ 230) - Slack integration for Django, using the templating engine to generate messages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lamby/django-slack) (👨‍💻 27 · 🔀 54 · 📦 300 · 📋 62 - 12% open · ⏱️ 02.09.2022):

	```
	git clone https://github.com/lamby/django-slack
	```
- [PyPi](https://pypi.org/project/django-slack) (📥 42K / month):
	```
	pip install django-slack
	```
</details>
<details><summary><b><a href="https://github.com/stefanfoulis/django-sendsms">django-sendsms</a></b> (🥈17 ·  ⭐ 240 · 💤) - A simple API to send SMS messages. It is modeled after the django email api. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stefanfoulis/django-sendsms) (👨‍💻 19 · 🔀 95 · 📦 310 · 📋 24 - 20% open · ⏱️ 27.12.2021):

	```
	git clone https://github.com/stefanfoulis/django-sendsms
	```
- [PyPi](https://pypi.org/project/django-sendsms) (📥 2.6K / month):
	```
	pip install django-sendsms
	```
</details>
<details><summary><b><a href="https://github.com/roaldnefs/django-sms">django-sms</a></b> (🥈17 ·  ⭐ 37) - A Django app for sending SMS with interchangeable backends. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/roaldnefs/django-sms) (👨‍💻 3 · 🔀 10 · 📦 110 · 📋 11 - 36% open · ⏱️ 25.12.2022):

	```
	git clone https://github.com/roaldnefs/django-sms
	```
- [PyPi](https://pypi.org/project/django-sms) (📥 1.9K / month):
	```
	pip install django-sms
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/Ninjaclasher/django-discord-integration">django-discord-integration</a></b> (🥉10 ·  ⭐ 15) - Discord integration for Django, supporting error reporting via webhooks. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/AdvocatesInc/django-channels-discord">django-channels-discord</a></b> (🥉5 ·  ⭐ 11) - An interface server connecting Djangos Channels and Discord. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Storage

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jschneier/django-storages">django-storages</a></b> (🥇26 ·  ⭐ 2.3K) - https://django-storages.readthedocs.io/. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jschneier/django-storages) (👨‍💻 240 · 🔀 740 · 📋 600 - 26% open · ⏱️ 01.01.2023):

	```
	git clone https://github.com/jschneier/django-storages
	```
- [PyPi](https://pypi.org/project/django-storages) (📥 1.7M / month):
	```
	pip install django-storages
	```
</details>
<br>

## Event Sourcing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pyeventsourcing/eventsourcing">eventsourcing</a></b> (🥇25 ·  ⭐ 1.2K) - A library for event sourcing in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyeventsourcing/eventsourcing) (👨‍💻 23 · 🔀 120 · 📦 110 · 📋 77 - 2% open · ⏱️ 14.11.2022):

	```
	git clone https://github.com/pyeventsourcing/eventsourcing
	```
- [PyPi](https://pypi.org/project/eventsourcing) (📥 22K / month):
	```
	pip install eventsourcing
	```
</details>
<details><summary><b><a href="https://github.com/pyeventsourcing/eventsourcing-django">eventsourcing-django</a></b> (🥈11 ·  ⭐ 29) - Python package for eventsourcing with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyeventsourcing/eventsourcing-django) (👨‍💻 5 · 🔀 6 · ⏱️ 22.11.2022):

	```
	git clone https://github.com/pyeventsourcing/eventsourcing-django
	```
- [PyPi](https://pypi.org/project/eventsourcing-django) (📥 1.1K / month):
	```
	pip install eventsourcing-django
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/pyeventsourcing/eventsourcing-eventstoredb">eventsourcing-eventstoredb</a></b> (🥉4 ·  ⭐ 6) - Python package for eventsourcing with EventStoreDB. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pyeventsourcing/eventsourcing-dynamodb">eventsourcing-dynamodb</a></b> (🥉4 ·  ⭐ 3) - Python package for eventsourcing with DynamoDB. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pyeventsourcing/eventsourcing-axonserver">eventsourcing-axonserver</a></b> (🥉4 ·  ⭐ 1) - Python package for eventsourcing with Axon Server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Locking

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/saxix/django-concurrency">django-concurrency</a></b> (🥇18 ·  ⭐ 400) - Optimistic lock implementation for Django. Prevents users from doing concurrent editing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/saxix/django-concurrency) (👨‍💻 24 · 🔀 46 · 📋 66 - 9% open · ⏱️ 04.08.2022):

	```
	git clone https://github.com/saxix/django-concurrency
	```
- [PyPi](https://pypi.org/project/django-concurrency) (📥 20K / month):
	```
	pip install django-concurrency
	```
</details>
<details><summary><b><a href="https://github.com/gavinwahl/django-optimistic-lock">django-optimistic-lock</a></b> (🥉12 ·  ⭐ 110 · 💤) - Offline optimistic locking for Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/gavinwahl/django-optimistic-lock) (👨‍💻 4 · 🔀 20 · 📦 12 · 📋 5 - 20% open · ⏱️ 02.01.2019):

	```
	git clone https://github.com/gavinwahl/django-optimistic-lock
	```
- [PyPi](https://pypi.org/project/django-optimistic-lock) (📥 3.5K / month):
	```
	pip install django-optimistic-lock
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/debrouwere/django-locking">django-locking</a></b> (🥉7 ·  ⭐ 140 · 💀) - Prevents users from doing concurrent editing in Django. Works out of the box in the admin interface, or you can.. <code>❗Unlicensed</code>
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
