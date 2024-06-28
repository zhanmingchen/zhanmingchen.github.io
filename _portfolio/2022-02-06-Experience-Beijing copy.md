---
title: "Experience Beijing"
excerpt: "I developed a web-based application called Project A using Vue.js, eCharts, and websocket to visualize the social welfare data of the disabled population in China.<br/><img src='/images/Project-A-2.png' width='400'><br/>"
collection: portfolio
date: 2022-02-06
tags:
  - Human-centered computing
  - Human computer interaction (HCI)
  - Web-based interaction
  - Information visualization
---

## Demonstration Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/WQNR--tgMC4?si=mPNmPJcieOALsqQH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Project Description

Marking a new dawn for the Paralympic Winter Games, the Beijing 2022 set a brand-new benchmark for all future ones. The Paralympians’ astonishing efforts have not only attracted applauds and cheers from sports enthusiasts, but also awakened the world’s awareness of building a better future for people with disabilities.

Actually, what should not be neglected is that, in China, there are still numerous disabled people struggling against poverty. Meanwhile, discrimination against them in both workplace and daily life continues to occur.

Recently, an idea came into my mind that I can use data visualization to present data related to social welfare conditions of the disabled, thus providing assistance for decision makers in the government.

To start with, I developed a web-based application called “Project A” with “Vue.js” (a progressive framework used for building user interfaces), “eCharts” (an open-source JavaScript visualization library), and websocket.

<p align="center">
  <img src="/images/Project-A-1.png" alt="Project-A-1" width="600"/>
</p>

The letter “A” contains multiple meanings, such as accessibility, assistance, angel, etc. Just as the project name indicates, I hope my project could help improve social welfare conditions of the disabled.

Here is the interface of Project A, a dashboard of social welfare data of the disabled in China. All the data was extracted from the websites of National Bureau of Statistics and China Disabled Persons’ Federation. Running through a data analysis process, I displayed a large amount of data with various types of charts in six containers.

<p align="center">
  <img src="/images/Project-A-2.png" alt="Project-A-2" width="600"/>
</p>

The colors of the blocks on the map represent the total social welfare score of each province, which are shown in a descending order with blue, cyan, green, orange, and red. You can check the detailed scores on the vertical bar chart below, with the bars automatically scrolling to the left side. These two charts share the same color patterns and meanings to increase the consistency.

The scatters on the map refer to the latest news about social welfare conditions of the disabled people, which are divided into three types, positive ones, negative ones, and notifications from the local Disabled Persons’ Federation.

In the upper-left corner, the line chart illustrates the trends of the construction of service facilities, social welfare scores in four dimensions, and occupations of the disabled, from 2006 to 2020.

In the lower-left corner, the horizontal bar chart illustrates ratios of the population of disabled people to the total population of each province in China, which indicates the priorities of the welfare-related work among different regions.

The pie chart depicts three demographic factors related to the social welfare of the disabled, while the doughnut chart shows China’s objectives in improving the social welfare of people with disabilities.

When hovering the mouse on the elements in charts, we can find more detailed information. You can also hover or click the labels to get more details or filter the data. Moreover, each chart can be displayed in full screen separately and the color theme of the visualization can be switched.

The most fascinating part of the visualization is that when we display it for audience in a conference hall for example, we can synchronize the status when logging into this web page in the LAN environment. Meanwhile, data details can be freely viewed on different devices. This can maximize the effects of presentation, compared with slides.

I sincerely hope that it can facilitate the improvement of social welfare of the disabled in the near future. Feel free to contact me if you are also interested in this project.
