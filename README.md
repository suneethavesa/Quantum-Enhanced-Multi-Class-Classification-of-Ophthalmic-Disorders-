Quantum-Enhanced Multi-Class Classification of Ophthalmic Disorders Using a Hybrid Transfer Learning Approach
 
 
Abstract—Early and accurate detection of ophthalmic disorders is essential for preventing irreversible vision loss. While deep learning has demonstrated promise in medical imaging, existing models struggle with fine-grained, multi-class classification due to computational complexity and diminishing accuracy gains. We propose Q-EyeNet, a hybrid quantum-classical framework that integrates classical feature extraction with quantum neural networks (QNNs) for the multi-class classification of 15 ophthalmic conditions from fundus and OCT images. By leveraging variational quantum circuits for enhanced feature representation, our approach demonstrates superior diagnostic performance, efficient parameter utilization, and robustness to noise. Evaluated on curated datasets, Q-EyeNet exhibits notable quantum advantage via entanglement-driven feature correlations and hardware-aware optimization on PennayLane platforms. This study represents the first validated application of quantum transfer learning in complex medical image classification, establishing a new paradigm for computational ophthalmology.

Index Terms—Hybrid neural networks, Medical imaging, Multi-class classification, Ophthalmology, Quantum advantage, Quantum machine learning

I.	INTRODUCTION
Ophthalmic disorders such as diabetic retinopathy,  glaucoma, and age-related macular degeneration are leading causes of irreversible vision loss, affecting billions worldwide . The automation of diagnosis using deep learning has shown remarkable success, with convolutional neural networks (CNNs) matching expert-level performance in detecting specific pathologies . However, these models encounter significant challenges when scaled to fine-grained, multi-class problems, often exhibiting diminishing returns in accuracy and escalating computational costs [4].
Quantum computing, leveraging principles of superposition and entanglement, presents a transformative approach to ma-chine learning. Quantum neural networks (QNNs) can model data in high-dimensional Hilbert spaces, offering a potential advantage in learning complex feature relationships .
 
The emergence of software platforms like Penny Lane  and Tensor Flow Quantum has enabled the practical development of hybrid quantum-classical models, making this nascent field ac-accessible for applied research. Recent years have seen a growing interest in applying these hybrid models to medical data, with pioneering works demonstrating feasibility in neuroimaging  and histopathology .
In this work, we present Q-EyeNet, a novel hybrid frame-work designed to overcome the scalability limitations of classical CNNs in multi-class ophthalmic diagnosis.
Our primary contributions are fourfold:
•	A hybrid framework is developed by integrating a classical CNN with a variational quantum circuit, optimized for complex medical image data.
•	The proposed model is rigorously compared with well-optimized classical baselines to ensure fair and meaningful evaluation.
•	Comprehensive ablation studies are conducted to isolate and assess the role of quantum entanglement in performance improvement.
•	Comprehensive ablation studies are conducted to isolate and assess the role of quantum entanglement in performance improvement.

