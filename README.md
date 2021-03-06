<p align="center">
  <br>
  <a href="https://github.com/ahmadawais/proposal-modern-tooling">
    <img src="https://on.ahmda.ws/954684/c" />
  </a>
</p>

<h1 align="center">Proposal: Modern Dev Tooling</h1>

<p align="center">
  A developer build tooling proposal for modern JavaScript based WordPress Core.
</p>

<p align="center">
  <a title="Autho — Ahmad Awais" href="https://AhmadAwais.com/">
    <img src="https://img.shields.io/badge/by-AHMAD%20AWAIS-gray.svg?colorA=757575&colorB=EF6C00&style=flat">
  </a>
  <a title="Follow on Twitter" href="https://twitter.com/MrAhmadAwais">
    <img src="https://img.shields.io/twitter/follow/MrAhmadAwais.svg?style=social&label=Follow">
  </a>
  <br>
  <br>
</p>

## GOALS

Hey, folks! 🙌

The goal behind creating this proposal document is to help convince the WordPress community, core developers, and especially the contributors behind the all-new [Twenty-Nineteen](https://github.com/WordPress/twentynineteen/) default WordPress theme to use developer build tooling. Which in turn will help modernize

## CONTEXT

I'm a full-time open source dev with hundreds of [developer-tooling](https://github.com/AhmadAwais) related FOSS (Free & Open Source Software) projects, one of which is most relevant to this proposal — it's called [create-guten-block](https://github.com/ahmadawais/create-guten-block). Investing in better developer experience and dev-tooling for WordPress developers in the post-Gutenberg world is vital.

#### STATS

The [create-guten-block](https://github.com/ahmadawais/create-guten-block) is used by ~200 Gutenberg WordPress plugins on the WordPress.org repo (As per my knowledge, that is 90% of the total plugins using Gutenberg on WP.org). CGB has about ~1500 Stargazers/forks and has been downloaded 100,000+ times.

The reason to share this context and the stats is to make a point that developers need to have better tooling at their disposal for not only a better development experience but also building plugins/themes based on Gutenberg with high-quality code. These stats are a testament towards the need of such tooling.

## BENEFITS

For years, default themes have been the source of truth for many new developers, so it's my recommendation that we start [Twenty-Nineteen](https://github.com/WordPress/twentynineteen/) default WordPress theme with developer build tooling in place. It will be beneficial for the WordPress community in many ways, some of which are listed below:

#### 🗃️ **MODERN CODE**

- Use of modern JavaScript, i.e. ES6+
- WordPress will have a modern code base
- Offline support for WordPress themes will lead to 10x better UX
- It will encourage the use of the latest JavaScript and PHP versions
- The possibility of a modern code base with PWAs, Web/Service Workers
- Make it easier to transition towards a more modular code for WordPress Core

#### 🏇 **FASTER WEB**

- WordPress is 32% of the meaningful web at the moment
- Build tools, i.e. webpack will help make 32% of web faster
- JS tree-shaking, removal of unused CSS, optimized mobile sites — all big wins

#### 🌟 **QUALITY CODE**

- Build tooling can help add ESLint & Prettier to the mix
- ESLint/Prettier + other linters help improve code quality
- Build tools make it easier to use standard coding best practices
- Modern code testing, coverage, deployment, and semantic versioning tools

#### 🦁 **DEVELOPER EXPERIENCE**

- Developer tooling will help improve the DX (Developer Experience)
- Integrations with modern JavaScript eco-system will become easier
- Generally, all build-tools (if used the right way) make developers happy
- Advanced JavaScript developers at Enterprise companies could contribute code

## **SUGGESTIONS**

For the development of [Twenty-Nineteen](https://github.com/WordPress/twentynineteen/) default WordPress theme, I suggest the inclusion/building of following dev-tools:

- `webpack` —  JavaScript bundler
- `Babel` —  Using Modern JavaScript today
- `ESLint` — Code linting and error reporting
- `Prettier` — Code reformatting as per set standards
- `phpcs` - PHP Code Sniffer to uphold WP PHP Code Standards
- `phpcbf` - PHP Code Beautifier and fixer comes with `phpcs` package
- `create-guten-block` — Sane defaults #ZeroConfig Gutenberg starter kit

## **FAQs**

It's expected to have some sort of backlash towards this proposal so, I am going to keep a log of frequently asked questions and their answers.

#### ❓ Are you suggesting we build custom blocks inside a WordPress Theme?

**NO**. I never said that. Since the day I built [create-guten-block](https://github.com/ahmadawais/create-guten-block) I have been preaching the same lesson, `Custom blocks should only be built inside plugins`. Yes, blocks go in plugins.

And in this case I am suggesting that we build a TwentyNineteen Companion plugin to showcase how we can extend WordPress with custom blocks. WordPress is a CMS and for building custom blocks we'll need companion plugin with the theme. That plugin should have a build tooling process to it.

Default themes used to do that. TwentySeventeen has custom pages and customizer helped. With TwentyNineteen we can showcase custom blocks as well. Developers look at default themes to derive inspiration for their work.

That's what I am recommending.

#### ❓ TwentyNineteen should be kept simple!

Sure, it should be. But there's an opportunity here that can be explored. If we built Gutenberg to only build simple CSS only WordPress themes without showcasing what custom blocks are now capable of — then we just wasted two years for nothing.

I get the idea that there should be a simple theme to showcase simple things. But there can easily be a companion plugin to showcase how to extend WordPress with Gutenberg and improve your dev experience with dev tooling.

> _*NOTE*_: I think all of the custom blocks related code should probably go in a companion plugin for this theme. That has always been the general consensus and my recommendation to fellow developers.

## WHAT'S NEXT

> For further discussions I have opened up this issue on the [TwentyNineteen repo →](https://github.com/WordPress/twentynineteen/issues/70)

Peace! ✌️
