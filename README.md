# [Evolutionary Neural Architecture Search for Autonomous Agents](https://github.com/AlexandraGna/Evolutionary_Neural_Architecture_Search_for_Autonomous_Agents)

Research thesis completed at Volkswagen. Contributor: Nihal Acharya Adde.

The design of neural network architectures for autonomous driving applications presents a significant challenge in balancing competing objectives: achieving high predictive accuracy while maintaining computational efficiency within hardware constraints. <b>Evolutionary Neural Architecture Search (ENAS)</b> addresses this challenge through automated exploration of the architecture space using evolutionary algorithms, enabling the discovery of network designs that satisfy multiple performance criteria simultaneously. This approach is particularly valuable in the autonomous driving domain, where real-time inference requirements and embedded hardware limitations necessitate architectures optimized for both accuracy and computational efficiency.

* <b>Transfer Learning for Architecture Optimization: </b>
Conventional architecture search methodologies train candidate architectures independently, resulting in substantial computational overhead. This thesis proposes a <b>Transfer Learning-based approach</b> that leverages knowledge from previously optimized architectures to accelerate the search process. By initializing new candidate architectures with learned representations from successful predecessors, this methodology reduces training iterations while improving convergence rates and final performance metrics. 
  
Comparative analysis in the figure below demonstrates that the Transfer Learning-enhanced architecture search (ADenas_EFPI_TL) consistently achieves superior reward values relative to the baseline approach (ADenas_EFPI) across all evolutionary generations, indicating sustained performance improvements.

<p align="center">
<img src="https://AlexandraGna.github.io/Portfolio/fig_5.8_low_res.png" alt="zigzag" width="90%" height="75%" />  
</p>

The proposed methodology, as shown in the figure below, demonstrates reduced computational overhead (measured in FLOPs) while achieving better performance from baseline methods, a critical requirement for deployment in resource-constrained automotive systems.

<p align="center">
<img src="https://AlexandraGna.github.io/Portfolio/fig_5.7_low_res.png" alt="zigzag" width="90%" height="75%" />  
</p>


The results indicate that Transfer Learning-based architecture search provides an efficient approach to neural architecture optimization for reinforcement learning agents in autonomous driving. By reducing computational requirements while improving solution quality, this methodology advances the practical applicability of ENAS in real-world autonomous driving systems.


For comprehensive technical documentation, implementation details, and extended experimental results, refer to the [complete thesis](https://github.com/AlexandraGna/Evolutionary_Neural_Architecture_Search_for_Autonomous_Agents/blob/main/Volkswagen_Thesis_Report.pdf). A summary of key findings has been published in the conference proceedings [here](https://www.esann.org/sites/default/files/proceedings/2025/ES2025-122.pdf).

Note: The implementation code is proprietary to Volkswagen and is not publicly available.
