# Analysis of Influential Factors for the Prediction of YouTube Views Using Tree-based Machine Learning

<p align="center">
  <b>Jin-Woong Kim<sup>1‡</sup> · Ji-Won Seo<sup>2‡</sup> · Chang-Ho Son<sup>3*</sup> · Seoung-Ho Choi<sup>4*</sup></b><br>
  <sup>1</sup>Department of Convergence IT Engineering, Hansung University, Seoul, Republic of Korea<br>
  <sup>2</sup>Department of Computer Engineering, Hansung University, Seoul, Republic of Korea<br>
  <sup>3</sup>Department of System Engineering, Korea Army Academy, Gyeongsangbuk-do, Republic of Korea<br>
  <sup>4</sup>College of Liberal Arts, Hansung University, Seoul, Republic of Korea
</p>

****

[![Paper](https://img.shields.io/badge/PAPER-JDCS_Open_Access-E84C3D?style=for-the-badge)](https://doi.org/10.9728/dcs.2025.26.1.175)
[![Journal](https://img.shields.io/badge/JOURNAL-JDCS-blue?style=for-the-badge)](http://journal.dcs.or.kr/)
[![Publisher](https://img.shields.io/badge/PUBLISHER-Digital_Contents_Society-black?style=for-the-badge)](http://www.dcs.or.kr/)


<img width="1200" alt="Architecture" src="https://github.com/user-attachments/assets/23ff1d2f-a0e4-470a-9ca7-690522e14c09" />
<p align="center"><em>Figure 1. Overall architecture of the proposed YouTube view prediction framework using tree-based machine learning and SHAP analysis.</em></p>

<br>

## Abstract

In recent years, YouTube has become the most popular media-sharing platform worldwide. The number of views of YouTube videos is a crucial indicator of content success, and its accurate prediction can significantly help in developing content strategies. However, the factors influencing YouTube view predictions are not well understood, making it difficult to predict the views of new content. To address this, we propose a method to predict the views of new videos using metadata and derived variables from YouTube videos across all categories. We validated the prediction performance using five tree-based machine-learning models and analyzed the key features influencing view prediction through SHapley Additive exPlanations (SHAP) analysis. Through the proposed method, we confirmed that several factors—such as the number of likes, video length, and category ID—have a significant impact on the prediction of YouTube views.

<br>

## Motivation

- YouTube view count serves as a fundamental metric for evaluating content performance and monetization potential.  
- Previous studies were limited to specific domains or lacked interpretability in factor influence.  
- This study aims to establish a generalized, explainable framework to predict views across diverse categories using metadata-driven variables.  
- By adopting SHAP, the model highlights the relative importance of features and clarifies their directional impact on predictions.

<br>

## Contribution

- Developed a **tree-based ensemble framework** integrating YouTube metadata and engineered features for view prediction.  
- Compared multiple ensemble models — Random Forest, Extra Trees, CatBoost, LightGBM, and XGBoost — to ensure robustness.  
- Applied **SHAP-based feature attribution** to interpret the contribution of major factors such as likes, length, and category ID.  
- Demonstrated an interpretable foundation for improving **content strategy optimization** and **recommendation systems**.

<br>

## Citation

If you use this work, please cite:

```bibtex
@article{kim2025youtubeviews,
  title={Analysis of Influential Factors for the Prediction of YouTube Views Using Tree-based Machine Learning},
  author={Jin-Woong Kim and Ji-Won Seo and Chang-Ho Son and Seoung-Ho Choi},
  journal={Journal of Digital Contents Society},
  volume={26},
  number={1},
  pages={175--182},
  year={2025},
  doi={10.9728/dcs.2025.26.1.175}
}
