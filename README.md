# DataOptimization-CV

<br />
<p align="left">
    <a href='https://arxiv.org/abs/2210.11717'>
      <img src='https://img.shields.io/badge/Paper-PDF-green?style=flat&logo=arXiv&logoColor=green' alt='arXiv PDF'>
    </a>
    <a href='https://github.com/Vivian-wzj/DataOptimization-CV' style='padding-left: 0.5rem;'>
      <img src='https://img.shields.io/badge/Project-Page-blue?style=flat&logo=Google%20chrome&logoColor=blue' alt='Project Page'>
    </a>
</p>
<br />

This repo is a collection of resources on data optimization for computer vision (CV), as a supplement for our [survey](https://arxiv.org/abs/2210.11717). If you find any work missing or have any suggestions (papers, implementations and other resources), feel free to [pull requests](https://github.com/Vivian-wzj/DataOptimization-CV/pulls).

<details style="margin-left:3%;">
  <summary>citation</summary>
  <pre><code class="language-bib" style="font-size: 0.9rem;" id="citation">@article{wan2022survey,
  title={A Survey of Data Optimization for Problems in Computer Vision Datasets},
  author={Wan, Zhijing and Wang, Zhixiang and Chung, CheukTing and Wang, Zheng},
  journal={arXiv preprint arXiv:2210.11717},
  year={2022}
}
</code></pre>
</details> 

<details><summary>Table of Contents</summary><p>

- [News](https://github.com/Vivian-wzj/DataOptimization-CV/edit/main/README.md#news)
- [Data Optimization for Robust Learning](https://github.com/Vivian-wzj/DataOptimization-CV/edit/main/README.md#data-optimization-for-robust-learning)
- [Data Optimization for Fair Learning](https://github.com/Vivian-wzj/DataOptimization-CV/edit/main/README.md#data-optimization-for-data-efficient-learning)
- [Data Optimization for Data-efficient Learning](https://github.com/Vivian-wzj/DataOptimization-CV/edit/main/README.md#data-optimization-for-label-efficient-learning)
- [Data Optimization for Label-efficient Learning](https://github.com/Vivian-wzj/DataOptimization-CV/edit/main/README.md#data-optimization-for-label-efficient-learning)

</p></details><p></p>

# News

[2022/10/14] We have submitted our Data-Optimization-for-Computer-Vision survey on arXiv: [A Survey of Data Optimization for Problems in Computer Vision Datasets](https://arxiv.org/abs/2210.11717).(:satisfied:) We will continue to polish this work.(:muscle:)

# Data Optimization for Robust Learning

## On the Class-imbalanced Dataset

### Data Sampling

**FASA: Feature Augmentation and Sampling Adaptation for Long-Tailed Instance Segmentation.**<br>
*[Yuhang Zang](https://yuhangzang.github.io/), Chen Huang, [Chen Change Loy](https://www.mmlab-ntu.com/person/ccloy/).*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/papers/Zang_FASA_Feature_Augmentation_and_Sampling_Adaptation_for_Long-Tailed_Instance_Segmentation_ICCV_2021_paper.pdf)] [[Github](https://github.com/yuhangzang/FASA)] [[Project](https://www.mmlab-ntu.com/project/fasa/index.html)]

**Videolt: Large-scale long-tailed video recognition.**<br>
*Xing Zhang, Zuxuan Wu, Zejia Weng, [Huazhu Fu](https://hzfu.github.io/), Jingjing Chen, Yu-Gang Jiang, Larry Davis.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_VideoLT_Large-Scale_Long-Tailed_Video_Recognition_ICCV_2021_paper.pdf)] [[Github](https://github.com/17Skye17/VideoLT)] [[Project](https://videolt.github.io/)]

**Influence-Balanced Loss for Imbalanced Visual Classification.**<br>
*Seulki Park, Jongin Lim, Younghan Jeon, [Jin Young Choi](http://pil.snu.ac.kr/).*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/papers/Park_Influence-Balanced_Loss_for_Imbalanced_Visual_Classification_ICCV_2021_paper.pdf)] [[Github](https://github.com/pseulki/IB-Loss)]

**Distribution Alignment: A Unified Framework for Long-tail Visual Recognition.**<br>
*[Songyang Zhang](https://www.zhangsongyang.com/), [Zeming Li](https://www.zemingli.com/), [Shipeng Yan](http://yanshipeng.com/), [Xuming He](https://faculty.sist.shanghaitech.edu.cn/faculty/hexm/index.html), [Jian Sun](http://www.jiansun.org/).*<br>
CVPR 2021. [[PDF](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Distribution_Alignment_A_Unified_Framework_for_Long-Tail_Visual_Recognition_CVPR_2021_paper.pdf)] [[Github](https://github.com/Megvii-BaseDetection/DisAlign)]

**The devil is in classification: A simple framework for long-tail instance segmentation.**<br>
*Tao Wang, Yu Li, Bingyi Kang, Junnan Li, Junhao Liew, [Sheng Tang](http://mcg.ict.ac.cn/people/shengtang.htm), [Steven Hoi](https://sites.google.com/view/stevenhoi/home), Jiashi Feng.*<br>
ECCV 2020. [[PDF](https://arxiv.org/pdf/2007.11978.pdf)] [[Github](https://github.com/twangnh/SimCal)]

**Balanced Meta-Softmax for Long-Tailed Visual Recognition.**<br>
*Jiawei Ren, Cunjun Yu, Shunan Sheng, [Xiao Ma](https://yusufma03.github.io/), Haiyu Zhao, Shuai Yi, [Hongsheng Li](https://www.ee.cuhk.edu.hk/~hsli/).*<br>
NeurIPS 2020. [[PDF](https://proceedings.neurips.cc/paper/2020/file/2ba61cc3a8f44143e1f2f13b2b729ab3-Paper.pdf)] [[Github](https://github.com/jiawei-ren/BalancedMetaSoftmax)]

**Meta-Weight-Net: Learning an Explicit Mapping For Sample Weighting.**<br>
*Jun Shu, Qi Xie, Lixuan Yi, Qian Zhao, [Sanping Zhou](http://gr.xjtu.edu.cn/web/spzhou), Zongben Xu, [Deyu Meng](http://gr.xjtu.edu.cn/web/dymeng).*<br>
NeurIPS 2019. [[PDF](https://proceedings.neurips.cc/paper/2019/file/e58cc5ca94270acaceed13bc82dfedf7-Paper.pdf)] [[Github](https://github.com/xjtushujun/meta-weight-net)]

**Focal loss for dense object detection.**<br>
*[Tsung-Yi Lin](https://tsungyilin.info/), [Priya Goyal](https://prigoyal.github.io/), [Ross Girshick](https://www.rossgirshick.info/), [Kaiming He](http://kaiminghe.com/), [Piotr Dollar](https://pdollar.github.io/).*<br>
ICCV 2017. [[PDF](https://openaccess.thecvf.com/content_ICCV_2017/papers/Lin_Focal_Loss_for_ICCV_2017_paper.pdf)]

**C4. 5, class imbalance, and cost sensitivity: why under-sampling beats over-sampling.**<br>
*Chris Drummond, Robert C. Holte.*<br>
Workshop on learning from imbalanced datasets II 2003. [[PDF](http://www.eiti.uottawa.ca/~nat/Workshop2003/drummondc.pdf)]

### Subset Selection

**SlimML: Removing non-critical input data in large-scale iterative machine learning.**<br>
*[Rui Han](https://sites.google.com/site/hanruisystem/), [Chi Harold Liu](https://cs.bit.edu.cn/szdw/jsml/gjjgccrc/lc_1065cf35e06845a7a667945726df0886/index.htm), Shilin Li, [Lydia Y. Chen](https://www.lydiaychen.com/), Guoren Wang, Jian Tang, Jieping Ye.*<br>
TKDE 2019. [[PDF](https://sci-hub.se/10.1109/TKDE.2019.2951388)]

## On the Dataset with Noisy Labels

### Data Sampling

**Dualgraph: A graph-based method for reasoning about label noise.**<br>
*HaiYang Zhang, XiMing Xing, Liang Liu.*<br>
CVPR 2021. [[PDF](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_DualGraph_A_Graph-Based_Method_for_Reasoning_About_Label_Noise_CVPR_2021_paper.pdf)]

**Learning to Reweight Examples for Robust Deep Learning.**<br>
*[Mengye Ren](https://mengyeren.com/), [Wenyuan Zeng](http://www.cs.toronto.edu/~wenyuan/), [Bin Yang](http://www.cs.toronto.edu/~byang/), [Raquel Urtasun](http://www.cs.toronto.edu/~urtasun/).*<br>
ICML 2018. [[PDF](http://proceedings.mlr.press/v80/ren18a/ren18a.pdf)]

**CurriculumNet: Weakly Supervised Learning from Large-Scale Web Images.**<br>
*Sheng Guo, [Weilin Huang](http://whuang.org/), Haozhi Zhang, Chenfan Zhuang, Dengke Dong, Matthew R. Scott, Dinglong Huang.*<br>
ECCV 2018. [[PDF](https://openaccess.thecvf.com/content_ECCV_2018/papers/Sheng_Guo_CurriculumNet_Learning_from_ECCV_2018_paper.pdf)] [[Github](https://github.com/guoshengcv/CurriculumNet)]

**Active Bias: Training More Accurate Neural Networks by Emphasizing High Variance Samples.**<br>
*Haw-Shiuan Chang, [Erik Learned-Miller](https://people.cs.umass.edu/~elm/), Andrew McCallum.*<br>
NeurIPS 2017. [[PDF](https://proceedings.neurips.cc/paper/2017/file/2f37d10131f2a483a8dd005b3d14b0d9-Paper.pdf)]

**Multiclass Learning With Partially Corrupted Labels.**<br>
*Ruxin Wang, [Tongliang Liu](https://tongliang-liu.github.io/), [Dacheng Tao](https://www.sydney.edu.au/engineering/about/our-people/academic-staff/dacheng-tao.html).*<br>
TNNLS 2017. [[PDF](https://sci-hub.se/10.1109/TNNLS.2017.2699783)]

**Self-Paced Learning for Latent Variable Models.**<br>
*[M. Kumar](http://mpawankumar.info/), Benjamin Packer, Daphne Koller.*<br>
NeurIPS 2010. [[PDF](https://proceedings.neurips.cc/paper/2010/file/e57c6b956a6521b28495f2886ca0977a-Paper.pdf)]

### Subset Selection

**NGC: a unified framework for learning with open-world noisy data.**<br>
*Zhi-Fan Wu, [Tong Wei](http://www.lamda.nju.edu.cn/weit/?AspxAutoDetectCookieSupport=1), Jianwen Jiang, Chaojie Mao, Mingqian Tang, Yu-Feng Li.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/papers/Wu_NGC_A_Unified_Framework_for_Learning_With_Open-World_Noisy_Data_ICCV_2021_paper.pdf)]

**Towards Understanding Deep Learning from Noisy Labels with Small-Loss Criterion.**<br>
*[Xian-Jin Gui](https://guixianjin.github.io/), [Wei Wang](http://web.cs.ucla.edu/~weiwang/), Zhang-Hao Tian.*<br>
IJCAI 2021. [[PDF](https://arxiv.org/pdf/2106.09291.pdf)]

**Robust learning by self-transition for handling noisy labels.**<br>
*[Hwanjun Song](https://songhwanjun.github.io/), [Minseok Kim](https://minseokkim.net/), Dongmin Park, Yooju Shin, [Jae-Gil Lee](https://dm.kaist.ac.kr/jaegil/).*<br>
SIGKDD 2021. [[PDF](https://arxiv.org/pdf/2012.04337.pdf)] [[Github](https://github.com/kaist-dmlab/MORPH)]

**Confident Learning: Estimating Uncertainty in Dataset Labels.**<br>
*[Curtis G. Northcutt](https://www.curtisnorthcutt.com/), [Lu Jiang](http://www.lujiang.info/), [Isaac L. Chuang](http://feynman.mit.edu/ike/homepage/index.html).*<br>
Journal of Artificial Intelligence Research 2021. [[PDF](https://dl.acm.org/doi/pdf/10.1613/jair.1.12125)] [[Github](https://github.com/cleanlab/cleanlab)] [[Project](https://cleanlab.ai/)] [[Blog](https://l7.curtisnorthcutt.com/confident-learning)]

**Crssc: salvage reusable samples from noisy data for robust learning.**<br>
*Zeren Sun, Xian-Sheng Hua, Yazhou Yao, [Xiu-Shen Wei](http://www.weixiushen.com/), Guosheng Hu, [Jian Zhang](https://profiles.uts.edu.au/Jian.Zhang).*<br>
ACM MM 2020. [[PDF](http://www.weixiushen.com/publication/acmmm_CRSSC.pdf)]

**Less is better: Unweighted data subsampling via influence function.**<br>
*[Zifeng Wang](https://zifengwang.xyz/), Hong Zhu, Zhenhua Dong, Xiuqiang He, Shao-Lun Huang.*<br>
AAAI 2020. [[PDF](https://arxiv.org/pdf/1912.01321.pdf)] [[Github](https://github.com/RyanWangZf/Influence_Subsampling)]

**Curriculum Loss: Robust Learning and Generalization against Label Corruption.**<br>
*[Yueming Lyu](https://yueminglyu.github.io/), [Ivor W. Tsang](https://www.a-star.edu.sg/cfar/about-cfar/management/prof-ivor-tsang).*<br>
ICLR 2020. [[PDF](https://arxiv.org/pdf/1905.10045.pdf)]

**A topological filter for learning with label noise.**<br>
*[Pengxiang Wu](https://pxiangwu.github.io/), [Songzhu Zheng](https://songzhu-academic-site.netlify.app/), [Mayank Goswami](https://boole.cs.qc.cuny.edu/mgoswami/), [Dimitris N. Metaxas](https://people.cs.rutgers.edu/~dnm/), [Chao Chen](https://chaochen.github.io/).*<br>
NeurIPS 2020. [[PDF](https://proceedings.neurips.cc/paper/2020/file/f4e3ce3e7b581ff32e40968298ba013d-Paper.pdf)] [[Github](https://github.com/pxiangwu/TopoFilter)]

**Identifying mislabeled data using the area under the margin ranking.**<br>
*[Geoff Pleiss](https://geoffpleiss.com/), [Tianyi Zhang](https://tiiiger.github.io/), [Ethan Elenberg](http://eelenberg.github.io/), [Kilian Q. Weinberger](https://www.cs.cornell.edu/~kilian/).*<br>
NeurIPS 2020. [[PDF](https://proceedings.neurips.cc/paper/2020/file/c6102b3727b2a7d8b1bb6981147081ef-Paper.pdf)] [[Github](https://github.com/asappresearch/aum)] [[Project](https://geoffpleiss.com/aum#list_of_mislabeled_examples)]

**O2u-net: A simple noisy label detection approach for deep neural networks.**<br>
*Jinchi Huang, Lie Qu, Rongfei Jia, Binqiang Zhao.*<br>
ICCV 2019. [[PDF](https://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_O2U-Net_A_Simple_Noisy_Label_Detection_Approach_for_Deep_Neural_ICCV_2019_paper.pdf)]

**Understanding and utilizing deep neural networks trained with noisy labels.**<br>
*Pengfei Chen, [Benben Liao](https://sites.google.com/view/benliao), [Guangyong Chen](https://guangyongchen.github.io/), [Shengyu Zhang](http://www.cse.cuhk.edu.hk/~syzhang/).*<br>
ICML 2019. [[PDF](http://proceedings.mlr.press/v97/chen19g/chen19g.pdf)] [[Github](https://github.com/chenpf1025/noisy_label_understanding_utilizing)]

**Learning with bad training data via iterative trimmed loss minimization.**<br>
*[Yanyao Shen](https://yanyao-shen.github.io/), [Sujay Sanghavi](http://users.ece.utexas.edu/~sanghavi/).*<br>
ICML 2019. [[PDF](http://proceedings.mlr.press/v97/shen19e/shen19e.pdf)]

**How does disagreement help generalization against label corruption?**<br>
*[Xingrui Yu](https://xingruiyu.github.io/), [Bo Han](https://bhanml.github.io/), [Jiangchao Yao](https://sunarker.github.io/), [Gang Niu](https://niug1984.github.io/), [Ivor W. Tsang](https://www.a-star.edu.sg/cfar/about-cfar/management/prof-ivor-tsang), [Masashi Sugiyama](http://www.ms.k.u-tokyo.ac.jp/sugi/index.html).*<br>
ICML 2019. [[PDF](http://proceedings.mlr.press/v97/yu19b/yu19b.pdf)]

**SELFIE: Refurbishing Unclean Samples for Robust Deep Learning.**<br>
*[Hwanjun Song](https://songhwanjun.github.io/), [Minseok Kim](https://minseokkim.net/), [Jae-Gil Lee](https://dm.kaist.ac.kr/jaegil/).*<br>
ICML 2019. [[PDF](http://proceedings.mlr.press/v97/song19b/song19b.pdf)] [[Github](https://github.com/kaist-dmlab/SELFIE)]

**Self: Learning to filter noisy labels with self-ensembling**<br>
*Duc Tam Nguyen, Chaithanya Kumar Mummadi, Thi Phuong Nhung Ngo, Thi Hoai Phuong Nguyen, Laura Beggel, Thomas Brox.*<br>
Arxiv 2019. [[PDF](https://arxiv.org/pdf/1910.01842.pdf)]

**Mentornet: Learning data-driven curriculum for very deep neural networks on corrupted labels.**<br>
*[Lu Jiang](http://www.lujiang.info/), [Zhengyuan Zhou](https://pages.stern.nyu.edu/~zzhou/?_ga=2.185698473.1447976582.1624993264-1707137673.1537489937), Thomas Leung, [Li-Jia Li](http://vision.stanford.edu/lijiali/), [Li Fei-Fei](http://vision.stanford.edu/).*<br>
ICML 2018. [[PDF](http://proceedings.mlr.press/v80/jiang18c/jiang18c.pdf)]

**Co-teaching: Robust Training of Deep Neural Networks with Extremely Noisy Labels.**<br>
*[Bo Han](https://bhanml.github.io/), [Quanming Yao](https://lars-group.github.io/), [Xingrui Yu](https://xingruiyu.github.io/), [Gang Niu](https://niug1984.github.io/), [Miao Xu](https://researchers.uq.edu.au/researcher/26509), [Weihua Hu](http://web.stanford.edu/~weihuahu/), [Ivor W. Tsang](https://www.a-star.edu.sg/cfar/about-cfar/management/prof-ivor-tsang), [Masashi Sugiyama](http://www.ms.k.u-tokyo.ac.jp/sugi/index.html).*<br>
NeurIPS 2018. [[PDF](https://proceedings.neurips.cc/paper/2018/file/a19744e268754fb0148b017647355b7b-Paper.pdf)]

**Decoupling "when to update" from "how to update".**<br>
*Eran Malach, [Shai Shalev-Shwartz](https://www.cs.huji.ac.il/~shais/).*<br>
NeurIPS 2017. [[PDF](https://proceedings.neurips.cc/paper/2017/file/58d4d1e7b1e97b258c9ed0b37e02d087-Paper.pdf)] [[Github](https://github.com/emalach/UpdateByDisagreement)]

**Learning with confident examples: Rank pruning for robust classification with noisy labels.**<br>
*[Curtis G. Northcutt](https://www.curtisnorthcutt.com/), [Tailin Wu](https://tailin.org/), [Isaac L. Chuang](http://feynman.mit.edu/ike/homepage/index.html).*<br>
Arxiv 2017. [[PDF](https://arxiv.org/pdf/1705.01936.pdf)] [[Github](https://github.com/cgnorthcutt/rankpruning)]

**A domain robust approach for image dataset construction.**<br>
*Yazhou Yao, Xian-sheng Hua, [Fumin Shen](https://cfm.uestc.edu.cn/~fshen/), [Jian Zhang](https://profiles.uts.edu.au/Jian.Zhang), Zhenmin Tang.*<br>
ACM MM 2016. [[PDF](https://kd.nsfc.gov.cn/paperDownload/ZD4242585.pdf)]

<p width="100%" align="right"><a href="https://github.com/Vivian-wzj/DataOptimization-CV/edit/main/README.md#dataoptimization-cv">🔝</a></p>

# Data Optimization for Fair Learning

Coming soon!

# Data Optimization for Data-efficient Learning

Coming soon!

# Data Optimization for Label-efficient Learning

Coming soon!

If you find this repo or our paper is helpful for your research, please consider to cite:

```bibtex
@article{wan2022survey,
  title={A Survey of Data Optimization for Problems in Computer Vision Datasets},
  author={Wan, Zhijing and Wang, Zhixiang and Chung, CheukTing and Wang, Zheng},
  journal={arXiv preprint arXiv:2210.11717},
  year={2022}
}
```
<p width="100%" align="right"><a href="https://github.com/Vivian-wzj/DataOptimization-CV/edit/main/README.md#dataoptimization-cv">🔝</a></p>
