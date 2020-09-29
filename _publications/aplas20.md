---
title: "Parameterized Synthesis with Safety Properties"
collection: publications
permalink: /publication/aplas20
excerpt: ''
date: 2020-12-01
venue: 'The 18th Asian Symposium on Programming Languages and Systems (APLAS)'
paperurl: 'http://valvestate.github.io/files/aplas20.pdf'
---
Parameterized synthesis offers a solution to the problem of constructing correct and verified controllers for parameterized systems. Such systems occur naturally in practice (e.g., in the form of distributed protocols where the amount of processes is often unknown at design time and the protocol must work regardless of the number of processes). In this paper, we present a novel learning based approach to the synthesis of reactive controllers for parameterized systems from safety specifications. We use the framework of regular model checking to model the synthesis problem as an infinite-duration two-player game and show how one can utilize Angluin's well-known L\* algorithm to learn correct-by-design controllers. This approach results in a synthesis procedure that is conceptually simpler than existing synthesis methods with a completeness guarantee, whenever a winning strategy can be expressed by a regular set. We have implemented our algorithm in a tool called L\*-PSynth and have demonstrated its performance on a range of benchmarks, including robotic motion planning and distributed protocols. Despite the simplicity of L\*-PSynth it competes well against (and in many cases even outperforms) the state-of-the-art tools for synthesizing parameterized systems.

[Download paper here](http://valvestate.github.io/files/aplas20.pdf)
