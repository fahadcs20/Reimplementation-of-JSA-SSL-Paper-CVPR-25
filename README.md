# Reimplementation of JSA-SSL Paper (CVPR 2025)

This Kaggle notebook provides a PyTorch reimplementation of the paper:
**"Improving Sound Source Localization with Joint Slot Attention on Image and Audio"**
by Inho Kim, Youngkil Song, Jicheol Park, Won Hwa Kim, and Suha Kwak.

This notebook focuses on demonstrating the core ideas of the paper using a **dummy dataset** for ease of execution and testing. It includes:

*   **Joint Slot Attention (JSA):** Implementing the mechanism for decomposing audio-visual features.
*   **Key Loss Components:** Contrastive learning, cross-modal attention matching, slot divergence, and reconstruction loss.
*   **False Negative Mitigation & IQR:** Implementing strategies for improved localization.
*   **Visualizations:** Showing sample localization results and training progress.

**Main Paper Link:** [https://openaccess.thecvf.com/content/CVPR2025/papers/Kim_Improving_Sound_Source_Localization_with_Joint_Slot_Attention_on_Image_CVPR_2025_paper.pdf](https://openaccess.thecvf.com/content/CVPR2025/papers/Kim_Improving_Sound_Source_Localization_with_Joint_Slot_Attention_on_Image_CVPR_2025_paper.pdf)

**Kaggle Notebook Link:** [https://www.kaggle.com/code/mdabdullahalfahadcv/dummydataver-jsa-ssl](https://www.kaggle.com/code/mdabdullahalfahadcv/dummydataver-jsa-ssl)

---

### How to Use This Notebook:

1.  **Open the Kaggle Notebook:** Click on the Kaggle Notebook Link above.
2.  **Run All Cells:** Simply run all the cells sequentially. The notebook includes:
    *   Package installations.
    *   Definition of the dummy dataset.
    *   Model architecture components (Encoders, Slot Attention, Decoders).
    *   Loss functions and training utilities.
    *   The main training loop and evaluation.
    *   Visualization of results and training history.
    *   A basic cross-modal retrieval demo.
    *   An optional ablation study configuration.
3.  **Observe Results:** The notebook will output training progress, validation metrics, and visualizations of the localization results.

**Note:** This implementation uses a simplified dummy dataset and reduced training epochs for demonstration purposes on Kaggle. For achieving state-of-the-art performance, a real dataset and more extensive training would be required.
