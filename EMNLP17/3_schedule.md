---
layout: page17
title: Schedule
permalink: /EMNLP17/schedule/
name: 3
---

* Venue: Hovedbanen, CPH conference
* Date: Sep. 07, 2017

<center>
<table style="border-spacing: 15px">
<tr>
<td ><img width="120" src="https://andre-martins.github.io/images/andre_beijing.jpg"></td>
<td ><img width="120" src="http://isabelleaugenstein.github.io/images/isabelle.jpg"></td>
<td ><img width="120" src="http://web.engr.oregonstate.edu/~huanlian/lianghuang-venice-canals.jpg"></td>
<td ><img width="120" src="https://www.microsoft.com/en-us/research/wp-content/uploads/2016/08/avatar_user__1472692894-180x180.jpg"></td>
</tr>
<tr>
<td><center>Andre Martins <br>  Unbabel and Instituto de Telecomunicacoes</center></td>
<td><center>Isabelle Augenstein  <br> University of Copenhagen</center> </td>
<td><center>Liang Huang<br>Oregon State University</center> </td>
<td><center>Scott Yih <br> Microsoft Research</center> </td>
</tr>
</table>
</center>

## Tentative Schedule

|9:00--9:15:    | Welcome  |
|9:15--10:00:    | Invited Talk: Andre Martins  |
|10:00--10:30:   | Contributed Talk: Emma Strubell |
|10:30--11:00:   | Coffee Break |
|11:00--11:45: | Invited Talk: Isabelle Augenstein  |
|11:45--12:15:   | Poster Madness |
|12:15--14:00:   | Lunch|
|14:00--14:45:  | Posters |
|14:45--15:30   | Invited Talk: Liang Huang |
|15:30--16:00:   | Coffee Break |
|16:00--16:45:   | Invited Talk: Scott Yih|
|16:45--17:15:   | Contributed Talk: Iulian Vlad Serban | 
| 17:30:         | Closing |

## [Accepted Papers](http://structuredprediction.github.io/EMNLP17/ac/) 


## Invited Speakers

### Andre Martins (Unbabel and Instituto de Telecomunicacoes)

**title**: Beyond Softmax: Sparsemax, Constrained Softmax, Differentiable Easy-First

**Abstract**:

In the first part of the talk, I will propose sparsemax, a new activation function similar to the traditional softmax, but able to output sparse probabilities. After deriving its properties, I will show how its Jacobian can be efficiently computed, enabling its use in a network trained with backpropagation. Then, I will propose a new smooth and convex loss function which is the sparsemax analogue of the logistic loss, revealing an unexpected connection with the Huber classification loss. I will show promising empirical results in multi-label classification problems and in attention-based neural networks for natural language inference.

In the second part, I will introduce constrained softmax, another activation function that allows imposing upper bound constraints on attention probabilities. Based on this activation, I will introduce a novel neural end-to-end differentiable easy-first decoder that learns to solve sequence tagging tasks in a flexible order. The decoder iteratively updates a "sketch" of the predictions over the sequence. The proposed models compare favourably to BILSTM taggers on three sequence tagging tasks.

This is joint work with Ramon Astudillo and Julia Kreutzer. 

**Bio**: 

André Martins is the Head of Research at Unbabel, a research scientist at Instituto de Telecomunicações, and an invited professor at Instituto Superior Técnico in the University of Lisbon. Previously, he was the Head Research Scientist of Priberam Labs. He received his dual-degree PhD in Language Technologies in 2012 from Carnegie Mellon University and Instituto Superior Técnico. His research interests include natural language processing, machine learning, deep learning, and optimization. He has published 30+ papers with over 1800 citations and h-index of 22 in top-tier conferences and journals (such as JMLR, PAMI, Computational Linguistics, ACL, ICML, and EMNLP), including a best paper award at the Annual Meeting of the Association for Computational Linguistics (ACL) for his work in natural language syntax. His PhD dissertation has been awarded with a SCS Honorable Mention at CMU. He won the Portuguese IBM Scientific Prize in 2012.

### Isabelle Augenstein (University of Copenhagen)

**title**: NLP beyond the sentence level

**Abstract**:

To successfully understand language, models must learn to understand and represent not just individual sentences, but also their context. This becomes evident when addressing tasks such as judging how sequences relate to one another, modelling conversational structures or summarising documents. Despite this, most current NLP work focuses on short sequences. This talk will revisit early as well as current approaches to text representation beyond the sentence level and point out their limitations. It will then examine the question of how structure, both in linguistic form and in terms of the context of a sentence, might help with this.

**Bio**:

Isabelle Augenstein is a a tenure-track assistant professor at the University of Copenhagen, Department of Computer Science, affiliated with the CoAStAL NLP group and work in the general areas of Statistical Natural Language Processing and Machine Learning. Her main research interests are weakly supervised and low-resource learning with applications including information extraction, machine reading and fact checking. Previously she was a postdoctoral research associate at UCL and was awarded a PhD from the University of Sheffield. She has recently co-organised the Deep Structured Prediction workshop at ICML 2017, the WiNLP workshop at ACL 2017 and is one of the organizers of EMNLP 2017.

### Liang Huang (Oregon State University)

### Scott Yih (Microsoft Research)

**Title**: Structured Prediction for Semantic Parsing: A Case Study on Sequential Question Answering
 
**Abstract**:
 
Mapping unstructured text to structured meaning representations, semantic parsing covers a wide variety of problems in the domain of natural language interaction. Common applications include translating human commands to executable programs, as well as question answering when using databases or semi-structured tables as the information source.  Settings of real-world semantic parsing problems, such as the large space of legitimate semantic parses, weak or mixed supervision signals, and complex semantic/syntactic constraints, pose interesting and yet difficult structured prediction challenges.  In this talk, I will give an overview on these technical challenges and present a case study on sequential question answering, answering sequences of simple but inter-related questions using semi-structured tables from Wikipedia. In particular, I will describe our dynamic neural semantic parsing framework trained using a weakly supervised reward-guided search, which effectively leverages the sequential context to outperform state-of-the-art QA systems that are designed to answer highly complex questions. The talk will be concluded with discussion on the open problems and promising directions for future research.
 
Details of the task of sequential question answering and our models can be found in:
1. Iyyer et al. Search-based Neural Structured Learning for Sequential Question Answering. ACL-17.
2. Peng et al. Maximum Margin Reward Networks for Learning from Explicit and Implicit Supervision. EMNLP-17.

**Bio**:

Scott Wen-tau Yih is a Senior Researcher at Microsoft Research AI. His research interests include natural language processing, machine learning and information retrieval. Yih received his Ph.D. in computer science at the University of Illinois at Urbana-Champaign. After joining Microsoft Research, he has worked on email spam filtering, keyword extraction and search & ad relevance. His recent work focuses on continuous representations and neural network models, with applications in knowledge base embedding, semantic parsing and question answering. Yih received the best paper award from CoNLL-2011, an outstanding paper award from ACL-2015 and has served as area chairs (HLT-NAACL-12, ACL-14, EMNLP-16,17), program co-chairs (CEAS-09, CoNLL-14) and action/associated editors (TACL, JAIR) in recent years. He is also a co-presenter for several tutorials on topics including Semantic Role Labeling (NAACL-HLT-06, AAAI-07), Deep Learning for NLP (SLT-14, NAACL-HLT-15, IJCAI-16), Question Answering (NAACL-HLT-16, SIGIR-16) and NLP for Precision Medicine (ACL-17).
