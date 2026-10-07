<p align="center">
  <img src="./assets/galaxy-header.svg" width="100%" alt="Born too late to explore the earth, born too soon to explore the galaxy, born just in time to create awesome products.">
</p>

<h1 align="center">Hi, I'm Miguel 👋</h1>
<p align="center"><em>Fullstack Product Engineer · Based in Spain</em></p>


## About me

I'm the engineer you want when a problem needs an owner, not a ticket. Over 4+ years as a fullstack engineer, I've worked across engineering, design and product, and I like owning the whole cycle, from idea to shipped feature.

Lately I've been focused on what happens after launch: defining how to measure a feature's success, designing sound experiments, and building the datasets that show how a product is actually used.

Off-topic, ego-driven fun facts:

- I speak four languages, and one of them is spoken by only about 3.5 million people.
- When a swell hits the coast, I want to be able to grab my board and paddle out. That's my whole reason for staying fit after a day at a screen.

## What I'm working on

<h3>Pitaya</h3>

**Fullstack Engineer - <a href="https://www.transkriptorium.com/">Transkriptorium</a>**

Building an end-to-end document annotation platform to train HTR (handwritten text recognition) models. Think Label Studio, but for old manuscript collections.

<h3>Wolflord</h3>

**Creator · In development**

Wolflord is the game I've always wanted to play but could never find. It is a multiplayer survival game set on a vast island system shared by every player alive: frozen arctic, steaming swamp, scorching desert, and forests. Build fires, hunt, craft, and outlast predators and other players. Every death is permanent. Every sunrise is earned.

**Under the hood**: TypeScript end to end, with Phaser 3 in the browser and Node.js on the server · the server is the single source of truth, and Socket.IO keeps every player in sync in real time · player progress is saved in PostgreSQL (Supabase) · the hard part was a huge island of about 16 million tiles, generated the same way every time and streamed to players piece by piece as they explore

## How I Approach AI-Native Development

> **改善**
>
> *I don't believe in software factories that pump out vibed unreviewed AI code. Instead, I apply Kaizen (改善), the Japanese philosophy of continuous improvement, to AI-native workflows: small, consistent improvements that compound over time.*

<p align="center">
  <img src="./assets/ai-workflow.svg" width="100%" alt="AI-native development workflow: spec, scope, tests as contract, agentic team, pull request, human review, quality gates, staging, human QA, production, measure, close the loop">
</p>

**0. Start with a strong spec**

A clear, well-defined spec is the foundation. The better the model understands what to build and why, the less time you spend correcting what it builds. The spec also defines how we'll know the feature worked.

**1. Scope it**

I break work into small, well-defined tasks, because agents do their best work on focused problems and small PRs are easier to review. I also scale the process to the risk: a copy change takes the light path, while auth, payments or data migrations get every step below.

**2. Make the tests the contract**

Many people treat the spec or the code as the contract between you and the model. I think the strongest contract is the tests: unit, integration and end-to-end. A spec can be misread and code can drift, but a test passes or it doesn't. This is where I put the pressure.

**3. Generate with an agentic team**

Instead of one model doing everything, I split the work across specialized agents:
- **Developer:** writes the implementation against the tests
- **Reviewer:** checks quality, readability and adherence to the spec
- **Security auditor:** looks for vulnerabilities and unsafe patterns

**4. Open a pull request**

Agent output goes through the same PR process as human work.

**5. Review the code as a human**

I review agent-written code the way I'd review a colleague's: carefully, critically and as a first-class contribution. Not rubber-stamped, and not dismissed.

**6. Automate the quality gates**

Tests, linting and formatting run automatically. Only when everything passes can the PR be merged, and the merge is always manual.

**7. Deploy to staging via CI**

CI deploys the dev branch to a staging environment that mirrors production.

**8. Human QA in staging**

A person validates the feature in a real environment. This catches what tests can't: UX issues, edge cases nobody specified, and things that are technically correct but feel wrong.

**9. Deploy to production**

Only after staging QA signs off, rolled out behind a feature flag when the change is risky.

**10. Measure in production**

Shipping isn't the finish line. I check the success metric defined in the spec, watch errors and performance, and look at how people actually use the feature. If it isn't working, the flag makes it easy to roll back.

### Closing the loop

After every cycle, I feed what went wrong back into the specs, tests and agent instructions, so the next cycle starts better than the last. That's where the Kaizen lives.

## Tech stack

<table>
  <tr>
    <td><strong>Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" height="24">
    </td>
  </tr>
  <tr>
    <td><strong>Frontend</strong></td>
    <td>
      <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/CSS-663399?style=flat&logo=css&logoColor=white" alt="CSS" height="24">
    </td>
  </tr>
  <tr>
    <td><strong>Backend</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white" alt="Express.js" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white" alt="Django" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/REST_APIs-6C63FF?style=flat&logo=openapiinitiative&logoColor=white" alt="REST APIs" height="24">
    </td>
  </tr>
  <tr>
    <td><strong>Testing</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat&logoColor=white" alt="Playwright" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white" alt="Vitest" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white" alt="Jest" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/React_Testing_Library-E33332?style=flat&logo=testinglibrary&logoColor=white" alt="React Testing Library" height="24">
    </td>
  </tr>
  <tr>
    <td><strong>Infra</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=flat&logo=githubactions&logoColor=white" alt="CI/CD" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/VM_deployments-4A4A55?style=flat&logo=linux&logoColor=white" alt="VM deployments" height="24">
    </td>
  </tr>
  <tr>
    <td><strong>Data</strong></td>
    <td>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" alt="MongoDB" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL" height="24">
    </td>
  </tr>
  <tr>
    <td><strong>Product analytics</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PostHog-1D4AFF?style=flat&logo=posthog&logoColor=white" alt="PostHog" height="24">
      &nbsp;
      <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" height="24">
    </td>
  </tr>
</table>


## Where to find me


If you want to contact me, you can reach me through LinkedIn.

<a href="https://www.linkedin.com/in/miguel-diaz-campos/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" height="28"></a>

---

<p align="center"><em>Thanks for stopping by! 🩵</em></p>