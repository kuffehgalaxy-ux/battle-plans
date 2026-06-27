# Battle Plans - Project Bible

> **Plan. Track. Command.**

---

# 1. Vision

Battle Plans is an intelligent command centre for **Star Wars: Galaxy of Heroes** guild officers.

Its purpose is to simplify Territory Battle management by bringing planning, tracking, communication and decision making into a single application.

Rather than requiring officers to constantly switch between the game, Discord, spreadsheets and bots, Battle Plans provides one place to understand the guild's current situation and decide what action to take.

---

# 2. Mission

Reduce the amount of time officers spend gathering information, allowing them to focus on making decisions and leading their guild.

Battle Plans should become the first place an officer opens during a Territory Battle.

---

# 3. Core Principles

Battle Plans follows seven core principles.

## Officer First

Every feature must help officers perform their role more efficiently.

## Plan vs Reality

Always compare what the guild intended to do with what is actually happening.

## Reduce Clicks

If the app can save officers from navigating multiple screens or tools, it should.

## Actionable Information

Information should always lead naturally to an action.

## Mobile First

The application should feel natural on a phone while remaining fully functional on desktop.

## Keep It Simple

A smaller number of excellent features is preferable to a larger number of average ones.

## Reduce Uncertainty

Battle Plans should tell officers what they need to know rather than make them search for it.

---

# 4. Product Goals

Battle Plans exists to help officers answer three questions.

## What is happening?

Current progress, stars, GP, combat missions, deployments and participation.

## What should we do?

Current strategy, deployment order and recommended actions.

## Who still needs to act?

Players requiring reminders or additional actions.

If a feature does not help answer one of these questions, it should be reconsidered before being added.

---

# 5. Product Scope

## In Scope (Version 1)

- Territory Battle Dashboard
- Battle Planning
- Officer Command Centre
- Member Participation Tracking
- Combat Mission Tracking
- Deployment Tracking
- Discord Notifications
- Officer Reminders
- Reports
- Phase Review

## Future Scope

- Territory Wars
- Raid Dashboard
- Guild Tickets
- Galactic Legend Tracker
- Capital Ship Tracker
- Guild Achievements
- Recruitment Tools
- Guild Analytics

## Out of Scope

- Playing SWGOH
- Mod Management
- Farming Guides
- Roster Optimisation
- Character Management

---

# 6. Design Philosophy

Battle Plans follows five design principles.

1. Mobile First
2. Officer First
3. Information before Decoration
4. Fewer Clicks than SWGOH
5. Every Screen Answers a Question

---

# 7. User Interface Principles

Every Battle Plans screen should follow the same structure.

## Status

What is happening?

## Attention

What requires officer attention?

## Action

What should happen next?

## Detail

Additional information for officers who wish to investigate further.

---

# 8. Information Hierarchy

Battle Plans follows a progressive disclosure approach.

## At a Glance

The most important information should be visible immediately.

## Quick Scroll

Supporting information should be available with minimal scrolling.

## Deep Dive

Detailed reports and member-level information should only appear when requested.

The goal is to minimise cognitive load while ensuring officers always know where to find more information.

---

# 9. User Personas

## Guild Leader

Needs strategic visibility across the entire guild.

Responsible for planning and overall performance.

---

## Officer

Needs actionable information.

Responsible for monitoring progress, issuing orders and helping members complete objectives.

---

## Guild Member

Needs simple instructions.

Responsible for completing assigned actions.

---

# 10. Officer Workflow

```
Login
    ↓
Command Centre
    ↓
Officer Inbox
    ↓
Review Battle Plan
    ↓
Issue Orders
    ↓
Monitor Progress
    ↓
Review Phase
    ↓
Prepare Next Phase
```

---

# 11. Navigation

```
🏠 Command Centre

⚔ Territory Battle

📋 Battle Plans

👥 Guild

📊 Reports

📥 Officer Inbox

⚙ Settings
```

---

# 12. Minimum Viable Product (MVP)

Version One will include:

- Command Centre
- Territory Battle Dashboard
- Battle Plans
- Phase Tracking
- Member Status
- Officer Inbox
- Discord Orders
- Discord Reminders
- Phase Reports

---

# Battle Plans

Battle Plans are the operational strategy for a Territory Battle phase.

A Battle Plan defines:

- Priority objectives
- Deployment order
- Combat mission expectations
- Officer notes
- Discord orders

Battle Plans should be versioned.

Every update should record:

- Version number
- Author
- Timestamp
- Summary of changes

This ensures all officers are working from the same plan.

## Publishing

Battle Plans support two publication types.

### Officer Plan

A complete operational briefing published to the officer Discord channel.

Includes:

- Current Battle Plan
- Objectives
- Officer Notes
- Version Number
- Timestamp
- Author

Purpose:

Maintain a permanent operational record and ensure all officers work from the same strategy.

---

### Member Orders

A simplified version of the Battle Plan published to the member orders channel.

Includes:

- Current Objectives
- Deployment Instructions
- Combat Mission Instructions

Purpose:

Provide members with clear, concise instructions without exposing officer planning discussions.

---

# 13. Definition of Done

A feature is considered complete when it:

- Solves a real officer problem.
- Works well on mobile.
- Requires fewer clicks than SWGOH.
- Can be understood within ten seconds.
- Supports future expansion.
- Is documented.
- Has been tested.

---

# 14. Success Metrics

Battle Plans will be considered successful if it:

- Reduces officer workload.
- Reduces time spent opening the game.
- Replaces multiple officer tools.
- Keeps guilds on their Battle Plan.
- Reduces manual reminders.
- Makes Territory Battles easier to manage.

---

# 15. Project Team

## Product Owner

Responsible for:

- Product Vision
- Prioritisation
- Testing
- User Feedback

---

## Technical Lead

Responsible for:

- Architecture
- Development
- UX Design
- Documentation

---

# 16. Version Roadmap

```
v0.1
Foundation
    ↓
v0.2
UI Design
    ↓
v0.3
Interactive Prototype
    ↓
v0.4
Discord Integration
    ↓
v0.5
Alpha Testing
    ↓
v1.0
GreyForceHeroes completes an entire Territory Battle using Battle Plans as its primary officer tool.
    ↓
v2.0
Public Release
```

---

# 17. North Star

Battle Plans should become the first application an officer opens during a Territory Battle.

An officer should be able to understand the current situation, decide what needs to happen next and communicate those instructions without opening the game simply to gather information.

# Product Values

Battle Plans should always strive to be:

## Clear

Information should be understandable within seconds.

## Reliable

Officers should be able to trust the information presented.

## Actionable

Every important piece of information should naturally lead to an action.

## Respectful

The application should assist officers and members without creating unnecessary pressure or noise.

## Expandable

Every feature should be designed so that future events such as Territory Wars, Raids and Guild Management can be added without redesigning the application.

# North Star Goal

Battle Plans should become the first application a Guild Leader or Officer opens during a Territory Battle.

An officer should be able to understand the current state of the guild, make decisions, communicate orders and identify outstanding actions without opening Star Wars: Galaxy of Heroes.

Every feature should move the product closer to this goal.
---

# 18. Product Philosophy

Battle Plans is not intended to replace Star Wars: Galaxy of Heroes.

Players will always play the game.

Battle Plans replaces the administrative work surrounding the game.

It transforms information into decisions.

Instead of asking:

> "What is happening?"

It should answer:

> "Here's what's happening, here's what needs attention, and here's what you should do next."

---

# 19. Future Vision

Battle Plans begins as a Territory Battle assistant.

Its long-term vision is to become the complete operating system for SWGOH guild officers.

Supporting:

- Territory Battles
- Territory Wars
- Raids
- Guild Administration
- Officer Collaboration
- Strategic Planning

One application.

One command centre.


# 20. Product Philosophy

Battle Plans exists to reduce the workload of guild officers.

The application should answer four questions within seconds:

1. What is happening?
2. What needs attention?
3. What should happen next?
4. Who still needs to act?

Every screen should recommend an action whenever possible.

Battle Plans should reduce the number of clicks, context switching and manual Discord messages required to successfully manage guild events.

If a feature does not help an officer make a better decision faster, it should be reconsidered.

# 21. Design Language

Battle Plans should feel like a professional command console.

The interface should take inspiration from military operations centres and Star Wars command bridges rather than the game's user interface.

## Visual Identity

- Dark graphite backgrounds
- Metallic silver panels
- Holographic blue highlights
- Republic green success indicators
- Amber warning indicators
- Imperial red critical alerts

The interface should feel clean, calm and professional.

Star Wars should be felt through the design language rather than through obvious branding or artwork.


