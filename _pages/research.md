---
layout: page
title: Research
permalink: /research/
image: 
---

<!--I’m an Assistant Professor at the [Dept. of Computer Science](https://comp.nus.edu.sg){:target="_blank"}, [National University of Singapore](https://www.nus.edu.sg){:target="_blank"} (NUS), where I direct the [Collaborative, Learning, and Adaptive Robots (CLeAR)](https://clear-nus.github.io/trust){:target="_blank"} Lab. -->

My broad goal is to improve people's lives through embodied AI.   

> Specifically, how can we create robots that fluently collaborate with us to solve problems? 

My general approach is to first ask questions about what enables successful collaboration. I often to look to biological organisms, such as humans, for inspiration and answers. What are the fundamental factors that enable people to come together to form families, build cities, and send people to space? What is missing when collaboration fails? 

We then formalize our ideas mathematically and develop new solutions using tools from computer science, typically [machine learning](https://clear-nus.github.io/learn). I'm particularly fond of data-efficient [deep generative and latent state-space models](https://clear-nus.github.io/generate){:target="_blank"} that enable robots to have imagination and simulate possible interactions. Finally,  we run rigorous experiments (typically with people) to gain inspiration and validate that our methods actually work. We have been fortunate to receive recognition for our work on these topics in the form of best paper nominations and press mentions.  

## Key Problems: What's Missing?

I'm particularly interested in assistive settings where the robot is helping a person with a particular task. During my graduate studies, I built [smart wheelchairs for children with disabilities](https://www.technologyreview.com/2012/09/28/183560/a-smart-safe-wheelchair-for-kids-who-cant-walk/){:target="_blank"} and more recently, I've been exploring how robots can assist the elderly. 

<img align="right" style="padding: 20px 15px 0px 10px;" width="400" src="/images/nurse_wound_small.jpg">
This image of a nurse helping to clean a patient's wound summarizes the challenges I seek to address. How can we enable robots to assist in such a task? And equally important, can we assure the  human patient so that they would cooperate with the robot and not refuse assistance (if the robot is indeed capable of helping)? The answers to these questions reveal important clues about what is missing in today's robots. I believe two of the most crucial pieces are:
- **Touch Intelligence**: To help appropriately, the robot needs to make sense of the tactile sensations it receives to avoid causing hurt or harm to the patient. Can the robot learn to apply the right amount of pressure to clean the wound, but not cause pain? Compared to vision, the sense of touch remains underdeveloped in robots. 
- **Trust in the robot**: Imagine if you cut your hand; would you allow a robot to clean your wound? Why or why not? I would argue your *trust* in the robot plays an important role in your decision. In addition to being *trustworthy*, the robot needs to understand when and how humans trust. 

Most of my work in the past few years has centered on these two topics, along with general robot learning. Together with my team at [CLeAR](https://clear-nus.github.io){:target="_blank"}, we have made important strides in giving robots a [sense of touch](https://clear-nus.github.io/tactile){:target="_blank"} and a [sense of trust](https://clear-nus.github.io/trust){:target="_blank"}. One key problem we've had to overcome is the lack of data in these settings; this is a fundamental problem in interactive, embodied AI.  

## Technical Approach: Data-Efficient Machine Learning

> Don't throw away what you know, but don't be constrained by it.

The *key idea* underlying many of our methods is to leverage existing knowledge, yet remain adaptable given new data. We've developed a body of work in **refinement** methods, which have been applied to [imitation learning](https://arxiv.org/abs/2402.16075), [trustworthy image generation](https://clear-nus.github.io/blog/sa), [human-AI communication](https://clear-nus.github.io/blog/mirror) and [robot grasping](https://clear-nus.github.io/blog/grace). These methods feature fast adaptation using prior knowledge encoded as models (e.g., existing robot behaviors/policies, foundation models). We've also studied the effectiveness of context-based adaptation using large foundation models, e.g., for [goal understanding from natural language](https://clear-nus.github.io/blog/llmpddl) and for [human and trust modeling](https://clear-nus.github.io/blog/llm-humanmodel).


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

<!-- - *Best Paper Award*, Extended Tactile Perception: Vibration Sensing through Tools and Grasped Objects, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2021. 
- *Best Paper Award Finalist*, [The Transfer of Human Trust in Robot Capabilities across Tasks](https://clear-nus.github.io/blog/multi-task-trust){:target="_blank"}, Robotics Science and Systems (RSS), 2018. 
- *Best Paper Award Finalist*, [Planning with Trust for Human Robot Collaboration](https://arxiv.org/abs/1801.04099){:target="_blank"}, ACM/IEEE Human Robot Interaction (HRI), 2018.
- *Best Long Paper Award Runner-up*, [Generation Meets Recommendation: Proposing Novel Items for Groups of Users](https://arxiv.org/abs/1808.01199){:target="_blank"}, ACM Recommender Systems (RecSys), 2018.
- *SMART Postdoctoral Scholar Fellowship Award*, Singapore-MIT Alliance, 2014
- *Best Cognitive Robotics Paper Finalist*, [Online Spatio-Temporal Gaussian Process Experts with Application to Tactile Classification](https://spiral.imperial.ac.uk/bitstream/10044/1/12658/4/iros2012.pdf){:target="_blank"}, IEEE/RSJ Intelligent Robots and Systems (IROS), 2012. 
- *Design London Fellow*, 2012.
- *James Dyson National Award Finalist (UK)*, 2012.
- *Khazanah Global Scholarship*, 2009-2013.
- *Regents Scholarship*, University of California, 2000-2004. -->




