# Why Does My GitHub Look Empty?

It doesn't - my repositories are just set to private.

I work on projects that involve proprietary code, internal tooling, and infrastructure that isn't suitable for public exposure. As a result, most of my work lives in private repos.

If you'd like to see examples of my work, I'm happy to walk through projects in a conversation.

From my most active private repo I have added 152,051 lines in the first 3 months of 2026.

```
❯ g log --author="[REDACTED]" --since="2026-01-01" --numstat --pretty="" | awk '{add+=$1} END {print "Added:", add}'
Added: 152051
```

## A Visual Demo of My Private Work

While I can't share the details of my private work, [here's a visualization](https://gource.io/) of the development history from one of my most active private repositories. It gives a sense of the scope and pace of the work without exposing any proprietary details.

[![Gource visualization of my private repo](gource.png)](https://youtu.be/99qZu40CS9I)

[Watch the full video on YouTube →](https://youtu.be/99qZu40CS9I)
