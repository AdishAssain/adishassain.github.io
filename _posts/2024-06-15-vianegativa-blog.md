---
layout: post
title: Model Development Via Negativa
date: 2024-06-15
author: Adish
---
Often we focus on positive knowledge, or "what something is". This approach is intuitive; after all, knowing what works seems like the most direct path to improving systems and models. "Via negativa" suggests that true understanding often comes not from affirming what we know, but from eliminating what we don't need or what doesn't work.

During the model development phase, the concept of Via Negativa can be applied at various stages. For example, understanding what not to do in model validation is crucial to avoid common pitfalls and ensure the robustness of the current model. Documenting each step of this process, including instances where methodologies didn't yield expected results or where assumptions proved incorrect, becomes paramount.This documentation should detail the specific techniques tested, data preprocessing steps, algorithmic choices, and validation strategies employed. It should also include any unexpected outcomes or anomalies encountered, providing a rich source of insights for future analyses.

This approach also promotes maximizing clarity, tractability, reproducibility, and generalisability, without sacrificing representativeness—ensuring that the model closely matches empirical reality. For example, in mechanistic disease modeling, when uncertainties arise regarding certain factors, it becomes crucial to narrow down possibilities by systematically excluding less plausible scenarios through expert elicitation. This process also aids in eliminating scenarios where specific control interventions prove ineffective or impractical.


>*"The principle that we know what is wrong with more clarity than what is right, and that knowledge grows by subtraction. Also, it is easier to know that something is wrong than to find the fix. Actions that remove are more robust than those that add because addition may have unseen, complicated feedback loops."* - <span style="font-style: italic; font-family: cursive; font-weight: 200;">Antifragile</span>