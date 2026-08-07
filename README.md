# FrontierPass Web

Official corporate website for FrontierPass.

This repository contains the public-facing website for FrontierPass.

**Website**
https://frontierpass.net

The actual FrontierPass platform is maintained separately.

**Platform**
https://app.frontierpass.net

This repository should only contain the marketing and corporate website.

---

# Purpose

The purpose of this website is to introduce FrontierPass to the world.

It should communicate:

- What FrontierPass is
- Why FrontierPass exists
- What we are building
- What we have already accomplished
- How organizations can collaborate with us

The website is designed primarily for:

- Large enterprises
- Universities
- Governments
- Investors
- Foundations
- Startup ecosystems

The learning platform itself is **not** part of this repository.

---

# Brand Direction

The website should feel:

- Premium
- Quiet
- Minimal
- Modern
- Trustworthy
- Human
- Long-term

We are **not** trying to look like:

- An NGO
- A charity
- An online course platform
- A recruitment agency
- A flashy startup

Instead, the website should feel closer to companies such as:

- Apple
- Stripe
- Palantir
- Linear

Confidence should come from execution, not decoration.

---

# Visual Identity

## Colors

### Background

White

### Primary Text

Black

### Accent

`#02772e`

Use the accent color intentionally.

Recommended usage:

- Buttons
- Important links
- Section highlights
- Statistics
- Icons

The website should remain mostly white.

Whitespace is part of the design.

---

## Typography

- Large headings
- Minimal body text
- Large margins
- Generous whitespace
- One idea per section

Avoid overwhelming visitors with information.

---

## Photography

Photography is one of the strongest assets of FrontierPass.

Always prioritize real FrontierPass photography.

Preferred images:

- Hackathons
- Universities
- Students collaborating
- Community events
- Workshops
- Field visits
- Team collaboration

Avoid:

- AI-generated people
- Generic African stock photography
- Charity-style imagery
- Poverty-focused storytelling

We are showcasing capability, not sympathy.

---

# Website Structure

The first version should contain only four pages.

- Home
- Solutions
- Vision
- About

Navigation:

- Our Work
- Solutions
- Vision
- About
- Login

The homepage should remain concise.

Additional details belong on dedicated pages.

---

# Homepage Structure

The homepage should communicate FrontierPass within one minute.

## 1. Hero

- Vision
- CTA

---

## 2. Talent is Everywhere

Headline:

> Talent is everywhere.  
> Opportunity isn't.

Keep text minimal.

Communicate the global opportunity gap.

---

## 3. Learn → Practice → Work

Illustrate the FrontierPass pipeline.

Keep explanations concise.

Show how FrontierPass creates trust.

---

## 4. Built on the Ground

Introduce FrontierPass's regional presence.

Display regional cards:

- Nigeria
- India
- Japan

Each card should include:

- Hero image
- Short description
- Learn More button

Regional websites:

- nigeria.frontierpass.net
- india.frontierpass.net
- japan.frontierpass.net

Regional sites should contain:

- Activities
- Universities
- Partners
- Events
- Communities
- Programs
- News

The global homepage should avoid excessive regional detail.

---

## 5. Solutions

Enterprise-focused.

Examples:

- Talent Development
- Innovation Programs
- Local Ecosystem Building
- University Collaboration

CTA:

> Explore Solutions

---

## 6. Vision

Keep this section inspirational.

Do not explain the entire roadmap.

Simply communicate the long-term direction.

CTA:

> Read Our Vision

---

## 7. Footer

Include:

- Company information
- Navigation
- Social links
- Newsletter (optional)

---

# Regional Websites

FrontierPass operates globally through regional ecosystems.

The homepage introduces FrontierPass globally.

Each country should have its own website.

Examples:

- nigeria.frontierpass.net
- india.frontierpass.net
- japan.frontierpass.net

Regional websites should contain:

- Local partnerships
- Activities
- Universities
- Community
- Events
- Programs
- News

This architecture allows FrontierPass to scale naturally into additional countries.

---

# Motion

Motion should be minimal and elegant.

Recommended:

- Fade-in
- Image reveal
- Sticky navigation
- Smooth transitions
- Hover effects
- Number counters

Avoid:

- Heavy animations
- Excessive parallax
- Large gradients
- Flashy effects

---

# Technical

Website

```
frontierpass.net
```

Platform

```
app.frontierpass.net
```

Deploy separately.

---

# Development Rules

## Never push directly to `main`

Always create a feature branch.

Examples:

```
feature/homepage
feature/vision-page
fix/navbar
content/update-copy
```

---

## Keep Pull Requests focused

One Pull Request should solve one problem.

Avoid combining unrelated work.

---

## Reuse Components

Create reusable components whenever possible.

Examples:

- Buttons
- Cards
- Navigation
- Footer
- Section headings
- CTA blocks

Avoid duplicate code.

---

## Preserve the Design System

Do not introduce:

- New colors
- New fonts
- Inconsistent spacing
- Different button styles
- Random border radius values

without discussion.

Consistency is more important than creativity.

---

## Respect Whitespace

Empty space is intentional.

Do not add content simply because there is room.

Every section should breathe.

---

## Mobile First

Every page must work correctly on:

- Desktop
- Tablet
- Mobile

Always verify responsiveness before opening a Pull Request.

---

## Performance

Keep the website lightweight.

Requirements:

- Optimized images
- Lazy loading
- Minimal JavaScript
- Fast loading

Many users access FrontierPass through slower mobile networks.

Performance matters.

---

## Content Accuracy

Never publish unverified:

- Statistics
- Partner logos
- Customer logos
- Supporter logos
- Company names
- Team members

Relationship labels must always be accurate.

Examples:

- Partner
- Supporter
- Collaborator
- Program Participant

These are **not** interchangeable.

---

# Commit Messages

Use meaningful commit messages.

Good examples:

```
feat: add homepage hero
feat: create vision page
fix: mobile navigation
refactor: simplify footer
content: update homepage copy
```

Avoid:

```
update
changes
fix
final
```

---

# Pull Request Checklist

Before requesting review:

- [ ] The page works locally
- [ ] Mobile layout has been checked
- [ ] No console errors
- [ ] Images are optimized
- [ ] Links work correctly
- [ ] The design system has been preserved
- [ ] Copy has been reviewed
- [ ] No unverified claims were added

---

# Repository Scope

This repository only contains the FrontierPass corporate website.

Do **not** add:

- Platform features
- Admin tools
- Backend logic
- Internal dashboards
- Experimental projects

Those belong in separate repositories.

---

# Related Repositories

## frontierpass-web

Corporate website

```
https://frontierpass.net
```

---

## frontierpass-platform

Learning platform and user dashboard

```
https://app.frontierpass.net
```

---

# Final Principle

Every design decision should answer one question:

> **Does this make FrontierPass feel like a company quietly building the future over the next 20 years?**

If the answer is **no**, reconsider the implementation.
