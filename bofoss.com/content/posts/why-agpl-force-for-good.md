+++
title = "Why AGPL is a force for good?"
date = 2025-02-25T00:00:00-07:00
description = "There's a common misconception that free software automatically means copyleft and that open source is inherently permissive. In reality, the AGPL license serves an important purpose."
tags = ["agpl", "licensing", "copyleft", "open-source", "free-software"]
categories = ["technology"]
+++

# Why AGPL is a force for good?

There’s a common misconception that free software automatically means copyleft and that open source is inherently permissive. In reality, these terms represent different philosophies and legal frameworks.

Copyleft licenses, including the AGPL, aren’t punitive — they require that modifications or derivative works remain under the same license, fostering a community-driven ecosystem. For example, Grafana Labs switched from Apache to AGPLv3 in 2021. Most users deploy Grafana unmodified, so the AGPL clause rarely becomes a hurdle, yet it ensures that any enhancements made to the software benefit everyone.


AGPLv3 from GNU— Free as in Freedom
Traditional GPL licenses (coming from GNU) were designed to ensure that modifications to software remained open when the software was redistributed. However, there was a loophole: when software was offered as a service over the web — what we call Software-as-a-Service (SaaS) — there was no obligation to share modifications since the software itself was never “distributed” in the traditional sense. The AGPL was introduced to address this gap. The AGPL extends the copyleft requirements of the GPL by including a “network use” clause. Hence, enforcing the AGPL can be challenging. Legal teams often point to instances like Google’s blanket ban on AGPL code — a decision likely driven by the complexity of ensuring correct license compliance. Even when paired with compatible licenses like GPLv3, AGPL’s requirements can extend to an entire distribution, complicating matters further.

Unmodified AGLP-licensed components
It’s crucial to understand that the AGPL doesn’t force companies to open-source proprietary code used internally or externally by default. If a business develops a proprietary user interface that interacts with an AGPL-licensed backend, such as Loki, there is no obligation to reveal its code.

This is akin to how dynamic linking with GPL software doesn’t require releasing proprietary modifications — only when the modified AGPL software is served directly to customers is the source code disclosure triggered, which brings us to our next point.

Modified AGLP-licensed components
In practice, it’s worth noting that most companies use AGPL components in their unmodified form. If the modifications are used strictly internally, the company isn’t obligated to disclose those changes. However, once the modified software is made accessible to external users (for instance, through a cloud service), the company must release the modified source code.

Case: What happened at Neo4J
In May 2018, Neo4j dropped the AGPL for its Enterprise Edition (EE) and instead combined the AGPLv3 with the Commons Clause. This additional clause prohibited non-paying users from reselling the software or offering competing support services.

The complexities of AGPL enforcement were highlighted in Neo4j, Inc. v. PureThink, LLC, which revolved around the right to add change / modify contractual restrictions on top of AGPL-licensed software. When a licensee removed these restrictions, arguing that AGPLv3 explicitly allowed it, litigation followed, reinforcing the legal uncertainties around AGPL’s enforcement in hybrid licensing models. The licensee argued that under AGPLv3, Section 7, Paragraph 4, licensees are granted the right to remove any “further restrictions” added to the license: “If the program as you received it, or any part of it, contains a notice stating that it is governed by this license along with a term that is a further restriction, you may remove that term.”

It's interesting to note that they choose to use an AGPL license and not a GPL license, which would have allowed them to add additional restrictive clauses easily. However, in 2022, a California court issued a partial summary judgment affirming that a license combining the AGPL with non-open-source restrictions cannot be called “free and open source.” The court also upheld Neo4j’s interpretation that licensors (those licensing the software) could add additional restrictive terms, while licensees (those using the software) could not remove those terms.

Since then, PureThink LLC's founder has appealed to the US Court of Appeals to reconsider the California district court’s decision as this judgement impacts the future of ‘free’ FOSS licenses. This case underscores the challenges with blending copyleft and proprietary licensing models, especially when additional restrictions are imposed on AGPL’s open-access principles. The outcome will likely create a binding precedent that would limit one of the major freedoms that AGPLv3 and other GPL licenses aim to protect — the ability to remove restrictions added to GPL-licensed code.

Latest News: https://www.theregister.com/2025/03/04/free_software_foundation_agplv3/

The guardian of Commercial Open Source Software
Some argue that the AGPL license creates a moat for commercial open source companies by not allowing competition to emerge around them. Competitors who might try to build a business around the modified product can only do so under the AGPL license, preventing the creation of any moat for the competitor. Hence, the application of the AGPL by commercial open source companies is defensive, not progressive.

In my opinion, inherent advantages for the licensee can be beneficial rather than detrimental as they make FOSS license commercially attractive. This helps businesses drive innovation and make money while keeping the end users' interests at heart. It also helps them prevent large cloud providers (like AWS) from profiting off their open-source software without contributing back.

The winners and the losers
Winner — The Community & commercial open source companies

AGPL licenses are designed to ensure that improvements to a codebase remain open and available to the community. When developers build on AGPL software, any modifications made and deployed — especially over a network — must be released under the same license. By mandating that derivative works remain free, the AGPL protects the collective effort of countless contributors. This “pay-it-forward” approach means that every enhancement, bug fix, or new feature becomes accessible to all, fueling rapid innovation and mutual benefit.

Commercial open source companies also benefit from the competitive moat that prevents others from using their work without contributing. While some argue this limits competition, it also strengthens the business model of COSS companies, allowing them to drive innovation and generate revenue while keeping user interests at heart.

The Loser — Cloud Commercial Gatekeepers

The primary impact of the AGPL is on companies like Amazon (AWS), whose cloud services might host popular open-source projects. The AGPL restricts them from offering these projects without complying with its terms. This stance supports the open source community by ensuring fair contribution and preventing free rides on community labor. Consequently, while these companies may have robust infrastructures and significant market power, the AGPL levels the playing field by enforcing a fair contribution policy.

Understanding these nuances is vital for product or engineering managers. Recognizing that the AGPL aims to protect community contributions without stifling internal innovation can help balance legal obligations with business strategy while nurturing a collaborative ecosystem that drives open source innovation.

Further Reading

https://drewdevault.com/2020/07/27/Anti-AGPL-propaganda.html
---

*This article was originally published on [Medium](https://medium.com/bofoss) as part of the BoFOSS publication.* 