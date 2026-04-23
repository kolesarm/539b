# Overview

This half-course covers some commonly used research designs and empirical
methods in applied microeconomics and related fields. Homework and solutions
will be posted on Canvas for Princeton students. The official course description
is at the [Registrar's
website](https://registrar.princeton.edu/course-offerings/course-details?term=1264&courseid=015253).

Good empirical research has three pillars:

1. Measurement. One can't really answer a policy question (what's the effect of
   some intervention) or a science question (what's the elasticity of demand)
   without being able to measure the key quantities. Indeed, much of the
   progress in the last 20 or so years in applied micro has been due to better
   measurement---access to better and more reliable data.
2. Design. This is a catch-all term that meaning the empirical specification you
   choose to run is grounded in something. You don't just throw a kitchen sink
   of controls at the problem and argue unconfoundedness. Instead, a solid
   design exploits a particular economic or institutional feature of the data.
3. Inference. You have a way of assessing the reliability and accuracy of your
   estimates.

This course has nothing to say about the most important pillar, measurement. It
will have something to say about design, though for much of the course we'll
take the empirical specification---the design---as given: we will not talk much
about whether to run a diff-in-diff regression versus a specification with
lagged dependent variables. Instead, we will think through the assumptions
needed to make sense of the empirical specification and talk about how the
underlying design (identification strategy) can be validated. We'll spend
considerable time on getting the inference right, which is the least important
pillar: while good measurement and good design are necessary for a paper to be
convincing, many great papers have minor inference issues.

In particular, while it is uncommon that a naive approach to standard error
estimation is off by an order of magnitude, there are lots of settings where the
estimates may be off by an order of magnitude if the design is off.
Nevertheless, it is important to recognize settings where naive inference may
mislead---such as when standard errors are clustered incorrectly---so your paper
doesn't end up being one of those exceptions.

# Notes

I provide detailed lecture notes with references. Sometimes I will provide
slides. The goal of the slides is simply to streamline classroom discussion;
they are incomplete. In contrast, the lecture notes aim to be self-contained and
detailed, so that they can serve as a reference for your own later research. In
lectures (and slides), we won't have time to dive into all the details, so it's
a good idea to read the notes ahead of time, or at least after class.

# Homework

I'll give weekly homework sets, which will be a mix of empirical exercises and
critical summaries of assigned readings. They will be posted on Canvas.

# Topics

1. The bootstrap: when does it work, when does it fail?
   [Notes](2026s_01_bootstrap.pdf)
2. Linear regression. What does regression estimate when the regression function
   is not linear / treatment effects are heterogeneous? When is the estimand
   causal? Model-based versus design-based identification and inference. What
   variable to cluster on? [Notes](2026s_02_ols.pdf)
3. Small-sample issues and large data issues in linear regression: when do usual
   robust standard errors mislead and what to do instead.
   [Notes](2026s_03_ehw.pdf) [Slides](2026s_03_ehw_slides.pdf)
4. Instrumental variables. What does IV estimate when treatment effects are
   heterogeneous? How does inference change under heterogeneity? How to detect
   weak instruments and what, if anything, to do about them.
   [Notes](2024s_04_iv.pdf) [Slides](2026s_04_iv_slides.pdf)
5. Leniency IV and many instruments. [Notes](2024s_05_manyiv.pdf)
   [Slides](2026s_05_manyiv_slides.pdf)
6. Shift-share instruments [Slides](2026s_06_ssiv_slides.pdf)
7. Regression discontinuity. Standard vs bias-aware approaches to inference.
   [Notes](2026s_07_rd.pdf) [Slides](2026s_07_rd_slides.pdf)
8. Differences in differences and event studies. Changes-in-Changes, conditional
   common trends, interpretation under treatment effect heterogeneity.
   [Notes](2024s_08_dd.pdf)
9. Simulated method of moments. Indirect inference, simulated maximum
   likelihood, importance sampling, and implementation issues.
   [Notes](2026s_09_simulation.pdf)
10. Synthetic controls [Notes](2024s_10_synthetic.pdf)
11. Double machine learning [Slides](2026s_11_doubly_robust_slides.pdf)


# Errors

Please report typos and errors in the lecture notes by opening an issue.
