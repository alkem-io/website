---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 1

# Section title
title: Alkemio security

# Section subtitle
subtitle: 


# Section design
design:
  # Use a 1-column layout
  columns: "1"
  # Use a dark navy background with light text.
  #background:
  #  color: 'navy'
  #  text_color_light: true
---
## Reporting a Vulnerability - Private Disclosure Process
Security is of the highest importance and all security vulnerabilities or suspected security vulnerabilities should be reported to Alkemio privately, to minimize attacks against current users of Alkemio before they are fixed. Vulnerabilities will be investigated and patched on the next patch (or minor) release as soon as possible. This information could be kept entirely internal to the project.  

If you know of a publicly disclosed security vulnerability for Alkemio, please **IMMEDIATELY** contact security@alkem.io to inform the Alkemio Security Team.
 
**IMPORTANT: Do not file public issues on GitHub for security vulnerabilities**

To report a vulnerability or a security-related issue, please email the private address security@alkem.io with the details of the vulnerability. The email will be fielded by the Alkemio Security Team, which is made up of Alkemio maintainers who have committer and release permissions. Emails will be addressed within 5 business days, including a detailed plan to investigate the issue and any potential workarounds to perform in the meantime. Do not report non-security-impacting bugs through this channel. 

### Proposed Email Content
Provide a descriptive subject line and in the body of the email include the following information:
* Basic identity information, such as your name and your affiliation or company.
* Detailed steps to reproduce the vulnerability  (POC scripts, screenshots, and compressed packet captures are all helpful to us).
* Description of the effects of the vulnerability on Alkemio and the related hardware and software configurations, so that the Alkemio Security Team can reproduce it.
* How the vulnerability affects Alkemio usage and an estimation of the attack surface, if there is one.
* List other projects or dependencies that were used in conjunction with Alkemio to produce the vulnerability.
 
## When to report a vulnerability
* When you think Alkemio has a potential security vulnerability.
* When you suspect a potential vulnerability but you are unsure that it impacts Alkemio.
* When you know of or suspect a potential vulnerability on another project that is used by Alkemio.

## Do's:

- Report the vulnerability as quickly as is reasonably possible, to minimise the risk of hostile actors finding it and taking advantage of  it.
- Report in a manner that safeguards the confidentiality of the report so that others do not gain access to the information.
- Provide sufficient information to reproduce the problem, so we will be able to resolve it. See also [Proposed Email Content](#proposed-email-content)
- Use the label 'informational' in case of a code review or other advice not linked to a specific category.

## Don'ts:

- Reveal the vulnerability or problem to others until it is resolved.
- Utilise a vulnerability further than necessary to establish its existence.
- Copy, modify or delete data on the system. An alternative for doing so is making a directory listing of the system.
- Make changes to the system.
- Repeatedly gain access to the system or sharing access with others.
- Use brute force attacks, attacks on physical security, social  engineering, distributed denial of service, spam or applications of  third parties to gain access to the system.
- Do NOT file a public issue on Github

## What we promise:

- We will respond to your report within 5 business days with our evaluation of the report and an expected resolution date.
- If you have followed the instructions above, we will not take any legal action against you concerning the report.
- We will not pass on your personal details to third parties without  your permission, unless it is necessary to comply with a legal obligation. Reporting under a pseudonym or anonymous is possible.
- We will keep you informed of the progress towards resolving the problem.
- In the public information concerning the reported problem, we will give your name as the discoverer of the problem (unless you desire otherwise).

We strive to resolve all problems as quickly as possible, and we  would like to play an active role in the ultimate publication on the  problem after it is resolved.

This Responsible Disclosure policy is based on an example written by [Harbor](https://goharbor.io/) and the [Responsible Disclosure Guideline of the NCSC](https://english.ncsc.nl/publications/publications/2019/juni/01/coordinated-vulnerability-disclosure-the-guideline).

