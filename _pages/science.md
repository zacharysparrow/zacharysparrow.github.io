---
permalink: /science/
title: "Scientific Work"
classes: wide
header: 
  overlay_image: assets/images/Mount+VanHoevenberg_crop.jpeg
---

Accurate simulations of molecules and materials have the potential to greatly acellerate the development of new technologies (better solar cells, batteries, drugs, etc.). On a theoretical level, we know how to do these simulations *exactly*. The problem? Running these simulations for any interesting molecule or material would take longer than the heat death of the universe. As such, the entire field of theoretical/computational chemistry is focused on developing fast, accurate approximations to the true quantum mechanical simulations. I believe the most promising solution to this problem lies in the development of both physics-informed machine learning models and fast (linear-scaling) algorithms to apply these models to large systems. 

<!---
## Featured
### Machine Learning for Post-Consumer HDPE Valorization
Relevant Publications: *Coming soon...*  
For a given processing method, all of the mechanical properties of high density polyethylene are uniqely defined by its molecular weight distribution (MWD)---the distriution of carbon chain lengths in the polymer. Historically, the relationship between the MWD and mechanical properties has been characterized primarily by only the MWD mean and standard deviation, which are insufficient for completely describing the MWD. We developed a deep neural network model (PolyEthylene Property Predictor, PEPPr) to predict the mechanical properties of an HDPE sample given its MWD, with ~15% error. We show that PEPPr is accurate enough to guide experimental design of commercially competitive materials. Additionally, we demonstrate how PEPPr can be used to guide revalorization of recycled polymer *via* selective addition of pristine polymer to degraded samples, suggesting a route towards significantly reducing plastic waste.

### Robust Linear Scaling Computation of Quantum Mechanical Interactions
Relevant Publications: [Link](https://doi.org/10.1021/acs.jctc.2c00827)  
One of the most important components of the interaction between quantum mechanical electrons is the exchange inteologies to address complex challenges. With extensive experience in data analysis, programming, and machine learning, I am adept at extracting actionable insights from diverse datasets. I am eager to apply my unique blend of scientific expraction. Within some well-understood approximations, the exchange interaction can be computed "exactly", resulting in so-called "exact exchange". Exact exchange is in important ingrediant in many quantum chemical approximations. However, the power required to naively compute the exact exchange interaction scales cubically with the number of electrons in the system. We developed a robust, easy-to-use black-box exact exchange algorithm with controlable accuracy that scales linearly with the number of electrons. This advance extends the scope of predictive quantum chemical calculations from a few hundred atoms to tens of thousands of atoms (or more), and provides a reliable method for high-throughput generation of quantum mechanical data to train machine learning-based methods.

### Physics-Based Regularization of Data Driven Approximations
Relevant Publications: [Link](https://doi.org/10.1021/acs.jpclett.2c00643)  
Exact quantum mechanics is too computationally expensive for all but the smallest chemical systems. The most popular theoretical framework for quantum chemistry, known as density functional theory, relies on non-systematic approximations to an unknown (exact) mapping from the electron density to the corresponding electronic energy. While this mapping is unknown (and likely too computationally costly to compute), decades of research have resulted in a set of exact physical constraints on this mapping. In this work, we suggested a general framework which allows construction of data driven approximations that are regularized to satisfy physical constraints. Using this technique, we developed an approximate machine learning-based method (dubbed Contrained And Smoothed Empirical approximation 2021, CASE21) that satisfies all of the same physical constraints as one of the most popular approximations used to date. CASE21 reliably reduces the error of common quantum chemical approximations by ~15% for an extensive set of molecules and chemical properties.

### Benchmark Quantum Chemical Database Generation and Analysis
Relevant Publications: [Link](https://doi.org/10.1063/5.0068862) (*Cover Article & Editor's Choice 2021*)  
Highly accurate, benchmark-level calculations on atoms and molecules are important because they give the computational chemistry community a way to measure the accuracy of quantum chemical models that are easier to compute. We've generated two databases of this kind: one describing the interactions between two distinct molecules as they get pushed together, and one of molecules with atoms displaced beyond their most likely positions in the molecule. Both of these databases are some of the largest of their kind. We have since analyed the performance of dozens of quantum chemistry approximations using these databases. One key observation that we've made is that the mean and variance of the distribution of errors across different systems for a given approximation increases as certain quantum mechanical contributions to the property increases. The latter database has also led to a new analysis technique that decomposes error into two distinct physical components. Both of these methods provide insight into how to further improve quantum chemical models.
-->

## Publications
OrcID: [0000-0001-6163-2843](https://orcid.org/0000-0001-6163-2843)

1. **Z. M. Sparrow**, H.-Y. Ko, J. Zhang, and R. A. DiStasio Jr., *Robust Linear-Scaling Hybrid Density Functional Theory with Controllable Accuracy for Finite-Gap Condensed-Phase Systems*, in preparation.
2. **Z. M. Sparrow**, R. Kang, B. G. Ernst, R. A. DiStasio Jr., *Decomposing Conformational Energy Errors into Geometric and Potential Energy Curvature Components: Application to NECE-2025*, in preparation.
3. R. Kang, **Z. M. Sparrow**,  B. G. Ernst, R. A. DiStasio Jr., *NECE-2025. A Large Benchmark Database of Non-Equilibrium Conformational Energies*, in preparation.
4. H.-Y. Ko, J. Zhang, M. F. C. Andrade, **Z. M. Sparrow**, S. Ghosh, P. T. Lin, R. A. DiStasio Jr., *Reactive Transport of Water Ions: Presolvated Proton Donors behind the
Scenes*, in review.
5. J. Hu, **Z. M. Sparrow**, B. G. Ernst, S. M. Mattes, G. W. Coates, R. A. DiStasio Jr., B. P. Fors, *Designing Polymers with Molecular Weight Distribution
Based Machine Learning*, J. Am. Chem. Soc., 147 12 (2025). [Link](https://doi.org/10.1021/jacs.4c16325)
6. H.-Y. Ko, M. F. C. Andrade, **Z. M. Sparrow**, and R. A. DiStasio Jr., *High-Throughput Condensed-Phase Hybrid Density Functional Theory for Large-Scale Finite-Gap Systems: The SeA Approach*, J. Chem. Theory Comput., 19 13 (2023). [Link](https://doi.org/10.1021/acs.jctc.2c00827)
7. **Z. M. Sparrow**, B. G. Ernst, T. K. Quady, and R. A. DiStasio Jr., *Uniting Non-Empirical and Empirical Density Functional Approximation Strategies Using Constraint-Based Regularization*, J. Phys. Chem. Lett., 13 30 (2022). [Link](https://doi.org/10.1021/acs.jpclett.2c00643)
8. V. Prabhakaran, J. Romo, A. Bhattarai, K. George, **Z. M. Norberg**[^1], D. Kalb, E. Aprà, E., P. A. Kottke, A. G. Fedorov, P. Z. El-Khoury, G. E. Johnson, and J. Laskin, *Integrated photoelectrochemical energy storage cells prepared by benchtop ion soft landing*, Chem. Commun., 58 9060 (2022). [Link](https://doi.org/10.1039/d2cc02595g)
9. **Z. M. Sparrow**, B. G. Ernst, P. T. Joo, K. U. Lao, and R. A. DiStasio Jr., *NENCI-2021 Part I: A Large Benchmark Database of Non-Equilibrium Non-Covalent Interactions Emphasizing Close Intermolecular Contacts*, J. Chem. Phys., 155 184303 (2021). **Cover Article & Editor's Choice 2021** [Link](https://doi.org/10.1063/5.0068862)
10. M. Pearce, **Z. M. Sparrow**, T. R. Mabote, and R. Sanchez-Gonzalez; *stoBEST: An Efficient Algorithm for Increased Spatial Resolution in Two-Component Molecular Tagging Velocimetry*, Meas. Sci. Technol. 32 035302 (2021). [Link](https://doi.org/10.1088/1361-6501/abb1e4)
11. Y. Vidavsky, M. R. Buche, **Z. M. Sparrow**, X. Zhang, S. J. Yang, R. A. DiStasio Jr., and M. N. Silberstein, *Tuning the Mechanical Properties of Metallopolymers via Ligand Interactions: A Combined Experimental and Theoretical Study*, Macromolecules 53 2021 (2020). [Link](https://doi.org/10.1021/acs.macromol.9b02756)



## Talks & Presentations
1. **Z. M. Sparrow**, R. Kang, B. G. Ernst, R. M. Hendley, R. A. DiStasio Jr., *Construction and Analysis of the NECE-2024 Benchmark Non-Equilibrium Conformational Energy Database*, Institute for Pure and Applied Mathematics Advancing Quantum Mechanics with Mathematics and Statistics Reunion Conference 2, Lake Arrowhead, CA. (2024).
2. **Z. M. Sparrow**, H.-Y. Ko, Ju-an Zhang, and R. A. DiStasio Jr., *Robust Linear-Scaling Hybrid Density Functional Theory with Controllable Accuracy for Finite-Gap Condensed-Phase Systems*, Institute for Pure and Applied Mathematics Advancing Quantum Mechanics with Mathematics and Statistics Reunion Conference 1, Lake Arrowhead, CA. (2023).
3. **Z. M. Sparrow**, H.-Y. Ko, and R. A. DiStasio Jr., *Towards Routine Use of Hybrid DFT for Large-Scale Finite-Gap Condensed-Phase Systems*, Institute for Pure and Applied Mathematics Advancing Quantum Mechanics with Mathematics and Statistics Seminar Series, Los Angeles, CA. (2022).
4. **Z. M. Sparrow**, *Predicting Chemical Properties on Your Computer Using Data and Physics*, Chemistry Department Seminar, St. Olaf College, Northfield, MN. (2022).
5. **Z. M. Sparrow**, B. G. Ernst, T. K. Quady, and R. A. DiStasio Jr., *Uniting non-empirical and semi-empirical density functional approximation strategies using constraint-based regularization*, American Chemical Society Spring Meeting, San Diego, CA. (2022).
6. **Z. M. Sparrow**, B. G. Ernst, P. T. Joo, K. U. Lao, R. A. DiStasio Jr., *NENCI-2021: A Large Benchmark Database of Non-Equilibrium Non-Covalent Interactions Emphasizing Close Intermolecular Contacts*, American Physical Society March Meeting, Online. (2021).
7. **Z. M. Sparrow**, B. G. Ernst, P. T. Joo, K. U. Lao, R. A. DiStasio Jr., *NENCI-2020: A Large Benchmark Database of Non-Equilibrium Non-Covalent Interactions with an Emphasis on Close Contacts*, American Physical Society March Meeting, Denver, CO. (2020) (cancelled)
8. **Z. M. Norberg**[^1], M. Pearce, S. Hoops, O. Dmytrenko, M. Richey, and R. Sanchez-Gonzalez, *An Efficient Algorithm for Increased Spatial Resolution in Two-Component Molecular Tagging Velocimetry*, National Conference on Undergraduate Research, Memphis, TN. (2017)
9. **Z. M. Norberg**[^1], V. Prabhakaran, J. Laskin, *Fabrication and Optimization of an Integrated Photoelectrochemical Device Using Ion Soft-Landing*, Pacific Northwest National Laboratory Summer Research Symposium, Richland, WA. (2016)








[^1]: Last name changed from Norberg to Sparrow




