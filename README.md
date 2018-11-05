# encounter-traffic
Code for "Learning the Relation Between Mobile Encounters and Web Traffic Patterns: A Data-driven Study" MSWiM 2018 (ACM: https://dl.acm.org/citation.cfm?id=3242137, Tech Report: https://arxiv.org/abs/1808.03842)

Please feel free to contact the authors:  
Babak Alipour <babak.alipour@gmail.com>  
Mimonah Alqathrady <mimonahalqathrady@gmail.com>  
Ahmed Helmy <helmy@ufl.edu>  

**Note: If you use any of these tools, code or data, please make sure to cite our correspnding paper(s).**

# Pre-built Docker image
Link: https://hub.docker.com/r/nomadsgroupm/encounter-traffic/  

To run the image:
>docker run -p 8888:8888 nomadsgroupm/encounter-traffic:demo

This starts a Jupyter notebook and bind the corresponding ports.  
Please note that the Docker image includes the code, __and__ a sample of data.

# Code License
[Apache License 2.0](https://spdx.org/licenses/Apache-2.0.html)

# Data License
By accessing the Docker image or any of the data files associated with this project, you (the "Researcher") agree to the following terms and conditions:  
  * Researcher shall use the data only for non-commercial research and educational purposes.  
  * University of Florida makes no representations or warranties regarding the data, including but not limited to warranties of non-infringement or fitness for a particular purpose.  
  * Researcher accepts full responsibility for his or her use of the data and shall defend and indemnify the Mobile Networking Laboratory team, and University of Florida, including their employees, Trustees, officers and agents, against any and all claims arising from Researcher's use of the data, including but not limited to Researcher's use of any copies of copyrighted images that he or she may create from the data.  
  * Researcher may provide research associates and colleagues with access to the data provided that they first agree to be bound by these terms and conditions.  
  * University of Florida reserves the right to terminate Researcher's access to the data at any time.
  * If Researcher is employed by a for-profit, commercial entity, Researcher's employer shall also be bound by these terms and conditions, and Researcher hereby represents that he or she is fully authorized to enter into this agreement on behalf of such employer.  
  * The law of the State of Florida shall apply to all disputes under this agreement.  

(Data license adapted from [ImageNet](http://image-net.org/download-faq))  

**Acknowledgements**  
This work was partially funded by NSF 1320694. We gratefully acknowledge the support of NVIDIA Corporation with the donation of the Titan Xp GPU used for this research.
