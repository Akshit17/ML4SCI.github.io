---
title: Implementation of Quantum Variational Autoencoders to Perform High Energy Physics Analysis at the LHC
layout: gsoc_proposal
project: QMLHEP
year: 2023
organization:
 - Alabama
 - Waterloo
 - Brown
 - EPFL
---

## Description
The ambitious [HL-LHC](https://hilumilhc.web.cern.ch) program will require enormous computing resources in the next two decades. New technologies are being sought after to replace the present computing infrastructure. A burning question is whether quantum computer can solve the ever growing demand of computing resources in High Energy Physics (HEP) in general and physics at [LHC](https://home.cern/science/accelerators/large-hadron-collider) in particular. Our goal here is to explore and to demonstrate that Quantum Computing can be the new paradigm (Proof of Principle).

Discovery of new physics requires the identification of rare signals against immense backgrounds. Development of machine learning methods will greatly enhance our ability to achieve this objective. However, with this ever-growing volume of data in the near future, current machine learning algorithms will require large computing resources and excessive computing time to achieve good performance. Quantum Computing in Qubit platform, where qubits are used instead of bits in classical computer, has the potential to improve the time complexity of classical algorithms.

With this project we seek to implement Quantum Machine Learning methods for LHC HEP analysis based on Google TensorFlow Quantum (“TF Quantum is an open source library for quantum machine learning”). This will enhance the ability of the HEP community to use Quantum Machine Learning methods. In addition, if possible, we also would like to develop a common QML interface for HEP which can support different quantum frameworks such as TensorFlow Quantum.

## Duration

Total project length: 175 hours.

## Task ideas
  * Implement a Quantum Variational Autoencoder (QVAE) method based on Google Tensorflow Quantum framework.
  * Apply the quantum machine learning method to one LHC flagship physics channel (e.g. double-Higgs production). Compare the quantum machine learning performance to the classical machine learning performance.
 
## Expected results
  * Trained Quantum Variational Autoencoder method based on Google TensorFlow Quantum framework.
  * Successfully apply the Quantum Machine Learning method to LHC physics analyses and obtain performance benchmarks to compare to classical machine learning methods.
  
<!-- ## Test

Please use [this link](https://docs.google.com/document/d/e/2PACX-1vSeQWHXbf-87eCPcEj-LcYEcBpPKnqCYoU0uf7PH-ou_XRdcg_xtXaP4fzSY8b_FiGMIyqsLjDNWqZD/pub) to access the test for this project. -->
  
## Requirements 
  * Solid knowledge of machine learning and deep learning
  * Some knowledge of quantum mechanics desired
  * Familiarity with c/c++
  * Strong python skills


## Mentors
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Raphael Koh](mailto:ml4-sci@cern.ch) (University of Waterloo)
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (Brown University)
  * [Ali Hariri](mailto:ml4-sci@cern.ch) (EPFL)

## Links
  * [HL-LHC](https://hilumilhc.web.cern.ch)
  * [LHC](https://home.cern/science/accelerators/large-hadron-collider)
  * [TensorFlow Quantum](https://www.tensorflow.org/quantum/overview)


Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.
