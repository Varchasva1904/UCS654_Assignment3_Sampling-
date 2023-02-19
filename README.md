# Sampling Assignment
<h2> Introduction </h2>
This study investigates the efficacy of various sampling approaches in producing a balanced dataset for a machine learning model. To produce a balanced dataset, random over-sampling and under-sampling techniques are used. The accuracy of the samples produced by the subsequent five sampling approaches are compared using five different machine learning models on this balanced dataset.<br>
The following five sampling techniques were used in this project:-<br>
<h4>Simple Random Sampling-</h4> In the statistical technique known as simple random sampling, each member of the population has an equal probability of being chosen for the sample. Each member of the population is independently and randomly chosen using simple random sampling, with no bias or preference.<br>
<h4>Stratified Sampling-</h4> In order to ensure that the sample is representative of the population, stratified sampling is a statistical sampling technique that divides a population into subgroups or strata and then chooses samples from each stratum in proportion to its size.This is done to ensure that the sample accurately represents the population in terms of important characteristics or variables.<br>
<h4>Systematic Sampling-</h4> Systematic sampling is a statistical sampling approach that involves choosing the k-th member of a population, where k is a specified interval or "sampling interval."The first member of the sample is randomly selected from the population, and subsequent members are selected at regular intervals thereafter.<br>
<h4>Cluster Sampling-</h4> Cluster sampling is a statistical sampling technique that involves grouping a population into clusters or groups and choosing a representative sample of those clusters at random to be included in the study. The sample is then expanded to include every individual from the chosen clusters.Then, all members of the selected clusters are included in the sample.<br>
<h4>Convenience Sampling-</h4> Convenience sampling is a non-probability sampling technique where participants are chosen for a study based on their availability or ease of accessibility to the researcher. When a researcher has to quickly collect data but lacks the time.<br>
<h2> Comparison Table </h2>
The table below shows the accuracies of each sampling technique on five different machine learning models. The dataset used for all models is a balanced version of the original unbalanced dataset using random over-sampling and under-sampling techniques.<br>
<br>
<table class="tg">
<thead>
  <tr>
    <th class="tg-teqq">Sampling Technique</th>
    <th class="tg-teqq">Extra Trees Classifier</th>
    <th class="tg-teqq">Random Forest Classifier</th>
    <th class="tg-teqq">Gradient Boosting Classifier</th>
    <th class="tg-4lcc">K- Nearest Neighbours</th>
    <th class="tg-4lcc">Logistic Regression</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">Simple Random Sampling</td>
    <td class="tg-baqh">1.0000</td>
    <td class="tg-baqh">0.9963</td>
    <td class="tg-baqh">0.9887</td>
    <td class="tg-baqh">0.9070</td>
    <td class="tg-baqh">0.8699</td>
  </tr>
  <tr>
    <td class="tg-0lax">Systematic Sampling</td>
    <td class="tg-baqh">1.0000</td>
    <td class="tg-baqh">1.0000</td>
    <td class="tg-baqh">0.9983</td>
    <td class="tg-baqh">0.9621</td>
    <td class="tg-baqh">0.9241</td>
  </tr>
  <tr>
    <td class="tg-0lax">Stratified Sampling</td>
    <td class="tg-baqh">0.9981</td>
    <td class="tg-baqh">0.9944</td>
    <td class="tg-baqh">0.9888</td>
    <td class="tg-baqh">0.9572</td>
    <td class="tg-baqh">0.9199</td>
  </tr>
  <tr>
    <td class="tg-0lax">Cluster Sampling</td>
    <td class="tg-baqh">1.0000</td>
    <td class="tg-baqh">0.9966</td>
    <td class="tg-baqh">0.9966</td>
    <td class="tg-baqh">0.9603</td>
    <td class="tg-baqh">0.9121</td>
  </tr>
  <tr>
    <td class="tg-0lax">Convenience Sampling</td>
    <td class="tg-baqh">1.0000</td>
    <td class="tg-baqh">0.9981</td>
    <td class="tg-baqh">0.9811</td>
    <td class="tg-baqh">0.9567</td>
    <td class="tg-baqh">0.9246</td>
  </tr>
</tbody>
</table>

<h2> Conclusion </h2>
Based on these results, it can be concluded that Cluster Sampling performs the best on all five models. Simple random sampling performs the worst on all five models. The other sampling techniques have varying performance depending on the model. The model which gives the best accuracy for all 5 samples is Extra Tree Classifier.
