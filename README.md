<p align="center">
  <br>
    <img src="https://on.ahmda.ws/88c124/c"/>
</p>

<h1 align="center">Proposal Modern Dev Tooling</h1>

<p align="center">
  A developer build tooling proposal for default and modern JavaScript based WordPress Core.
</p>

<p align="center">
  <a title="MIT License" href="LICENSE">
    <img src="https://img.shields.io/badge/%E2%86%92-AHMAD%20AWAIS-gray.svg?colorA=2D2A56&colorB=4D2AFF&style=flat">
  </a>
  <a title="Follow on Twitter" href="https://twitter.com/MrAhmadAwais">
    <img src="https://img.shields.io/twitter/follow/MrAhmadAwais.svg?style=social&label=Follow">
  </a>
  <br>
  <br>
</p>

## GOALS

Hey, folks! 🙌

The goal behind creating this proposal document is to help convince the WordPress community, core developers, and especially the contributors behind the all new [Twenty-Nineteen](https://github.com/WordPress/twentynineteen/) default WordPress theme to use developer build tooling. Which in turn will help modernize

## CONTEXT

I'm a full-time open source dev with hundreds of [developer-tooling](https://github.com/AhmadAwais) related FOSS (Free & Open Source Software) projects, one of which is most relevant to this proposal — it's called [create-guten-block](https://github.com/ahmadawais/create-guten-block). Investing in better developer experience and dev-tooling for WordPress developers in the post-Gutenberg world is vital.

#### STATS

The [create-guten-block](https://github.com/ahmadawais/create-guten-block) is used by ~200 Gutenberg WordPress plugins on the WordPress.org repo (As per my knowledge, that is 90% of the total plugins using Gutenberg on WP.org). It's also been download 100,000+ times.

The reason to share this context and the stats is to make a point that developers need to have better tooling at their disposal for not only a better development experience but also building plugins/themes based on Gutenberg with high-quality code. These stats are a testament towards the need of such tooling.

## BENEFITS

For years, default themes have been the source of truth for many new developers, so it's my recommendation that we start [Twenty-Nineteen](https://github.com/WordPress/twentynineteen/) default WordPress theme with some sort of tooling in place. It will be beneficial for the WordPress community in a number of ways, some of which are listed below:

#### 🗃️ **MODERN CODE**

- Use of modern JavaScript i.e. ES6+
- WordPress will have modern code base
- Offline support for WordPress themes will lead to 10x better UX
- It will encourage the use of the latest JavaScript and PHP versions
- The possibility of a modern code base with PWAs, Web/Service Workers
- Make it easier to transition towards a more modular code for WordPress Core

#### 🏇 **FASTER WEB**

- WordPress is 32% of the meaningful web at the moment
- Build tools i.e. webpack will help make 32% of web faster
- JS tree-shaking, removal of unused CSS, optimized mobile sites — all big wins

#### 🌟 **QUALITY CODE**

- Use of standard coding best practice can be enforced
- Build tooling can help add ESLint & Prettier to the mix
- ESLint/Prettier + other linters help improve code quality
- Modern code testing, coverage, deployment, and semantic versioning tools

#### 🦁 **DEVELOPER EXPERIENCE**

- Developer tooling will help improve the DX (Developer Experience)
- Integrations with modern JavaScript eco-system will become easier
- Generally, all build-tools (if used the right way) make developers happy
- Advanced JavaScript developers at Enterprise companies could contribute code

## **SUGGESTIONS**

For the development of [Twenty-Nineteen](https://github.com/WordPress/twentynineteen/) default WordPress theme, I suggest the inclusion of following dev-tools:

- `webpack` —  JavaScript bundler
- `Babel` —  Using Modern JavaScript today
- `ESLint` — Code linting and error reporting
- `Prettier` — Code reformatting as per set standards
- `phpcs` - PHP Code Sniffer to uphold WP PHP Code Standards
- `phpcbf` - PHP Code Beautifier and fixer comes with `phpcs` package
- `create-guten-block` — Sane defaults #ZeroConfig Gutenberg starter kit

Peace! ✌️
