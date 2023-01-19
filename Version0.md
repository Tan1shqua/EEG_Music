# Version 0

## Vision:
We will build an application that will be compose music using emotion recognition.

## Abstract: 
Emotion recognition can be done on the basis of Behavioural changes or Physiological changes. Behavioural changes are encaptured from the facial expression and
body movements. Hence, these behavioural changes can be intentionally controlled. Whereas, Physiological changes are unhindered by the concious mind. These can be data 
obtained from brain signals(EEG), heart signals(ECG), Heart Rate(HR), Galvanic Skin Response(GSR), etc. Of which EEG signals are the most accurate but really challenging 
to obtain. So to overcome this, we shall go with the ECG signals which can be obtained from smartwatches with ECG Monitor. 

## Work-Flow of Version 0:
  -> ECG Signals captured by the SmartWatch
  
  -> Fetching the data and manipulating it for ML model.
  
  -> ML Model 1 - Recognising the emotion using MMAS algorithm with KNN classification algorithm for optimized accuracy. 
                  
                  It shall recognise happy, sad, pleasant and angry emotions.
                  
                  https://iopscience.iop.org/article/10.1088/1742-6596/1678/1/012091/pdf
  
  -> ML Model 2 - Russell emotion model of arousal and valence (discussed by Dhyanesh in last meeting)
                  
                  https://www.frontiersin.org/articles/10.3389/fpsyg.2022.841926/full
                  
                  https://axon.cs.byu.edu/papers/Kristine.ICCC10.pdf
           
  -> Music will be generated.
  
  -> (Optional) Storing the generated music as per the choice of listener.
                  

## Challenges: 
  i. Obtaining the ECG data from the smartwatch.
  
  ii. No knowledge of professional music and it's impact on human emotions.
  
  iii. Dataset to train our ML model for relating music annotations(pitch and notes) with emotion.
  
## Alternatives:
  -> Music recognition using GSR - https://eprints.whiterose.ac.uk/141387/1/IIA_2019_paper_84.pdf
  
  -> Emotion recognition using Facial expressions
