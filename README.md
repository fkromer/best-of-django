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
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-10-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/fkromer/best-of-django/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/fkromer/best-of-django?color=green&label=updated"></a>
</p>

This curated list contains 10 awesome open-source projects with a total of 24K stars grouped into 7 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/fkromer/best-of-django/issues/new/choose), submit a [pull request](https://github.com/fkromer/best-of-django/pulls), or directly edit the [projects.yaml](https://github.com/fkromer/best-of-django/edit/main/projects.yaml). Contributions are very welcome!

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Admin Interface](#admin-interface) _1 projects_
- [Concurrent Data Access](#concurrent-data-access) _3 projects_
- [Finite State Machine](#finite-state-machine) _1 projects_
- [RESTful API](#restful-api) _1 projects_
- [GraphQL API](#graphql-api) _4 projects_
- [CMS frameworks based on Django.](#cms-frameworks-based-on-django) _0 projects_
- [E-Commerce frameworks based on Django.](#e-commerce-frameworks-based-on-django) _0 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(12 months no activity)_
- 💀&nbsp; Dead project _(99999 months no activity)_
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

<details><summary><b><a href="https://github.com/sehmaschine/django-grappelli">django-grappelli</a></b> (🥇28 ·  ⭐ 3.3K · ➕) - A jazzy skin for the Django Admin-Interface (official repository). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sehmaschine/django-grappelli) (👨‍💻 82 · 🔀 640 · 📦 5K · 📋 690 - 0% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/sehmaschine/django-grappelli
	```
- [PyPi](https://pypi.org/project/django-grappelli) (📥 170K / month):
	```
	pip install django-grappelli
	```
</details>
<br>

## Concurrent Data Access

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to help providing issues w.r.t. concurrent data access._

<details><summary><b><a href="https://github.com/saxix/django-concurrency">django-concurrency</a></b> (🥇18 ·  ⭐ 390 · ➕) - Optimistic lock implementation for Django. Prevents users from doing concurrent editing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/saxix/django-concurrency) (👨‍💻 24 · 🔀 46 · 📋 65 - 7% open · ⏱️ 04.08.2022):

	```
	git clone https://github.com/saxix/django-concurrency
	```
- [PyPi](https://pypi.org/project/django-concurrency) (📥 22K / month):
	```
	pip install django-concurrency
	```
</details>
<details><summary><b><a href="https://github.com/gavinwahl/django-optimistic-lock">django-optimistic-lock</a></b> (🥉12 ·  ⭐ 110 · 💤) - Offline optimistic locking for Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/gavinwahl/django-optimistic-lock) (👨‍💻 4 · 🔀 20 · 📦 12 · 📋 5 - 20% open · ⏱️ 02.01.2019):

	```
	git clone https://github.com/gavinwahl/django-optimistic-lock
	```
- [PyPi](https://pypi.org/project/django-optimistic-lock) (📥 3.8K / month):
	```
	pip install django-optimistic-lock
	```
</details>
<details><summary><b><a href="https://github.com/debrouwere/django-locking">django-locking</a></b> (🥉7 ·  ⭐ 140 · 💤) - Prevents users from doing concurrent editing in Django. Works out of the box in the admin interface, or you can.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/debrouwere/django-locking) (👨‍💻 3 · 🔀 13 · 📦 4 · ⏱️ 15.02.2012):

	```
	git clone https://github.com/debrouwere/django-locking
	```
- [PyPi](https://pypi.org/project/django-locking) (📥 14 / month):
	```
	pip install django-locking
	```
</details>
<br>

## Finite State Machine

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement Finite State Machines (e.g. to implement workflows)._

<details><summary><b><a href="https://github.com/viewflow/django-fsm">django-fsm</a></b> (🥇28 ·  ⭐ 2.1K · ➕) - Django friendly finite state machine support. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/viewflow/django-fsm) (👨‍💻 64 · 🔀 250 · 📦 1.1K · 📋 150 - 11% open · ⏱️ 15.08.2022):

	```
	git clone https://github.com/viewflow/django-fsm
	```
- [PyPi](https://pypi.org/project/django-fsm) (📥 290K / month):
	```
	pip install django-fsm
	```
</details>
<br>

## RESTful API

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement RESTful API._

<details><summary><b><a href="https://github.com/vitalik/django-ninja">django-ninja</a></b> (🥇23 ·  ⭐ 3.5K · ➕) - Fast, Async-ready, Openapi, type hints based framework for building APIs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vitalik/django-ninja) (👨‍💻 64 · 🔀 210 · 📋 380 - 31% open · ⏱️ 20.09.2022):

	```
	git clone https://github.com/vitalik/django-ninja
	```
- [PyPi](https://pypi.org/project/encode/django-rest-framework):
	```
	pip install encode/django-rest-framework
	```
</details>
<br>

## GraphQL API

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement GraphQL API._

<details><summary><b><a href="https://github.com/graphql-python/graphene">graphene</a></b> (🥇36 ·  ⭐ 7.4K · ➕) - GraphQL framework for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene) (👨‍💻 190 · 🔀 760 · 📦 14K · 📋 960 - 11% open · ⏱️ 19.09.2022):

	```
	git clone https://github.com/graphql-python/graphene
	```
- [PyPi](https://pypi.org/project/graphene) (📥 1.4M / month):
	```
	pip install graphene
	```
</details>
<details><summary><b><a href="https://github.com/graphql-python/graphene-django">graphene-django</a></b> (🥈34 ·  ⭐ 3.9K · ➕) - Integrate GraphQL into your Django project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene-django) (👨‍💻 200 · 🔀 680 · 📦 8.6K · 📋 750 - 17% open · ⏱️ 26.09.2022):

	```
	git clone https://github.com/graphql-python/graphene-django
	```
- [PyPi](https://pypi.org/project/graphene-django) (📥 390K / month):
	```
	pip install graphene-django
	```
</details>
<details><summary><b><a href="https://github.com/strawberry-graphql/strawberry">strawberry</a></b> (🥉31 ·  ⭐ 2.6K · ➕) - A GraphQL library for Python that leverages type annotations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/strawberry-graphql/strawberry) (👨‍💻 150 · 🔀 310 · 📥 480 · 📦 650 · 📋 560 - 40% open · ⏱️ 03.10.2022):

	```
	git clone https://github.com/strawberry-graphql/strawberry
	```
- [PyPi](https://pypi.org/project/strawberry) (📥 370 / month):
	```
	pip install strawberry
	```
</details>
<details><summary><b><a href="https://github.com/strawberry-graphql/strawberry-graphql-django">strawberry-graphql-django</a></b> (🥉23 ·  ⭐ 190 · ➕) - Strawberry GraphQL Django extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/strawberry-graphql/strawberry-graphql-django) (👨‍💻 28 · 🔀 39 · 📋 110 - 44% open · ⏱️ 01.10.2022):

	```
	git clone https://github.com/strawberry-graphql/strawberry-graphql-django
	```
- [PyPi](https://pypi.org/project/strawberry-graphql-django) (📥 16K / month):
	```
	pip install strawberry-graphql-django
	```
</details>
<br>

## CMS frameworks based on Django.

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Content Management Systems which use Django under the hood._

<br>

## E-Commerce frameworks based on Django.

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_E-Commerce frameworks which use Django under the hood._


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
