---
hide:
  - navigation
  - toc
---

# Lunchbox Labs

Lunchbox Labs makes an iPhone compass app and plugins for the OpenCode coding agent.

<div class="grid cards" markdown>

-   :lucide-compass:{ .lg .middle } **Compasslet**

    ---

    See your direction on iPhone and while driving with CarPlay. Requires iOS 27
    or later.

    [Compasslet website](https://compasslet.lunchbox-labs.dev/) ·
    [Compasslet on GitHub](https://github.com/lunchbox-labs/compasslet)

-   :lucide-sliders-horizontal:{ .lg .middle } **Config Composer**

    ---

    Share native OpenCode settings through agent groups, with one selected
    profile per worktree.

    Add the package to `plugin` in both `opencode.jsonc` and `tui.jsonc`:

    ```json
    {
      "plugin": [
        "@lunchbox-labs/opencode-config-composer"
      ]
    }
    ```

    [Config Composer on GitHub](https://github.com/lunchbox-labs/opencode-config-composer)

-   :lucide-text-quote:{ .lg .middle } **Prompt Composer**

    ---

    Share reusable prompt text across native OpenCode agents, commands and
    skills with inline includes. Requires Node 22.18 or later.

    Add the package to `plugin` in `opencode.jsonc`, and to `tui.jsonc` for the
    prompt viewer:

    ```json
    {
      "plugin": [
        "@lunchbox-labs/opencode-prompt-composer"
      ]
    }
    ```

    [Prompt Composer on GitHub](https://github.com/lunchbox-labs/opencode-prompt-composer)

</div>

- [Lunchbox Labs on GitHub](https://github.com/lunchbox-labs)
