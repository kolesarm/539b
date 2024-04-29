# Overview

This half-course covers some commonly used designs and empirical research in
applied microeconomics and related fields. For Princeton students, homework and
solutions to it will be posted on Canvas. Official course description is at the
[Registrar's
website](https://registrar.princeton.edu/course-offerings/course-details?term=1244&courseid=015253).

Good empirical research has three pillars:

1. Measurement. One can't really answer a policy question (what's the effect of
   intervention A) or a science question (what's the elasticity of demand)
   without being able to measure the key quantities. Indeed, much of the
   progress in the last 20 or so years in applied micro has been due to better
   measurement---access to better and more reliable data.
2. Design. This another catch-all that just means the empirical specification
   you run is grounded in something. You don't just throw a kitchen sink of
   controls at the problem and argue unconfoundedness. Instead, identification
   exploits some economic or institutional feature of the data.
3. Inference. You have a way of assessing the reliability of your estimates.

This course has nothing to say about the most important pillar, measurement. It
will have something to say about the second pillar, though for much of the
course we'll take the empirical specification as given, and instead think
through the assumptions needed to make sense of the estimand. We'll spend much
time on getting the inference right, which is the least important pillar: a good
paper requires good measurement and good design, but not necessarily great
inference.

It is not that common that some naive way of estimating the standard errors is
off by an order of magnitude (one major exception being the question of whether
to cluster the standard errors), but there are lots of settings where the
estimates may be off by an order of magnitude if the design is off. Yet there
are many settings where naive inference may mislead, and it's important to
recognize those settings.

# Notes

I provide detailed lecture notes with references. Sometimes I will provide
slides. The goal of the slides is just to streamline classroom discussion; they
are incomplete. In contrast, the goal of the lecture notes is to serve as a
reference for your own later research, and as such, they aim to be
self-contained and detailed. In lectures (and slides), we won't have time to
dive into all the details, so it's a good idea to read the notes ahead of time,
or at least after class.

# Homework

I'll give weekly homework, which will be a mix of empirical exercises and
critical summaries of assigned readings. They will be posted on Canvas.

# Topics

1. The bootstrap: when does it work, when does it fail? [Notes](2024s_01_bootstrap.pdf)
2. Linear regression. What does regression estimate when regresison function is
   not linear / treatment effects are heterogeneous? When is the estimand
   causal? Model-based versus design-based identification and inference. What
   variable to cluster on? [Notes](2024s_02_ols.pdf)
3. Small-sample issues and large data issues in linear regression: when do usual
   robust standard errors mislead and what to do instead.
   [Notes](2024s_03_ehw.pdf)
4. Instrumental variables. What does IV estimate when treatment effects are
   heterogeneous? How does inference change under heterogeneity? How to detect
   weak instruments and what, if anything, to do about them. [Notes](2024s_04_iv.pdf)
5. Many instruments and judge designs. [Notes](2024s_05_manyiv.pdf)
   [Slides](2024s_05_manyiv_slides.pdf)
6. Shift-share instruments [Slides](2024s_06_ssiv_slides.pdf)
7. Regression discontinuity. Standard vs bias-aware approaches to inference.
   [Notes](2024s_07_rd.pdf) [Slides](2024s_07_rd_slides.pdf)
8. Differences in differences and event studies. Changes-in-Changes, conditional
   common trends, interpretation under treatment effect heterogeneity.
   [Notes](2024s_08_dd.pdf)
9. Simulated method of moments. Indirect inference, simulated maximum
   likelihood, importance sampling, and implementation issues.
   [Notes](2024s_09_simulation.pdf)
10. Synthetic controls [Notes](2024s_10_synthetic.pdf)


# Errors

Please report typos and errors in the lecture notes by opening an issue.
