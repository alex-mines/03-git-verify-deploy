# Decisions

A decision log: what you chose and why, in your own words.
P1 uses a file with this name and five questions; this one has one.
Answer it in two or three sentences after the live page is verified, then commit and push it.

## How you know it works

What check did you run on the live page, and what would have made that check fail?
A check that could not have failed is not a check.

We first had the agent check that the page was successfully built by having it poll until it went live; this check could have failed if the polling did not succeed. Then I performed a manual check by navigating to the page and visually inspecting it before taking a screenshot.
