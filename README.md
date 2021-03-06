

<div id="top"></div>



![Screenshot_1](https://user-images.githubusercontent.com/82190357/137617782-5d8d6180-0c64-4ce5-9351-4eb1abfd946e.png)









#                                                               Fighting Fire with Data 


<a href="https://fightingfirewithdata.herokuapp.com/">FightingFireWithData WEB APP</a>
<b>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a></li>
      <ul>
        <li><a href="#Considerations">Considerations</a></li>
      </ul>
    </li>
    <li>
      <a href="#Process">Process</a>
      <ul>
        <li><a href="#ETL">ETL</a></li>
        <li><a href="#Visualizations">Visualizations</a></li>
        <li><a href="#Dashboard">Dashboard</a></li>
        <li><a href="#Deployment">Deployment</a></li>
      </ul>
    </li>
    <li><a href="#Data-Sources">Data Sources</a></li>
    <li><a href="#Tools">Tools</a></li>
    <li><a href="#Team">Team</a></li>
  </ol>
</details>

<br>

  

## About the Project

The Texas Parks and Wildlife's Fire Management Division has recently received an additional $10 million in state funding for wildfire prevention. The department has hired our firm to help make an informed decision about where to best invest their funds.

The goal of the project is to provide a consistent, comparable set of scientific results to be used as a foundation for wildfire mitigation and prevention planning across Texas. These results to help prioritize areas in the state where tactical analyses, community interaction and education, or mitigation treatments might be necessary to reduce risk from wildfires.

## Considerations
- Education and Marketing: Which audience is best suited to receive wildfire prevention education?
- Law Enforcement: Would an increase in penalties create positive change?
- Area/Regions of Concern: Which locations would benefit the most from the deployment of preventative measures?
- Prediction: Are there significant changes in the intensity, speed, or size of wildfires?

<p align="right">(<a href="#top">back to top</a>)</p>

<br>
<br>

![original (1)](https://user-images.githubusercontent.com/82190357/137281572-0335e82c-8b80-4629-ba77-f52850a4988b.jpg)

<br>
<br>

## Process
- ETL
- Visualizations
- Dashboard
- Deployment
<p align="right">(<a href="#top">back to top</a>)</p>

### ETL
One of the biggest challenges during  the ETL process for this project was working with a dataset that consisted of nearly 2 millions records. Pandas and  Jupyter Notebook were utilized to downscale the dataset and create dataframes that would eventually be used to create data tables in the postgres database. 

<p align="right">(<a href="#top">back to top</a>)</p>

### Visualizations
Through the use of data visualizations, large volumes of data can be readily transformed into comprehensible information to assess high risk areas and help prioritize preventive action. Javascript, Plotly, and Chart.js were used to create the interactive maps and charts that are used on the dashboard. 

<p align="right">(<a href="#top">back to top</a>)</p>

### Dashboard
The Dashboard was constructed with Bootstrap and HTML. Focus was delivering an application that would deliver required information through a visually appealing and  user-friendly interface. 

<p align="right">(<a href="#top">back to top</a>)</p>

### Deployment
A Python Flask App was written to facilitate the retrieval of data from the postgres database that users requested on the dashboard. It was then deployed using Heroku to create a fully functional Web App.    

<br>
<br>
<br>
<p align="right">(<a href="#top">back to top</a>)</p>

![Screenshot_1](https://user-images.githubusercontent.com/82190357/137281183-61a99571-7f9b-44b2-a7e6-bc53a48d4028.png)


<b>
<b>


![QuickDBD-export (2)](https://user-images.githubusercontent.com/82190357/137862833-0c838645-077a-4a9a-96a5-e5932e9285ed.jpg)


### Data Sources
- U.S. DEPARTMENT OF AGRICULTURE - RDS-2013-0009.4_SQLITE
- Drought.gov
- xxxx
<p align="right">(<a href="#top">back to top</a>)</p>

<br>

### Tools
- MongoDB Atlas/PostgreSQL/pgAdmin
- Python/Pandas/Flask
- Jupyter Notebook
- Javascript/Plotly/D3/Chart.js/[Bootstrap](https://getbootstrap.com)
  
  <p align="right">(<a href="#top">back to top</a>)</p>

<br>
<br>


![original (2)](https://user-images.githubusercontent.com/82190357/137583931-03c513ea-a48b-441b-be67-ff8462385408.jpg)



### Team
Dillon Carter ---|--- Felecia Helms ---|--- [Darrell Horich](https://github.com/D11eleven) ---|--- Taylor Lyons
  
  <p align="right">(<a href="#top">back to top</a>)</p>





