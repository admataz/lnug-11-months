what we should have been talking about

The talks that were not
Given we missed 11 months of LNUG meetups, I hought I'd quickly fill the gaps in the speaker slots. Here we go, 2 talks per month, sometimes 3 on the relevant items to node.js developers each month. 

(all names are fictional)

---



I realise I"ve been asleep a bit longer than I thought
[Platformatic HQ](https://www.platformatichq.com/node-principles) The Nine Node Pillars

Modern Node.js Patterns for 2025
https://kashw1n.com/blog/nodejs-2025/



## October 

Node releases
- Node 23.0
- Node 22.11.0 becomes Active LTS
[Node v23.0.0 (Current) Released](https://nodejs.org/en/blog/release/v23.0.0 "nodejs.org") — Say hello to the newest release line of Node.js that gets all the cutting edge features first (Node 22 will soon become the active LTS release). v23 notably enables support for loading ES modules with `require()` _by default_, drops 32-bit Windows support, and [`node --run`goes stable.](https://nodejs.org/api/cli.html#--run)


[How Node.js Can Now Run TypeScript](https://samthor.au/2024/node-run-typescript/)  SAM THOROGOOD

[Node v22.11.0 'Jod' Released; Becomes Active LTS Release](https://nodejs.org/en/blog/release/v22.11.0 "nodejs.org") — With this release, Node 22 flips from being the ‘Current’ cutting edge release to being a dependable release with the all-important LTS (Long Term Support) designation. It is, however, broadly the same as Node v22.10.


Ecosystem
[Introducing Express v5: The Official Express v5 Release Post!](https://expressjs.com/2024/10/15/v5-release.html "expressjs.com") — We first spied the release of Express.js v5 [over a month ago](https://nodeweekly.com/issues/547) but now we get an official release post that tidies up a lot of loose ends and explains the broad plan. For now, v5 is considered a _bleeding edge_ release with work still required in areas of security and overall process, but things are broadly progressing well.

Other
🎉 In other GitHub news, their Copilot AI coding tool [can now use alternative LLMs like Gemini and Claude](https://github.blog/news-insights/product-news/bringing-developer-choice-to-copilot/), and [GitHub Spark](https://githubnext.com/projects/github-spark) is a new AI-powered tool for rapidly creating and deploying small apps.
- 🤖 Anthropic's Claude AI system has [introduced an 'analysis' tool](https://www.anthropic.com/news/analysis-tool) for writing and running JavaScript within a sandbox, so Claude can perform various calculations and analysis before returning answers.




## November

[Node v23.2.0 (Current) Released](https://nodejs.org/en/blog/release/v23.2.0 "nodejs.org") — On paper, a relatively minor release that updates the root certificates, adding five new ones, but [development of TypeScript support](https://github.com/nodejs/node/pull/55536) has now moved into _active_ development (as opposed to ‘early development’) and there’s [a new `module.stripTypeScriptTypes` API.](https://github.com/nodejs/node/pull/55282)

[Node.js v22 Enters Long Term Support (LTS)](https://nodesource.com/blog/Node.js-v22-Long-Term-Support-LTS "nodesource.com") — This happened in the past couple of weeks, but Lizz has put together a useful update on Node 22’s recent transition to becoming an LTS release and the key features it has baked in.

[Node v18.20.5 (LTS) Released](https://nodejs.org/en/blog/release/v18.20.5 "nodejs.org") — Node v18 remains in its ‘Maintenance LTS’ phase (until May 2025) and while you can’t expect anything big, this release updates a lot of key dependencies and marks import attributes and JSON module support as stable.

[Node.js 22 Runtime Now Available in AWS Lambda](https://aws.amazon.com/blogs/compute/node-js-22-runtime-now-available-in-aws-lambda/ "aws.amazon.com") — AWS’s popular serverless platform, which initially launched with _only_ Node.js support, has [just turned ten](https://aws.amazon.com/blogs/aws/aws-lambda-turns-ten-the-first-decade-of-serverless-innovation/), and this week adds official support for the latest Node LTS release too.

- [Node v23.3.0 (Current)](https://nodejs.org/en/blog/release/v23.3.0) and [v20.18.1 (LTS)](https://nodejs.org/en/blog/release/v20.18.1) have both been released. Both are quite minor in their scope.

Did you know there's and SQlite native lib in node? 


## December
[Node.js Delivers First LTS with `require(esm)` Enabled](https://socket.dev/blog/node-js-delivers-first-lts-with-require-esm-enabled "socket.dev") — It’s a modest milestone, but [Node v22.12.0 (LTS)](https://nodejs.org/en/blog/release/v22.12.0) has been released and marks Node’s first LTS release with non-flagged support for loading native ES modules with `require()`. It’s _still experimental_, though, and [you’re encouraged](https://nodejs.org/en/blog/release/v22.12.0#requireesm-is-now-enabled-by-default) to send in feedback and bug reports.

⚛️ [React 19 has been released.](https://react.dev/blog/2024/12/05/react-19)

[Node v23.4.0 (Current) Released](https://nodejs.org/en/blog/release/v23.4.0 "nodejs.org") — There are new `--trace-env`, `--trace-env-js-stack` and `--trace-env-native-stack` options to track environment variable use by a script. Also `assert.partialDeepStrictEqual`has been added as a way to more quickly assert _certain_ properties are present in an object – you don’t have to supply them all.




timeless but worth mentioning again: 
# The Nine Node Pillars


## January
[Node.js Now Supports TypeScript By Default](https://www.totaltypescript.com/typescript-is-coming-to-node-23 "www.totaltypescript.com") — It’s been possible to run TypeScript directly with Node.js since v22.6 introduced [experimental ‘type stripping’ support](https://nodejs.org/en/learn/typescript/run-natively), but in the [to-be-released-at-any-moment Node 23.6](https://github.com/nodejs/node/pull/56450) (or the current Node nightly) you’ll be able to run `node yourapp.ts` and it’ll Just Work™. Matt provides some details on _how_ it works and what you’ll be able to do.

[Node v23.5.0 (Current) Released](https://nodejs.org/en/blog/release/v23.5.0 "nodejs.org") — A Node release that slipped in just before 2024 ended. WebCryptoAPI’s Ed25519 and X25519 algorithms are now stable and [on-thread hooks](https://nodejs.org/en/blog/release/v23.5.0#on-thread-hooks-are-back) are now back.

[Node v23.6.0 (Current) Released](https://nodejs.org/en/blog/release/v23.6.0 "nodejs.org") — In last week’s issue, we said Node 23.6 was imminent, and it came out a few hours later ;-) Along with the usual dependency updates and bug fixes, the big news is type stripping is now enabled by default, enabling that `node yourapp.ts` magic, described in more detail below..

[Node’s New Built-in Support for TypeScript Explained](https://2ality.com/2025/01/nodejs-strip-type.html "2ality.com") — [Node.js v23.6.0 (Current)](https://nodejs.org/en/blog/release/v23.6.0) (above) makes Node’s new type-stripping features work by default. Dr. Axel digs into how it works and what the limitations are. A handy primer.

[pnpm 10.0: The Alternative, Efficient Package Manager](https://github.com/pnpm/pnpm/releases/tag/v10.0.0 "github.com") — Long admired for its performance and efficiency improvements over npm, [pnpm](https://pnpm.io/) is now thinking hard about security too with v10 no longer running lifestyle scripts of dependencies by default, improved hashing, and a myriad of other tweaks.

[The January 21, 2025 Security Releases](https://nodejs.org/en/blog/vulnerability/january-2025-security-releases "nodejs.org") — Not yet released at the time of publication, but coming to you any moment soon, are fresh releases of the Node 23.x, 22.x, 20.x, and 18.x release lines to tackle some as yet undisclosed security issues.

## February
[Announcing TypeScript 5.8 Beta: A Big One for Node Developers](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8-beta/ "devblogs.microsoft.com") — It's unusual for a TypeScript beta to be exciting for Node developers in particular, but while TypeScript 5.8 is low on features generally, it's _really_ Node focused with [support for `require()` of ES modules in the `nodenext` mode](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8-beta/#support-for-require\(\)-of-ecmascript-modules-in---module-nodenext), a [stable `--module node18`](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8-beta/#--module-node18), and most notably [a `--erasableSyntaxOnly` option](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8-beta/#the---erasablesyntaxonly-option) for ensuring the use of TypeScript that Node 22.6+'s type-stripping features can deal with.

- [Node.js v23.7.0 (Current) has been released](https://nodejs.org/en/blog/release/v23.7.0) with many bug fixes and tweaks. You can now [use glob patterns in the `exclude` option](https://github.com/nodejs/node/pull/56489) of glob functions and [there's a new error](https://github.com/nodejs/node/pull/56610) to let TypeScript users know unsupported TypeScript features are present in their code.

Shout out to Deno
The Deno vs Oracle [JavaScript™ trademark case](https://javascript.tm/) rolls on with Oracle just barely meeting a deadline to [file a motion to dismiss the case.](https://ttabvue.uspto.gov/ttabvue/v?pno=92086835&pty=CAN&eno=7) Oracle asserts that _"relevant consumers do not perceive JAVASCRIPT as a generic term"_and implies JavaScript is quite _clearly_ theirs in the eyes of the public thanks to the popularity of their [Oracle JavaScript Extension Toolkit (JET)](https://www.oracle.com/webfolder/technetwork/jet/index.html).

[Node v22.14.0 (LTS) Released](https://nodejs.org/en/blog/release/v22.14.0 "nodejs.org") — The latest stable/LTS release of Node gets the usual raft of bug fixes and tweaks. Among the more notable ones are [TypeScript support for code evalled via `stdin`](https://github.com/nodejs/node/pull/56359), a new [`--disable-sigusr1` flag](https://github.com/nodejs/node/pull/56441), [`assert.register()`](https://github.com/nodejs/node/pull/56434), and [`t.assert.fileSnapshot()`.](https://github.com/nodejs/node/pull/56459)

[Node v20.18.3 (LTS) Released](https://nodejs.org/en/blog/release/v20.18.3 "nodejs.org") — The main update is the backporting of import attributes and JSON modules is now considered stable.

[Node v23.8.0 (Current) Released](https://nodejs.org/en/blog/release/v23.8.0 "nodejs.org") — You can now tell Node to use the system’s trusted CA certificate store with `--use-system-ca` and there’s an implementation of the [URL Pattern API](https://developer.mozilla.org/en-US/docs/Web/API/URL_Pattern_API) (`URLPattern` will become a global in Node 24). Other minor enhancements include an update to Node’s timezone data and initial support for the zstd compression algorithm (via `node:zlib`).

- The React team has now [officially deprecated _Create React App._](https://react.dev/blog/2025/02/14/sunsetting-create-react-app)

[Announcing TypeScript 5.8](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8/ "devblogs.microsoft.com") — Four months in the making, TypeScript 5.8 lands with a strong Node focus. You can now [use `require()` for ES modules in the `nodenext` module](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8/#support-for-require\(\)-of-ecmascript-modules-in---module-nodenext), there’s [a new `node18` module](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8/#--module-node18) for developers who want to keep targeting Node 18, and most notably there’s now [an `--erasableSyntaxOnly`option](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8/#the---erasablesyntaxonly-option) to ensure no TypeScript-only runtime semantics can be used (ideal if you’re using [Node’s type stripping features](https://nodejs.org/api/typescript.html#type-stripping) to run TypeScript code directly).


## March
[Node Added TypeScript Support, But What Does That Mean for Deno?](https://deno.com/blog/typescript-in-node-vs-deno "deno.com") — The Deno team, learning from previous experiences with Node, went ‘all in’ with TypeScript from day one. Now, Node can work with TypeScript too, but the experience is still very different, and the Deno team explains how here.

[Updates on CVE for End-of-Life Versions](https://nodejs.org/en/blog/vulnerability/updates-cve-for-end-of-life "nodejs.org") — Back in January, the Node.js project decided to [issue CVEs for end-of-life versions of Node](https://nodejs.org/en/blog/vulnerability/upcoming-cve-for-eol-versions) to warn people of the security impacts of using old versions of Node. This [didn’t go down well](https://socket.dev/blog/node-js-eol-versions-cve-dubbed-the-worst-cve-of-the-year) and so the Node project has a new plan going forward.

- A North Korean group of hackers is [continuing with its attempts to poison the npm ecosystem](https://socket.dev/blog/lazarus-strikes-npm-again-with-a-new-wave-of-malicious-packages) with nefarious packages.
- [endoflife.date](https://endoflife.date/) is a handy, updated source of 'end-of-life' dates for hundreds of open source projects, including [Angular](https://endoflife.date/angular), [Node.js](https://endoflife.date/nodejs), and [Vue.](https://endoflife.date/vue) A great resource.

[Node.js Gets an Official Community Space on Discord](https://nodejs.org/en/blog/announcements/official-discord-launch-announcement "nodejs.org") — While there have been numerous IRC channels and Discord and Slack servers where Node developers can congregate, the Nodeiflux Discord server has been promoted to being _an official one_ – [here’s the invite link](https://discord.com/invite/vUsrbjd) if you’re a Discord user. There are already 15k members, so it’s hopping.

[Node v23.10.0 (Current) Released](https://nodejs.org/en/blog/release/v23.10.0 "nodejs.org") — Node gains a new `--experimental-config-file` option for writing a JSON-based config file that contains options that would otherwise litter your command line flags – ideal for configuring the test runner, say.

[Node v20.19.0 (LTS) Released with `require(esm)`](https://nodejs.org/en/blog/release/v20.19.0 "nodejs.org") — Node v20 is in maintenance mode, which usually means no new features, but it lands a significant one here: support for `require(esm)` enabled by default. This means all Node v20+ releases now support loading native ES modules with `require` out of the box. Ideal if you have dependencies to update and you’re still on v20.

[Node.js TSC Votes to Stop Distributing Corepack](https://socket.dev/blog/node-js-tsc-votes-to-stop-distributing-corepack "socket.dev") — [Corepack](https://nodejs.org/api/corepack.html) was introduced as an (experimental) tool _bundled with Node_ to help with managing versions of your package managers. Corepack will live on as a separately installable tool, but will be phased out from future Node releases following [a recent TSC vote](https://github.com/nodejs/TSC/pull/1697#issuecomment-2737093616).

[New URLPattern API Brings Improved Pattern Matching to Node](https://blog.cloudflare.com/improving-web-standards-urlpattern/ "blog.cloudflare.com") — The Cloudflare Workers team has implemented the [URLPattern API](https://urlpattern.spec.whatwg.org/) in the [Ada](https://github.com/ada-url/ada) URL parser, used by both Node.js and Cloudflare Workers. The API lets you take patterns like `/blog/:year/:month/:slug` and test whether URLs match against them. If you’re using Node 23.8+, you can start using it today.


## April
[Express 5.1: Express 5 Finally Becomes the 'Latest' Release](https://expressjs.com/2025/03/31/v5-1-latest-release.html "expressjs.com") — After a period of some dormancy, [Express 5.0](https://expressjs.com/2024/10/15/v5-release.html) was released last year, but remained a somewhat experimental ‘edge’ release as it went through [a security audit](https://expressjs.com/2024/10/22/security-audit-milestone-achievement.html) and process of building up new governance. With 5.1, however, Express 5.x finally becomes the ‘`latest`’ tagged release on npm, so be careful with those upgrades (luckily there’s [a migration guide](https://expressjs.com/en/guide/migrating-5.html)).

💬 I was amused by [some discussion about the release](https://www.reddit.com/r/node/comments/1jo4jzf/express_v510_is_latest/mkqce0b/) on Reddit, where maintainer Wes Todd said: _"We tried to kill [Express] over and over and it keeps on getting up and converting more people into zombies for the zombie mob. So we did the best we could to research a way to bring it back from zombie status."_


- [Node v18.20.8 (LTS)](https://nodejs.org/en/blog/release/v18.20.8) has been released. It's noteworthy mostly due to v18 going 'end of life' later this month. OpenSSL and root certificates get a bump to keep you going for a little longer, but you should update from v18 to v20 or v22 whenever you can.
    
- [Access to Node.js's test CI infrastructure has been restricted](https://nodejs.org/en/blog/vulnerability/march-2025-ci-incident) due to an as-yet-undisclosed vulnerability. A full report of the incident is forthcoming
📄 [Malware Found on npm Infecting Local Package with Reverse Shell](https://www.reversinglabs.com/blog/malicious-npm-patch-delivers-reverse-shell) – _“For the first time, RL researchers discover malicious locally-installed npm packages infecting other legitimate packages.”_


[Node.js Testing Best Practices](https://github.com/goldbergyoni/nodejs-testing-best-practices#readme "github.com") — A detailed guide to modern testing in Node from a group of developers who know all about it. It’s on GitHub but is essentially written like a free book covering over 50 battle-tested tips covering areas as diverse as the ‘Testing Diamond’, testing microservices, checking contracts, verifying OpenAPI correctness, and simulating flaky network conditions.

- [Node v23.11.0 (Current)](https://nodejs.org/en/blog/release/v23.11.0) was released on April Fools' Day but no jokes were in sight, just fixes, tweaks, as well as [a new `process.execve` method](https://github.com/nodejs/node/pull/56496).

[Fastify + React – 7x Faster than Next.js?](https://hire.jonasgalvez.com.br/2025/apr/9/fastify-speed/ "hire.jonasgalvez.com.br") — Node’s [Fastify](https://fastify.dev/) framework has a mature plugin for Vite integration ([explained in detail here](https://blog.platformatic.dev/exploring-react-ssr-with-fastify)), including [@fastify/react](https://github.com/fastify/fastify-vite/releases/tag/react-v1.0.0)which [just hit version 1.0](https://github.com/fastify/fastify-vite/releases/tag/react-v1.0.0) and makes it easy to create fast, featureful (though obviously less so than Next.js) React apps atop Fastify. How fast? Very, it seems.

- If you had problems with npm late last week, the npm registry [accidentally wiped everyone's access tokens.](https://github.com/orgs/community/discussions/156354) The incident, [rounded up here](https://status.npmjs.org/incidents/bndr0gf8nnsq), is now over and everything should be working again.

📄 [NPM Security Best Practices](https://cheatsheetseries.owasp.org/cheatsheets/NPM_Security_Cheat_Sheet.html)  OWASP CHEAT SHEET SERIES

[Microsoft Warns About Node.js' Role in Modern Malware](https://www.microsoft.com/en-us/security/blog/2025/04/15/threat-actors-misuse-node-js-to-deliver-malware-and-other-malicious-payloads/ "www.microsoft.com") — Microsoft’s security team is observing a sharp increase in the use of Node.js to deliver malware and other malicious payloads. This post digs into a couple of examples and what's going on behind the scenes.

[Node v20.19.1 (LTS) Released](https://nodejs.org/en/blog/release/v20.19.1 "nodejs.org") — You know it’s a quiet week when a .1 release is feature-worthy news. Little here except dependency bumps, though, but it’s always good to see an update of what remains a popular Node version (though Node 22 ‘Jod’ should now be your LTS version of choice, ideally).

[Node v22.15.0 (LTS) Released](https://nodejs.org/en/blog/release/v22.15.0 "nodejs.org") — With over 300 commits, this is a meaty update for the most up to date LTS release of Node, though with no _huge_ features. You can now use system certificates on Windows and macOS, numerous dependencies are updated, doc tweaks, and [`process.execve`](https://github.com/nodejs/node/pull/56496) makes an appearance.

[Koa 3.0: The Expressive HTTP Middleware Framework](https://koajs.com/ "koajs.com") — Koa first appeared over a decade ago as a ‘next-generation’ Web framework that shared some of the lineage (and team) of Express.js, but leaning on more modern JavaScript features and ideas of the time. While Express has [been making a comeback recently](https://expressjs.com/2025/03/31/v5-1-latest-release.html), Koa has progressed too and offers a compelling alternative. [v3.0 release notes.](https://github.com/koajs/koa/releases/tag/v3.0.0)

[The Node.js Test CI Security Incident Explained](https://nodejs.org/en/blog/vulnerability/march-2025-ci-incident "nodejs.org") — The Node.js project recently experienced a critical security incident with its test CI infrastructure. Attackers exploited a flaw in the Jenkins pipeline and this post goes into detail about how it came about and was resolved.

- 🤖 Microsoft's Burke Holland [▶️ shows off VS Code's new 'agent mode' feature](https://www.youtube.com/watch?v=dutyOc_cAEU) which really makes Copilot far more powerful and a fine alternative to dedicated AI-powered editors. I've been using it a lot recently and it's worth a try if you're bored of Cursor, etc.


## May
[Node 24 (Current) Released](https://nodejs.org/en/blog/release/v24.0.0 "nodejs.org") — [Node’s release lines](https://nodejs.org/en/about/previous-releases) are in flux – v18 has just gone EOL and now v23 bows out to let v24 be the ‘Current’ release for when you want all the cutting edge features. It comes with npm 11, V8 13.6 (hello `RegExp.escape`, `Float16Array`, `Error.isError` and more), the [`URLPattern`API](https://developer.mozilla.org/en-US/docs/Web/API/URLPattern) exposed as a default object, and Undici 7.

- [Bun v1.2.12 is out](https://bun.sh/blog/bun-v1.2.12) with, surprise, surprise, yet more Node.js compatibility enhancements :-) As part of Bun's new full-stack focus, you can now also stream _browser_ console logs back through Bun at the terminal.
    
- In other alternative runtime news, [Deno 2.3 has been released](https://deno.com/blog/v2.3) with improvements to its single-binary compilation feature which now supports FFI and Node native add-ons, as well as support for using local npm packages.

📄 [npm Targeted by Malware Campaign Mimicking Familiar Library Names](https://socket.dev/blog/npm-targeted-by-malware-campaign-mimicking-familiar-library-names)

- If you've been avoiding Redis after the license controversy in 2024, you'll be happy to know [Redis is now open source again](https://antirez.com/news/151) as of version 8.0.

[Best Practices for Creating a Modern npm Package](https://snyk.io/blog/best-practices-create-modern-npm-package/ "snyk.io") — A step-by-step “as of 2025” walkthrough of creating your own npm package using current best practices. We’ve linked to this before but it’s just been updated

[A Report From April's Node.js Collaboration Summit](https://nodejs.org/en/blog/events/collab-summit-2025-paris "nodejs.org") — Twice a year, a large group of Node contributors and community members get together to discuss the project, brainstorm ideas, and push forward new initiatives. This time, they talked about [the recent CI security incident](https://nodejs.org/en/blog/vulnerability/march-2025-ci-incident), [Async Context](https://github.com/tc39/proposal-async-context), improving Node’s ability to [compile apps into executables](https://nodejs.org/api/single-executable-applications.html), Undici, module loader hooks, and better integration with Chrome’s DevTools.

[Google Gen AI SDK for TypeScript and JavaScript v1](https://github.com/googleapis/js-genai "github.com") — Why let Python developers have all the fun? Now you can harness the full power of Google’s Gemini API (and Vertex platform) from Node too. v1.0 landed a few days ago, but today we also get v1.1 which includes CommonJS support. [The Gemini docs](https://ai.google.dev/gemini-api/docs#javascript) and examples now use it too (if you select JavaScript).

- 🎉 The Deno team put together [a fantastic timeline of JavaScript's history](https://deno.com/blog/history-of-javascript)to celebrate JavaScript's 30th birthday this year.

### June
[php-node: A New Way to Bring PHP and Node Together](https://blog.platformatic.dev/seamlessly-blend-php-with-nodejs "blog.platformatic.dev") — I bet some readers have strong feelings about the idea of mixing PHP and Node.js, but this is a neat project. [php-node](https://github.com/platformatic/php-node) is a native module for Node that enables the running of PHP apps within the Node environment. Why? For migrating legacy apps, building hybrid PHP/JS apps, or Node apps that simply need to call out to PHP for some reason (WordPress, maybe, as we see in this post).

- [DigitalOcean shows off its new Node-powered MCP server](https://www.digitalocean.com/community/tutorials/control-apps-using-mcp-server) which lets you manage DO hosted apps from AI agents / Claude, etc.
- 
[PSA: Beware of End-of-Life Node.js Versions](https://nodejs.org/en/blog/announcements/node-18-eol-support "nodejs.org") — Matteo Collina notes the Node.js ecosystem is _“at a critical juncture”_, with v18 and earlier now ‘End-of-Life’. He breaks down what that really means for users of legacy versions, and why you should skip Active LTS v20 and leap straight to v22 for maximum future-proofing. If you _have_ to stay on older versions, though, Matteo shares an option to consider.

[Node v24.2.0 (Current) Released](https://nodejs.org/en/blog/release/v24.2.0 "nodejs.org") — `import.meta.main` is a new boolean value available in ES modules that tells you if the current module was the entry point of the current process (so you could run specific code only if a module is run directly, say). Support for HTTP/2 priority signalling has also been removed from nghttp2.

[Node.js Moves Toward Stable TypeScript Support with Amaro 1.0](https://socket.dev/blog/node-js-moves-toward-stable-typescript-support-with-amaro-1-0 "socket.dev") — [Amaro](https://github.com/nodejs/amaro) is Node’s official way to strip types out of TypeScript code so that Node can run it (though you can also use Amaro as a library, if you prefer). The [1.0 release](https://github.com/nodejs/amaro/pull/236) is a key milestone on the way to moving TypeScript support in Node.js from experimental to stable in a release later this year. Sarah rounds up the entire story
💡 If you want to dig deeper, Marco Ippolito [▶️ gave a talk called _The Path to Native TypeScript_](https://www.youtube.com/watch?v=l28lEXaUsak) at Node Congress 2025. By the end of it, you'll know everything you need to know about how TypeScript support in Node works and what its limitations are.

- Isaac Z. Schlueter shares [a tribute to Mikeal Rogers](https://blog.izs.me/2025/06/mikeal-rogers/), someone heavily involved in Node over the years, who died last week.

- [Node v20.19.3 (LTS)](https://nodejs.org/en/blog/release/v20.19.3) has been released with Ed25519 and X25519 promoted to stable in WebCryptoAPI, root certificate and dependency updates, and some V8 backports for fix builds on Xcode.


## July
[Node v22.17.0 (LTS) Released](https://nodejs.org/en/blog/release/v22.17.0 "nodejs.org") — A notable LTS release as `assert.partialDeepStrictEqual()` gets promoted to stable along with numerous long-time experimental APIs/functions, and a few Node 24 features get backported.
[Node v24.3.0 (Current)](https://nodejs.org/en/blog/release/v24.3.0) has been released, with no significant new features.

[Ecma International Approves ECMAScript 2025: What’s New?](https://2ality.com/2025/06/ecmascript-2025.html "2ality.com") — The Ecma General Assembly has approved the ES2025 language specification, which you can [read in full here](https://tc39.es/ecma262/2025/), or you can enjoy Dr. Axel’s more succinct explainer instead.

[Node v24.4.0 (Current) Released](https://nodejs.org/en/blog/release/v24.4.0 "nodejs.org") — You can now use `--watch-kill-signal` to specify which signal is sent to a process being restarted by [Node’s ‘watch mode’](https://nodejs.org/api/cli.html#--watch); `spawn` and `spawnSync` now propagate permission model flags; plus the usual V8 and dependency updates.

💡 The Node team has also [announced there are new releases of v24.x, 22.x, and 20.x](https://nodejs.org/en/blog/vulnerability/july-2025-security-releases) in the next day or two to resolve some security issues, so keep an eye out for those.

[Proposal: Shift Node.js to Annual Major Releases](https://github.com/nodejs/Release/issues/1113 "github.com") — A discussion is currently taking place around whether Node could move to having annual major releases and then reducing the LTS duration of the even-numbered releases from the current 30 months down to 24. Community feedback is encouraged on this thread.

[The Node.js July 15 Security Releases](https://nodejs.org/en/blog/vulnerability/july-2025-security-releases "nodejs.org") — Mentioned in passing last week, but landing hours after we sent the newsletter came the releases of [Node.js v24.4.1 (Current)](https://nodejs.org/en/blog/release/v24.4.1/), [v22.17.1 (LTS)](https://nodejs.org/en/blog/release/v22.17.1/) and [v20.19.4](https://nodejs.org/en/blog/release/v20.19.4/) to resolve some security vulnerabilities (a path traversal issue on Windows, and an issue related to hashing in V8).

[How to Create an NPM Package in 2025](https://www.totaltypescript.com/how-to-create-an-npm-package "www.totaltypescript.com") — One of JavaScript’s most essential tasks, but one with numerous steps involved if you want to follow best practices, integrate useful tools, and get things just right. Matt Pocock rounds up the overall process and, notably, drops CommonJS in this 2025 update.

- [Phishers are now targeting npm package developers](https://socket.dev/blog/npm-phishing-email-targets-developers-with-typosquatted-domain) – be alert to this.
- 
- Attacks on the npm ecosystem have continued with [the `is` package getting hijacked](https://socket.dev/blog/npm-is-package-hijacked-in-expanding-supply-chain-attack) through an npm-related typosquatted domain being used to [phish login details.](https://socket.dev/blog/npm-phishing-email-targets-developers-with-typosquatted-domain)

## August
[Node.js v24.5.0 (Current) Released](https://nodejs.org/en/blog/release/v24.5.0 "nodejs.org") — The cutting edge Node release line gets an update to OpenSSL 3.5, `--experimental-wasm-modules` is now unflagged, and `node:http` and `node:https` now support proxies.

- 🔒 [npm now lets you securely publish npm packages](https://github.blog/changelog/2025-07-31-npm-trusted-publishing-with-oidc-is-generally-available/) from CI/CD workflows using OpenID Connect (OIDC) for authentication.

- ⚖️ The Deno team has put together [▶️ a brief video summarizing the Deno vs Oracle JavaScript™ trademark fight.](https://www.youtube.com/watch?v=_tGwOv3scKw) You can also learn a bit more about it in [this open letter to Oracle](https://javascript.tm/) asking it to 'free JavaScript.'

[Node.js v24.6.0 (Current) Released](https://nodejs.org/en/blog/release/v24.6.0 "nodejs.org") — A relatively minor step forward. Node 24.6 lets you use your system’s trusted certificates by setting the `NODE_USE_SYSTEM_CA` environment variable (a la `--use-system-ca`), `zlib` adds Zstd dictionary support, and `http` adds a `keepAliveTimeoutBuffer` option for servers.

- 👋 The official Node site now [has a page explaining the 'End of Life' (EOL) process](https://nodejs.org/en/eol), what things can break when a version goes EOL, and the current status of different Node versions.

- [jQuery 4.0 RC 1](https://blog.jquery.com/2025/08/11/jquery-4-0-0-release-candidate-1/) has been released!

## September
[A Major Supply Chain Attack Hits the npm Ecosystem](https://nodeweekly.com/link/173905/web "socket.dev") — In July, Socket warned us about [a phishing campaign](https://nodeweekly.com/link/173906/web) targeting npm package publishers. Sadly, a prolific package author (among [others](https://nodeweekly.com/link/173907/web), like [DuckDB, who explain how the attack worked on them](https://nodeweekly.com/link/173963/web)) [fell victim](https://nodeweekly.com/link/173908/web) to the scam, resulting in some popular packages becoming compromised ([like Chalk](https://nodeweekly.com/link/173909/web), [debug](https://nodeweekly.com/link/173910/web), and [others](https://nodeweekly.com/link/173911/web)).

[Bringing Node HTTP Servers to _Cloudflare Workers_](https://nodeweekly.com/link/173915/web "blog.cloudflare.com") — A few weeks ago [we linked to an item](https://nodeweekly.com/link/173916/web) that noticed Cloudflare Workers' local dev tools had begun to support Express.js apps – now support has come to _Workers_ proper, with support for `node:http`’s client and server APIs if you enable [Node.js compatibility.](https://nodeweekly.com/link/173917/web)

- On X, [Marco Ippolito laments that Node.js lives in a paradox](https://nodeweekly.com/link/173923/web) of progressing both "too fast" and "too slow" for many developers.

[Node.js v20.19.5 (LTS) Released](https://nodeweekly.com/link/173924/web "nodejs.org") — A quiet release dominated by bugfixes and a large number of dependency updates. It arrived quickly after [v22.19.0 (LTS)](https://nodeweekly.com/link/173925/web), which unflagged `--experimental-wasm-modules`, added `server.keepAliveTimeoutBuffer` to `http`, and added the ability for Node to use the system’s certificate authority (CA) via the `NODE_USE_SYSTEM_CA`environment variable.

[Node.js v24.8.0 (Current) Released](https://nodeweekly.com/link/174291/web "nodejs.org") — The big new feature is added support for inspecting HTTP/2 network calls made from Node in Chrome DevTools. There have also been some [cryptography related enhancements](https://nodeweekly.com/link/174292/web) and `npm` gets upgraded to v11.6.


[pnpm 10.16 Adds Support for Delayed Dependency Updates](https://nodeweekly.com/link/174293/web "pnpm.io") — The alternative efficient npm package manager has added a way to specify a ‘minimum release age’ for package dependencies, so a setting of ‘1440’ (minutes) will mean only packages released more than one day ago will be installed. This can help avoid malicious versions of packages which are quickly withdrawn.

- ⚠️ Last week we featured news of [a significant npm supply chain attack](https://nodeweekly.com/link/174294/web)relating to a variety of popular packages, but yet more are continuing to occur, [this time affecting @ctrl/tinycolor](https://nodeweekly.com/link/174295/web) among others. The payload in this case is particularly dangerous as it installed a secrets scanner and exfiltrated the tokens found. [More technical details here.](https://nodeweekly.com/link/174296/web)
[Oh No, Not Again: A Meditation on npm Supply Chain Attacks](https://nodeweekly.com/link/174300/web "tane.dev") — Noting that “_npm has become the largest and easiest way to ship malware_”, Tane points a finger at Microsoft, the custodians of the npm registry.

- Someone figured out how to [host a web site on a disposable vape.](https://nodeweekly.com/link/174331/web)
