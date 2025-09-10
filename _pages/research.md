---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.paper-title {
  font-size: 1.2em;
  font-weight: bold;
  margin-top: 20px;
  margin-bottom: 10px;
}

.abstract-button {
  background-color: #0366d6;
  color: white;
  border: none;
  padding: 5px 10px;
  cursor: pointer;
  border-radius: 3px;
  font-size: 0.9em;
  margin-top: 5px;
}

.abstract-button:hover {
  background-color: #0256c7;
}

.abstract-content {
  display: none;
  margin-top: 10px;
  padding: 15px;
  background-color: #add8ff;
  border-left: 4px solid #0366d6;
  border-radius: 3px;
}

.coauthors {
  font-style: italic;
  margin-bottom: 5px;
}
  /* Dark mode fixes for abstracts */
@media (prefers-color-scheme: dark) {
  .paper-title {
    color: #f3f4f6;           /* light text */
  }
  .coauthors {
    color: #cbd5e1;           /* softer light text */
  }
  .abstract-content {
    background-color: #111827; /* dark panel */
    color: #e5e7eb;            /* readable text */
    border-left-color: #60a5fa;
  }
  .abstract-content a {
    color: #93c5fd;           /* link visible on dark */
    text-decoration: underline;
  }
  .abstract-content code {
    background: #1f2937;      /* code blocks readable */
    color: #e5e7eb;
  }
  .abstract-button {
    background-color: #3b82f6; /* brighter button for dark */
    color: #0b1220;
  }
  .abstract-button:hover {
    background-color: #2563eb;
  }
  .abstract-button:focus-visible {
    outline: 2px solid #93c5fd;
    outline-offset: 2px;
  }
}
</style>

<script>
function toggleAbstract(id) {
  var abstract = document.getElementById(id);
  var button = document.getElementById(id + '-button');
  if (abstract.style.display === "none" || abstract.style.display === "") {
    abstract.style.display = "block";
    button.innerHTML = "Hide Abstract";
  } else {
    abstract.style.display = "none";
    button.innerHTML = "Show Abstract";
  }
}
</script>

## Working Papers

<div class="paper-title">Joining the Revolution: Elite Support for Revolutionary Movements</div>
<div class="coauthors">with Daniel Baquero</div>


<button class="abstract-button" id="paper1-abstract-button" onclick="toggleAbstract('paper1-abstract')">Show Abstract</button>
<div id="paper1-abstract" class="abstract-content">
Recent research suggests that politically excluded elites play a crucial role in revolutions and regime transitions. However, little research has been conducted on the factors that lead to the emergence of these elites. We propose that international trade is an important yet understudied cause of the emergence of such elites. In agrarian, commodity-exporting countries, economic integration can be highly lucrative for the incumbent government. However, shifts in international demand for commodities, such as those driven by technological innovations, create opportunities for individuals outside the autocratic coalition—such as landowners in politically marginalized regions—to gain economic power. In this project, we leverage shifts in American imports of agricultural commodities during the Second Industrial Revolution as an exogenous cause of the emergence of anti-regime elites during the Mexican Revolution. Using biographical data on over 5,000 key figures from the Mexican Revolution, we identify and geolocate elite revolutionary leaders. Our analysis shows that the local trade shock intensity is significantly associated with the emergence of elite revolutionary leaders in regions where local elites were politically marginalized. Our study provides causal evidence that trade shocks can create elites who are politically excluded yet economically powerful, highlighting international trade as a critical yet previously overlooked driver of elite-led regime change.
</div>

---

<div class="paper-title">Elite Clubs and Political Office Holding</div>
<div class="coauthors">with Julienne Labonne, Pablo Querubin, Sebastian Saiegh, and Shanker Satyanath</div>

<button class="abstract-button" id="paper2-abstract-button" onclick="toggleAbstract('paper2-abstract')">Show Abstract</button>
<div id="paper2-abstract" class="abstract-content">
An extensive literature argues that social associations facilitate participation in politics. This paper contributes to this literature by studying the effect of elite club membership on political office holding. We argue that elite social clubs broaden members’ social networks, which are critical for gaining political power in highly clientelistic societies. We exploit the founding of the Buenos Aires Jockey Club—the most prominent elite club in Argentina—in 1882 to identify the causal effect of elite club membership on political office holding. Our data—collected from numerous historical sources—allow us to use a robust two-way fixed effects empirical strategy for identification. We find that Jockey Club membership substantially increases the probability of winning a legislative position. We also show that membership in the Jockey Club increases a family’s eigenvector centrality in elite marriage networks. Our paper provides robust causal evidence that elite social club membership substantially increases access to political power.
</div>

---

<div class="paper-title">Economic Growth and Working-class Representation: Evidence from Brazil</div>
<div class="coauthors">with Jamil Civitarese</div>

<button class="abstract-button" id="paper3-abstract-button" onclick="toggleAbstract('paper3-abstract')">Show Abstract</button>
<div id="paper3-abstract" class="abstract-content">
Economic growth is often assumed to broaden political inclusion, yet it can just as easily entrench political inequality. Drawing on a panel that identifies the occupational background of every city-council candidate in Brazil from 2004 to 2020, we show that periods of elite-biased growth erode working-class representation. We show that economic growth widens the campaign finance gap between affluent and working-class candidates, leading to fewer elected working class candidates. Two-way fixed-effects estimates and politician-level difference-in-differences models reveal a consistent negative association between sustained municipal economic growth and the electoral participation of working-class candidates. The effect is concentrated among right-wing parties and in rural municipalities, settings where elite dominance and weak party-labor ties are most pronounced. A controlled qualitative comparison further reveals that right-wing parties actively accommodate donor preferences by selecting richer candidates and prioritizing elite interests, offering direct evidence for the mechanisms linking growth to political exclusion.
</div>

---

## Work in Progress


<div class="paper-title">When Winners Revolt: Export Shocks and Electoral Backlash in Competitive Autocracies.</div>
<div class="coauthors"></div>


---

<div class="paper-title">Trade Shocks, Elite Splits, and the Origins of Redistributive Coalitions</div>
<div class="coauthors"></div>
