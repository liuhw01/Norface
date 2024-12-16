# Norface
Hanwei Liu, Rudong An,  Zhimeng Zhang, Bowen Ma,  Wei Zhang, Yan Song, Yujing Hu, Wei Chen, and Yu Ding. [Norface: Improving Facial Expression Analysis by Identity Normalization](https://arxiv.org/pdf/2407.15617), ECCV 2024. 



---

Facial Expression Analysis remains a challenging task due to unexpected task-irrelevant noise, such as identity, head pose, and background. To address this issue, this paper proposes a novel framework, called Norface, that is unified for both Action Unit (AU) analysis and Facial Emotion Recognition (FER) tasks. Norface consists of a normalization network and a classification network. First, the carefully designed normalization network struggles to directly remove the above task-irrelevant noise, by maintaining facial expression consistency but normalizing all original images to a common identity with consistent pose, and background. Then, these additional normalized images are fed into the classification network. Due to consistent identity and other factors (e.g. head pose, background, etc.), the normalized images enable the classification network to extract useful expression information more effectively. Additionally, the classification network incorporates a Mixture of Experts to refine the latent representation, including handling the input of facial representations and the output of multiple (AU or emotion) labels. Extensive experiments validate the carefully designed framework with the insight of identity normalization. The proposed method outperforms existing SOTA methods in multiple facial expression analysis tasks, including AU detection, AU intensity estimation, and FER tasks, as well as their cross-dataset tasks. For the normalized datasets and code please visit [https://norface-fea.github.io].


---
# Normalized dataset Links

For the normalized data of all facial expression datasets (AffectNet, RAF-DB, BP4D, BP4D+, DISFA), please visit ([https://norface-fea.github.io]).

We are actively reaching out to the authors of the BP4D, BP4D+, and DISFA datasets to seek legal permission. Thank you.

For the normalized data of individual facial expression dataset:

1. AffectNet. Baidu Cloud ([https://pan.baidu.com/s/1IoqRTy_GD6h_XYxOL9VBng?pwd=norf]).

2. RAF-DB. Baidu Cloud ([https://pan.baidu.com/s/1ni2JmNZ97ldaso1nhkIVCA?pwd=norf]).

3. BP4D.

4. BP4D+.

5. DISFA.

If you use our normalized dataset, please cite both our work and the original datasets.

1. AffectNet: Mollahosseini, A., Hasani, B., Mahoor, M.H.: Affectnet: A database for facial expression, valence, and arousal computing in the wild. IEEE Transactions on Affective Computing 10(1), 18–31 (2017).

2. RAF-DB: Li, S., Deng, W., Du, J.: Reliable crowdsourcing and deep locality-preserving learning for expression recognition in the wild. In: Proceedings of the IEEE conference on computer vision and pattern recognition. pp. 2852–2861 (2017).

3. BP4D: Zhang, X., Yin, L., Cohn, J.F., Canavan, S., Reale, M., Horowitz, A., Liu, P., Girard, J.M.: Bp4d-spontaneous: a high-resolution spontaneous 3d dynamic facial expression database. Image and Vision Computing 32(10), 692–706 (2014).

4. BP4D+: Zhang, Z., Girard, J.M., Wu, Y., Zhang, X., Liu, P., Ciftci, U., Canavan, S., Reale, M., Horowitz, A., Yang, H., et al.: Multimodal spontaneous emotion corpus for human behavior analysis. In: Proceedings of the IEEE conference on computer vision and pattern recognition. pp. 3438–3446 (2016).

5. DISFA: Mavadati, S.M., Mahoor, M.H., Bartlett, K., Trinh, P., Cohn, J.F.: Disfa: A spontaneous facial action intensity database. IEEE Transactions on Affective Computing 4(2), 151–160 (2013).


