# Product Requirements Document (PRD)

# GrowIN

### AI Personal Branding OS

**Version:** 1.0

**Status:** Draft

**Founder:** Abdul Azeem

---

# 1. Vision

GrowIN is an AI-powered SaaS platform that helps professionals consistently build their personal brand on LinkedIn.

Instead of acting as another AI writing tool, GrowIN works as an intelligent branding assistant that understands the user's goals, writing style, audience, and expertise to create authentic, high-performing LinkedIn content.

Our mission is to eliminate writer's block and help users grow their authority, audience, and career opportunities.

---

# 2. Problem Statement

Professionals struggle with consistently creating high-quality LinkedIn content.

Common problems include:

* Not knowing what to post
* Running out of ideas
* Generic AI-generated content
* Poor hooks
* Weak storytelling
* Inconsistent posting
* No personal brand strategy
* Low engagement
* Lack of confidence

Existing AI writing tools only generate text.

They don't understand the user.

---

# 3. Solution

GrowIN becomes the user's AI Personal Branding Assistant.

Instead of asking:

"Write me a LinkedIn post."

GrowIN asks intelligent questions.

It understands:

* Who the user is
* Their goals
* Their audience
* Their writing style
* Their expertise

Then generates content that sounds authentic.

---

# 4. Product Goals

Primary Goals

* Help users publish consistently.
* Improve content quality.
* Increase engagement.
* Build authority.
* Generate business opportunities.

Secondary Goals

* Save time.
* Reduce writer's block.
* Teach better writing.
* Build long-term personal branding habits.

---

# 5. Target Audience

Primary

* Freelancers
* Designers
* Developers
* Startup founders
* Students
* Agency owners

Secondary

* Coaches
* Recruiters
* Product managers
* Marketers
* Consultants

---

# 6. User Personas

## Persona 1

Name

Sarah

Profession

UI/UX Designer

Goal

Get freelance clients through LinkedIn.

Pain Points

* Doesn't know what to post.
* Doesn't enjoy writing.
* Wants authority.

---

## Persona 2

Name

Ahmed

Profession

Software Engineer

Goal

Build audience and get remote jobs.

Pain Points

* Writes inconsistently.
* Doesn't know storytelling.

---

## Persona 3

Name

Emily

Profession

Startup Founder

Goal

Share startup journey.

Pain Points

* Limited time.
* Needs fast content.

---

# 7. Product Positioning

GrowIN is not an AI writer.

GrowIN is an AI Personal Branding Operating System.

It combines:

* AI Writing
* Strategy
* Memory
* Analytics
* Brand Voice
* Planning

---

# 8. Core Features (MVP)

## Feature 1

AI Interview Mode

Description

Instead of prompting the AI manually, users answer guided questions.

Example Flow

What happened today?

↓

Why is it important?

↓

What lesson did you learn?

↓

Who should read this?

↓

What action should readers take?

↓

Generate post.

Priority

Critical

---

## Feature 2

LinkedIn Post Generator

Supports

* Story
* Educational
* Tutorial
* Build in Public
* Case Study
* Hot Take
* Career
* Startup
* Design
* Technology

Priority

Critical

---

## Feature 3

Hook Generator

Generate

10 hooks.

Provide

* Hook score
* Curiosity score
* Improvement suggestions

Priority

High

---

## Feature 4

Rewrite Assistant

Modes

* Professional
* Casual
* Storytelling
* Founder
* Educational
* Shorter
* Longer
* Viral

Priority

High

---

## Feature 5

Brand Voice

User configures

* Writing style
* Industry
* Audience
* Tone
* Emoji usage
* Sentence length
* CTA style

AI remembers these settings.

Priority

High

---

## Feature 6

Content History

Users can

* Save drafts
* Edit drafts
* Delete drafts
* Duplicate drafts
* Search drafts

Priority

Medium

---

## Feature 7

CTA Generator

Generate

* Engagement CTA
* Follow CTA
* Client CTA
* Newsletter CTA
* Discussion CTA

Priority

Medium

---

## Feature 8

Hashtag Generator

Generate

Relevant hashtags with explanation.

Priority

Medium

---

# 9. Future Features

* Carousel Generator
* Content Calendar
* AI Profile Review
* Analytics Dashboard
* LinkedIn Scheduler
* AI Comments
* AI Replies
* Team Workspace
* Multi-platform publishing
* Newsletter Generator
* Video Script Generator
* AI Research Assistant

---

# 10. User Flow

Landing Page

↓

Sign Up

↓

Complete Onboarding

↓

Create Brand Profile

↓

Dashboard

↓

Choose Tool

↓

Interview Mode

↓

Generate Content

↓

Edit

↓

Save

↓

Export

↓

Publish

---

# 11. Technical Architecture

Frontend

* Next.js
* TypeScript
* Tailwind CSS
* shadcn/ui
* Framer Motion

Backend

* Python
* FastAPI
* SQLAlchemy
* Pydantic

Database

* PostgreSQL (Supabase)

Authentication

* Supabase Auth

Storage

* Supabase Storage

AI Providers

* Gemini
* OpenAI
* Anthropic

Deployment

Frontend

* Vercel

Backend

* Railway

Database

* Supabase

---

# 12. Database Design

Users

* id
* name
* email
* avatar
* created_at

Profiles

* id
* user_id
* profession
* niche
* audience
* writing_style
* tone
* goals

Posts

* id
* user_id
* title
* content
* type
* created_at
* updated_at

Drafts

* id
* user_id
* content
* status

Brand Voice

* id
* user_id
* sentence_length
* emoji_preference
* tone
* vocabulary_level
* cta_style

Generation History

* id
* user_id
* prompt
* output
* model
* created_at

---

# 13. API Endpoints

Authentication

POST /auth/signup

POST /auth/login

POST /auth/logout

Profile

GET /profile

PUT /profile

AI

POST /generate/post

POST /generate/hooks

POST /generate/rewrite

POST /generate/cta

POST /generate/hashtags

Brand Voice

GET /brand

PUT /brand

Posts

GET /posts

POST /posts

PUT /posts/{id}

DELETE /posts/{id}

History

GET /history

---

# 14. UI Pages

Landing Page

Authentication

Dashboard

Interview Generator

Post Generator

Hook Generator

Rewrite Tool

Brand Voice

Saved Posts

Settings

Pricing

Profile

---

# 15. Non-Functional Requirements

* Mobile responsive
* Dark mode
* Fast response times
* Secure authentication
* Clean architecture
* Modular codebase
* REST API
* Scalable database
* Error handling
* Logging
* Type safety
* Environment variable management

---

# 16. Success Metrics

* Daily Active Users
* Weekly Active Users
* Posts Generated
* Posts Saved
* Average Session Time
* User Retention
* Conversion to Paid Plan
* User Satisfaction
* Time Saved Per User

---

# 17. Monetization

Free

* Limited generations/day
* Basic AI model
* Basic templates

Pro

* Unlimited generations
* Premium AI models
* Brand Voice
* Content Calendar
* Analytics
* Priority generation
* Export options

Team

* Multiple users
* Shared workspace
* Collaboration
* Team analytics
* Shared templates

---

# 18. Design Principles

* Minimal interface
* Fast interactions
* Professional aesthetics
* Excellent typography
* Consistent spacing
* Accessibility first
* Dark mode by default
* Mobile-friendly
* AI should assist, never overwhelm

---

# 19. Development Principles

* Build reusable components.
* Keep business logic separate from UI.
* Follow clean architecture.
* Write modular APIs.
* Use environment variables for secrets.
* Use version control from day one.
* Document all major decisions.
* Optimize for maintainability over shortcuts.

---

# 20. Long-Term Vision

GrowIN will evolve from a LinkedIn content assistant into a complete Personal Branding Operating System.

Future capabilities include:

* Cross-platform publishing
* AI brand strategy
* Content performance analytics
* AI research
* Personal knowledge base
* CRM integration
* Email newsletter generation
* Team collaboration
* Enterprise workspaces

The long-term mission is to become the default workspace professionals use to build and manage their online reputation.
