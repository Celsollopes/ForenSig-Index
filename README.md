# ForenSig-Index
## Metrics to evaluate reliability and interpretability in Automatic Signature Verification systems.

This material must be used together with the BR-ForenSig Dataset database. Available at this Link: https://github.com/Celsollopes/BR-ForenSig-Dataset
The full application will soon be available.
```
If this material is useful to you, we only ask that you cite this material as follows:
LOPES JUNIOR, Celso A. M. ForenSig Index
[QUOTE]
```
Metrics developed to evaluate signature verification systems from the perspective of forensic expertise and graphotechnical science.

The general metric, ForenSig Index (FSI), has three other components that quantify the signature overlap index (SIP), consistency of interpretability (CI), and Correlation of SVA Model Accuracy (CPM).
The Equations that describe each metric are:


### SIP

$$
\text{SIP} = \frac{\sum (I_{\text{model}} \cdot I_{\text{experts}})}{\sum I_{\text{experts}}}
$$

on what,

$$
\text{SIP} = \frac{\text{Overlap Area}}{\text{Total area marked by experts}}
$$


### CI

$$
\text{CI} = \sigma(\text{SIP})
$$

### CPM

$$
\text{CPM} = \text{Correlation}(\text{SIP}, \text{Precision}_{\text{model}})
$$

### ForenSig Index

$$
\text{FSI} = w_{1} \cdot \text{SIP} + w_{2} \cdot (1 - \text{CI}) + w_{3} \cdot \text{CPM}
$$
