# AI Marketing Automation Crew (CrewAI Project)

An end-to-end AI-powered marketing automation system built using CrewAI and LLMs.

This project simulates a real marketing team where multiple AI agents collaborate to perform:

Market research
Strategy planning
Content creation
Blog writing
SEO optimization

# Project Overview

This system creates a multi-agent marketing workflow where each AI agent has a specialized role:

# Agent	Responsibility
Head of Marketing	Research & strategy planning
Social Media Content Creator	Posts, reels & content calendar
Blog Writer	Blog research & drafting
SEO Specialist	Optimization for search engines

The agents collaborate sequentially to produce a complete marketing pipeline from scratch.

# Tech Stack
CrewAI
LLM: Gemini (gemini-2.5-flash)
SerperDevTool (Search)
Web Scraping Tools
File Handling Tools
Python

# Architecture

User Input

    ↓
   
Head of Marketing (Research + Strategy)

    ↓
   
Content Creator (Calendar + Posts + Reels)

    ↓
   
Blog Writer (Research + Draft Blogs)

    ↓
   
SEO Specialist (Optimization)

    ↓
   
Final Output Files (Markdown)

# Features

✅ Multi-agent collaboration

✅ Real-world marketing workflow simulation

✅ Automated content generation

✅ SEO optimization pipeline

✅ File-based output storage

✅ Tool-augmented AI (search + scraping + file ops)


# Project Structure

├── main.py

├── resources/

│   ├── drafts/

│   │   ├── marketing_strategy.md

│   │   ├── content_calendar.md

│   │   ├── posts/

│   │   ├── reels/

│   │   └── blogs/

# Agents
1. Head of Marketing
   
Market research

Competitor analysis

Strategy creation

2. Social Media Content Creator
   
Content calendar

Social media posts

Reel scripts

3. Blog Writer
   
Blog topic research

Blog drafting

4. SEO Specialist
   
Keyword optimization

Meta tags

Internal linking

# Tasks Pipeline
Market Research

Marketing Strategy

Content Calendar

Social Media Drafts

Reel Scripts

Blog Research

Blog Drafting

SEO Optimization

# Output

The system automatically generates:

Marketing Strategy

Content Calendar

Social Media Posts

Reel Scripts

Blog Articles

SEO Optimized Content
