# Thinking Trail — add/sceneforge-site

> Note: prompts taken verbatim from the session conversation (the work spans the
> Personal-repo session; branch-scoped extraction doesn't apply here).

## Problem Framing

Ahmed asked "are they both missing SceneForge?" while auditing where his AI side
projects are listed, then followed the portfolio PR with: "merge the PR... can you
also make sure its reflected in the /me repo."

## Approach

Audit found the SceneForge card existed locally (commit `ac2b674`) but was never
pushed — the live site didn't show it. The card also had no screenshot (every other
card has one), the two prepared screenshots were unusable (an SPA loading state and
a Vercel 404), and the README had no SceneForge entry.

## Key Decisions

- Retake the screenshot with headless Chrome against the live Studio demo,
  deep-linked to the sample project board (`/generation-styled/p/spring-cafe-look`)
  so the shot shows real product surface — scenes, image options, per-artifact cost,
  GPU spend — instead of an empty profiles page.
- Move the unpushed main-only commit onto a branch and reset local main to origin,
  restoring the branch → PR workflow.
- Update README counts 9 → 10 and add a SceneForge entry consistent with the card.

## Outcome

Live site gains the SceneForge card with screenshot, tools page entry, and README
listing — deployed via GitHub Pages on merge.

<details>
<summary>Raw prompts</summary>

1. "find me the page that has all my AI related side projects"
2. "are they both missing SceneForge? give me the urls"
3. "yes in a PR"
4. "merge the PR... can you also make sure its reflected in the /me repo"

</details>
