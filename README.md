# Overview
__Paper Title:__ Am I a Real or Fake Celebrity? Evaluating the Robustness of Commercial Celebrity Recognition Web Services with Deepfakes

__Short Description:__ Testing commerical APIs against the threat of deepfakes using Deepfake Impersonation Attack.

#### Main Contributions
* __Deepfake Impersonation Attack:__ We introduce a novel approach to deceive and evaluate commercial celebrity recognition web services against deepfakes emulating impersonation attacks.We also create two novel datasets, Celebrity First Order Motion(CelebFOM) and the Celebrity Blend (CelebBlend), for evaluation.
* __Extensive Evaluation of Commercial Web APIs:__ We evaluate how popular major commercial celebrity recognition web APIs from Amazon, Microsoft, and Naver respond to celebrity deepfakes using four different metrics. We demonstrate that celebrity deepfakes fool all three APIs with an attack successrate of up to 78.0% and 99.9% on targeted and non-targeted attacks, respectively.
* __Defense Mechanism__ 
We present a defense mechanism against the above mentioned deepfake attacks and show that even in the worst-case scenario, our proposed mechanism significantly decreases the original attack success rate from 99.8% to 0.1%.

<img src="https://i.ibb.co/56wKNVq/DFIA-pipeline.png" alt="DFIA-pipeline" border="0" width="700">

# Dataset Samples

* __FCelebDF (Ours)__ [[Link]](samples/FCelebDF.txt) 
  * __Real__ Gal Gadot - Played Wonder Woman in 2010s Movies (Left) [just a refernce image]
  * __Real__ Lynda Carter - Played Wonder Woman in 1970s TV series (Center-Left) [just a refernce image]
  * __Fake__ Gal Gadot playing Wonder Woman in 1970s series (Center-Right) [Originally played by Lynda Carter]
  * __Fake__ Lynda Carter playing Wonder Woman in 2017 Wonder Woman Movie (Right) [Originally played by Gal Gadot]
  
 
  <img src="https://i.ibb.co/DKLXhWc/Gal-Gadot-Original.png" alt="Gal-Gadot-Original" border="0" width="200" height="200"><img src="https://i.ibb.co/D4QrQgK/linda-carter-org.png" alt="linda-carter-org" border="0" width="200" height="200"><img src="https://i.ibb.co/gzCcjvQ/Gal-Gadot-wonder-woman-70-s.png" alt="Gal-Gadot-wonder-woman-70-s" border="0" width="200" height="200"><img src="https://i.ibb.co/McSmhzL/linda-carter-new-wonder-woman.png" alt="linda-carter-new-wonder-woman" border="0" width="200" height="200">
  

* __CelebDF__ [[Link]](http://www.cs.albany.edu/~lsw/celeb-deepfakeforensics.html) 
  * __Real__ Emma Watson (Left)
  * __Fake__ Scarlett Johansson (Right) 
  
  <img src="https://i.ibb.co/ngQcXCr/Emma-Watson-real.png" alt="Emma-Watson-real" border="0" width="250"><img src="https://i.ibb.co/j4zz0Fh/Scarlett-Johansson-fake.png" alt="Scarlett-Johansson-fake" border="0" width="250">

* __CelebFOM (Ours)__ [[Link]](samples/CelebFOM) [To view the images in the link click on the image and then scroll down the page to view them]
  * __Real__ Gal Gadot (Left)
  * __Fake__ Gal Gadot (Right) [Reenacted using a real video of Eva Mendes]
  
  <img src="https://i.ibb.co/5K6kSRj/Gal-Gadot-real.png" alt="Gal-Gadot-real" border="0" width="200" height="200"><img src="https://i.ibb.co/dWPNG8W/Eva-Mendes-fake.png" alt="Eva-Mendes-fake" border="0" width="200" height="200">

* __VoxCelebTH__ [[Link]](https://drive.google.com/drive/folders/1PeGG6zO3ZjrHk2GAXItB8khwMhPPyDHe) 
  * __Real__ Chris Hemsworth (Left) [just a reference image]
  * __Fake__ Chris Hemsworth (Right) [Reenacted using an unknown video]
  
  <img src="https://i.ibb.co/6tXkzpM/Chris-Hemsworth.jpg" alt="Chris-Hemsworth" border="0" width="200" height="200"><img src="https://i.ibb.co/L9dwGj6/0004325.jpg" alt="Chris-Hemsworth-Fake" border="0" width="200"  height="200"> 

* __CelebBlend (Ours)__ [[Link]](samples/CelebBlend) [To view the images in the link click on the image and then scroll down the page to view them]
  * __Real__ Aamir Khan (Left)
  * __Real__ Donald Trump (Center-Left)
  * __Fake__ Aamir Khan blended with Donald Trump (Center-Right)
  * __Fake__ Donald Trump blended with Aamir Khan (Right)
  
  <img src="https://i.ibb.co/7QhvB2G/Amir-Khan-Real-3.jpg" alt="Amir-Khan-Real" border="0" width="200" height="200"><img src="https://i.ibb.co/LdnX7Yx/Donald-Trump-Real.jpg" alt="Donald-Trump-Real" border="0" width="200" height="200"><img src="https://i.ibb.co/VMR9sht/Amir-Khan-Fake.jpg" alt="Amir-Khan-Fake" border="0" width="200" height="200"><img src="https://i.ibb.co/z2WbhZQ/Donald-Trump-Fake.jpg" alt="Donald-Trump-Fake" border="0" width="200" height="200">

# Defense Models
1. __ABNET__
    * [[Article]](https://arxiv.org/abs/2004.14491)
2. __CLRNet__
    * [[Article]](https://arxiv.org/abs/2009.07480)
3. __FakeSpotter__
    * [[Article]](https://www.ijcai.org/Proceedings/2020/476)
4. __FTDetect__
    * [[Article]](https://openaccess.thecvf.com/content_ICCVW_2019/html/HBU/Jeon_FakeTalkerDetect_Effective_and_Practical_Realistic_Neural_Talking_Head_Detection_with_ICCVW_2019_paper.html) [[Code]](https://github.com/cutz-j/FakeTalkerDetect)
6. __MesoNet__
    * [[Article]](https://ieeexplore.ieee.org/abstract/document/8630761) [[Code]](https://github.com/DariusAf/MesoNet)
5. __ShallowNet__
    * [[Article]](https://dl.acm.org/doi/abs/10.1145/3267357.3267367) [[Code]](https://github.com/shahroztariq/ShallowNet)
7. __Xception__
    * [[Article]](https://openaccess.thecvf.com/content_cvpr_2017/html/Chollet_Xception_Deep_Learning_CVPR_2017_paper.html) [[Code]](https://github.com/fchollet/deep-learning-models/blob/master/xception.py)
