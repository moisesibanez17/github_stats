<div align="center">
  <img src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" width="100px" alt="GitHub Readme Stats" />
  <h1 style="font-size: 28px; margin: 10px 0;">GitHub Readme Stats</h1>
  <p>Get dynamically generated GitHub stats on your READMEs!</p>
</div>

<details>
<summary>Table of contents (Click to show)</summary>

- [GitHub Stats Card](#github-stats-card)
    - [Hiding individual stats](#hiding-individual-stats)
    - [Showing additional individual stats](#showing-additional-individual-stats)
    - [Showing icons](#showing-icons)
    - [Showing commits count for specified year](#showing-commits-count-for-specified-year)
    - [Themes](#themes)
    - [Customization](#customization)
- [GitHub Extra Pins](#github-extra-pins)
    - [Usage](#usage)
    - [Options](#options)
    - [Demo](#demo)
- [GitHub Gist Pins](#github-gist-pins)
    - [Usage](#usage-1)
    - [Options](#options-1)
    - [Demo](#demo-1)
- [Top Languages Card](#top-languages-card)
    - [Usage](#usage-2)
    - [Options](#options-2)
    - [Language stats algorithm](#language-stats-algorithm)
    - [Exclude individual repositories](#exclude-individual-repositories)
    - [Hide individual languages](#hide-individual-languages)
    - [Show more languages](#show-more-languages)
    - [Compact Language Card Layout](#compact-language-card-layout)
    - [Donut Chart Language Card Layout](#donut-chart-language-card-layout)
    - [Donut Vertical Chart Language Card Layout](#donut-vertical-chart-language-card-layout)
    - [Pie Chart Language Card Layout](#pie-chart-language-card-layout)
    - [Hide Progress Bars](#hide-progress-bars)
    - [Change format of language's stats](#change-format-of-languages-stats)
    - [Demo](#demo-2)
- [WakaTime Stats Card](#wakatime-stats-card)
    - [Options](#options-3)
    - [Demo](#demo-3)
- [All Demos](#all-demos)
  - [Quick Tip (Align The Cards)](#quick-tip-align-the-cards)
    - [Stats and top languages cards](#stats-and-top-languages-cards)
    - [Pinning repositories](#pinning-repositories)
- [Deploy on your own](#deploy-on-your-own)
  - [First step: get your Personal Access Token (PAT)](#first-step-get-your-personal-access-token-pat)
    - [Classic token](#classic-token)
    - [Fine-grained token](#fine-grained-token)
  - [On Vercel](#on-vercel)
    - [:film_projector: Check Out Step By Step Video Tutorial By @codeSTACKr](#film_projector-check-out-step-by-step-video-tutorial-by-codestackr)
  - [On other platforms](#on-other-platforms)
  - [Available environment variables](#available-environment-variables)
  - [Keep your fork up to date](#keep-your-fork-up-to-date)
- [:sparkling_heart: Support the project](#sparkling_heart-support-the-project)
</details>

# Important Notices > [!IMPORTANT]
> Since the GitHub API only [allows 5k requests per hour per user account](https://docs.github.com/en/graphql/overview/resource-limitations), the public Vercel instance hosted on `https://github-readme-stats.vercel.app/api` could possibly hit the rate limiter (see [#1471](https://github.com/anuraghazra/github-readme-stats/issues/1471)). We use caching to prevent this from happening (see https://github.com/anuraghazra/github-readme-stats#common-options). You can turn off these rate limit protections by [deploying your own Vercel instance](#deploy-on-your-own).

<img alt="Uptime Badge" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fgithub-readme-stats-git-monitoring-github-readme-stats-team.vercel.app%2Fapi%2Fstatus%2Fup%3Ftype%3Dshields">

> [!IMPORTANT]
> We're a small team, and to prioritize, we rely on upvotes :+1:. We use the Top Issues dashboard for tracking community demand (see [#1935](https://github.com/anuraghazra/github-readme-stats/issues/1935)). Do not hesitate to upvote the issues and pull requests you are interested in. We will work on the most upvoted first.

# GitHub Stats Card

Copy and paste this into your markdown, and that's it. Simple!

Change the `?username=` value to your GitHub username.

```md
[![Moises's GitHub stats](https://githubstats-eight-virid.vercel.app/api?username=moisesibanez17)](https://github.com/moisesibanez17)
```

# Top Languages Card

The top languages card displays the languages you use the most across your repositories.

```md
[![Top Langs](https://githubstats-eight-virid.vercel.app/api/top-langs/?username=moisesibanez17)](https://github.com/moisesibanez17)
```

# GitHub Extra Pins

GitHub extra pins allow you to pin more than 6 repositories in your profile.

```md
[![Readme Card](https://githubstats-eight-virid.vercel.app/api/pin/?username=moisesibanez17&repo=github-readme-stats)](https://github.com/moisesibanez17/github-readme-stats)
```

# WakaTime Stats Card

Translate your WakaTime stats to a nice card.

```md
[![WakaTime Stats](https://githubstats-eight-virid.vercel.app/api/wakatime?username=moisesibanez17)](https://github.com/moisesibanez17)
```

# Themes

With built-in themes, you can customize the look of the card.

```md
[![Moises's GitHub stats](https://githubstats-eight-virid.vercel.app/api?username=moisesibanez17&show_icons=true&theme=radical)](https://github.com/moisesibanez17)
```

# Deploy on your own

This instance is deployed at: `https://githubstats-eight-virid.vercel.app`
