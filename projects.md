---
layout: page
title: Projects
description: Details about course projects.
mathjax: true
---

# Algorithm Design Projects

Throughout the semester, you will work in teams to tackle in-depth algorithm design challenges. 

Each project spans a **four-week cycle**, designed to take you through the complete lifecycle of algorithm design, from theoretical conception to empirical validation and technical communication. 

The first two deliverables are graded based on **effort and completion**. The final two deliverables, which represent the polished outcome of your work, are graded on **correctness**, **depth of analysis**, and **effectiveness of communication**.

Your team will collaborate throughout the project cycle, contributing to each deliverable and participating in discussions to refine your approach. Each team member should lead at least one deliverable for the project. On each of your submissions, note the contributions of each team member. 

[Project 1 Topics](https://docs.google.com/document/d/1pTKetb_EuZRGcA39BaDLchRSRRrMXAxWEI9UJK41JOU/edit?usp=sharing)

You should maintain your project files and documentation in a GitHub repository. Make sure to commit regularly and provide clear commit messages to track your progress effectively. On the due date for each deliverable, I will review your repository to assess your progress and provide feedback.

---

## Deliverable 1: Planning and Analysis (Week 1)
**Focus:** Theoretical Foundation  
**Grading:** Effort & Completion

Before writing any code, your team must formalize the problem and design a theoretical solution. 

**Tasks:**
1. **Problem Formulation:** Break down the project prompt. Clearly define the input parameters, expected outputs, and constraints.
2. **Algorithmic Strategy:** Select an appropriate design paradigm (e.g., divide-and-conquer, dynamic programming, greedy). Write detailed pseudocode for your proposed solution.
3. **Baseline Solutions:** Design a simple algorithm that solves the problem to serve as a reference point for performance comparisons.
4. **Complexity Analysis:** Establish the theoretical running time bounds ($O$, $\Omega$, or $\Theta$). Provide mathematical justification for your claims.

**Submission:** A concise writeup detailing the formulation, pseudocode, and mathematical analysis in a file called `planning.md`.

---

## Deliverable 2: Implementation and Evaluation (Week 2)
**Focus:** Prototyping and Evaluation
**Grading:** Effort & Completion

In this phase, you will translate your theoretical design into a functional, measurable prototype.

**Tasks:**
1. **Code Implementation:** Translate your pseudocode into functional, well-documented code.
2. **Testing Suite:** Develop comprehensive test cases. Ensure you code works as intended.
3. **Benchmarking Script:** Empirically measure the running time of your baseline and proposed algorithm as the input size scales.

**Submission:** Source code, test scripts, and a summary of your empirical evaluation in a file called `evaluation.md`.

---

## Deliverable 3: Findings and Reflection (Week 3)
**Focus:** Synthesis  
**Grading:** Correctness & Effectiveness

This is the capstone report for your project, combining your theoretical expectations with your empirical findings.

**Tasks:**
1. **Empirical Synthesis:** Create visualizations using your benchmarking data. Does it support your theoretical analysis? Identify and explain any discrepancies (e.g., unexpected hardware overhead, hidden constants).
2. **Baseline Comparison:** Compare your proposed algorithm's performance against the baseline. Discuss any improvements or regressions observed in your empirical evaluation.
3. **Reflection:** Write a reflection on your team's design and debugging process. Discuss any two-stage submission improvements made from earlier weeks. Be specific about your challenges: detail specific structural pivots your team had to make, or debugging moments that led to critical breakthroughs.

**Submission:** A finalized writeup including the description of the problem, visualizations, analysis, and reflection in a file called `findings.md`.

---

## Deliverable 4: Presentation of Results (Week 4)
**Focus:** Technical Communication  
**Grading:** Correctness & Effectiveness

Your team will give a presentation detailing your problem, approach, and results.

**Tasks:**
1. **Narrative Design:** Structure your presentation to guide the audience through the problem, your chosen strategy, and the final results. 
2. **Conciseness:** Limit the presentation to 7 to 10 minutes. Avoid unnecessary details and focus on delivering a clear and coherent narrative.
3. **Q&A Defense:** Prepare to field technical questions from your peers and the teaching staff.

**Submission:** Giving the presentation.