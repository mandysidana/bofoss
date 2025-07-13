+++
title = "Business Models supporting FOSS end-of-life"
date = 2025-04-15T00:00:00-07:00
description = "Open source forms the backbone of modern software development. However, this landscape is ever-evolving, and inevitably, projects reach end-of-life."
tags = ["open-source", "business-models", "end-of-life", "sustainability", "maintenance"]
categories = ["business"]
+++

# Business Models supporting FOSS end-of-life

Open source forms the backbone of modern software development. However, this landscape is ever-evolving, and inevitably, projects reach their end-of-life (EOL). This presents both a challenge and an opportunity: how can businesses effectively navigate this EOL maze, and what business models can support them?


My experience at Sonatype provided a crucial perspective on this. We focused on empowering developers to identify secure and reliable replacements for EOL open-source components, leveraging Software Bill of Materials (SBOM). This proactive approach is vital for maintaining software security and stability. Similarly, at Plotly, I witnessed the impact of EOL on popular charting OSS libraries, highlighting the need for strategic planning and support for users facing these transitions.

One key aspect of informing business decisions around EOL framework support lies in understanding the adoption rates of specific package versions. While not perfectly accurate, analyzing download statistics from repositories like Maven Central and GitHub, alongside engagement metrics from platforms like Stack Overflow, can offer valuable insights. A high volume of downloads for a particular version, coupled with active discussions (especially those related to implementation challenges or bug fixes) on Stack Overflow, suggests a significant and potentially dependent user base. This data can act as a strong signal, indicating where investment in EOL support and migration pathways would be most impactful.

End-of-life (EOL) Software Scanning SaaS
These platforms help proactively identify EOL components within a project’s dependencies and suggest secure and up-to-date alternatives, much like the product I managed at Sonatype. This is typically offered as a SaaS solution integrated into the development lifecycle, providing continuous monitoring and alerts. Popular vendors in this space include FOSSA obsolescence management, Aikido.dev, and Tenable.io. These tools often integrate with build pipelines and IDEs, offering developers real-time feedback on their dependencies.

Providing Support Beyond EOL (Never-Ending Support — NES)
Several business models capitalize on the need for EOL support. One approach is offering enhanced support and extended security maintenance for EOL frameworks to organizations that are not yet ready or able to migrate. Vendors such as Herodevs and Tuxcare have established businesses by providing NES (Never-Ending Support) for these open-source frameworks. This typically involves providing critical bug fixes, security patches, and sometimes even limited feature backports beyond the official EOL date, offered as a subscription service. While offering “never-ending” support has challenges regarding resource allocation and the evolving threat landscape, it caters to organizations with complex systems or strict compliance requirements that necessitate prolonged stability.

Providing Migration Services and Tools
Another model focuses on providing migration services and tools. Companies can offer expertise and tooling to help organizations seamlessly transition from EOL frameworks to newer or alternative technologies. This could include automated migration scripts, compatibility assessments, code refactoring services, and expert consulting. These services can significantly reduce the time and cost associated with complex migrations.

Data-Driven Insights and Analytics
Finally, the data-driven insights gleaned from download statistics and community activity can be valuable offerings. Websites like Endoflife.date provide key reports on open-source adoption trends, the prevalence of specific EOL versions, and prediction of upcoming EOL risks based on project activity. This can help organizations make informed decisions about their technology roadmap and proactively plan migrations. This could include identifying emerging EOL risks within their dependency trees based on broader usage patterns.

Navigating the end-of-life of open-source frameworks effectively is crucial for the stability, security, and longevity of software projects. The business models outlined above demonstrate the growing recognition of this need and offer valuable solutions for organizations seeking to manage this ever-evolving landscape.

---

*This article was originally published on [Medium](https://medium.com/bofoss) as part of the BoFOSS publication.* 