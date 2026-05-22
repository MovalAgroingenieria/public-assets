# Moval Public Assets

Public static assets used by Moval Agroingeniería repositories, documentation, and module README files.

This repository is intended to provide stable, public URLs for shared resources such as logos, badges, and common images used across multiple repositories.

## Purpose

Many Moval repositories need to reference the same public images in their `README.rst` or documentation files.

Instead of duplicating those files in every repository, this repository centralizes them in a single public location.

## Available assets

### Logos

| File | Description |
|---|---|
| `logos/moval_logo_small.png` | Moval Agroingeniería logo in PNG format used in repository README |
| `logos/logo_color_moval_agro_h.svg` | Moval Agroingeniería logo color horizontal in SVG format  |

## Usage in README.rst

Recommended usage with a versioned tag:

```rst
.. image:: https://raw.githubusercontent.com/MovalAgroingenieria/public-assets/logos/moval_logo_small.png
   :alt: Moval Agroingeniería
   :width: 220px
