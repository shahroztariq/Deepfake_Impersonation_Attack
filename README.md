# Overview
__Paper Title:__ Am I a Real or Fake Celebrity? Evaluating the Robustness of Commercial Celebrity Recognition Web Services with Deepfakes

__Short Description:__ Testing commerical APIs against the threat of deepfakes using Deepfake Impersonation Attack.

#### Main Contributions
* __Deepfake Impersonation Attack:__ We introduce a novel ap-proach to deceive and evaluate commercial celebrity recognitionweb services against deepfakes emulating impersonation attacks.We also create two novel datasets, Celebrity First Order Motion(CelebFOM) and the Celebrity Blend (CelebBlend), for evaluation.
* __Extensive Evaluation of Commercial Web APIs:__ We eval-uate how popular major commercial celebrity recognition webAPIs from Amazon, Microsoft, and Naver respond to celebritydeepfakes using four different metrics. We demonstrate that celebrity deepfakes fool all three APIs with an attack successrate of up to 78.0% and 99.9% on targeted and non-targeted attacks, respectively.
* __Defense Mechanism__ 
We present a defense mechanism againstthe above mentioned deepfake attacks and show that even inthe worst-case scenario, our proposed mechanism significantly decreases the original attack success rate from 99.8% to 0.1%.

<img src="https://i.ibb.co/56wKNVq/DFIA-pipeline.png" alt="DFIA-pipeline" border="0" width="700">

# Dataset Samples

* __FCelebDF (Ours)__ [[Link]](http://www.cs.albany.edu/~lsw/celeb-deepfakeforensics.html) 
  * __Real__ Emma Watson (Left) - __Fake__ Scarlett Johansson (Right)
  
  <img src="https://i.ibb.co/ngQcXCr/Emma-Watson-real.png" alt="Emma-Watson-real" border="0" width="300"><img src="https://i.ibb.co/j4zz0Fh/Scarlett-Johansson-fake.png" alt="Scarlett-Johansson-fake" border="0" width="300"><div class="row">

* __CelebDF__ [[Link]](http://www.cs.albany.edu/~lsw/celeb-deepfakeforensics.html) 
  * __Real__ Emma Watson (Left) - __Fake__ Scarlett Johansson (Right) 
  
  <img src="https://i.ibb.co/ngQcXCr/Emma-Watson-real.png" alt="Emma-Watson-real" border="0" width="300"><img src="https://i.ibb.co/j4zz0Fh/Scarlett-Johansson-fake.png" alt="Scarlett-Johansson-fake" border="0" width="300"><div class="row">

* __CelebFOM (Ours)__ [[Link]](http://www.cs.albany.edu/~lsw/celeb-deepfakeforensics.html) 
  * __Real__ Gal Gadot (Left) - __Fake__ Gal Gadot (Right) [Reenacted using a real video of Eva Mendes]
  
  <img src="https://i.ibb.co/5K6kSRj/Gal-Gadot-real.png" alt="Gal-Gadot-real" border="0" width="300"><img src="https://i.ibb.co/dWPNG8W/Eva-Mendes-fake.png" alt="Eva-Mendes-fake" border="0" width="300">

* __VoxCelebTH__ [[Link]](http://www.cs.albany.edu/~lsw/celeb-deepfakeforensics.html) 
  * __Real__ Emma Watson (Left) - __Fake__ Scarlett Johansson (Right) 
  
  <img src="https://i.ibb.co/ngQcXCr/Emma-Watson-real.png" alt="Emma-Watson-real" border="0" width="300"><img src="https://i.ibb.co/j4zz0Fh/Scarlett-Johansson-fake.png" alt="Scarlett-Johansson-fake" border="0" width="300"><div class="row">

* __CelebBlend (Ours)__ [[Link]](http://www.cs.albany.edu/~lsw/celeb-deepfakeforensics.html) 
  * __Real__ Emma Watson (Left) - __Fake__ Scarlett Johansson (Right) 
  
  <img src="https://i.ibb.co/ngQcXCr/Emma-Watson-real.png" alt="Emma-Watson-real" border="0" width="300"><img src="https://i.ibb.co/j4zz0Fh/Scarlett-Johansson-fake.png" alt="Scarlett-Johansson-fake" border="0" width="300"><div class="row">
