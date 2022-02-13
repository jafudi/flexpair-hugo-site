---
date: 2022-01-16
title: Which problem do we solve?
image: images/blog/01.jpg
author_info:
  name: Jens F.
  image: images/author/jens.png
author: Jens

---
## Problem

Data science has become location-independent. Still it is lacking a meaningful integration of synchronous and asynchronous work steps in one tool.

1. most data science applications are evaluated and eventually approved by the customer based on visualizations and using real data

2. CI/CD pipelines usually contain neither significant amounts of real data nor visualizations for technical and runtime reasons and due to data protection.

3. workarounds like testing on local machines and traditional screen sharing do not solve the problem, as these individual development environments are neither identical to each other nor to the production environment (dependencies etc.)

4. Even if a dedicated (shared) staging environment exists, it is often used only for the master branch and thus far too rarely or late in the process. Nevertheless, financial and environmental fixed costs are constantly incurred.

5. The problem existed before Corona, and it does not get easier in a hybrid work context. But hybrid is good for inclusion and the environment. And as more and more companies transition to a hybrid working model, we asked ourselves the question: How can we make those frequent handovers more consistent and a truly hands-on experience?

<!-- Nach dem Intro geht es normalerweise um das Problem, was euer Produkt oder eure Dienstleistung für einen potenziellen Markt löst. Vermeidet hier komplizierte Formulierungen oder diskutable Argumente. In der Regel sind drei sehr klare und unwiderlegbare Aussagen völlig ausreichend. Lasst keine Zweifel aufkommen und formuliert diese Folie so, dass jeder das Problem nachvollziehen kann. -->

## Solution

1. Automatically create an identical clone of a standardized staging environment whenever opening a merge request for a feature branch.

2. Have automated CI/CD run in the created staging environment

3. Schedule an interactive live review session with one of your peers, where you both access the staging environment over the web

4. After the merge, tear down the environment automatically.

<!-- Für jedes Problem, das ihr in eurem Pitch Deck aufzeigt, solltet ihr auch schlagkräftige Lösungen präsentieren. Diese Folie muss so konzipiert sein, dass ihr schnell und verständlich den Nutzen eures Produktes oder eurer Dienstleistung kommunizieren könnt. Auf diese Weise solltet ihr ebenfalls sehr klare Aussagen darüber treffen, wie die zuvor dargestellten Problemen durch eure Technologie gelöst werden. Keine Verkomplizierung! Haltet es einfach und auf den Punkt! -->