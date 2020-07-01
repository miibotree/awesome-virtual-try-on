# A Curated List of Awesome Virtual Try-on (VTON) Research
A curated list of awesome research papers, projects, code, dataset, workshops etc. related to virtual try-on (VTON).

- [Image-based (2D) Virtual Try-on](#Image-based-2D-Virtual-Try-on)
- [3D Virtual Try-on](#3D-virtual-try-on)
- [Multi-Pose Guided Virtual Try-on](#Multi-Pose-Guided-Virtual-Try-on)
- [Video Virtual Try-on](#Video-Virtual-Try-on)
- [Non-clothing Virtual Try-on](#non-clothing-virtual-try-on)
- [Datasets for Virtual Try-on](#Datasets-for-Virtual-Try-on)
- [Related Conference Workshops](#Related-Conference-Workshops)
- [Related Repositories](#Related-Repositories)


## Image-based (2D) Virtual Try-on

  #### CVPR 2020
  - Towards Photo-Realistic Virtual Try-On by Adaptively Generating↔Preserving Image Content - [Paper/Code/Data](https://github.com/switchablenorms/DeepFashion_Try_On)
  - Image Based Virtual Try-On Network From Unpaired Data - [Paper](http://openaccess.thecvf.com/content_CVPR_2020/html/Neuberger_Image_Based_Virtual_Try-On_Network_From_Unpaired_Data_CVPR_2020_paper.html)
  #### CVPRW 2020
  - CP-VTON+: Clothing Shape and Texture Preserving Image-Based Virtual Try-On - [Paper/Code/Data](https://minar09.github.io/cpvtonplus/)
  - 3D Reconstruction of Clothes using a Human Body Model and its Application to Image-based Virtual Try-On - [Paper/Code](https://minar09.github.io/c3dvton/)

  #### ICCV 2019
  - VTNFP: An Image-Based Virtual Try-On Network With Body and Clothing Feature Preservation - [Paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Yu_VTNFP_An_Image-Based_Virtual_Try-On_Network_With_Body_and_Clothing_ICCV_2019_paper.html)
  - ClothFlow: A Flow-Based Model for Clothed Person Generation - [Paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Han_ClothFlow_A_Flow-Based_Model_for_Clothed_Person_Generation_ICCV_2019_paper.html)
  
  #### ICCVW 2019
  - UVTON: UV Mapping to Consider the 3D Structure of a Human in Image-Based Virtual Try-On Network, [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Kubo_UVTON_UV_Mapping_to_Consider_the_3D_Structure_of_a_ICCVW_2019_paper.html)
  - LA-VITON: A Network for Looking-Attractive Virtual Try-On - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Lee_LA-VITON_A_Network_for_Looking-Attractive_Virtual_Try-On_ICCVW_2019_paper.html)
  - Robust Cloth Warping via Multi-Scale Patch Adversarial Loss for Virtual Try-On Framework - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/HBU/Ayush_Robust_Cloth_Warping_via_Multi-Scale_Patch_Adversarial_Loss_for_Virtual_ICCVW_2019_paper.html)
  - Powering Virtual Try-On via Auxiliary Human Segmentation Learning - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Ayush_Powering_Virtual_Try-On_via_Auxiliary_Human_Segmentation_Learning_ICCVW_2019_paper.html)
  - Generating High-Resolution Fashion Model Images Wearing Custom Outfits - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Yildirim_Generating_High-Resolution_Fashion_Model_Images_Wearing_Custom_Outfits_ICCVW_2019_paper.html)

  #### ECCV 2018
  - Toward Characteristic-Preserving Image-based Virtual Try-On Network - [Paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Bochao_Wang_Toward_Characteristic-Preserving_Image-based_ECCV_2018_paper.pdf), [Code](https://github.com/sergeywong/cp-vton)
  - SwapNet: Garment Transfer in Single View Images - [Paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Amit_Raj_SwapNet_Garment_Transfer_ECCV_2018_paper.pdf), [Code](https://github.com/andrewjong/SwapNet)
  
  #### CVPR 2018
  - VITON: An Image-based Virtual Try-on Network - [Paper](https://arxiv.org/abs/1711.08447), [Code/Model](https://github.com/xthan/VITON)
  
  #### Others
  - LGVTON: A Landmark Guided Approach to Virtual Try-On - [Paper](https://arxiv.org/abs/2004.00562v1)
  - SieveNet: A Unified Framework for Robust Image-Based Virtual Try-On, WACV 2020 - [Paper](http://openaccess.thecvf.com/content_WACV_2020/html/Jandial_SieveNet_A_Unified_Framework_for_Robust_Image-Based_Virtual_Try-On_WACV_2020_paper.html)
  - GarmentGAN: Photo-realistic Adversarial Fashion Transfer - [Paper](https://arxiv.org/abs/2003.01894)
  - Toward Accurate and Realistic Virtual Try-on Through Shape Matching and Multiple Warps - [Paper](https://arxiv.org/abs/2003.10817)
  - FashionFit Analysis of Mapping 3D Pose and neural body fit for custom virtual try-on, IEEE Access 2020 - [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9091008)
  - SP-VITON: shape-preserving image-based virtual try-on network, Multimedia Tools and Applications 2019 - [Paper](https://link.springer.com/article/10.1007/s11042-019-08363-w)
  - VITON-GAN: Virtual Try-on Image Generator Trained with Adversarial Loss, Eurographics 2019 Posters - [Paper](https://arxiv.org/abs/1911.07926v1), [Code/Model](https://github.com/shionhonda/viton-gan)
  - Image-Based Virtual Try-on Network with Structural Coherence, ICIP 2019 - [Paper](https://ieeexplore.ieee.org/document/8803811)
  - End-to-End Learning of Geometric Deformations of Feature Maps for Virtual Try-On - [Paper](https://arxiv.org/abs/1906.01347v2)
  - M2E-Try On Net: Fashion from Model to Everyone - [Paper](https://arxiv.org/abs/1811.08599v1)



## 3D Virtual Try-on

  #### CVPR 2020
  - Learning to Transfer Texture from Clothing Images to 3D Humans - [Paper/Code](http://virtualhumans.mpi-inf.mpg.de/pix2surf/)
  - TailorNet: Predicting Clothing in 3D as a Function of Human Pose, Shape and Garment Style - [Paper/Code/Data](http://virtualhumans.mpi-inf.mpg.de/tailornet/)
  - Learning to Dress 3D People in Generative Clothing - [Paper/Code/Data](https://cape.is.tue.mpg.de/)

  #### ICCV 2019
  - Multi-Garment Net: Learning to Dress 3D People from Images - [Paper/Code/Data](http://virtualhumans.mpi-inf.mpg.de/mgn/)
  - 3DPeople: Modeling the Geometry of Dressed Humans - [Paper](https://arxiv.org/abs/1904.04571)
  - GarNet: A Two-Stream Network for Fast and Accurate 3D Cloth Draping - [Paper/Data](https://www.epfl.ch/labs/cvlab/research/garment-simulation/garnet/)

  #### ECCV 2018
  - DeepWrinkles: Accurate and Realistic Clothing Modeling - [Paper](https://arxiv.org/abs/1808.03417)
  
  #### CVPR 2018
  - Video Based Reconstruction of 3D People Models - [Paper/Code/Data](http://gvv.mpi-inf.mpg.de/projects/wxu/VideoAvatar/)

  #### Others
  - 3D Reconstruction of Clothes using a Human Body Model and its Application to Image-based Virtual Try-On, CVPRW 2020 - [Paper/Code](https://minar09.github.io/c3dvton/)
  - Learning-Based Animation of Clothing for Virtual Try-On, Eurographics 2019 - [Paper](https://arxiv.org/abs/1903.07190v1)
  - Learning an Intrinsic Garment Space for Interactive Authoring of Garment Animation, SIGGRAPH Asia 2019 - [Paper/Code](http://geometry.cs.ucl.ac.uk/projects/2019/garment_authoring/)
  - 3D Virtual Garment Modeling from RGB Images, ISMAR 2019 - [Paper](https://arxiv.org/abs/1908.00114)
  - Deep Garment Image Matting for a Virtual Try-on System, ICCVW 2019 - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Shin_Deep_Garment_Image_Matting_for_a_Virtual_Try-on_System_ICCVW_2019_paper.html)
  - Learning a Shared Shape Space for Multimodal Garment Design, SIGGRAPH Asia 2018 - [Paper/Code/Data](http://geometry.cs.ucl.ac.uk/projects/2018/garment_design/)
  - Detailed Garment Recovery from a Single-View Image, ACM TOG 2018 - [Paper](https://arxiv.org/abs/1608.01250)
  - ClothCap: Seamless 4D Clothing Capture and Retargeting, SIGGRAPH 2017 - [Paper](http://clothcap.is.tue.mpg.de/)
  - Virtual Try-On through Image-Based Rendering, IEEE T-VCG 2013 - [Paper](https://ieeexplore.ieee.org/document/6487501)
  - Markerless Garment Capture, ACM TOG 2008 - [Paper/Data](http://www.cs.ubc.ca/labs/imager/tr/2008/MarkerlessGarmentCapture/)




## Multi-Pose Guided Virtual Try-on

- Down to the Last Detail: Virtual Try-on with Detail Carving - [Paper](https://arxiv.org/abs/1912.06324v2), [Code/Model](https://github.com/JDAI-CV/Down-to-the-Last-Detail-Virtual-Try-on-with-Detail-Carving)
- Towards Multi-pose Guided Virtual Try-on Network, ICCV 2019 - [Paper](https://arxiv.org/abs/1902.11026), [Code](https://github.com/thaithanhtuan/MyMGVTON)
- FIT-ME: IMAGE-BASED VIRTUAL TRY-ON WITH ARBITRARY POSES, ICIP 2019 - [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8803681&casa_token=2CL5K9pwy1IAAAAA:OTa5P-h6RWj9BdQVvkxQURR8tDy4Eg1BZynYOizMyQACnE-zL_EHu2xRzyXBOWijP_cItaO4)
- Virtually Trying on New Clothing with Arbitrary Poses, ACM MM 2019 - [Paper](https://dl.acm.org/doi/pdf/10.1145/3343031.3350946?casa_token=w7EzejnZIaEAAAAA:KvDBsi1xYswuQuzEdJO-rsTDvysnSLYlAYi1J2st5lf8lnyotm5-umPKQupGaMEPUGxyBzijUkA9)
- FashionOn: Semantic-guided Image-based Virtual Try-on with Detailed Human and Clothing Information, ACM MM 2019 - [Paper](https://dl.acm.org/doi/pdf/10.1145/3343031.3351075?casa_token=7y85FCo6B-QAAAAA:diZbVYmcSK13bMQ94MzrMG_-VvVG_oNFoGpI8wCBFJ_dHEzYnLBAPn2ZwbAgj_pmOWFMD6_1hOuk)
- Pose Guided Fashion Image Synthesis Using Deep Generative Model - [Paper](https://arxiv.org/pdf/1906.07251.pdf)
- Pose Guided Person Image Generation, NeurIPS 2017 - [Paper](https://arxiv.org/pdf/1705.09368.pdf)
  
  
  
## Video Virtual Try-on

- FW-GAN: Flow-Navigated Warping GAN for Video Virtual Try-On, ICCV 2019 - [Paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Dong_FW-GAN_Flow-Navigated_Warping_GAN_for_Video_Virtual_Try-On_ICCV_2019_paper.html)
- Unsupervised Image-to-Video Clothing Transfer, ICCVW 2019 - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Pumarola_Unsupervised_Image-to-Video_Clothing_Transfer_ICCVW_2019_paper.html)


## Non-clothing Virtual Try-on
- Regularized Adversarial Training for Single-Shot Virtual Try-On, ICCVW 2019 - [Paper](http://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Kikuchi_Regularized_Adversarial_Training_for_Single-Shot_Virtual_Try-On_ICCVW_2019_paper.html)
- Disentangled Makeup Transfer with Generative Adversarial Network - [Paper](https://arxiv.org/pdf/1907.01144v1.pdf)
- PIVTONS: Pose Invariant Virtual Try-On Shoe with Conditional Image Completion, ACCV 2018 - [Paper](https://winstonhsu.info/wp-content/uploads/2018/09/chou18PIVTONS.pdf)
- Virtual Try-on of Eyeglasses using 3D Model of the Head - [Paper](https://dl.acm.org/doi/pdf/10.1145/2087756.2087838)
- A MIXED REALITY SYSTEM FOR VIRTUAL GLASSES TRY-ON - [Paper](https://dl.acm.org/doi/pdf/10.1145/2087756.2087816)
- A virtual try-on system in augmented reality using RGB-D cameras for footwear personalization - [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0278612514000594)



## Datasets for Virtual Try-on

- VITON - [Download](https://drive.google.com/file/d/1MxCUvKxejnwWnoZ-KoCyMCXo3TLhRuTo/view), [Paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Han_VITON_An_Image-Based_CVPR_2018_paper.pdf)
- MPV - [Download](https://drive.google.com/drive/folders/1e3ThRpSj8j9PaCUw8IrqzKPDVJK_grcA), [Paper](https://arxiv.org/abs/1902.11026)
- Deep Fashion3D - [Paper](https://arxiv.org/abs/2003.12753)
- Digital Wardrobe - [Download/Paper/Project](http://virtualhumans.mpi-inf.mpg.de/mgn/)
- TailorNet Dataset - [Download](https://github.com/zycliao/TailorNet_dataset), [Project](http://virtualhumans.mpi-inf.mpg.de/tailornet/)
- CLOTH3D - [Paper](https://arxiv.org/abs/1912.02792)
- 3DPeople - [Project](https://www.albertpumarola.com/research/3DPeople/index.html)
- THUman Dataset - [Project](http://www.liuyebin.com/deephuman/deephuman.html)
- Garment Dataset, Wang et al. 2018 - [Project](http://geometry.cs.ucl.ac.uk/projects/2018/garment_design/)


## Related Conference Workshops

- Workshop on Computer Vision for Fashion, Art and Design: [CVPR 2020](https://sites.google.com/view/cvcreative2020), [ICCV 2019](https://sites.google.com/view/cvcreative), [ECCV 2018](https://sites.google.com/view/eccvfashion)
- Workshop on Towards Human-Centric Image/Video Synthesis: [CVPR 2020](https://vuhcs.github.io/), [CVPR 2019](https://vuhcs.github.io/vuhcs-2019/index.html)


## Related Repositories

- [awesome-fashion-ai](https://github.com/ayushidalmia/awesome-fashion-ai)
- [Cool Fashion Papers](https://github.com/lzhbrian/Cool-Fashion-Papers)
- [Clothes-3D](https://github.com/lzhbrian/Clothes-3D)
- [Awesome 3D Human](https://github.com/lijiaman/awesome-3d-human)
- [Awesome 3D reconstruction list](https://github.com/openMVG/awesome_3DReconstruction_list)
- [Human Body Reconstruction](https://github.com/chenweikai/Body_Reconstruction_References)


#### Pull requests are welcome!
