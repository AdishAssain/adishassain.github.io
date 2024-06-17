---
layout: post
title: Model Development Via Negativa
date: 2024-06-15
author: Adish
tags: [model validation, documentation, reproducibility, expert elicitation]
---
In model development, we often emphasise positive knowledge—understanding “what something is.” This approach seems intuitive, as knowing what works appears to be the most direct path to improving systems and models. However, the concept of “Via Negativa” suggests that true understanding often comes from identifying and eliminating what doesn’t work.

Applying Via Negativa during model development involves recognising what not to do at various stages. For example, understanding what not to do in model validation is crucial to avoid common pitfalls and ensure the robustness of the current model. Detailed documentation of each step, including when methodologies fail or assumptions prove incorrect, is paramount. This documentation should cover specific techniques tested, data preprocessing steps, algorithmic choices, and validation strategies. Additionally, noting unexpected outcomes or anomalies can provide valuable insights for future analyses.

This approach enhances clarity, reproducibility, and generalisability, without compromising representativeness. In mechanistic disease modelling, for instance, uncertainties about certain factors can be managed by systematically excluding less plausible scenarios through expert elicitation. This process also helps in identifying ineffective or impractical control interventions, further refining the model. 

By focusing on what not to do, we can streamline model development and create more reliable models. This method not only prevents mistakes but also ensures that our models are as close to empirical reality as possible.


>*"The principle that we know what is wrong with more clarity than what is right, and that knowledge grows by subtraction. Also, it is easier to know that something is wrong than to find the fix. Actions that remove are more robust than those that add because addition may have unseen, complicated feedback loops."* - <span style="font-style: italic; font-family: cursive; font-weight: 200;">Antifragile</span>