# Contributor Experience Special Interest Group Charter

This charter adheres to the conventions described in the [Spinnaker Charter README] and uses the Roles and Organization Management outlined in [sig-governance].

## Scope

The [Contributor Experience Special Interest Group] (SIG) is responsible for improving the experience of those who upstream contribute to the Spinnaker project. We do this by creating, and maintaining programs and processes that promote community health and reduce project friction while retiring those programs and processes that don't. Being conscientious of our contributor base is critical to scaling the project, growing the ecosystem, and helping the project succeed.

We do this by listening - whether it’s through our roadshows to SIG meetings, surveys, data, or [GitHub issues], we take in the feedback and turn it into our [project list]. We build a welcoming and inclusive community of contributors by giving them places to be heard and productive.

### In scope

#### Code, Binaries and Services

- Establish policies, standards, and procedures for the use, [moderation], and management of all public platforms officially used by the project, including but not limited to:
  - [GitHub Management]
  - [Mailing lists] / Google groups for the project as a whole (eg: <need community mailing list>@googlegroups.com) and for individual sigs and working groups where the Chairs have provided us ownership
  - [Slack]
  - [/spinnaker] YouTube channel
  - [Zoom]
- Work with other SIGs and interested parties in the project to execute GitHub tasks where required, see [GitHub Management] for more detail
- Own and execute events that are targeted to the Spinnaker contributor community, including:
  - The weekly (or monthly) [Spinnaker Community meeting]
  - [Contributor Summit(s)]
  - [Steering Committee elections] (though we do not own policy creation, see 'out of scope' below)
  - Retrospective moderation for other SIGs upon request
  - Other events, like other SIG face to face events, upon request and consideration
- Strategize, build, and execute on scalable [mentoring programs] for all contributor levels. These may include:
  - [Google Summer of Code]
  - [Outreachy]
  - [Meet Our Contributors]
  - [Group Mentoring - WIP]
  - [The 1:1 Hour - WIP]
 - [Project Office Hours]
  - Speed Mentoring sessions at selected Spinnaker/CloundNative/CDFCon's
- Help onboard new and current contributors into the culture, workflow, and CI of our contributor experience through the [contributor guide], other related documentation, [contributor summits], and programs tailored to onboarding.
- Perform issue triage on and maintain the [spinnaker/community] repository.  
- Help SIGs with being as transparent and open as possible through creating best practices, guidelines, and general administration of YouTube, Zoom, and our mailing lists where applicable
- Assist SIGs/WG Chairs and Technical Leads with organizational management operations as laid out in the [sig-governance] doc
- Distribute contributor related news on various Spinnaker channels, including Continous Delivery Foundation ([CDF]) for posting blogs, social media, and other platforms as needed.
- Establish and share metrics to measure project health, community health, and general trends, including:
  - ongoing work with the CDF to improve [DevStats]
  - the contributor experience survey(s)
  - engagement on project platforms that we manage
- Research other OSS projects and consult with their leaders about contributor experience topics to make sure we are always delivering value to our contributors

#### Cross-cutting and Externally Facing Processes

We cross-cut all SIGs and working groups to deliver the following processes:

- Deploying Changes:
  When implementing policy changes we strive to balance responding quickly to the needs of the community and ensuring a disruption-free experience for project contributors. As such, the amount of notice we provide and the amount of consensus we seek is driven by our estimation of risk. We don't measure risk objectively at this time, but estimate it based on these parameters:
  - Low-risk changes impact a small number (<4) of SIGs, working groups, or repositories, do not break existing contributor workflows, and are easy to roll back. When implementing low-risk changes we:
    - Socialize on <community mailing list>@googlegroups.com and our weekly update calls
    - We will go to each lead, their mailing lists, slack channel, and/or their update meetings and ask for feedback and a [lazy consensus] process. We will follow up with a post to [<need to figure out what the main mailing list is>@]googlegroups.com mailing list
  - High-risk changes impact a large number (>4) of SIGs, working group, or repositories, break existing contributor workflows and are not easy to roll back. When implementing high-risk changes we:
    - Socialize on <we will need community mailing list> and our weekly update calls
    - Seek [lazy consensus] with a time box of at least 72 business hours with a GitHub issue link (or proposal if not applicable) to the following mailing lists:
        - [<mailinglist>@]googlegroups.com
        - <sig lead mailing list>@googlegroups.com
        - [<need to figure out what the main mailing list is>@]googlegroups.com with the GitHub issue link including the subject [NOTICE]: $announcement
        - We will also announce it at the weekly Spinnaker Community Meeting on <we will need to decide on a day>
- Depending on how wide of an ecosystem change this is, we may also slack, blog, tweet, and use other channels to get the word out.
- Our standard time box is 72 business hours; however, there may be situations where we need to act quickly but the time period will always be clear and upfront.
- Encourage automation to improve productivity for contributors where it makes sense and consults with SIG Testing if automation is covering GitHub workflows.

If we need funding for any reason, we approach [CDF].
CDF in many of the noted cases above contributes funding to our platforms, processes, and/or programs. They do not play a day-to-day operations role and have bestowed that to our community to run as we see fit. Since they do fund some of our initiatives, this means that they hold owner account privileges on certain platforms like Zoom and Slack. In these cases, such as Slack, there is at least two Contributor Experience [communication] subproject OWNERs listed as admins.

### Out of scope

- Code for the testing and CI infrastructure - that’s SIG Testing
- [spinnaker/community]  ownership of folders for RFCs and Design Proposals. Members are to follow those folder’s owner’s files and SIG leadership for the specific issue/PR in question.
- User community management. We hold office hours because contributors are a large portion of the volunteers that run that program.
- The contributor experience for repositories not included in the Spinnaker associated repositories lists found in the [GitHub Management] subproject README.
- Steering committee election policy updates and maintenance.
- We do not create SIGs/working group but can assist in the various community management needs of their micro-communities that would kick off their formation and keep them going.
- We are not the [code of conduct committee] and therefore do not control incident management reporting or decisions; however, our moderation guidelines allow us to act swiftly if there is a clear violation of terms of either our code of conduct or one of the terms of our supported platform of service. If there is an action that the committee needs to take that involves one of these platforms (example: the removal of someone from GitHub), we will carry that out if none of the committee members have access.
- Communication platforms that are out of our scope for maintenance and support but we may still have some influence:
    - [r/spinnaker]
    - [@spinnaker] twitter account

## Roles and Organization Management

This sig adheres to the Roles and Organization Management outlined in [sig-governance]
and opts-in to updates and modifications to [sig-governance].


### Additional responsibilities of Chairs

Chairs SHOULD plan at least one face to face Contributor Experience meeting per year

### Additional responsibilities of Tech Leads

Ensuring that technical changes from subprojects follow the process change communication guidelines listed above.

### Deviations from sig-governance
Six months after this charter is first ratified, it MUST be reviewed and re-approved by the SIG in order to evaluate the assumptions made in its initial drafting.

### Subproject Creation
Chairs and Technical Leads

[sig-governance]: 
