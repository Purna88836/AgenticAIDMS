---
# Fill in the fields below to create a basic custom agent for your repository.
# The Copilot CLI can be used for local testing: https://gh.io/customagents/cli
# To make this agent available, merge this file into the default repository branch.
# For format details, see: https://gh.io/customagents/config

name: AI-Powered Dropshipping Automation Platform
description:
AI-Powered Dropshipping Automation Platform

# My Agent
AI-Powered Dropshipping Automation Platform
Objective

Build an AI-driven dropshipping automation platform that minimizes manual effort by automating product research, product listing creation, marketing content generation, customer support, and sales analytics.

Components to Implement
1. Product Research Agent

Purpose: Identify profitable products automatically.

Features:

Collect trending products from Amazon, Flipkart, Google Trends, and social media platforms.
Analyze customer reviews and sentiment.
Calculate demand, competition, and profitability scores.
Generate daily product recommendations.

Output:

{
  "product": "Portable Blender",
  "demand_score": 85,
  "competition_score": 40,
  "profitability_score": 78,
  "recommendation": "High Potential"
}
2. Product Listing Generator Agent

Purpose: Automatically create e-commerce product listings.

Features:

Generate SEO-friendly titles.
Create detailed product descriptions.
Generate feature lists and FAQs.
Create meta tags and keywords.
Publish listings via Shopify API.

Output:

Product title
Description
SEO metadata
Product images (optional AI-generated)
3. Marketing Content Agent

Purpose: Generate promotional content for multiple channels.

Features:

Create Instagram posts and captions.
Generate Facebook ad copy.
Create email marketing campaigns.
Generate blog content and SEO articles.
Produce short-form video scripts.

Output:

Social media content calendar
Ad creatives
Email campaigns
4. Customer Support Agent

Purpose: Automate customer interactions.

Features:

AI chatbot for website and WhatsApp.
Order tracking assistance.
FAQ handling.
Return and refund support.
Escalation to human support when required.

Technology:

RAG (Retrieval Augmented Generation)
Vector Database
OpenAI/Azure OpenAI
5. Sales & Analytics Agent

Purpose: Monitor business performance and provide insights.

Features:

Track orders and revenue.
Monitor ad spend and ROAS.
Analyze customer feedback.
Generate daily and weekly reports.
Provide AI-generated business recommendations.

Example Insight:

Sales decreased by 18% this week.
Primary reason: Facebook ad CTR dropped by 22%.
Recommendation: Pause Ad Set B and increase budget on Ad Set A.
Recommended Technology Stack
Backend
Python
FastAPI
PostgreSQL
AI Layer
OpenAI GPT-4o / GPT-5
LangGraph
CrewAI
Vector Database
Qdrant
ChromaDB
Frontend
React
Next.js
Integrations
Shopify API
Meta Ads API
Google Trends API
WhatsApp Business API
Success Criteria
80–90% automation of dropshipping operations.
Daily automated product recommendations.
One-click product publishing.
Automated marketing content generation.
AI-powered customer support.
Real-time business analytics dashboard.
Suggested Development Phases

Phase 1

Product Research Agent
Listing Generator Agent

Phase 2

Marketing Agent
Analytics Dashboard

Phase 3

Customer Support Agent
WhatsApp Integration

Phase 4

Multi-Agent Orchestration using LangGraph/CrewAI
Full workflow automation

Can you build application by considering all  above scenarios ?
