# dong4j.dev

Personal website built with Astro and deployed on Cloudflare Pages. Features a blog, project showcase, and integration with GitHub and Hugging Face APIs.

## Tech Stack

- [Astro](https://astro.build) - Web framework
- [Tailwind CSS](https://tailwindcss.com) - Styling
- [TypeScript](https://www.typescriptlang.org) - Type safety
- [Cloudflare Pages](https://pages.cloudflare.com) - Hosting

## Development

### Prerequisites

- [Node.js](https://nodejs.org) (v20 or higher)
- [pnpm](https://pnpm.io)

### Setup

1. Clone the repository

    ```sh
    git clone https://github.com/dong4j/dong4j.dev.git
    cd dong4j.dev
    ```

2. Install dependencies

    ```sh
    pnpm install
    ```

3. Start the development server

    ```sh
    pnpm dev
    ```

### Build

To build the project for production:

```sh
pnpm build
```

### Scripts

- `pnpm dev` - Start the development server
- `pnpm build` - Build the project for production
- `pnpm preview` - Preview the production build locally
- `pnpm fetch:all` - Fetch latest data from GitHub and Hugging Face APIs

## Features

- **Dark/Light Mode**: Toggle between themes
- **Command Palette**: Access via ⌘K
- **Blog**: Write posts with MDX support
- **Project Showcase**: Highlight your projects
- **GitHub Integration**: Display repositories
- **Hugging Face Integration**: Showcase models and datasets
- **Comments**: Powered by Utterances
- **SEO Friendly**: Optimized for search engines

## Cloudflare Pages Deployment

https://docs.astro.build/zh-cn/guides/deploy/cloudflare/


```bash
npm install -g wrangler
wrangler login
npm run build && npx wrangler pages deploy dist
```

## License

This project is licensed under the [MIT License](LICENSE).
