# Customer Feedback Extraction Prompt

Use this prompt with Claude to extract product feedback from customer call transcripts. Copy the output and paste it into #product-feedback in Slack so Priya can ingest it.

---

## Prompt (copy everything below this line into Claude along with your transcript)

You are extracting product feedback from a customer conversation transcript for Bookmarked, an EdTech company that provides book intelligence and compliance tools for school districts.

Read the transcript below and extract every piece of product feedback — feature requests, complaints, friction points, missing functionality, workflow gaps, or things the customer wishes the product did differently.

For each piece of feedback, format it using this exact template:

---

📊 **Product Feedback Intake**

- **District/Customer:** [District name and contact name if mentioned]
- **Date Reported:** [Date of the conversation]
- **Product Area:** [Which area: Book Intelligence / Orders / Staff Management / Parent Portal / Library Management / SFTP/Rostering / Reporting / Onboarding / Other]
- **Core User Problem:** [The actual friction or pain point — NOT the solution they're asking for. What is hard, slow, broken, or missing from their perspective?]
- **Requested Feature/Gap:** [What they want or what's missing — the solution they described or implied]
- **Business Impact:** [Why it matters — churn risk, onboarding blocker, daily workflow friction, compliance gap, etc.]
- **Frequency:** [Is this the first time we've heard this, or has it come up from other districts? Say "First report" if you're not sure]
- **Evidence/Source:** [Name of the transcript file or meeting, with approximate timestamp if possible]

---

Rules:
1. Separate the PROBLEM from the SOLUTION. If the customer says "I need a button to export this," the problem is "I can't get this data out of the system" and the requested feature is "Export button."
2. One feedback item per issue. If a customer raises 3 different things, create 3 separate entries.
3. Skip general compliments, small talk, or satisfaction comments — only extract actionable product feedback.
4. If the customer describes something that's broken (not working as expected), note it as a bug in the Product Area field: e.g., "Library Management (BUG)"
5. Be specific. "The reporting is bad" is not useful. "The superintendent dashboard doesn't show parent-restricted books" is useful.

## Transcript:

[PASTE YOUR TRANSCRIPT HERE]
