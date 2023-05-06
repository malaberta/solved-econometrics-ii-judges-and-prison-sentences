Download Link: https://assignmentchef.com/product/solved-econometrics-ii-judges-and-prison-sentences
<br>
<h1>Problem 1: Judges and Prison Sentences</h1>

A researcher is interested in the effect of prison sentence on later criminal behavior. The researcher collects data from one particular court, which has two active judges. The researcher learns that cases are assigned randomly to the judges. However, judge Jones convicts someone to a prison sentence in 70% of the cases while judge Smith only convicts someone to a prison sentence in 40% of the cases. Next, the researcher collects information on whether or not an individual is arrested in the three years after the trial.

<table width="344">

 <tbody>

  <tr>

   <td width="112">Judge</td>

   <td colspan="2" width="116">Jones</td>

   <td colspan="2" width="116">Smith</td>

  </tr>

  <tr>

   <td width="112">Sentences</td>

   <td width="68">Prison</td>

   <td width="48">Other</td>

   <td width="68">Prison</td>

   <td width="48">Other</td>

  </tr>

  <tr>

   <td width="112">Cases</td>

   <td width="68">70%</td>

   <td width="48">30%</td>

   <td width="68">40%</td>

   <td width="48">60%</td>

  </tr>

  <tr>

   <td width="112">Future arrests</td>

   <td width="68">40%</td>

   <td width="48">60%</td>

   <td width="68">20%</td>

   <td width="48">50%</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Use the Wald estimator to compute the causal effect of a prison sentence on the probability of being arrested later.</li>

 <li>What is the interpretation of the estimated effect? And for which fraction of the population does this causal effect hold?</li>

 <li>Explain what an always taker is in this setting and which fraction of the population are always takers?</li>

</ul>

<h1>Problem 2: Eating and exams</h1>

A teacher is interested in how important eating and drinking is for academic achievement. Therefore, the teacher decides to run a field experiment. The teacher randomizes students into two groups. The control group is allowed to have breakfast and snacks before the exam. The treatment group is only allowed to have a glass of milk in the morning and drink water during the remaining time before the exam. The key outcome variable of interest is passing the exam. In past years about 50% of the students passed the exam. The teacher thinks that not eating or drinking will reduce the passing rate with 10%-points. The teacher is aiming for 70% power in the field experiment and a significance level of 5% (recall <em>t</em><sub>0<em>.</em>3 </sub>= −0<em>.</em>524 and <em>t</em><sub>0<em>.</em>975 </sub>= 1<em>.</em>960). The teacher randomizes students equally over the treatment and control group.

<ul>

 <li>Perform a power calculation for the number of students that the teacher should include in the field experiment.</li>

</ul>

The teacher is afraid that some people in the treatment group will actually have breakfast. Furthermore he assumes that all people in the control group will have breakfast.

<ul>

 <li>The teacher assumes that 20% of the students randomized in the treatment group will actually have breakfast. How does this change the number of students required to participate in the field experiment?</li>

</ul>

<h1>Problem 3: Flu shots for young children</h1>

A researcher is interested in studying the effects of providing flu shots for young children. Therefore, the researcher sets up a randomized experiment in which about 20% of the children are not entitled to a flu shot. The remaining 80% of the children are supposed to get a flu shot. The randomization is expressed in the variable TreatGroup in the excel-sheet or Stata-file. The key outcome variable is whether or not children get the flu, which is described by the dummy-variable Flu.

<ul>

 <li>Compute for the children assigned to the control group the variance in flu incidence. If the researcher aims at reducing flu incidence by 0.05, how many children should participate in the randomized experiment.</li>

</ul>

Unfortunately for the researcher, there was a shortage of flu shots, and therefore not all children in the treatment group could actually get a flu shot. The variable Treatment indicates which children got a flu shot.

<ul>

 <li>Compute which fraction of the children in the treatment group actually received a flu shot. What is the implication for the power analysis of the experiment?</li>

</ul>

The researcher hopes that within the treatment group the flu shots are randomly assigned to children. Therefore, the researcher considers the background characteristics gender of the child, age of the mother at birth, years of education of the mother, whether or not the mother is married, nationality and monthly household income.

<ul>

 <li>Make a table with summary statistics for (1) the control group, (2) the treated treatment group, and (3) the untreated treatment group. What do you conclude?</li>

</ul>

The researcher first focuses on only those children randomized in the treatment group. The researcher specifies the linear regression model

Flu<em><sub>i </sub></em>= <em>α </em>+ <em>δ </em>Flu Shot<em><sub>i </sub></em>+ <em>U<sub>i</sub></em>

<ul>

 <li>Estimate this model using OLS. Next, include subsequently the individual characteristics. What do you learn from these regressions?</li>

</ul>

The researcher returns to the specification

Flu<em><sub>i </sub></em>= <em>α </em>+ <em>δ </em>Flu Shot<em><sub>i </sub></em>+ <em>U<sub>i</sub></em>

but decides to instrument whether or not a child actually had a flu shot by the assignment to the treatment group.

<ul>

 <li>Use 2SLS to estimate <em>δ </em>and check the robustness with respect to adding individual characteristics.</li>

</ul>

Now consider the first-stage regression

Flu Shot<em><sub>i </sub></em>= <em>γ</em><sub>0 </sub>+ <em>γ</em><sub>1 </sub>Treatment Group<em><sub>i </sub></em>+ <em>V<sub>i</sub></em>

<ul>

 <li>Estimate the first-stage regression using OLS. Are you afraid of a weak instruments problem?</li>

 <li>Explain why in this case the local average treatment effect is the same as the average treatment effect on the treated.</li>

</ul>