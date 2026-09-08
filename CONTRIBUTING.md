# Contributing

Contributions to this actively maintained list of progress reward modeling papers are welcome. Open an issue to suggest a paper, or submit a pull request that updates [README.md](README.md).

## What to Contribute

- Relevant papers on constructing or evaluating progress signals and rewards for robotic learning.
- Confirmed conference, journal, or workshop acceptances.
- Missing code or project links, clearer preview images, and corrected bibliographic information.
- Fixes for broken links, duplicated entries, or formatting issues.

## How to Add a Paper

Add one row to the `## Paper List` table in [README.md](README.md), in descending date order. Use the first arXiv submission month, not the latest revision or the conference year. If no arXiv submission date can be verified, use the proceedings or conference month and mark it with `*`.

```markdown
| YYYY/MM | [**Paper Title**](https://arxiv.org/abs/xxxx.xxxxx) | arXiv | [Code](https://github.com/author/repo) | Instruction-tuned |
```

The columns are `Date`, `Paper`, `Venue / Status`, `Resources`, and `Primary Category`.

For an accepted paper, replace `arXiv` with a linked venue and year, such as `[ICLR 2026](https://official-publication-page)`. Link to the official proceedings, conference listing, or an explicit acceptance announcement from the authors. Label workshops explicitly, including the workshop name when available; a workshop acceptance is not a main-conference acceptance. Use the conference's event year even if its proceedings appeared the following year. Use `arXiv` when an accepted venue has not been verified; submission or review alone does not establish acceptance.

Choose one primary label from the [category legend](README.md#categories): `Instruction-tuned`, `Frozen FM`, `Temporal / relative`, or `Programmatic`. Mention the reason for the choice in the issue or pull request if it is not obvious. A paper can relate to several families, but should appear only once in the table.

Keep existing category assignments when reorganizing the list or updating publication metadata. For new papers, use the paper's reward-construction method to choose a primary category.

## Optional Resources

Use `-` if there is no code or project link. Existing previews and BibTeX entries can be included as collapsible details to keep the list easy to scan.

Append a preview to the `Paper` cell:

```html
<details><summary>Preview</summary><img width="220" alt="Paper Title overview" src="img/your_image.png"></details>
```

Put the image in `img/` and use a relative path. Keep it readable and trim excessive blank space.

Append a citation to the `Resources` cell:

```html
<details><summary>BibTeX</summary><pre><code class="language-bibtex">@misc{key,<br>  title={Paper Title},<br>  author={Author One and Author Two},<br>  year={2026},<br>  eprint={xxxx.xxxxx},<br>  archivePrefix={arXiv},<br>  url={https://arxiv.org/abs/xxxx.xxxxx}<br>}</code></pre></details>
```

Use a citation supplied by the paper's authors, arXiv, or the publisher. An arXiv citation and a later conference status can coexist; do not change a citation's year solely to match the venue column.

## Before Submitting

- Confirm that the paper fits the scope and is not already listed.
- Check its title, first-submission month, and primary category.
- Provide evidence for the venue and year, distinguishing main conferences, journals, and workshops.
- Keep the list sorted newest first, including the actual submission order within each month when available.
- Check that paper, venue, code, and project links point to the intended work.
- Keep each table entry on one Markdown line, using `<br>` inside BibTeX blocks.
- Check that optional previews and citation blocks expand correctly.

New work can be proposed for the paper list independently of a survey manuscript update. Small fixes are welcome too.
