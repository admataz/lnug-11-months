
![[Pasted image 20250815121209.png]]

Here's a summary of main newsworthy events, announcements, and releases from Node Weekly and JavaScript Weekly in the last 11 months:  
  
**Node Weekly:**

- **Node.js Releases and Proposals:**
    - Node v24.4.0 (Current) was released, allowing users to specify the kill signal for processes restarted by Node's 'watch mode'. It also propagates permission model flags for `spawn` and `spawnSync`.
    - New security releases for Node.js v24.x, v22.x, and v20.x were anticipated in July 2025 to resolve security issues.
    - A discussion is ongoing about shifting Node.js to annual major releases and reducing the LTS duration of even-numbered releases from 30 to 24 months.
    - Node v22.17.0 (LTS) was released, promoting `assert.partialDeepStrictEqual()` to stable and backporting some Node 24 features.
    - Node v24.3.0 (Current) was released without significant new features.
    - Node.js v18 reached 'end of life' in April 2025, but Canonical will provide support for Ubuntu Pro users until 2032.
    - Node.js v20.18.0 (LTS) now includes network inspection support.
- **Tools & Libraries:**
    - **Upyo:** A cross-runtime email sending library that offers a unified, type-safe API for both SMTP and HTTP-based providers.
    - **Necord:** A framework for creating Discord bots using Nest and Discord.js.
    - **Rewire 9.0:** Enhances CommonJS modules for easier monkey-patching in unit tests.
    - **Envalid 8.1:** A utility for environment variable validation.
    - **cRonstrue 3.0:** Converts cron expressions into natural language, supporting around thirty locales.
    - **Transformers.js 3.6:** Now supports Google’s new Gemma 3n model, bringing Hugging Face's machine learning models to JavaScript.
    - **Repomix 1.0:** A Node.js-based tool to pack codebases into AI-friendly formats from a GitHub URL.
    - **Marked 16.0:** A fast Markdown parser and compiler.
    - **Whatsapp-api-js:** A library for WhatsApp's official API for Meta Business App users.
    - **dotenv v17.0:** A module to load environment variables from .env files.
    - **npm-package-json-lint 9.0:** A package.json linter for Node projects.
    - **better-sqlite3 v12.2:** Updated to the latest SQLite 3.50.2.
    - **xero-node 13.0:** Node SDK for the Xero accounting system.
    - **Mineflayer 4.30:** Allows creation of Minecraft bots in JavaScript.
    - **Undici 7.11:** Node's HTTP client library.
    - **Docx 9.0:** Generates Word .docx files from JavaScript.
    - **TinyJS:** A lightweight library for working with DOM elements with a jQuery-esque syntax.
    - **SVGuitar 2.4:** Creates SVG-based guitar chord charts dynamically.
    - **TutorialKit 1.0:** StackBlitz’s framework for creating interactive coding tutorials.
    - **Jeasx:** A new server-side rendering framework built on JSX and Fastify.
    - **IP-Address 10.0:** A library for parsing and manipulating IPv4 and IPv6 addresses.
- **Other Noteworthy Information:**
    - A performance comparison of Node version managers showed a 500x performance gap, though it may not matter for most users.
    - ECMAScript 2025 language specification was approved by the Ecma General Assembly.
    - Callstack announced Node-API support for React Native, enhancing native code sharing.
    - North Korean 'threat actors' deployed 67 malicious npm packages.
    - The Node.js project has an official Bluesky account and is seeking community input for content.
    - A quick update on the JavaScript™ trademark dispute between Deno and Oracle.
    - The official Node blog celebrated Pride Month by looking at identity and profiling Emilia Smith.
    - V8 team shared a technical post on speculative optimizations for WebAssembly using deopts and inlining.
    - Tae Kim demonstrated processing a 1 billion row file in Bun in under 10 seconds.
    - Nginx's njs module now uses QuickJS, providing full ES2023 support for extending Nginx functionality with JavaScript.

**JavaScript Weekly:**

- **Key Releases and Updates:**
    - **Next.js 15.4** was released with updates to performance, stability, and Turbopack compatibility. Next.js 16 is also on the horizon.
    - **Vue 3.6 Alpha** was released as a preview, with Vapor Mode as a key addition.
    - **Nuxt v4.0** was released as a major DX-focused update for the full-stack Vue.js framework.
    - **ESLint v9.31.0** updated four core rules to support explicit resource management. ESLint v9.28.0 added more TypeScript syntax support to core rules.
    - **Astro 5.12** was released. Astro 5.9 was also released.
    - **Neutralinojs 6.2** and **OpenPGP.js 6.2** were released.
    - **Tiptap v3:** The headless rich text editor framework, brings DX improvements like unmounting/remounting editors, Markviews, and an SSR mode.
    - **Jest 30:** A faster release of the popular testing framework, with improved ESM and TypeScript support and performance enhancements.
    - **Oxlint 1.0:** The super-fast Rust-powered linter for JavaScript and TypeScript, boasting significant performance improvements over ESLint, has gone stable.
    - **pnpm 10.12:** Introduces an experimental 'global virtual store' for sharing dependencies more efficiently.
    - **Safari 26 (beta):** Includes support for pattern modifiers in RegExp objects.
    - **H3 v2 Beta:** A cross-runtime Web standards focused HTTP server framework.
    - **Deno 2.3.6** was released.
    - **Rollup v4.43** was released.
    - **Jasmine 5.8** was released.
    - **Vue DevTools v7** for Firefox was released.
    - **Babel 8 Beta:** All planned breaking changes for Babel 8 are complete.
    - **Vitest 3.2** was released.
    - **Ionic 8.6** was released.
    - **Prisma 6.9.0** was released.
    - **Storybook 9:** Brings significant updates to testing, offering interaction, visual, and accessibility testing with a 'watch mode'.
    - **Starry Night 3.8:** GitHub-like syntax highlighting.
    - **ngx-vflow 1.9:** Adds node-based interfaces to Angular apps.
    - **Acorn 8.15:** A small, fast, JavaScript-based JavaScript parser.
    - **xo 1.2** and **xo 1


Focusing on Node.js news from the last 11 months, here are some of the most interesting developments in the platform and ecosystem, based on the information I previously provided:  
  
**Platform Developments:**

- **Node.js Releases and Proposals:** There have been several significant Node.js releases, including Node v24.4.0 (Current) and Node v22.17.0 (LTS). These releases brought features like specifying kill signals for 'watch mode' and promoting `assert.partialDeepStrictEqual()` to stable. Discussions are also underway regarding a shift to annual major releases and a reduced LTS duration for even-numbered releases, which could impact release cycles and support timelines. The 'end of life' for Node.js v18 in April 2025 is also a notable event, with Canonical offering extended support for Ubuntu Pro users.
- **Security and Network Inspection:** New security releases for various Node.js versions were anticipated, highlighting ongoing efforts to maintain platform security. Node.js v20.18.0 (LTS) now includes network inspection support, providing developers with better tools for debugging and monitoring network activity.
- **Performance and Optimizations:** A performance comparison of Node version managers revealed significant performance gaps, though the practical impact on most users may be minimal. The V8 team shared technical insights into speculative optimizations for WebAssembly, indicating advancements in how Node.js handles WebAssembly code. Tae Kim' demonstrated impressive performance in Bun, processing a large file quickly, which is relevant to the broader JavaScript runtime ecosystem.

**Ecosystem Developments:**

- **New Tools and Libraries:** The Node.js ecosystem has seen a influx of new and updated tools and libraries. Examples include Upyo for cross-runtime email sending, Necord for Discord bot development, Rewire 9.0 for enhancing CommonJS modules, Envalid 8.1 for environment variable validation, and cRonstrue 3.0 for converting cron expressions. Other notable releases include Repomix 1.0 for packing codebases into AI-friendly formats, Marked 16.0 for Markdown parsing, and Whatsapp-api-js for WhatsApp's official API. These tools and libraries demonstrate the continued innovation and expansion of the Node.js ecosystem, addressing various development needs and use cases.
- **React Native and Native Code Sharing:** Callstack's announcement of Node-API support for React Native is a significant development for developers working with both technologies, enabling enhanced native code sharing.
- **Security Concerns in the Ecosystem:** The deployment of malicious npm packages by 'threat actors' from North Korea highlights the ongoing security challenges within the ecosystem and the importance of vigilance.
- **Community Engagement and Communication:** The Node.js project's official Bluesky account and efforts to seek community input for content indicate a focus on community engagement and broader communication. The quick update on the JavaScript™ trademark dispute between Deno and Oracle is also relevant to the wider JavaScript community.
- **Integration with Other Technologies:** Nginx's njs module now using QuickJS, providing full ES2023 support, demonstrates how Node.js and related technologies are being integrated with other systems to extend functionality.

These developments collectively showcase a dynamic and evolving Node.js platform and ecosystem, with ongoing efforts to improve performance, security, and developer experience, while also expanding into new areas and addressing emerging challenges.  
  
Would you like me to elaborate on any of these points or provide more details on specific releases or tools?