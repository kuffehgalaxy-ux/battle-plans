# Battle Plans - Developer Bible

Version: 0.1

This document defines the engineering standards, architecture and development practices for Battle Plans.

The objective is to ensure that every contribution is consistent, maintainable and scalable.

---

# Philosophy

Battle Plans is designed to solve real officer workflows.

Technical decisions should prioritise:

- Simplicity
- Readability
- Reliability
- Mobile-first design
- Maintainability

Never introduce complexity without measurable benefit.

---

# Technology Stack

## Frontend

- Next.js
- React
- TypeScript

## Styling

- Tailwind CSS

## Backend

- Supabase

## Database

- PostgreSQL

## Authentication

- Discord OAuth

## Hosting

- Vercel

## Source Control

- GitHub

---

# Core Principles

## Officer First

Every feature must reduce officer workload.

## Mobile First

Design for mobile before desktop.

## Component Driven

Reusable components should always be preferred.

## One Source of Truth

Avoid duplicated logic or duplicated data.

## Documentation First

Major features should be documented before implementation.

---

# Coding Standards

- TypeScript Strict Mode enabled.
- Functional React components only.
- Use hooks.
- Avoid unnecessary state.
- Components should remain small and focused.
- Prefer composition over inheritance.

---

# Naming Conventions

Components

PascalCase

Example:

BattlePlanCard.tsx

Hooks

camelCase beginning with "use"

Example:

useGuild.ts

Types

PascalCase

Example:

GuildMember

Functions

camelCase

Example:

publishOrders()

Constants

UPPER_SNAKE_CASE

Example:

MAX_DEPLOYMENT_GP

---

# Folder Structure

app/
components/
features/
hooks/
lib/
services/
types/
styles/
docs/
public/

Each feature should remain self-contained where possible.

---

# Git Branch Strategy

main

Always stable.

develop

Integration branch.

feature/*

One feature per branch.

Examples:

feature/action-board

feature/publish-orders

feature/discord-login

---

# Pull Requests

Every Pull Request should include:

- Purpose
- Screenshots (if UI)
- Documentation updates
- Acceptance Criteria

---

# Documentation Rule

No feature is complete unless:

- Documentation updated
- UI updated
- Acceptance Criteria met

---

# Performance Goals

Battle Plans should:

- Load quickly on mobile.
- Require minimal clicks.
- Minimise page reloads.
- Prefer live updates where possible.

---

# Accessibility

All interactive elements should:

- Support keyboard navigation
- Meet colour contrast guidelines
- Include accessible labels

---

# Security

Never store Discord tokens directly.

Authentication should always use OAuth.

All officer actions should be permission checked.

---

# Future Expansion

Architecture should support:

- Multiple guilds
- Alliances
- Territory Battles
- Territory Wars
- Raids

without major redesign.
