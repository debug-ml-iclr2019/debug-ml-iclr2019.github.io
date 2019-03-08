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
- **Submission deadline**: ~~March 1, 2019, 11.59pm~~. March 2, 2019, 11.59pm Pacific Time. If you miss the deadline, email us your submission at debugging.ml@gmail.com and we will consider it on a case-to-case basis.
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
- [Suchi Saria](https://suchisaria.jhu.edu/) (Johns Hopkins University)
- [Aleksander Madry](https://people.csail.mit.edu/madry/) (MIT)
- More to come soon, covering the different perspectives of the workshop

# Tentative Schedule

| Time | Event |
| --- | --- |
| 8.50 - 9.00 | Introductory Remarks from Organizers |
| 9.00 - 9.30 | Invited talk 1 |
| 9.30 - 9.45 | Oral contributed talk 1 (best paper) |
| 9.45 - 10.15 | Invited talk 2 | 
| 10.15 - 10.30 | Coffee break |
| 10.30 - 11.00 | Invited talk 3 |
| 11.00 - 11.15 | Oral contributed talk 2 (best paper) |
| 11.15 - 11.45 | Opinion piece (Cynthia Rudin): Interpretability and debugging? |
| 11.45 - 12.00 | Floor discussion for opinion piece | 
| 12.00 - 1.15 | Lunch |
| 1.15 - 1.45 | Invited talk 4 |
| 1.45 - 2.00 | Spotlight contributed talks |
| 2.00 - 2.30 | Panel |
| 2.30 - 2.45 | Oral contributed talk 3 (best paper) |
| 2.45 - 3.45 | Poster session and Coffee break |
| 3.45 - 4.15 | Invited talk 5 |
| 4.15 - 5.15 | Industry/applications forum -- talks and demos |
| 5.15 - 5.25 | Closing remarks |

## Organizers
- [Himabindu Lakkaraju](https://web.stanford.edu/~himalv/) (Harvard University)
- [Sarah Tan](https://shftan.github.io/) (Cornell University and UCSF)
- [Julius Adebayo](http://juliusadebayo.com/) (MIT)
- [Jacob Steinhardt](https://cs.stanford.edu/~jsteinhardt/) (Open Philanthropy Project and OpenAI)
- [D. Sculley](https://www.eecs.tufts.edu/~dsculley/) (Google)
- [Rich Caruana](https://www.microsoft.com/en-us/research/people/rcaruana/) (Microsoft Research)

## Program Committee

| --- | --- |
| Samira Abnar (University of Amsterdam) | Lezhi Li (Uber) |
| David Alvarez Melis (MIT) | Anqi Liu (Caltech) |
| Forough Arabshahi (Carnegie Mellon University) | Yin Lou (Ant Financial) |
| Kamyar Azzizzadenesheli (UC Irvine) | David Madras (University of Toronto / Vector Institute) |
| Gagan Bansal (University of Washington) | Sara Magliacane (IBM Research) |
| Osbert Bastani (University of Pennsylvania) | Momin Malik (Berkman Klein Center) |
| Joost Bastings (University of Amsterdam) | Matthew Mcdermott (MIT) |
| Andrew Beam (Harvard University) | Smitha Milli (UC Berkeley) |
| Kush Bhatia (UC Berkeley) | Shira Mitchell () |
| Umang Bhatt (Carnegie Mellon University) | Tristan Naumann (Microsoft Research) |
| Cristian Canton (Facebook) | Besmira Nushi (Microsoft Research) |
| Arthur Choi (UCLA) | Saswat Padhi (UCLA) |
| Grzegorz Chrupala (Tilburg University) | Emma Pierson (Stanford University) |
| Sam Corbett-Davies (Stanford University) | Forough Poursabzi-Sangdeh (Microsoft Research) |
| Amit Dhurandhar (IBM Research) | Manish Raghavan (Cornell University) |
| Samuel Finlayson (Harvard Medical School, MIT) | Ramya Ramakrishnan (MIT) |
| Tian Gao (IBM Research) | Alexander Ratner (Stanford University) |
| Efstathios Gennatas (UCSF) | Andrew Ross (Harvard University) |
| Siongthye Goh (Singapore Management University) | Shibani Santurkar (MIT) |
| Albert Gordo (Facebook) | Prasanna Sattigeri (IBM Research) |
| Ben Green (Harvard University) | Peter Schulam (Johns Hopkins University) |
| Jayesh Gupta (Stanford University) | Ravi Shroff (NYU) |
| Satoshi Hara (Osaka University) | Camelia Simoiu (Stanford University) |
| Tatsunori Hashimoto (MIT) | Sameer Singh (UC Irvine) |
| He He (NYU) | Alison Smith-Renner (University of Maryland) |
| Fred Hohman (Georgia Institute of Technology) | Jina Suh (Microsoft Research) |
| Lily Hu (Harvard University) | Adith Swaminathan (Microsoft Research) |
| Xiaowei Huang (University of Liverpool) | Michael Tsang (University of Southern California) |
| Yannet Interian (University of San Francisco) | Dimitris Tsipras (MIT) |
| Saumya Jetley (University of Oxford) | Berk Ustun (Harvard University) |
| Shalmali Joshi (Vector Institute) | Gilmer Valdes (UCSF) |
| Yannis Kalantidis (Facebook) | Paroma Varma (Stanford University) |
| Ece Kamar (Microsoft Research) | Kush Varshney (IBM Research) |
| Madian Khabsa (Apple) | Fulton Wang (Sandia National Labs) |
| Heidy Khlaaf (Adelard) | Yang Wang (Uber) |
| Pang Wei Koh (Stanford University) | Fanny Yang (ETH Zurich) |
| Josua Krause (Accern) | Jason Yosinski (Uber) |
| Ram Kumar (Microsoft / Berkman Klein Center) | Muhammad Bilal Zafar (Bosch Center for Artificial Intelligence) |
| Isaac Lage (Harvard University) | Xuezhou Zhang (University of Wisconsin-Madison) |
| Finnian Lattimore (Australian National University) | Xin Zhang (MIT) |
