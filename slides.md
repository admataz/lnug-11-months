---
title: LNUG Fictional Talk Agenda 2024-2025
info: |
  ## LNUG Fictional Talk Agenda: November 2024 - August 2025
  Catching up on the 11 months we missed - A fictional but thoroughly researched meetup schedule
class: text-center text-sm
drawings:
  persist: false
transition: slide-left
mdc: true
theme: ./theme-lnug

colorScheme: dark
css: unocss
---




<style>
    .slidev-layout {
  font-size: 1em;
}

.slidev-layout ul, .slidev-layout p {
  margin-top: 0;
  margin-bottom: 0.5em;
  font-size: 0.9em;
}

.slidev-layout h1,
.slidev-layout p + h2,
.slidev-layout ul + h2,
.slidev-layout h3{
    font-size: 1.2em;
    margin-top: 0.5em;
    font-family: Montserrat;
    line-height: 100%;
}
 
.references-panel {
  background-color: #efefef;
  color: #000000;
  padding: 1rem;
  border-radius: 0.5rem;
  font-size: 0.85em;
  margin: 1em;
}

.references-panel h3 {
  color: #000000;
  margin-bottom: 0.5rem;
}

.references-panel a {
  color: #2563EB;
  text-decoration: underline;
}

.abstractbox {
    border: 1px solid #ccc; padding: 1rem; margin-top: 0.5rem; border-radius: 0.5rem; background: rgba(255,255,255,0.05);
}

</style>



![](/lnug-logo.svg){width=30% style="display:inline"}

## November 2024 - August 2025

*Catching up on the 11 months of node.js talks*

A fictional but thoroughly researched meetup schedule

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Let's see what we missed <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: default
transition: fade-out
---

<div class="grid grid-cols-3 gap-4 text-xs">

<div>

#### [November 2024 🍂](/3)
**Node.js 23 & Express 5.x Revival**
- Native ESM + require() support
- Express rises from security audit
</div>


<div>

#### [December 2024 🎄](/6) 
**Database & Module Harmony**
- Hidden SQLite in Node.js runtime
- First LTS with require(esm)
</div>

<div>

#### [January 2025 ❄️](/9)
**TypeScript Takes Center Stage**
- Native TS support arrives
- pnpm 10.0 security revolution

</div>

<div>

#### [February 2025 💝](/12)
**Evolution & Security Lessons**
- TypeScript 5.8 for Node devs
- npm's "annus horribilis" analysis
</div>

<div>

#### [March 2025 🌸](/15)
**APIs & Infrastructure Security**
- URLPattern API goes global
- Node.js CI gets compromised
</div>

<div>

#### [April 2025 🌱](/18)
**AI Tooling & Performance Wars**
- VS Code + AI productivity boost
- Fastify vs Next.js showdown

</div>

<div>

#### [May 2025 🌺](/21)
**Version Leaps & Bridges**
- Node 24 worth your attention
- php-node: when worlds collide
</div>

<div>

#### [June 2025 ☀️](/24)
**Performance Revolution & TypeScript Maturity**
- Amaro 1.0 TypeScript engine
- JSON.stringify gets 2x faster
</div>

<div>

#### [July 2025 🏖️](/27)
**Parallelism & Defense**
- Worker threads go production
- npm attack prevention playbook

</div>



<div>

#### [August 2025 🌻](/30)
**Standards & Lifecycle**
- Node 24.6 web APIs evolution
- Node 18 EOL reality check

</div>
</div>


---
transition: fade-out
---

![](/lnug-logo.svg){width=100px style="display:inline"}

# November 2024 🍂

<div class="grid grid-cols-2 gap-4 mt-8">
<div>

### Talk 1: Node.js 23 Features
**The Features That'll Make You Want to Upgrade Yesterday**

**Speaker:** Sarah Chen-Martinez (Senior Platform Engineer at CloudNinja Ltd)

<div class="abstractbox" >
<em>Node.js 23 landed with some game-changing features - ESM modules with `require()` by default, stable `node --run`, and the death of 32-bit Windows support (finally!). Sarah breaks down what these changes mean for your codebase and why the transition from Node 22 LTS might be smoother than you think.</em>
</div>

</div>
<div>

### Talk 2: Express.js Rises
**Version 5.x Is Finally Here**

**Speaker:** Marcus "The Framework Whisperer" Thompson (Freelance Consultant)

<div class="abstractbox" >
<em>As maintainer Wes Todd put it: "We tried to kill [Express] over and over and it keeps on getting up and converting more people into zombies." Express 5.x has officially emerged from its security audit cocoon as a production-ready butterfly. Marcus explores the breaking changes and new governance model.</em>
</div>

</div>
</div>


---
layout: two-cols
---

# Node.js 23: The Features That'll Make You Want to Upgrade Yesterday

**Speaker:** Sarah Chen-Martinez (Senior Platform Engineer at CloudNinja Ltd)  


## 🚀 What's New

- ESM modules with `require()` by default
- Stable `node --run` command
- Death of 32-bit Windows support (finally!)
- TypeScript support brewing in experimental pipeline

## 🎭 Fun Factor
Sarah promises to recreate the "This is Fine" dog meme using only Node.js 23 terminal output.

::right::
<div class="references-panel">

![alt text](/image.png)

### 📚 Source References
- [Node v23.0.0 (Current) Released](https://nodejs.org/en/blog/release/v23.0.0)
- [How Node.js Can Now Run TypeScript](https://samthor.au/2024/node-run-typescript/)

</div>

<!--
Speaker Notes:

**Abstract:** Node.js 23 landed with some game-changing features - ESM modules with `require()` by default, stable `node --run`, and the death of 32-bit Windows support (finally!). Sarah breaks down what these changes mean for your codebase and why the transition from Node 22 LTS might be smoother than you think. Plus, she'll show off some TypeScript support that's still brewing in the experimental pipeline.

**Fun Factor:** Sarah promises to recreate the "This is Fine" dog meme using only Node.js 23 terminal output.
-->

---
layout: two-cols
---

# Express.js Rises From the Zombie Apocalypse

**Speaker:** Marcus "The Framework Whisperer" Thompson (Freelance Consultant)  


## 🧟‍♂️ The Resurrection Story

> "We tried to kill [Express] over and over and it keeps on getting up and converting more people into zombies." 
> — Wes Todd, Maintainer

- Express 5.x emerges from security audit cocoon
- Production-ready butterfly 🦋
- New governance model
- Breaking changes exploration

## 💼 Business Angle
Learn how Express 5's improved security posture affects enterprise adoption decisions.

::right::

<div class="references-panel">


![alt text](/image-2.png)

### 📚 Source References
- [Introducing Express v5: The Official Express v5 Release Post!](https://expressjs.com/2024/10/15/v5-release.html)

</div>

<!--
Speaker Notes:

**Abstract:** As maintainer Wes Todd put it: "We tried to kill [Express] over and over and it keeps on getting up and converting more people into zombies." Express 5.x has officially emerged from its security audit cocoon as a production-ready butterfly. Marcus explores the breaking changes, the new governance model, and answers the burning question: "Should I migrate from Fastify back to Express?"

**Business Angle:** Learn how Express 5's improved security posture and governance changes affect enterprise adoption decisions.
-->

---
transition: fade-out
---
![](/lnug-logo.svg){width=100px style="display:inline"}

# December 2024 🎄

<div class="grid grid-cols-2 gap-4 mt-8">
<div>

### Talk 1: SQLite in Node.js
**The Database That's Been Hiding in Your Runtime**

**Speaker:** Priya Sharma (Database Architect at DataFlow Systems)

<div class="abstractbox" >
<em>While everyone was arguing about MongoDB vs PostgreSQL, Node.js quietly shipped with built-in SQLite support. Priya demonstrates how native SQLite can replace your Redis cache, simplify your test setup, and maybe even handle your next MVP's data layer.</em>
</div>

</div>
<div>

### Talk 2: require(esm)
**The Harmony We've All Been Waiting For**

**Speaker:** Alex Rodriguez (Core Contributor, Node.js)

<div class="abstractbox" >
<em>Node v22.12.0 marked a historic milestone - the first LTS release with non-flagged `require(esm)` support. Alex explains how this seemingly simple feature required years of careful engineering, what edge cases still exist, and why your CommonJS packages can finally make friends with ES modules.</em>
</div>

</div>
</div>

---
layout: two-cols
---

# SQLite in Node.js: The Database That's Been Hiding in Your Runtime

**Speaker:** Priya Sharma (Database Architect at DataFlow Systems)  


## 🗄️ Hidden in Plain Sight

- Native SQLite support shipped quietly with Node.js
- Replace your Redis cache
- Simplify test setups
- Perfect for MVP data layers

## 🌐 Use Cases
- Edge computing
- Embedded applications
- Local development

## 🎯 Fun Factor
Live demo: Build a URL shortener with zero external dependencies (except the domain name)!

::right::


<div class="references-panel">

![alt text](/image-3.png)

### 📚 Source References
- [SQLite | Node.js v24.8.0 Documentation](https://nodejs.org/api/sqlite.html#sqlite) 


</div>

<!--
Speaker Notes:

**Abstract:** While everyone was arguing about MongoDB vs PostgreSQL, Node.js quietly shipped with built-in SQLite support. Priya demonstrates how native SQLite can replace your Redis cache, simplify your test setup, and maybe even handle your next MVP's data layer. From edge computing to embedded applications, discover where SQLite shines brightest.

**Fun Factor:** Live demo of building a URL shortener with zero external dependencies (except the domain name).
-->

---
layout: two-cols
---

# require(esm): The Harmony We've All Been Waiting For

**Speaker:** Alex Rodriguez (Core Contributor, Node.js)  


## 🤝 Historic Milestone

**Node v22.12.0** - First LTS release with non-flagged `require(esm)` support

## 🔧 Technical Deep-dive
- Years of careful engineering
- Edge cases still exist
- CommonJS packages + ES modules = friends without therapy

## ⚙️ Under the Hood
- Module loading mechanics
- "Experimental but enabled by default" explained

::right::

<div class="references-panel">

![alt text](/image-4.png)

### 📚 Source References
- [Node.js Delivers First LTS with `require(esm)` Enabled](https://socket.dev/blog/node-js-delivers-first-lts-with-require-esm-enabled)
- [Node v22.12.0 (LTS)](https://nodejs.org/en/blog/release/v22.12.0)

</div>

<!--
Speaker Notes:

**Abstract:** Node v22.12.0 marked a historic milestone - the first LTS release with non-flagged `require(esm)` support. Alex explains how this seemingly simple feature required years of careful engineering, what edge cases still exist, and why your CommonJS packages can finally make friends with ES modules without family therapy.

**Technical Deep-dive:** Under the hood mechanics of module loading and what "experimental but enabled by default" really means.
-->

---
transition: fade-out
---

![](/lnug-logo.svg){width=100px style="display:inline"}

# January 2025 ❄️

<div class="grid grid-cols-2 gap-4 mt-8">
<div>

### Talk 1: TypeScript + Node.js
**A Love Story 10 Years in the Making**

**Speaker:** Dr. Emma Watson (Type Theory Researcher)

<div class="abstractbox" >
<em>`node yourapp.ts` is no longer a pipe dream! Node 23.6's type stripping brings us native TypeScript support. Emma explores how this differs from ts-node, what TypeScript features you can and can't use, and why this matters for the broader JavaScript ecosystem.</em>
</div>

</div>
<div>

### Talk 2: pnpm 10.0
**The Package Manager That Actually Cares About Your Security**

**Speaker:** Jamie Kim (Security Engineer at SecureStack Inc)

<div class="abstractbox" >
<em>pnpm 10.0 stopped running lifecycle scripts by default, and npm package developers everywhere shed a single tear. Jamie explains why this matters, how the new security features protect against supply chain attacks, and demonstrates the delayed dependency updates feature.</em>
</div>

</div>
</div>



---
layout: two-cols
---

# TypeScript Meets Node.js: A Love Story 10 Years in the Making

**Speaker:** Dr. Emma Watson (Not the actress, but equally brilliant - Type Theory Researcher)  


## 💕 The Dream Realized

```bash
node yourapp.ts
```

No longer a pipe dream!

## 🚀 Node 23.6's Type Stripping

- Native TypeScript support
- Different from ts-node
- Feature limitations and capabilities
- Ecosystem impact

## 💼 Business Impact
- Reduced build complexity
- Faster CI/CD pipelines  
- Happier developers

::right::

<div class="references-panel">

![alt text](/image-5.png)

### 📚 Source References
- [Node.js Now Supports TypeScript By Default](https://www.totaltypescript.com/typescript-is-coming-to-node-23)
- [Node v23.6.0 (Current) Released](https://nodejs.org/en/blog/release/v23.6.0)
- [Node's New Built-in Support for TypeScript Explained](https://2ality.com/2025/01/nodejs-strip-type.html)

</div>

<!--
Speaker Notes:

**Abstract:** `node yourapp.ts` is no longer a pipe dream! Node 23.6's type stripping brings us native TypeScript support. Emma explores how this differs from ts-node, what TypeScript features you can and can't use, and why this matters for the broader JavaScript ecosystem. Spoiler: It's not just about convenience.

**Business Impact:** Reduced build complexity, faster CI/CD pipelines, and happier developers.
-->

---
layout: two-cols
---

# pnpm 10.0: The Package Manager That Actually Cares About Your Security

**Speaker:** Jamie Kim (Security Engineer at SecureStack Inc)  


## 🔒 Security First

- Stopped running lifecycle scripts by default
- npm package developers shed a single tear
- Supply chain attack protection
- Delayed dependency updates

## 📊 Real-world Focus
Case studies from recent npm supply chain attacks and prevention strategies

## 🛡️ Protection Features
- Enhanced security controls
- Weekend-saving delayed updates
- Supply chain vulnerability mitigation

::right::

<div class="references-panel">

![alt text](/image-6.png)

### 📚 Source References
- [pnpm 10.0: The Alternative, Efficient Package Manager](https://github.com/pnpm/pnpm/releases/tag/v10.0.0)
- [pnpm 10.16 Adds Support for Delayed Dependency Updates](https://pnpm.io)

</div>

<!--
Speaker Notes:

**Abstract:** pnpm 10.0 stopped running lifecycle scripts by default, and npm package developers everywhere shed a single tear. Jamie explains why this matters, how the new security features protect against supply chain attacks, and demonstrates the delayed dependency updates feature that could save your weekend.

**Real-world Focus:** Case studies from recent npm supply chain attacks and how pnpm 10's features could have prevented them.
-->

---
transition: fade-out
---

![](/lnug-logo.svg){width=100px style="display:inline"}

# February 2025 💝

<div class="grid grid-cols-2 gap-4 mt-8">
<div>

### Talk 1: TypeScript 5.8
**The Node.js Developer's Dream Release**

**Speaker:** Carlos Martinez (TypeScript Team Liaison, Microsoft)

<div class="abstractbox" >
<em>TypeScript 5.8 was practically made for Node.js developers. From the new `--erasableSyntaxOnly` flag that plays nicely with Node's type stripping to stable `--module node18`, Carlos shows how TypeScript and Node.js are finally becoming best friends.</em>
</div>

</div>
<div>

### Talk 2: npm Security
**The Great npm Security Wake-Up Call**

**Speaker:** Dr. Lisa Zhang (Cybersecurity Researcher, University of Tech London)

<div class="abstractbox" >
<em>From hijacked packages to phishing campaigns targeting maintainers, 2024 was npm's "annus horribilis." Lisa analyzes the attack patterns, explains how social engineering targeted package authors, and provides actionable strategies to protect your projects.</em>
</div>

</div>
</div>


---
layout: two-cols
---

# TypeScript 5.8: The Node.js Developer's Dream Release

**Speaker:** Carlos Martinez (TypeScript Team Liaison, Microsoft)  


## 🎯 Made for Node.js Developers

- New `--erasableSyntaxOnly` flag
- Works perfectly with Node's type stripping
- Stable `--module node18`
- `require()` ES modules in `nodenext` mode

## 🎄 Christmas in February!

Live coding session showcasing:
- Real Node.js applications
- New features in action
- Developer experience improvements

::right::

<div class="references-panel">

![alt text](/image-7.png)

### 📚 Source References
- [Announcing TypeScript 5.8 Beta: A Big One for Node Developers](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8-beta/)
- [Announcing TypeScript 5.8](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8/)

</div>

<!--
Speaker Notes:

**Abstract:** TypeScript 5.8 was practically made for Node.js developers. From the new `--erasableSyntaxOnly` flag that plays nicely with Node's type stripping to stable `--module node18`, Carlos shows how TypeScript and Node.js are finally becoming best friends. Plus, `require()` ES modules in `nodenext` mode - it's like Christmas in February!

**Developer Experience:** Live coding session showing the new features in action with real Node.js applications.
-->

---
layout: two-cols
---

# The Great npm Security Wake-Up Call: Lessons from 2024's Attack Spree

**Speaker:** Dr. Lisa Zhang (Cybersecurity Researcher, University of Tech London)  


## ⚠️ 2024: npm's "Annus Horribilis"

- Hijacked packages
- Phishing campaigns targeting maintainers
- Social engineering attacks on package authors
- Attack pattern analysis

## 🛡️ Defense Strategies

Beyond dependency scanning:
- Practical security policies
- Team protection measures
- Business-critical implementations

::right::

<div class="references-panel">

![alt text](/image-8.png)

### 📚 Source References
- North Korean hackers targeting npm ecosystem
- [Malware Found on npm Infecting Local Package with Reverse Shell](https://www.reversinglabs.com/blog/malicious-npm-patch-delivers-reverse-shell)
- [A Major Supply Chain Attack Hits the npm Ecosystem](https://socket.dev)

</div>

<!--
Speaker Notes:

**Abstract:** From hijacked packages to phishing campaigns targeting maintainers, 2024 was npm's "annus horribilis." Lisa analyzes the attack patterns, explains how social engineering targeted package authors, and provides actionable strategies to protect your projects. Spoiler: It's not just about dependency scanning.

**Business Critical:** Practical implementation of security policies for development teams.
-->

---
transition: fade-out
---

![](/lnug-logo.svg){width=100px style="display:inline"}

# March 2025 🌸

<div class="grid grid-cols-2 gap-4 mt-8">
<div>

### Talk 1: URLPattern API
**The Router You Never Knew You Needed**

**Speaker:** Ryan O'Connor (Web Standards Enthusiast & Framework Author)

<div class="abstractbox" >
<em>Node 23.8 brought us the URLPattern API as a global, and it's quietly revolutionary. Ryan demonstrates how patterns like `/blog/:year/:month/:slug` can simplify routing, API design, and even file system operations. URLPattern is the Swiss Army knife of path matching.</em>
</div>

</div>
<div>

### Talk 2: Node.js CI Security
**When Jenkins Becomes Jekyll & Hyde**

**Speaker:** Tom Wilson (DevSecOps Engineer at CloudSecure)

<div class="abstractbox" >
<em>The Node.js project's own CI infrastructure got compromised, proving that no one is immune. Tom breaks down the attack vector, explains how the Jenkins pipeline flaw was exploited, and shares the lessons learned for CI/CD pipelines.</em>
</div>

</div>
</div>



---
layout: two-cols
---

# URLPattern API: The Router You Never Knew You Needed

**Speaker:** Ryan O'Connor (Web Standards Enthusiast & Framework Author)  


## 🌐 Node 23.8's Quiet Revolution

URLPattern API as a global

```javascript
/blog/:year/:month/:slug
```

## 🔧 Swiss Army Knife of Path Matching

- Routing simplification
- API design improvements
- File system operations
- Express middleware integration
- Static site generators

::right::

<div class="references-panel">

![alt text](/image-13.png)

### 📚 Source References
- [Node v23.8.0 (Current) Released](https://nodejs.org/en/blog/release/v23.8.0)
- [New URLPattern API Brings Improved Pattern Matching to Node](https://blog.cloudflare.com/improving-web-standards-urlpattern/)

</div>

<!--
Speaker Notes:

**Abstract:** Node 23.8 brought us the URLPattern API as a global, and it's quietly revolutionary. Ryan demonstrates how patterns like `/blog/:year/:month/:slug` can simplify routing, API design, and even file system operations. From Express middleware to static site generators, URLPattern is the Swiss Army knife of path matching.

**Framework Focus:** How URLPattern enables new patterns in existing frameworks and libraries.
-->

---
layout: two-cols
---

# Node.js CI Security: When Jenkins Becomes Jekyll & Hyde

**Speaker:** Tom Wilson (DevSecOps Engineer at CloudSecure)  


## 🚨 Nobody Is Immune

**The Node.js project's own CI infrastructure got compromised**

## 🔍 Attack Breakdown
- Jenkins pipeline flaw exploitation
- Attack vector analysis
- Lessons learned from the incident

## 🛡️ Hardening Strategies
Practical CI/CD environment security for Node.js projects

::right::

<div class="references-panel">

![alt text](/image-9.png)


### 📚 Source References
- [Access to Node.js's test CI infrastructure has been restricted](https://nodejs.org/en/blog/vulnerability/march-2025-ci-incident)
- [The Node.js Test CI Security Incident Explained](https://nodejs.org/en/blog/vulnerability/march-2025-ci-incident)

</div>

<!--
Speaker Notes:

**Abstract:** The Node.js project's own CI infrastructure got compromised, proving that no one is immune. Tom breaks down the attack vector, explains how the Jenkins pipeline flaw was exploited, and shares the lessons learned. Essential viewing for anyone running CI/CD pipelines with Node.js projects.

**Security Deep-dive:** Practical hardening strategies for CI/CD environments.
-->

---
transition: fade-out
---

![](/lnug-logo.svg){width=100px style="display:inline"}


# April 2025 🌱

<div class="grid grid-cols-2 gap-4 mt-8">
<div>

### Talk 1: Gen AI tooling for developers
**VS Code + AI: The Node.js Developer's Secret Weapon for 10x Productivity**

**Speaker:** Alex Chen (Developer Productivity Engineer at IntelliFlow)

<div class="abstractbox" >
<em>Beyond basic GitHub Copilot autocomplete lies a treasure trove of AI-powered VS Code extensions revolutionizing Node.js development. Alex demonstrates the latest AI tooling ecosystem: from Copilot's new agent mode that can refactor entire codebases, to Claude and Gemini integrations for code review.</em>
</div>

</div>
<div>

### Talk 2: Fastify + React
**David vs Goliath (Next.js Edition)**

**Speaker:** Jonas Silva (Performance Engineer at SpeedDemon Labs)

<div class="abstractbox" >
<em>Fastify + React claims to be 7x faster than Next.js - but is it too good to be true? Jonas benchmarks real-world applications, explores the trade-offs between features and performance, and demonstrates when Fastify might be the right choice.</em>
</div>

</div>
</div>


---
layout: two-cols
---
# VS Code + AI: The Node.js Developer's Secret Weapon for 10x Productivity

**Speaker:** Alex Chen (Developer Productivity Engineer at IntelliFlow)  


## 🤖 Beyond Basic Autocomplete

The AI revolution in VS Code goes far beyond GitHub Copilot's tab completion

## 🛠️ The New Toolchain
- Copilot's agent mode for codebase refactoring
- Claude & Gemini integrations for code review
- AI-powered debugging that understands async/await
- Context-aware Node.js suggestions

## 🚀 10x Developer Reality
Live coding session: Build a REST API with AI assistance from scratch to deployment

## 💡 Secret Weapons
Extensions and workflows that actually make you faster, not just feel productive

::right::

<div class="references-panel">

![alt text](/image-12.png)

### 📚 Source References
- [Microsoft's Burke Holland shows off VS Code's new 'agent mode' feature](https://www.youtube.com/watch?v=dutyOc_cAEU)
- [GitHub Copilot can now use alternative LLMs like Gemini and Claude](https://github.blog/news-insights/product-news/bringing-developer-choice-to-copilot/)
- [Google Gen AI SDK for TypeScript and JavaScript v1](https://github.com/googleapis/js-genai)
</div>

<!--
Speaker Notes:

**Abstract:** Beyond basic GitHub Copilot autocomplete lies a treasure trove of AI-powered VS Code extensions revolutionizing Node.js development. Alex demonstrates the latest AI tooling ecosystem: from Copilot's new agent mode that can refactor entire codebases, to Claude and Gemini integrations for code review, to AI-powered debugging extensions that actually understand your async/await patterns. See how the right VS Code setup can make you write better Node.js code faster than ever.

**Live Demo Focus:** Real-time coding session showing AI-assisted Node.js development workflows, debugging, and code generation.
-->

---
layout: two-cols
---

# Fastify + React: David vs Goliath (Next.js Edition)

**Speaker:** Jonas Silva (Performance Engineer at SpeedDemon Labs)  


## ⚡ The Bold Claim

**Fastify + React claims to be 7x faster than Next.js**

But is it too good to be true?

## 📊 The Benchmarks
- Real-world applications tested
- Feature vs performance trade-offs
- When Fastify might be the right choice

## ⚠️ Warning
Contains actual performance numbers that might shock you!

::right::

<div class="references-panel">

![alt text](/image-14.png)

### 📚 Source References
- [Fastify + React – 7x Faster than Next.js?](https://hire.jonasgalvez.com.br/2025/apr/9/fastify-speed/)
- [@fastify/react v1.0.0](https://github.com/fastify/fastify-vite/releases/tag/react-v1.0.0)

</div>

<!--
Speaker Notes:

**Abstract:** Fastify + React claims to be 7x faster than Next.js - but is it too good to be true? Jonas benchmarks real-world applications, explores the trade-offs between features and performance, and demonstrates when Fastify might be the right choice. Warning: Contains actual performance numbers that might shock you.

**Performance Focus:** Live benchmarking and practical optimization techniques.
-->

---
transition: fade-out
---

![](/lnug-logo.svg){width=100px style="display:inline"}


# May 2025 🌺

<div class="grid grid-cols-2 gap-4 mt-8">
<div>

### Talk 1: Node 24
**The Current Release That's Actually Worth Your Attention**

**Speaker:** Maria Santos (Platform Engineering Lead at TechFlow)

<div class="abstractbox" >
<em>Node 24 arrived with npm 11, V8 13.6, and URLPattern as a default global. Maria explores the headline features (hello `RegExp.escape` and `Float16Array`), explains why the version jumping from 23 to 24 matters, and demonstrates how Undici 7 changes the HTTP client game.</em>
</div>

</div>
<div>

### Talk 2: php-node
**When Two Worlds Collide**

**Speaker:** Roberto Mendez (Legacy Systems Whisperer)

<div class="abstractbox" >
<em>The folk at Platformatic created php-node, allowing PHP to run inside Node.js. Roberto explores this fascinating bridge between worlds, demonstrates WordPress integration scenarios, and answers the question everyone's thinking: "But... why?" Sometimes the weirdest tools solve the most practical problems.</em>
</div>

</div>
</div>

---
layout: two-cols
---

# Node 24: The Current Release That's Actually Worth Your Attention

**Speaker:** Maria Santos (Platform Engineering Lead at TechFlow)  


## 🎯 Notable Features

- npm 11 included
- V8 13.6 engine
- URLPattern as default global
- `RegExp.escape` and `Float16Array`
- Undici 7 changes the HTTP client game

## 📊 Version Strategy
- Understanding Node.js release cycles
- When to adopt new versions
- Why jumping from 23 to 24 matters

::right::

<div class="references-panel">

![alt text](/image-15.png)

### 📚 Source References
- [Node 24 (Current) Released](https://nodejs.org/en/blog/release/v24.0.0)

</div>

<!--
Speaker Notes:

**Abstract:** Node 24 arrived with npm 11, V8 13.6, and URLPattern as a default global. Maria explores the headline features (hello `RegExp.escape` and `Float16Array`), explains why the version jumping from 23 to 24 matters, and demonstrates how Undici 7 changes the HTTP client game.

**Version Strategy:** Understanding Node.js release cycles and when to adopt new versions.
-->

---
layout: two-cols
---

# The php-node Experiment: When Two Worlds Collide

**Speaker:** Roberto Mendez (Legacy Systems Whisperer)  


## 🤔 The Question Everyone's Thinking

**"But... why?"**

The developers at Platformatic created php-node, allowing PHP to run inside Node.js

## 🌉 Bridge Between Worlds
- WordPress integration scenarios
- Hybrid PHP/Node.js applications
- Migration strategies
- Real-world use cases

## 🛠️ Sometimes the Weirdest Tools...
...solve the most practical problems

::right::

<div class="references-panel">

![alt text](/image-16.png)

### 📚 Source References
- [php-node: A New Way to Bring PHP and Node Together](https://blog.platformatic.dev/seamlessly-blend-php-with-nodejs)
- [php-node GitHub repository](https://github.com/platformatic/php-node)

</div>

<!--
Speaker Notes:

**Abstract:** Someone created php-node, allowing PHP to run inside Node.js. Roberto explores this fascinating bridge between worlds, demonstrates WordPress integration scenarios, and answers the question everyone's thinking: "But... why?" Sometimes the weirdest tools solve the most practical problems.

**Migration Stories:** Real-world use cases for hybrid PHP/Node.js applications.
-->

---
transition: fade-out
---
![](/lnug-logo.svg){width=100px style="display:inline"}


# June 2025 ☀️

<div class="grid grid-cols-2 gap-4 mt-8">
<div>

### Talk 1: Amaro 1.0
**Node.js TypeScript Support Gets Serious**

**Speaker:** Isabella Chen (Node.js Core Team Member)

<div class="abstractbox" >
<em>Amaro 1.0 represents Node.js's official TypeScript type-stripping engine moving from experimental to production-ready. Isabella explains how Amaro works under the hood, what the 1.0 milestone means for TypeScript adoption, and when type stripping will lose its experimental flag.</em>
</div>

</div>
<div>

### Talk 2: JSON.stringify Revolution
**How V8 Made JSON Serialization 2x Faster**

**Speaker:** Dr. Patricia Singh (V8 Performance Engineer at Google)

<div class="abstractbox" >
<em>V8's latest optimization makes JSON.stringify over twice as fast, providing automatic performance boosts for API responses, caching, and data serialization. Patricia breaks down the technical improvements, demonstrates real-world impact, and shows how to take advantage of this free performance win in your Node.js applications.</em>
</div>

</div>
</div>


---
layout: two-cols
---

# Amaro 1.0: Node.js TypeScript Support Gets Serious

**Speaker:** Isabella Chen (Node.js Core Team Member)  


## 🎓 From Experimental to Production

Amaro 1.0 = Node.js's official TypeScript type-stripping engine

## 🏗️ Under the Hood
- Type stripping architecture
- Performance characteristics
- 1.0 milestone significance
- When experimental flag disappears

## 📈 TypeScript Adoption Impact
Production-ready native support changes everything

::right::

<div class="references-panel">

![alt text](/image-17.png)

### 📚 Source References
- [Node.js Moves Toward Stable TypeScript Support with Amaro 1.0](https://socket.dev/blog/node-js-moves-toward-stable-typescript-support-with-amaro-1-0)
- [Amaro 1.0 release](https://github.com/nodejs/amaro/pull/236)
- [The Path to Native TypeScript (video)](https://www.youtube.com/watch?v=l28lEXaUsak)

</div>

<!--
Speaker Notes:

**Abstract:** Amaro 1.0 represents Node.js's official TypeScript type-stripping engine moving from experimental to production-ready. Isabella explains how Amaro works under the hood, what the 1.0 milestone means for TypeScript adoption, and when type stripping will lose its experimental flag.

**Technical Implementation:** Deep dive into type stripping architecture and performance characteristics.
-->

---
layout: two-cols
---

# JSON.stringify Revolution: How V8 Made JSON Serialization 2x Faster

**Speaker:** Dr. Patricia Singh (V8 Performance Engineer at Google)  


## ⚡ The Performance Revolution

**V8 optimizations make JSON.stringify over 2x faster**

## 🚀 Automatic Benefits
- API responses get instant speed boost
- Caching operations accelerate
- Data serialization overhead reduced
- Zero code changes required

## � Technical Deep-dive
- V8 engine optimizations explained
- Benchmark comparisons
- Real-world performance impact

## 💼 Business Impact
Free performance improvements for all Node.js applications using JSON serialization

::right::

<div class="references-panel">

![alt text](/image-18.png)

### 📚 Source References
- [How V8 is Making JSON.stringify More Than Twice as Fast](https://v8.dev/blog/json-stringify)
- V8 performance engineering team blog
- Node.js performance benchmarks

</div>

<!--
Speaker Notes:

**Abstract:** V8's latest optimization makes JSON.stringify over twice as fast, providing automatic performance boosts for API responses, caching, and data serialization. Patricia breaks down the technical improvements, demonstrates real-world impact, and shows how to take advantage of this free performance win in your Node.js applications.

**Performance Focus:** Live benchmarking showing before/after performance comparisons and practical optimization techniques.
-->

---
transition: fade-out
---

![](/lnug-logo.svg){width=100px style="display:inline"}


# July 2025 🏖️

<div class="grid grid-cols-2 gap-4 mt-8">
<div>

### Talk 1: Worker Threads
**Finally Making JavaScript Truly Parallel**

**Speaker:** Yuki Tanaka (Performance Computing Specialist)

<div class="abstractbox" >
<em>Worker threads have matured from experimental curiosity to production-ready parallelism. Yuki demonstrates practical use cases beyond CPU-intensive calculations, shows how to architect applications for multi-core performance, and explains when NOT to use worker threads.</em>
</div>

</div>
<div>

### Talk 2: npm Attack Playbook
**How They Got Us and How We Fight Back**

**Speaker:** Dr. Amanda Foster (Supply Chain Security Expert)

<div class="abstractbox" >
<em>The chalk, debug, and other package hijackings showed how sophisticated npm attacks have become. Amanda analyzes the attack vectors, explains how phishing campaigns targeted package maintainers, and provides a defensive playbook for anyone who runs `npm install` professionally.</em>
</div>

</div>
</div>

---
layout: two-cols
---

# Worker Threads: Finally Making JavaScript Truly Parallel

**Speaker:** Yuki Tanaka (Performance Computing Specialist)  


## 🚀 From Curiosity to Production

Worker threads matured:
- Experimental → Production-ready parallelism
- Beyond CPU-intensive calculations
- Multi-core performance architecture
- When NOT to use worker threads

## 📊 Mind-Changing Benchmarks
Live performance demonstrations for CPU-bound workloads

## 🏗️ Practical Patterns
Real-world use cases and implementation strategies

::right::

<div class="references-panel">

![alt text](/image-19.png)

### 📚 Source References
- [Modern Node.js Patterns - Worker Threads: True Parallelism](https://kashw1n.com/blog/nodejs-2025/)

</div>

<!--
Speaker Notes:

**Abstract:** Worker threads have matured from experimental curiosity to production-ready parallelism. Yuki demonstrates practical use cases beyond CPU-intensive calculations, shows how to architect applications for multi-core performance, and explains when NOT to use worker threads. Includes live benchmarks that will change how you think about Node.js performance.

**Performance Engineering:** Practical patterns for CPU-bound workloads in Node.js.
-->

---
layout: two-cols
---

# The npm Supply Chain Attack Playbook: How They Got Us and How We Fight Back

**Speaker:** Dr. Amanda Foster (Supply Chain Security Expert)  


## 🎯 Sophisticated Attack Vectors

- chalk, debug package hijackings
- Phishing campaigns targeting maintainers
- Attack sophistication evolution

## 🛡️ Defensive Playbook

Required viewing for anyone who runs `npm install` professionally

## 🚨 Critical Security
Actionable strategies for protecting development workflows

::right::

<div class="references-panel">

![alt text](/image-20.png)

### 📚 Source References
- [A Major Supply Chain Attack Hits the npm Ecosystem](https://socket.dev)
- [Chalk package compromise](https://socket.dev)
- [debug package hijacking](https://socket.dev)
- [Phishers targeting npm package developers](https://socket.dev/blog/npm-phishing-email-targets-developers-with-typosquatted-domain)

</div>

<!--
Speaker Notes:

**Abstract:** The chalk, debug, and other package hijackings showed how sophisticated npm attacks have become. Amanda analyzes the attack vectors, explains how phishing campaigns targeted package maintainers, and provides a defensive playbook. Required viewing for anyone who runs `npm install` professionally.

**Critical Security:** Actionable strategies for protecting development workflows.
-->

---
transition: fade-out
---

![](/lnug-logo.svg){width=100px style="display:inline"}


# August 2025 🌻

<div class="grid grid-cols-2 gap-4 mt-8">
<div>

### Talk 1: Node.js 24.6
**Web APIs, Diagnostics, and Web Standards**

**Speaker:** Kevin O'Brien (Web Standards Advocate & Node.js Contributor)

<div class="abstractbox" >
<em>Node 24.6 shows how Node.js is embracing web standards faster than ever. Kevin explores the latest Web API implementations, demonstrates the enhanced diagnostic capabilities, and explains why Node.js's alignment with browser APIs matters for the future of JavaScript development.</em>
</div>

</div>
<div>

### Talk 2: Node.js 18 EOL
**Saying Goodbye to Node.js 18**

**Speaker:** Sofia Andersson (Enterprise Node.js Consultant)

<div class="abstractbox" >
<em>Node.js 18 reached end-of-life, and many production applications are still running it. Sofia explains what EOL really means, demonstrates the upgrade path to Node 22 LTS, and provides a business case for staying current. Plus, she'll share horror stories from the Node 16 to 18 migration trenches.</em>
</div>

</div>
</div>



---
layout: two-cols
---

# Node.js 24.6: Web APIs, Diagnostics, and the Path to Web Standards

**Speaker:** Kevin O'Brien (Web Standards Advocate & Node.js Contributor)  


## 🌐 Embracing Web Standards

Node 24.6 shows faster web standards adoption than ever

## 🚀 Latest Features
- Web API implementations
- Enhanced diagnostic capabilities
- Browser API alignment importance
- Future of JavaScript development

## 🏗️ Architecture Impact
How Node.js's web compatibility strategy affects applications

::right::

<div class="references-panel">

![alt text](/image-21.png)

### 📚 Source References
- [Node.js v24.6.0 (Current) Released](https://nodejs.org/en/blog/release/v24.6.0)
- [Modern Node.js Patterns - Built-in Web APIs](https://kashw1n.com/blog/nodejs-2025/)

</div>

<!--
Speaker Notes:

**Abstract:** Node 24.6 shows how Node.js is embracing web standards faster than ever. Kevin explores the latest Web API implementations, demonstrates the enhanced diagnostic capabilities, and explains why Node.js's alignment with browser APIs matters for the future of JavaScript development.

**Web Standards:** How Node.js's web compatibility strategy affects application architecture.
-->

---
layout: two-cols
---

# The End of an Era: Saying Goodbye to Node.js 18 (And Why You Should Care)

**Speaker:** Sofia Andersson (Enterprise Node.js Consultant)  


## ⚰️ End of Life Reality

**Node.js 18 reached EOL** - many production apps still running it

## 🚀 What EOL Really Means
- Business case for staying current
- Upgrade path to Node 22 LTS
- Horror stories from Node 16→18 migration

## 🏢 Enterprise Strategy
Managing Node.js version lifecycles in business environments

::right::

<div class="references-panel">

![alt text](/image-22.png)

### 📚 Source References
- [PSA: Beware of End-of-Life Node.js Versions](https://nodejs.org/en/blog/announcements/node-18-eol-support)
- [Official Node.js End of Life (EOL) process](https://nodejs.org/en/eol)
- [endoflife.date - Node.js](https://endoflife.date/nodejs)

</div>

<!--
Speaker Notes:

**Abstract:** Node.js 18 reached end-of-life, and many production applications are still running it. Sofia explains what EOL really means, demonstrates the upgrade path to Node 22 LTS, and provides a business case for staying current. Plus, she'll share horror stories from the Node 16 to 18 migration trenches.

**Business Strategy:** Managing Node.js version lifecycles in enterprise environments.
-->

---
layout: center
class: text-center
---

# Key Themes Across the Series

<div class="grid grid-cols-2 gap-8 mt-8">

<div>

## 🔒 **Security & Supply Chain**
Monthly focus on npm attacks, security best practices, and defensive strategies

## 🤖 **AI & Code Generation**  
Integration with modern development workflows and GitHub Copilot

## 🚀 **Major Node.js Releases**
Deep dives into Node 23, 24, and LTS transitions

## ⚡ **Framework Evolution**
Express 5.x revival, Fastify comparisons, and ecosystem changes

</div>

<div>

## 📘 **TypeScript Integration**
Native support development and practical implementation

## 🎯 **Performance & Optimization**
Worker threads, benchmarking, and modern patterns

## 🌐 **Web Standards Alignment**
URLPattern, Web APIs, and browser compatibility

## 👨‍💻 **Developer Experience**
Built-in testing, watch mode, and productivity improvements

</div>

</div>

---
layout: center
class: text-center
---

# Thank You! 🎉

## Questions & Discussion

**Meetup Format:** Hybrid (in-person + streaming)

**Special Features:**
- Live coding demonstrations
- Interactive polls during presentations  
- "Ask the Expert" segments with community contributions
- Monthly "Node.js News Lightning Round"

---

*All speakers are fictional, but the topics and technical content are based on real developments in the Node.js ecosystem from October 2024 through September 2025.*

<div class="absolute bottom-4 right-4">
  <img src="https://nodejs.org/static/images/logo.svg" class="h-8" alt="Node.js" />
</div>