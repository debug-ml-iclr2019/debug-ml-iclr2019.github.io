# Overview
Machine learning (ML) models are increasingly being employed to make highly consequential decisions pertaining to employment, bail, parole, and lending. While such models can learn from large amounts of data and are often very scalable, their applicability is limited by certain safety challenges. A key challenge is identifying and correcting systematic patterns of mistakes made by ML models before deploying them in the real world.

The goal of this workshop, held at the [2019 International Conference on Learning Representations (ICLR)](https://iclr.cc/), is to bring together researchers and practitioners with different perspectives on debugging ML models. Topics of interest are listed below, although we also welcome submissions that do not directly fit into these topics.

## Topics
- Debugging via **interpretability**: How can interpretable models and techniques aid us in effectively debugging ML models?

- **Program verification** as a tool for model debugging: Are existing program verification frameworks readily applicable to ML models? If not, what are the gaps that exist and how do we bridge them?

- **Visualization** tools for debugging ML models: What kind of visualization techniques would be most effective in exposing vulnerabilities of ML models?

- **Human-in-the-loop** techniques for model debugging: What are some of the effective strategies for using human input and expertise for debugging ML models?

- Novel **adversarial** attacks for highlighting errors in model behavior: How do we design adversarial attacks that highlight vulnerabilities in the functionality of ML models?

- **Theoretical correctness** of model debugging techniques: How do we provide guarantees on the correctness of proposed debugging approaches? Can we take cues from statistical considerations such as multiple testing and uncertainty to ensure that debugging methodologies and tools actually detect ‘true’ errors?

- Theoretical guarantees on the **robustness** of ML models: Given a ML model or system, how do we bound the probability of its failures?

- Insights into **errors or biases of real-world ML systems**: What can we learn from the failures of widely deployed ML systems? What can we say about debugging for different types of biases, including discrimination? 

- **Best practices** for debugging large-scale ML systems: What are standardized best practices for debugging large-scale ML systems? What are existing tools, software, and hardware, and how might they be improved? 

## Important Dates
- **Submission deadline**: ~~March 1, 2019, 11.59pm~~. March 2, 2019, 11.59pm Pacific Time. If you miss the deadline by a few hours, email us the submission at debugging.ml@gmail.com and we will consider it on a case-to-case basis. 
- **Acceptance notification**: March 18, 2019 (before ICLR early registration deadline)
- **Camera-ready deadline** for accepted papers: April 10, 2019
- **Workshop**: Monday May 6th 09:00 AM -- 06:00 PM @ Room R3

If you are a student or postdoc, we encourage you to apply for ICLR’s [volunteer](https://iclr.cc/accounts/login/?next=/Volunteers/volunteerapplication) and [travel grants](https://iclr.cc/accounts/login/?next=/TravelApplication) before their March 13 deadline. If you need a visa to travel to the US, consider submitting your paper before the submission deadline. Then contact us so that we can fast track reviewing of your paper. 

## Submission Instructions
- Submission page: [https://easychair.org/conferences/?conf=debugml19](https://easychair.org/conferences/?conf=debugml19)

- Submit anonymized papers of up to 4 pages (not including references, and an optional appendix) using the [ICLR template](https://iclr.cc/Conferences/2019/CallForPapers). The 4 page limit is strict, but references and optional appendix can be as many pages as needed. As reviewers may not read the optional appendix, it should be used sparingly for technical proofs and/or reproducibility (e.g. code, experiment details). 

- The reviewing process is double blind. Hence, please ensure that the PDF does not contain any information that could identify authors or institutions. Do not put author names or institutions in the filename of the PDF. 

- Concurrent submission to other venues (journal, conference workshop) is allowed. Work already published in a journal,conference, or workshop should be extended in a meaningful way. 

Accepted papers will be presented as posters at the workshop. Additionally, some accepted papers will also be invited to present spotlight or oral talks at the workshop. Selected papers will be recognized with **Best Research Paper**, **Best Applied Paper**, **Best Student Paper** awards. Camera-ready versions of accepted papers will be uploaded to the conference website (unless requested not to), but there will be no formal published proceedings. 

Please email [debugging.ml@gmail.com](mailto:debugging.ml@gmail.com) with any questions.

# Confirmed Speakers & Panelists
- [Cynthia Rudin](https://users.cs.duke.edu/~cynthia/) (Duke University)
- [Sameer Singh](http://sameersingh.org/) (University of California, Irvine)
- More to come soon, covering the different perspectives of the workshop

# Tentative Schedule

| Time | Event |
| --- | --- |
| 8:50 - 9:00 | Introductory Remarks from Organizers |
| 9:00 - 9:40 | Invited talk 1 (30-40 mins talk including 5 mins questions) |
| 9:40 - 10:00 | Contributed oral talk |
| 10:00 - 10:15 | Break |
| 10:15 - 10:55 | Invited talk 2 |
| 10:55 - 11:10 | 3 spotlight contributed talks (5 mins each) |
| 11.10 - 12.00 | First poster session |
| 12.00 - 1.15 | Lunch |
| 1.15 - 1.45 | Opinion piece (Cynthia Rudin): Interpretability and debugging? | 
| 1.45 pm - 2.00 | Floor discussion (for opinion piece) | 
| 2.00 pm - 2.40 | Invited talk 3 |
| 2.40 pm - 2.55 | Break |
| 2.55 pm - 3.40 | Panel (Different perspectives on debugging ML models) |
| 3.40 pm - 4.00 | Contributed oral talk |
| 4.00 pm - 4.40 | Invited talk 4 |
| 4.40 pm - 5.30 | Second poster session |

## Organizers
- [Himabindu Lakkaraju](https://web.stanford.edu/~himalv/) (Harvard University)
- [Sarah Tan](https://shftan.github.io/) (Cornell University and UCSF)
- [Julius Adebayo](http://juliusadebayo.com/) (MIT)
- [Jacob Steinhardt](https://cs.stanford.edu/~jsteinhardt/) (Open Philanthropy Project and OpenAI)
- [D. Sculley](https://www.eecs.tufts.edu/~dsculley/) (Google)
- [Rich Caruana](https://www.microsoft.com/en-us/research/people/rcaruana/) (Microsoft Research)

## Program Committee

| --- | --- |
| Samira Abnar (University of Amsterdam) | Sara Magliacane (IBM Research) |
| David Alvarez Melis (MIT) | Momin Malik (Berkman Klein Center) |
| Forough Arabshahi (Carnegie Mellon University) | Matthew Mcdermott (MIT) |
| Kamyar Azzizzadenesheli (UC Irvine) | Smitha Milli (UC Berkeley) |
| Gagan Bansal (University of Washington) | Shira Mitchell |
| Osbert Bastani (University of Pennsylvania) | Tristan Naumann (Microsoft Research) |
| Joost Bastings (University of Amsterdam) | Besmira Nushi (Microsoft Research) |
| Andrew Beam (Harvard University) | Saswat Padhi (UCLA) |
| Kush Bhatia (UC Berkeley) | Emma Pierson (Stanford University) |
| Umang Bhatt (Carnegie Mellon University) | Forough Poursabzi-Sangdeh (Microsoft Research) |
| Sam Corbett-Davies (Stanford University) | Manish Raghavan (Cornell University) |
| Amit Dhurandhar (IBM Research) | Ramya Ramakrishnan (MIT) |
| Samuel Finlayson (Harvard Medical School, MIT) | Alexander Ratner (Stanford University) |
| Tian Gao (IBM Research) | Andrew Ross (Harvard University) |
| Efstathios Gennatas (UCSF) | Shibani Santurkar (MIT) |
| Albert Gordo (Facebook) | Prasanna Sattigeri (IBM Research) |
| Ben Green (Harvard University) | Peter Schulam (Johns Hopkins University) |
| Jayesh Gupta (Stanford University) | Camelia Simoiu (Stanford University) |
| Satoshi Hara (Osaka University) | Sameer Singh (UC Irvine) |
| Tatsunori Hashimoto (MIT) | Alison Smith-Renner (University of Maryland) |
| He He (NYU) | Jina Suh (Microsoft Research) |
| Fred Hohman (Georgia Institute of Technology) | Adith Swaminathan (Microsoft Research) |
| Lily Hu (Harvard University) | Michael Tsang (University of Southern California) |
| Xiaowei Huang (University of Liverpool) | Dimitris Tsipras (MIT) |
| Yannet Interian (University of San Francisco) | Berk Ustun (Harvard University) |
| Saumya Jetley (University of Oxford) | Gilmer Valdes (UCSF) |
| Shalmali Joshi (Vector Institute) | Paroma Varma (Stanford University) |
| Yannis Kalantidis (Facebook) | Kush Varshney (IBM Research) |
| Ece Kamar (Microsoft Research) | Fulton Wang (Sandia National Labs) |
| Madian Khabsa (Apple) | Yang Wang (Uber) |
| Heidy Khlaaf (University College London) | Fanny Yang (ETH Zurich) |
| Pang Wei Koh (Stanford University) | Muhammad Bilal Zafar (Bosch Center for Artificial Intelligence) |
| Josua Krause (Accern) | Xuezhou Zhang (University of Wisconsin-Madison) |
| Ram Kumar (Microsoft / Berkman Klein Center) | Xin Zhang (MIT) |
| Isaac Lage (Harvard University) | Cristian Canton (Facebook) |
| Finnian Lattimore (Australian National University) | Grzegorz Chrupala (Tilburg University) |
| Lezhi Li (Uber) | Jason Yosinski (Uber) |
| Anqi Liu (Caltech) | Siongthye Goh (Singapore Management University) |
| Yin Lou (Ant Financial) | Ravi Shroff (NYU) |
| David Madras (University of Toronto / Vector Institute) |  |
