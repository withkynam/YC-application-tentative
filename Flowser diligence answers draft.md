# Flowser Diligence Answers Draft

Draft style: short, direct, YC-ish. Replace bracketed items before sending.

## 1. Team & Capabilities

### What is the current team structure? What are each person's role and scope?

Ky-Nam Nguyen is CEO/product, full-time. He owns product, frontend, customer discovery, GTM, content, community, and day-to-day shipping. Before Flowser, he ran a web agency, shipped multiple side projects, built a 40M+ impression personal brand with $0 spend, and co-built 6+ products with Zi Hao, including a study platform they sold for $50K and EngageKit.

Zi Hao Lam is CTO/cofounder. He owns infra, backend, agents, browser/container reliability, and technical architecture. He is ex-AWS solutions architect and ex-head of engineering at a Nasdaq-listed company. He is currently part-time because of his job, but remains the core technical cofounder.

We met at HKU in Hong Kong over 4 years ago, started as hackathon partners, became best friends, and have built together since. We work async across Vietnam/Malaysia and talk daily.

Links: Ky-Nam GitHub: https://github.com/withkynam, Ky-Nam LinkedIn: https://www.linkedin.com/in/withkynam, Zi Hao LinkedIn: https://my.linkedin.com/in/zi-hao-lam, Zi Hao GitHub: https://github.com/zihaolam.

We are testing Chris Nguyen as a possible GTM cofounder or Head of Growth. The role is not finalized and cannot be included in the YC application as Head of Growth.

### Besides GTM, what capability gaps are still uncovered?

The biggest gap is senior GTM: positioning, sales motion, pricing, enterprise discovery, and repeatable customer acquisition.

Secondary gaps are design polish, customer support ops, finance, and legal. We can cover early design/support ourselves. Finance/legal should be handled with lightweight outside help until scale.

### What is each founder's personal runway?

Ky-Nam can keep going full-time for the next 12 months by living lean in Vietnam and using savings/project income only if needed.

Zi Hao currently has salary from his job, so his personal runway is not the blocker. The blocker is time commitment. The plan is for him to return full-time after YC/seed funding or meaningful revenue.

## 2. Business Model & Economics

### Where does current revenue come from?

Current revenue is early customer revenue, mostly subscription/service-like usage from businesses that want AI agents for GTM and internal workflows.

The intended model is subscription plus usage credits. Custom work is acceptable early because it teaches us the templates, but we do not want a services company.

### What is the pricing and cost structure?

The old live pricing was the Flowser Computer Agent plan: $9.99/week, $34.99/month, or $299.99/year. That is being replaced.

Planned pricing has 3 paid products: Single Agent, Member Seat, and Full Container. Single Agent is $14.99/month or $9.99/month billed yearly. Member Seat is $29.99/seat/month or $24.99/seat/month billed yearly. Full Container is $49.99/month or $39.99/month billed yearly.

Free users get one single-agent slot on a shared free container. Paid single-agent users get one slot on a shared paid container. Full Container customers get a dedicated container and can add member seats. A standard 2 CPU / 4 GB box is the near-term ceiling: about 20 seats / 40 users for a dedicated org, with larger orgs handled manually.

Weekly AI allowance also differs by tier: Free gets $0.15/day only, Single Agent gets $0.15/day + $0.50/week, and Container/Member Seat gets $0.15/day + $2/week per seat pooled at org level. We still need live gross-margin measurement by segment. Main COGS are Hetzner VM, LLM tokens, proxy/browser infra, Composio, storage, and payment fees.

### What is the current traction?

Current hard facts: Flowser has two paying customers driving product development, plus existing distribution from prior products and community: 1,000+ EngageKit users, 1,000+ AI event leads, 500 GTM waitlist contacts for Flowser, and 800+ indie builder contacts.

## 3. Customers & Market

### What is the persona of the current paying customers?

Small business owners and startup operators who want AI agents inside real daily channels, not another chat tab.

They ask for agents that know SOPs, help staff onboard, answer customer questions, prepare work artifacts, and run GTM/admin workflows through Zalo, Slack, Discord, and similar tools.

### Who is the ICP?

Near-term ICP: SMBs and agencies in Vietnam/Southeast Asia with 5-50 white-collar staff, messy ops, and high willingness to adopt AI.

Decision maker: founder, owner, agency principal, or ops/growth lead.

They need an "AI office": agents with memory, tools, browser/account access, files, dashboards, and messaging-channel presence. The main gap today is onboarding simplicity and packaging, not core capability.

### What target market do you want to pursue?

Start with Vietnamese and SEA SMBs because we have local distribution, fast customer access, and a strong Zalo wedge that global AI products ignore.

Then expand to English-speaking startup/agencies because the same need exists globally: every small team wants automation but cannot hire an internal AI engineer.

## 4. Product & Positioning

### What are possible pivot directions if Flowser does not reach PMF?

1. Verticalize into one workflow, such as AI customer support/onboarding for Zalo-heavy businesses.
2. Focus on GTM agents for founders, using EngageKit as the first template.
3. Become the agent-hosting/control plane for businesses that want persistent AI workers.
4. Build the marketplace of workflow templates and skill apps after enough repeated customer requests.

### What will you do to position Flowser as more than an OpenClaw wrapper?

OpenClaw is the engine. Flowser is the product layer businesses pay for: hosted agent computers, org/seat management, billing, credits, integrations, memory, skill templates, artifact publishing, safety, onboarding, and support.

The value is not "we run OpenClaw." The value is "your company can hire AI workers in 10 seconds and deploy them into real business channels."

## 5. 12-Month Direction

### What is the single objective over the next 12 months?

Prove SMBs will pay repeatedly for AI agents that operate inside their daily work channels.

Target: get to repeatable paid onboarding, strong retention, and enough usage to know which templates become the platform wedge.

### What is the product roadmap for the next two quarters?

Q1: finish self-serve onboarding, seat-based org billing, free shared-slot tier, paid dedicated instances, Zalo/Slack/Discord onboarding, artifact publishing, and 3-5 high-retention templates.

Q2: turn repeated customer work into reusable skill apps/templates, improve workspace memory/files, ship admin controls, and begin marketplace-style workflow requests.

Ky-Nam owns product, UI, customer discovery, and GTM. Zi Hao owns infra, agents, reliability, security, and scaling. A GTM cofounder, if finalized, owns positioning, sales, pricing tests, customer pipeline, and partnerships.

### Product-led self-serve or sales-led?

Product-led with founder-led sales at the start.

SMBs need handholding to see the "AI office" use case. Once we learn the winning templates, onboarding should become self-serve and repeatable.

### Do you intend to raise funding?

Yes, but only if it is YC right now.

If YC accepts us, YC is the round and we move to SF. If YC does not accept us, we do not plan to raise immediately. We will keep selling and only raise again after reaching roughly $1M ARR or having much stronger proof.

The investor story is: persistent AI workers for SMBs, starting in SEA where we have distribution and channel integrations, expanding into a global workflow marketplace.

### What exit scenario does Nam have in mind?

Build for IPO-scale, not acquihire.

The big outcome is a new operating layer for small companies: every employee and department gets AI workers connected to tools, accounts, data, and communication channels.

### What signs would indicate pivot or stop?

Pivot if customers like demos but do not activate weekly, if paid retention is weak, or if all revenue becomes custom services with no repeatable template.

Deadline: by 6 months, we need a narrow use case with repeated paid usage. By 12 months, we need clear retention and a path to meaningful MRR.

## 6. Legal Entity & Risk

### Has the company been incorporated yet?

Yes. We already have a Hong Kong LLC.

If accepted to YC, we will convert/restructure into a YC-standard Delaware C-Corp.

### What is the current cap table?

Current YC application draft says 50/50 between Ky-Nam and Zi Hao.

The internal working proposal is a target fully vested split of 60/30/10: Ky-Nam 60%, Zi Hao 30%, new GTM cofounder 10%. This is not immediate fully owned equity. It is a target after vesting, cliffs, and full-time commitment.

Proposed structure:

1. Ky-Nam: 60% grant. He has already been full-time for about 1 year, so vesting can be backdated 12 months. On a 4-year schedule, that means roughly 15% already vested, 45% unvested, and the rest vesting monthly over the next 3 years.
2. Zi Hao: 30% target. Suggested split is 10% treated as earned/past-contribution equity, plus 20% future founder equity that only starts vesting when he joins full-time. Trigger: YC/seed funding or $15k MRR. If the trigger happens and he does not join full-time within 60-90 days, the unvested 20% should be cancelled or renegotiated.
3. New GTM cofounder: up to 10% target if fit is proven. Suggested split is 2% part-time trial grant with 6-month cliff, then 8% full-time cofounder grant only after joining full-time. The full-time grant vests over 4 years with a 1-year cliff.

Everything is tentative and negotiable, especially after YC. A lawyer should turn this into proper founder stock restriction, vesting, repurchase, and shareholder documents.

No ESOP is finalized yet. We should create one when incorporating/raising.

### How are you handling customer data and credentials?

Flowser isolates user/org workspaces at the product and infrastructure layer, uses per-instance tokens, and is building stronger slot-level auth for shared tiers.

For credentials, the principle is least access and user-controlled keys where possible. BYOK means user-owned model keys can bypass Flowser credit billing, but the company still needs careful secret handling for integrations it brokers. We should not oversell this: shared-tier hardening is still an active workstream.

## 7. Co-Founder Role

### Why cofounder instead of Head of Growth?

We are open to either a cofounder path or a Head of Growth path. The title and economics should follow the actual commitment, risk, and output.

The reason a cofounder path is on the table is that the GTM problem is still founder-level: market, positioning, pricing, wedge, sales motion, customer truth, and personally selling before any playbook exists. If the role is narrower or part-time for longer, Head of Growth may be more appropriate.

Either way, this is tentative and negotiable after the YC application. We cannot include Chris in the YC application as Head of Growth.

### Why Chris?

Chris has founder energy, public distribution, taste for building in public, and a real interest in Flowser before the role is polished.

We have not closed someone else because this role needs trust, speed, and ambiguity tolerance. But we are still open to a Head of Growth structure if that is the cleaner fit.

### What is the specific scope?

Likely scope: positioning, pricing experiments, ICP, sales pipeline, founder-led sales, partnerships, launch/content, customer relationships, and investor narrative input.

Not owned alone: final product architecture, security, legal commitments, cap table, or spending beyond agreed budget.

### Where is the boundary with Nam?

Ky-Nam has final call on product/company direction while the role is still tentative. The GTM lead/cofounder can own agreed GTM experiments inside budget and strategy.

If we disagree, we write the bet, define the metric, run the smallest test, and let customer behavior decide.

## 8. Working Expectations & Fit

### What traits does a good cofounder have?

High agency, hustle, emotional honesty, customer obsession, speed, and low ego.

A good cofounder makes the company more truthful and faster. For this GTM role specifically, the bar is high ownership, sales and deal-making ability, personal branding, growth hacking, innovative ideas, and strong design/product taste.

Deal-breakers: hiding bad news, waiting for permission, politics, low urgency, weak follow-through, and protecting ego over learning.

### Expected hours and working style?

Part-time during trial is acceptable if output is real and weekly. Full cofounder equity requires full-time commitment after the funding/revenue trigger.

Working style: async by default, fast written updates, weekly strategy review, and heavy customer-facing execution. The role should create momentum every week: customer calls, demos, partnerships, posts, launches, pricing tests, and new distribution experiments.

### Which channels and decision mechanism?

Current founder communication is daily async chat/calls, with deeper decisions written down in docs.

Mechanism: write the decision, options, owner, metric, and deadline. Avoid vague alignment.

### How does Nam handle disagreement?

Nam and Zi Hao disagree directly, especially on vertical vs horizontal strategy and infrastructure risk. Example: Zi Hao pushed for more vertical workflow focus; Nam argued SMBs are asking for a horizontal AI office. They discussed the customer evidence and chose horizontal first while keeping vertical templates as a later path.

### What would make Nam disappointed in Chris during the first 6 months?

Lots of brand talk but no customer pipeline.

The first 6 months should produce clear market learning and visible business momentum: calls, demos, pricing tests, closed customers, partnerships, distribution wins, lost-deal notes, and sharper positioning every week.

## 9. Deal Terms

### Equity terms?

Working proposal: up to 10% fully vested target if this becomes a true GTM cofounder role.

Suggested structure:

1. Trial grant: 2% maximum while part-time.
2. Trial cliff: 6 months. If they leave or both sides stop before 6 months, they keep 0%.
3. After the 6-month cliff: the trial equity starts vesting monthly over 12 months total. Maximum part-time earned amount before full-time commitment is 2%.
4. Full cofounder grant: additional 8%, granted only if they join full-time after YC/seed funding or $15k MRR.
5. Full-time vesting: 4 years with a 1-year cliff, starting when they become full-time.

Everything is tentative and negotiable, especially after YC. If the role is Head of Growth instead of cofounder, the title/equity/vesting should be renegotiated.

### If the next funding round happens, how would I be diluted?

Everyone dilutes pro rata, including founders and unvested founder grants. No special anti-dilution or pro-rata protection unless all founders agree and counsel says it is standard.

Example: if YC takes 7%, a 10% fully diluted target becomes 9.3% post-YC before any ESOP/top-up changes.

### If after 6 months both sides feel it is not a fit?

If before the 6-month cliff, the GTM cofounder keeps 0%.

If after the cliff, they keep only the vested portion of the trial grant. Any unvested trial equity can be repurchased/cancelled by the company. The 8% full-time grant is not issued unless they actually join full-time.

Same principle for all founders: vested equity is earned; unvested equity can be repurchased or cancelled if the person leaves, resigns, does not join full-time after the agreed trigger, or stops contributing. Customer docs, data, code, and company assets stay with Flowser.

### Non-compete or exclusivity restrictions?

No broad non-compete by default. During trial, disclose conflicts and do not work on a directly competing AI agent/workflow product.

If someone becomes a cofounder, they should not start, join, or materially help a directly competing company for at least 1 year after leaving. "Directly competing" means a product in the same core category as Flowser: hosted claw-like / OpenClaw-like nondeterministic agent systems with persistent computers, tools, memory, browser/account access, and business workflow automation.

This should not block normal employment, advisory work, or unrelated AI products. Full cofounder grant requires exclusivity/full-time commitment. Final legal terms should be founder-friendly and enforceable in the chosen jurisdiction.
