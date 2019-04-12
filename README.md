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

## Invited Speakers & Panelists
- [Cynthia Rudin](https://users.cs.duke.edu/~cynthia/) (Duke University)
- [Sameer Singh](http://sameersingh.org/) (University of California, Irvine)
- [Suchi Saria](https://suchisaria.jhu.edu/) (Johns Hopkins University)
- [Dan Moldovan](https://ai.google/research/people/DanMoldovan) (Google -- TensorFlow AutoGraph project)
- [Aleksander Madry](https://people.csail.mit.edu/madry/) (MIT)
- [Osbert Bastani](https://obastani.github.io/) (University of Pennsylvania)
- [Deborah Raji](https://www.linkedin.com/in/deborah-raji-065751b2/) (University of Toronto)

## Contributed Talks
- Michela Paganini (Facebook), Jessica Zosa Forde. The Scientific Method in the Science of Machine Learning
- Simon Kornblith, Mohammad Norouzi, Honglak Lee, Geoffrey Hinton (Google). Similarity of Neural Network Representations Revisited
- Tomer Arnon, Christopher Lazarus (Stanford), Changliu Liu (CMU), Mykel Kochenderfer (Stanford). NeuralVerification.jl: Algorithms for Verifying Deep Neural Networks
- Daniel Kang, Deepti Raghavan, Peter Bailis, Matei Zaharia (Stanford). Debugging Machine Learning via Model Assertions
- More to be announced from Debugging-in-Practice track

## Contributed Posters and Demos
- Research Track [accepted posters](https://docs.google.com/document/d/1yfyekuaF6Yb2O3nDNtDk5-EbHlpOAF3FS-G5dHoGMZA). Note for accepted Research Track authors: if you wish, you may bring an interactive demo to accompany your poster and present both side-by-side at the poster session. 
- Research Track [call for submissions (deadline now passed)](https://docs.google.com/document/d/17ccUz0F1kD9JEQC1LIrBeJNpH3xTf2w-esZWyZMjsto)
- Debugging-in-Practice Track accepted demos: to be announced
- Debugging-in-Practice Track [call for submissions (deadline now passed)](https://docs.google.com/document/d/1vrhn7FhsCbYULF5To-Hgcec9s8kpMR5K7jhQtFzsjRo)

Please email [debugging.ml@gmail.com](mailto:debugging.ml@gmail.com) any questions.

## Schedule
- Please see https://docs.google.com/document/d/1RoeyDLNup6Ym9ZEJhnMu3z720-5U8LK3FoUfVkUoC0c (https://docs.google.com/document/d/1RoeyDLNup6Ym9ZEJhnMu3z720-5U8LK3FoUfVkUoC0c)

## Sponsors
<a href="https://openai.com/">
<img alt="OpenAI logo" src="openai-logo-horizontal-dimensional-purple.png" width="50%" height="auto">
</a>

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
| Marco Tulio Ribeiro (Microsoft Research) | |
