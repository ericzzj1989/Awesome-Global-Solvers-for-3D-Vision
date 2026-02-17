# How to Contribute

Suggestions, paper updates, and any contributions to this list are most welcome! 

## Ways to Contribute

You can contribute by:

- 📄 Adding new papers
- 🔧 Updating paper information (code/project links)
- 🐛 Fixing errors or broken links
- 💡 Suggesting improvements to organization

## How to Submit

Please feel free to *open issues* or *create pull requests*.

### Format for Adding Papers

When adding a paper, modify the `README.md` and add a new row to the **corresponding table**. Each table follows this format:

```markdown
| Year | Venue | Paper Title | [[Paper](link)] [[Code](link)] [[Project](link)] |
```

**Example**:

```markdown
| 2024 | ECCV | GlobalPointer: Large-Scale Plane Adjustment with Bi-Convex Relaxation | [[Paper](https://arxiv.org/pdf/2407.13537)] [[Code](https://github.com/WU-CVGL/GlobalPointer)] [[Project](https://bangyan101.github.io/GlobalPointer/)] |
```

### Guidelines

- **Year**: Publication year (e.g., `2024`)
- **Venue**: Conference/journal abbreviation (e.g., `CVPR`, `TPAMI`, `arXiv`)
- **Paper Title**: Use the exact title from the paper
- **Links**: 
  - `[[Paper](link)]` — should point to PDF if available (arXiv, OpenAccess, etc.)
  - `[[Code](link)]` — include if available
  - `[[Project](link)]` — include if available
  - If code/project page doesn't exist, omit those tags
- **Placement**: Add the paper to the appropriate section and subsection based on method type (BnB / Shor's / Moment-SOS / Other / GNC) and application task
- **Row ordering**: Insert the paper in chronological order within the table

### Notes

- Not all papers need to have code or project page links
- Please verify that links are working before submitting
- For papers in multiple categories, add to the most relevant section

Thank you for contributing to the community! 🙏
