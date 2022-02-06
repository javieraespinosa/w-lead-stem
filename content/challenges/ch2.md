---

widget: "blank"
headless: true  # This file represents a page section.

title : "Challenge 2"
subtitle : ""
active : false
weight : 42

share: false
commentable: false
editable: false
header:
  caption: ""
  image: ""
---

# Estimation of stacking velocity using CDP semblance

The estimation of the stacking velocities is one of the most important steps in the CMP (Common Mid Point) seismic processing. This is because the better the estimation of the stacking velocities, the better the quality of zero-offset section obtained. Currently, the most conventional method of velocity analysis consists in the manual picking of the stacking velocities in the velocity spectrum, using the semblance as a coherence measure. The semblance gives us a measure of multichannel coherence.

### Couching group:

<Names> Flávio

### Data sets: CDP or CMP gather traces

<Here description of the data including format, attributes and a short description in natural language>

The  raw dataset is here: https://drive.google.com/drive/folders/11D97D1qo8huynWxHYH-rtvxcTxqb_fI9?usp=sharing

### Material

1. Description of data format and code for reading data.
2. Equations used for NMO correction.

### To Do

For addressing the challenge, you can use any method you prefer, mathematical, machine learning or artificial intelligence. Use Kaggle or Collab for developing your solution. We do not ask for a finalized application but for a data science study that you can report on a clean, documented notebook. You can choose to use any underlying execution tool you need, a database system for dealing with your data, or a library.

#### Part I: Questions

1. Provide a dataset study with a quantitative analysis of the data that goes beyond what Kaggle     automatically produces.
2. Transform the CDP or CMP gather traces from the offset and time coordinates into the coherence semblances in coordinates of time and stacking velocities.
3. Pick local maxima of these coherence semblances and assign zero-offset time and corresponding stacking velocities. Note that in presence of not properly accounted for shallow or overburden velocity anomalies, the difference between stacking and interval velocities can be quite large (up to 30% and more). Therefore before using this approach, we have to remove the effects of the lateral velocity changes in the overburden.
4. Correct the CDP or CMP gathers for normal moveout (NMO).
5. Report and plot your results, including an explanation of the results. Compare the results of your approaches, if you develop more than one.

![challenge2](http://adageo.github.io/summit-2021/img/challenge2.png)
