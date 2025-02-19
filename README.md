<div align="center">
  <h1 align="center">Hextra</h1>
  <sup align="center"><a href="README.md">English</a> | <a href="README.zh-cn.md">简体中文</a> ｜ <a href="README.fa.md">فارسی</a></sup>
  <p align="center">Modern, responsive, batteries-included Hugo theme for creating beautiful static websites.</p>

Demo → [imfing.github.io/hextra](https://imfing.github.io/hextra/)
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/5097752/263550533-c18343ca-3848-4230-b5c0-ee989d7916da.png">
  <img alt="Hextra" src="https://user-images.githubusercontent.com/5097752/263550528-663599f9-17a1-4686-b5c4-3da233b5034d.png">
</picture>

<div align="right">
<a href="https://github.com/imfing/hextra/actions/workflows/pages.yml"><img alt="GitHub Actions Status" src="https://github.com/imfing/hextra/actions/workflows/pages.yml/badge.svg"></a> <a href="https://app.netlify.com/sites/hugo-hextra/deploys"><img alt="Netlify Status" src="https://api.netlify.com/api/v1/badges/61d6e55a-2447-487e-b59f-c9537e5df175/deploy-status"></a>
</div>

## Features

- **Beautiful Design** - Inspired by Nextra, Hextra utilizes Tailwind CSS to offer a modern design that makes your site look outstanding.
- **Responsive Layout and Dark Mode** - It looks great on all devices, from mobile to desktop. Dark mode is also supported to accommodate various lighting conditions.
- **Fast and Lightweight** - Powered by Hugo, a lightning-fast static-site generator housed in a single binary file, Hextra keeps its footprint minimal. No JavaScript or Node.js are needed to use it.
- **Full-text Search** - Built-in offline full-text search powered by FlexSearch, no extra configuration required.
- **Battery-included** - Markdown, syntax highlighting, LaTeX math formulae, diagrams and Shortcodes elements to enhance your content. Table of contents, breadcrumbs, pagination, sidebar navigation and more are all automatically generated.
- **Multi-language and SEO Ready** - Multi-language sites made easy with Hugo's multilingual mode. Out-of-the-box support is included for SEO tags, Open Graph, and Twitter Cards.

## Quick Start

### Use the template

Using the [Hextra Starter Template](https://github.com/imfing/hextra-starter-template) is the simplest method to bootstrap a new website with Hextra theme. Get started by clicking the "Use this template" button on the template repository page.

The template repository also includes a [GitHub Actions workflow](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-with-a-custom-github-actions-workflow) for deploying your website to GitHub Pages.

<img alt="Hextra Starter Template" src="https://user-images.githubusercontent.com/5097752/263551418-c403b9a9-a76c-47a6-8466-513d772ef0b7.jpg" width=600/>

### Usage

Refer to the [documentation](https://imfing.github.io/hextra/docs) for more information.

## Contributing

Contributions are welcome.
Check out the [contributing guide](.github/CONTRIBUTING.md) to get started.

I dont have much time so here is the FAQ shortcode usage sample

{{< faq >}}
  {{< faq-item title="Who am I?" >}}
  I'm a product designer and front-end developer with over 10 years of experience creating digital experiences. I specialize in user interface design, design systems, and accessibility.
  {{< /faq-item >}}
  
  {{< faq-item title="What services do I offer?" >}}
  - UI/UX Design
  - Front-end Development
  - Design System Implementation
  - Website Optimization
  {{< /faq-item >}}
  
  {{< faq-item title="Who have I worked with?" >}}
  I've collaborated with startups, agencies, and established brands including [Client A], [Client B], and [Client C]. My work spans across fintech, e-commerce, and SaaS platforms.
  {{< /faq-item >}}
  
  {{< faq-item title="How do I work?" >}}
  I follow a collaborative, iterative process focused on solving real user problems. I prefer working in 2-4 week sprints with regular check-ins and clearly defined deliverables.
  {{< /faq-item >}}
  
  {{< faq-item title="What are my rates?" >}}
  I offer project-based pricing as well as monthly retainers depending on your needs. For projects, I typically charge between $X-$Y depending on scope and timeline.
  {{< /faq-item >}}
{{< /faq >}}

I dont have much time so here ENDS the FAQ shortcode usage sample



## License

[MIT License](./LICENSE)
