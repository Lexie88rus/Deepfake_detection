# Deepfake_detection
Repository containing the materials for Kaggle Deepfake detection competition

## Introduction
Deepfake techniques, which present realistic AI-generated videos of people doing and saying fictional things, have the
potential to have a significant impact on how people determine the legitimacy of information presented online. These content
generation and modification technologies may affect the quality of public discourse and the safeguarding of human
rights—especially given that deepfakes may be used maliciously as a source of misinformation, manipulation, harassment,
and persuasion. Identifying manipulated media is a technically demanding and rapidly evolving challenge that requires
collaborations across the entire tech industry and beyond. [Link to competition on Kaggle](https://www.kaggle.com/c/deepfake-detection-challenge).
[Examples of DeepFakes](https://www.creativebloq.com/features/deepfake-examples)

## DeepFake Papers Review:
1. [Unmasking DeepFakes with simple Features](https://arxiv.org/pdf/1911.00686v2.pdf): The method is based on a classical frequency domain analysis
followed by a basic classifier. Compared to previous systems, which need to be fed with large amounts of labeled data, this
approach showed very good results using only a few annotated training samples and even achieved good accuracies in fully
unsupervised scenarios. [Github repo](https://github.com/cc-hpc-itwm/DeepFakeDetection)

2. [FaceForensics++: Learning to Detect Manipulated Facial Images](https://arxiv.org/pdf/1901.08971v3.pdf): This paper
examines the realism of state-of- the-art image manipulations, and how difficult it is to detect them, either automatically
or by humans. [Github repo](https://github.com/ondyari/FaceForensics)

3. [In Ictu Oculi: Exposing AI Generated Fake Face Videos by Detecting Eye Blinking](https://arxiv.org/pdf/1806.02877v2.pdf): Method is based on detection of eye blinking in the videos,
which is a physiological signal that is not well presented in the synthesized fake videos. Method is tested over
benchmarks of eye-blinking detection datasets and also show promising performance on detecting videos generated with DeepFake.
[Github repo](https://github.com/danmohaha/WIFS2018_In_Ictu_Oculi)

4. [USE OF A CAPSULE NETWORK TO DETECT FAKE IMAGES AND VIDEOS](https://arxiv.org/pdf/1910.12467v2.pdf): "Capsule-Forensics"
method to detect fake images and videos. [Github repo](https://github.com/nii-yamagishilab/Capsule-Forensics-v2)

5. [Exposing DeepFake Videos By Detecting Face Warping Artifacts](https://arxiv.org/pdf/1811.00656v3.pdf): Deep learning based
method that can effectively distinguish AI-generated fake videos (referred to as DeepFake videos hereafter) from real videos.
Method is based on the observations that current DeepFake algorithm can only generate images of limited resolutions, which
need to be further warped to match the original faces in the source video. Such transforms leave distinctive artifacts in
the resulting DeepFake videos, and we show that they can be effectively captured by convolutional neural networks (CNNs).
[Github repo](https://github.com/danmohaha/CVPRW2019_Face_Artifacts)

6. [Limits of Deepfake Detection: A Robust Estimation Viewpoint](https://arxiv.org/pdf/1905.03493v1.pdf): This work gives a
generalizable statistical framework with guarantees on its reliability. In particular, we build on the information-theoretic
study of authentication to cast deepfake detection as a hypothesis testing problem specifically for outputs of GANs,
themselves viewed through a generalized robust statistics framework.
