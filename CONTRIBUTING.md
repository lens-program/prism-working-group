# Working in this repository

PRISM is a working group, so this repository is a workbench rather than a showcase.
Half-finished things are welcome here.

## Meeting notes

`meetings/YYYY-MM-DD.md`. An agenda plus what was discussed and what anyone agreed to look at
next is enough. These are working notes, not minutes — brevity is fine, and a rough note is far
better than no note.

## Code

`code/` for prototypes, scratch analyses, and worked examples. Anything that matures into a
method implementation or a paper's reproduction materials should graduate to its own **public**
repository in the [lens-program](https://github.com/lens-program) organization and be linked
from the README.

## Data — read this before committing anything

**Private is not the same as permitted.** Members work with Tribal, clinical, and restricted
surveillance data under data-use agreements, and those agreements govern what may be copied,
where it may be stored, and who may see it. A private GitHub repository does not satisfy them.

- Do not commit data you do not have the right to share, even here.
- Prefer synthetic data that reproduces the analysis structure. This is the approach taken in
  [BEACON](https://github.com/Enpeterson/BEACON), where original data cannot be shared under
  Tribal data governance.
- If in doubt, ask before committing. Removing data from git history is far harder than not
  adding it.

## Proposing something

Open an issue. For anything larger than a typo, an issue first is easier than a surprise pull
request.
