---


---

<h1 id="intro-to-machine-learning">Intro to Machine Learning</h1>
<p><strong>Machine Learning</strong> is about making predictions and classifications.<br>
Decision Trees are used for making classifications.</p>
<h4 id="a-silly-example-on-regression-">A silly example on regression :</h4>
<p>Imagine we have data showing that people who eat more yams run faster in a 100-meter dash. We can draw two different lines to fit this data and to show the trends. These lines are a type of Machine Learning.<br>
<img src="https://github.com/riti2043/images-for-articles/blob/main/WhatsApp%20Image%202025-09-07%20at%2016.13.24%20(1).jpeg?raw=true" alt="image failed to load"></p>
<p>The <strong>black line</strong> is straight and simple. The <strong>green squiggly line</strong> curves and bends to match every data point perfectly. At first glance, the green line seems better because it fits the original data(red dots) called as <em><strong>training data</strong></em> more closely.<br>
But here’s the key , <em>machine learning isn’t just about fitting existing data - it’s about making good predictions for new situations.</em><br>
To test which line works better, we collect new data called as <em><strong>testing data</strong></em> (the blue dots). We then measure how far off each line’s predictions are from the actual results and add up all the mistakes.</p>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/WhatsApp%20Image%202025-09-07%20at%2016.18.26.jpeg?raw=true" alt="image failed to load"><br>
Even though the green squiggly line fit the training data way better , the black line did a better job at predicting speeds with the testing data.  The green line’s total prediction errors were much larger.Hence we would choose the black line over the green squiggle to make predictions.<br>
No matter how fancy a Machine Learning method sounds or how well it fits the training data, the important thing is how well it performs with the testing data.</p>
<h2 id="how-is-data-prepared-for-machine-learning">How is Data prepared for Machine Learning?</h2>
<p>The process starts with <strong>planning</strong> and <strong>defining the problem</strong> we want to solve using <em>machine learning</em>.</p>
<p>Next comes building a dataset, which raises the question: <em>how much data is enough?</em> We need lots of <em>training data</em>, so we collect as much as possible since it’s hard to predict which samples will be most valuable. The amount needed depends on how complex the project is. Quality matters just as much as quantity. Poor or inaccurate data leads to poor results. The data must also fit the specific task we’re trying to solve.<br>
<img src="https://github.com/riti2043/images-for-articles/blob/main/WhatsApp%20Image%202025-09-08%20at%2001.05.43.jpeg?raw=true" alt=""></p>
<p>Then, we prepare the data into a format that’s easy for the machine learning model to understand and process.</p>
<h3 id="labelling-">Labelling :</h3>
<p>In supervised ML we go through a process called <em><strong>labelling</strong></em>.<br>
It is a process where we show a model the correct answers to a problem by leaving corresponding <em>labels</em> within a dataset. The model needs some measurable characteristics  called <em><strong>features</strong></em> that describes data to it. When it has seen enough examples of features it can apply learned pattern and decide on new data inputs on its own.</p>
<h3 id="data-reduction">Data Reduction</h3>
<p>Not every piece of data carries value for our Machine Learning project.<br>
So we reduce it to put only <em>relevant data</em> in our model.</p>
<p>Consider each column of some data to be a dimension and its also a feature input to a model. When the number of dimensions are too big and some of them aren’t very useful (having zero to no variance) the performance of the ML algorithm can decrease. Logically , we reduce the dimensions this is called as <em><strong>dimensionality reduction</strong></em>.</p>
<p>When the data sets are too big , they can slow down the training process as they require large computational and memory resources and take more time for algorithms to run on. <em><strong>Sampling</strong></em> is a process where a subset of examples is singled out for training instead of using the whole data set.</p>
<h3 id="data-wrangling-">Data Wrangling :</h3>
<p>It is the process of transforming raw data into a form that best describes the underlying problem to a model. It’s techniques include :</p>
<ul>
<li><em><strong>Formatting :</strong></em> Ensuring that data from multiple sources is consistent and standardized and is in a format that fits our ML system best.</li>
<li><em><strong>Normalization :</strong></em> Ensuring that each feature has equal importance to model performance. It helps to unify scales of figures. <em>Min-Max</em> normalization is a classical example.<br>
<img src="https://github.com/riti2043/images-for-articles/blob/main/WhatsApp%20Image%202025-09-08%20at%2001.00.34.jpeg?raw=true" alt=""></li>
</ul>
<h3 id="feature-engineering-">Feature Engineering :</h3>
<p>So far , we saw processes that worked on features already present in data. In <em>feature engineering</em> we create new features.<br>
<strong>Feature engineering</strong> involves creating new <strong>features</strong> or transforming <strong>features</strong> from raw data for machine learning model input.</p>
<p>In conclusion , a machine learns exactly what its taught. A <em>machine learning</em> model is only as good as the data its fed . There are no flawless datasets , striving to make them flawless is the key to success.</p>

