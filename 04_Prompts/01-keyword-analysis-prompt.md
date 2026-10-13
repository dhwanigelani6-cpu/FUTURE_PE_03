# Prompt 1 – Keyword Analysis & Intent Mapping

## Purpose
Generate and classify local SEO keywords for any small business.

## Prompt
```
Act as an experienced local SEO strategist.

Business: {business_name}
Type: {business_type}
Location: {area}, {city}
Key offerings: {offerings}
Landmarks nearby: {landmarks}

Task:
1. Suggest 2 primary keywords, 4 secondary keywords and 6 long-tail keywords for local search.
2. Classify each keyword by search intent (Informational, Commercial, Local, Navigational).
3. Assign each keyword to ONE page type (pillar or supporting blog).
4. Rate priority as High, Medium or Low.

Rules:
- Do not invent search volume numbers.
- Keep keywords natural, the way real people search on mobile.

Output format: a markdown table with columns Keyword | Intent | Target page | Priority.
```

## Prompt Logic
- Role prompting sets the expert context.
- Variables make the prompt reusable for salon, clinic, agency, etc.
- "Do not invent numbers" prevents fake data.
- Table output makes it easy to paste into documentation.
