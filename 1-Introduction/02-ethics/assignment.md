## Write A Data Ethics Case Study

## Instructions

You've learned about various [Data Ethics Challenges](README.md#2-ethics-challenges) and seen some examples of [Case Studies](README.md#3-case-studies) reflecting data ethics challenges in real-world contexts.

In this assignment, you'll write your own case study reflecting a data ethics challenge from your own experience, or from a relevant real-world context you are familiar with. Just follow these steps:

1. `Pick a Data Ethics Challenge`. Look at [the lesson examples](README.md#2-ethics-challenges) or explore online examples like [the Deon Checklist](https://deon.drivendata.org/examples/) to get inspiration.

2. `Describe a Real World Example`. Think about a situation you have heard of (headlines, research study etc.) or experienced (local community), where this specific challenge occurred. Think about the data ethics questions related to the challenge - and discuss the potential harms or unintended consequences that arise because of this issue. Bonus points: think about potential solutions or processes that may be applied here to help eliminate or mitigate the adverse impact of this challenge.

3. `Provide a Related Resources list`. Share one or more resources (links to an article, a personal blog post or image, online research paper etc.) to prove this was a real-world occurrence. Bonus points: share resources that also showcase the potential harms & consequences from the incident, or highlight positive steps taken to prevent its recurrence.


--

Personal data for B2C customers was held in a company system for the purposes of fulfilling orders and sending marketing information from the company to those customers.

The company then offered similar marketing facilities to other companies. It received those companies' B2C customer details but unfortunately stored them in the same place without adequate controls to ensure that they were properly segregated.

Staff in the company marketing department sent out marketing mailings to people listed in the system - both their own customers and the customers of the other companies - but only sending information with the company's own branding, contact details, etc. This meant that customers of the other companies were treated as if they were the company's own customers. Not surprisingly, this upset both the B2C customers and the other companies. The former complained of data privacy breaches and the latter complained that the company was trying to steal their customers. Both complaints were reasonable judgements even if they had not been the intention of the marketing department.

The situation arose because there was an assumption that anyone exporting data for marketing purposes would understand that there were both internal and external customers in the system and would ensure that they only chose the appropriate ones. In practice this understanding was insufficient and the system itself didn't do anything to prevent the export of a mixture.

Steps were subsequently taken to address the issue and to put stronger controls in place to ensure the problem didn't happen again. These were more onerous than they would have needed to be if the issue had been properly handled in the first place. Depsite this, the trust that had been lost was never fully regained.

Controls that were applied included extra fields to indicate the ownership of the data and controls on exporting to ensure that a dataset couldn't include both internally and externally-owned customers together. Further considerations included a completely independent copy of the entire system to handle the externally-owned data.

I have no resources to link to as the company is no longer trading and it happened many years ago. However, I was working in the IT department at the time and have direct experience of the event and (especially) the resulting work.


## Rubric

Exemplary | Adequate | Needs Improvement
--- | --- | -- |
One or more data ethics challenges are identified. <br/> <br/> The case study clearly describes a real-world incident reflecting that challenge, and highlights undesirable consequences or harms it caused. <br/><br/> There is at least one linked resource to prove this occurred. | One data ethics challenge is identified. <br/><br/> At least one relevant harm or consequence is discussed briefly. <br/><br/> However discussion is limited or lacks proof of real-world occurence. | A data challenge is identified. <br/><br/> However the description or resources do not adequately reflect the challenge or prove it's real-world occurence. |
