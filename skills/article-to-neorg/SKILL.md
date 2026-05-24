---
name: article-to-neorg
description: Transcribe web articles into Neorg note format
---

## What I do
When you give me a URL or paste article content, I'll convert it into a Neorg-formatted note with:

- Title as first heading
- Published date + link on second line
- Body text with proper Neorg formatting
- Clean structure with headings, lists, quotes, code blocks, and links

## Neorg Format
```
* Title
Published YYYY-MM-DD {http://example.com}[link text]

** Heading
Subheadings have a number of asterisks in front matching the depth

- List item
-- Nested list item

*bold* (shows as red)
/italics/

`inline code`

> quote
> - author

@code language
code block
@end

$ term
Definition
```

## When to use me
- Paste a URL and ask me to transcribe it
- Provide article content and ask me to format it as Neorg
- Convert existing notes from other formats to Neorg

## Notes
- Extract the title from the article or use provided title
- Format dates as YYYY-MM-DD
- Convert links to Neorg format: {http://url}[text]
- Copy the article verbatim, do not summarize anything
- Preserve code blocks, quotes, and formatting
- Put the output into the user's clipboard using the program `pbcopy`
