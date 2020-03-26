# Bug Bounty Guide

This guide was created for the `Intro to Hacking Workshop`. In this guide, you will find how to write a basic bug bounty report and information on our scoring system.

## Bug Bounty 101

A bug bounty report is based on your personal writing style. Everyone will develop a style overtime. We encourage people to explore and use their own style. For these workshops, we developed a system that will hopefully keep your bug bounty reports simple. Take note that this procedure might change from company to company, so make sure to read their bug bounty guidelines carefully.

### Writing a Bug Bounty Report

We are looking for a clear and concise description of the bug. Assume that your audience is a beginner in security. We will favor bug bounties that explain concepts and include visual content. We will also consider bugs that have already been reported as long as the report isn't a total copy. Do not include any spoilers like CTF keys, passwords, etc (If you need the answer part of the explanation, censor a substantial amount of the word(s) with `*`). Bug bounties should be written in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). The following bug bounty template should give you an idea of the information you should include:

```
# Descriptive Report Name

Brief overview of the bug. Include a mention about if this bug is unique. In addition, include a rough estimate of the score.

## Description

Offer an elaborate description of the bug. Explain and/or include links to concepts. Include tools used (if any).

## Procedure

Give a step by step of how to reproduce the bug. Visual content and script snippets are welcome. Include links to external documentation if necessary.

## Fix (Optional)

Describe the fix that you put in place. Point to a pull request or fork that fixes the issue.

## Scoring

Enumerate which points you believe you deserve. Refer to the scoring section.
```

### Submitting Bug Bounties

We will be using the issue board for each problem to submit Bug Bounties. These can be found under `/issues` for each repository. An admin will look over your submission and close the issue with a final score. 

## Score

Score systems are somewhat subjective for each person. To have a balanced system, we will attempt to make all bounties out of `100 points`. The following are criterias that will be considered. (The scoring is subject to change).

- Originality (20 points) - How original is this solution? We will base ourselves off of the issue board. The more a bug bounty is common, the less points will be attributed to this section. If your submission is considered very impressive, bonus points will be attributed.

- Description (50 points) - How effective were you at explaining the issue? Would someone with no knowledge about the subject gain value from this report? The more descriptive and understandable, the better. We will favor solutions that are beginner friendly.

- Procedure (20 points) - How effective were you at explaining the steps? Did you explain your thought process well? Could anyone reproduce the issue using only your guide?

- Fix (10 points) - Did the proposed solution fix the issue? 

These scores are subjective and will most likely change. We understand that some solutions might not fall well in these guidelines - feel free to explain why they wouldn't.
