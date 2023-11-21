---
title: "Surgical scenarios understanding "
excerpt: "Understanding the surgical scenarios from phase, step to action <br/><img src='/yanhu/images/surgeryunderstanding.jpg'>"
collection: Research
---
Cataracts are the most common cause of vision loss and blindness in the worldwide; the World Health Organization (WHO) has estimated that the number of people with blindness globally is projected to increase from 43.3 million in 2020 to 61.0 million in 2050.
A surgical procedure to replace the eye lens with an artificial one when the cataract makes the vision cloudy, usually in geriatrics. 
Instrument-tissue interaction detection in cataract surgery video is a fundamental problem for surgical scene understanding.

Task 1: Quintuple Detection [instrument bounding box, tissue bounding box, instrument class, tissue class, action class]
1. Instrument-tissue Interaction Quintuple Detection in Surgery Videos (MICCAI2022)
   We first define instrument-tissue interaction quintuple: [instrument bounding box, tissue bounding box, instrument class, tissue class, action class]
   For the problem of Quintuple Detection, we propose a Quintuple Detection Network (QDNet), including instrument and tissue detection stage, and quintuple prediction stage.
   <br/><img src='/yanhu/images/QDNet.png'>
   The experiment results based on Cataract Dataset are: <br/><img src='/yanhu/images/QDNetexperiment.jpg'>

Dataset:
We define instrument-tissue interaction quintuple: [instrument bounding box, tissue bounding box, instrument class, tissue class, action class]. Please contact Yan Hu (huy3@sustech.edu.cn) about the dataset.
1. We collect a Cataract Quintuple Dataset based on phacoemulsification.
   Data: 15 videos for training, 5 videos for test
   Annotation: class label (12 instruments, 12 tissues, 15 actions), bounding box (12 instruments, 12 tissues) <br/><img src='/yanhu/images/quintupledata.png'>
   

2. We also label a Cholecystectomy CholecQ Dataset based on publicly available dataset.

Task 2: Action Detection (coarse-fine-grained representation)
1. ACT-Net: Anchor-context Action Detection in Surgery Vidoes (MICCAI2023, Oral)
   We develop an anchor-context action detection network (ACTNet), to answer the following questions:
   a) Where actions locate; b) What actions are; c) How confident our model is about predictions <br/><img src='/yanhu/images/ACTNet.png'>
   The experiments results are: <br/><img src='/yanhu/images/ACTNetexperiment.png'>

Dataset: (coming soon)
   


