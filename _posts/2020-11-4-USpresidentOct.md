---
layout: post
title:  "2020 US Presidential Election (Oct.)"
img: 2020_USpresident/USpoll2020.jpg
---

This is a poll conducted after the last debate (Oct. 22nd) for 2020 US Presidential Election.

<div class="jumbotron">
  <h4>What is the most important issue to you personally in the upcoming election?</h4>
</div>

| Summary | |
|------|------|
| Period | Oct. 26th -- 30th, 2020 |
| Num. of respondents | 278 |
| Num. of opinions | 177 |
| Num. of initial opinions | 0 |
| Platform | MTurk (US residents) |
{: .table .table-striped .table-hover}

<br>

## Response patterns
**Circular palette diagram**

<img src="{{site.baseurl}}/images/2020_USpresident/October/circular_palette_diagram.png" alt="fig_circular_palette"
style = "
  width: 600px;
  border: none;
  background: none;
  margin: 1% 1% 1% 1%;
  text-align: center;
  display: inline-block;
">

**Linear palette diagram**

<img src="{{site.baseurl}}/images/2020_USpresident/October/linear_palette_diagram.png" alt="fig_group_size"
style = "
  width: 600px;
  border: none;
  background: none;
  margin: 1% 1% 1% 10%;
  text-align: center;
  display: inline-block;
">

The above circular/linear palette diagrams show the response pattern of each respondent; the respondents are aligned azimuthally/horizontally, and their response patterns are shown radially/vertically. 
The color of the most dominant group is indicated at the center of the circular palette diagram. 
(See [here](https://github.com/palette-diagram/palette-diagram){:target="_blank"} for more details about the palette diagrams).


**Technical details**
- The data has been collected through *Aska*[^0], which generates a graph (network) as a result of a poll.
- Opinions are classified into groups using graph clustering based on the response patterns[^1].
- The group labels (i.e., coding) are determined by us, based on the classified opinion texts.
- No annotation has been performed in the present analysis. That's why we have groups of overlapped contents (*Economy* and *COVID-19 & Economy*) and there are few misclassified opinions. 

[^0]: We renamed our graph-based survey framework to *Aska* from *voteclustering*.
[^1]: You might have noticed that the opinion graph is too sparse to detect these groups. Actually, we have collected more than 278 responses (but with a slightly different setting) and we used those extra information behind to achieve this resolution. 


<br>


## Opinions in each opinion group
Popular opinions in each group are listed below.

<div class="card">
  <div class="card-header">
  Healthcare (25 posts)
  </div>
  <ul class="list-group list-group-flush">
  <li class="list-group-item">
    The most important to me is letting the president do his job. Parties working together. Accepting the results! Not destroying cities when you don't get your way.
    <br><span class="badge badge-dark">17 likes</span>
  </li>
  <li class="list-group-item">
    Some sort of health care reform to make it more affordable.
    <br><span class="badge badge-dark">14 likes</span>
  </li>
  <li class="list-group-item">
    The most important issue is access to affordable healthcare
    <br><span class="badge badge-dark">13 likes</span>
  </li>
  <div class="collapse" id="collapseExample0">
  <li class="list-group-item">
    Healthcare is the most important issue in the upcoming election. I have a pre-existing condition, a daughter who is covered under my policy but is now 23 years old and I have concern for siblings, family members and friends. 
    <br><span class="badge badge-dark">13 likes</span>
  </li>
  <li class="list-group-item">
    Healthcare reform and access
    <br><span class="badge badge-dark">13 likes</span>
  </li>
  <li class="list-group-item">
    Universal healthcare.
    <br><span class="badge badge-dark">13 likes</span>
  </li>
  <li class="list-group-item">
    Protecting health care and the affordable care act
    <br><span class="badge badge-dark">12 likes</span>
  </li>
  <li class="list-group-item">
    Change the president and change America
    <br><span class="badge badge-dark">11 likes</span>
  </li>
  <li class="list-group-item">
    climate change
    <br><span class="badge badge-dark">10 likes</span>
  </li>
  <li class="list-group-item">
    Improving basic human rights issues like health, nourishment, housing, and education.
    <br><span class="badge badge-dark">10 likes</span>
  </li>
  </div>
  <button class="btn btn-light btn-block" type="button" data-toggle="collapse" data-target="#collapseExample0" aria-expanded="false" aria-controls="collapseExample0">
    See more
  </button>
  </ul>
</div>

<div class="card">
  <div class="card-header">
  Economy (5 posts)
  </div>
  <ul class="list-group list-group-flush">
  <li class="list-group-item">
    Reopening and stabilizing the economy. Getting employment numbers back up. 
    <br><span class="badge badge-dark">12 likes</span>
  </li>
  <li class="list-group-item">
    I SUPPORT ALL THE RESPONSES FIRST THE PEOPLE AND THE ECONOMY HAS TO BE OPEN NORMAL AND MORE JOBS HERE IN FLORIDA THE MINIMUN WAGE
    <br><span class="badge badge-dark">5 likes</span>
  </li>
  <li class="list-group-item">
    The most important issue in the upcoming election is the economy. 
    <br><span class="badge badge-dark">4 likes</span>
  </li>
  <div class="collapse" id="collapseExample1">
  <li class="list-group-item">
    Income Inequality
    <br><span class="badge badge-dark">0 likes</span>
  </li>
  <li class="list-group-item">
    My most important issue is the current economy. 
    <br><span class="badge badge-dark">0 likes</span>
  </li>
  </div>
  <button class="btn btn-light btn-block" type="button" data-toggle="collapse" data-target="#collapseExample1" aria-expanded="false" aria-controls="collapseExample1">
    See more
  </button>
  </ul>
</div>

<div class="card">
  <div class="card-header">
  COVID-19 & Economy (75 posts)
  </div>
  <ul class="list-group list-group-flush">
  <li class="list-group-item">
    Covid-19 Relief 
    <br><span class="badge badge-dark">38 likes</span>
  </li>
  <li class="list-group-item">
    Economy
    <br><span class="badge badge-dark">33 likes</span>
  </li>
  <li class="list-group-item">
    Covid-19 measures.
    <br><span class="badge badge-dark">30 likes</span>
  </li>
  <div class="collapse" id="collapseExample2">
  <li class="list-group-item">
    The most important issue to me is re-opening the economy and getting back to our normal lives.
    <br><span class="badge badge-dark">23 likes</span>
  </li>
  <li class="list-group-item">
    bringing back the economy to what it was pre covid-19
    <br><span class="badge badge-dark">21 likes</span>
  </li>
  <li class="list-group-item">
    Our healthcare and for those with pre-existing conditions 
    <br><span class="badge badge-dark">19 likes</span>
  </li>
  <li class="list-group-item">
    Healthcare coverage for all Americans to help us through the pandemic and beyond.
    <br><span class="badge badge-dark">19 likes</span>
  </li>
  <li class="list-group-item">
    Coronavirus crises
    <br><span class="badge badge-dark">19 likes</span>
  </li>
  <li class="list-group-item">
    Solve Covid and preventing further sickness.
    <br><span class="badge badge-dark">19 likes</span>
  </li>
  <li class="list-group-item">
    Preserving the rights of the individual. 
    <br><span class="badge badge-dark">18 likes</span>
  </li>
  </div>
  <button class="btn btn-light btn-block" type="button" data-toggle="collapse" data-target="#collapseExample2" aria-expanded="false" aria-controls="collapseExample2">
    See more
  </button>
  </ul>
</div>

<div class="card">
  <div class="card-header">
  Racial equality (11 posts)
  </div>
  <ul class="list-group list-group-flush">
  <li class="list-group-item">
    Racial equality
    <br><span class="badge badge-dark">18 likes</span>
  </li>
  <li class="list-group-item">
    Reduce the taxes
    <br><span class="badge badge-dark">9 likes</span>
  </li>
  <li class="list-group-item">
    Social justice issues
    <br><span class="badge badge-dark">7 likes</span>
  </li>
  <div class="collapse" id="collapseExample3">
  <li class="list-group-item">
    ANY PARTY WILL BUT THE MAIN THING IS THE WORLD BECAME NORMAL
    <br><span class="badge badge-dark">4 likes</span>
  </li>
  <li class="list-group-item">
    criminal justice reform, specifically being more lenient on laws and prevent prison overcrowding
    <br><span class="badge badge-dark">4 likes</span>
  </li>
  <li class="list-group-item">
    Stopping the race-baiting and division of the population
    <br><span class="badge badge-dark">4 likes</span>
  </li>
  <li class="list-group-item">
    Equality. Justice. A president who doesn't give handouts but also had a heart
    <br><span class="badge badge-dark">4 likes</span>
  </li>
  <li class="list-group-item">
    Decency, ending racism and bringing the country together.
    <br><span class="badge badge-dark">3 likes</span>
  </li>
  <li class="list-group-item">
    Violence in the streets. 
    <br><span class="badge badge-dark">1 likes</span>
  </li>
  <li class="list-group-item">
    Some one with a moral compass. 
    <br><span class="badge badge-dark">1 likes</span>
  </li>
  </div>
  <button class="btn btn-light btn-block" type="button" data-toggle="collapse" data-target="#collapseExample3" aria-expanded="false" aria-controls="collapseExample3">
    See more
  </button>
  </ul>
</div>

<div class="card">
  <div class="card-header">
  Climate change, Women's rights, etc. (61 posts)
  </div>
  <ul class="list-group list-group-flush">
  <li class="list-group-item">
    The corruption and lawlessness of the current administration. 
    <br><span class="badge badge-dark">15 likes</span>
  </li>
  <li class="list-group-item">
    Immigration
    <br><span class="badge badge-dark">15 likes</span>
  </li>
  <li class="list-group-item">
    Hunger, homelessness, and affordable housing
    <br><span class="badge badge-dark">11 likes</span>
  </li>
  <div class="collapse" id="collapseExample4">
  <li class="list-group-item">
    Climate change solutions, not denials
    <br><span class="badge badge-dark">11 likes</span>
  </li>
  <li class="list-group-item">
    Women's rights/pro-choice
    <br><span class="badge badge-dark">10 likes</span>
  </li>
  <li class="list-group-item">
    abortion and reproductive rights 
    <br><span class="badge badge-dark">10 likes</span>
  </li>
  <li class="list-group-item">
    covid and harm reduction from conservatives 
    <br><span class="badge badge-dark">10 likes</span>
  </li>
  <li class="list-group-item">
    Equal rights for women
    <br><span class="badge badge-dark">9 likes</span>
  </li>
  <li class="list-group-item">
    Corruption actually being addressed and nepotism laws being enforced. The fact that Trump has funneled millions into his own businesses and contacts at the tax payers expense is out of line and He should have sold off Mar-a-lag
    <br><span class="badge badge-dark">9 likes</span>
  </li>
  <li class="list-group-item">
    Climate change.
    <br><span class="badge badge-dark">9 likes</span>
  </li>
  </div>
  <button class="btn btn-light btn-block" type="button" data-toggle="collapse" data-target="#collapseExample4" aria-expanded="false" aria-controls="collapseExample4">
    See more
  </button>
  </ul>
</div>


<hr>


