---
layout: frontpage
title: Ximeng Sun - AMD GenAI

---

<div class="navbar">
<div class="navbar-inner">
<ul class="nav">
<li><a href="https://www.linkedin.com/in/ximeng-sun-a8a9ab13a/">LinkedIn</a></li>
<li><a href="https://github.com/sunxm2357">Github</a></li>
<li><a href="https://scholar.google.com/citations?user=iegEnEwAAAAJ">Google Scholar</a></li>
</ul>
</div>
</div>


---
<div class="container">
<div class="span8">
<table>
<tr>
<td> Hello, I am a research scientist at AMD GenAI Team. I am interested in the deep learning and computer vision. In particular, I work on efficient learning, vision-language models, and multi-task learning.

I earned my Ph.D. degree from Computer Science at Boston University starting from 2019 Spring, supervised by  <a href="http://ai.bu.edu/ksaenko.html">Prof. Kate Saenko</a>. 
During my Ph.D. study, I have been fortunate to collaborate with top research labs as an intern, including Meta AI, Google Cloud and IBM Research. During 2022, I was part of Meta AI's team where I had the opportunity to collaborate with <a href="https://xidexia.github.io/">Xide Xia</a>, <a href="https://pzzhang.github.io/pzzhang/">Pengchuan Zhang</a> and <a href="https://research.facebook.com/people/zhang-peizhao/">Peizhao Zhang</a>.  In 2021 Summer, I joined Google Cloud where I worked closely with  <a href="https://scholar.google.com/citations?user=Vu3vH2sAAAAJ&hl=en">Clayton Mellina</a>, <a href="https://scholar.google.com/citations?user=ZpF26loAAAAJ&hl=en">Xiao Bian</a> and <a href="https://scholar.google.com/citations?user=VxpypngAAAAJ&hl=en">Kihyuk Sohn</a>.  In 2019 and 2020 Summer, I worked alongside <a href="http://rogerioferis.com/">Rogerio Feris</a> and <a href="https://rpand002.github.io/ ">Rameswar Panda</a> at IBM Research.
<br/>
<br/>
Previously, I received my M.S. in ECE from University of Michigan, Ann Arbor and received B.ENG. in Communication Engineering from Beijing University of Posts and Telecommunications.
<br/>
<br/> </td>
<td><img src="../assets/pics/ximeng.png" title="Ximeng Sun" alt="Ximeng Sun" height="600"/> </td>
</tr>
</table>

</div>
</div>


---
<h2><a name="publication"></a>Publications</h2>


<h3>Conferences</h3>
<ul>

<li>Reuben Tan, <strong> Ximeng Sun </strong>, Ping Hu, Jui-hsien Wang, Hanieh Deilamsalehy, Bryan A. Plummer, Bryan Russell, Kate Saenko "Koala: Key frame-conditioned long video-LLM". CVPR 2024 </li>
<p><a href="https://arxiv.org/pdf/2303.18232.pdf">pdf</a> / <a href="https://github.com/sunxm2357/DIME-FM">code</a></p>


<li><strong>Ximeng Sun</strong>, Rameswar Panda, Chun-Fu Chen, Naigang Wang, Bowen Pan, Aude Oliva, Rogerio Feris, Kate Saenko, "All at Once Network Quantization via Collaborative Knowledge Transfer", WACV 2024  </li>
<p><a href="">pdf</a> / <a href="">code</a> </p>

<li><strong>Ximeng Sun</strong>,  Pengchuan Zhang, Peizhao Zhang, Hardik Shah, Kate Saenko, Xide Xia. "DIME-FM: DIstilling Multimodal and Efficient Foundation Models". ICCV 2023.</li>
<p><a href="https://arxiv.org/pdf/2303.18232.pdf">pdf</a> / <a href="https://github.com/sunxm2357/DIME-FM">code</a></p>

[//]: # (<p><strong>Overview</strong>: Large Vision-Language Foundation Models &#40;VLFM&#41;,  such as CLIP, ALIGN and Florence, are trained on largescale datasets of image-caption pairs and achieve superior transferability and robustness on downstream tasks, but they  are difficult to use in many practical applications due to the large size, high latency and fixed architectures. Unfortunately, recent work shows training a small custom VLFM for resource-limited applications is currently very difficult using public and smaller-scale data. In this paper, we introduce a new distillation mechanism &#40;DIME-FM&#41; that allows us to transfer the knowledge contained in large VLFMs to  smaller, customized foundation models using a relatively small amount of inexpensive, unpaired images and sentences. We transfer the knowledge from the pre-trained CLIP-ViTL/14 model to a ViT-B/32 model, with only 40M public images and 28.4M unpaired public sentences. The resulting  model ''Distill-ViT-B/32'' rivals the CLIP-ViT-B/32 model pre-trained on its private WiT dataset &#40;400M image-text pairs&#41;: Distill-ViT-B/32 achieves similar results in terms  of zero-shot and linear-probing performance on both ImageNet and the ELEVATER &#40;20 image classification tasks&#41;  benchmarks. It also displays comparable robustness when  evaluated on five datasets with natural distribution shifts from ImageNet. </p>)


<li><strong>Ximeng Sun</strong>, Ping Hu, Kate Saenko. "DualCoOp: Fast Adaptation to Multi-Label Recognition with Limited Annotations". NeurIPS 2022.</li>
<p><a href="https://arxiv.org/pdf/2206.09541.pdf">pdf</a> / <a href="https://github.com/sunxm2357/DualCoOp">code</a></p>

[//]: # (<p><strong>Overview</strong>: Solving multi-label recognition &#40;MLR&#41; for images in the low-label regime is a challenging task with many real-world applications. Recent work learns an alignment between textual and visual spaces to compensate for insufficient image labels, but loses accuracy because of the limited amount of available MLR annotations. In this work, we utilize the strong alignment of textual and visual features pretrained with millions of auxiliary image-text pairs and propose Dual Context Optimization &#40;DualCoOp&#41;  as a unified framework for partial-label MLR and zero-shot MLR. DualCoOp encodes positive and negative contexts with class names  as part of the linguistic input &#40;i.e. prompts&#41;. Since DualCoOp only introduces a very light learnable overhead upon the pretrained vision-language framework, it can quickly adapt to  multi-label recognition tasks that have limited annotations and even unseen classes.  Experiments on  standard multi-label recognition benchmarks across two challenging low-label settings demonstrate the advantages of our approach over state-of-the-art methods.</p>)

<li><strong>Ximeng Sun</strong>, Rameswar Panda, Chun-Fu Chen, Aude Oliva, Rogerio Feris, Kate Saenko. "Dynamic Network Quantization for Efficient Video Inference". ICCV 2021.</li>
<p><a href="https://arxiv.org/pdf/2108.10394.pdf">pdf</a> / <a href="https://github.com/sunxm2357/VideoIQ">code</a></p>

[//]: # (<p><strong>Overview</strong>: Motivated by the effectiveness of quantization for boosting efficiency, in this paper, we propose a dynamic network quantization framework, that selects optimal precision for each frame conditioned on the input for efficient video recognition. Specifically, given a video clip, we train a very lightweight network in parallel with the recognition network, to produce a dynamic policy indicating which numerical precision to be used per frame in recognizing videos. We train both networks effectively using standard backpropagation with a loss to achieve both competitive performance and resource efficiency required for video recognition. Extensive experiments on four challenging diverse benchmark datasets demonstrate that our proposed approach provides significant savings in computation and memory usage while outperforming the existing state-of-the-art methods.</p>)


<li>Rameswar Panda, Chun-Fu Chen, Quanfu Fan, <strong>Ximeng Sun</strong>, Kate Saenko, Aude Oliva, Rogerio Feris. "AdaMML: Adaptive Multi-Modal Learning for Efficient Video Recognition".  <em>International Conference on Computer Vision (ICCV)</em>, 2021.  </li>
<p><a href="https://arxiv.org/pdf/2105.05165">paper</a>  / <a href="https://github.com/IBM/AdaMML">code</a></p>


<li><strong>Ximeng Sun</strong>, Rameswar Panda, Rogerio Feris,  Kate Saenko. "AdaShare:  Learning What To Share For Efficient Deep Multi-Task Learning". NeurIPS 2020.</li>
<p><a href="https://arxiv.org/pdf/1911.12423.pdf">pdf</a> / <a href="https://github.com/sunxm2357/AdaShare">code</a> </p>

[//]: # (<p><strong>Overview</strong>: AdaShare is a novel and differentiable approach for efficient multi-task learning that learns the feature sharing pattern to achieve the best recognition accuracy, while restricting the memory footprint as much as possible. Our main idea is to learn the sharing pattern through a task-specific policy that selectively chooses which layers to execute for a given task in the multi-task network. In other words, we aim to obtain a single network for multi-task learning that supports separate execution paths for different tasks.</p>)

<li><strong>Ximeng Sun</strong>, Huijuan Xu, Kate Saenko. "TwoStreamVAN: Improving Motion Modeling in Video Generation". WACV 2020.</li>
<p><a href="https://arxiv.org/pdf/1812.01037">paper</a> / <a href="https://github.com/sunxm2357/TwoStreamVAN">code</a>  </p>

<li>Xingchao Peng, Zijun Huang, <strong>Ximeng Sun</strong>, Kate Saenko. "Domain Agnostic Learning with Disentangled Representations". <em> International Conference on Machine Learning (ICML)</em>, 2019.</li>
<p><a href="https://arxiv.org/pdf/1904.12347">paper</a>  / <a href="https://github.com/VisionLearningGroup/DAL">code</a></p>

[//]: # (<p><strong>Overview</strong>: We propose <i>TwoStreamVAN</i> to output a realistic video given an input action label by progressively generating and fusing motion and content features at multiple scales using adaptive motion kernels. In addition, to better evaluate video generation models, we design a new synthetic human action  dataset <i>SynAction</i> to bridge the difficulty gap between overcomplicated human action datasets and simple toy datasets.</p>)


<li><strong>Ximeng Sun</strong>,  Ryan Szeto, Jason Corso. "A Temporally-Aware Interpolation Network for Video Frame Inpainting". ACCV 2018.</li> 
<p><a href="https://link.springer.com/chapter/10.1007/978-3-030-20893-6_16">paper</a> /  <a href="https://youtu.be/I27HHr3VWjg">demo</a> / <a href="https://github.com/sunxm2357/TAI_video_frame_inpainting">code</a></p>



[//]: # (<p><strong>Overview</strong>: We propose the first deep learning solution to video frame inpainting. We devise a pipeline composed of two modules: a bidirectional video prediction module and a temporally-aware frame interpolation module. Our experiments demonstrate that our approach produces more accurate and qualitatively satisfying results than a state-of-the-art video prediction method and many strong frame inpainting baselines.</p>)

</ul>

<h3>Journal</h3>
<ul>

<li>Ping Hu, <strong>Ximeng Sun</strong>, Stan Sclaroff, Kate Saenko. "DualCoOp++: Fast and Effective Adaptation to Multi-Label Recognition with Limited Annotations", TPAMI 2024 </li>
<p><a href="https://arxiv.org/abs/2308.01890">paper</a>  / code </p>


<li>Ryan Szeto, <strong>Ximeng Sun</strong>,  Kunyi Lu, Jason Corso. "A Temporally-Aware Interpolation Network for Video Frame Inpainting". TPAMI 2019 </li> 
<p><a href="https://ieeexplore.ieee.org/document/8892406">paper</a>  / <a href=" https://github.com/MichiganCOG/video-frame-inpainting">code</a></p>

</ul>

<h3>Patents</h3>
<ul>
  <li>Rameswar Panda, <strong>Ximeng Sun</strong>, Richard Chen, Rogerio Schmidt Feris and Ekaterina Saenko. "Dynamic network quantization for efficient video inference". US Patent App. 17/566,782  </li>


</ul>

<h3>Preprints</h3>
<ul>
  <li>Piotr Teterwak, <strong>Ximeng Sun</strong>, Bryan A. Plummer, Kate Saenko, and Ser-Nam Lim. "CLAMP: Contrastive LAnguage Model Prompt-tuning" </li>

  <li><strong>Ximeng Sun</strong>, Kihyuk Sohn, Kate Saenko, Clayton Mellina, and Xiao Bian. "Label Budget Allocation in Multi-Task Learning" </li>


  <li>Ping Hu, <strong>Ximeng Sun</strong>, Kate Saenko, Stan Sclaroff. "Weakly-supervised Compositional Feature Aggregation for Few-shot Recognition"  </li>

 <li>Huijuan Xu, Bingyi Kang, <strong>Ximeng Sun</strong>, Jiashi Feng, Kate Saenko, Trevor Darrell. "Similarity R-C3D for Few-shot Temporal Activity Detection" </li>

</ul>

---
<div class="container">
<h4><a name="contact"></a>Contact</h4>

<div class="row-fluid">
<div class="span5">
Ximeng Sun<br/>
<div id="hide_email">
Email: sxm2357 [AT] gmail [dot] com <br/>


</div>
</div>
</div>
</div>

