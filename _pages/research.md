---
layout: page
title: Research
permalink: /research/
image: 
---

My broad goal is to develop robots that people can depend on. My research focuses on **trustworthy embodied AI**, guided by a question:

> How can we enable reliable, fluent, and safe robots?

By **reliable**, I mean robots that work consistently. A robot that succeeds today but struggles with the same task tomorrow is difficult to depend on. It should adapt when conditions change and recognize when a task is beyond its capabilities. By **fluent**, I mean robots that are easy to work with—you should not need a degree in robotics or computer science to get a robot to help you. And by **safe**, I mean robots that can provide that help without causing harm to you or the people around you.

Together with my team at [CLeAR](https://clear-nus.github.io/), we work across the full pipeline: from mathematical foundations and learning algorithms to perception, planning, and control on physical robots. We build systems and test them in real-world settings, using what we learn to refine our methods and identify new research questions.

## From Human Trust to Trustworthy Robots

Imagine asking a robot to bring you a cup of hot coffee. Can it carry the cup without spilling it? Does it understand where you want it placed? And would you trust it to do so? How about handing that cup to your grandmother or your child?

These questions connect the robot's capabilities with our beliefs about those capabilities. We have studied [how human trust transfers across tasks](https://clear-nus.github.io/blog/multi-task-trust) and how robots can [reason about trust when planning their actions](https://arxiv.org/abs/1801.04099). We have also explored how modeling a person's perspective can help a robot [communicate useful information](https://clear-nus.github.io/blog/mirror). This work asks when people rely on robots, and how we can support effective collaboration.

In recent years, much of our work has focused on developing the capabilities and methods that make robots more dependable. How can we understand their failures? How can we improve their behavior? And how do we establish that these improvements carry over to the physical world?

## Learning and Acting Reliably

Recent generative models can produce impressive robot behavior, but their failures raise fundamental questions. In our work on [action hallucination](https://clear-nus.github.io/blog/action-hallucination), we examine why generative robot policies can produce physically infeasible actions. Our analysis identifies limitations arising from the structure of these models, the precision required by a task, and the length of a plan. Understanding these limitations helps us reason about how to build better systems.

I'm particularly interested in methods that build on what a robot already knows:

> Don't throw away what you know, but don't be constrained by it.

This idea runs through our work on refining learned behavior and adapting it to new requirements. For example, [LTLDoG](https://clear-nus.github.io/blog/ltldog) guides diffusion-based planning with constraints such as avoiding obstacles and visiting locations in a specified order. Our [guided streaming policies](https://clear-nus.github.io/blog/guided-ssip) connect a mathematical formulation of guidance with reactive control, allowing robots to adjust their actions as conditions change. We also study how robots can reuse skills: [SkillVLA](https://clear-nus.github.io/blog/skillvla) enables a robot to combine learned single-arm skills into new two-arm behaviors.

Dependability also requires knowing when a model's output should not be used. Our work on [selective classification](https://arxiv.org/abs/2505.15008) develops principled methods for abstaining from uncertain predictions, including when the inputs differ from those seen during training.

## Grounding Intelligence in Physical Interaction

To help us with physical tasks, robots need to sense and respond to the world around them. Touch gives a robot access to information that can be difficult to obtain from vision alone: material properties such as texture and stiffness, contact forces, and the vibrations produced as objects interact. Is an object soft or rigid? How firmly is the robot holding it? Is it beginning to slip? This information helps a robot understand both what it is handling and how the interaction is unfolding.

My interest in robot touch goes back to my PhD, when I developed methods for [online tactile classification](https://doi.org/10.1109/IROS.2012.6385992), enabling the iCub robot to learn to recognize objects by touch as new data arrived. Our later work on [extended tactile perception](https://clear-nus.github.io/blog/extsense) enables robots to sense contact through tools and objects they hold by interpreting vibrations at their fingers.

More recently, we have been exploring how tactile sensing can complement robot foundation models. [Octopi](https://clear-nus.github.io/blog/octopi) combines tactile perception with vision-language models to reason about physical object properties. [VLA-Touch](https://clear-nus.github.io/blog/vla-touch) uses tactile feedback for both task planning and the refinement of physical actions. Our [Heterogeneous Tactile Transformer](https://arxiv.org/abs/2606.29948) learns representations across different tactile sensors, with the aim of making tactile knowledge more transferable across tasks and hardware.

These projects connect physical understanding with action. Returning to the cup handover, a robot needs to account for the cup's material, the forces it applies, and the other person's grasp. Learning to use this information is part of making physical interactions more reliable, fluent, and safe.

## From Theory to Systems in the Real World

Does a method still work when we take the robot outside the lab? What happens when the terrain changes, the sensors are noisy, or people behave differently from what we expected?

Answering these questions requires building and evaluating complete systems. Our [GeNIE navigation system](https://clear-nus.github.io/blog/genie) combines terrain understanding with planning and was evaluated across six countries in the Earth Rover Challenge at ICRA 2025. It took first place and completed the competition without human intervention. More recently, CLeAR won the [REAL-I Embodied AI Challenge at ICRA 2026](https://clear-nus.github.io/blog/real-i-champion). Our [report on lessons from the challenge](https://arxiv.org/abs/2609.13679) examines how data quality, adaptation, evaluation, and deployment affect robot performance.

Working in the real world also means working around people. Through projects such as [ACME](https://arxiv.org/abs/2607.21964), we study social navigation across different countries and robot embodiments. These efforts help us understand the range of situations that our methods need to handle.

This is what I mean by working across the full pipeline. Mathematical analysis helps us understand a problem, algorithms give us ways to address it, and experiments with robots and people tell us what we have missed.

For more on our work, visit the [CLeAR publications page](https://clear-nus.github.io/publications/) and [research blog](https://clear-nus.github.io/blog), or see my [Google Scholar profile](https://scholar.google.com/citations?user=lkgd1BsAAAAJ&hl=en).

### Research Awards

| Year      | Award | Comment |
|----------- | ----------- | ------ |
| 2023      | R:SS Early Career Spotlight Award | Robotics: Science and Systems Conference | 
| 2022      | Best of IEEE Transactions on Affective Computing (T-AFFC) 2021 Award  | [Applying Probabilistic Programming to Affective Computing](https://arxiv.org/abs/1903.06445){:target="_blank"} |
| 2021      | IEEE/RSJ IROS Best Paper Award       | Extended Tactile Perception: Vibration Sensing through Tools and Grasped Objects |
| 2018   | RSS Best Paper Award Finalist       | [The Transfer of Human Trust in Robot Capabilities across Tasks](https://clear-nus.github.io/blog/multi-task-trust){:target="_blank"} |
| 2018   | ACM/IEEE HRI Best Paper Award Finalist       | [Planning with Trust for Human Robot Collaboration](https://arxiv.org/abs/1801.04099){:target="_blank"} |
| 2018   | ACM RecSys Best Long Paper Award Runner-up    | [Generation Meets Recommendation: Proposing Novel Items for Groups of Users](https://arxiv.org/abs/1808.01199){:target="_blank"} |
| 2014-2016   | SMART Postdoctoral Scholar Fellowship Award    |  Singapore-MIT Alliance for Research and Technology |
| 2012-2013 | Design London Fellow | Imperial-RCA Fellowships  |
| 2012 | James Dyson National Award Finalist (UK) |  [Assistive Robotic Transport for Youngsters (ARTY)](https://www.technologyreview.com/2012/09/28/183560/a-smart-safe-wheelchair-for-kids-who-cant-walk/) |
| 2012 | IEEE/RSJ IROS Best Cognitive Robotics Paper Finalist | [Online Spatio-Temporal Gaussian Process Experts with Application to Tactile Classification](https://spiral.imperial.ac.uk/bitstream/10044/1/12658/4/iros2012.pdf){:target="_blank"} |
| 2009-2013 | Khazanah Global Scholarship | Khazanah Foundation Malaysia |
| 2000-2004 | Regents Scholarship | University of California, Davis |
