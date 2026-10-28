# Code559 Code Examples

Small, working demonstrations of one concept each, served with GitHub Pages so they can be shown in a session and shared afterward.

Live site: https://jrw2july.github.io/code559-code-examples/

## Models

| Folder | Concept | Used in |
| --- | --- | --- |

## How a model is built

- One folder per model, named for the model, with a self-contained `index.html` inside. No build step, no shared files.
- The code shown on the page is the code that runs. Each demo function is written once in the page's script and printed into its code box with `.toString()`, so the two cannot drift apart.
- Only use language and DOM features the learner already has at that point in the course, plus the one concept being demonstrated.
- The page must work at phone width and in light and dark mode.

## Adding a model

1. Branch from `main`, named for the model.
2. Add the folder and its `index.html`.
3. Add a row to the table above and a card to the root `index.html`.
4. Open a pull request and merge it. GitHub Pages publishes `main` from the root.
