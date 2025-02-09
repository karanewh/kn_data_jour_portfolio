# Kara Newhouse Data Journalism Portfolio
## Overview
<p>I am committed to journalism that holds public officials accountable and shines a light on systemic inequities. This repository includes examples of my work using data to discover, report and tell those kinds of stories.</p>

## :basketball_woman: Unlevel Playing Fields: Flaws in federal Title IX data
<p>Through public records requests, data analysis and traditional reporting, I found that <a href"https://cnsmaryland.org/2022/04/11/title-ix-federal-sports-data/">federal data often overstates high school girls’ participation in sports</a>. That makes it impossible to tell whether schools are in compliance with Title IX, unless someone complains.<p>
<p>This story ran on the front page of <a href="https://www.baltimoresun.com/sports/bs-sp-cns-federal-title-ix-sports-data-unreliable-20220427-baaxhw2ebfcclegy564idvieey-story.html">The Baltimore Sun<a>. It was part of “Unlevel Playing Fields,” a series that examined the continued obstacles to gender equity in high school sports as Title IX turned 50. I also produced <a href="https://cnsmaryland.org/2022/04/11/title-ix-federal-sports-data/">data visualizations<a></a> for the story. The underlying code for my data analysis and graphics can be seen in the <a href="https://howard-center-investigations.github.io/title-ix/fact_check.html">fact check notebook<a> that accompanied the story.</p>
  
## :newspaper: Printing Hate: Newspaper lineage web scraper
<p>For "Printing Hate," a <a href="https://lynching.cnsmaryland.org/">series</a> and <a href="https://cnsmaryland.org/lynching/lynching_data/index.html">news app</a> examining white-owned newspapers' role in promoting racial terror lynchings, a colleague and I built a web scraper that uses the Library of Congress' <a href="https://chroniclingamerica.loc.gov/search/titles/">U.S. Newspaper Directory</a> to access more than 150,000 newspapers' lineage information. We created a ‘newspaper family tree,’ which we connected to historians’ lynching victim datasets. We wrote the code for <a href ="https://github.com/karanewh/kn_data_jour_portfolio/blob/main/loc_scraper_kara.ipynb">loc_scraper_kara.ipynb</a> in Python using Selenium and exported the resulting files for further manipulation and analysis in R. This scraper laid the foundation for analysis of historical newspaper coverage about our topic. In addition to working on the archival database, I conducted a gender analysis of the lynching dataset in R for an article on <a href="https://lynching.cnsmaryland.org/2021/11/10/black-women-lynchings/">how lynchings of Black women were covered</a>.</p>

## :balance_scale: Courts Slackbot
<p>I created <a href=https://github.com/karanewh/courts-slackbot>Courts Slackbot</a> to solve a problem I experienced as a local education reporter in Pennsylvania: keeping track of lawsuits against school districts I covered. The bot uses a Python script to parse entries from a list of RSS feeds for court dockets and search for the phrase "school district" in the entry titles. If those keywords appear, it sends a Slack message containing the case title, a link to its docket sheet in Pacer and a description of the latest activity.</p>

## :safety_vest: Essential and Exposed: Analysis of workplace COVID-19 outbreaks
<p>Analysis of state health department records led to key findings for <a href="https://cnsmaryland.org/2021/05/12/as-walmart-sales-soared-workers-got-scant-covid-19-protection-from-osha/">"Essential and Exposed,"</a> a Howard Center for Investigative Journalism project on worker safety during the first year of the COVID-19 pandemic. We found that essential workers at places like Walmart paid the price for splintered government oversight. The 13 data findings that shaped the final story, along with their underlying code, can be seen in our <a href="https://howard-center-investigations.github.io/essential_and_exposed/osha_walmart/index.html">line-by-line fact check</a>.</p>
<p>From records acquisition to analysis to many late-night rounds of writing, revising and fact checking, I was deeply involved in every aspect of the data work on this project. My responsibilities included:
<ul>
  <li>Coordinating a 50-person public records campaign to obtain data on workplace COVID-19 outbreaks from state health departments.</li>
  <li>Co-leading a team of seven reporters in cleaning, wrangling and analyzing data.</li>
  <li>Writing code to look for patterns and outliers within states and identify outbreaks at Walmart stores and distribution centers across states.</li>
  <li>As the most senior reporter on the team, assisting team members in asking journalistic questions about the data, problem-solving in R and transforming data findings into language that the reporting team and readers could digest.</li>
  <li>Applying news judgment and journalism ethics to decisions about data from states that differed in their definitions of "workplace outbreak" across multiple variables, and some did not even use the term "outbreak."
</ul>
The <a href="https://apnews.com/article/coronavirus-pandemic-health-business-caf5e31d883a18deae6cd367a5ee8978">Associated Press</a> ran the story, and it was picked up by newspapers across the country, including The Washington Post.</p>

## 📊 Datawrapper & Flourish charts
<ul>
  <li><a href="https://www.kqed.org/mindshift/64582/how-can-the-community-school-model-support-newcomer-education">How Can the Community School Model Support Newcomer Education</a></li>
  <li><a href="https://www.kqed.org/news/12001154/valley-fever-rises-after-california-music-festival-experts-warn-of-climate-change-link">Valley Fever Rises After California Music Festival, Experts Warn of Climate</a></li>
  <li><a href="https://lynching.cnsmaryland.org/2021/11/10/black-women-lynchings/">History focuses on men, but Black women were lynched, too</a></li>
</ul>

## :school: Data-driven education reporting
<p>As an education beat reporter in Lancaster, Pennsylvania, I used data to connect public policy to people’s lives.</p>
<p>For example, as frustration over standardized testing surged nationwide, I obtained data from the state Department of Education about families opting children out of mandated assessments and <a href="https://drive.google.com/file/d/11LfYrtY3hN7CudxUktHKJmYL8ume31QM/view?usp=sharing">reported on a statewide spike in this practice</a>. I found that Lancaster County was a hotspot for opt-outs — a discovery that complemented my prior reporting on local parents organizing around this issue. After my story was published, other education reporters across Pennsylvania sought the same data I had obtained and localized the topic to their regions.</p>
<p>For that story and others on the ed beat, I conducted my analyses using self-taught methods in Google Sheets. I also experimented with building interactive maps via Fusion Tables and regularly created my own graphics using free web tools. I bring my love of learning and willingness to try new techniques to every setting.</p>

## :fountain_pen: About Me
<p>Kara Newhouse is an award-winning reporter who has worked at the Howard Center for Investigative Journalism, KQED MindShift and LNP/LancasterOnline, among other outlets. As an education reporter in Pennsylvania, she and another reporter uncovered financial mismanagement and persistent Sunshine Act violations in Lancaster County's wealthiest school district. Their reporting prompted hundreds of taxpayers to attend public meetings and demand changes to school district operations, including a more transparent superintendent search and the restoration of elementary art and music classes.</p>
<p>Newhouse holds a master’s degree in journalism with an emphasis on investigative and data journalism at the Philip Merrill College of Journalism at the University of Maryland. Her undergraduate degree is from American University, where she studied anthropology.</p>
