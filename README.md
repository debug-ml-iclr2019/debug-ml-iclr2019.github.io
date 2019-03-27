# Overview
Machine learning (ML) models are increasingly being employed to make highly consequential decisions pertaining to employment, bail, parole, and lending. While such models can learn from large amounts of data and are often very scalable, their applicability is limited by certain safety challenges. A key challenge is identifying and correcting systematic patterns of mistakes made by ML models before deploying them in the real world.

The goal of this workshop, held at the [2019 International Conference on Learning Representations (ICLR)](https://iclr.cc/), is to bring together researchers and practitioners with different perspectives on debugging ML models. Topics of interest are listed below.

### Topics
- Debugging via **interpretability**: How can interpretable models and techniques aid us in effectively debugging ML models?

- **Program verification** as a tool for model debugging: Are existing program verification frameworks readily applicable to ML models? If not, what are the gaps that exist and how do we bridge them?

- **Visualization** tools for debugging ML models: What kind of visualization techniques would be most effective in exposing vulnerabilities of ML models?

- **Human-in-the-loop** techniques for model debugging: What are some of the effective strategies for using human input and expertise for debugging ML models?

- Novel **adversarial** attacks for highlighting errors in model behavior: How do we design adversarial attacks that highlight vulnerabilities in the functionality of ML models?

- **Theoretical correctness** of model debugging techniques: How do we provide guarantees on the correctness of proposed debugging approaches? Can we take cues from statistical considerations such as multiple testing and uncertainty to ensure that debugging methodologies and tools actually detect ‘true’ errors?

- Theoretical guarantees on the **robustness** of ML models: Given a ML model or system, how do we bound the probability of its failures?

- Insights into **errors or biases of real-world ML systems**: What can we learn from the failures of widely deployed ML systems? What can we say about debugging for different types of biases, including discrimination? 

- **Best practices** for debugging large-scale ML systems: What are standardized best practices for debugging large-scale ML systems? What are existing tools, software, and hardware, and how might they be improved? 

## Organizers
- [Himabindu Lakkaraju](https://web.stanford.edu/~himalv/) (Harvard University)
- [Sarah Tan](https://shftan.github.io/) (Cornell University and UCSF)
- [Julius Adebayo](http://juliusadebayo.com/) (MIT)
- [Jacob Steinhardt](https://cs.stanford.edu/~jsteinhardt/) (Open Philanthropy Project and OpenAI)
- [D. Sculley](https://www.eecs.tufts.edu/~dsculley/) (Google)
- [Rich Caruana](https://www.microsoft.com/en-us/research/people/rcaruana/) (Microsoft Research)

## Confirmed Invited Speakers & Panelists
- [Cynthia Rudin](https://users.cs.duke.edu/~cynthia/) (Duke University)
- [Sameer Singh](http://sameersingh.org/) (University of California, Irvine)
- [Suchi Saria](https://suchisaria.jhu.edu/) (Johns Hopkins University)
- [Dan Moldovan](https://ai.google/research/people/DanMoldovan) (Google -- TensorFlow AutoGraph project)
- [Aleksander Madry](https://people.csail.mit.edu/madry/) (MIT)
- [Osbert Bastani](https://obastani.github.io/) (University of Pennsylvania)
- [Deborah Raji](https://www.linkedin.com/in/deborah-raji-065751b2/) (University of Toronto)
- More to come soon, covering the different perspectives of the workshop

## Contributed Papers
- Research track: [List of accepted papers](https://docs.google.com/document/d/1yfyekuaF6Yb2O3nDNtDk5-EbHlpOAF3FS-G5dHoGMZA). [Call for papers (deadline now passed)](https://docs.google.com/document/d/17ccUz0F1kD9JEQC1LIrBeJNpH3xTf2w-esZWyZMjsto)
- Debugging-in-Practice Track: Submissions accepted until April 1, 2019. See below for instructions. 

## Call for Talks and Demos for Debugging-in-Practice Track
For this Debugging-in-Practice track, we solicit work that advances the understanding of issues related to **debugging ML models in practice**. Submissions from industry practitioners are encouraged. Accepted submissions will be presented as **talks or interactive demos**. An award will be given to the best submission in this track.

Topics of interest include but are not limited to: 

- **Success and failure stories** from deploying ML models in the real world

- **Software and hardware tools** for model debugging -- demos of tools are welcome and highly encouraged

- Understanding the **domain-specific** nuances of debugging ML models - e.g., debugging ML models in healthcare, criminal justice, public policy, education, and other social good applications

- Best practices for **debugging large-scale ML systems in industry**

### Important Dates
- **Submission deadline**: April 1, 2019, 11.59pm Anywhere on Earth (AoE) time
- **Acceptance notification**: April 12, 2019 (before ICLR registration cancellation deadline)
- **Camera-ready deadline for accepted extended abstracts**: April 25, 2019
- **Workshop**: Monday May 6th 09:45 AM – 06:30 PM @ Room R3

If you need a visa to travel to the US, consider submitting your work before the submission deadline. Then contact us so that we can fast track reviewing of your work. If you need more time to prepare your submission, please contact us early on and we will see what we can do.

### Submission Instructions
- Submission page: [https://easychair.org/conferences/?conf=debugml19](https://easychair.org/conferences/?conf=debugml19)
- In EasyChair, you will be asked to select if you would like to present your work, if accepted, as a talk (7-15 minutes) during a Debugging-in-Practice session at the workshop, or as an interactive demo during a Posters & Demos session, or both.
- Submit extended abstracts of 1 page (not including references, and an optional appendix) using any template with minimum 11 point font and page margins of at least 1 inch. The 1-page limit is strict, but references and optional appendix (e.g. for screenshots, video links, etc.) can be as many pages as needed. As reviewers may not read the optional appendix, the extended abstract should standalone. 
- If you intend to present your work as a demo, we strongly encourage you to provide screenshots of the demo in the optional appendix. 
- The reviewing process is not blind, hence you do not need to anonymize your submission. Links to software implementations need not be anonymized. 
- Concurrent submission to other venues is allowed. Work already published or made public in some form will also be considered. 

Camera-ready versions of extended abstracts will be uploaded to the conference website (unless requested not to), but there will be no formal published proceedings.

Please email [debugging.ml@gmail.com](mailto:debugging.ml@gmail.com) any questions.

## Tentative Schedule

| Time | Event |
| --- | --- |
| 9.50 - 10.00 | Opening remarks |
| 10.00 - 10.30 | Research invited talk 1 |
| 10.30 - 10.40 | Contributed talk |
| 10.40 - 10.50 | Contributed talk/demo | 
| 10.50 - 11.10 | Coffee break (main conference coffee break 10.30-11) |
| 11.10 - 11.40 | Research invited talk 2 |
| 11.40 - 11.50 | Contributed talk |
| 11.50 - 12.00 | Contributed talk/demo | 
| 12.00 - 12.10 | Break |
| 12.10 - 12.40 | Research invited talk 2 |
| 12.40 - 1.00 | Practical invited talk 1 |
| 1.00 - 2.30 | Lunch (Main conference lunch until 2.30) |
| 2.30 - 3.20 | Break in workshop schedule (main conference invited talk) |
| 3.20 - 3.25 | Welcome back remarks |
| 3.25 - 3.55 | Research invited talk 4 |
| 3.55 - 4.15 | Practical invited talk 2 |
| 4.15 - 5.15 | Posters & Interactive Demos + Coffee Break (main conference coffee break 4-4.30)|
| 5.15 - 5.25 | Contributed talk/demo | 
| 5.25 - 5.55 | Opinion piece (Cynthia Rudin): Interpretability and debugging? |
| 5.55 - 6.15 | Floor discussion for opinion piece + informal panel on perspectives on debugging | 
| 6.15 - 6.25 | Closing remarks |

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
| Sam Corbett-Davies (Facebook) | Forough Poursabzi-Sangdeh (Microsoft Research) |
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
| Madian Khabsa (Facebook) | Fulton Wang (Sandia National Labs) |
| Heidy Khlaaf (Adelard) | Yang Wang (Uber) |
| Pang Wei Koh (Stanford University) | Fanny Yang (ETH Zurich) |
| Josua Krause (Accern) | Jason Yosinski (Uber) |
| Ram Kumar (Microsoft / Berkman Klein Center) | Muhammad Bilal Zafar (Bosch Center for Artificial Intelligence) |
| Isaac Lage (Harvard University) | Xuezhou Zhang (University of Wisconsin-Madison) |
| Finnian Lattimore (Australian National University) | Xin Zhang (MIT) |
