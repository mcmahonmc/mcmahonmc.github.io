---
title: Measuring Momentum
date: 2023-09-30
subtitle: Benchmarking / UX • Mercari
image: '/images/projects/benchmarking/header.png'
---

### Mercari was on the cusp of developing three bold, new features. We needed a way to systematically monitor changes in ease of use, navigation, and core functionality over time.

### I spearheaded a systematic benchmarking survey program to measure how our product aligned with company objectives and UX values over time, including ease of use, navigation, competitor engagement, & product performance.

# Outcome

The UX Benchmarking dashboard allowed our research team to streamline analysis and reporting of rating scale, multiple choice, and open text survey responses collected from app users on a quarterly basis.

In its first iteration, the benchmarking survey led to search experiments designed to improve the relevance of search queries for items that either (1) returned few related results (low inventory), or (2) were in the clothing category.

* __+13%__ orders via low-hit search queries
* __+5%__ orders via clothing size searches
* __+8%__ likes via clothing size searches

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/benchmarking/dashboard-1.png" B loading="lazy" alt="Artifact">
  </div>
   <em>Dashboard Screenshot</em>
</div>

# My Research Process

## Research Brainstorming

I researched both prior internal approaches to benchmarking as well as external examples to understand what was possible and how benchmarking could best benefit our organization.

I audited existing resources and budget for recruitment channels, then drafted a proposal based on the priorities and constraints I identified.

## Stakeholder Interviews

Getting buy in and measuring what matters were crucial to the success of this project. While I conducted my own exploration, I scheduled 1:1 interviews both within and outside of the design team to understand what stakeholders would want to get out of a benchmarking program. Ultimately, a key theme was that we wanted to measure key UX values like ease of use and navigability, and remain adaptable irrespective of changes in company direction or prioritization. 

## Study Plan

I asked stakeholders, including product managers, product leadership, product marketing managers, UX designers, and UX management, to help co-create the recruitment criteria and content. This was reviewed with UX, product managers, CRM, and product leadership.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/benchmarking/study-plan.jpeg" B loading="lazy" alt="Artifact">
    <img src="/images/projects/benchmarking/study-plan-3.jpeg" B loading="lazy" alt="Artifact">
    <img src="/images/projects/benchmarking/study-plan-2.jpeg" B loading="lazy" alt="Artifact">
  </div>
  <em>Study Plan Excerpts</em>
  
</div>

## Looker Integration and Dashboard Creation

I worked closely with Data Engineering to set up a Looker integration to
facilitate data accessibility and triangulation. This way, incoming survey data from the benchmarking reports would automatically be visualized in a Looker dashboard, which could be filtered by other key segmentation criteria we were considering such as customer growth segment and age group.

## Facilitation

I fielded the survey, which was administered as a shorter live-intecept survey with the option of continuing to a longer form, static link survey. We collected data on ease of use, navigability, core user tasks, product-market fit, and competitor experiences. 

I also got approval to offer a sweepstakes style incentive for the first time at Mercari. 

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/benchmarking/sprig.png" B loading="lazy" alt="Artifact">
  </div>
  <em>Live-intercept survey audience settings / <a href="www.sprig.com" target="_blank">Sprig</a></em>
</div>

## Analysis

In addition to tracking quarterly metrics like user satisfaction, ease of use, ease of navigation, and product-market fit, we also collected open-text feedback that was synthesized at first pass using Sprig's AI. Aided with manual
inspection, three main opportunity areas emerged, including search (especially low-hit search queries and clothing queries), item discovery, and listing efficiency.

## Reporting

I organized a recurring quarterly research share-out venue, which drew 70+ employees from across the entire organization. At the time, this was the majority of our US staff!

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/benchmarking/slide-1.png" B loading="lazy" alt="">
    <img src="/images/projects/benchmarking/slide-2.png" B loading="lazy" alt="">
  </div>
  <em>Initial Benchmarking Report Excerpts</em>
</div>

# Research Impact

## Immediately influenced product roadmap

The benchmarking program findings were influential in approving a new focus on search UX improvements for the following quarter, and were immediately actioned on by our machine learning and customer relations management teams.

## Upskilled research team in behavioral analytics

Advocating for a Looker integration provided our team with greater need and opportunities to develop more quantitative skills. I led “Looker labs” and hosted office hours to support teammates in growing this skillset.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/benchmarking/looker-labs.png" B loading="lazy" alt="Artifact">
  </div>
  <em>Hosting a 'Looker Lab'</em>
</div>

## Built bridges with data engineering and business insights teams

Quantitative data historically has been more accessible to Mercari employees. But in collaborating with new teams to build this integration, and in establishing our first company-facing dashboard, this opened more opportunities for user research consumption across the organization.

## Visibility into trends over time

Because this was conducted on a quarterly basis, we were able to glean the relative prevalence of different pain points in relation to each quarter's rapid product changes.

# Future applications

Because of the size of this dataset, we can derive clusters based on a combination of users' attitudinal and behavioral data to inform user segmentation. As a personal project, I applied variable selection and  maximum likelihood estimation [cluster analysis](https://github.com/mcmahonmc/benchmarking/tree/main) in R using data collected in the first three benchmarking assessments to identify patterns in user characteristics. 

This approach segmented users according to three types: sellers, buyers, and "overlappers," or people who both buy and sell. Overlappers were actually a challenging segment to define through behavioral analytics alone - What time window do we use to identify overlapper behavior? What user actions signal sufficiently differentiate intent by buyer vs. seller?

Using unsupervised methods, I successfully identified overlappers through a combination of behavioral and attitudinal characteristics. While overlappers are more likely to be more engaged on Mercari and contribute higher lifetime value, they also tended to rate Mercari less favorably on ease of use and ease of navigation. This suggests there is opportunity to improve the experience for users with dual roles on our platform, with significant upside for business growth. Future analysis could drill into open-text themes around product suggestions and pain points for this cluster of users. This model may also be applied to predict user type, so as to make more relevant recommendations or tailor marketing communications more clearly to user needs.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/benchmarking/Screenshot 2024-06-24 at 6.00.54 PM.png" B loading="lazy" alt="">
    <img src="/images/projects/benchmarking/Screenshot 2024-06-24 at 5.47.13 PM.png" B loading="lazy" alt="">
    <img src="/images/projects/benchmarking/Screenshot 2024-06-24 at 5.47.28 PM.png" B loading="lazy" alt="">
    <img src="/images/projects/benchmarking/Screenshot 2024-06-24 at 5.48.04 PM.png" B loading="lazy" alt="">
    <img src="/images/projects/benchmarking/Screenshot 2024-06-24 at 6.03.56 PM.png" B loading="lazy" alt="">
    <img src="/images/projects/benchmarking/Screenshot 2024-06-24 at 6.04.06 PM.png" B loading="lazy" alt="">
  </div>
  <em>Benchmarking Survey Cluster Analysis in R</em>
</div>
