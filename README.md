<img align="left" src="headshot.png" width="190">


# Andrew (Maozheng) Zhao
Computer Science PhD student at Stony Brook University <br/>
Email: andrew.zhao.2024@gmail.com<br/>
Phone：(631) 428-3846<br/>
[Resume](Resume_Andrew.pdf) \|
[LinkedIn](https://www.linkedin.com/in/andrew-maozheng-z-51079914a/) \|
[Google scholar](https://scholar.google.com/citations?hl=en&user=3wbgHbIAAAAJ)

## Introduction
I'm a computer science PhD candidate at Stony Brook University graduating in December 2023. My research focuses on language model powered multimodal human-computer interaction on mobile devices. I have publications in CHI, UIST, and IUI. I interned at Google and Meta. I have experience with LLM fine-tuning, and CNN training. I've built multiple end-to-end Android/iOS Apps that have language models and multimodal input for enhanced user experience. 
## Internship experience

**Student researcher, Google, Mountain View, CA**<br/>
Dec, 2022 - May, 2023<br/> 
Fine tuned LLMs to enable Android settings search to understand natural language queries. Evaluated the fine-tuned LLMs with real user queries. The fine-tuned LLMs outperforms other search methods such as TF-IDF, sentence encoding, and prompt engineering. <br/>
**Research Intern, Google, Mountain View, CA**<br/>
Oct, 2022 - Dec, 2022<br/>
Created a synthetic dataset by prompt engineering using the PaLM LLM. Fine tuned the LaMDA LLM on the synthetic dataset to enable Android settings search to understand natural language queries.<br/>

**Research Scientist Intern, Meta, Redmond, WA**<br/>
Reduced users' hand movement burden by 30% during gesture typing in virtual reality by utilizing users' eye gaze input. Published a conference paper in IUI 2024 from this internship project.<br/>

## Education

**Ph.D., Stony Brook University, USA**<br/>
Major: Computer Science.  Advisor: Prof. Xiaojun Bi.  GPA: 3.78 <br/>
**Graduation date: December 2023.**<br/>
The CS program is ranked #23 in the US by CSRankings.org <br/>
Aug, 2016-present.<br/><br/>

**M.S., Beijing University of Posts and Telecommunications, China**<br/>
Major: Information and Communication Engineering.  GPA: 3.80<br/>
Sep, 2013 - Mar, 2016<br/><br/>

**B.S., Harbin Engineering University, China**<br/>
Major: Electronic and Information Engineering.  GPA: 3.58<br/>
Aug, 2009 - Jul, 2013.<br/><br/>

## Programming experience
Python (7 years), Java (3 years), Swift (2 years), Pytorch (2 years), TensorFlow (0.5 year), C# (0.5 year)

Android development (3 years), iOS development (2 years), VR development (0.5 year)

## Project experience

<a href="https://maozheng6.github.io/LLM-VT/"><img align="left" src="llm_teaser.png" width="250">  

### LLM-based text correction with voice and touch input on smartphones

[Project webpage](https://maozheng6.github.io/LLM-VT/), <a href="https://maozheng6.github.io/LLM-VT/LLM-VT.pdf"><img  src="pdf.gif" width="20" >  [Preprint](https://maozheng6.github.io/LLM-VT/LLM-VT.pdf) <br/>

Developed an end-to-end Android APP for a new LLM-based text correction method with voice and touch input. Fine-tuned FLAN-T5 LLM on Google colab with a semi-synthetic dataset. Served the LLM on a cloud server that communicates with the Android APP for text correction. Carried out a user study and proved that the proposed LLM-based method reduced 15% text correction time from the state-of-the-art method. <br/>

<br/>

<a href="https://maozheng6.github.io/VT/"><img align="left" src="VT_teaser.png" width="250" >  

### Language model based text correction and text editing with voice and touch input on smartphones

[Project webpage](https://maozheng6.github.io/VT/), <a href="https://dl.acm.org/doi/pdf/10.1145/3472749.3474742"><img  src="pdf.gif" width="20" >  [Paper](https://dl.acm.org/doi/pdf/10.1145/3472749.3474742) <br/>

Developed an end-to-end Android APP for a new text correction and text formatting method with voice and touch input. Converted voice input to executable text correction or formatting commands. Implemented a 3-gram language model and word embedding model on Android phones to correct text. Carried out a user study which proved that the proposed method reduced 31% text editing time and 48% text correction time from the iOS Voice Control. <br/>

<br/>

<a href="https://maozheng6.github.io/EyeSayCorrect/"><img align="left" src="ESC_teaser.png" width="250" >  

### Eye Gaze and voice based text correction on iPad Pro

[Project webpage](https://maozheng6.github.io/EyeSayCorrect/), <a href="https://dl.acm.org/doi/pdf/10.1145/3490099.3511103"><img  src="pdf.gif" width="20" >  [Paper](https://dl.acm.org/doi/pdf/10.1145/3490099.3511103) <br/>


Developed an end-to-end iOS APP for a new text correction method with eye gaze and voice input on an iPad Pro. Proposed a new eye gaze target selection method using Beyesian theory for noisy eye gaze input. Implemented a 3-gram language model on a cloud server connected with the APP for text correction. Carried out a user study which proved that the Bayesian method reduced up to 23% text correction time from the non-Bayesian method.  <br/>

<br/>

<a href="https://maozheng6.github.io/GazeSpeedup/"><img align="left" src="gc_teaser.png" width="250" >  

### (Meta internship) Eye gaze assisted swipe typing in VR

[Project webpage](https://maozheng6.github.io/GazeSpeedup/), <a href="https://dl.acm.org/doi/pdf/10.1145/3581641.3584072"><img  src="pdf.gif" width="20" >  [Paper](https://dl.acm.org/doi/pdf/10.1145/3581641.3584072) <br/>

Developed an end-to-end 3D Unity APP on Meta Quest 2 with C# for a new text input method with eye gaze and wristband input. Reduced 30% hand movement burden from users during swipe typing in VR by utilizing users' eye gaze. <br/>

<br/>

<img align="left" src="search_teasor.png" width="250">  

### (Google internship) LLM-based Android search for natural queries

Fine tuned LLMs to enable Android settings search to understand natural language queries. Created a synthetic dataset using LLMs, evaluated the fine-tuned model with real user queries. The fine-tuned model significantly outperforms other search methods such as TF-IDF, sentence encoding, and LLM prompt engineering. <br/>

<br/>

## Selected publications
#### CHI 2024 (under review)
**Zhao, Maozheng**, Nathan Huang, Rui Liu, Shumin Zhai, I. V. Ramakrishnan and Xiaojun Bi. "Beyond Autocorrect: LLM-based Multi-modal Text Correction on Smartphones with Voice and Touch Input." (Under review) CHI 2024 conference on Human Factors in Computing Systems. <br/>
[Project webpage](https://maozheng6.github.io/LLM-VT/), <a href="https://maozheng6.github.io/LLM-VT/LLM-VT.pdf"><img  src="pdf.gif" width="20" >  [Preprint](https://maozheng6.github.io/LLM-VT/LLM-VT.pdf) <br/>

#### UIST 2021
**Zhao, Maozheng**, Wenzhe Cui, I. V. Ramakrishnan, Shumin Zhai, and Xiaojun Bi. "Voice and Touch Based Error-tolerant Multimodal Text Editing and Correction for Smartphones." In The 34th Annual ACM Symposium on User Interface Software and Technology (UIST 2021), pp. 162-178. 2021. [Acceptance Rate: 25.05%] <br/>
[Project webpage](https://maozheng6.github.io/VT/), <a href="https://dl.acm.org/doi/pdf/10.1145/3472749.3474742"><img  src="pdf.gif" width="20" >  [Paper](https://dl.acm.org/doi/pdf/10.1145/3472749.3474742) <br/>

#### IUI 2022
**Zhao, Maozheng**, Henry Huang, Zhi Li, Rui Liu, Wenzhe Cui, Kajal Toshniwal, Ananya Goel et al. "EyeSayCorrect: Eye Gaze and Voice Based Hands-free Text Correction for Mobile Devices." In 27th International Conference on Intelligent User Interfaces (IUI 2022), pp. 470-482. 2022. [Acceptance Rate: 24.5%] <br/>
[Project webpage](https://maozheng6.github.io/EyeSayCorrect/), <a href="https://dl.acm.org/doi/pdf/10.1145/3490099.3511103"><img  src="pdf.gif" width="20" >  [Paper](https://dl.acm.org/doi/pdf/10.1145/3490099.3511103) <br/>

#### IUI 2023
**Zhao, Maozheng**, Alec M. Pierce, Ran Tan, Ting Zhang, Tianyi Wang, Tanya R. Jonker, Hrvoje Benko, and Aakar Gupta. "Gaze Speedup: Eye Gaze Assisted Gesture Typing in Virtual Reality." In Proceedings of the 28th International Conference on Intelligent User Interfaces (IUI 2023), pp. 595-606. 2023. [Acceptance Rate: 24.1%] <br/>
[Project webpage](https://maozheng6.github.io/GazeSpeedup/), <a href="https://dl.acm.org/doi/pdf/10.1145/3581641.3584072"><img  src="pdf.gif" width="20" >  [Paper](https://dl.acm.org/doi/pdf/10.1145/3581641.3584072) <br/>

#### CHI 2022
Li, Zhi, **Maozheng Zhao**, Dibyendu Das, Hang Zhao, Yan Ma, Wanyu Liu, Michel Beaudouin-Lafon, Fusheng Wang, Iv Ramakrishnan, and Xiaojun Bi. "Select or Suggest? Reinforcement Learning-based Method for High-Accuracy Target Selection on Touchscreens." In CHI Conference on Human Factors in Computing Systems (CHI), pp. 1-15. 2022. [Acceptance Rate: 24.8%]<br/>
 <a href="https://maozheng6.github.io/Maozheng/SOS.pdf"><img  src="pdf.gif" width="20" >  [Paper](https://maozheng6.github.io/Maozheng/SOS.pdf) <br/>

#### GI 2021
Li, Zhi, **Maozheng Zhao**, Yifan Wang, Sina Rashidian, Furqan Baig, Rui Liu, Wanyu Liu et al. "BayesGaze: A Bayesian Approach to Eye-Gaze Based Target Selection." In Proceedings. Graphics Interface (GI), vol. 2021, p. 231. NIH Public Access, 2021.<br/>
 <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8853835/"><img  src="pdf.gif" width="20" >  [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8853835/) <br/>

#### ICCV 2017

Nguyen, Vu, Tomas F. Yago Vicente, **Maozheng Zhao**, Minh Hoai, and Dimitris Samaras. "Shadow detection with conditional generative adversarial networks." In Proceedings of the IEEE International Conference on Computer Vision (ICCV), pp. 4510-4518. 2017. <br/>
<a href="https://maozheng6.github.io/Maozheng/scgan.pdf"><img  src="pdf.gif" width="20" >  [Paper](https://maozheng6.github.io/Maozheng/scgan.pdf) <br/>

#### PCS 2015
**Zhao, Maozheng**, Qin Tu, Yanping Lu, Yongyu Chang, and Bo Yang. "No-reference image quality assessment based on phase congruency and spectral entropies." In 2015 Picture Coding Symposium (PCS), pp. 302-306. IEEE, 2015.<br/>
<a href="https://maozheng6.github.io/Maozheng/iqa.pdf"><img  src="pdf.gif" width="20" >  [Paper](https://maozheng6.github.io/Maozheng/iqa.pdf) <br/>

## Teaching Experience
Teaching Assistance for CSE323 human-computer interaction, CSE214 data structures and CSE215 foundations of computer science



