---
layout: post
title:  "2020 US Presidential Election (Sep.)"
img: 2020_USpresident/USpoll2020.jpg
---

The first Presidential Debate for 2020 US Presidential Election took place on Sep. 29th. 


<div class="jumbotron">
  <h4>What is the most important issue to you personally in the upcoming election?</h4>
</div>

Using our open-ened survey system, we have conducted a poll from Sep. 30th to Oct. 2nd. 
We recruited 881 respondents through Amazon Mechanical Turk [^0].

[^0]: Disclaimer: The results here may not be accurate. Moreover, it is possible that the results presented here may be update in the future.

<br>

## Response patterns

<img src="{{site.baseurl}}/images/2020_USpresident/population_matrix.png" alt="fig_popularity"
style = "
  width: 600px;
  border: none;
  background: none;
  margin: 1% 1% 1% 1%;
  text-align: center;
  display: inline-block;
">

In this poll, we identified three statistically distinct respondents groups [^1]. 
Each row in the above table represents an opinion group and each column represents a respondent group. 
The value in a cell is the fraction (in percentage) of "Likes," which is normalized within each column. 
You can find the list of actual opinion texts at the bottom of this post. 

[^1]: There is no initially prepared opinions in this poll.

The fractions of ***Economy*** and ***Healthcare*** are high in every respondent group. 
We found several other topics and categorized them as the opinion groups [^2]; many of them are related to recent unprecedented events such as COVID-19, wildfire, Black lives matter issues, and death of Ruth Bader Ginsburg. 
The three respondent groups have different response patterns for these topics. 

[^2]: We put annotations on most of the opinions, and utilized them in graph clustering. 

It is evident that respondent group B is characterized by ***Support Biden, Never Trump***. 
In contrast, we can hardly conclude that groups A and C are Trump supporters. 
The fact that the fractions of ***Support Trump*** are 5.2% and 2.3% in these groups indicates that this is not their major issue; note that this result does not implies that there are not so many Trump supporters or Joe Biden is in the lead. 
The population of each respondent group is shown below. 



**Population of the respondent groups**

<img src="{{site.baseurl}}/images/2020_USpresident/respondent_population.png" alt="fig_group_size"
style = "
  width: 400px;
  border: none;
  background: none;
  margin: 1% 1% 1% 10%;
  text-align: center;
  display: inline-block;
">


The acutal opinion texts of each category are listed below. 
Among 144 independent opinions [^3], we only show few of them that earned many "Likes."

[^3]: We have excluded invalid opinions. 

<div class="card">
  <div class="card-header">
    "Kindness"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      Love and unity
      <br><span class="badge badge-dark">27 likes</span>
    </li>
    <li class="list-group-item">
      Be kind.
      <br><span class="badge badge-dark">27 likes</span>
    </li>
    <li class="list-group-item">
      Kindness, compassion, and decency. I'd like for there to be more important things to the administration than their own power and income.
      <br><span class="badge badge-dark">23 likes</span>
    </li>
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Climate change"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      Taking action on climate change
      <br><span class="badge badge-dark">67 likes</span>
    </li>
    <li class="list-group-item">
      Pass laws that address climate change by reducing the use of fossil fuels and encouraging the use of alternative energy sources 
      <br><span class="badge badge-dark">61 likes</span>
    </li>
    <li class="list-group-item">
      Climate Change
      <br><span class="badge badge-dark">56 likes</span>
    </li>    
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Other responses"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      eliminating world wide corruption
      <br><span class="badge badge-dark">90 likes</span>
    </li>
    <li class="list-group-item">
      Basic human decency.
      <br><span class="badge badge-dark">64 likes</span>
    </li>
    <li class="list-group-item">
      No new wars, reigning in the riots, removing anti-white and anti-American propaganda from schools ending all COVID lockdowns/stay at home orders, stopping Democrat politicians from imposing open-ended unconstitutional limitations on American citizens.
      <br><span class="badge badge-dark">45 likes</span>
    </li>
    <li class="list-group-item">
      Review and rewrite outdated laws and their process. 
      <br><span class="badge badge-dark">30 likes</span>
    </li>
    <li class="list-group-item">
      We have had Democratic presidents and Republican presidents. The country always survives no matter who is in power.
      <br><span class="badge badge-dark">28 likes</span>
    </li>    
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "COVID-19"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      COVID-19 GOING TO DO THE ALL EFFECTS IN ELECTION. WE NEED TO WAIT AND SEE IT
      <br><span class="badge badge-dark">110 likes</span>
    </li>
    <li class="list-group-item">
      The COIVD virus. Slowing the spread and saving lives. And the economy
      <br><span class="badge badge-dark">98 likes</span>
    </li>
    <li class="list-group-item">
      How covid 19 influences job market.
      <br><span class="badge badge-dark">97 likes</span>
    </li>    
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Support Biden/Never Trump"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      Having a functional adult in office
      <br><span class="badge badge-dark">75 likes</span>
    </li>
    <li class="list-group-item">
      Biden earned a reputation for being a "drug warrior", leading efforts in the war on drugs
      <br><span class="badge badge-dark">65 likes</span>
    </li>
    <li class="list-group-item">
      Who else believes that Donald tRump is a narcissist?
      <br><span class="badge badge-dark">64 likes</span>
    </li>
    <li class="list-group-item">
      Getting sanity and professionalism back into the White House and leading our country once again
      <br><span class="badge badge-dark">63 likes</span>
    </li>
    <li class="list-group-item">
      I support Biden for president. 
      <br><span class="badge badge-dark">62 likes</span>
    </li>    
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Healthcare"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      I want to see healthcare become more affordable and that is available to everyone. No person should go bankrupt because of healthcare bills. 
      <br><span class="badge badge-dark">84 likes</span>
    </li>
    <li class="list-group-item">
      Universal Healthcare
      <br><span class="badge badge-dark">71 likes</span>
    </li>
    <li class="list-group-item">
      Medicare for all
      <br><span class="badge badge-dark">70 likes</span>
    </li>    
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Economy"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      Universal Basic Income so people can breathe and stop living paycheck to paycheck in fear that if 1 little thing happens you lose it all
      <br><span class="badge badge-dark">63 likes</span>
    </li>
    <li class="list-group-item">
      Economy and jobs
      <br><span class="badge badge-dark">55 likes</span>
    </li>
    <li class="list-group-item">
      Protect the working middle class
      <br><span class="badge badge-dark">55 likes</span>
    </li>
    <li class="list-group-item">
      Student debt crisis.
      <br><span class="badge badge-dark">54 likes</span>
    </li>    
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Black lives matter"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      Stopping police murders and brutality toward Black people
      <br><span class="badge badge-dark">44 likes</span>
    </li>
    <li class="list-group-item">
      Stopping environmental racism
      <br><span class="badge badge-dark">43 likes</span>
    </li>
    <li class="list-group-item">
      Electing people who will respect our constitution and the values that REALLY make our nation great, instead of the bigotry and hatred espoused by white supremacists.
      <br><span class="badge badge-dark">43 likes</span>
    </li>
    <li class="list-group-item">
      I think race issues are the biggest problem right now.  It's become ridiculous all these people protesting, rioting, etc over two people who were involved in criminal activity.
      <br><span class="badge badge-dark">40 likes</span>
    </li>    
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Aptitude as the president"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      Taking a step back and seeing the destruction of mankind in its self by the very ones who think they are upholding good values for the nation 
      <br><span class="badge badge-dark">51 likes</span>
    </li>
    <li class="list-group-item">
      Bringing people into office who prioritize what is best for the nation as a whole, instead of just an elite few.
      <br><span class="badge badge-dark">41 likes</span>
    </li>
    <li class="list-group-item">
      I believe that the president should be able to lead the nation out of hardship.
      <br><span class="badge badge-dark">41 likes</span>
    </li>    
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Violence"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      Safety for myself and family.
      <br><span class="badge badge-dark">83 likes</span>
    </li>
    <li class="list-group-item">
      right wing violence
      <br><span class="badge badge-dark">79 likes</span>
    </li>
    <li class="list-group-item">
      Violence in America
      <br><span class="badge badge-dark">75 likes</span>
    </li>    
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Support Trump"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      I want to see our country continue in the right direction and love on the people inside it’s borders
      <br><span class="badge badge-dark">28 likes</span>
    </li>
    <li class="list-group-item">
      Trump 2020
      <br><span class="badge badge-dark">26 likes</span>
    </li>
    <li class="list-group-item">
      I support Trump for president. 
      <br><span class="badge badge-dark">26 likes</span>
    </li>    
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "LGBT rights"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      Keeping and expanding on the rights for LGBT+ people, please do not take away my right to marry.
      <br><span class="badge badge-dark">88 likes</span>
    </li>
    <li class="list-group-item">
      Rights and protections for LGBT+ individuals, stopping the epidemic of violence against trans people
      <br><span class="badge badge-dark">76 likes</span>
    </li>
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Women's rights"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      Women's rights and their right to choose, keep abortion safe and legal.
      <br><span class="badge badge-dark">79 likes</span>
    </li>
    <li class="list-group-item">
      Overturning Roe v. Wade
      <br><span class="badge badge-dark">75 likes</span>
    </li>
    <li class="list-group-item">
      Women's reproductive rights (easier and more affordable access to feminine hygiene products, revised abortion laws, etc.)
      <br><span class="badge badge-dark">72 likes</span>
    </li>    
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Democracy"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      Saving our democracy.
      <br><span class="badge badge-dark">65 likes</span>
    </li>
    <li class="list-group-item">
      Protect, preserve and expand where needed any and all issues which would threaten DEMOCRACY and each and every citizen's rights within said Democracy.
      <br><span class="badge badge-dark">59 likes</span>
    </li>
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Immigration"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      Abolishing ICE and ensuring safe asylum for refugees and others
      <br><span class="badge badge-dark">54 likes</span>
    </li>
    <li class="list-group-item">
      10 year moratorium on legal immigration
      <br><span class="badge badge-dark">53 likes</span>
    </li>
    <li class="list-group-item">
      illegal immigration 
      <br><span class="badge badge-dark">51 likes</span>
    </li>
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "Fascism"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      Respecting Law and Order, denouncing ANTIFA
      <br><span class="badge badge-dark">54 likes</span>
    </li>
    <li class="list-group-item">
      Stopping America's descent into fascism
      <br><span class="badge badge-dark">46 likes</span>
    </li>
  </ul>
</div>

<div class="card">
  <div class="card-header">
    "2nd amendment"
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item">
      2nd amendment 
      <br><span class="badge badge-dark">67 likes</span>
    </li>
    <li class="list-group-item">
      2nd amendment AND 1ST ADMENDMENT!!!! 
      <br><span class="badge badge-dark">59 likes</span>
    </li>
    <li class="list-group-item">
      Defending the right to keep and bear arms.
      <br><span class="badge badge-dark">49 likes</span>
    </li>
  </ul>
</div>




<!-- ## 分析手法
- Non-negative matrix factorization (no annotations, no manual post-processing)
 -->

---


