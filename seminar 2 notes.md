11563147 楊道恩  
Sep. 22, 2026 彭徐鈞 教授 國立臺北醫學大學  
從數據驅動到臨床轉譯：人工智慧於醫學訊號診斷與預後評估之最新進展

1\. Using a deep learning model to predict postoperative (手術後) visual outcomes of idiopathic epiretinal membrane surgery (黃斑前膜 ERM 手術)

\-ERM recovery of vision after surgery takes 3-6 months, or more.  
\-Many challenges of Clinical Practice regarding OCT biomarkers

Research Framework \- Model Building (Image 6, Image 7):  
OCT images \-\> Preprocess\* \-\> Get Training & Validation sets \-\> Data Augmentation (more data) \-\> Deep learning models \-\> Results: Classification and Accuracy

\*Preprocess: ROI (regions of interest) Cropping

Applications \-   
一般眼科醫師: Provides decision-making whether the ERM patient needs referral or determines if further treatment is necessary.

視網膜專科醫師: Assist in treatment planning and decision-making. (Image 11-Clinical Applications.jpg)

Limitations \- 

1. Sample size was small  
2. Postoperative visual acuity was categorized with two classes  
3. Limited OCT machine  
4. Manual image extraction/segmentation

Conclusion \- Successful Prediction (Image 13\)  
DL Models effectively predict postoperative visual outcomes in ERM surgery using OCT images, with ResNet-101 demonstrating superior performance.

2\. Morphometric(形態定量) and Radiomics(放射組學) Analysis toward the prediction of Epilepsy associated with Supratentorial(幕上) Low-grade Glioma(膠質瘤) in children

Methods:  
Preprocess T2 flair \-\> Identify ROI \-\> Preprocess Medical image for Radiomics \-\> Radiomic features computation \-\> Postprocessing  
(Image 14, 15\)

Conclusion:  
The results suggested 8 features of radiomics are distinct between seizure and non-seizure groups. With significant locations, the prediction models can differentiate whether seizure is or is not associated with supratentorial low-grade glioma, more precisely.

3\. Predicting the Longitudinal Efficacy(長期療效) of Depression Medication using Electroencephalography(腦電圖) and Machine Learning

Methods:  
\-ML Models are trained from 77 patients with major depressive disorder  
\-Workflow: EEG Preprocessing \-\> Feature extraction \-\> ML Prediction (Image 18\)

Conclusions (Image 21):  
\-This research highlights the potential of using non-invasive EEG recordings and data-driven methods to optimize clinical decision-making  
\-Helps clinicians to identify responders early in treatment process, reducing the burden of lengthy trial-and-error methods  
\-Has rooms of improvement

4\. Prediction of Long-term treatment response in Vestibular Schwannoma(聽神經瘤) after Stereotactic Radiosurgery(立體定位放射手術) using nnU-Net segmentation and MRI Radiomics

Workflow (Image 22):  
Input raw data \-\> preprocessing \-\> nnU-Net model training \-\> Automatic segmentation \-\> Tumor ROI extraction \-\> Radiomic features extraction \-\> 5-fold cross validation \-\> ML Model training \-\> Treatment response prediction

Treatment response (Image 26, 27):

1. Growth  
2. Stable  
3. Delayed Regression (grow first, then regress)  
4. Direct Regression