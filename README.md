# Remotion Custom Dev Workspace - by Dedi Nugroho

> **This is a personal fork of [remotion-dev/remotion](https://github.com/remotion-dev/remotion).**
> Remotion is created and maintained by [Remotion](https://www.remotion.dev) (Jonny Burger and contributors).
> All credit for the Remotion engine, its packages and its documentation belongs to the upstream project.

## About this fork

This repository is my personal development workspace on top of Remotion. It is used for a **custom personal use-case & contributing bug fixes/improvements back to upstream Remotion**, in line with the "Allowed use cases" clause of the [Remotion License](LICENSE.md).

Goals of this fork:

- **React video architecture research**: studying how Remotion composes, schedules and renders React-based video (core, renderer, Studio, Player).
- **Testing internal performance and feature fixes**: reproducing issues and validating fixes locally before proposing them upstream.
- **Short-form video rendering automation experiments**: exploring workflows for programmatically rendering short videos with Remotion's existing APIs.

### What this fork is not

- It is **not** an official Remotion distribution and is not affiliated with or endorsed by Remotion.
- It is **not** sold, rented, licensed, relicensed or sublicensed, and it is not offered as a standalone product or replacement for Remotion.
- It does **not** change the license. [LICENSE.md](LICENSE.md) is kept exactly as published upstream and applies to all code in this repository.

If you want to use Remotion, please use the official project:

- Website & docs: [https://www.remotion.dev](https://www.remotion.dev)
- Source: [https://github.com/remotion-dev/remotion](https://github.com/remotion-dev/remotion)
- License & pricing: [remotion.dev/license](https://remotion.dev/license)

## Proposed Upstream Contributions / Custom Fixes

Experiments and bug fixes developed in this fork that may be proposed as pull requests to [remotion-dev/remotion](https://github.com/remotion-dev/remotion). Each entry lives on its own branch so it can be submitted upstream independently.

| Topic | Package(s) | Branch | Status | Upstream PR / Issue |
| ----- | ---------- | ------ | ------ | ------------------- |
| _No entries yet_ | | | | |

Status legend: `Experiment` → `Ready for PR` → `PR opened` → `Merged upstream` / `Closed`

### Workflow

1. Keep `main` in sync with upstream:
   ```bash
   git remote add upstream https://github.com/remotion-dev/remotion.git  # once
   git fetch upstream && git merge upstream/main
   ```
2. Create a topic branch per fix/experiment and add a row to the table above.
3. Build and test with the monorepo tooling (`bun install`, `bunx turbo run make`, `bunx turbo run lint test`).
4. Follow the upstream [CONTRIBUTING.md](CONTRIBUTING.md) and the [contribution guide](https://remotion.dev/docs/contributing) before opening a PR against `remotion-dev/remotion`.

---

_The original upstream Remotion README follows below, unchanged._

<p align="center">
  <a href="https://github.com/remotion-dev/logo">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/remotion-dev/logo/raw/main/animated-logo-banner-dark.apng">
      <img alt="Animated Remotion Logo" src="https://github.com/remotion-dev/logo/raw/main/animated-logo-banner-light.gif">
    </picture>
  </a>
</p>

[![Discord Shield](https://img.shields.io/discord/809501355504959528?color=000000&label=Discord&logo=fdgssdf)](https://remotion.dev/discord)
[![NPM Version](https://img.shields.io/npm/v/remotion.svg?style=flat&color=black)](https://www.npmjs.org/package/remotion)
[![NPM Downloads](https://img.shields.io/npm/dm/remotion.svg?style=flat&color=black&label=Downloads)](https://npmcharts.com/compare/remotion?minimal=true)
<a href="https://twitter.com/remotion"><img src="https://img.shields.io/twitter/follow/remotion?label=Twitter&color=black" alt="Twitter"></a>

Video tools for the agent era.

## Video Creation

- **Make videos agentically**: Turn your idea into a video using your coding agent.
- **Make videos interactively**: Edit and animate using drag and drop.
- **Make videos programmatically**: Connect to data, and manage complexity with code.

React Code is the source of truth. Switch your workflow at any point.

## Video Automation

- **Design systems**: Create a library of animated assets for your organization.
- **Batch rendering**: Render millions of videos on your own infrastructure.
- **Applications**: Publish a simple tool or a complex video editor.

## Get started

If you already have Node.JS installed, type

```console
npx create-video@latest
```

to get started. Otherwise, read the [installation page](https://www.remotion.dev/docs/) in the documentation.

## Discover Remotion

Remotion is extensively documented over more than 1000 pages.

- Get Started
  - [Installation](https://remotion.dev/docs)
  - [Agent Skills](https://www.remotion.dev/docs/ai/skills)
  - [Prompts](https://www.remotion.dev/prompts)
  - [Templates](https://remotion.dev/templates)
- Components
  - [Elements](https://remotion.dev/elements)
  - [Effects](https://remotion.dev/effects)
  - [Shapes](https://remotion.dev/docs/shapes)
  - [Transitions](https://remotion.dev/transitions)
  - [Sound Effects](https://remotion.dev/docs/sfx)
  - [Captions](https://remotion.dev/docs/captions)
  - [Fonts](https://remotion.dev/docs/fonts)
- Rendering
  - [Node.js APIs](https://www.remotion.dev/docs/ssr)
  - [Lambda](https://www.remotion.dev/docs/lambda)
  - [Vercel](https://www.remotion.dev/docs/vercel-sandbox)
  - [Client-side rendering](https://www.remotion.dev/docs/client-side-rendering/)
  - [Comparison of options](https://remotion.dev/docs/compare-ssr)
- Making apps
  - [Player](https://remotion.dev/docs/player)
  - [Editor Starter](https://remotion.dev/editor-starter)
  - [Mediabunny](https://remotion.dev/docs/mediabunny)
- Community
  - [Discord](https://remotion.dev/discord)
  - [Experts](https://remotion.dev/experts)
  - [Resources](https://remotion.dev/resources)
  - [Contributing](https://remotion.dev/contributing)
  - Follow us on [X](https://x.com/remotion), [YouTube](https://youtube.com/@remotion_dev), [Instagram](https://instagram.com/remotion), [LinkedIn](https://linkedin.com/company/remotion)
- Commercial
  - [License](https://remotion.dev/license)
  - [Store](https://remotion.pro/store)
  - [About Remotion](https://remotion.dev/about)
  - [Showcase](https://remotion.dev/showcase)
- Help
  - [Support](https://remotion.dev/support)
  - [Discord](https://remotion.dev/discord)
  - [Search](https://remotion.dev/search)
  - [Ask AI](https://remotion.dev/ai)
  - [GitHub Issues](https://remotion.dev/issues)

## Documentation

Documentation: [**remotion.dev/docs**](https://www.remotion.dev/docs)  
API Reference: [**remotion.dev/api**](https://www.remotion.dev/api)

## License

Be aware of that Remotion has a special license and requires obtaining a company license in some cases. Read the [LICENSE](LICENSE.md) page for more information.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) to learn about contributing to this project.
