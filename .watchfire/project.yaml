version: 1
project_id: fafe4c77-495a-44fc-9eaf-8e38596cdc04
name: blowfish
status: active
color: '#8b5cf6'
default_agent: claude-code
sandbox: auto
auto_merge: true
auto_delete_branch: true
auto_start_tasks: true
notifications:
    muted: false
definition: |
    Blowfish is a powerful, lightweight Hugo theme built with Tailwind CSS.
    Repo: https://github.com/nunocoracao/blowfish · Demo & docs: https://blowfish.page/

    Stack & layout:
    - Hugo theme (min Hugo 0.141.0). Templates in `layouts/`, partials in `layouts/partials/`, shortcodes in `layouts/shortcodes/`.
    - Tailwind CSS 4 via `@tailwindcss/cli` — source in `assets/css/main.css`, output in `assets/css/compiled/main.css`.
    - JS vendored from `node_modules/` into `assets/lib/` via `vendor-copy` (configured in `package.json` under `devVendorCopy`).
    - Localisation strings live in `i18n/`. All static text MUST go through `i18n` lookups, never hardcoded.
    - `exampleSite/` is the testbed. Run `npm run example` (or `:core` / `:production`) to preview locally.
    - `config/` holds default theme config; users override in their own site.

    Coding conventions (from CONTRIBUTING.md):
    - 2-space indent. Spaces inside Go template tags: `{{< alert >}}` not `{{<alert>}}`.
    - Extract repeated template logic into partials.
    - Relative asset paths without leading slash; trailing slash for folders (e.g. `static/img/`).
    - Prettier config is included; respect it.

    PR & commit rules (strict — enforced):
    - Single-purpose PRs only. Do NOT bundle unrelated changes (e.g. bug fix + version bump + new user entry). Mixed PRs get closed.
    - NO breaking changes unless strictly required by a dependency. Renaming partials, removing config options, or changing template signatures will be rejected — they silently break user customisations.
    - Commits: Gitmoji prefix, imperative mood ("Fix bug", not "Fixed"), ≤72-char summary, no trailing period. Reference issue numbers when relevant.
    - Commit incrementally rather than one giant commit.

    Before marking a task done:
    - If templates/CSS/JS changed, run `npm run example` and verify in the browser. Type-checks alone don't validate Hugo theme behavior.
    - Check that any new user-facing string is wired through `i18n/` for all supported languages (or at least English with a clear note).
    - Don't bump `package.json` version or touch `release-versions/` as part of a feature/fix PR — those are released separately.
created_at: 2026-05-04T23:12:29.75161Z
updated_at: 2026-05-04T23:12:30.276795Z
next_task_number: 1
