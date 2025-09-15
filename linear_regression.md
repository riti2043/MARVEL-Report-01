---


---

<h1 id="build-your-own-brain-linear-regression">BUILD YOUR OWN BRAIN-LINEAR REGRESSION</h1>
<p><strong>Linear Regression</strong>  is a fundamental <strong>supervised machine learning algorithm</strong> used for prediction. It aims to predict a dependent variable (y), based on an independent variable (x).<br>
The process of finding the right function to predict a dependent variable (y) from an independent variable (x) is called <strong>regression</strong>. When this function is assumed to be a <strong>linear function</strong> represented by <strong>y = αx + β</strong>, where α is the slope and β is the intercept, it is then referred to as <strong>linear regression</strong>.</p>
<p>The goal is to find the optimal values for α and β that make this line best fit the available training data. The “fit” is quantified by calculating the <strong>sum of the squared differences (residuals)</strong> between the actual data points and the values predicted by the line. By minimizing this sum, the best-fit line is determined, often by computing the gradient and setting it to zero to solve for the parameters.</p>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/linearREggg.jpeg?raw=true" alt=""></p>
<h3 id="gradient-descent">Gradient Descent:</h3>
<p>Gradient Descent is an iterative <strong>optimization algorithm</strong> used for training linear regression models by minimizing prediction error. Its goal is to find the optimal parameters (also referred to as weights), such as the <strong>intercept and slope</strong>, that minimize a <strong>Loss Function</strong> (e.g., the sum of squared residuals or Mean Squared Error)<br>
The process:</p>
<ol>
<li>
<p><strong>Take the Derivative of the Loss Function:</strong> First,  <strong>take the derivative of the loss function for each parameter</strong> involved in the model. In machine learning terminology, this is known as taking the <strong>gradient of the loss function</strong>.</p>
</li>
<li>
<p><strong>Pick Random Initial Parameter Values:</strong> Next, <strong>pick random initial values for the parameters</strong> (e.g., the intercept and the slope). This serves as an initial guess for the algorithm to improve upon.</p>
</li>
<li>
<p><strong>Plug Parameter Values into Derivatives:</strong>  then <strong>plug these initial (or current) parameter values into the derivatives</strong> (the gradient) you calculated in Step 1. This gives the slope of the loss function at the current parameter values.</p>
</li>
<li>
<p><strong>Calculate Step Sizes:</strong> After obtaining the slopes, <strong>calculate the step sizes</strong>. The step size for each parameter is determined by <strong>multiplying its corresponding slope by a small number called the learning rate</strong>.</p>
</li>
<li>
<p><strong>Calculate New Parameters:</strong> Using the calculated step sizes, <strong>determine the new parameter values</strong>. The new parameter is typically the old parameter minus the step size.</p>
</li>
<li>
<p><strong>Repeat Until Convergence:</strong>  <strong>repeat steps 3 to 5</strong> until one of two conditions is met:</p>
</li>
</ol>
<p>◦ The <strong>step size becomes very small</strong> (e.g., 0.001 or smaller), indicating that the algorithm has approached the optimal value where the slope of the curve is close to zero.</p>
<p>◦ The <strong>maximum number of steps</strong> (e.g., 1000 or greater) is reached, acting as a safeguard to prevent endless iteration.</p>
<p>This iterative process allows Gradient Descent to take larger steps when far from the optimal solution and smaller “baby steps” as it gets closer to the minimum of the loss function. The algorithm is named <strong>“Gradient Descent”</strong> because it uses the gradient to descend to the lowest point in the loss function. When dealing with multiple parameters, the process remains the same, but involves taking more derivatives, one for each parameter.</p>
<p><img src="!%5BGradient.jpeg%5D(https://github.com/riti2043/images-for-articles/blob/main/Gradient.jpeg?raw=true)" alt=""></p>
<h3 id="common-evaluation-metrics-for-linear-regression">Common Evaluation Metrics for Linear Regression</h3>
<p>Evaluation metrics help determine the strength and performance of a linear regression model.</p>
<ol>
<li><strong>Mean Squared Error (MSE)</strong>  The Mean Squared Error (MSE) is an evaluation metric that calculates the <strong>average of the squared differences between the actual and predicted values</strong> for all data points. The squaring of differences ensures that negative and positive errors do not cancel each other out.<br>
The formula for MSE is:  <strong>MSE = (1/n) * Σ(yᵢ - ŷᵢ)²</strong><br>
Where:<br>
◦ <code>n</code> is the number of data points.</li>
</ol>
<p>◦ <code>yᵢ</code> is the actual or observed value for the iᵗʰ data point.</p>
<p>◦ <code>ŷᵢ</code> is the predicted value for the iᵗʰ data point.  MSE quantifies the accuracy of a model’s predictions and is <strong>sensitive to outliers</strong>, as large errors contribute significantly to the overall score. It is also employed as a cost function in linear regression to find optimal parameters.</p>
<ol start="2">
<li><strong>Coefficient of Determination (R-squared)</strong>  R-squared is a statistic that indicates <strong>how much variation the developed model can explain or capture</strong>. It is always in the range of 0 to 1, with a greater R-squared number generally indicating a better model fit to the data. It measures the <strong>proportion of variance in the dependent variable that is explained by the independent variables</strong> in the model.  The formula for R-squared is:<br>
<strong>R² = 1 - (RSS / TSS)</strong><br>
Where:</li>
</ol>
<p>◦ <strong>Residual Sum of Squares (RSS)</strong>: This is the sum of the squares of the residuals (differences between observed and anticipated output) for each data point. RSS = Σ(yᵢ - b₀ - b₁xᵢ)².</p>
<p>◦ <strong>Total Sum of Squares (TSS)</strong>: This is the sum of the data points’ errors from the mean of the dependent variable. TSS = Σ(y - ȳᵢ)².  An extension, <strong>Adjusted R-squared</strong>, measures the proportion of variance explained while <strong>accounting for the number of predictors</strong> in the model, penalising the model for including irrelevant predictors. This helps to prevent overfitting.</p>
<p>Other evaluation metrics mentioned include Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE)</p>
<p><strong>Regularisation techniques</strong> are used for linear models to improve performance by addressing overfitting and enhancing generalisation. Overfitting occurs when a model learns the training data too well but fails to generalise to new, unseen data.</p>

