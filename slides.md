---
theme: geist
title: "Machine Learning Introduction"
layout: default
---

<div class="mt-32">
  <h1 text="6xl">🧠 Machine Learning Introduction</h1>
  <div text="xl">✨ Let's learn how to make a machine learn</div>
</div>

<div class="absolute bottom-12 left-12 flex space-x-2">
  <div class="p-1 rounded-full flex space-x-3 pr-6 items-center bg-black dark:bg-opacity-20 bg-opacity-5">
    <img src="/assets/divy.png" class="rounded-full h-10 w-10" />
    <p class="m-0 font-bold text-sm">Divya Jain</p>
  </div>
  <div class="p-1 rounded-full flex space-x-3 pr-6 items-center bg-black dark:bg-opacity-20 bg-opacity-5">
    <img src="/assets/shweta.png" class="rounded-full h-10 w-10" />
    <p class="m-0 font-bold text-sm">Shweta Nadar</p>
  </div>
</div>

---
title: What will you learn?

layout: header-image-right
header: What will you learn today?
image: ./assets/contents.svg
imageClass: mt-8
---

- <mdi-check class="bullet" /> **Machine Learning** (duh!)
- <mdi-check class="bullet" /> **Data Cleaning and Exploration**
- <mdi-check class="bullet" /> Basic **ML Algorithms**

<div m="t-8">

- <mdi-multiply class="bullet" /> How to build Jarvis?

</div>

<style>
.bullet {
    @apply inline mr-2 dark:text-indigo-300 text-indigo-700
}
</style>

---
layout: center
---

<img h="120" src="/assets/dsmlai.png" />

---
src: ./slides/what-is-ai.md
title: What is Artificial Intelligence?

layout: header-image-right
header: Artificial Intelligence
image: https://media.giphy.com/media/lPvZkGZ2jv26H5U4T4/giphy.gif
imageClass: rounded-lg
---
---
src: ./slides/what-is-ai.md
title: Artificial Intelligence

layout: header-image-right
header: Artificial Intelligence
image: https://media.giphy.com/media/3og0IRjGWktH44GccU/giphy.gif
imageClass: rounded-lg
---
---
title: Intelligent Agent
class: flex items-center justify-center h-full
---

<div bg="black dark:opacity-20 opacity-10" p="6" rounded="lg" w="3/5">
  <div text="2xl dark:white black" font="bold">Intelligent Agent</div>
  <div text="sm dark:indigo-300 indigo-700">/ɪnˈtɛlɪdʒ(ə)nt ˈeɪdʒ(ə)nt/</div>
  <div text="sm dark:gray-300 gray-700" class="italic">noun phrase</div>
  <div text="base">
    <div m="t-4">
      Agents that perceive the <b>Environment</b> using <b>Sensors</b> and take specific actions using <b>Actuators</b>, in order to maximize a <b>Performance Measure</b>
    </div>
  </div>
</div>

---
layout: header-image-right
title: Tesla Autopilot

image: https://media.giphy.com/media/Mbdwhq8d3COS8dv1CU/giphy.gif
imageClass: rounded-lg
header: "Intelligent Agent: Tesla Autopilot"
---

- **Environment:** Road, Cars, Pedestrians
- **Sensors:** Cameras, Ultrasonic Sensors
- **Actuators:** Steering Wheel, Accelerator, Brake
- **Performance Measures:** Reach Destination, Journey Time, Safety, Fuel Efficiency

---
title: What is Machine Learning?

layout: header-image-right
header: What is Machine Learning?
---

---
title: What is Machine Learning?

layout: header-image-right
header: What is Machine Learning?
image: ./assets/ml.svg
---

- a branch of **artificial intelligence (AI)**
- that focuses on the use of **data** and **algorithms**
- to imitate the way that humans **learn**

---
title: Applications of ML
---

<h1 text="5xl">Applications of ML</h1>
<div m="t-12" grid="~ cols-3" gap="4">
  <div class="application-box">Image Recognition</div>
  <div class="application-box">Personal Assistant</div>
  <div class="application-box">Language Translation</div>
  <div class="application-box">Online Fraud Detection</div>
  <div class="application-box">Personal Recommendations</div>
  <div class="application-box">Traffic Prediction</div>
</div>

<style>
.application-box {
    @apply px-12 py-10 rounded-lg dark:bg-black dark:bg-opacity-20 bg-indigo-100 text-center text-2xl font-bold dark:text-indigo-300 text-indigo-700 flex items-center justify-center
}
</style>

---
title: Types of Learning
---

<h1 text="5xl">Types of Learning</h1>
<div m="t-12" grid="~ cols-3" gap="4">
<div class="application-box">
  Supervised Learning
  <div class="subtitle">Training using Data and Labels</div>
</div>
<div class="application-box">
  Unsupervised Learning
  <div class="subtitle">Training using only Data</div>
</div>
<div class="application-box">
  Reinforcement Learning
  <div class="subtitle">Training using Experiences</div>
</div>

<style>
.application-box {
    @apply px-12 py-16 rounded-lg dark:bg-black dark:bg-opacity-20 bg-indigo-100 text-center text-3xl font-bold dark:text-indigo-300 text-indigo-700 flex items-center justify-center flex-col
}
.subtitle {
    @apply dark:text-gray-100 text-gray-900 font-medium text-lg mt-4
}
</style>

</div>

---
title: Types of Tasks
---

<h1 text="5xl">Types of Tasks</h1>
<div m="t-12" grid="~ cols-4" gap="4">
  <div class="application-box">
    <img src="https://camo.githubusercontent.com/8e4d3b60f3cbea7ecd0090ae39aa501bc73f1013d2991c113410e9eb592652ed/687474703a2f2f6572696b6c696e6465726e6f72656e2e73652f696d616765732f705f7265672e676966" m="b-2" rounded="md" />
    Regression
  </div>
  <div class="application-box">
    <img src="https://thumbs.gfycat.com/AgileSlimConure-size_restricted.gif" m="b-2" rounded="md" />
    Classification
  </div>
  <div class="application-box">
    <img src="https://iq.opengenus.org/content/images/2018/07/kmeans.gif" m="b-2" rounded="md" />
    Clustering
  </div>
  <div class="application-box">
    <img src="https://images2.programmersought.com/355/60/606f4e462736c0b54aa48aae126a02a3.gif" m="b-2" rounded="md" />
    Dimesionality Reduction
  </div>
</div>

<style>
.application-box {
    @apply  p-4 rounded-lg dark:bg-black dark:bg-opacity-20 bg-indigo-100 text-center text-xl font-bold dark:text-indigo-300 text-indigo-700 flex items-center self-start flex-col
}
</style>

---
title: Steps of ML
---

<h1 text="5xl">Steps of ML</h1>
<div h="80" flex="~" class="items-center justify-center">
<img src="/assets/ml-steps.png" bg="white" p="4" rounded="md" />
</div>

---
layout: header-image-right
title: Step 1 - Data Collection

image: ./assets/data-processing.svg
imageClass: rounded-lg p-8 dark:bg-white !ml-12
header: 'Step 1: Data Collection'
---

<div text="2xl">

- Success of model depends on the **quantity** and **quality** of the data.
- Sources can be Surveys, Databases, Web Scraping, Pre-compiled Datasets, etc

</div>

---
layout: header-image-right
title: Step 2 - Data Preparation

image: ./assets/charts.svg
imageClass: "rounded-lg p-8 dark:bg-white"
header: "Step 2: Data Preparation & Exploration"
---

<div text="2xl">

- **Most important step**
- **Takes majority of the time**
- Prepare, Clean, and Visualize data
- Get intuition about data
- Split into training and evaluation sets

</div>

---
layout: header-image-right
title: Step 3 - Data Collection

image: ./assets/choice.svg
imageClass: "rounded-lg p-8 dark:bg-white"
header: "Step 3: Choosing a Model"
---

<div text="2xl">

- Find the learning method
- Identify the task
- Find relevant models

</div>

---
layout: header-image-right
title: Step 4 - Training

image: ./assets/training.svg
imageClass: "rounded-lg p-8 dark:bg-white"
header: "Step 4: Training"
---

<div text="2xl">

- Learning to predict more correctly
- Involves gradually **minimizing cost function** and **maximizing accuracy**

</div>

---
layout: header-image-right
title: Step 5 - Evaluation

image: ./assets/testing.svg
imageClass: "rounded-lg p-8 dark:bg-white"
header: "Step 5: Evaluation"
---

<div text="2xl">

- Use **metrics** to measure **objective performance**
- Test the model against previously unseen data
- **Validation set** used here

</div>

---
layout: header-image-right
title: Step 6 - Parameter Tuning

image: ./assets/tuning.svg
imageClass: "rounded-lg p-8 dark:bg-white"
header: "Step 6: Parameter Tuning"
---

<div text="2xl">

- Tune different model parameters for improved performance
- Some parameters are number of **training steps**, **learning rate**, **initialization values** and **distribution**, etc.

</div>

---
layout: header-image-right
title: Step 7 - Prediction

image: ./assets/prediction.svg
imageClass: "rounded-lg p-4 dark:bg-white"
header: "Step 7: Prediction"
---

- Find test predictions for final results
- Get the required insights
- Deploy the model for onsite predictions

---
title: Learning Process
---

<h1 text="5xl">Learning Process: Gradient Descent</h1>
<div h="80" flex="~" class="items-center justify-center">
<img src="http://rasbt.github.io/mlxtend/user_guide/general_concepts/gradient-optimization_files/ball.png" h="72" bg="white" p="4" rounded="md" />
</div>

---
title: Learning Process 2
---

<h1 text="5xl">Learning Process: Maxima Minima</h1>
<div h="80" flex="~" class="items-center justify-center">
<img src="https://study.com/cimages/multimages/16/maxmin3.png" h="72" bg="white" p="4" rounded="md" />
</div>

---
title: Performance Measures
---

<h1 text="5xl">Performance Measures</h1>

<div grid="~ cols-2">
<div text="2xl">
<h1 text="3xl">Regression</h1>

- Mean Absolute Error (MAE)
- Mean Absolute Percentage Error (MAPE)
- Mean Square Error (MSE)
- Root Mean Square Error (RMSE)

</div>
<div text="2xl">
<h1 text="3xl">Classification</h1>

- Accuracy
- Confusion Matrix (TP, FP, TN, FN)
- Precision (TP/(TP+FP))
- Recall (TP/(TP+FN))

</div>

</div>

---
title: ML Models
layout: default
---

<div class="mt-40">
  <h1 w="160" text="6xl">Some Machine Learning Models</h1>
</div>

---
layout: header-image-right
title: Linear Regression

image: https://miro.medium.com/max/1200/1*MtuQBTW0-XbjA2RrP2z3Kw.gif
imageClass: rounded-lg
header: Linear Regression
containerClass: "!mt-2"
---

<a p="y-2 x-6" font="medium" rounded="md" bg="dark:indigo-300 indigo-100" class="dark:text-black text-indigo-700 uppercase text-base" href="https://www.mladdict.com/linear-regression-simulator">Simulation</a>

Linear regression attempts to model the relationship between two variables by fitting a linear equation (a straight line) to the observed data.

<div text="base" m="t-6">

- For 2D data,
- $Y=mX+c$
- For multi-dimensional data,
- $Y = a_{0}x_{0} + a_{1}x_{1} + a_{2}x_{2} + a_{3}x_{3} + ...$

</div>

---
layout: header-image-right
title: Decision Tree

image: https://www.gormanalysis.com/blog/introduction-to-decision-trees_files/tree1.png
imageClass: "rounded-lg p-4 dark:bg-white bg-gray-200"
header: Decision Tree
containerClass: "!mt-2"
---

<a p="y-2 x-6" font="medium" rounded="md" bg="dark:indigo-300 indigo-100" class="dark:text-black text-indigo-700 uppercase text-base" href="http://www.r2d3.us/visual-intro-to-machine-learning-part-1">Simulation</a>

A decision tree is an upside-down tree that makes decisions based on the conditions present in the data.

---
layout: header-image-right
title: K Nearest Neighbors

image: https://miro.medium.com/max/753/0*jqxx3-dJqFjXD6FA
imageClass: "rounded-lg p-4 dark:bg-white"
header: K Nearest Neighbors
---

<a p="y-2 x-6" font="medium" rounded="md" bg="dark:indigo-300 indigo-100" class="dark:text-black text-indigo-700 uppercase text-base" href="http://vision.stanford.edu/teaching/cs231n-demos/knn/">Simulation</a>

KNN considers K Nearest Neighbors (from the training data points) to predict the class or continuous value for the new data point.

---
layout: header-image-right
title: Support Vector Machines

image: https://miro.medium.com/max/1088/1*6U9NrruycDBsPOyivpn8UQ.png
imageClass: "rounded-lg p-8 dark:bg-white bg-gray-200"
header: Support Vector Machines
---

The objective of the support vector machine algorithm is to find a hyperplane in an N-dimensional space(N — the number of features) that distinctly classifies the data points.

---
layout: header-image-right
title: K Means Clustering

image: https://sandipanweb.files.wordpress.com/2017/03/wkmeans1.gif
imageClass: "rounded-lg p-4 dark:bg-white"
header: K Means Clustering
---

K-means algorithm identifies k number of centroids, and then allocates every data point to the nearest cluster, while keeping the centroids as small as possible.

---
layout: header-image-right
title: Principal Component Analysis

image: http://1.bp.blogspot.com/-pgMAHiIWvuw/Tql5HIXNdRI/AAAAAAAABLI/I2zPF5cLRwQ/s1600/clust.gif
imageClass: "rounded-lg p-4 dark:bg-white"
header: Principal Component Analysis
---

Principal Component Analysis, or PCA, is a dimensionality-reduction method that is often used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information in the large set.

---
title: Thank You
layout: center
---

<h1 text="6xl" class="text-center">
  Thank You 💖
  <h2 text="2xl">(for staying till the end)</h2>
</h1>
