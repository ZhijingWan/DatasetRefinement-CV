# DataOptimization-CV

<br />
<p align="left">
    <a href='https://arxiv.org/pdf/2210.11717.pdf'>
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

- [News](#news)
- [Data Optimization for Robust Learning](#data-optimization-for-robust-learning)
- [Data Optimization for Fair Learning](#data-optimization-for-data-efficient-learning)
- [Data Optimization for Data-efficient Learning](#data-optimization-for-label-efficient-learning)
- [Data Optimization for Label-efficient Learning](#data-optimization-for-label-efficient-learning)
- [Related Search](#related-search)

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

<p width="100%" align="right"><a href="#dataoptimization-cv">🔝</a></p>

# Data Optimization for Fair Learning

### Subset Selection

**Adversarial filters of dataset biases.**<br>
*[Ronan Le Bras](https://allenai.org/team/ronanl), [Swabha Swayamdipta](https://swabhs.com/), [Chandra Bhagavatula](https://www.chandrab.page/), [Rowan Zellers](http://rowanzellers.com/), Matthew Peters, [Ashish Sabharwal](http://ashishs.people.allenai.org/), [Yejin Choi](https://homes.cs.washington.edu/~yejin/).*<br>
ICML 2020. [[PDF](http://proceedings.mlr.press/v119/bras20a/bras20a.pdf)] [[Github](https://github.com/swabhs/notebooks_for_aflite)]

**Repair: Removing representation bias by dataset resampling.**<br>
*[Yi Li](http://www.svcl.ucsd.edu/people/yili/), [Nuno Vasconcelos](http://www.svcl.ucsd.edu/~nuno).*<br>
CVPR 2019. [[PDF](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_REPAIR_Removing_Representation_Bias_by_Dataset_Resampling_CVPR_2019_paper.pdf)] [[Github](https://github.com/JerryYLi/Dataset-REPAIR/)]

**Resound: Towards action recognition without representation bias.**<br>
*Yingwei Li, [Yi Li](http://www.svcl.ucsd.edu/people/yili/), [Nuno Vasconcelos](http://www.svcl.ucsd.edu/~nuno).*<br>
ECCV 2018. [[PDF](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yingwei_Li_RESOUND_Towards_Action_ECCV_2018_paper.pdf)]

<p width="100%" align="right"><a href="#dataoptimization-cv">🔝</a></p>

# Data Optimization for Data-efficient Learning

### Data Sampling

**Variance reduced training with stratified sampling for forecasting models.**<br>
*[Yucheng Lu](http://www.cs.cornell.edu/~yucheng/), [Youngsuk Park](https://youngsuk0723.github.io/), Lifan Chen, Yuyang Wang, Christopher De Sa, Dean Foster.*<br>
ICML 2021. [[PDF](http://proceedings.mlr.press/v139/lu21d/lu21d.pdf)]

**Curriculum learning by dynamic instance hardness.**<br>
*[Tianyi Zhou](https://tianyizhou.github.io/), [Shengjie Wang](https://wsjloomise.github.io/), [Jeffrey Bilmes](https://people.ece.uw.edu/bilmes/p/pgs/index.html).*<br>
NeurIPS 2020. [[PDF](https://proceedings.neurips.cc/paper/2020/file/62000dee5a05a6a71de3a6127a68778a-Paper.pdf)] [[Github](https://github.com/tianyizhou/DIHCL)]

**Ordered sgd: A new stochastic optimization framework for empirical risk minimization.**<br>
*[Kenji Kawaguchi](https://ml.comp.nus.edu.sg/), [Haihao Lu](https://faculty.chicagobooth.edu/haihao-lu).*<br>
AISTATS 2020. [[PDF](http://proceedings.mlr.press/v108/kawaguchi20a/kawaguchi20a.pdf)]

**Accelerating Minibatch Stochastic Gradient Descent Using Typicality Sampling.**<br>
*Xinyu Peng, Li Li, [Fei-Yue Wang](http://www.compsys.ia.ac.cn/people/wangfeiyue.html).*<br>
TNNLS 2019. [[PDF](https://sci-hub.se/10.1109/tnnls.2019.2957003)]

**Accelerating deep learning by focusing on the biggest losers.**<br>
*Angela H. Jiang, [Daniel Lin-Kit Wong](https://wonglkd.fi-de.net/), Giulio Zhou, [David G. Andersen](http://www.cs.cmu.edu/~dga/), Jeffrey Dean, Gregory R. Ganger, Gauri Joshi, Michael Kaminksy, Michael Kozuch, Zachary C. Lipton, Padmanabhan Pillai.*<br>
Arxiv 2019. [[PDF](https://arxiv.org/pdf/1910.00762.pdf)]

**Variance reduction in sgd by distributed importance sampling.**<br>
*Guillaume Alain, Alex Lamb, [Chinnadhurai Sankar](https://chinnadhurai.github.io/), [Aaron Courville](https://aaroncourville.wordpress.com/), [Yoshua Bengio](https://yoshuabengio.org/).*<br>
Arxiv 2015. [[PDF](https://arxiv.org/pdf/1511.06481.pdf)]

**Accelerating minibatch stochastic gradient descent using stratified sampling.**<br>
*[Peilin Zhao](https://peilinzhao.github.io/), [Tong Zhang](http://tongzhang-ml.org/).*<br>
Arxiv 2014. [[PDF](https://arxiv.org/pdf/1405.3080.pdf)]

### Subset Selection

**Adaptive second order coresets for data-efficient machine learning.**<br>
*Omead Pooladzandi, David Davini, [Baharan Mirzasoleiman](http://web.cs.ucla.edu/~baharan/).*<br>
ICML 2022. [[PDF](https://proceedings.mlr.press/v162/pooladzandi22a/pooladzandi22a.pdf)] [[Github](https://github.com/opooladz/AdaCore)]

**Online coreset selection for rehearsal-based continual learning.**<br>
*[Jaehong Yoon](https://jaehong31.github.io/), [Divyam Madaan](https://dmadaan.com/), Eunho Yang, [Sung Ju Hwang](http://www.sungjuhwang.com/index.php/sample-page/).*<br>
ICLR 2022. [[PDF](https://arxiv.org/pdf/2106.01085.pdf)]

**AUTOMATA: Gradient Based Data Subset Selection for Compute-Efficient Hyper-parameter Tuning.**<br>
*[Krishnateja Killamsetty](https://krishnatejakillamsetty.me/), Guttu Sai Abhishek, Aakriti, Alexandre V. Evfimievski, [Lucian Popa](https://researcher.watson.ibm.com/researcher/view.php?person=us-lpopa), [Ganesh Ramakrishnan](https://www.cse.iitb.ac.in/~ganesh/), [Rishabh Iyer](https://www.rishiyer.com/).*<br>
Arxiv 2022. [[PDF](https://arxiv.org/pdf/2203.08212.pdf)] [[Github](https://github.com/decile-team/cords)]

**Glister: Generalization based data subset selection for efficient and robust learning.**<br>
*[Krishnateja Killamsetty](https://krishnatejakillamsetty.me/), Durga Sivasubramanian, [Ganesh Ramakrishnan](https://www.cse.iitb.ac.in/~ganesh/), [Rishabh Iyer](https://www.rishiyer.com/).*<br>
AAAI 2021. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/16988/16795)] [[Github](https://github.com/dssresearch/GLISTER)] [[Project](https://cords.readthedocs.io/en/latest/strategies/cords.selection_strategies.SL.html#module-cords.selectionstrategies.SL.glisterstrategy)]

**Grad-match: Gradient matching based data subset selection for efficient deep model training.**<br>
*[Krishnateja Killamsetty](https://krishnatejakillamsetty.me/), Durga Sivasubramanian, [Ganesh Ramakrishnan](https://www.cse.iitb.ac.in/~ganesh/), [Abir De](https://people.mpi-sws.org/~ade/index.html), [Rishabh Iyer](https://www.rishiyer.com/).*<br>
ICML 2021. [[PDF](http://proceedings.mlr.press/v139/killamsetty21a/killamsetty21a.pdf)] [[Github](https://github.com/decile-team/cords)] [[Project](https://cords.readthedocs.io/en/latest/strategies/cords.selection_strategies.SL.html#module-cords.selectionstrategies.SL.gradmatchstrategy)]

**Retrieve: Coreset selection for efficient and robust semi-supervised learning.**<br>
*[Krishnateja Killamsetty](https://krishnatejakillamsetty.me/), [Xujiang Zhao](https://zxj32.github.io/), [Feng Chen](https://personal.utdallas.edu/~fxc190007/), [Rishabh Iyer](https://www.rishiyer.com/).*<br>
NeurIPS 2021. [[PDF](https://proceedings.neurips.cc/paper/2021/file/793bc52a941b3951dfdb85fb04f9fd06-Paper.pdf)] [[Github](https://github.com/decile-team/cords)] [[Project](https://cords.readthedocs.io/en/latest/strategies/cords.selection_strategies.SSL.html#module-cords.selectionstrategies.SSL.retrievestrategy)]

**Deep learning on a data diet: Finding important examples early in training.**<br>
*Mansheej Paul, [Surya Ganguli](https://ganguli-gang.stanford.edu/surya.html), Gintare Karolina Dziugaite.*<br>
NeurIPS 2021. [[PDF](https://proceedings.neurips.cc/paper/2021/file/ac56f8fe9eea3e4a365f29f0f1957c55-Paper.pdf)]

**Coresets for data-efficient training of machine learning models.**<br>
*[Baharan Mirzasoleiman](http://web.cs.ucla.edu/~baharan/), [Jeff Bilmes](https://people.ece.uw.edu/bilmes/p/pgs/index.html), [Jure Leskovec](https://cs.stanford.edu/~jure/).*<br>
ICML 2020. [[PDF](http://proceedings.mlr.press/v119/mirzasoleiman20a/mirzasoleiman20a.pdf)]

**Selection via proxy: Efficient data selection for deep learning.**<br>
*[Cody Coleman](https://www.codycoleman.com/), [Christopher Yeh](https://chrisyeh96.github.io/), [Stephen Mussmann](https://stephen.mussmann.xyz/), [Baharan Mirzasoleiman](http://web.cs.ucla.edu/~baharan/), [Peter Bailis](http://www.bailis.org/), [Percy Liang](https://cs.stanford.edu/~pliang/), [Jure Leskovec](https://cs.stanford.edu/~jure/), [Matei Zaharia](https://cs.stanford.edu/~matei/).*<br>
ICLR 2020. [[PDF](https://openreview.net/pdf?id=HJg2b0VYDr)] [[Github](https://github.com/stanford-futuredata/selection-via-proxy)]

**Coresets via bilevel optimization for continual learning and streaming.**<br>
*Zalán Borsos, Mojmir Mutny, Andreas Krause.*<br>
NeurIPS 2020. [[PDF](https://proceedings.neurips.cc/paper/2020/file/aa2a77371374094fe9e0bc1de3f94ed9-Paper.pdf)] [[Github](https://github.com/zalanborsos/bilevel_coresets)]

**Coresets for robust training of deep neural networks against noisy labels.**<br>
*[Baharan Mirzasoleiman](http://web.cs.ucla.edu/~baharan/), [Kaidi Cao](https://ai.stanford.edu/~kaidicao/), [Jure Leskovec](https://cs.stanford.edu/~jure/).*<br>
NeurIPS 2020. [[PDF](https://proceedings.neurips.cc/paper/2020/file/8493eeaccb772c0878f99d60a0bd2bb3-Paper.pdf)] [[Github](https://github.com/snap-stanford/crust)]

**Data shapley: Equitable valuation of data for machine learning.**<br>
*[Amirata Ghorbani](https://www.amiratag.com/), [James Zou](https://www.james-zou.com/).*<br>
ICML 2019. [[PDF](http://proceedings.mlr.press/v97/ghorbani19c/ghorbani19c.pdf)] [[Github](https://github.com/amiratag/DataShapley)]

**An empirical study of example forgetting during deep neural network learning.**<br>
*[Mariya Toneva](http://mtoneva.com/), Alessandro Sordoni, Remi Tachet des Combes, [Adam Trischler](https://www.microsoft.com/en-us/research/people/adtrisch/), [Yoshua Bengio](https://yoshuabengio.org/), Geoffrey J. Gordon.*<br>
ICLR 2019. [[PDF](https://arxiv.org/pdf/1812.05159.pdf)] [[Github](https://github.com/mtoneva/example_forgetting)]

**Gradient based sample selection for online continual learning.**<br>
*[Rahaf Aljundi](http://rahafaljundi.com/), [Min Lin](https://linmin.me/), Baptiste Goujaud, [Yoshua Bengio](https://yoshuabengio.org/).*<br>
NeurIPS 2019. [[PDF](https://proceedings.neurips.cc/paper/2019/file/e562cd9c0768d5464b64cf61da7fc6bb-Paper.pdf)] [[Github](https://github.com/rahafaljundi/Gradient-based-Sample-Selection)]

**E2-train: Training state-of-the-art cnns with over 80% energy savings.**<br>
*Yue Wang, [Ziyu Jiang](https://geekjzy.github.io/), [Xiaohan Chen](http://xiaohanchen.com/), [Pengfei Xu](https://sites.google.com/view/pengfei-xu/home), [Yang Zhao](https://www.yangkatiezhao.net/), Yingyan Lin, [Zhangyang Wang](https://vita-group.github.io/).*<br>
NeurIPS 2019. [[PDF](https://proceedings.neurips.cc/paper/2019/file/663772ea088360f95bac3dc7ffb841be-Paper.pdf)] [[Project](https://rtml.eiclab.net/code/)]

**Semantic Redundancies in Image-Classification Datasets: The 10% You Don't Need.**<br>
*[Vighnesh Birodkar](http://vighneshbirodkar.github.io/), [Hossein Mobahi](http://people.csail.mit.edu/hmobahi/), [Samy Bengio](https://bengio.abracadoudou.com/).*<br>
Arxiv 2019. [[PDF](https://arxiv.org/pdf/1901.11409.pdf)]

**Selective experience replay for lifelong learning.**<br>
*David Isele, Akansel Cosgun.*<br>
AAAI 2018. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/11595/11454)]

**Learning what data to learn.**<br>
*[Yang Fan](https://fyabc.github.io/), [Fei Tian](https://ustctf.github.io/), [Tao Qin](https://www.microsoft.com/en-us/research/people/taoqin/?from=http%3A%2F%2Fresearch.microsoft.com%2F%7Etaoqin), [Jiang Bian](https://sites.google.com/view/jiangbian), [Tie-Yan Liu](https://www.microsoft.com/en-us/research/people/tyliu/?from=http%3A%2F%2Fresearch.microsoft.com%2Fusers%2Ftyliu).*<br>
Arxiv 2017. [[PDF](https://arxiv.org/pdf/1702.08635.pdf)]

**Training region-based object detectors with online hard example mining.**<br>
*[Abhinav Shrivastava](https://www.cs.umd.edu/~abhinav/), [Abhinav Gupta](http://www.cs.cmu.edu/~abhinavg), [Ross Girshick](http://www.rossgirshick.info/).*<br>
CVPR 2016. [[PDF](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Shrivastava_Training_Region-Based_Object_CVPR_2016_paper.pdf)]

**Coresets for nonparametric estimation-the case of DP-means.**<br>
*[Olivier Bachem](http://olivierbachem.ch/), [Mario Lucic](https://lucic.ai/), [Andreas Krause](https://las.inf.ethz.ch/krausea).*<br>
ICML 2015. [[PDF](http://proceedings.mlr.press/v37/bachem15.pdf)]

<p width="100%" align="right"><a href="#dataoptimization-cv">🔝</a></p>

# Data Optimization for Label-efficient Learning

### Active Learning

**Low-Shot Validation: Active Importance Sampling for Estimating Classifier Performance on Rare Categories.**<br>
*[Fait Poms](https://cs.stanford.edu/~fpoms/), Vishnu Sarukkai, Ravi Teja Mullapudi, Nimit S. Sohoni, [William R. Mark](http://www.billmark.com/), [Deva Ramanan](http://www.cs.cmu.edu/~deva/), [Kayvon Fatahalian](http://graphics.stanford.edu/~kayvonf/).*<br>
ICCV 2021. [[PDF]([https://ojs.aaai.org/index.php/AAAI/article/view/16988/16795](https://openaccess.thecvf.com/content/ICCV2021/papers/Poms_Low-Shot_Validation_Active_Importance_Sampling_for_Estimating_Classifier_Performance_on_ICCV_2021_paper.pdf))]

**Glister: Generalization based data subset selection for efficient and robust learning.**<br>
*[Krishnateja Killamsetty](https://krishnatejakillamsetty.me/), Durga Sivasubramanian, [Ganesh Ramakrishnan](https://www.cse.iitb.ac.in/~ganesh/), [Rishabh Iyer](https://www.rishiyer.com/).*<br>
AAAI 2021. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/16988/16795)] [[Github](https://github.com/dssresearch/GLISTER)] [[Project](https://cords.readthedocs.io/en/latest/strategies/cords.selection_strategies.SL.html#module-cords.selectionstrategies.SL.glisterstrategy)]

**Deep batch active learning by diverse, uncertain gradient lower bounds.**<br>
*[Jordan T. Ash](http://www.jordantash.com/), [Chicheng Zhang](https://zcc1307.github.io/), [Akshay Krishnamurthy](https://people.cs.umass.edu/~akshay/), [John Langford](https://hunch.net/~jl/), [Alekh Agarwal](https://alekhagarwal.net/).*<br>
ICLR 2020. [[PDF](https://arxiv.org/pdf/1906.03671.pdf)]

**Single shot active learning using pseudo annotators.**<br>
*Yazhou Yang, Marco Loog.*<br>
Pattern Recognition 2019. [[PDF](https://arxiv.org/pdf/1805.06660.pdf)]

**The power of ensembles for active learning in image classification.**<br>
*William H. Beluch, [Tim Genewein](http://tim.inversetemperature.net/), [Andreas Nürnberger](https://www.dke.ovgu.de/en/), [Jan Mathias Köhler](https://enable-ai.de/).*<br>
CVPR 2018. [[PDF](https://openaccess.thecvf.com/content_cvpr_2018/papers/Beluch_The_Power_of_CVPR_2018_paper.pdf)]

**Active learning for convolutional neural networks: A core-set approach.**<br>
*[Ozan Sener](http://ozansener.net/), [Silvio Savarese](https://profiles.stanford.edu/silvio-savarese).*<br>
ICLR 2018. [[PDF](https://arxiv.org/pdf/1708.00489.pdf),)]

**Meta-learning for batch mode active learning.**<br>
*[Sachin Ravi](https://sachinravi14.github.io/), [Hugo Larochelle](https://mila.quebec/en/person/hugo-larochelle/).*<br>
ICLR Workshop 2018. [[PDF](https://openreview.net/pdf?id=r1PsGFJPz)]

**Optimization as a model for few-shot learning.**<br>
*[Sachin Ravi](https://sachinravi14.github.io/), [Hugo Larochelle](https://mila.quebec/en/person/hugo-larochelle/).*<br>
ICLR 2017. [[PDF](https://openreview.net/pdf?id=rJY0-Kcll)] [[Github](https://github.com/twitter/meta-learning-lstm)]

**Learning how to active learn: A deep reinforcement learning approach.**<br>
*[Meng Fang](https://mengf1.github.io/), Yuan Li, [Trevor Cohn](https://people.eng.unimelb.edu.au/tcohn/).*<br>
EMNLP 2017. [[PDF](https://arxiv.org/pdf/1708.02383.pdf)] [[Github](https://github.com/mengf1/PAL)]

**Deep active learning for image classification.**<br>
*Hiranmayi Ranganathan, [Hemanth Venkateswara](https://www.hemanthdv.org/), [Shayok Chakraborty](http://shayokch.com/), Sethuraman Panchanathan.*<br>
ICIP 2017. [[PDF](https://sci-hub.se/10.1109/ICIP.2017.8297020)]

**A meta-learning approach to one-step active learning.**<br>
*[Gabriella Contardo](https://contardog.github.io/), Ludovic Denoyer, [Thierry Artieres](https://pageperso.lis-lab.fr/thierry.artieres/).*<br>
Arxiv 2017. [[PDF](https://arxiv.org/pdf/1706.08334.pdf)]

**Submodularity in data subset selection and active learning.**<br>
*Kai Wei, [Rishabh Iyer](https://www.rishiyer.com/), [Jeff Bilmes](https://people.ece.uw.edu/bilmes/p/pgs/index.html).*<br>
ICML 2015. [[PDF](http://proceedings.mlr.press/v37/wei15.pdf)]

**A convex optimization framework for active learning.**<br>
*[Ehsan Elhamifar](http://khoury.northeastern.edu/home/eelhami/), [Guillermo Sapiro](http://sapirolab.pratt.duke.edu/), [Allen Yang](https://people.eecs.berkeley.edu/~yang/), [S. Shankar Sasrty](https://people.eecs.berkeley.edu/~sastry/).*<br>
ICCV 2013. [[PDF](https://openaccess.thecvf.com/content_iccv_2013/papers/Elhamifar_A_Convex_Optimization_2013_ICCV_paper.pdf)]

**Active instance sampling via matrix partition.**<br>
*[Yuhong Guo](http://people.scs.carleton.ca/~yuhongguo/).*<br>
NeurIPS 2010. [[PDF](https://proceedings.neurips.cc/paper/2010/file/f29c21d4897f78948b91f03172341b7b-Paper.pdf)]

**Batch-mode active-learning methods for the interactive classification of remote sensing images.**<br>
*[Begüm Demir](https://rsim.berlin/), [Claudio Persello](https://sites.google.com/site/cpersello), [Lorenzo Bruzzone](https://rslab.disi.unitn.it/).*<br>
IEEE Trans Geosci Remote Sens 2010. [[PDF](http://eprints.biblio.unitn.it/1865/1/DISI-10-041.pdf)]

**Multi-class active learning for image classification.**<br>
*Ajay J. Joshi, [Fatih Porikli](https://www.porikli.com/), [Nikolaos Papanikolopoulos](https://www-users.cse.umn.edu/~papan001/).*<br>
CVPR 2009. [[PDF](https://www.merl.com/publications/docs/TR2009-034.pdf)]

**Active learning using pre-clustering.**<br>
*Hieu T. Nguyen, Arnold Smeulders.*<br>
ICML 2004. [[PDF](https://sci-hub.se/10.1145/1015330.1015349)]

<p width="100%" align="right"><a href="#dataoptimization-cv">🔝</a></p>

# Related Search

## Dataset distillation/condensation

**Dataset distillation by matching training trajectories.**<br>
*[George Cazenavette](https://georgecazenavette.github.io/), [Tongzhou Wang](https://www.tongzhouwang.info/), [Antonio Torralba](https://groups.csail.mit.edu/vision/torralbalab/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/), [Jun-Yan Zhu](https://www.cs.cmu.edu/~junyanz/).*<br>
CVPR 2022. [[PDF](https://openaccess.thecvf.com/content/CVPR2022W/VDU/papers/Cazenavette_Dataset_Distillation_by_Matching_Training_Trajectories_CVPRW_2022_paper.pdf)] [[Github](https://github.com/GeorgeCazenavette/mtt-distillation)] [[Project](https://georgecazenavette.github.io/mtt-distillation/)]

**Dataset Condensation with Gradient Matching.**<br>
*[Bo Zhao](https://bozhaonanjing.wixsite.com/mysite), [Konda Reddy Mopuri](https://krmopuri.github.io/), [Hakan Bilen](https://homepages.inf.ed.ac.uk/hbilen/).*<br>
ICLR 2021. [[PDF](https://www.pure.ed.ac.uk/ws/files/202549394/main.pdf)]

**Dataset distillation.**<br>
*[Tongzhou Wang](https://www.tongzhouwang.info/), [Jun-Yan Zhu](https://www.cs.cmu.edu/~junyanz/), [Antonio Torralba](https://groups.csail.mit.edu/vision/torralbalab/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/).*<br>
Arxiv 2018. [[PDF](https://arxiv.org/pdf/1811.10959.pdf)]

## Other Surveys

**A survey on curriculum learning.**<br>
*[Xin Wang](http://mn.cs.tsinghua.edu.cn/xinwang/), Yudong Chen, Wenwu Zhu.*<br>
TPAMI 2022. [[PDF](https://arxiv.org/pdf/2010.13166.pdf)]

**A Survey on Active Deep Learning: From Model Driven to Data Driven.**<br>
*Peng Liu, Lizhe Wang, [Rajiv Ranjan](https://rajivranjan.net/), Guojin He, Lei Zhao.*<br>
ACM Comput. Surv. 2022. [[PDF](https://dl.acm.org/doi/abs/10.1145/3510414)]

**Learning from noisy labels with deep neural networks: A survey.**<br>
*[Hwanjun Song](https://songhwanjun.github.io/), [Minseok Kim](https://minseokkim.net/), [Dongmin Park](https://sites.google.com/view/dongmin-park/%ED%99%88), Yooju Shin, [Jae-Gil Lee](https://dm.kaist.ac.kr/jaegil/).*<br>
TNNLS 2022. [[PDF](https://arxiv.org/pdf/2007.08199.pdf)] [[Github](https://github.com/songhwanjun/Awesome-Noisy-Labels)]

**A survey on bias in visual datasets.**<br>
*Simone Fabbrizzi, [Symeon Papadopoulos](https://sites.google.com/site/sympapadopoulos/), [Eirini Ntoutsi](https://aiml-research.github.io/), [Ioannis Kompatsiaris](https://mklab.iti.gr/).*<br>
CVIU 2022. [[PDF](https://arxiv.org/pdf/2107.07919.pdf)]

**DeepCore: A Comprehensive Library for Coreset Selection in Deep Learning.**<br>
*Chengcheng Guo, Bo Zhao, Yanbing Bai.*<br>
Arxiv 2022. [[PDF](https://arxiv.org/pdf/2204.08499.pdf)] [[Github](https://github.com/PatrickZH/DeepCore)]

**Data Collection and Quality Challenges in Deep Learning: A Data-Centric AI Perspective.**<br>
*[Steven Euijong Whang](https://sites.google.com/view/whanglab/di-lab), [Yuji Roh](https://www.yujiroh.com/), [Hwanjun Song](https://songhwanjun.github.io/), [Jae-Gil Lee](https://dm.kaist.ac.kr/jaegil/).*<br>
Arxiv 2021. [[PDF](https://arxiv.org/pdf/2112.06409.pdf)]

**Deep long-tailed learning: A survey.**<br>
*[Yifan Zhang](https://sites.google.com/view/yifan-zhang/%E9%A6%96%E9%A1%B5), Bingyi Kang, [Bryan Hooi](https://bhooi.github.io/), [Shuicheng Yan](https://yanshuicheng.ai/), [Jiashi Feng](https://sites.google.com/site/jshfeng/).*<br>
Arxiv 2021. [[PDF](https://arxiv.org/pdf/2110.04596.pdf)] [[Github](https://github.com/Vanint/Awesome-LongTailed-Learning)]

**A Survey on Deep Learning with Noisy Labels: How to train your model when you cannot trust on the annotations?.**<br>
*Filipe R. Cordeiro, [Gustavo Carneiro](https://cs.adelaide.edu.au/~carneiro/).*<br>
SIBGRAPI 2020. [[PDF](https://arxiv.org/pdf/2012.03061.pdf)]

**A review of instance selection methods.**<br>
*[J. Arturo Olvera-López](http://www.cs.buap.mx/~aolvera/), [J. Ariel Carrasco-Ochoa](http://ccc.inaoep.mx/~ariel/), [J. Francisco Martínez-Trinidad](http://ccc.inaoep.mx/~fmartine/), Josef Kittler.*<br>
Artif Intell Rev 2010. [[PDF](https://inaoe.repositorioinstitucional.mx/jspui/bitstream/1009/1389/1/165.-CC.pdf)]


If you find this repo or our paper is helpful for your research, please consider to cite:

```bibtex
@article{wan2022survey,
  title={A Survey of Data Optimization for Problems in Computer Vision Datasets},
  author={Wan, Zhijing and Wang, Zhixiang and Chung, CheukTing and Wang, Zheng},
  journal={arXiv preprint arXiv:2210.11717},
  year={2022}
}
```
<p width="100%" align="right"><a href="#dataoptimization-cv">🔝</a></p>
