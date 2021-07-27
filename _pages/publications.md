---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## All publications
### International conference

1. Takayuki Semitsu, Mitsuki Nakamura, Shotaro Ishigami, Teng-Yok Lee, Toru Aoki, Yoshimi Isu, "Estimating Contribution of Training Datasets using Shapley Values in Data-scale for Visual Recognition", Machine Vision Application 2021(MVA2021)(Oral)
2. Takayuki Semitsu, Xiongxin Zhao and Wataru Matsumoto, “Heterogeneous Multi-task Learning on Non-overlapping Datasets for Facial Landmark Detection.”, International Conference on Neural Information Processing of the Asia-Pacific Neural Network Society ICONIP 2016
3. Takayuki Semitsu, Daiki Kudo, Shun-ichi Sekiguchi, Hirofumi Nishikawa and Hironobu Abe, “Video Re-compression Using Inter-scene Correlation among Multiple Video Streams”, 2014 International Workshop on Advanced Image Technology IWAIT2014  

### Domestic conference
1. **瀬光孝之**、南本高志、毬山利貞, “複数オブジェクトのイベントの組み合わせによる行動記述方式”, 人工知能学会全国大会, 2018, 4Pin1-53
1. **瀬光孝之**、大澤淳真、原田亞矢子, “監視カメラの推奨設定値算出アルゴリズム”, 電子情報通信学会総合大会講演論文集 2016年_情報・システム(2), 61, 2016-03-01


### Journal publications
1. **瀬光孝之**，吉村玄太, 毬山利貞m, 杉本和夫, "技術解説「機械学習モデルの解釈性に関する最新動向」"，[電子情報通信学会，Vol.102 No.10 pp.973-977](https://app.journal.ieice.org/trial/102_10/k102_10_973/index.html), 2019年10月．

### Preprint
1. Kei Ota, Devesh K. Jha, Diego Romeres, Jeroen van Baar, Kevin A. Smith, **Takayuki Semitsu**, Tomoaki Oiki, Alan Sullivan, Daniel Nikovski, Joshua B. Tenenbaum, “Towards Human-Level Learning of Complex Physical Puzzles,” arXiv, 2020. [arxiv](https://arxiv.org/abs/2011.07193).

### Seminar/Workshops
1. オンラインセミナー "機械学習モデルへの解釈性付与手法と応用・今後の動向", サイエンス&テクノロジー, 2020年8月