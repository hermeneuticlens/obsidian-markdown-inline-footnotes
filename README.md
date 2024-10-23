**Markdown Inline Footnotes Plugin for Obsidian**

To make it easy to use inline footnotes instead of standard Markdown footnotes.

Why Use Inline Footnotes
- Traditioanl Markdown footnotes consist of two separate parts, marker and content, which are connected by an ID such as `^[13]` or `^[32s3dd39]`.
- Inline footnotes, which may sound like an oxymoron, actaully refers to inline notes in Markdown during the drafting/editing process but are intended to be footnotes when the document is finally presented. In this way, inline footnotes are the functional equivalent of `\footnote{}` in LaTeX.


Benefit of Using Inline Footnotes
- No need to manage footnote IDs or worry about conflicts, either within the same document or across documents.
- No need to jump between main text area and footnote area back and forth.


This plugin aspires to promote the usage of inline footnote by addressing the signular challenge: long inline footnotes interrupting the flow of the main text.
- Step 1: Implement support for folidng and unfolding of inline footnotes in Obsidain's Live Preview mode. (Similar to Overleaf's Visual Editor or Lyx)
- Step 2: Enable on-hover popup preview of folded inline footnotes.
- Step 3 (stretch goal): Design a panel listing all the footnotes in the document, with the option of following the cursor's position. (Similar to the Footnote Panel in Microsoft Word under Draft or Web view mode.)


Notes
- This plugin will use [Pandoc's implementation](https://pandoc.org/MANUAL.html#extension-inline_notes)'s implementation of inline footnotes, since Pandoc is also the dominant option for converting Markdown sources to publishable and sharable formats. I am aware of the existence of other differing implementations.
