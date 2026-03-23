# Cursor Rules for Lifecycle Agent Development

## Context
Developing agentic skills for B2B SaaS Lifecycle Management focusing on:
- Trial Activation
- Trial Monetization
- Paid Customer Onboarding
- Paid Customer Expansion

## Core Principles
1. **Cohort-First Thinking**: Always consider segmentation and cohort analysis
2. **Data-Driven**: Leverage MCP connections for real-time analytics
3. **Enrichment Priority**: Enrich user/account data with demos, behavioral, firmographic, and technographic signals
4. **Milestone Tracking**: Focus on new user workflow milestone success metrics
5. **PLG-Centric**: Product-led growth patterns should guide skill design

## Skill Development Guidelines
- Skills should be composable and chainable
- All skills must have clear input/output contracts (manifest.json)
- Include test cases for each skill, especially edge cases
- Consider MCP connections as primary data sources
- Document all API integrations (Mixpanel, enrichment services, etc.)

## Code Style
- Use TypeScript for type safety
- Implement error handling and retry logic for external API calls
- Log all API interactions for observability
- Use consistent naming: snake_case for skill names, PascalCase for classes

## Evaluation Standards
- Skills must include success criteria in manifest
- Create benchmark datasets for skill evaluation
- Track performance across lifecycle stages
- Document failure modes and mitigation strategies
