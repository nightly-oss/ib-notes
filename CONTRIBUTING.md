> Already know the basics and want to get to contributing? **[[#Contributing Guidelines|Skip to this section]]**

---

The wiki is open to contributions by other students of the IB. If you’re familiar with Git, you’re encouraged to clone this repository, make any changes needed locally, and submit a **pull request** with your changes.

If you’re not familiar with Git or don’t want to submit changes, you can **open an issue instead**. Read the guidelines below for creating a good issue.

> [!CAUTION]
> **Make sure you’re in the right repo!** This `CONTRIBUTING.md` document is in the root of the notes repository. Contribute here if you want to contribute to the notes, like making changes, refining notes, adding new pages or subjects, or submitting feedback. If you want to contribute to the actual code making this possible, go [here](https://github.com/nightly-oss/ib-wiki)

## Submitting an Issue
Issues are used for any suggestions you have about the repository.

| What an Issue here is for                                  | What an issue here is NOT for                                                                                                     |
| ---------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| ✅ Pointing out a mistake in the notes                      | ❌ Asking a question about the notes (do this in Discussions)                                                                      |
| ✅ Proposing a new layout/folder organization for the notes | ❌ Poitning out an issue in the code, like a bug or accessibility issue (You do this in issues, yes, but you’re in the wrong repo) |
| ✅ Fixing grammar, consistency, and accuracy mistakes       |                                                                                                                                   |
| ✅ Suggesting a new note or subject                         |                                                                                                                                   |

# Contributing Guidelines
We do not accept direct notes. **Please do not try to send anyone your Markdown file and expect us to upload it.** Instead, follow the standard GitHub workflow: Fork the repository, clone it locally, make the changes needed, then submit a Pull Request.

## What defines a good note
Notes must always be written in English, unless for subjects of a different language like Modern Greek. Also, **only Markdown notes are accepted.** PDFs, image files (unless to be embedded in the notes), plain text files, Overleaf files, or any format other than Markdown will be automatically rejected.

### A. Good Markdown formatting
IB Wiki notes are written in Markdown, as it’s easy and quick to write and compatible with basically anything out there. **Make sure you know how to properly write in Markdown.** If you want to learn, **[this is a very helpful resource](https://www.markdownguide.org/)**.

- **Headings are mainly hierarchical:** Whatever is in a **Heading 3** is part of the content of whatever is under a **Headng 2**.
- **Callouts are encouraged:** The ones supported are `[!FAIL]`, `[!CAUTION]`, `[!WARNING]`, `[!NOTE]`, `[!IMPORTANT]`, `[!TIP]`, and more. Check [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#alerts) for more details about callouts.
- **LaTeX** is used for math. Make sure to learn it if you’re writing math. For example `$\frac{4 + x}{3}$` will show $\frac{4 + x}{3}$

###### For math graphs, we use Desmos embeds.
Copy your graph from Desmos (Share button near “Sign Up” → Share a Snapshot → Embed Snapshot and copy the code), then just paste it in your note area, like this:
```html
<iframe 
    src="https://www.desmos.com/calculator/e939103c80?embed" 
    width="100%" 
    height="400px" 
    style="border: 1px solid #333; border-radius: 8px;" 
    frameborder="0">
</iframe>
```

If you need support for more elements to be expanded, please notify me be opening an issue.

### B. It follows the Nightly_ philosphy
> *If something can be simplified further, then simplify it further. Treat the reader as someone completely new to the concept you’re describing.*

This is the philosophy I follow in my own documentation and note-taking. It is recommended that your notes follow this philosophy and have a similar “walkthrough” or tutorial style. Your writing should encourage learning and engage curiosity. As an extra, adding sources and links to your notes is an extra that is very highly-appreciated.

### C. It respects the current structure of the Wiki
The structure of this Wiki and vault can always change, but your notes should be placed in the appropriate folders, having the appropriate names, and repsecting the structure of this vault as it is right now. If it changes later, your note will be moved without you needing to intervene.

## Respect the Code of Conduct
Please read it [[CONDUCT|here]].

## One *important* thing to be mindful of when working on the notes
If you have this repository cloned locally, make sure to **touch only what you need**. If you modify anything else like the Obsidian settings or theme, or a document you didn’t mean to edit, make sure to exclude it from your commit!