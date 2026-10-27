<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SurajMondem/SurajMondem/master/assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SurajMondem/SurajMondem/master/assets/header-light.svg">
  <img alt="Suraj Mondem. Full-stack engineer. Event-driven backends, rules engines, and the React screens people use on top." src="https://raw.githubusercontent.com/SurajMondem/SurajMondem/master/assets/header-light.svg" width="100%">
</picture>

<p>
  <a href="https://www.mondemsuraj.com"><img alt="Website" src="https://img.shields.io/badge/mondemsuraj.com-1f2328?style=flat-square"></a>
  <a href="https://www.mondemsuraj.com/writing"><img alt="Writing" src="https://img.shields.io/badge/Writing-1f2328?style=flat-square&logo=rss&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/surajmondem"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0a66c2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:surajmondem@gmail.com"><img alt="Email" src="https://img.shields.io/badge/surajmondem@gmail.com-c2410c?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://leetcode.com/surajmondem"><img alt="LeetCode" src="https://img.shields.io/badge/LeetCode-1f2328?style=flat-square&logo=leetcode&logoColor=ffa116"></a>
</p>

I replaced 40+ API routes in a healthcare claims app with one config-driven API layer, so a new screen needs a config entry instead of a new endpoint.

That's the kind of work I like: systems where the next change is cheap. I've spent 4+ years building them across healthcare, insurance and title.

## Selected work

<table>
<tr>
<td width="50%" valign="top">

**[posthouse](https://github.com/SurajMondem/posthouse)** · open source

Turns a written post into a narrated, captioned video. One continuous stage, a camera that moves between ideas, visuals timed to the spoken word. Narration from ElevenLabs, a local voice model, or no voice at all.

<sub>Remotion · JavaScript · MIT</sub>

</td>
<td width="50%" valign="top">

**Vaahan** · trucking compliance, 2026

As technical cofounder I built the platform: an event-driven AWS pipeline over Samsara ELD data, a rules engine for federal hours-of-service law, the dashboard and CI/CD. Its warnings flagged likely violations a median 7.7 minutes ahead.

<sub>AWS SAM · Lambda · SQS/SNS · PostgreSQL · React</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Config-driven claims platform** · healthcare

Split a 12-tab claims app into a host and 11 independently deployed microfrontends. Behind it, a FastAPI layer that builds its PostgreSQL queries from config.

<sub>FastAPI · DynamoDB · React · Module Federation</sub>

</td>
<td width="50%" valign="top">

**Change-data-capture audit pipeline** · title insurance

Built the rules-driven enricher in a Debezium and Kafka pipeline on Kubernetes. Rules live in tables and reload every 60 seconds, so a new audit table is a config change, not a deploy.

<sub>Kafka Connect · Spring Boot · Redis · AKS</sub>

</td>
</tr>
</table>

## Writing

**[Beyond First Paint](https://www.mondemsuraj.com/writing/beyond-first-paint)**. What a Lighthouse score actually measures, with 9 interactive demos. The lab said my homepage loads in 3.3 s. Real visitors saw 1.5 s.

More at [mondemsuraj.com/writing](https://www.mondemsuraj.com/writing).

## Stack

<p>
  <img alt="Python, TypeScript, React, Next.js, Angular, FastAPI, Java, Spring, Node.js, PostgreSQL, Redis, Kafka, AWS, Azure, Docker, Kubernetes, GitHub Actions" src="https://skillicons.dev/icons?i=py,ts,react,nextjs,angular,fastapi,java,spring,nodejs,postgres,redis,kafka,aws,azure,docker,kubernetes,githubactions&perline=17" height="40">
</p>

<sub>MS Computer Science, University of Colorado Boulder · BS Computer Science, San Francisco State University · AWS Certified Solutions Architect, Associate</sub>
