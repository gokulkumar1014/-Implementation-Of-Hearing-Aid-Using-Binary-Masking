# Implementation of Hearing Aid using Binary Masking

## Overview
* Hearing impaired listeners find more difficulty in distinguishing speech in noisy environments as compared to persons with normal hearing. While using correct hearing devices hearing impaired listeners find it difficult in interpreting speech. . Approximately 10% of the world's population suffers from some type of hearing loss, yet only a small percentage of this statistic use a hearing aid. The stigma associated with wearing a hearing aid, customer dissatisfaction with hearing aid performance, and the cost associated with a high performance solution are all causes of low market penetration the use of digital signal processing, digital hearing aid now offers what the analog hearing aid cannot offer. The existing methods used in available speech algorithms gives better results for quality of speech signal. While clarity of speech will give poor performance. Because of this hearing impaired listeners having problems in communication.<br/>
* This speech intelligibility problem is significantly removed by using binary mask algorithm.<br/>
* This proposed method is suitable for hearing aid application. Time frequency masking technique is introduced in this algorithm. Time frequency masks often take the values of ’zero’ and ’one’, resulting in mixture of two signals. Binary mask is calculated in classification stage and noise signal is removed.<br/>


## Abstract
As we all know that the current hearing application is just enhancing the speech audibility only. The algorithm we have proposed here enhances both the speech intelligibility and audio intelligibility. Various speech enhancement algorithms were developed but only a couple of algorithms can be used for practical hearing aid application. We have used STFT for transforming the audio signal to T-F domain. We have created the binary mask based on comparing the local target energy with the long-term average of spectral energy of speech. In this, Matlab implementation of binary mask algorithm is provided which shows better results for speech intelligibility as compared to other algorithms.

## Algorithm:
![algo](https://user-images.githubusercontent.com/71454390/134505911-32b5856b-ab41-452d-83ea-446cedd9e2da.jpg)
* Binary mask algorithm discards those signals having noise. It is possible with the audio masking of speech signal.<br/>
* After applying mixture of signals as input, signals are mapped from time domain to time-frequency region. This stage represents the signal in time-frequency region.<br/>
* After mapping of signals is done separation of signals is needed for creation of mask. Original speech Signals are separated from the signals having noise.<br/>
* In the final stage by Comparing the Local and Longterm target spectral average energy to create the binary mask so that noise part is removed.<br/>
* Forming the binary mask requires access to the unmixed target and noise signals. As these signals are unobtainable in practice, they instead have to be estimated via spatial filtering method.<br/>


For live simulation [Click here](https://drive.google.com/drive/u/2/folders/18OIRkCK0Om5WKJMkcByvwLiiPez8dluf)
