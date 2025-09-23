# LNUG Fictional Talk Agenda: November 2024 - August 2025

*Catching up on the 11 months we missed - A fictional but thoroughly researched meetup schedule*

---

## November 2024 🍂

### "Node.js 23: The Features That'll Make You Want to Upgrade Yesterday"
**Speaker:** Sarah Chen-Martinez (Senior Platform Engineer at CloudNinja Ltd)
**Duration:** 20 minutes

**Abstract:** Node.js 23 landed with some game-changing features - ESM modules with `require()` by default, stable `node --run`, and the death of 32-bit Windows support (finally!). Sarah breaks down what these changes mean for your codebase and why the transition from Node 22 LTS might be smoother than you think. Plus, she'll show off some TypeScript support that's still brewing in the experimental pipeline.

**Fun Factor:** Sarah promises to recreate the "This is Fine" dog meme using only Node.js 23 terminal output.

**Source References:**
- [Node v23.0.0 (Current) Released](https://nodejs.org/en/blog/release/v23.0.0)
- [How Node.js Can Now Run TypeScript](https://samthor.au/2024/node-run-typescript/)
- Note heading: "## October - Node releases"

---

### "Express.js Rises From the Zombie Apocalypse: Version 5.x Is Finally Here"
**Speaker:** Marcus "The Framework Whisperer" Thompson (Freelance Consultant)
**Duration:** 20 minutes

**Abstract:** As maintainer Wes Todd put it: "We tried to kill [Express] over and over and it keeps on getting up and converting more people into zombies." Express 5.x has officially emerged from its security audit cocoon as a production-ready butterfly. Marcus explores the breaking changes, the new governance model, and answers the burning question: "Should I migrate from Fastify back to Express?"

**Business Angle:** Learn how Express 5's improved security posture and governance changes affect enterprise adoption decisions.

**Source References:**
- [Introducing Express v5: The Official Express v5 Release Post!](https://expressjs.com/2024/10/15/v5-release.html)
- Note heading: "## October - Ecosystem"

---

## December 2024 🎄

### "SQLite in Node.js: The Database That's Been Hiding in Your Runtime"
**Speaker:** Priya Sharma (Database Architect at DataFlow Systems)
**Duration:** 20 minutes

**Abstract:** While everyone was arguing about MongoDB vs PostgreSQL, Node.js quietly shipped with built-in SQLite support. Priya demonstrates how native SQLite can replace your Redis cache, simplify your test setup, and maybe even handle your next MVP's data layer. From edge computing to embedded applications, discover where SQLite shines brightest.

**Fun Factor:** Live demo of building a URL shortener with zero external dependencies (except the domain name).

**Source References:**
- Note: "Did you know there's and SQlite native lib in node?"
- Note heading: "## November"

---

### "require(esm): The Harmony We've All Been Waiting For"
**Speaker:** Alex Rodriguez (Core Contributor, Node.js)
**Duration:** 20 minutes

**Abstract:** Node v22.12.0 marked a historic milestone - the first LTS release with non-flagged `require(esm)` support. Alex explains how this seemingly simple feature required years of careful engineering, what edge cases still exist, and why your CommonJS packages can finally make friends with ES modules without family therapy.

**Technical Deep-dive:** Under the hood mechanics of module loading and what "experimental but enabled by default" really means.

**Source References:**
- [Node.js Delivers First LTS with `require(esm)` Enabled](https://socket.dev/blog/node-js-delivers-first-lts-with-require-esm-enabled)
- [Node v22.12.0 (LTS)](https://nodejs.org/en/blog/release/v22.12.0)
- Note heading: "## December"

---

## January 2025 ❄️

### "TypeScript Meets Node.js: A Love Story 10 Years in the Making"
**Speaker:** Dr. Emma Watson (Not the actress, but equally brilliant - Type Theory Researcher)
**Duration:** 20 minutes

**Abstract:** `node yourapp.ts` is no longer a pipe dream! Node 23.6's type stripping brings us native TypeScript support. Emma explores how this differs from ts-node, what TypeScript features you can and can't use, and why this matters for the broader JavaScript ecosystem. Spoiler: It's not just about convenience.

**Business Impact:** Reduced build complexity, faster CI/CD pipelines, and happier developers.

**Source References:**
- [Node.js Now Supports TypeScript By Default](https://www.totaltypescript.com/typescript-is-coming-to-node-23)
- [Node v23.6.0 (Current) Released](https://nodejs.org/en/blog/release/v23.6.0)
- [Node's New Built-in Support for TypeScript Explained](https://2ality.com/2025/01/nodejs-strip-type.html)
- Note heading: "## January"

---

### "pnpm 10.0: The Package Manager That Actually Cares About Your Security"
**Speaker:** Jamie Kim (Security Engineer at SecureStack Inc)
**Duration:** 20 minutes

**Abstract:** pnpm 10.0 stopped running lifecycle scripts by default, and npm package developers everywhere shed a single tear. Jamie explains why this matters, how the new security features protect against supply chain attacks, and demonstrates the delayed dependency updates feature that could save your weekend.

**Real-world Focus:** Case studies from recent npm supply chain attacks and how pnpm 10's features could have prevented them.

**Source References:**
- [pnpm 10.0: The Alternative, Efficient Package Manager](https://github.com/pnpm/pnpm/releases/tag/v10.0.0)
- [pnpm 10.16 Adds Support for Delayed Dependency Updates](https://pnpm.io)
- Note heading: "## January" and "## September"

---

## February 2025 💝

### "TypeScript 5.8: The Node.js Developer's Dream Release"
**Speaker:** Carlos Martinez (TypeScript Team Liaison, Microsoft)
**Duration:** 20 minutes

**Abstract:** TypeScript 5.8 was practically made for Node.js developers. From the new `--erasableSyntaxOnly` flag that plays nicely with Node's type stripping to stable `--module node18`, Carlos shows how TypeScript and Node.js are finally becoming best friends. Plus, `require()` ES modules in `nodenext` mode - it's like Christmas in February!

**Developer Experience:** Live coding session showing the new features in action with real Node.js applications.

**Source References:**
- [Announcing TypeScript 5.8 Beta: A Big One for Node Developers](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8-beta/)
- [Announcing TypeScript 5.8](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8/)
- Note heading: "## February"

---

### "The Great npm Security Wake-Up Call: Lessons from 2024's Attack Spree"
**Speaker:** Dr. Lisa Zhang (Cybersecurity Researcher, University of Tech London)
**Duration:** 20 minutes

**Abstract:** From hijacked packages to phishing campaigns targeting maintainers, 2024 was npm's "annus horribilis." Lisa analyzes the attack patterns, explains how social engineering targeted package authors, and provides actionable strategies to protect your projects. Spoiler: It's not just about dependency scanning.

**Business Critical:** Practical implementation of security policies for development teams.

**Source References:**
- Note: "A North Korean group of hackers is continuing with its attempts to poison the npm ecosystem"
- [Malware Found on npm Infecting Local Package with Reverse Shell](https://www.reversinglabs.com/blog/malicious-npm-patch-delivers-reverse-shell)
- [A Major Supply Chain Attack Hits the npm Ecosystem](https://socket.dev)
- Note heading: "## March" and "## September"

---

## March 2025 🌸

### "URLPattern API: The Router You Never Knew You Needed"
**Speaker:** Ryan O'Connor (Web Standards Enthusiast & Framework Author)
**Duration:** 20 minutes

**Abstract:** Node 23.8 brought us the URLPattern API as a global, and it's quietly revolutionary. Ryan demonstrates how patterns like `/blog/:year/:month/:slug` can simplify routing, API design, and even file system operations. From Express middleware to static site generators, URLPattern is the Swiss Army knife of path matching.

**Framework Focus:** How URLPattern enables new patterns in existing frameworks and libraries.

**Source References:**
- [Node v23.8.0 (Current) Released](https://nodejs.org/en/blog/release/v23.8.0)
- [New URLPattern API Brings Improved Pattern Matching to Node](https://blog.cloudflare.com/improving-web-standards-urlpattern/)
- Note heading: "## February" and "## March"

---

### "Node.js CI Security: When Jenkins Becomes Jekyll & Hyde"
**Speaker:** Tom Wilson (DevSecOps Engineer at CloudSecure)
**Duration:** 20 minutes

**Abstract:** The Node.js project's own CI infrastructure got compromised, proving that no one is immune. Tom breaks down the attack vector, explains how the Jenkins pipeline flaw was exploited, and shares the lessons learned. Essential viewing for anyone running CI/CD pipelines with Node.js projects.

**Security Deep-dive:** Practical hardening strategies for CI/CD environments.

**Source References:**
- [Access to Node.js's test CI infrastructure has been restricted](https://nodejs.org/en/blog/vulnerability/march-2025-ci-incident)
- [The Node.js Test CI Security Incident Explained](https://nodejs.org/en/blog/vulnerability/march-2025-ci-incident)
- Note heading: "## March" and "## April"

---

## April 2025 🌱

### "Express 5.1: The Zombie Framework's Triumphant Return to 'Latest'"
**Speaker:** Jessica Park (Full-stack Developer & Express Contributor)
**Duration:** 20 minutes

**Abstract:** Express 5.1 finally claimed the "latest" tag on npm, making it the default choice for new projects. Jessica explores what this means for the Express ecosystem, the new governance model in action, and whether Express can reclaim its crown from Fastify. Plus, a migration guide that won't make you cry.

**Ecosystem Impact:** How Express 5.x affects the broader Node.js framework landscape.

**Source References:**
- [Express 5.1: Express 5 Finally Becomes the 'Latest' Release](https://expressjs.com/2025/03/31/v5-1-latest-release.html)
- Note heading: "## April"

---

### "Fastify + React: David vs Goliath (Next.js Edition)"
**Speaker:** Jonas Silva (Performance Engineer at SpeedDemon Labs)
**Duration:** 20 minutes

**Abstract:** Fastify + React claims to be 7x faster than Next.js - but is it too good to be true? Jonas benchmarks real-world applications, explores the trade-offs between features and performance, and demonstrates when Fastify might be the right choice. Warning: Contains actual performance numbers that might shock you.

**Performance Focus:** Live benchmarking and practical optimization techniques.

**Source References:**
- [Fastify + React – 7x Faster than Next.js?](https://hire.jonasgalvez.com.br/2025/apr/9/fastify-speed/)
- [@fastify/react v1.0.0](https://github.com/fastify/fastify-vite/releases/tag/react-v1.0.0)
- Note heading: "## April"

---

## May 2025 🌺

### "Node 24: The Current Release That's Actually Worth Your Attention"
**Speaker:** Maria Santos (Platform Engineering Lead at TechFlow)
**Duration:** 20 minutes

**Abstract:** Node 24 arrived with npm 11, V8 13.6, and URLPattern as a default global. Maria explores the headline features (hello `RegExp.escape` and `Float16Array`), explains why the version jumping from 23 to 24 matters, and demonstrates how Undici 7 changes the HTTP client game.

**Version Strategy:** Understanding Node.js release cycles and when to adopt new versions.

**Source References:**
- [Node 24 (Current) Released](https://nodejs.org/en/blog/release/v24.0.0)
- Note heading: "## May"

---

### "The php-node Experiment: When Two Worlds Collide"
**Speaker:** Roberto Mendez (Legacy Systems Whisperer)
**Duration:** 20 minutes

**Abstract:** Someone created php-node, allowing PHP to run inside Node.js. Roberto explores this fascinating bridge between worlds, demonstrates WordPress integration scenarios, and answers the question everyone's thinking: "But... why?" Sometimes the weirdest tools solve the most practical problems.

**Migration Stories:** Real-world use cases for hybrid PHP/Node.js applications.

**Source References:**
- [php-node: A New Way to Bring PHP and Node Together](https://blog.platformatic.dev/seamlessly-blend-php-with-nodejs)
- [php-node GitHub repository](https://github.com/platformatic/php-node)
- Note heading: "## June"

---

## June 2025 ☀️

### "Amaro 1.0: Node.js TypeScript Support Gets Serious"
**Speaker:** Isabella Chen (Node.js Core Team Member)
**Duration:** 20 minutes

**Abstract:** Amaro 1.0 represents Node.js's official TypeScript type-stripping engine moving from experimental to production-ready. Isabella explains how Amaro works under the hood, what the 1.0 milestone means for TypeScript adoption, and when type stripping will lose its experimental flag.

**Technical Implementation:** Deep dive into type stripping architecture and performance characteristics.

**Source References:**
- [Node.js Moves Toward Stable TypeScript Support with Amaro 1.0](https://socket.dev/blog/node-js-moves-toward-stable-typescript-support-with-amaro-1-0)
- [Amaro 1.0 release](https://github.com/nodejs/amaro/pull/236)
- [The Path to Native TypeScript (video)](https://www.youtube.com/watch?v=l28lEXaUsak)
- Note heading: "## June"

---

### "ECMAScript 2025: The JavaScript Features You'll Actually Use"
**Speaker:** Dr. Mikhail Petrov (TC39 Committee Observer)
**Duration:** 20 minutes

**Abstract:** ECMAScript 2025 was approved by Ecma International, bringing new language features to JavaScript. Mikhail highlights the practical additions that will impact Node.js development, explains the standardization process, and demonstrates features you can start using today.

**Standards Deep-dive:** How language evolution affects the Node.js ecosystem.

**Source References:**
- [Ecma International Approves ECMAScript 2025: What's New?](https://2ality.com/2025/06/ecmascript-2025.html)
- [ECMAScript 2025 specification](https://tc39.es/ecma262/2025/)
- Note heading: "## July"

---

## July 2025 🏖️

### "Worker Threads: Finally Making JavaScript Truly Parallel"
**Speaker:** Yuki Tanaka (Performance Computing Specialist)
**Duration:** 20 minutes

**Abstract:** Worker threads have matured from experimental curiosity to production-ready parallelism. Yuki demonstrates practical use cases beyond CPU-intensive calculations, shows how to architect applications for multi-core performance, and explains when NOT to use worker threads. Includes live benchmarks that will change how you think about Node.js performance.

**Performance Engineering:** Practical patterns for CPU-bound workloads in Node.js.

**Source References:**
- [Modern Node.js Patterns - Worker Threads: True Parallelism](https://kashw1n.com/blog/nodejs-2025/)
- Note heading: "## 6. Worker Threads: True Parallelism for CPU-Intensive Tasks"
- From Modern Node.js Patterns article

---

### "The npm Supply Chain Attack Playbook: How They Got Us and How We Fight Back"
**Speaker:** Dr. Amanda Foster (Supply Chain Security Expert)
**Duration:** 20 minutes

**Abstract:** The chalk, debug, and other package hijackings showed how sophisticated npm attacks have become. Amanda analyzes the attack vectors, explains how phishing campaigns targeted package maintainers, and provides a defensive playbook. Required viewing for anyone who runs `npm install` professionally.

**Critical Security:** Actionable strategies for protecting development workflows.

**Source References:**
- [A Major Supply Chain Attack Hits the npm Ecosystem](https://socket.dev)
- [Chalk package compromise](https://socket.dev)
- [debug package hijacking](https://socket.dev)
- [DuckDB explains how the attack worked](https://socket.dev)
- [Phishers are now targeting npm package developers](https://socket.dev/blog/npm-phishing-email-targets-developers-with-typosquatted-domain)
- Note heading: "## July" and "## September"

---

## August 2025 🌻

### "Node.js 24.6: Web APIs, Diagnostics, and the Path to Web Standards"
**Speaker:** Kevin O'Brien (Web Standards Advocate & Node.js Contributor)
**Duration:** 20 minutes

**Abstract:** Node 24.6 shows how Node.js is embracing web standards faster than ever. Kevin explores the latest Web API implementations, demonstrates the enhanced diagnostic capabilities, and explains why Node.js's alignment with browser APIs matters for the future of JavaScript development.

**Web Standards:** How Node.js's web compatibility strategy affects application architecture.

**Source References:**
- [Node.js v24.6.0 (Current) Released](https://nodejs.org/en/blog/release/v24.6.0)
- [Modern Node.js Patterns - Built-in Web APIs](https://kashw1n.com/blog/nodejs-2025/)
- Note heading: "## August" and from Modern Node.js Patterns article

---

### "The End of an Era: Saying Goodbye to Node.js 18 (And Why You Should Care)"
**Speaker:** Sofia Andersson (Enterprise Node.js Consultant)
**Duration:** 20 minutes

**Abstract:** Node.js 18 reached end-of-life, and many production applications are still running it. Sofia explains what EOL really means, demonstrates the upgrade path to Node 22 LTS, and provides a business case for staying current. Plus, she'll share horror stories from the Node 16 to 18 migration trenches.

**Business Strategy:** Managing Node.js version lifecycles in enterprise environments.

**Source References:**
- [PSA: Beware of End-of-Life Node.js Versions](https://nodejs.org/en/blog/announcements/node-18-eol-support)
- [The official Node site now has a page explaining the 'End of Life' (EOL) process](https://nodejs.org/en/eol)
- [endoflife.date - Node.js](https://endoflife.date/nodejs)
- Note heading: "## June" and "## August"

---

## Key Themes Covered Across the Series:

- **Security & Supply Chain:** Monthly focus on npm attacks, security best practices, and defensive strategies
- **AI & Code Generation:** Integration with modern development workflows and GitHub Copilot
- **Major Node.js Releases:** Deep dives into Node 23, 24, and LTS transitions
- **Framework Evolution:** Express 5.x revival, Fastify comparisons, and ecosystem changes
- **TypeScript Integration:** Native support development and practical implementation
- **Performance & Optimization:** Worker threads, benchmarking, and modern patterns
- **Web Standards Alignment:** URLPattern, Web APIs, and browser compatibility
- **Developer Experience:** Built-in testing, watch mode, and productivity improvements

---

*All speakers are fictional, but the topics and technical content are based on real developments in the Node.js ecosystem from October 2024 through September 2025.*

**Meetup Format:** Hybrid (in-person + streaming), with interactive Q&A and networking sessions after each talk block.

**Special Features:**
- Live coding demonstrations
- Interactive polls during presentations  
- "Ask the Expert" segments with community contributions
- Monthly "Node.js News Lightning Round" covering rapid ecosystem changes