# A Survey on Modern Code Review (MCR) 
In this repository, we collected papers related to modern code review (MCR) from Jan. 2013 to Nov. 2025. We propose a taxonomy of MCR tasks, aiming to assist developers and researchers to gain a better understanding of MCR. More detailed information can be found in our paper ["A Survey on Modern Code Review: Progresses, Challenges and Opportunities"](https://arxiv.org/abs/2405.18216).

## Overview

### Workflow

![MCR-workflow](./MCR-workflow.jpg)

### Taxonomy

![The taxonomy of MCR](./MCR-Taxonomy.png)

## Catalogue

### Improvement Techniques

![Improvement Techniques](./pic/Improvement-Techniques-1.png)


#### Code Change Analysis

![Code Change Analysis](./pic/Improvement/Code-Change-Analysis.png)

##### Change Decomposition

2015

[Partitioning composite code changes to facilitate code review](https://ieeexplore.ieee.org/abstract/document/7180078/)

[Helping developers help themselves: Automatic decomposition of code review changesets](https://ieeexplore.ieee.org/abstract/document/7194568/)

2018

[Automatic decomposition of java open source pull requests: a replication study](https://link.springer.com/chapter/10.1007/978-3-319-73117-9_18)

2019

[The effects of change decomposition on code review—a controlled experiment](https://peerj.com/articles/cs-193.pdf)

[Decomposing composite changes for code review and regression test selection in evolving software](https://link.springer.com/article/10.1007/s11390-019-1917-9)

[Cora: Decomposing and describing tangled code changes for reviewer](https://ieeexplore.ieee.org/abstract/document/8952413/)

#### Change Understanding

2013

[Supporting Automatic Code Review via Design](https://ieeexplore.ieee.org/abstract/document/6616346/)

2014

[Clustering commits for understanding the intents of implementation](https://ieeexplore.ieee.org/abstract/document/6976107/)

2015

[Code review: Veni, vidi, vici](https://ieeexplore.ieee.org/abstract/document/7081825/)

2017

[Semantics-assisted code review: An efficient tool chain and a user study](https://ieeexplore.ieee.org/abstract/document/8115666/)

[Multi-perspective visualization to assist code change review](https://ieeexplore.ieee.org/abstract/document/8305982/)

2018

[Blimp tracer: Integrating build impact analysis with code review](https://ieeexplore.ieee.org/abstract/document/8530081/)

2019

[Aiding code change understanding with semantic change impact analysis](https://ieeexplore.ieee.org/abstract/document/8918947/)

2021

[Predicting design impactful changes in modern code review: A large-scale empirical study](https://ieeexplore.ieee.org/abstract/document/9463137/)

[Automatic patch linkage detection in code review using textual content and file location features](https://www.sciencedirect.com/science/article/pii/S0950584921001038)

[Augmenting Code Review Experience Through Visualization](https://ieeexplore.ieee.org/abstract/document/9604852/)

2022

[DIDIFFFF: A viewer for comparing changes in both code and execution traces](https://dl.acm.org/doi/abs/10.1145/3524610.3527877)

2023

[Graph-based visualization of merge requests for code review](https://www.sciencedirect.com/science/article/pii/S0164121222001820)

2024

[Design of Flexible Code Block Comparisons to Improve Code Review of Refactored Code](https://dl.acm.org/doi/10.1145/3660829.3660842)

[Visual Integration of Static and Dynamic Software Analysis in Code Reviews via Software City Visualization](https://ieeexplore.ieee.org/document/10794801)

[Help Me to Understand this Commit! - A Vision for Contextualized Code Reviews](https://dl.acm.org/doi/10.1145/3643796.3648447)

##### Specific Code Identification

2013

[LASE: locating and applying systematic edits by learning from examples](https://ieeexplore.ieee.org/abstract/document/6606596/)

2015

[Interactive code review for systematic changes](https://ieeexplore.ieee.org/abstract/document/7194566/)

2017

[Tool support for managing clone refactorings to facilitate code review in evolving software](https://ieeexplore.ieee.org/abstract/document/8029620/)

[Refactoring-aware code review](https://ieeexplore.ieee.org/abstract/document/8103453/)

2018

[Clonemap: A clone-aware code inspection tool in evolving software](https://ieeexplore.ieee.org/abstract/document/8500143/)

[What makes a code change easier to review: an empirical investigation on code change reviewability](https://dl.acm.org/doi/abs/10.1145/3236024.3236080)

2019

[Leveraging change intents for characterizing and identifying large-review-effort changes](https://dl.acm.org/doi/abs/10.1145/3345629.3345635)

[Automatic code review by learning the revision of source code](https://ojs.aaai.org/index.php/AAAI/article/view/4420)

2020

[Code inspection support for recurring changes with deep learning in evolving software](https://ieeexplore.ieee.org/abstract/document/9202813/)

2021

[RAID: Tool support for refactoring-aware code reviews](https://ieeexplore.ieee.org/abstract/document/9463030/)

2022

[Code review knowledge perception: Fusing multi-features for salient-class location](https://ieeexplore.ieee.org/abstract/document/9186620/)

2023

[Towards verifiable web-based code review systems](https://content.iospress.com/articles/journal-of-computer-security/jcs210098)

[Are your dependencies code reviewed?: Measuring code review coverage in dependency updates](https://ieeexplore.ieee.org/abstract/document/10266387/)

[Code compliance assessment as a learning problem](https://ieeexplore.ieee.org/abstract/document/10172520/)

2024

[The utility of complexity metrics during code reviews for CSE software projects](https://www.sciencedirect.com/science/article/abs/pii/S0167739X2400270X)

[Don’t forget to change these functions! recommending co-changed functions in modern code review](https://www.sciencedirect.com/science/article/pii/S0950584924001526)

2025

[On the Classification of Refactoring Code Reviews](https://ieeexplore.ieee.org/document/11141041)

##### Defective Change Prediction

2016

[Predicting defectiveness of software patches](https://dl.acm.org/doi/abs/10.1145/2961111.2962601)

2017

[Code review analysis of software system using machine learning techniques](https://ieeexplore.ieee.org/abstract/document/7855962/)

[A case study on machine learning model for code review expert system in software engineering](https://ieeexplore.ieee.org/abstract/document/8104731/)

2019

[Using Stack Overflow content to assist in code review](https://onlinelibrary.wiley.com/doi/abs/10.1002/spe.2706)

2021

[Using Paragraph Vectors to improve our existing code review assisting tool-CRUSO](https://dl.acm.org/doi/abs/10.1145/3452383.3452393)

[Rigorous code review by reverse engineering](https://www.sciencedirect.com/science/article/pii/S0950584920302457)

2022

[Where should i look at? recommending lines that reviewers should pay attention to](https://ieeexplore.ieee.org/abstract/document/9825760/)

[Leveraging test plan quality to improve code review efficacy](https://dl.acm.org/doi/abs/10.1145/3540250.3558952)

2023

[A multi-step learning approach to assist code review](https://ieeexplore.ieee.org/abstract/document/10123491/)

2024

[RevToken: A Token-Level Review Recommendation: How Far Are We?](https://ieeexplore.ieee.org/document/10795052)

[Investigation on Integration of Machine Learning Techniques into LC/NC Platforms for Code Review, Quality Assessment, and Error Detection Automation](https://ieeexplore.ieee.org/document/10522267)

2025

[Unlocking LLM Security: Automated Penetration Testing and Source Code Review Based on Vulnerability Analysis and NLP](https://www.researchgate.net/publication/394169044_Unlocking_LLM_Security_Automated_Penetration_Testing_and_Source_Code_Review_Based_on_Vulnerability_Analysis_and_NLP)

[iCodeReviewer: Improving Secure Code Review with Mixture of Prompts](https://arxiv.org/abs/2510.12186)

##### Change Prioritization

2013

[0-1 Programming Model-Based Method for Planning Code Review Using Bug Fix History](https://ieeexplore.ieee.org/abstract/document/6754348/)

2015

[Automatically prioritizing pull requests](https://ieeexplore.ieee.org/abstract/document/7180094/)

[Work practices and challenges in pull-based development: The integrator's perspective](https://ieeexplore.ieee.org/abstract/document/7194588/)

2018

[Early prediction of merged code changes to prioritize reviewing tasks](https://link.springer.com/article/10.1007/s10664-018-9602-0)

2019

[Improving the pull requests review process using learning-to-rank algorithms](https://link.springer.com/article/10.1007/s10664-019-09696-8)

2021

[Using machine intelligence to prioritise code review requests](https://ieeexplore.ieee.org/abstract/document/9402093/)

2022

[Reviewing rounds prediction for code patches](https://link.springer.com/article/10.1007/s10664-021-10035-z)

[Early prediction for merged vs abandoned code changes in modern code reviews](https://www.sciencedirect.com/science/article/pii/S0950584921002032)

2024

[A multi-objective effort-aware approach for early code review prediction and prioritization](https://link.springer.com/article/10.1007/s10664-023-10431-7)

[An Empirical Study on Code Review Activity Prediction and Its Impact in Practice](https://dl.acm.org/doi/10.1145/3660806)

[GPP: A Graph-Powered Prioritizer for Code Review Requests](https://dl.acm.org/doi/10.1145/3691620.3694990)

2025

[Prioritizing code review requests to improve review efficiency: a simulation study](https://link.springer.com/article/10.1007/s10664-024-10575-0)

##### Change Improvement

2013

[Fix-it: An extensible code auto-fix component in review bot](https://ieeexplore.ieee.org/abstract/document/6648198/)

2019

[Mining source code improvement patterns from similar code review works](https://ieeexplore.ieee.org/abstract/document/8665852/)

2021

[Towards automating code review activities](https://ieeexplore.ieee.org/abstract/document/9402025/)

2022

[Autotransform: Automated code transformation to support modern code review process](https://dl.acm.org/doi/abs/10.1145/3510003.3510067)

2023

[Towards Automated Code Reviews: Does Learning Code Structure Help?](https://ieeexplore.ieee.org/abstract/document/10123547/)

[D-act: Towards diff-aware code transformation for code review under a time-wise evaluation](https://ieeexplore.ieee.org/abstract/document/10123643/)

2024

[Resolving Code Review Comments with Machine Learning](https://dl.acm.org/doi/10.1145/3639477.3639746)

[Exploring the Potential of ChatGPT in Automated Code Refinement: An Empirical Study](https://dl.acm.org/doi/10.1145/3597503.3623306)

2025

[Divide-and-Conquer: Automating Code Revisions via Localization-and-Revision](https://dl.acm.org/doi/full/10.1145/3697013)


#### Reviewer Recommendation

![Reviewer Recommendation](./pic/Improvement/Reviewer-Recommendation.png)

##### Technical Factors

* Change characteristics

  2013

  [Reducing human effort and improving quality in peer code reviews using automatic static analysis and reviewer recommendation](https://ieeexplore.ieee.org/abstract/document/6606642/)

  2015

  [Who should review my code? a file location-based code-reviewer recommendation approach for modern code review](https://ieeexplore.ieee.org/abstract/document/7081824/)

  [Who should review this change?: Putting text and file location analyses together for more accurate recommendations](https://ieeexplore.ieee.org/abstract/document/7332472/)

  2023

  [Code reviewer recommendation for architecture violations: An exploratory study](https://dl.acm.org/doi/abs/10.1145/3593434.3593450)

* Reviewers' experience
  
  2014

  [Mining peer code review system for computing effort and contribution metrics for patch reviewers](https://ieeexplore.ieee.org/abstract/document/6980189/)

  2016

  [Automatically recommending code reviewers based on their expertise: An empirical comparison](https://dl.acm.org/doi/abs/10.1145/2970276.2970306)

  [Search-based peer reviewers recommendation in modern code review](https://ieeexplore.ieee.org/abstract/document/7816482/)

  [Correct: code reviewer recommendation in github based on cross-project and technology experience](https://dl.acm.org/doi/abs/10.1145/2889160.2889244)

  [Automatically recommending peer reviewers in modern code review](https://ieeexplore.ieee.org/abstract/document/7328331/)

  2020

  [ADCR: An Adaptive TOOL to select” Appropriate Developer for Code Review” based on Code Context](https://ieeexplore.ieee.org/abstract/document/9298102/)

  2021

  [Detection and elimination of systematic labeling bias in code reviewer recommendation systems](https://dl.acm.org/doi/abs/10.1145/3463274.3463336)

  2024

  [Distilling Quality Enhancing Comments from Code Reviews to Underpin Reviewer Recommendation](https://ieeexplore.ieee.org/abstract/document/10411501/)


##### Non-Technical Factors

* Social relations

  2016

  [Reviewer recommendation for pull-requests in GitHub: What can we learn from code review and bug assignment?](https://www.sciencedirect.com/science/article/pii/S0950584916000069)

  2017

  [Who should comment on this pull request? analyzing attributes for more accurate commenter recommendation in pull-based development](https://www.sciencedirect.com/science/article/pii/S095058491630283X)


  2023

  [Using large-scale heterogeneous graph representation learning for code review recommendations at microsoft](https://ieeexplore.ieee.org/abstract/document/10172555/)


* Workload balancing

  2019

  [Whodo: Automating reviewer suggestions at scale](https://dl.acm.org/doi/abs/10.1145/3338906.3340449)

  2020

  [Does reviewer recommendation help developers?](https://ieeexplore.ieee.org/abstract/document/8453850/)

  [Multi-objective code reviewer recommendations: balancing expertise, availability and collaborations](https://link.springer.com/article/10.1007/s10515-020-00275-6)

  2023

  [Integrating Visual Aids to Enhance the Code Reviewer Selection Process](https://ieeexplore.ieee.org/abstract/document/10336290/)

  2024

  [Factoring Expertise, Workload, and Turnover into Code Review Recommendation](https://ieeexplore.ieee.org/abstract/document/10444097/)

  2025

  [Improving Code Reviewer Recommendation: Accuracy, Latency, Workload, and Bystanders](https://dl.acm.org/doi/10.1145/3736405)

##### Hybrid approaches

2017

[A hybrid approach to code reviewer recommendation with collaborative filtering](https://ieeexplore.ieee.org/abstract/document/8100850/)

2019

[Reviewer recommendation using software artifact traceability graphs](https://dl.acm.org/doi/abs/10.1145/3345629.3345637)

2021

[RSTrace+: Reviewer suggestion using software artifact traceability graphs](https://www.sciencedirect.com/science/article/pii/S0950584920300021)

2022

[Intelligent Code Review Assignment for Large Scale Open Source Software Stacks](https://dl.acm.org/doi/abs/10.1145/3551349.3561147)

[Recommending code reviewers for proprietary software projects: A large scale study](https://ieeexplore.ieee.org/abstract/document/9825901/)

[Corms: a github and gerrit based hybrid code reviewer recommendation approach for modern code review](https://dl.acm.org/doi/abs/10.1145/3540250.3549115)

[Modeling review history for reviewer recommendation: A hypergraph approach](https://dl.acm.org/doi/abs/10.1145/3510003.3510213)

2023

[A code reviewer recommendation approach based on attentive neighbor embedding propagation](https://www.mdpi.com/2079-9292/12/9/2113)

2024

[Code Reviewer Recommendation Based on a Hypergraph with Multiplex Relationships](https://ieeexplore.ieee.org/document/10589808)


#### Review Comment Synthesis

![Reviewer Comment Synthesis](./pic/Improvement/Review-Comment-Synthesis.png)

* Retrieval-based methods

  2018

  [Diggit: Automated code review via software repository mining](https://ieeexplore.ieee.org/abstract/document/8330261/)

  2022

  [Commentfinder: a simpler, faster, more accurate code review comments recommendation](https://dl.acm.org/doi/abs/10.1145/3540250.3549119)

  2023

  [Recommending Code Reviews Leveraging Code Changes with Structured Information Retrieval](https://ieeexplore.ieee.org/abstract/document/10336317/)

  2024

  [Automating modern code review processes with code similarity measurement](https://www.sciencedirect.com/science/article/abs/pii/S0950584924000958)

  2025

  [ACoRA-A Platform for Automating Code Review Tasks](https://www.e-informatyka.pl/attach/e-Informatica_papers/eInformatica2025Art02.pdf)

* Generation-based methods

  - Deep learning-based methods

    2018
    [Intelligent code reviews using deep learning](https://www.kdd.org/kdd2018/files/deep-learning-day/DLDay18_paper_40.pdf)

    2020

    [Core: Automating review recommendation for code changes](https://ieeexplore.ieee.org/abstract/document/9054794/)

    2022

    [Example driven code review explanation](https://dl.acm.org/doi/abs/10.1145/3544902.3546639)
    
  - LLM-based methods

    2024

    [Exploring the impact of code review factors on the code review comment generation](https://link.springer.com/article/10.1007/s10515-024-00469-2)

    2025

    [Combining Large Language Models with Static Analyzers for Code Review Generation](https://arxiv.org/abs/2502.06633)

    [LAURA: Enhancing Code Review Generation with Context-Enriched Retrieval-Augmented LLM](https://www.arxiv.org/abs/2512.01356)

    [CodeDoctor: multi-category code review comment generation](https://link.springer.com/article/10.1007/s10515-025-00491-y)

    [Leveraging Reviewer Experience in Code Review Comment Generation](https://dl.acm.org/doi/10.1145/3762183)

    [Too Noisy To Learn: Enhancing Data Quality for Code Review Comment Generation](https://arxiv.org/abs/2502.02757)

#### Review Comment Analysis

![Review-Comment-Analysis](./pic/Improvement/Review-Comment-Analysis.png)

##### Content and Intent Analysis

[Automated code review comment classification to improve modern code reviews](https://link.springer.com/chapter/10.1007/978-3-031-04115-0_3)

2024

[Named Entity Recognition for Code Review Comments](https://link.springer.com/article/10.1134/S0361768824700233)

2025
[Supporting the identification of prevalent quality issues in code changes by analyzing reviewers’ feedback](https://link.springer.com/article/10.1007/s11219-025-09720-9)

[Building a Dataset for Combined Classification of Source Code Reviews](https://link.springer.com/article/10.1134/S1054661825700336)

##### Sentiment and Tone Analysis

2017

[SentiCR: A customized sentiment analysis tool for code review interactions](https://ieeexplore.ieee.org/abstract/document/8115623/)

2020

[Predicting developers' negative feelings about code review](https://dl.acm.org/doi/abs/10.1145/3377811.3380414)

[Affect recognition in code review: An in-situ biometric study of reviewer's affect](https://www.sciencedirect.com/science/article/pii/S0164121219302080)

2022

[Detecting interpersonal conflict in issues and code review: cross pollinating open-and closed-source approaches](https://dl.acm.org/doi/abs/10.1145/3510458.3513019)

2023

[ToxiSpanSE: An Explainable Toxicity Detection in Code Review Comments](https://ieeexplore.ieee.org/abstract/document/10304855/)

2024

[Do Words Have Power? Understanding and Fostering Civility in Code Review Discussion](https://dl.acm.org/doi/10.1145/3660780)

##### Quality and Usefulness Assessment

2014

[Assessing MCR discussion usefulness using semantic similarity](https://ieeexplore.ieee.org/abstract/document/6976022/)

2017

[Confusion detection in code reviews](https://ieeexplore.ieee.org/abstract/document/8094460/)

[Predicting usefulness of code review comments using textual features and developer experience](https://ieeexplore.ieee.org/abstract/document/7962371/)

2021

[Using a balanced scorecard to identify opportunities to improve code review effectiveness: An industrial experience report](https://link.springer.com/article/10.1007/s10664-021-10038-w)

2023

[EvaCRC: Evaluating Code Review Comments](https://dl.acm.org/doi/abs/10.1145/3611643.3616245)

[Exploring the Advances in Identifying Useful Code Review Comments](https://arxiv.org/abs/2307.00692)

2025

[Hold on! is my feedback useful? evaluating the usefulness of code review comments](https://link.springer.com/article/10.1007/s10664-025-10617-1)

#### Unified Automation Frameworks

![Unified Automation Frameworks](./pic/Improvement/Unified-Automation-Frameworks.png)

##### Deep learning-based methods

2022

[Using pre-trained models to boost code review automation](https://dl.acm.org/doi/abs/10.1145/3510003.3510621)

[Automating code review activities by large-scale pre-training](https://dl.acm.org/doi/abs/10.1145/3540250.3549081)

2023

[Automatic code review by learning the structure information of code graph](https://www.mdpi.com/1424-8220/23/5/2551)

2024

[Structuring Meaningful Code Review Automation in Developer Community](https://www.sciencedirect.com/science/article/pii/S0952197623011545)

[MULTICR: Predicting Merged and Abandoned Code Changes in Modern Code Review Using Multi-Objective Search](https://dl.acm.org/doi/10.1145/3680472)

[AI-Assisted Assessment of Coding Practices in Modern Code Review](https://dl.acm.org/doi/10.1145/3664646.3665664)

[Automated Code Review and Bug Detection](https://ieeexplore.ieee.org/document/10799479/)

[Improving the Learning of Code Review Successive Tasks with Cross-Task Knowledge Distillation](https://dl.acm.org/doi/pdf/10.1145/3643775)

2025

[Harnessing Large Language Models for Curated Code Reviews](https://www.computer.org/csdl/proceedings-article/msr/2025/018300a187/27vTzHLTs1W)

##### LLM-based methods

2023

[LLaMA-Reviewer: Advancing Code Review Automation with Large Language Models through Parameter-Efficient Fine-Tuning](https://ieeexplore.ieee.org/abstract/document/10299938/)

2024

[Fine-Tuning Large Language Models to Improve Accuracy and Comprehensibility of Automated Code Review](https://dl.acm.org/doi/10.1145/3695993)

[AICodeReview: Advancing code quality with AI-enhanced reviews](https://www.sciencedirect.com/science/article/pii/S2352711024000487)

[AI-Powered Code Reviews: Leveraging Large Language Models](https://ieeexplore.ieee.org/document/10829223)

[GitRev: An LLM-Based Gamification Framework for Modern Code Review Activities](https://ieeexplore.ieee.org/document/10795351)

[CodeAgent: Autonomous Communicative Agents for Code Review](https://aclanthology.org/2024.emnlp-main.632.pdf)

2025

[Adaptive Multi-Agent AI Framework for Real-Time Energy Optimization and Context-Aware Code Review in Software Development](https://ieeexplore.ieee.org/document/11066037)

[Hydra-Reviewer: A Holistic Multi-Agent System for Automatic Code Review Comment Generation](https://ieeexplore.ieee.org/document/11203269/)

[Automated Code Review Using Large Language Models at Ericsson: An Experience Report](https://arxiv.org/abs/2507.19115)

[BitsAI-CR: Automated Code Review via LLM in Practice](https://dl.acm.org/doi/10.1145/3696630.3728552)

[Multi-Agent LLM Collaboration for Adaptive Code Review, Debugging, and Security Analysis](https://ieeexplore.ieee.org/document/11135756)


### Understanding Study

![Understanding-Studies-1](./pic/Understanding-Studies-1.png)


#### Quality Assurance and Reliability 

![Quality Assurance and Reliability](./pic/Understanding/Quality-Assurance-and-Reliability.png)


##### Defect and Risk Detection

2015

[Would static analysis tools help developers with code reviews?](https://ieeexplore.ieee.org/abstract/document/7081826/)

[Investigating code review practices in defective files: An empirical study of the qt system](https://ieeexplore.ieee.org/abstract/document/7180077/)

2016

[Can formal methods improve the efficiency of code reviews?](https://link.springer.com/chapter/10.1007/978-3-319-33693-0_1)

2017

[Using metrics to track code review performance](https://dl.acm.org/doi/abs/10.1145/3084226.3084247)

[Evaluating how static analysis tools can reduce code review effort](https://ieeexplore.ieee.org/abstract/document/8103456/)

2018

[Impact of coding style checker on code review-a case study on the openstack projects](https://ieeexplore.ieee.org/abstract/document/8661217/)

2023

[Can static analysis tools find more defects? a qualitative study of design rule violations found by code review](https://link.springer.com/article/10.1007/s10664-022-10232-4)

[Concerns identified in code review: A fine-grained, faceted classification](https://www.sciencedirect.com/science/article/pii/S0950584922001653)

2024

[Studying the impact of risk assessment analytics on risk awareness and code review performance](https://link.springer.com/article/10.1007/s10664-024-10443-x)

##### Security Review Effectiveness

2013

[Expectations, outcomes, and challenges of modern code review](https://ieeexplore.ieee.org/abstract/document/6606617/)

2016

[A security perspective on code review: The case of chromium](https://ieeexplore.ieee.org/abstract/document/7781793/)

2018

[A survey on source code review using machine learning](https://ieeexplore.ieee.org/abstract/document/8614720/)

2022

[Software security during modern code review: The developer's perspective](https://dl.acm.org/doi/abs/10.1145/3540250.3549135)

2023

[Empirical analysis of security-related code reviews in npm packages](https://www.sciencedirect.com/science/article/pii/S0164121223001474)

[Security Defect Detection via Code Review: A Study of the OpenStack and Qt Communities](https://ieeexplore.ieee.org/abstract/document/10304852/)

2024

[Toward effective secure code reviews: an empirical study of security-related coding weaknesses](https://link.springer.com/article/10.1007/s10664-024-10496-y)

[An Empirical Study of Static Analysis Tools for Secure Code Review](https://dl.acm.org/doi/10.1145/3650212.3680313)

[Serious Game for Industrial Cybersecurity: Experiential Learning Through Code Review](https://ieeexplore.ieee.org/document/10663058)

##### Reviewing Specialized Artifacts

- Documentation and Specs

  2022

  [Comments on comments: Where code review and documentation meet](https://dl.acm.org/doi/abs/10.1145/3524842.3528475)

  2023

  [Code review of build system specifications: prevalence, purposes, patterns, and perceptions](https://ieeexplore.ieee.org/abstract/document/10172582/)

  2024

  [Ten simple rules for scientific code review](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012375)

- Test Code

  2018

  [When testing meets code review: Why and how developers review tests](https://dl.acm.org/doi/abs/10.1145/3180155.3180192)

  2019

  [Test-driven code review: an empirical study](https://ieeexplore.ieee.org/abstract/document/8811911/)

- Refactoring Challenges

  2018

  [Why did this reviewed code crash? An empirical study of mozilla firefox](https://ieeexplore.ieee.org/abstract/document/8719430/)

  2020

  [Behind the intents: An in-depth empirical study on software refactoring in modern code review](https://dl.acm.org/doi/abs/10.1145/3379597.3387475)


  2022

  [Code review practices for refactoring changes: An empirical study on openstack](https://dl.acm.org/doi/abs/10.1145/3524842.3527932)

  2021

  [Refactoring practices in the context of modern code review: An industrial case study at Xerox](https://ieeexplore.ieee.org/abstract/document/9401999/)

- Semantics and Maintainability
  
  2020

  [Does code review really remove coding convention violations?](https://ieeexplore.ieee.org/abstract/document/9252011/)

  2022

  [Code smells detection via modern code review: A study of the openstack and qt communities](https://link.springer.com/article/10.1007/s10664-022-10178-7)

  2024

  [Do code reviews lead to fewer code smells?](https://www.sciencedirect.com/science/article/abs/pii/S0164121224001468)

  2025

  [Understanding Code Understandability Improvements in Code Reviews](https://ieeexplore.ieee.org/document/10670481)

  [How Are We Detecting Inconsistent Method Names? An Empirical Study from Code Review Perspective](https://dl.acm.org/doi/10.1145/3711901)

- Strategies for Structural Quality

  2024

  [A qualitative study on refactorings induced by code review](https://link.springer.com/article/10.1007/s10664-024-10560-7)

  2025

  [Deciphering refactoring branch dynamics in modern code review: An empirical study on Qt](https://www.sciencedirect.com/science/article/abs/pii/S0950584924002015)

- Emerging Domains

  2022

  [Developers perception of peer code review in research software development](https://link.springer.com/article/10.1007/s10664-021-10053-x)


  2023

  [Code review guidelines for GUI-based testing artifacts](https://www.sciencedirect.com/science/article/pii/S0950584923001532)

  2025

  [Towards understanding code review practices for infrastructure-as-code: An empirical study on OpenStack projects](https://link.springer.com/article/10.1007/s10664-025-10654-w)

  [Enhancing Aerospace Software Quality with Automated Code Review](https://ieeexplore.ieee.org/document/11068615)

#### Process Efficiency and Workflow Patterns

![Process Efficiency and Workflow Patterns](./pic/Understanding/Process-Efficiency-and-Workflow-Patterns.png)


[Modern Code Reviews—Survey of Literature and Practice](https://dl.acm.org/doi/10.1145/3585004)

##### Code Velocity and Turnaround Time

2015

[Lessons learned from building and deploying a code review analytics platform](https://ieeexplore.ieee.org/abstract/document/7180079/)

2016

[Investigating technical and non-technical factors influencing modern code review](https://link.springer.com/article/10.1007/s10664-015-9366-8)

2018

[Investigating the effectiveness of peer code review in distributed software development](https://dl.acm.org/doi/abs/10.1145/3131151.3131161)

2019

[Rebasing in code review considered harmful: A large-scale empirical investigation](https://ieeexplore.ieee.org/abstract/document/8930883/)

[Improving Code Review with GitHub Issue Tracking](https://ieeexplore.ieee.org/abstract/document/10068709/)


2022

[Understanding why we cannot model how long a code review will take: an industrial case study](https://dl.acm.org/doi/abs/10.1145/3540250.3558945)

[How Developers Modify Pull Requests in Code Review](https://ieeexplore.ieee.org/abstract/document/9507319/)

[Mining code review data to understand waiting times between acceptance and merging: An empirical analysis](https://dl.acm.org/doi/abs/10.1145/3524842.3528432)

2023

[Are We Speeding Up or Slowing Down? On Temporal Aspects of Code Velocity](https://ieeexplore.ieee.org/abstract/document/10173977/)

[Learning to predict code review completion time in modern code review](https://link.springer.com/article/10.1007/s10664-023-10300-3)


2024

[Does code review speed matter for practitioners?](https://link.springer.com/article/10.1007/s10664-023-10401-z)

2025

[Are All Code Reviews the Same? Identifying and Assessing the Impact of Merge Request Deviations](https://www.computer.org/csdl/proceedings-article/icsme/2025/958700a308/2bgfUMZMqQM)

##### Review Strategies and Change Taxonomy

2014

[Modern code reviews in open-source projects: Which problems do they fix?](https://dl.acm.org/doi/abs/10.1145/2597073.2597082)

2016

[Comparing pre commit reviews and post commit reviews using process simulation](https://dl.acm.org/doi/abs/10.1145/2904354.2904362)

[A faceted classification scheme for change-based industrial code review processes](https://ieeexplore.ieee.org/abstract/document/7589787/)

2017

[Broadcast vs. unicast review technology: Does it matter?](https://ieeexplore.ieee.org/abstract/document/7927977/)

2018

[Comparing sequential and parallel code review techniques for formative feedback](https://dl.acm.org/doi/abs/10.1145/3160489.3160498)

2020

[An empirical investigation of relevant changes and automation needs in modern code review](https://link.springer.com/article/10.1007/s10664-020-09870-3)

2022

[Less is more: supporting developers in vulnerability detection during code review](https://dl.acm.org/doi/abs/10.1145/3510003.3511560)

[First come first served: the impact of file position on code review](https://dl.acm.org/doi/abs/10.1145/3540250.3549177)

[Do explicit review strategies improve code review performance?](https://dl.acm.org/doi/abs/10.1145/3379597.3387509)

[The evolution of the code during review: an investigation on review changes](https://link.springer.com/article/10.1007/s10664-022-10205-7)

[What happens in my code reviews? An investigation on automatically classifying review changes](https://link.springer.com/article/10.1007/s10664-021-10075-5)

2023

[Towards Automated Classification of Code Review Feedback to Support Analytics](https://ieeexplore.ieee.org/abstract/document/10304851/)

2025

[Peer Code Review Methods: An Experience Report from a Data Structures and Algorithms Course](https://dl.acm.org/doi/10.1145/3641554.3701799)

[A fine-grained taxonomy of code review feedback in TypeScript projects](https://link.springer.com/article/10.1007/s10664-024-10604-y)


##### Information Needs and Supporting Materials

2015

[The impacts of supporting materials on code reading: A controlled experiment](https://ieeexplore.ieee.org/abstract/document/7467287/)

[Characteristics of useful code reviews: An empirical study at microsoft](https://ieeexplore.ieee.org/abstract/document/7180075/)

2016

[Code review quality: How developers see it](https://dl.acm.org/doi/abs/10.1145/2884781.2884840)

2017

[On the optimal order of reading source code changes for review](https://ieeexplore.ieee.org/abstract/document/8094433/)

[What are they talking about? Analyzing code reviews in pull-based development model](https://link.springer.com/article/10.1007/s11390-017-1783-2)

[The choice of code review process: A survey on the state of the practice](https://link.springer.com/chapter/10.1007/978-3-319-69926-4_9)

2018

[Communicative intention in code review questions](https://ieeexplore.ieee.org/abstract/document/8530057/)

[Information needs in contemporary code review](https://dl.acm.org/doi/abs/10.1145/3274404)

[An empirical study of design discussions in code review](https://dl.acm.org/doi/abs/10.1145/3239235.3239525)

2019

[Associating working memory capacity and code change ordering with code review performance](https://link.springer.com/article/10.1007/s10664-018-9676-8)

[Using auxiliary artifacts during code inspection activity: findings from an exploratory study](https://dl.acm.org/doi/abs/10.1145/3364641.3364658)

[The review linkage graph for code review analytics: A recovery approach and empirical study](https://dl.acm.org/doi/abs/10.1145/3338906.3338949)

[Understanding developer commenting in code reviews](https://search.ieice.org/bin/summary.php?id=e102-d_12_2423)

2021

[Understanding shared links and their intentions to meet information needs in modern code review: A case study of the OpenStack and Qt projects](https://link.springer.com/article/10.1007/s10664-021-09997-x)

[An exploratory study on confusion in code reviews](https://link.springer.com/article/10.1007/s10664-020-09909-5)

2022

[Understanding code snippets in code reviews: A preliminary study of the openstack community](https://dl.acm.org/doi/abs/10.1145/3524610.3527884)

2024 

[Demystifying code snippets in code reviews: a study of the OpenStack and Qt communities and a practitioner survey](https://link.springer.com/article/10.1007/s10664-024-10484-2)

[What makes a code review useful to opendev developers? an empirical investigation](https://link.springer.com/article/10.1007/s10664-023-10411-x)

[Understanding Developer-Analyzer Interactions in Code Reviews](https://dl.acm.org/doi/10.1145/3691620.3695257)

2025

[Understanding Practitioners’ Expectations on Clear Code Review Comments](https://dl.acm.org/doi/10.1145/3728931)

[Explaining Explanations: An Empirical Study of Explanations in Code Reviews](https://dl.acm.org/doi/10.1145/3708518)

[Code Review Comprehension: Reviewing Strategies Seen Through Code Comprehension Theories](https://www.computer.org/csdl/proceedings-article/icpc/2025/022300a589/27CwLeFtXuE)

##### Process Bottlenecks and Failures

2017

[Review participation in modern code review: An empirical study of the android, Qt, and OpenStack projects](https://link.springer.com/article/10.1007/s10664-016-9452-6)

2019

[Why is my code change abandoned?](https://www.sciencedirect.com/science/article/pii/S0950584919300424)

2021

[The" shut the f** k up" phenomenon: Characterizing incivility in open source code review discussions](https://dl.acm.org/doi/abs/10.1145/3479497)

[Why security defects go unnoticed during code reviews? a case-control study of the chromium os project](https://ieeexplore.ieee.org/abstract/document/9402130/)

2022

[Using nudges to accelerate code reviews at scale](https://dl.acm.org/doi/abs/10.1145/3540250.3549104)

[Understanding the experience of code review: misalignments, attention, and units of analysis](https://dl.acm.org/doi/abs/10.1145/3530019.3530037)

2023

[Towards Better Code Reviews: Using Mutation Testing to Improve Reviewer Attention](https://ieeexplore.ieee.org/abstract/document/10169070/)


2024

[Towards Unmasking LGTM Smells in Code Reviews: A Comparative Study of Comment-Free and Commented Reviews](https://ieeexplore.ieee.org/document/10794990)

[Advancing modern code review effectiveness through human error mechanisms](https://www.sciencedirect.com/science/article/pii/S0164121224001055)

#### Human Factors and Social Interaction

![Human Factors and Social Interaction](./pic/Understanding/Human-Factors-and-Social-Interaction.png)

##### Demographic and Social Influence

2013

[The influence of non-technical factors on code review](https://ieeexplore.ieee.org/abstract/document/6671287/)

2014

[Impact of developer reputation on code review outcomes in oss projects: An empirical investigation](https://dl.acm.org/doi/abs/10.1145/2652524.2652544)

[An empirical investigation of socio-technical code review metrics and security vulnerabilities](https://dl.acm.org/doi/abs/10.1145/2661685.2661687)

[Peer review on open-source software projects: Parameters, statistical models, and theory](https://dl.acm.org/doi/abs/10.1145/2594458)

2015

[Investigating code review quality: Do people and participation matter?](https://ieeexplore.ieee.org/abstract/document/7332457/)

2016

[Factors influencing code review processes in industry](https://dl.acm.org/doi/abs/10.1145/2950290.2950323)

2017

[Code reviewing in the trenches: Challenges and best practices](https://ieeexplore.ieee.org/abstract/document/7950877/)

[WAP: Does reviewer age affect code review performance?](https://ieeexplore.ieee.org/abstract/document/8109083/)

2018

[" Was my contribution fairly reviewed?" a framework to study the perception of fairness in modern code reviews](https://dl.acm.org/doi/abs/10.1145/3180155.3180217)

2019

[Expressions of sentiments during code reviews: Male vs. female](https://ieeexplore.ieee.org/abstract/document/8667987/)

[The impact of human factors on the participation decision of reviewers in modern code review](https://link.springer.com/article/10.1007/s10664-018-9646-1)

2021

[Accept or not? an empirical study on analyzing the factors that affect the outcomes of modern code review?](https://ieeexplore.ieee.org/abstract/document/9724868/)

2022

[Engineering impacts of anonymous author code review: A field experiment](https://ieeexplore.ieee.org/abstract/document/9361116/)

2023

[Systemic gender inequities in who reviews code](https://dl.acm.org/doi/abs/10.1145/3579527)

[Code reviews in open source projects: how do gender biases affect participation and outcomes?](https://link.springer.com/article/10.1007/s10664-023-10324-9)

2024

[GenderMag Improves Discoverability in the Field, Especially for Women: An Multi-Year Case Study of Suggest Edit, a Code Review Feature](https://dl.acm.org/doi/10.1145/3597503.3639097)

2025

[Tokenized Peer Review: An Adaptive Blockchain Mechanism for Open Source Supply Chains](https://www.researchgate.net/publication/397503222_Tokenized_Peer_Review_An_Adaptive_Blockchain_Mechanism_for_Open_Source_Supply_Chains)

##### Biometrics and Cognitive Factors

2021

[iReview: an Intelligent Code Review Evaluation Tool using Biofeedback](https://ieeexplore.ieee.org/document/9700337)

2023

[Visual Expertise in Code Reviews: Using Holistic Models of Image Perception to Analyze and Interpret Eye Movements](https://dl.acm.org/doi/abs/10.1145/3588015.3589189)

[Quality evaluation of modern code reviews through intelligent biometric program comprehension](https://ieeexplore.ieee.org/abstract/document/9733211/)

[Gander: a platform for exploration of gaze-driven assistance in code review](https://dl.acm.org/doi/abs/10.1145/3588015.3589191)

2024

[Exploring the Effects of Urgency and Reputation in Code Review: An Eye-Tracking Study](https://dl.acm.org/doi/10.1145/3643916.3644425)

[Barriers for Students During Code Change Comprehension](https://dl.acm.org/doi/10.1145/3597503.3639227)

2025

[How Developers Make Decisions When Choosing Issues and Reviewing Code: An Eye Tracking GitHub Study](https://dl.acm.org/doi/10.1145/3715669.3723108)

[Towards Debiasing Code Review Support](https://ieeexplore.ieee.org/document/11024485)

[Understanding Comparative Comprehension Barriers for Students during Code Review through Simplification](https://dl.acm.org/doi/10.1145/3696630.3727249)

[Investigating the effects of PuppyCodeReview, an AI-based code review system, on students’ cognitive load](https://www.sciencedirect.com/science/article/pii/S235271102500250X)

[Code-Review-as-an-Educational-Service: A tool for Java code review in programming education](https://www.sciencedirect.com/science/article/pii/S2352711025000159)

[A GPT-Based Code Review System With Accurate Feedback for Programming Education](https://ieeexplore.ieee.org/document/11039773)

[Analyzing student perceptions and behaviors in the use of an engaging visualization dashboard for peer code review activities](https://www.sciencedirect.com/science/article/abs/pii/S0167642325001339)

[A Unified Holistic Model of Visual Perception for Code Reviews](https://dl.acm.org/doi/10.1145/3723010.3723017)

##### Communication and Collaboration

2016

[A collaborative code review platform for github](https://ieeexplore.ieee.org/abstract/document/7816585/)

[The impact of a low level of agreement among reviewers in a code review process](https://link.springer.com/chapter/10.1007/978-3-319-39225-7_8)

2019

[An empirical study of sentiments in code reviews](https://www.sciencedirect.com/science/article/pii/S0950584919301387)

2020

[Primers or reminders? The effects of existing review comments on code review](https://dl.acm.org/doi/abs/10.1145/3377811.3380385)

2021

[Anti-patterns in modern code review: Symptoms and prevalence](https://ieeexplore.ieee.org/abstract/document/9425884/)

2022

[Code reviews with divergent review scores: An empirical study of the openstack and qt communities](https://ieeexplore.ieee.org/abstract/document/9023005/)

[Interpersonal Conflicts During Code Review: Developers' Experience and Practices](https://dl.acm.org/doi/abs/10.1145/3512945)

[Destructive criticism in software code review impacts inclusion](https://dl.acm.org/doi/abs/10.1145/3555183)

2023

[Automated identification of toxic code reviews using toxicr](https://dl.acm.org/doi/abs/10.1145/3583562)

[How social interactions can affect Modern Code Review](https://www.frontiersin.org/articles/10.3389/fcomp.2023.1178040/full)

[Competencies for code review](https://dl.acm.org/doi/abs/10.1145/3579471)

2024

[Understanding and effectively mitigating code review anxiety](https://link.springer.com/article/10.1007/s10664-024-10550-9)

[Constructive Code Review: Managing the Impact of Interpersonal Conflicts in Practice](https://dl.acm.org/doi/10.1145/3639477.3639715)

##### Benefits of MCR

2013

[Convergent contemporary software peer review practices](https://dl.acm.org/doi/abs/10.1145/2491411.2491444)

2017

[Process aspects and social dynamics of contemporary code review: Insights from open source development and industrial practice at microsoft](https://ieeexplore.ieee.org/abstract/document/7484733/)

2018

[Modern code review: a case study at google](https://dl.acm.org/doi/abs/10.1145/3183519.3183525)

2020

[Knowledge transfer in modern code review](https://dl.acm.org/doi/abs/10.1145/3387904.3389270)

2021

[Code Review is just reviewing code? A qualitative study with practitioners in industry](https://dl.acm.org/doi/abs/10.1145/3474624.3477063)

[Does code review promote conformance? a study of openstack patches](https://ieeexplore.ieee.org/abstract/document/9463066/)

[What really matters in Code Review? A study about challenges and opportunities related to code review in industry](https://dl.acm.org/doi/abs/10.1145/3493244.3493255)

2022

[Symptoms of architecture erosion in code reviews: A study of two OpenStack projects](https://ieeexplore.ieee.org/abstract/document/9779696/)

[How does code reviewing feedback evolve? a longitudinal study at Dell EMC](https://dl.acm.org/doi/abs/10.1145/3510457.3513039)

2023

[On potential improvements in the analysis of the evolution of themes in code review comments](https://ieeexplore.ieee.org/abstract/document/10371592/)

[Please fix this mutant: How do developers resolve mutants surfaced during code review?](https://ieeexplore.ieee.org/abstract/document/10172345/)

2024

[A Systematic Literature Review on Recent Peer Code Review Implementation in Education](https://ieeexplore.ieee.org/document/10844661)

2025

[The upper bound of information diffusion in code review](https://link.springer.com/article/10.1007/s10664-024-10442-y)

[A Serious Game Approach to Introduce the Code Review Practice](https://onlinelibrary.wiley.com/doi/full/10.1002/smr.2750)

#### Evolution toward Human-AI Collaboration

![Evolution toward Human-AI Collaboration](./pic/Understanding/Evolution-toward-Human-AI Collaboration.png)

##### AI Capabilities and Model Performance

2023

[Generation-based code review automation: how far are we?](https://ieeexplore.ieee.org/abstract/document/10174115/)

2024

[Code Review Automation: Strengths and Weaknesses of the State of the Art](https://ieeexplore.ieee.org/abstract/document/10378848/)

[Fine-tuning and prompt engineering for large language models-based code review automation](https://www.sciencedirect.com/science/article/pii/S0950584924001289)

2025

[Exploring the Capabilities of LLMs for Code-Change-Related Tasks](https://dl.acm.org/doi/10.1145/3709358)

[Transformer Models for Code Review Comment Generation: A Performance Comparison on GitHub Data](https://ieeexplore.ieee.org/abstract/document/11203699)

[Benchmarking and Studying the LLM-based Code Review](https://arxiv.org/abs/2509.01494)

##### Integration and Practical Challenges

2020

[Effects of adopting code review bots on pull requests to oss projects](https://ieeexplore.ieee.org/abstract/document/9240622/)

[What to expect from code review bots on GitHub? a survey with OSS maintainers](https://dl.acm.org/doi/abs/10.1145/3422392.3422459)

2022

[Quality gatekeepers: investigating the effects of code review bots on pull request activities](https://link.springer.com/article/10.1007/s10664-022-10130-9)

[Understanding automated code review process and developer experience in industry](https://dl.acm.org/doi/abs/10.1145/3540250.3558950)

2023

[Generative Pre-Trained Transformer (GPT) Models as a Code Review Feedback Tool in Computer Science Programs](https://www.ccsc.org/publications/journals/NW2023.pdf#page=38)

[Suggestion bot: analyzing the impact of automated suggested changes on code reviews](https://ieeexplore.ieee.org/abstract/document/10190399/)

2024

[Tales From the Trenches: Expectations and Challenges From Practice for Code Review in the Generative AI Era](https://ieeexplore.ieee.org/document/10604721)

2025
[Automated Code Review in Practice](https://ieeexplore.ieee.org/document/11121707)

[Deep Learning-Based Code Reviews: A Paradigm Shift or a Double-Edged Sword?](https://dl.acm.org/doi/10.1109/ICSE55347.2025.00060)

##### Human-AI Alignment

2022
[How readable is model-generated code? examining readability and visual inspection of github copilot](https://dl.acm.org/doi/abs/10.1145/3551349.3560438)

2024

[On the Use of ChatGPT for Code Review: Do Developers Like Reviews By ChatGPT?](https://dl.acm.org/doi/10.1145/3661167.3661183)

2025

[Human and Machine: How Software Engineers Perceive and Engage with AI-Assisted Code Reviews Compared to Their Peers](https://www.computer.org/csdl/proceedings-article/chase/2025/387100a063/27ueyOspLt6)

[Accountability in Code Review: The Role of Intrinsic Drivers and the Impact of LLMs](https://dl.acm.org/doi/10.1145/3721127)

[AI-Driven Continuous Integration: Automating Code Review and Deployment with LLMs](https://ieeexplore.ieee.org/document/11119365)



## Cite

If you find this work useful, please cite our paper:

```
@article{yang2024survey,
  title={A Survey on Modern Code Review: Progresses, Challenges and Opportunities},
  author={Yang, Zezhou and Gao, Cuiyun and Guo, Zhaoqiang and Li, Zhenhao and Liu, Kui and Xia, Xin and Zhou, Yuming},
  journal={arXiv preprint arXiv:2405.18216},
  year={2024}
}
```





