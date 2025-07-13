+++
title = "Open Source Copilot Gambit: Microsoft's Two-Pronged Plan to Stifle Competitors"
date = 2025-05-22T00:00:00-07:00
description = "We had some exciting news yesterday about Microsoft's moves in the AI coding space. This post delves into the strategy and understands the implications."
tags = ["microsoft", "copilot", "ai", "open-source", "strategy", "competition"]
categories = ["technology"]
+++

# Open Source Copilot Gambit: Microsoft's Two-Pronged Plan to Stifle Competitors

We had some exciting news yesterday about Microsoft’s moves in the AI coding space. This post delves into the strategy and understands what’s behind these actions. What does it tell us about the fight for developers?

![](https://miro.medium.com/v2/resize:fit:1400/1*V88iPFrz2OVVpFAKD4p3qg.png)

Microsoft is open-sourcing the client-side component of the [GitHub co-pilot](https://code.visualstudio.com/blogs/2025/05/19/openSourceAIEditor) chat extension for VS Code, and it is being done under the MIT license, which is as permissive as open-source licenses get. This means that anyone can use it, modify it, or make changes based on the sources provided. This allows you to see how Copilot chat works within VS Code, including how it builds prompts, displays suggestions, and all other user-facing features. The key point here is that the actual AI models used in the backend remain proprietary. So while the Copilot AI model is still owned and controlled by Microsoft, opening up the client means that developers or even large companies could potentially point the Copilot interface at their own models, whether internal or other open-source LLMs, which directly addresses some significant concerns about vendor lock-in and data privacy.

Besides driving adoption for GitHub Copilot, the open-source approach would allow AI to feel more native to VS Code itself, enabling it to catch up with AI-first editors like Cursor, which are perceived as offering a significantly better AI experience. It’s also worthwhile to note that while OpenAI and Microsoft have remained partners, OpenAI recently [launched](https://openai.com/index/introducing-codex/) a preview of its own cloud-based software engineering agent, signalling a move away from Microsoft.

Amidst this rising competition, something significant happened last month — [Microsoft removed VSCode extensions from code forks](https://www.theregister.com/2025/04/24/microsoft_vs_code_subtracts_cc_extension/). Microsoft started enforcing certain license terms, blocking specific key Microsoft VS Code extensions from running in VS Code forks like [VSCodium](https://vscodium.com/) and [Cursor](https://github.com/getcursor/cursor/issues/2976). Please note that the license terms themselves aren’t new; they have been in place since 2020. What’s new is the start of enforcing a five-year license term that restricts other IDE forks from using extensions shared via the VS Code Marketplace. One example is the C++ extension — It provides essential features, such as intelligent code completion and debugging tools, which are crucial for C++ developers. Blocking that extension for a tool like Cursor, which is built on VS Code’s open-source fork, directly broke developer workflows 😱.

This certainly appears to be a move aimed at hindering competition, as confirmed by Cursor’s CEO, Michael Trull, who mentioned that they will now be moving to open-source alternatives. This hasn’t gone unnoticed in the industry — Developers are calling it unfair competition. There’s even some talk of an FTC complaint being filed. The allegation is that Microsoft is blocking rivals to keep users locked into its ecosystem, which wouldn’t be the first time.

What is immediately striking when examining this is that Microsoft appears to be holding almost contradictory positions at first glance. Open-sourcing the client-side of VS Code Autopilot is a move towards open source and fostering competition. However, they then use licensing to restrict those very competitors, such as Cursor, from using essential extensions built on the same underlying open-source VS Code platform. This is a strategy with two distinct parts: proactively opening up your offering to attract users who would have otherwise chosen open-source alternatives, while also defensively limiting rivals who are building on the same open-source base.

What appears to be an upholding of OSS principles is, in reality, when combined with defensive restrictions, a proactive move to maintain leadership position, manage competition, and the developer narrative. The tension between open platforms and competitive business realities in the AI era is only going to intensify from here.


---

*This article was originally published on [Medium](https://medium.com/bofoss) as part of the BoFOSS publication.* 