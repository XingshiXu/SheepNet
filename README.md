# SheepNet
Round-the-clock accurate sheep face recognition via frequency enhancement and cross-modal aggregation  
  
## **Author**:   
Ph.D. candidate [Xingshi Xu](https://orcid.org/0000-0002-6687-6975), Prof. [**Huaibo Song**](https://cmee.nwsuaf.edu.cn/szdw/gjzcry/318457.htm)*, Prof. [Diyi Chen](https://www.nwafu.edu.cn/jsdw/zjrc/yxjjhdz/72652.htm), Prof. [Shuming Yang](https://jxgc.nxu.edu.cn/info/1043/6391.htm)  
    
## **1.Abstract**  
  Accurate identity recognition of sheep is essential for precision livestock farming. As an efficient and contact-less identification approach, sheep face recognition aligns with the needs of modern farming and has garnered significant attention. However, existing studies primarily focus on optimizing model architectures to enhance recognition accuracy and reduce complexity, with limited exploration of accurate recognition under low natural light and efficient extraction of identity-related information from wool texture. In this study, a novel sheep face recognition model called SheepNet was proposed. SheepNet recognized identities through NIR-RGB cross-modal matching, where the query images are NIR, available throughout the day, and the identity-labeled gallery images are in RGB. First, the model employed a Shallow Dual-Stream (SDS) architecture to process cross-modal inputs, extracting modality-specific features with separate weights in shallow layers and modality-shared features with shared weights in deep layers to mitigate modality discrepancies. Second, a Frequency Feature Decoupling and Enhancement (FFDE) module was introduced to explicitly modulate features by leveraging high-frequency information, such as wool texture, and low-frequency information, such as patterns and structures, thereby enhancing identity discrimination. Finally, an Embedded Diversity Generation (EDG) module was incorporated to optimize the feature embedding space by generating diverse feature representations, improving cross-modal retrieval capability. Experimental results demonstrated the effectiveness of the proposed method. Under a closed-set setting with 80 sheep, the proposed method achieved CMC-1 and mAP scores of 97.22% and 88.55%, respectively. In an open-set setting with 40 sheep, the CMC-1 and mAP scores reached 97.12% and 83.83%, respectively. In summary, the proposed method provided a reliable solution for sheep identity recognition under low-light conditions, and further improved recognition accuracy by explicitly utilizing wool texture information. This approach is expected to further drive the development of precision livestock farming.  
  
## **2.Why we do & What we do?**  
![中文海报](https://github.com/XingshiXu/SheepNet/blob/main/Poster_Chinese.jpg)
  
## **3. Dataset**   
To find the dataset used in this study, please make sure all files are downloaded from [Google Drive](https://drive.google.com/drive/folders/1nt2-sccBekM6PBtjKPmcP0YlvqtmJ6aH?usp=sharing)  
(Because the relevant funding projects of this study are still ongoing, the complete data set remains under protection. Therefore, at this stage, we released part of the data set.)  
  
  
We thank the potential Reviewers and readers for their attention. Best wishes for you!  
我们感谢潜在审稿人及读者给予的关注，祝工作开心，科研顺利，生活幸福！  
