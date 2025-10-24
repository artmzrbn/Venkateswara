# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is the **Venkateswara** project - a collection of AI agent system prompts for product strategy and management. The repository contains specialized AI agent configurations designed to facilitate product decision-making processes.

## Repository Structure

- `brain/` - Contains AI agent system prompts (written in Russian)
  - `nsm_creator.md` - Agent for determining North Star Metric (NSM) based on Julia Bilinkis's methodology
  - `product_hypotesy_creator.md` - Agent for formulating product hypotheses in a structured format
- `memory/` - Currently empty directory (purpose unclear)

## Key Concepts

### North Star Metric (NSM) Agent
The NSM agent follows a strict 4-step facilitation process:
1. Understanding product value and JTBD (Job to be Done)
2. Asking clarifying questions across 5 validation rules
3. Proposing 2-3 NSM variants
4. Final formulation with rationale

NSM must satisfy ALL criteria:
- Reflects customer value
- Leading indicator of business success
- Single and understandable
- Measures overall product usage
- Measures action and engagement (not passive metrics)

### Product Hypothesis Agent
This agent transforms ideas into testable hypotheses using the structure:

**We believe that** [CHANGE IN PRODUCT] **for** [CUSTOMER SEGMENT] **will lead to** [BEHAVIOR CHANGE], **because** [RATIONALE].

**We will know this is true when** [METRIC] **changes by** [VALUE].

**And this change will increase/decrease** [MONETARY METRIC] **by XX%**.

The agent follows a 4-step process:
1. Input analysis
2. Identifying missing components (5 required elements)
3. Hypothesis synthesis
4. Quality verification

## Language

All agent prompts and documentation are written in Russian. The agents are designed to conduct conversations in Russian with users to facilitate product strategy discussions.

## Git Workflow

- Main branch: `main`
- Standard GitHub workflow with pull requests
- Recent activity shows documentation improvements to README

## Notes for Claude Code

When working with this repository:
- The agents are meant to be conversational facilitators, not solution providers
- They extract information through structured questioning
- Both agents emphasize not fabricating information - they must gather all required components from the user
- The methodologies are based on specific product management frameworks and must be followed strictly
