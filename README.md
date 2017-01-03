{\rtf1\ansi\ansicpg1252\cocoartf1504\cocoasubrtf760
{\fonttbl\f0\fswiss\fcharset0 ArialMT;\f1\froman\fcharset0 TimesNewRomanPSMT;\f2\fnil\fcharset0 LucidaGrande;
\f3\fnil\fcharset0 Menlo-Regular;}
{\colortbl;\red255\green255\blue255;\red26\green26\blue26;\red255\green255\blue255;\red38\green38\blue38;
}
{\*\expandedcolortbl;;\cssrgb\c13333\c13333\c13333;\cssrgb\c100000\c100000\c100000;\cssrgb\c20000\c20000\c20000;
}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sl300\partightenfactor0

\f0\fs25\fsmilli12800 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Model to classify the claim as fast track or complex based on the claim cycle time (number of days the claims is open). Claims which were closed 10 days or lesser as fast track and other claims I classified as complex.\
\'a0\
The model is able to predict with 85% accuracy with below listed features (sorted in order of importance).\
\'a0\
\pard\pardeftab720\sl300\sa256\partightenfactor0
\cf2 1.
\f1\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0 
\f0\fs25\fsmilli12800 Loss Type code\
2.
\f1\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0 
\f0\fs25\fsmilli12800 Jurisdiction state\
3.
\f1\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0 
\f0\fs25\fsmilli12800 Claim Tier code\
4.
\f1\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0 
\f0\fs25\fsmilli12800 Glass only indicator\
5.
\f1\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0 
\f0\fs25\fsmilli12800 Fault rating code\
6.
\f1\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0 
\f0\fs25\fsmilli12800 Coverage sub type\
7.
\f1\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0 
\f0\fs25\fsmilli12800 Product type\
8.
\f1\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0 
\f0\fs25\fsmilli12800 Subrogation Indicator\
\pard\pardeftab720\sl300\partightenfactor0
\cf2 In the second model the claims are classified as fast track based on the owning adjuster group. The confusion matrix is better in the model where the claims are classified based on the owning adjuster group. The model based on cycle time and the model based on owning adjuster have the same prediction accuracy of 85%\
\'a0\
Used the below algorithms:\
\
1.
\f1\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0 
\f0\fs25\fsmilli12800 Logistic regression\
\pard\pardeftab720\sl300\sa256\partightenfactor0
\cf2 \
2.
\f1\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0 
\f0\fs25\fsmilli12800 SVM\
3.
\f1\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0 
\f0\fs25\fsmilli12800 Gradient Boosting\
\pard\pardeftab720\sl300\partightenfactor0
\cf2 \'a0\
\pard\pardeftab720\sl300\partightenfactor0

\b \cf2 Reference:
\b0 \
Claims_fastTrack-CYCLETIME.pdf 
\f2 \'e0
\f0  Model based on cycle time\
Claims_fastTrack-Owning_adjuster.pdf 
\f2 \'e0
\f0  Model based on the owning adjuster\
\pard\pardeftab720\sl320\partightenfactor0

\f3\fs28 \cf4 \cb1 \strokec4 \
}