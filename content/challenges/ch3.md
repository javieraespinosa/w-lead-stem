---

widget: "blank"
headless: true  # This file represents a page section.

title : "Challenge 3"
subtitle : ""
active : false
weight : 43

share: false
commentable: false
editable: false
header:
  caption: ""
  image: ""
---

# Filtering data from sensors

Seismic stations collect signals that can represent earthquakes produced in a specific area. This data usually contains noise produced by the context where the sensor is placed, as well as by the technology of the sensor itself.

The challenge is to filter this data to make it ready to be analyzed.

### Couching group

<Names>

### Data sets

<Here description of the data including format, attributes and a short description in natural language>

The  raw dataset of seismic stations is here: https://drive.google.com/drive/folders/1K-NoNJtSZfFC9D_LkGC3rGWIw6X0638g?usp=sharing

### To Do

For addressing the challenge, you can use any method you prefer, mathematical, machine learning or artificial intelligence. Use Kaggle or Collab for developing your solution. We do not ask for a finalised application but for a data science study that you can report on a clean, documented notebook. You can choose to use any underlying execution tool you need, a database system for dealing with your data, or a library.

#### Part I: Questions

1. Provide a dataset study with a quantitative analysis of the data that goes beyond what Kaggle automatically produces.
2. Compute the direction of the earthquake epicentre. Use the sensor’s initial movement polarity when the waves P and S are discovered.
3. Compute the distance considering how the sensor moves from North-South (it should be the same as the East-West), as shown in Figure 1.
4. Propose an assessment strategy with metrics for determining the “performance” of your results.
5. Report and plot your results, including an explanation of the results.

#### Part II: Questions

1. Now the objective is to use the dataset to locate the earthquakes. You can plot a map to show your results.
