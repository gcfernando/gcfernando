---
layout: default
title: "Gehan Fernando — C#, .NET, Python and Developer Projects"
description: "Explore Gehan Fernando’s open-source libraries, desktop applications, developer tools, datasets and programming guides."
permalink: /projects/
---

# 🧭 Gehan Fernando — Project Catalog

Explore the public project collection: .NET libraries, Windows desktop applications, Python examples, developer references, datasets and MicroPython hardware learning. Each project links to its documentation, source and sitemap.

<div class="project-grid">
{% for project in site.data.projects %}
<section class="project-card">
<p class="eyebrow">{{ project.category }}</p>
<h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
<p>{{ project.description }}</p>
<div class="project-links"><a href="{{ project.guides }}">Explore guides</a><a href="{{ project.source }}">GitHub source</a><a href="{{ project.sitemap }}">Sitemap</a></div>
</section>
{% endfor %}
</div>

<!-- Preserve links to earlier section headings. -->
<a id="projects-with-repository-documentation"></a>
<a id="choose-a-starting-point"></a>

## 📚 Projects with repository documentation

- [Pipewarden — local and CI quality gates](https://github.com/gcfernando/pipewarden): Python CLI for supported language toolchains, secret scanning and machine-readable reports. Its repository includes configuration, contribution and release guides.

## 🚀 Choose a starting point

- **Learn programming:** begin with the Python, C#/.NET, VB.NET or knowledge-base guides.
- **Build desktop applications:** explore Glass.Message, Spectrum, Audio8D and the [Aster Windows calculator guides](https://gcfernando.github.io/aster/documentation/).
- **Improve logging:** read the Nilog documentation and examples.
- **Practice with data:** browse the CSV dataset collection.
- **Learn hardware basics:** start with the Pico 2 W LED example.
- **Explore developer references:** browse the project lab’s Linux and AI coding add-on guides.

## 🧪 Verify before getting started

Each card links to a separate project with its own prerequisites, supported platforms, support and license terms. Start from the repository README when installing or running code. The catalog is a navigation aid; package availability and live pages can change.

## 🔗 Related documentation

[Profile overview](README.md) · [Documentation index](documentation.md)
