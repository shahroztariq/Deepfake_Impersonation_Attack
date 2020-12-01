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

* __FCelebDF (Ours)__ [[Link]]() 
  * __Real__ Jim Carrey (Left) [just reference]
  * __Fake__ Jim Carrey (Right) [Reenacted using a real video of Joe Biden]
  
  <img src="https://i.ibb.co/TTHLGK1/Mandatory-Credit-Photo-by-Magnus-Sundholm-Shutterstock-10553545n-Jim-Carrey-Sonic-the-Hedgehog-film.jpg" alt="" border="0" width="300" height="300"><img src="https://i.ibb.co/6DFtxDJ/Jim-Carry-fake-FCeleb-DF.png" alt="Jim-Carry-fake-FCeleb-DF" border="0" width="300" height="300">

* __CelebDF__ [[Link]](http://www.cs.albany.edu/~lsw/celeb-deepfakeforensics.html) 
  * __Real__ Emma Watson (Left)
  * __Fake__ Scarlett Johansson (Right) 
  
  <img src="https://i.ibb.co/ngQcXCr/Emma-Watson-real.png" alt="Emma-Watson-real" border="0" width="300"><img src="https://i.ibb.co/j4zz0Fh/Scarlett-Johansson-fake.png" alt="Scarlett-Johansson-fake" border="0" width="300">

* __CelebFOM (Ours)__ [[Link]]() 
  * __Real__ Gal Gadot (Left)
  * __Fake__ Gal Gadot (Right) [Reenacted using a real video of Eva Mendes]
  
  <img src="https://i.ibb.co/5K6kSRj/Gal-Gadot-real.png" alt="Gal-Gadot-real" border="0" width="300"><img src="https://i.ibb.co/dWPNG8W/Eva-Mendes-fake.png" alt="Eva-Mendes-fake" border="0" width="300">

* __VoxCelebTH__ [[Link]](http://www.cs.albany.edu/~lsw/celeb-deepfakeforensics.html) 
  * __Real__ Chris Hemsworth (Left) [just reference]
  * __Fake__ Chris Hemsworth (Right) [Reenacted using an unknown video]
  
  <img src="https://i.ibb.co/6tXkzpM/Chris-Hemsworth.jpg" alt="Chris-Hemsworth" border="0" width="300" height="300"><img src="https://i.ibb.co/L9dwGj6/0004325.jpg" alt="Chris-Hemsworth-Fake" border="0" width="300"  height="300"> 

* __CelebBlend (Ours)__ [[Link]]() 
  * __Real__ Aamir Khan (Left)
  * __Real__ Donald Trump (Center-Left)
  * __Fake__ Aamir Khan blended with Donald Trump (Center-Right)
  * __Fake__ Donald Trump blended with Aamir Khan (Right)
  
  <img src="https://i.ibb.co/7QhvB2G/Amir-Khan-Real-3.jpg" alt="Amir-Khan-Real" border="0" width="200" height="200"><img src="https://i.ibb.co/LdnX7Yx/Donald-Trump-Real.jpg" alt="Donald-Trump-Real" border="0" width="200" height="200"><img src="https://i.ibb.co/VMR9sht/Amir-Khan-Fake.jpg" alt="Amir-Khan-Fake" border="0" width="200" height="200"><img src="https://i.ibb.co/z2WbhZQ/Donald-Trump-Fake.jpg" alt="Donald-Trump-Fake" border="0" width="200" height="200">


