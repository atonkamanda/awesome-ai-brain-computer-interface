# AI for Brain-Computer interface


![](https://img.shields.io/github/last-commit/atonkamanda/awesome-ai-brain-computer-interface?color=green) ![](https://img.shields.io/badge/PaperNumber-54-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 

A curated list of resources dedicated to AI (ML/DL/RL) applied to brain-computer interfaces.

For several years now, as hardware and learning methods have been perfected, the applications of AI to brain-machine interfaces have become more and more numerous. The brain is a highly complex system The brain is a complex system and learning algorithms are probably the only technique that will allow BCIs to develop to their full potential .

I strongly encourage people interested in the fields to make **pull request** to update their paper's information! 

## Contents

Must-read papers on AI for Brain computer interfaces.

- [AI for BCI papers](#promptpapers)
  - [Introduction](#introduction)
    - [Keywords Convention](#keywords-convention)
  - [Papers](#papers)
    - [Overview](#overview)
    - [Pilot Work](#pilot-work)
    - [Related](#Related)
  - [Contribution](#contribution)
    - [Other contributors](#other-contributors)
    - [Contributing to this paper list](#contributing-to-this-paper-list)




## Introduction

This is a list of articles about **AI for brain-computer interface**. 

I have tried to include both major papers from the biomedical field - **curing epilepsy, restoring sight to the blind, curing paraplegic, restoring the sense of touch via a robotic prosthesis** - as well as more theoretical and conceptual papers - **the brain as a non linear dynamical system,inferring latent variable from recordings,multi-agent framework...** because I think both are relevant to the field.

I spend a lot of time reading all the articles to make sure the tags match what is described in the article. If you see an error, please let me know. I will be updating this list regularly with incoming literature, so feel free to contribute as well. 

### Keywords Convention

![](https://img.shields.io/badge/BCI-brightgreen) 		   The "invasivness" of the BCI used.

![](https://img.shields.io/badge/Device-darkviolet)	    The precise device used in the paper.

![](https://img.shields.io/badge/Experiment-orange)  The type of model used for the experiment (Human/Animal/Simulation).

 ![](https://img.shields.io/badge/Interface-red)    The type of interaction between the brain and the machine (Recording/Stimulation/Bidirectional).

 ![](https://img.shields.io/badge/Conceptual-teal)  If the paper develop concepts without any particular experimentation.

### Overviews
This section contains the papers that overview the general trends in AI for brain-computer interface.

1. **Brain Co-Processors: Using AI to Restore and Augment Brain Function.** 2020 ![](https://img.shields.io/badge/Conceptual-teal)

   *Rajesh P. N. Rao* [[pdf](https://arxiv.org/abs/2012.03378)] 

2. **Computation Through Neural Population Dynamics.** 2020 ![](https://img.shields.io/badge/Conceptual-teal)

   *Saurabh Vyas,Matthew D. Golub,David Sussillo,and Krishna V. Shenoy* [[pdf](https://homes.cs.washington.edu/~mgolub/publications/2020-Vyas-ARN.pdf)]

3. **Efficient characterization of electrically evoked responses for neural interfaces.** 2019 ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Bidirectional-red)

   *Nishal Shah, Sasidhar Madugula, Pawel Hottowy, Alexander Sher, Alan Litke, Liam Paninski, E.J. Chichilnisky*  [[pdf](https://proceedings.neurips.cc/paper/2019/hash/65184321c340b4d56581ee59b58d9d56-Abstract.html)]

4. **Computational challenges and opportunities for a bi-directional artificial retina.** 2020 ![](https://img.shields.io/badge/Conceptual-teal)

   *Nishal P Shah, E. J. Chichilnisky* [[pdf](https://iopscience.iop.org/article/10.1088/1741-2552/aba8b1)]

5. **The combination of brain-computer interfaces and artificial intelligence: applications and challenges** 2020 ![](https://img.shields.io/badge/Conceptual-teal)

   *Xiayin Zhang,..,Haotian Lin* [[pdf](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7327323/)]

6. **A multi-agent control framework for co-adaptation in brain-computer interfaces**, 2013 ![](https://img.shields.io/badge/Conceptual-teal)

   *Josh S. Merel, Roy Fox, Tony Jebara, Liam Paninski* [[pdf](https://proceedings.neurips.cc/paper/2013/hash/286674e3082feb7e5afb92777e48821f-Abstract.html)]



### Pilot work
This section contains the pilot works of AI for brain computer interfaces.
1. **Using Neural Networks to Improve Cochlear Implant Speech Perception** 1987. ![](https://img.shields.io/badge/Invasive-brightgreen) ![](https://img.shields.io/badge/Cochlear_Implant-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Stimulation-red)

   *Manoel Tenorio*.  [[pdf](https://proceedings.neurips.cc/paper/1987/hash/c20ad4d76fe97759aa27a0c99bff6710-Abstract.html)]

2.  **A Novel Channel Selection System in Cochlear Implants Using Artificial Neural Network** 1995.  ![](https://img.shields.io/badge/Invasive-brightgreen) ![](https://img.shields.io/badge/Cochlear_Implant-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Stimulation-red)
   *Marwan Jabri, Raymond Wang* [[pdf](https://papers.nips.cc/paper/1995/hash/16e6a3326dd7d868cbc926602a61e4d0-Abstract.html)]


3. **An Auditory Paradigm for Brain-Computer Interfaces** 2004. ![](https://img.shields.io/badge/Non_invasive-g) ![](https://img.shields.io/badge/EEG-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Recording-red) 

   *N. Hill, Thomas Lal, Karin Bierig, Niels Birbaumer, Bernhard Schölkopf*.  [[pdf](https://papers.nips.cc/paper/2004/hash/921c2dc40d0b979c2910298d2f880152-Abstract.html)]

4. **Methods Towards Invasive Human Brain Computer Interfaces** 2004. ![](https://img.shields.io/badge/Semi_Invasive-g) ![](https://img.shields.io/badge/ECoG-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Bidirectional-red) 

   *Zhengbao Jiang, Frank F. Xu, Jun Araki, Graham Neubig*.  [[pdf](https://papers.nips.cc/paper/2004/hash/98b418276d571e623651fc1d471c7811-Abstract.html)]

5. **Dynamic Bayesian Networks for Brain-Computer Interfaces** 2004. ![](https://img.shields.io/badge/Non_Invasive-g) ![](https://img.shields.io/badge/EEG_&_EMG-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Recording-red) 

   *Pradeep Shenoy, Rajesh PN Rao*.  [[pdf](https://papers.nips.cc/paper/2004/hash/daaaf13651380465fc284db6940d8478-Abstract.html)]

6. **A recurrent neural network for closed-loop intracortical brain-machine interface decoders** 2012. ![](https://img.shields.io/badge/Invasive-g) ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Recording-red) *David Sussillo,Paul Nuyujukian,Joline M Fan, Jonathan C Kao, Sergey D Stavisky, Stephen Ryu, and Krishna Shenoy*.  [[pdf](https://iopscience.iop.org/article/10.1088/1741-2560/9/2/026027)]

7. **Reducing Calibration Time For Brain-Computer Interfaces: A Clustering Approach** 2006. ![](https://img.shields.io/badge/Non_invasive-g) ![](https://img.shields.io/badge/EEG-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Recording-red) 

   *Matthias Krauledat, Michael Schröder, Benjamin Blankertz, Klaus-Robert Müller* [[pdf](https://papers.nips.cc/paper/2006/hash/275d7fb2fd45098ad5c3ece2ed4a2824-Abstract.html)]

 8.  **Adaptive Treatment of Epilepsy via Batch-mode Reinforcement Learning** 2008. ![](https://img.shields.io/badge/Invasive-g) ![](https://img.shields.io/badge/EEG_&_Deep_brain_stimulation-darkviolet) ![](https://img.shields.io/badge/Simulation-orange) ![](https://img.shields.io/badge/Bidirectionnal-red) 
 *Arthur Guez, Massimo Avoli, Joelle Pineau*.  [[pdf](https://www.cs.mcgill.ca/~jpineau/files/guez-iaai08.pdf)]


9. **Kernel-ARMA for Hand Tracking and Brain-Machine interfacing During 3D Motor Control** 2008. ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Bidirectional-red) 

   *Lavi Shpigelman, Hagai Lalazar, Eilon Vaadia*.  [[pdf](https://papers.nips.cc/paper/2008/hash/61b4a64be663682e8cb037d9719ad8cd-Abstract.html)]    
    

10. **A general framework for investigating how far the decoding process in the brain can be simplified** 2008.  ![](https://img.shields.io/badge/Invasive-g) ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Simulation-orange) ![](https://img.shields.io/badge/Recording-red) 

    *Masafumi Oizumi, Toshiyuki Ishii, Kazuya Ishibashi, Toshihiko Hosoya, Masato Okada*.  [[pdf](https://proceedings.neurips.cc/paper/2008/hash/8dd48d6a2e2cad213179a3992c0be53c-Abstract.html)]


    
 11. **Coadaptive Brain–Machine Interface via Reinforcement Learning** 2009. ![](https://img.shields.io/badge/Invasive-g) ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Bidirectional-red) 
    
      *Jack DiGiovanna, Babak Mahmoudi, Jose C. Principe,Justin C. Sanchez*. [[pdf](https://ieeexplore.ieee.org/document/4540104)]
    
12. **Optimization of Electrical Stimulation for a High-Fidelity Artificial Retina** 2017. ![](https://img.shields.io/badge/Invasive-g)  ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Bidirectional-red) 

    *Nishal P. Shah, Babak Mahmoudi, Jose Fortes, Jose C. Principe,E.J. Chichilnisky*.  [[pdf](https://ieeexplore.ieee.org/document/8716987/authors#authors)]

13. **Multiscale Semi-Markov Dynamics for Intracortical Brain-Computer Interfaces** 2017. ![](https://img.shields.io/badge/Invasive-g)  ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Recording-red) 

    *Daniel Milstein, Jason Pacheco, Leigh Hochberg, John D. Simeral, Beata Jarosiewicz, Erik Sudderth*.  [[pdf](https://papers.nips.cc/paper/2017/hash/99c5e07b4d5de9d18c350cdf64c5aa3d-Abstract.html)]

14. **Information-based Adaptive Stimulus Selection to Optimize Communication Efficiency in Brain-Computer Interfaces** 2018. ![](https://img.shields.io/badge/Non_Invasive-g)  ![](https://img.shields.io/badge/P300_speller-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Recording-red) 

    *Boyla Mainsah, Dmitry Kalika, Leslie Collins, Siyuan Liu, Chandra Throckmorton*.  [[pdf](https://proceedings.neurips.cc/paper/2018/hash/a3eb043e7bf775de87763e9f8121c953-Abstract.html)]

15. **Model-Based Design of Closed Loop Deep Brain Stimulation Controller using Reinforcement Learning** 2020. ![](https://img.shields.io/badge/Invasive-g)  ![](https://img.shields.io/badge/Deep_brain_stimulation-darkviolet) ![](https://img.shields.io/badge/Simulation-orange) ![](https://img.shields.io/badge/Bidirectional-red) 

    *Qitong Gao,..., Miroslav Pajic*.  [[pdf](https://ieeexplore.ieee.org/document/9096004)]

16. **Adversarial Domain Adaptation for Stable Brain-Machine Interfaces** 2019. ![](https://img.shields.io/badge/Invasive-g)  ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Recording-red)

    *Ali Farshchian, Juan A. Gallego, Lee E. Miller,Sara A. Sollag,Joseph P. Cohen, Yoshua Bengio*.  [[pdf](https://arxiv.org/abs/1810.00045)]

17. **Reinforcement Learning Framework for Deep Brain Stimulation Study** 2019. ![](https://img.shields.io/badge/Invasive-g)  ![](https://img.shields.io/badge/Deep_brain_stimulation-darkviolet) ![](https://img.shields.io/badge/Simulation-orange) ![](https://img.shields.io/badge/Bidirectional-red) 

    *Dmitrii Krylov, Remi Tachet, Romain Laroche, Michael Rosenblum, Dmitry V. Dylov*.  [[pdf](https://arxiv.org/abs/2002.10948)]

18. **Hierarchical Bayesian Optimization of Spatiotemporal Neurostimulations for Targeted Motor Outputs** 2020. ![](https://img.shields.io/badge/Invasive-g)  ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Bidirectional-red) 

    *Samuel Laferriere, Marco Bonizzato, Sandrine L Cote, Numa Dancause, Guillaume Lajoie*.  [[pdf](https://ieeexplore.ieee.org/document/9062604)]

 19.   **Neurolight: A Deep Learning Neural Interface for Cortical Visual Prostheses** 2020. ![](https://img.shields.io/badge/Invasive-g)  ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Human_and_simulation-orange) ![](https://img.shields.io/badge/Bidirectional-red) 

          *Antonio Lozano,.., Eduardo Fernandez* . [[pdf](https://www.researchgate.net/publication/341315898_Neurolight_A_Deep_Learning_Neural_Interface_for_Cortical_Visual_Prostheses)]


20. **Stabilizing brain-computer interfaces through alignment of latent dynamics** 2022. ![](https://img.shields.io/badge/Invasive-g)  ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Bidirectional-red) 

    *Brianna M. Karpowicz,Yahia H. Ali, Lahiru N. Wimalasena, Andrew R. Sedler, Mohammad Reza Keshtkaran, Kevin Bodkin, Xuan Ma,  Lee E. Miller,  Chethan Pandarinath*.  [[pdf](https://www.biorxiv.org/content/10.1101/2022.04.06.487388v1)]

    

21. **A Hybrid Neural Autoencoder for Sensory Neuroprostheses and Its Applications in Bionic Vision** 2022.   ![](https://img.shields.io/badge/Invasive-brightgreen) ![](https://img.shields.io/badge/Visual_prosthesis-darkviolet) ![](https://img.shields.io/badge/Artificial_neural_network-orange) ![](https://img.shields.io/badge/Bidirectional-red) 

    *Jacob Granley, Lucas Relic, Michael Beyeler*[[pdf](https://arxiv.org/abs/2205.13623)]

22. **Adapting Brain-Like Neural Networks for Modeling Cortical Visual Prostheses** 2022.   ![](https://img.shields.io/badge/Invasive-brightgreen) ![](https://img.shields.io/badge/Visual_prosthesis-darkviolet) ![](https://img.shields.io/badge/Artificial_neural_network-orange) ![](https://img.shields.io/badge/Bidirectional-red) 

    *Jacob Granley, Alexander Riedel, Michael Beyeler*[[pdf](https://arxiv.org/abs/2209.13561)]

19. **Mind Reader: Reconstructing complex images from brain activities** 2022. ![](https://img.shields.io/badge/Non_Invasive-g) ![](https://img.shields.io/badge/fMRI-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Recording-red)

    *Sikun Lin, Thomas Sprague, Ambuj K Singh* [[pdf](https://papers.nips.cc/paper_files/paper/2022/hash/bee5125b773414d3d6eeb4334fbc5453-Abstract-Conference.html)]

20. **Plug-and-Play Stability for Intracortical Brain-Computer Interfaces: A One-Year Demonstration of Seamless Brain-to-Text Communication** 2023. ![](https://img.shields.io/badge/Invasive-g) ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Recording-red)

    *Chaofei Fan, Nick Hahn, Foram Kamdar, Donald Avansino, Guy Wilson, Leigh Hochberg, Krishna V Shenoy, Jaimie Henderson, Francis Willett* [[pdf](https://papers.nips.cc/paper_files/paper/2023/hash/83a14a36de4502bac5b580db36e81858-Abstract-Conference.html)]

21. **Balancing memorization and generalization in RNNs for high performance brain-machine Interfaces** 2023. ![](https://img.shields.io/badge/Invasive-g) ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Recording-red)

    *Joseph Costello, Hisham Temmar, Luis Cubillos, Matthew Mender, Dylan Wallace, Matt Willsey, Parag Patil, Cynthia Chestek* [[pdf](https://papers.nips.cc/paper_files/paper/2023/hash/17a234c91f746d9625a75cf8a8731ee2-Abstract-Conference.html)]


22. **PPi: Pretraining Brain Signal Model for Patient-independent Seizure Detection** 2023. ![](https://img.shields.io/badge/Invasive-g) ![](https://img.shields.io/badge/SEEG-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Recording-red)

    *Zhizhang Yuan, Daoze Zhang, Yang Yang, Junru Chen, Yafeng Li* [[pdf](https://papers.nips.cc/paper_files/paper/2023/hash/dbeb7e621d4a554069a6a775da0f7273-Abstract-Conference.html)]

23. **Human-in-the-Loop Optimization for Deep Stimulus Encoding in Visual Prostheses** 2023. ![](https://img.shields.io/badge/Invasive-g) ![](https://img.shields.io/badge/Visual_prosthesis-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Bidirectional-red)

    *Jacob Granley, Tristan Fauvel, Matthew Chalk, Michael Beyeler* [[pdf](https://papers.nips.cc/paper_files/paper/2023/hash/fb06bc3abcece7b8725a8b83b8fa3632-Abstract-Conference.html)]

24. **Brain decoding: toward real-time reconstruction of visual perception** 2023. ![](https://img.shields.io/badge/Non_invasive-g) ![](https://img.shields.io/badge/MEG-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Recording-red)

    *Yohann Benchetrit, Hubert Banville, Jean-Rémi King* [[pdf](https://arxiv.org/abs/2310.19812)]
    
### Related

This section contains neuroscience/BCI related subject that don't directly refere to AI for BCI but are relevant to the subject (e.g decoding latent variable, using dynamical systems framework,bioengineering,....)


1. **Restoring Natural Sensory Feedback in Real-Time Bidirectional Hand Prostheses** 2014. ![](https://img.shields.io/badge/Invasive-g)![](https://img.shields.io/badge/Hand_prosthesis-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Bidirectional-red)
      
      *Stanisa Raspopovic,..., Silvestro Micera*  [[pdf](https://www.science.org/doi/10.1126/scitranslmed.3006820)]
 
1. **LFADS - Latent Factor Analysis via Dynamical Systems** 2016. 

      *David Sussillo, Rafal Jozefowicz, L. F. Abbott, Chethan Pandarinath*  [[pdf](https://arxiv.org/abs/1608.06315)]
 
 
2. **Using goal-driven deep learning models to understand sensory cortex** 2016. ![](https://img.shields.io/badge/Conceptual-teal) 

    *Daniel L K Yamins & James J DiCarlo*.  [[pdf](https://www.nature.com/articles/nn.4244)]
    
3. **Correlation-based model of artificially induced plasticity in motor cortex by a Bidirectional brain-computer interface** 2017 ![](https://img.shields.io/badge/Simulation-orange) ![](https://img.shields.io/badge/Bidirectional-red) 

    *Guillaume Lajoie ,Nedialko I. Krouchev,John F. Kalaska,Adrienne L. Fairhall,Eberhard E. Fetz*  [[pdf](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005343)]


3. **Inferring single-trial neural population dynamics using sequential auto-encoders** 2018  ![](https://img.shields.io/badge/Animal-orange)

    *Chethan Pandarinath ,...,David Sussillo*  [[pdf](https://www.nature.com/articles/s41592-018-0109-9)]

4. **Structure in neural population recordings: an expected byproduct of simpler phenomena?** 2017  ![](https://img.shields.io/badge/Invasive-g)![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Recording-red) 
    
    *Gamaleldin F Elsayed , John P Cunningham* [[pdf](https://www.nature.com/articles/nn.4617)]

5. **An integrated brain-machine interface platform with thousands of channels (Neuralink device launch paper)** 2019. ![](https://img.shields.io/badge/Invasive-g)![](https://img.shields.io/badge/Neuralink-darkviolet) ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Bidirectional-red)

    *Elon Musk,Neuralink* [[pdf](https://www.jmir.org/2019/10/e16194/)]


6. **From deep learning to mechanistic understanding in neuroscience: the structure of retinal prediction** 2019  ![](https://img.shields.io/badge/Human/Animal/Simulation-orange)  

    *Hidenori Tanaka, Aran Nayebi, Niru Maheswaranathan, Lane McIntosh, Stephen Baccus, Surya Ganguli* [[pdf](https://proceedings.neurips.cc/paper/2019/hash/eeaebbffb5d29ff62799637fc51adb7b-Abstract.html)]

7. **Structure in neural population recordings: an expected byproduct of simpler phenomena?** 2019. ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Recording-red)

    *Gamaleldin F Elsayed & John P Cunningham* [[pdf](https://www.nature.com/articles/nn.4617)]

8. **A deep learning framework for neuroscience** 2019. ![](https://img.shields.io/badge/Conceptual-teal)

   *Blake .A Richards & Konrad P. Kording* [[pdf](https://www.nature.com/articles/s41593-019-0520-2)]
   
8. **Neural population control via deep image synthesis** 2019. ![](https://img.shields.io/badge/Non_invasive-brightgreen)

   *Pouya Bashivan, Kohitij Kar, James J Dicarlo* [[pdf](https://www.science.org/doi/10.1126/science.aav9436)]

9. **Generative Models of Brain Dynamics -- A review** 2021 ![](https://img.shields.io/badge/Conceptual-teal) 
      
      *Mahta Ramezanian Panahi, Germán Abrevaya, Jean-Christophe Gagnon-Audet, Vikram Voleti, Irina Rish, Guillaume Dumas* 
      [[pdf](https://arxiv.org/abs/2112.12147)]

10. **A brain-computer interface that evokes tactile sensations improves robotic arm control** 2021 ![](https://img.shields.io/badge/Invasive-g)![](https://img.shields.io/badge/Prototype_implant-darkviolet) ![](https://img.shields.io/badge/Human-orange) ![](https://img.shields.io/badge/Bidirectional-red) 
    
      *Sharlene N. Flesher,..,Robert A. Gaunt* [[pdf](https://www.science.org/doi/10.1126/science.abd0380)]

11. **Mine Your Own vieW: Self-Supervised Learning Through Across-Sample Prediction** 2021. ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Recording-red) 

    *Mehdi Azabou,Eva L. Dyer* [[pdf](https://arxiv.org/abs/2102.10106)]

12. **Drop, Swap, and Generate: A Self-Supervised Approach for Generating Neural Activity** 2021. ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Recording-red) 

    *Ran Liu,Mehdi Azabou, Max Dabagia, Chi-Heng Lin, Mohammad Gheshlaghi Azar, Keith B. Hengen, Michal Valko, Eva L. Dyer* 
    [[pdf](https://arxiv.org/abs/2111.023386)]


12. **Latent Factors and Dynamics in Motor Cortex and Their Application to Brain–Machine Interfaces** 2021. ![](https://img.shields.io/badge/Invasive-g)  ![](https://img.shields.io/badge/Deep_brain_stimulation-darkviolet) ![](https://img.shields.io/badge/Simulation-orange) ![](https://img.shields.io/badge/Bidirectional-red)   

    *Chethan Pandarinath, K. Cora Ames, Abigail A. Russo, Ali Farshchian, Lee E. Miller, Eva L. Dyer and Jonathan C. Kao*
      [[pdf](https://www.jneurosci.org/content/38/44/9390)]

    

13. **Neural Latents Benchmark '21: Evaluating latent variable models of neural population activity** 2021. ![](https://img.shields.io/badge/Invasive-g) ![](https://img.shields.io/badge/Animal-orange)![](https://img.shields.io/badge/Recording-red) 

    *Felix Pei,..,Chethan Pandarinath* [[pdf](https://arxiv.org/abs/2109.04463)]

    


14. **Comparing high-dimensional neural recordings by aligning their low-dimensional latent representations** 2022. ![](https://img.shields.io/badge/Conceptual-teal) 

      *Max Dabagia, Konrad P Kording, Eva L Dyer* [[pdf](https://arxiv.org/abs/2205.08413)]

    

15. **The application of artificial intelligence to biology and neuroscience** 2022. ![](https://img.shields.io/badge/Conceptual-teal)

    *Blake Richards, Doris Tsao, Anthony Zador* [[pdf](https://www.sciencedirect.com/science/article/pii/S0092867422007991)] 

16. **A Unified, Scalable Framework for Neural Population Decoding** 2023. ![](https://img.shields.io/badge/Invasive-g) ![](https://img.shields.io/badge/Utah_array-darkviolet) ![](https://img.shields.io/badge/Animal-orange) ![](https://img.shields.io/badge/Recording-red)

    *Mehdi Azabou, Vinam Arora, Venkataramana Ganesh, Ximeng Mao, Santosh Nachimuthu, Michael J. Mendelson, Blake Richards, Matthew G. Perich, Guillaume Lajoie, Eva L. Dyer* [[pdf](https://arxiv.org/abs/2310.16046)]




## Contribution


### Contributing to this paper list
   - First, think about which category the work should belong to. 
   - Second, use the same format as the others to discribe the work. Note that there should be an empty line between the title and the authors list, and take care of the indentation.
   - Then, add [keywords tags](#keywords-convention). Add the pdf link of the paper. I

   **Don't worry if you put all these wrong, we will fix them for you.** Just contribute and promote your awesome work here! 

Thanks to https://github.com/thunlp/PromptPapers for their awesome template !.
