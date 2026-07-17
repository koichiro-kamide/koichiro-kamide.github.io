---
permalink: /
title: 自己紹介
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  .language-switcher {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin: 0 0 1.5rem;
  }

  .about-language-target {
    position: absolute;
    width: 1px;
    height: 1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    scroll-margin-top: 6rem;
  }

  .language-switcher a {
    padding: 0.35rem 0.8rem;
    border: 1px solid #7a8288;
    border-radius: 999px;
    background: transparent;
    color: inherit;
    cursor: pointer;
    font: inherit;
    font-size: 0.85rem;
    line-height: 1.4;
    text-decoration: none;
  }

  .language-switcher a:hover,
  .language-switcher a:focus-visible {
    border-color: #2a7ae2;
    text-decoration: none;
  }

  .language-switcher a[data-language-link="ja"],
  #about-lang-ja:target ~ .language-switcher a[data-language-link="ja"],
  #about-lang-zh:target ~ .language-switcher a[data-language-link="zh"],
  #about-lang-en:target ~ .language-switcher a[data-language-link="en"] {
    border-color: #2a7ae2;
    background: #2a7ae2;
    color: #fff;
  }

  #about-lang-zh:target ~ .language-switcher a[data-language-link="ja"],
  #about-lang-en:target ~ .language-switcher a[data-language-link="ja"] {
    border-color: #7a8288;
    background: transparent;
    color: inherit;
  }

  .about-language-content [data-language-block],
  .about-language-content [data-language-text] {
    display: none;
  }

  .about-language-content [data-language-block="ja"] {
    display: block !important;
  }

  .about-language-content [data-language-text="ja"] {
    display: inline !important;
  }

  #about-lang-zh:target ~ .about-language-content [data-language-block="ja"],
  #about-lang-en:target ~ .about-language-content [data-language-block="ja"],
  #about-lang-zh:target ~ .about-language-content [data-language-text="ja"],
  #about-lang-en:target ~ .about-language-content [data-language-text="ja"] {
    display: none !important;
  }

  #about-lang-zh:target ~ .about-language-content [data-language-block="zh"],
  #about-lang-en:target ~ .about-language-content [data-language-block="en"] {
    display: block !important;
  }

  #about-lang-zh:target ~ .about-language-content [data-language-text="zh"],
  #about-lang-en:target ~ .about-language-content [data-language-text="en"] {
    display: inline !important;
  }
</style>

<div class="about-language-page" markdown="1">
<div class="about-language-target" id="about-lang-ja" aria-hidden="true"></div>
<div class="about-language-target" id="about-lang-zh" aria-hidden="true"></div>
<div class="about-language-target" id="about-lang-en" aria-hidden="true"></div>

<nav class="language-switcher" aria-label="Language selection">
  <a href="#about-lang-ja" data-language-link="ja" lang="ja">日本語</a>
  <a href="#about-lang-zh" data-language-link="zh" lang="zh-CN">中文</a>
  <a href="#about-lang-en" data-language-link="en" lang="en">English</a>
</nav>

<div class="about-language-content" markdown="1">
<div data-language-block="ja" lang="ja" markdown="1">
富山大学理工学研究科M2の上出耕一郎です。  
[張研究室](https://www.labzhang.com/)にて異常検知に関する研究に取り組んでいます。

## 学歴
* 2025年4月–現在　富山大学 理工学研究科
* 2021年4月–2025年3月　富山大学 工学部

## 研究分野
深層学習、コンピュータビジョン、異常検知、人物動作など
</div>

<div data-language-block="zh" lang="zh-CN" markdown="1">
我是富山大学理工学研究科硕士二年级学生上出耕一郎。<br>
目前在[张研究室](https://www.labzhang.com/)从事异常检测研究。

## 教育经历
* 2025年4月–至今　富山大学 理工学研究科
* 2021年4月–2025年3月　富山大学 工学部

## 研究方向
深度学习、计算机视觉、异常检测、人体动作等
</div>

<div data-language-block="en" lang="en" markdown="1">
I am Koichiro Kamide, a second-year master's student at the Graduate School of Science and Engineering, University of Toyama.<br>
I conduct research on anomaly detection in the [Zhang Laboratory](https://www.labzhang.com/).

## Education
* April 2025–Present: Graduate School of Science and Engineering, University of Toyama
* April 2021–March 2025: Faculty of Engineering, University of Toyama

## Research Interests
Deep learning, computer vision, anomaly detection, human motion, and related topics
</div>

<h2>
  <span data-language-text="ja">研究業績</span>
  <span data-language-text="zh" lang="zh-CN">研究成果</span>
  <span data-language-text="en" lang="en">Publications</span>
</h2>

[14] **Learning Emotion from Motion: Kinetic Multi-Stream Skeleton Modeling with Metadata-Conditioned Weak Label Distributions**  
Sosuke Suzuki, Yijin Wei, <u>Koichiro Kamide</u>, Ran Dong, Haoran Xie, Chao Zhang,
[**14th International Conference on Affective Computing and Intelligent Interaction Workshops and Demos (ACIIW)**](https://sites.google.com/view/mmac-acii-2026/overview?authuser=0), 2026 (accepted)

[13] [**VT-3DAD: Cross-Category 3D Anomaly Detection via Visual-Text Normal Space Alignment**](https://arxiv.org/abs/2606.04369)  
Zi Wang, Katsuya Hotta, Yawen Zou, <u>Koichiro Kamide</u>, Yijin Wei, Chao Zhang, Jun Yu,  
[**International Conference on Machine Vision (ICMV)**](https://icmv.org/), 2026 (accepted)

[12] [**DMP-3DAD: Cross-Category 3D Anomaly Detection via Realistic Depth Map Projection with Few Normal Samples**](https://www.jstage.jst.go.jp/article/transinf/advpub/0/advpub_2026EDP7008/_article)  
Zi Wang, Katsuya Hotta, <u>Koichiro Kamide</u>, Yawen Zou, Jianjian Qin, Chao Zhang, Jun Yu,  
[**IEICE TRANSACTIONS on Information and Systems**](https://globals.ieice.org/en_transactions/information), Vol. xx, No. xx, pp. xx-xx, 2026

[11] **Image Anomaly Detection with Foreground-Aware Anomaly Synthesis**  
Shohei Fuwa, <u>Koichiro Kamide</u>, Chunzhi Gu, Chao Zhang,  
[NICOGRAPH International (NicoInt)](https://www.art-science.org/nicograph/nicoint2026/), 2026 (accepted)

[10] **Human Action Recognition via Dataset Condensation**  
Yijin Wei, Yawen Zou, <u>Koichiro Kamide</u>, Chunzhi Gu, Hangli Ge, Chao Zhang,  
[NICOGRAPH International (NicoInt)](https://www.art-science.org/nicograph/nicoint2026/), 2026 (accepted)

[9] **Topology-Aware Multi-Scale Learning for Skeleton-Based Human Action Anomaly Detection**  
Shun Maeda, Yijin Wei, <u>Koichiro Kamide</u>, Shogo Tokai, Chunzhi Gu, Chao Zhang,  
[NICOGRAPH International (NicoInt)](https://www.art-science.org/nicograph/nicoint2026/), 2026 (accepted)

[8] **Human Action Anomaly Detection via Spatial-Temporal Transformer Network**  
Kousuke Yamamoto, <u>Koichiro Kamide</u>, Yijin Wei, Chunzhi Gu, Chao Zhang,  
[NICOGRAPH International (NicoInt)](https://www.art-science.org/nicograph/nicoint2026/), 2026 (accepted)

[7] [**3DKeyAD: High-Resolution 3D Point Cloud Anomaly Detection via Keypoint-Guided Point Clustering**](https://www.jstage.jst.go.jp/article/transinf/advpub/0/advpub_2025EDP7152/_article)  
Zi Wang, Katsuya Hotta, <u>Koichiro Kamide</u>, Yawen Zou, Chao Zhang, Jun Yu,  
[**IEICE TRANSACTIONS on Information and Systems**](https://globals.ieice.org/en_transactions/information), Vol. E109-D, No. 8, pp. xx-xx, 2026  
<span data-language-text="ja">コードは[こちら](https://github.com/bigbearbear520/3DKeyAD)で公開しています。</span><span data-language-text="zh" lang="zh-CN">代码已发布于[此处](https://github.com/bigbearbear520/3DKeyAD)。</span><span data-language-text="en" lang="en">The code is available [here](https://github.com/bigbearbear520/3DKeyAD).</span>

[6] [**Few-shot human action anomaly detection via a unified contrastive learning framework**](https://www.sciencedirect.com/science/article/pii/S0950705125021689)  
<u>Koichiro Kamide</u>, Shunsuke Sakai, Shun Maeda, Chunzhi Gu, Chao Zhang,  
[**Knowledge-Based Systems**](https://www.sciencedirect.com/journal/knowledge-based-systems) (<span style="color: red;">**Impact Factor 2024=7.6**</span>), Vol. 334, pp. 115133, 2026<br>
<span data-language-text="ja">コードは[こちら](https://github.com/koichiro-kamide/Few-shotHAAD)で公開しています。</span><span data-language-text="zh" lang="zh-CN">代码已发布于[此处](https://github.com/koichiro-kamide/Few-shotHAAD)。</span><span data-language-text="en" lang="en">The code is available [here](https://github.com/koichiro-kamide/Few-shotHAAD).</span>

[5]
<span data-language-text="ja">**相互作用を意識した複数人物の動作異常検知**</span>
<span data-language-text="zh" lang="zh-CN">**面向交互关系的多人动作异常检测**</span>
<span data-language-text="en" lang="en">**Multi-Person Action Anomaly Detection Considering Human Interactions**</span><br>
<span data-language-text="ja">前田駿, 顧淳祉, <u>上出耕一郎</u>, 東海彰吾, 張潮,</span>
<span data-language-text="zh" lang="zh-CN">Shun Maeda, Chunzhi Gu, <u>Koichiro Kamide</u>, Shogo Tokai, Chao Zhang,</span>
<span data-language-text="en" lang="en">Shun Maeda, Chunzhi Gu, <u>Koichiro Kamide</u>, Shogo Tokai, Chao Zhang,</span><br>
<span data-language-text="ja">[電気学会 電子・情報・システム部門大会](https://www.iee.jp/eiss/event/conf2025)</span><span data-language-text="zh" lang="zh-CN">[日本电气学会电子、信息与系统部门大会](https://www.iee.jp/eiss/event/conf2025)</span><span data-language-text="en" lang="en">[Annual Conference of the IEEJ Electronics, Information and Systems Society](https://www.iee.jp/eiss/event/conf2025)</span>, OS4-2-9, pp. 979-982, 2025

[4]
<span data-language-text="ja">**データ拡張を用いた人物動作異常検知**</span>
<span data-language-text="zh" lang="zh-CN">**基于数据增强的人体动作异常检测**</span>
<span data-language-text="en" lang="en">**Human Action Anomaly Detection Using Data Augmentation**</span><br>
<span data-language-text="ja"><u>上出耕一郎</u>, 前田駿, 坂井俊介, 顧淳祉, 張潮,</span>
<span data-language-text="zh" lang="zh-CN"><u>Koichiro Kamide</u>, Shun Maeda, Shunsuke Sakai, Chunzhi Gu, Chao Zhang,</span>
<span data-language-text="en" lang="en"><u>Koichiro Kamide</u>, Shun Maeda, Shunsuke Sakai, Chunzhi Gu, Chao Zhang,</span><br>
<span data-language-text="ja">[電気学会 電子・情報・システム部門大会](https://www.iee.jp/eiss/event/conf2025)</span><span data-language-text="zh" lang="zh-CN">[日本电气学会电子、信息与系统部门大会](https://www.iee.jp/eiss/event/conf2025)</span><span data-language-text="en" lang="en">[Annual Conference of the IEEJ Electronics, Information and Systems Society](https://www.iee.jp/eiss/event/conf2025)</span>, OS4-2-8, pp. 975-978, 2025

[3] **Dynamically Adaptive Negative Pairs for Contrastive Multi-View Clustering**  
Yu Ding, <u>Koichiro Kamide</u>, Jun Yu, Chao Zhang,  
[Quality Control by Artificial Vision (QCAV)](https://www.tc-iaip.org/qcav/2025/), S5-4, 2025

[2] **One-Model-All-Category Human Action Anomaly Detection**  
<span data-language-text="ja"><u>Koichiro Kamide</u>, Chunzhi Gu, Shun Maeda, Jun Yu, Chao Zhang,</span>
<span data-language-text="zh" lang="zh-CN"><u>Koichiro Kamide</u>, Chunzhi Gu, Shun Maeda, Jun Yu, Chao Zhang,</span>
<span data-language-text="en" lang="en"><u>Koichiro Kamide</u>, Chunzhi Gu, Shun Maeda, Jun Yu, Chao Zhang,</span><br>
<span data-language-text="ja">[動的画像処理実利用化ワークショップ (DIA)](https://www.tc-iaip.org/dia/2025/)</span><span data-language-text="zh" lang="zh-CN">[动态影像处理实际应用化研讨会 (DIA)](https://www.tc-iaip.org/dia/2025/)</span><span data-language-text="en" lang="en">[Dynamic Image Processing for Real Application Workshop (DIA)](https://www.tc-iaip.org/dia/2025/)</span>, IS2-30, pp. 356-360, 2025

[1]
<span data-language-text="ja">**Few-shot三次元人物動作異常検知**</span>
<span data-language-text="zh" lang="zh-CN">**少样本三维人体动作异常检测**</span>
<span data-language-text="en" lang="en">**Few-Shot 3D Human Action Anomaly Detection**</span><br>
<span data-language-text="ja"><u>上出耕一郎</u>, 顧淳祉, 前田駿, 余俊, 張潮,</span>
<span data-language-text="zh" lang="zh-CN"><u>Koichiro Kamide</u>, Chunzhi Gu, Shun Maeda, Jun Yu, Chao Zhang,</span>
<span data-language-text="en" lang="en"><u>Koichiro Kamide</u>, Chunzhi Gu, Shun Maeda, Jun Yu, Chao Zhang,</span><br>
<span data-language-text="ja">[メディア工学研究会 (ME)](https://www.ite.or.jp/ken/program/index.php?tgs_regid=eaad7329a67e51120a4fda78e0770437c4d94cd15318bc2211cb5356630849dd&tgid=ITE-ME)</span><span data-language-text="zh" lang="zh-CN">[媒体工程研究会 (ME)](https://www.ite.or.jp/ken/program/index.php?tgs_regid=eaad7329a67e51120a4fda78e0770437c4d94cd15318bc2211cb5356630849dd&tgid=ITE-ME)</span><span data-language-text="en" lang="en">[Technical Group on Media Engineering (ME)](https://www.ite.or.jp/ken/program/index.php?tgs_regid=eaad7329a67e51120a4fda78e0770437c4d94cd15318bc2211cb5356630849dd&tgid=ITE-ME)</span>, 2025

<h3>
  <span data-language-text="ja">査読中</span>
  <span data-language-text="zh" lang="zh-CN">审稿中</span>
  <span data-language-text="en" lang="en">Under Review</span>
</h3>

[1] [**3D Human-Human Interaction Anomaly Detection**](https://arxiv.org/abs/2512.13560)  
Shun Maeda, Chunzhi Gu, <u>Koichiro Kamide</u>, Katsuya Hotta, Shangce Gao, Chao Zhang

<h2>
  <span data-language-text="ja">受賞</span>
  <span data-language-text="zh" lang="zh-CN">获奖</span>
  <span data-language-text="en" lang="en">Awards</span>
</h2>

[3] [**Short Paper Award**](https://www.art-science.org/nicograph/nicoint2026/#nicoint2026-awards:~:text=and%20Haoran%20Xie-,Short%20Paper%20Award,-Human%20Action%20Recognition)
**Human Action Recognition via Dataset Condensation**,  
Yijin Wei, Yawen Zou, <u>Koichiro Kamide</u>, Chunzhi Gu, Hangli Ge, Chao Zhang,  
[NICOGRAPH International (NicoInt)](https://www.art-science.org/nicograph/nicoint2026/), 2026

[2] [**Best Paper Award**](https://www.tc-iaip.org/qcav/2025/#:~:text=S5%2D4%E2%80%83Dynamically%20Adaptive%20Negative%20Pairs%20for%20Contrastive%20Multi%2DView%20Clustering)  
**Dynamically Adaptive Negative Pairs for Contrastive Multi-View Clustering**  
Yu Ding, <u>Koichiro Kamide</u>, Jun Yu, Chao Zhang  
[Quality Control by Artificial Vision (QCAV)](https://www.tc-iaip.org/qcav/2025/), S5-4, 2025

[1]
<span data-language-text="ja">[**研究奨励賞**](https://www.ite.or.jp/study/me/files/award.html)</span>
<span data-language-text="zh" lang="zh-CN">[**研究鼓励奖**](https://www.ite.or.jp/study/me/files/award.html)</span>
<span data-language-text="en" lang="en">[**Research Encouragement Award**](https://www.ite.or.jp/study/me/files/award.html)</span><br>
<span data-language-text="ja">**Few-shot三次元人物動作異常検知**</span>
<span data-language-text="zh" lang="zh-CN">**少样本三维人体动作异常检测**</span>
<span data-language-text="en" lang="en">**Few-Shot 3D Human Action Anomaly Detection**</span><br>
<span data-language-text="ja"><u>上出耕一郎</u>, 顧淳祉, 前田駿, 余俊, 張潮</span>
<span data-language-text="zh" lang="zh-CN"><u>Koichiro Kamide</u>, Chunzhi Gu, Shun Maeda, Jun Yu, Chao Zhang</span>
<span data-language-text="en" lang="en"><u>Koichiro Kamide</u>, Chunzhi Gu, Shun Maeda, Jun Yu, Chao Zhang</span><br>
<span data-language-text="ja">[メディア工学研究会 (ME)](https://www.ite.or.jp/ken/program/index.php?tgs_regid=eaad7329a67e51120a4fda78e0770437c4d94cd15318bc2211cb5356630849dd&tgid=ITE-ME)</span><span data-language-text="zh" lang="zh-CN">[媒体工程研究会 (ME)](https://www.ite.or.jp/ken/program/index.php?tgs_regid=eaad7329a67e51120a4fda78e0770437c4d94cd15318bc2211cb5356630849dd&tgid=ITE-ME)</span><span data-language-text="en" lang="en">[Technical Group on Media Engineering (ME)](https://www.ite.or.jp/ken/program/index.php?tgs_regid=eaad7329a67e51120a4fda78e0770437c4d94cd15318bc2211cb5356630849dd&tgid=ITE-ME)</span>, 2025

<div data-language-block="ja" lang="ja" markdown="1">
## 資格
* 2024年4月　TOEIC Listening & Reading Test 865点　取得
* 2023年6月　応用情報技術者試験　合格
* 2023年6月　基本情報技術者試験　合格
* 2022年2月　第二種電気工事士　取得
</div>

<div data-language-block="zh" lang="zh-CN" markdown="1">
## 资格证书
* 2024年4月　TOEIC Listening & Reading Test 865分
* 2023年6月　通过应用信息技术者考试
* 2023年6月　通过基本信息技术者考试
* 2022年2月　取得第二种电气工事士资格
</div>

<div data-language-block="en" lang="en" markdown="1">
## Qualifications
* April 2024: TOEIC Listening & Reading Test — Score: 865
* June 2023: Passed the Applied Information Technology Engineer Examination
* June 2023: Passed the Fundamental Information Technology Engineer Examination
* February 2022: Obtained a Second-Class Electrician License
</div>

</div>
</div>

<script>
  (function () {
    var supportedLanguages = ["ja", "zh", "en"];
    var titles = {
      ja: "自己紹介",
      zh: "自我介绍",
      en: "About Me"
    };
    var requestedLanguage = null;
    var savedLanguage = null;

    try {
      requestedLanguage = new URLSearchParams(window.location.search).get("lang");
    } catch (error) {
      requestedLanguage = null;
    }

    try {
      savedLanguage = window.localStorage.getItem("about-language");
    } catch (error) {
      savedLanguage = null;
    }

    function languageFromHash() {
      var language = window.location.hash.replace("#about-lang-", "");
      return supportedLanguages.indexOf(language) !== -1 ? language : null;
    }

    function updatePageLanguage(language) {
      if (supportedLanguages.indexOf(language) === -1) {
        language = "ja";
      }

      document.documentElement.lang = language === "zh" ? "zh-CN" : language;

      var pageTitle = document.querySelector(".page__title");
      if (pageTitle) {
        pageTitle.textContent = titles[language];
      }
      document.title = titles[language] + " - {{ site.title | escape }}";

      try {
        window.localStorage.setItem("about-language", language);
      } catch (error) {
        // The language switch still works when browser storage is unavailable.
      }
    }

    document.querySelectorAll("[data-language-link]").forEach(function (link) {
      link.addEventListener("click", function () {
        updatePageLanguage(link.getAttribute("data-language-link"));
      });
    });

    window.addEventListener("hashchange", function () {
      updatePageLanguage(languageFromHash() || "ja");
    });

    var initialLanguage = languageFromHash()
      || (supportedLanguages.indexOf(requestedLanguage) !== -1 ? requestedLanguage : null)
      || (supportedLanguages.indexOf(savedLanguage) !== -1 ? savedLanguage : "ja");

    if (!languageFromHash() && initialLanguage !== "ja") {
      window.location.hash = "about-lang-" + initialLanguage;
    }
    updatePageLanguage(initialLanguage);
  }());
</script>
