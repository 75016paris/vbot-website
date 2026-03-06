# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A minimalist static website for a TikTok automation tool ("Channel Tools" / TikBot Creator Tool). The site is hosted on Vercel and serves as the public-facing presence for a backend bot running on Google Cloud Platform that automates TikTok video posting and scheduling.

## Site Structure (planned)

- `index.html` — Landing page with a starfield/constellation background, product description, and footer links
- `privacy.html` — Privacy Policy page (`/privacy`)
- `terms.html` — Terms of Service page (`/terms`)

## Content & Legal Text

The README.md contains the full draft text for both the Privacy Policy and Terms of Service. When creating these pages, use that content directly — placeholders like `[Ton Nom ou Société]`, `[URL du site]`, `[Date]`, `[Ton Pays]`, and `[Ton Email]` need to be filled in with real values before publishing.

## Design Direction

- Minimalist aesthetic
- Starfield / constellation animation on the homepage background
- Footer with clearly visible links to Privacy Policy and Terms of Service
- Primary language: French (content in README is French)

## Deployment

- Target hosting: Vercel
- Backend bot: Google Cloud Platform (separate from this website repo)
- TikTok API integration is backend-only; this site is purely frontend/static
