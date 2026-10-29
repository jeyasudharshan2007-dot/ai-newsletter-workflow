AI Newsletter Automation Workflow

Project

CAPSTONE 51 — AI Newsletter Production Workflow

Objective

Design a repeatable workflow for collecting news, summarizing articles with AI, verifying information, and preparing a weekly newsletter.

Tools Used

1. Perplexity: Discover relevant news articles.
2. ChatGPT: Summarize articles and draft newsletter content.
3. Google Docs: Organize and review newsletter drafts.
4. Google Sheets: Track article sources and verification status.
5. Zapier Free: Explore automation between supported applications.
6. GitHub: Store project documentation and track changes.

Workflow

Step 1: Collect News

Search for AI and technology news from reputable publishers.

Output: Article titles, URLs, publishers, and publication dates.

Step 2: Track Sources

Record each article in a spreadsheet.

Suggested columns:

- Article title
- Publisher
- Publication date
- URL
- Summary
- Verification status

Step 3: Summarize with AI

Use ChatGPT to prepare a short summary based on the original article.

Output: A draft summary for human review.

Step 4: Verify Information

Open the original article and check its headline, date, names, figures, and claims.

Output: A corrected summary with a verification status.

Step 5: Draft the Newsletter

Combine the approved summaries into a consistent newsletter format.

Output: A complete newsletter draft.

Step 6: Human Review

Check grammar, readability, source links, attribution, and factual accuracy.

Output: A reviewed draft ready for publication.

Step 7: Prepare Publication

Format the newsletter in Canva or Google Docs.

Output: A final newsletter suitable for the selected publishing platform.

Proposed Automation

1. Use an RSS feed or another supported news source to discover new articles.
2. Send article details to Google Sheets using a supported automation integration.
3. Review collected items and remove duplicates.
4. Use AI to summarize selected articles.
5. Require human verification before approving any summary.
6. Prepare the newsletter draft.
7. Publish manually after final approval.

Automation Safety Rules

- Never publish unverified AI-generated content automatically.
- Check the availability and permissions of each integration.
- Respect website terms, copyright, and rate limits.
- Do not store API keys or passwords in GitHub.
- Record errors and review failed automation runs.

Testing Plan

- [ ] Test whether the selected source provides new articles.
- [ ] Check whether article details are recorded correctly.
- [ ] Test duplicate detection.
- [ ] Compare AI summaries with original articles.
- [ ] Test the workflow with one sample article.
- [ ] Confirm that human approval is required before publication.

Current Status

Workflow designed on paper. Live automation is not yet implemented or tested.

Expected Outcome

A repeatable process that reduces manual work while retaining human control over research quality, verification, and publication.