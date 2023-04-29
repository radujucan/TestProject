
<br/>
<p align="center">
  <h3 align="center">Software Testing Project</h3>

  <p align="center">
    Final Project for Software Testing Course - IT Informal School -
    <br/>
    <br/>
  </p>
</p>



## About The Project

This project involves testing the website desprecluj.ro using Exploratory and Performance Tests.


## Contents

* PDF presentation of the project
* An Excel Report with all the created and executed Test Cases 
* JSRPreprocessor file for JMeter 


### Description

Test Cases were documented in TestLink, and identified bugs were reported in Mantis. 
Performance Tests were executed using JMeter.


### Challenges 

One of the challenges faced in this project was creating a realistic simulation of user interaction with the web application - in order to create a Test Plan in JMeter.

*For example, a user navigating the map and searching for a certain area would require a set of HTTP Requests for all the tiles needed to compose the map. To address this challenge, a JSRPreprocessor file was created to compute the necessary parameters for obtaining three sets of map tiles that an ordinary user would need in his search of an area (defined by a random X and Y coordinate) that he would like to analyze.*
