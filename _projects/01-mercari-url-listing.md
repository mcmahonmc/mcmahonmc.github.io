---
title: URL Listing
date: 2024-05-01
subtitle: Simplifying Cross-Platform Listing on Mercari
image: '/images/projects/url-listing/header.png'
---
# Streamlined Selling: The Power of Cross-Platform Integration

Mercari wanted to enable experienced sellers to easily list many listings at once. We knew that many experienced sellers cross-post, or use multiple resale platforms simultaneously, to increase their exposure and maximize their chance of making a sale.

An engineer proposed an idea at Go Bold Day, Mercari's bi-annual hackathon, to simplify cross-posting for power sellers by creating an import tool that picks up metadata from other sites and easily populates the Mercari listing form. This idea won the company-wide hackathon and was pursued for development.

# Tripling Daily Listings and Power Seller Growth

URL listing launched in April 2024, catalyzing listing growth on an unprecedented scale at Mercari. 

* __3x__ new daily listings
* __+395k__ new listings in 1 month
* __+1k__ new power sellers in 1 month

# The Research Journey

## Crafting the Research Strategy

Before moving forward with design, I urged our project team to consider our current understanding of our existing Mercari power sellers' unmet needs. At the time, we didn't have a concrete definition of what the term 'power seller' meant, or who might be our target audience for this feature. With these new learnings, we could move forward with design that is in alignment with data rather than assumptions.

I focused initial conversations around these main questions: 
* What are power sellers who sell on Mercari and other platforms' unmet needs?
* What value, if any, do non-Mercari power sellers perceive in this feature? 
* How can we optimize this feature to maximize adoption and listing growth?

## A Strategic Research Roadmap

I developed a sequence of study plans to interrogate our assumptions about power sellers' needs and motivations when seeking a new resale platform or to increase listing exposure.

# Study 1
## Unpacking the Processes and Pain Points of Mercari’s Power Sellers
First, I surveyed power sellers who currently did not use a third-party listing tool to mass-import listings, then follow-up with a handful for more detailed contextual inquiry. 

* How do power sellers who don’t use a third-party tool carry out their listing process? 
* What are their pain points with cross posting and managing listings across platforms?
* At a high level, how do existing Mercari power sellers perceive the usefulness of Import Listing?
* Based on what we learn about the listing process, at what stage in the listing process might it make the most sense to introduce Import Listing?

## Insights from Our First Study
From this study, we gained an understanding of the unique steps and pain points power sellers experience when listing across multiple platforms. They appeared unencumbered by their proceses, were able to list efficiently using mental heuristics and personal templates, and paid special attention to detail when checking their listing.

The most requested feature among power sellers was not an import tool, but the ability to copy listings within a platform. Power sellers were not lured by the import tool because it didn't solve their copy listing problem for their other platforms. This narrowed our perception about who this feature holds value for, limiting the target audience to new Mercari users.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/url-listing/IMG_7033.png" B loading="lazy" alt="Artifact">
    <img src="/images/projects/url-listing/power-sellers-request.png" B loading="lazy" alt="Artifact">
  </div>
  <em>Slide Excerpt from Final Report Deck</em>
</div>

# Study 2
## Putting the Import Tool to the Test

Through UserZoom (now [UserTesting](https://www.usertesting.com/platform/userzoom)), I ran remote, moderated usability testing using static images of the import listing feature with 8 eBay sellers who list at least 30 items each month. Participants were asked to “Think aloud” so the experimenter could collect notes on any issues the participants may have encountered.

While I never consider AI to be a valid standalone substitute for user feedback, I utilized an AI tool, EyeQuant’s Visual Attention Analysis and Design Metrics, to supplement feedback from user testing and aid discussion about opportunities to improve attention, clarity, and excitingness. Since we intended to market this feature to new users, these were important characteristics of the import listing experience to benchmark.

Together, these subjective and objective measures informed opportunities for design improvement.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/url-listing/attention.png" B loading="lazy" alt="">
    <img src="/images/projects/url-listing/excitingness.png" B loading="lazy" alt="">
  </div>
  <em>EyeQuant heatmaps showing areas for visual attention and excitingness</em>
</div>

## Collaborative Insights
After analyzing interview transcripts, I created a FigJam board to show user clips, behavioral observations, and key insights for each step of the import listing process. I hosted a workshop for the project team, where in rounds, designers and product managers individually spent time reviewing a section of the board, jotted down questions, and then met again for discussion. This helped the team immerse themselves in the participants' feedback and generate their own actionable next steps.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/url-listing/share-out-ebay.png" B loading="lazy" alt="Reduct">
  </div>
  <em>Co-Synthesis Workshop FigJam Board Excerpt</em>
</div>

## Critical Discoveries
Initially, we hypothesized that new users would want to be as time efficient as possible, and would find value in completing the sign up process while their listings imported to Mercari. 

Through this research, we found that users were actually suspicious that the sign up step came after the import, and thought that Mercari, or other users, may take advantage of this for malicious intent.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/url-listing/report/013.png" B loading="lazy" alt="">
  </div>
</div>

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/url-listing/report/018.png" B loading="lazy" alt="">
  </div>
</div>

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/url-listing/report/019.png" B loading="lazy" alt="">
  </div>
  <em>Design Recommendations / <a href="/images/projects/url-listing/report/report.pdf" target="_blank">See Full PDF Report</a></em>
</div>

# Study 3
## Live Feedback: Capturing Real-Time User Experiences Post-Launch

URL listing was launched to a select group of Mercari power sellers for beta-testing. I launched a live-interept survey to trigger upon selecting 'Import listing' or viewing 'Ready to List' listings to quickly identify top opportunities for improvement in this new feature.

Because the feature was in beta and event tracking was in development, recruitment for this survey was a challenge. We made do with a sample size of 117, although a larger sample would have been preferred for analysis of open-text questions.

## Post-Launch Learnings
From this survey we learned that users were most frustrated by a lack of troubleshooting guidance and error transparency. When they were unsuccessful in their task, they also didn't know what to do differently.

Second, some listers weren't aware of bulk editing capabilities - many were leaving their listings in their draft form. Using [Sprig Replay](https://docs.sprig.com/docs/replays), I was able to show real user clips of failed attempts at listing imports, which helped drive urgency around this improvement opportunity. This finding was also consistent with earlier research pointing to difficulties finding how to access draft listings as well as analytics showing a significant increase in the number of action-required and ready-to-list draft listings amongst new feature adopters.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/url-listing/daily-draft-items.png" B loading="lazy" alt="Artifact">
  </div>
  <em>Daily Draft Listings / Ready to List Zero State</em>
</div>

# How Research Enhanced the URL Listing Feature

Overall, this research guided the development of the URL listing feature from ideation through launch. Some of the key contributions of this research were:

* Identifying key value propositions and narrowing our target audience
* Improved direct success rates in URL listing imports through clearer guidance, error messages and FAQs, and more intuitive design elements
* Optimizing the new user flow for trust and exploration
* Increasing confidence in import success through visual import progress

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/url-listing/report/021.png" B loading="lazy" alt="">
  </div>
  <em>Import Listing Landing Page</em>
</div>

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/projects/url-listing/report/022.png" B loading="lazy" alt="">
  </div>
  <em>Import Listing In Progress</em>
</div>