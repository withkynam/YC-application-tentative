# Zihao Lam and Ky-Nam Nguyen Catchup

**Date:** July 22, 2026  
**Meeting:** catchup Lam Nam  
**Participants:** Zihao Lam, Ky-Nam Nguyen  
**Source:** Gemini meeting notes

## Summary

The session compared vertical versus horizontal AI strategies while refining platform infrastructure and finalizing team expansion equity.

## Key Topics

### Vertical Versus Horizontal AI

The discussion contrasted niche legal workflows with horizontal AI office frameworks for small businesses. Flowser prioritized broad utility over deep vertical customization to serve immediate market demand.

### Infrastructure Development and Pricing

The team refined seat-based pricing models for commercial growth while implementing soft isolation mechanisms for free-tier users. Security restrictions on system tools will prevent unauthorized file access.

### Team Expansion Equity Offer

The partners decided to offer 10% equity to a new candidate with a specific vesting schedule to preserve existing ownership stakes.

## Decisions

- **Prioritize horizontal AI assistant strategy:** The team will prioritize selling a horizontal AI assistant solution to SMBs through easy-to-use building blocks, deferring deep niche workflows to a later stage.
- **Implement per-seat pricing model:** Flowser pricing will transition to a per-seat model. Free trial users receive a single shared agent slot, while paying customers gain access to dedicated resources.
- **Prepare equity reallocation for Chris Muen:** Zihao agreed to relinquish his equity to facilitate offering a 10% equity stake to Chris Muen, with the formal proposal to be reviewed before finalization.

## Next Steps

- **Zihao:** Review the proposal draft regarding Chris Muen and provide feedback.
- **Ky-Nam Nguyen:** Research OpenCloud sandbox limitations and share findings regarding observed quirks.
- **Zihao:** Repost the Law Defi announcement and add personal commentary.

## Detailed Notes

### Law Defi Overview

Zihao announced a new role at Law Defi on LinkedIn. Law Defi is a seed-stage startup backed by a $500k USD seed round from Analog VC, which was described as comparable to YC, and a prior pre-seed round from Iterative VC, a Singaporean accelerator.

Zihao joined after being approached by a recruiter. He completed a two-to-three-month work trial and part-time period before transitioning to a full-time, work-from-office arrangement as the company seeks to execute rapidly during its initial three months.

Ky-Nam Nguyen and Zihao agreed that the company's logo looks AI-generated in Stable Diffusion and contains too many details, a sentiment also shared by Zihao's girlfriend.

Law Defi operates two core AI workflow platforms for the legal and insurance sectors:

- The legal platform functions as a ChatGPT wrapper using a custom knowledge base with file indexing, RAG, and basic web search for legal research.
- The insurance platform automates the tedious manual workflow of claim examiners reading receipts and verifying documents using specialized, tuned AI agents.

### Flowser Strategy: Niche Versus Horizontal Workflows

Zihao suggested that Flowser should adopt a similar strategy of building niche workflows for single clients across different verticals.

Ky-Nam contrasted Law Defi's vertical niche approach and dedicated GTM platforms with a horizontal "AI office" framework aimed at white-collar workers. He noted that small business owners are driven by fear of missing out on AI digitization and seek immediate, accessible solutions in the office.

Ky-Nam reported that prospects regularly ask whether their employees will receive personal AI assistants that:

- Know company policies and SOPs.
- Help with employee onboarding.
- Help with presentation preparation.
- Are accessible through existing communication tools like Slack, Discord, Microsoft Teams, or Zalo.

Because Flowser runs on an OpenCloud instance capable of supporting 20 to 30 simultaneous agents and up to 20 users on a 2 CPU / 4 GB RAM hardware configuration, Ky-Nam said it already satisfies roughly 80% of this demand, making it a compelling horizontal offering for small teams.

### Flowser Onboarding and Customer Validation

Ky-Nam emphasized that the primary touchpoint should focus on seamless onboarding and horizontal utility rather than deep workflows.

To prove immediate value, Ky-Nam demonstrated Flowser's deployment by logging in on a manager's phone to spin up an OpenCloud instance connected to Discord, Slack, or Zalo in under 10 seconds. Zalo was noted as the dominant messaging application in Vietnam, heavily used for client interactions and HR, and not natively addressed by OpenAI.

Flowser currently serves two paying customers who drive product development. When users request unsupported capabilities, Ky-Nam builds the required plugin or ability directly into the platform.

The forward-looking strategy is to:

1. Establish an initial horizontal onboarding layer for small business digitization needs.
2. Expand to larger enterprises later.
3. Eventually launch a self-sustaining workflow marketplace where users submit requirements and the Flowser team builds custom niche templates and mini-app skills.

### Small Business Use Cases and Technical Primitives

Zihao asked what specific SMB employees use Flowser for. Ky-Nam identified three primary non-GTM use cases from customer feedback:

- Transform uploaded Excel spreadsheets into dynamic project management dashboards that update automatically with new data.
- Deploy a 24/7 Zalo bot to group chats where human staff can step in to assist clients with company policies and products.
- Set up internal personal assistants to handle employee onboarding and policy queries.

Ky-Nam explained that once the underlying building blocks are robust, including plugins, seat-based organizational structures, and omni-channel integrations, they can be grouped into tailored templates.

Ky-Nam also identified an untapped opportunity to link agents directly to real social media accounts to reply to mentions, similar to the xAI Grok bot on X.

### Pricing Model and Seat-Based Accounts

Ky-Nam detailed the ongoing development of Flowser's commercial infrastructure to replace the original single-container public launch plan, which cost $30 per month and allowed unlimited members to access one container for free.

The new pricing model introduces a base price for the container plus a per-seat fee when additional organizational members are added to create agents.

Ky-Nam capped capacity at 20 seats per organization because testing confirmed that a 2 CPU / 4 GB RAM VPS configuration can only sustain 20 agents running simultaneously. Upgrading VPS configurations to increase seats remains a future option.

### Free Trial Infrastructure and Soft Isolation

Ky-Nam is implementing a single-agent slot concept for free trials, where up to 40 free trial users share a single container instance to manage hosting costs.

To prevent individual trial accounts from accessing the broader container environment, Ky-Nam is developing front-end and server-side soft isolation rather than a full sandbox.

Zihao raised architectural concerns regarding filesystem security and data proxy sharing, noting that OpenCore has its own built-in sandbox but lacks full isolation if an agent uses system tools.

Ky-Nam clarified that while the entire container shares a single provisioned data proxy, users can configure custom proxies for individual browser contexts, which already run in isolated contexts to separate login credentials.

To mitigate security risks without a complete sandbox, Ky-Nam is setting up an allow-list that denies agents access to low-level execution tools like bash or exec. In place of standard utilities, Ky-Nam is writing custom plugins, including a specialized browser-based tool and an isolated version of grep, to restrict file reading and memory scanning to the agent's personal workspace.

If soft isolation proves too complex, Ky-Nam noted that bash can be disabled entirely for the individual tier, since casual users seeking a personal assistant on WhatsApp or Telegram rarely require command-line access.

Ky-Nam also confirmed that an automated reaper script is currently running to terminate idle instances and manage infrastructure overhead.

### Team Expansion and YC Application

Ky-Nam raised the topic of inviting Chris Muen to join the team, noting that Chris has expressed strong interest and maintains a high-profile "building in public" presence that could strengthen the upcoming Y Combinator application.

Due to the imminent YC deadline and the extensive preparation required, Ky-Nam expressed hesitation about entering complex equity negotiations that might distract from the application. He suggested formal equity arrangements could be finalized after submission.

Zihao openly disclosed a lack of future time to dedicate to Flowser and proposed forfeiting his own equity share to accommodate Chris Muen's onboarding, thereby protecting Ky-Nam's equity stake from dilution.

Ky-Nam agreed that part-time commitments are acceptable initially and proposed an initial 10% equity offer for Chris Muen.

To account for Chris's status as a new part-time participant, Ky-Nam noted that the equity arrangement will include a distinct vesting schedule and cliff that triggers fully only when the team transitions to full-time work, ensuring prior contributions by Ky-Nam and Zihao are fairly preserved.

Ky-Nam committed to sending the formal written proposal to Zihao for thorough review while Zihao is traveling on the train.
