Source code for o Neural Computing and Applica 2022 paper:Self-Supervised Commonsense Knowledge Learning forDocument-level Relation Extraction

Document-level relation extraction (Doc-level RE) is a more challenging task than sentence-level relation extraction. It aims at extracting relationships between two entities over multiple sentences at once while taking into account significant cross-sentence features. However, learning long-distance semantic relation representation across sentences in a document is a difficult task. To address this problem, this paper proposes a self-supervised commonsense-enhanced Doc-level RE method, called SCDRE, without external knowledge. First, we introduce self-supervised learning to represent commonsense knowledge of each entity in an entity pair based on the commonsense entailed text. Second, we convert the cross-sentence entity pairs into anonymous entity pairs with coreference commonsense replacement. Finally, we perform semantic relation representation learning on the anonymous entity pairs and convert them into target entity pairs. We conducted experiments on three publicly available datasets: DocRED, DialogRE, and MPDD, and the results show that our model has a significant performance advantage over strong baselines by 2.03% F1, and common knowledge has an important contribution to the Doc-level RE by the ablation experimental analysis.

Architecture
![2-1](https://user-images.githubusercontent.com/9714955/174421629-6e37ff8f-a060-4c36-8af4-3b1de0e0929e.PNG)
Illustration of our proposed SCDRE. First, self-supervised learning is introduced to acquire and refine commonsense knowledge. Second, the entity pair representation is constructed to enhance entity contextualized embedding. Finally, entity pair rich attention fusion incorporates commonsense knowledge into the entity pair contextualized embedding by knowledge attention.

Overall Results

![Overall Results](https://user-images.githubusercontent.com/9714955/174421755-65779f08-4c93-4399-aaaf-2b4717d02aed.PNG)

