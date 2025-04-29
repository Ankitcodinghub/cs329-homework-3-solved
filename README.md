# cs329-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [CS329 Homework#3 Solved](https://www.ankitcodinghub.com/product/cs329-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115922&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS329 Homework#3  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

Question 1

Consider a data set in which each data point tn is associated with a weighting factor rn &gt; 0, so that the sum-of-squares error function becomes

1 ∑N T (xn)}2.

ED(w) = rn{tn − w φ

2 n=1

Find an expression for the solution w∗ that minimizes this error function. Give two alternative interpretations of the weighted sum-of-squares error function in terms of

(i) data dependent noise variance and (ii) replicated data points.

Question 2

We saw in Section 2.3.6 that the conjugate prior for a Gaussian distribution with unknown mean and unknown precision (inverse variance) is a normal-gamma distribution. This property also holds for the case of the conditional Gaussian distribution

p(t|x, w, β) of the linear regression model. If we consider the likelihood function,

N

p(t|X, w, β) = ∏ N(tn|wTφ(xn), β−1)

n=1

then the conjugate prior for w and β is given by

p(w, β) = N(w|m0, β−1S0)Gam(β|a0, b0).

Show that the corresponding posterior distribution takes the same functional form,so that

p(w, β|t) = N(w|mN, β−1SN)Gam(β|aN, bN).

and find expressions for the posterior parameters mN, SN, aN, and bN.

1

Question 3

Show that the integration over w in the Bayesian linear regression model gives the result

Z

exp{−E(w)}dw = exp{−E(mN)}(2π)M/2|A|−1/2.

Hence show that the log marginal likelihood is given by

N

ln(2π).

2

Question 4

Consider real-valued variables X and Y . The Y variable is generated, conditional on X, from the following process:

e ∼ N(0, σ2)

Y = aX + e

where every e is an independent variable, called a noise term, which is drawn from a Gaussian distribution with mean 0, and standard deviation σ. This is a one-feature linear regression model, where a is the only weight parameter. The conditional probability of Y has distribution p(Y|X, a) ∼ N(aX, σ2), so it can be written as

p

Assume we have a training dataset of n pairs (Xi,Yi) for i = 1…n, and σ is known. Derive the maximum likelihood estimate of the parameter a in terms of the training example Xi0s and Yi0s. We recommend you start with the simplest form of the problem:

1

F(a) = ∑(Yi − aXi)2 2 i

Question 5

If a data point y follows the Poisson distribution with rate parameter θ, then the probability of a single observation y is

θ e−θ y

p(y|θ) = , for y = 0, 1, 2, . . .

y!

You are given data points y1, . . . , yn independently drawn from a Poisson distribution with parameter θ . Write down the log-likelihood of the data as a function of θ .

Question 6

Suppose you are given n observations, X1, . . . , Xn, independent and identically distributed with a Gamma(α, λ) distribution. The following information might be useful for the problem. (a) If X ∼ Gamma(α, λ), then E[X] = and E[X2] = α(α+21)

λ

(b) The probability density function of X ∼ Gamma(α, λ) is fX x where the function Γ is only dependent on α and not λ.

Suppose, we are given a known, fixed value for α. Compute the maximum likelihood estimator for λ.

Program Question

In this question, we will try to use logistic regression to solve a binary classification problem. Given some information of a house, such as area and the number of living rooms, would it be expensive? We would like to predict 1 if it is expensive, and 0 otherwise. We will use the hw3_house_sales.zip dataset.

We will first implement it with python Scikit learn package, and then try to implement it by updating weights with gradient descent. We will derive the gradient formula, and use Stochastic gradient descent and AdaGrad to calculate the weights.

(a) Logistic regression with Scikit. Fill in the logisticRegressionScikit() function using the Scikit toolbox.

Report the weights and prediction accuracy here in your submitted file.

(b) Gradient derivation. Assume a sigmoid is applied to a linear function of the input features:

1 hw(x) = −wTx 1 + e

Assume also that P(y = 1|x; w) = hw(x), P(y = 0|x; w) = 1 − hw(x). Calculate the maximum likelihood estimation L(w) = P(Y|X; w), then formulate the stochastic gradient ascent rule. Please writing out the log likelihood, calculating the derivative and writing out the update formula step by step.

(c) Logistic regression with simple gradient descent. Fill in the LogisticRegressionSGD() function. To do that, two helper functions sigmoid_activation(), to calculate the sigmoid function result, and model_optimize(), to calculate the gradient of w, will be needed. Both helper functions can be used in the following AdaGrad optimization function. Use a learning rate of 10−4, run with 2000 iterations. Keep track of the accuracy every 100 iterations in the training set (no need to report). It will be used later.

Report weights, training accuracy and test accuracy here in your submitted file. Your final score will depends on correct sigmoid_activation(), model_optimize(), LogisticRegressionSGD() functions.

(d) Logistic regression with AdaGrad. Fill in the LogisticRegressionAda() function. Use a learning rate of 10−4, run with 2000 iterations. Keep tracks of the accuracy every 100 iterations in the training set (no need to report). It will be used later. Report weights, training accuracy and test accuracy here in your submitted file.

(e) Comparision of Scikit, SGD and AdaGrad convergence. Plot the loss function of SGD and AdaGrad over 2000 iterations on both the training and test data. What do you observe? Which one has better accuracy on the test dataset? Why might that be the case?
