---
layout: default
---
# Theia
## Project Overview

> **Project Overview**

Our capstone project is a collaboration with Illumination Works LLC to develop a user interface (UI) for the Theia Autonomous Knowledge Generator (AKG).

The Theia AKG was conceived to address the challenges faced by many in recalling and analyzing data from diverse sources swiftly. In today's data-driven landscape, companies deal with extensive datasets ranging from images to spreadsheets, necessitating expert-level understanding to navigate through the information effectively. Theia aims to simplify this process by leveraging innovative technology to extract relevant metadata from various sources, analyze data relationships, and store the information in a graph database. This approach streamlines the search and analysis of interconnected data, facilitating rapid retrieval of pertinent information.

For instance, consider an article titled "Modern Agriculture in Brazil" and a spreadsheet containing fruit and vegetable prices. Theia can extract metadata from both datasets, identify commonalities such as their origin in Brazil in 2019, and establish a relationship between them in the graph database. Subsequently, a user searching for "Prices of bananas in Brazil in 2019" would receive both datasets as relevant results.

Following the initial data storage, Theia employs an "Active Metadata" approach to continuously update and analyze data changes. This ensures that users can track changes in data properties and relationships over time without losing existing information.

Our task from Illumination Works was to develop the UI for Theia, bridging the gap between users and the graph database. Unlike traditional database interfaces that rely on complex query languages like Cypher, Theia's UI enables users to interact with the graph database intuitively, without prior knowledge of database structure or query languages.

The UI development primarily focuses on frontend implementation, with some backend integration. We are tasked with displaying information from the graph database to users in a user-friendly manner. Wireframes provided at the project's outset serve as a blueprint for the UI's structure, ensuring a seamless user experience.

Backend development involves retrieving and querying data from the Neo4j graph database, converting database queries into user-friendly English sentences, and displaying the retrieved data to users. Each piece of data in the graph database is represented as a "node," containing properties and relationships that are essential for data retrieval and display.

In summary, our project aims to empower users with seamless access to complex data through an intuitive UI, bridging the gap between advanced data analytics and user experience.

## Project Sponsor

**Illumination Works**

![Illumination Works Logo](https://i.imgur.com/qEQsNwh.png)

Illumination Works is a digital transformation firm focused on meeting the needs of users. They possess extensive knowledge and experience in creating robust infrastructures for managing large-scale data, conducting data science, advanced analytics, and visualization. Their expertise lies in adapting to the evolving landscape of data, including various sources like behavioral, social, sensor, and spatial data, as well as advancements such as personal devices, cloud computing, and wireless connectivity. Illumination Works specializes in tailoring data solutions to handle diverse data types and analytical demands. They construct scalable data platforms capable of accommodating growing data volumes and supporting unconventional data sources, ensuring flexibility and efficiency.

# Team Members

**Ignacio Abrams**

![alt text](https://i.imgur.com/Rm9bUwq.jpeg)

Ignacio Abrams is a senior at the University of Dayton majoring in Computer Information Systems and minoring in Business Administration.

**Sam Jennes**
<div>
    <img src="https://i.imgur.com/Hzn0xSp.jpeg" alt="alt text" width="300" height="300">
</div>

Sam Jennes is a senior at the University of Dayton majoring in Computer Science. Contact him on [LinkedIn](https://www.linkedin.com/in/samuel-jennes/).

**Quinn Hanley**

<div>
    <img src="https://i.imgur.com/9KUxWiO.jpeg" width="240" height="360" />
</div>


Quinn Hanley is a senior at the University of Dayton majoring in Computer Information Systems and minoring in Communications. Contact him on [LinkedIn](https://www.linkedin.com/in/quinn-hanley-700708207/).

# Project Progress

## Month 1 Design

During the first month of Theia project, our focus was on translating wireframes provided by the Illumination Works Team into tangible designs while acquiring the necessary technological expertise. Given that the project was slated for React, a JavaScript library for UI development, we embarked on a learning journey. Despite having a clear end goal, our team initially grappled with the process of replicating the wireframes.

To bridge this knowledge gap, we commenced by completing the React tutorial to gain a solid foundation in the technology. With growing confidence in our React skills, we commenced the construction of key components, namely the Article box and the Tag component. The latter proved particularly crucial as it pervaded various facets of the UI, laying a foundational aspect for the project's progression.

These images below show our progress after month one with the bottom image being the wireframe that we were working towards.
<div>
    <img src="https://i.imgur.com/Aoxa5cx.png" width="720" height="480" style="border: 2px solid black;"/>
    <img src="https://i.imgur.com/ZNz5dAs.png" width="720" height="480" style="border: 2px solid black;"/>
    <img src="https://i.imgur.com/g30sH0h.png" width="720" height="480" style="border: 2px solid black;"/>
</div>


## Month 2 Development

In the second month of the Theia project, our focus shifted towards refining the wireframes to align our UI more closely with the initial designs. We made significant progress, particularly in implementing key features such as the "Save Article" button, accompanied by a sidebar to store saved articles. Additionally, we enhanced the functionality and aesthetics of the tag component, incorporating updated styling and enabling server-side filtering based on the selected tags.

Moreover, we introduced the article view feature, providing users with a dedicated space to view articles. These advancements represent a substantial step forward in realizing our vision for Theia's user interface, bringing us closer to delivering a polished and functional product.

### Demo Video

<video width="640" height="360" controls>
  <source src="video/video.mov" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Month 3 Development

In the third month of Theia project's development, our focus honed in on several key areas crucial for the platform's functionality. One major aspect was the refinement of page routing, particularly with the integration of the new searchView page. Leveraging Neo4j packages such as neo4j-driver and use-neo4j, we delved into database interaction, laying the groundwork for data retrieval from our Neo4j database.

Connecting our application to the Neo4j database was a pivotal step in our project's development journey. Through the use of Neo4j's powerful querying capabilities, we were able to seamlessly pull source data and tag names directly from the database, enriching the user experience.

With the assistance of Neo4j's neo4j-driver package, we established a secure and efficient connection to our database, enabling seamless data retrieval processes. By leveraging the use-neo4j package, we streamlined data fetching operations, ensuring optimal performance and responsiveness throughout the application.

Simultaneously, considerable efforts were dedicated to refining the user interface through meticulous CSS styling. Guided by the wireframes, we meticulously crafted the visual elements of Theia, ensuring alignment with the initial design concepts while also prioritizing responsiveness and usability. Key pages such as the searchView, browseView, and articleView underwent extensive styling enhancements, resulting in a cohesive and visually appealing user experience.

In summary, the third month of development marked a significant milestone in the evolution of Theia, wherein backend integration with Neo4j and frontend styling efforts converged to form a cohesive and polished product. By marrying technical functionality with aesthetic appeal, we laid a solid foundation for subsequent phases of development, setting the stage for further enhancements and feature expansions in the journey towards realizing Theia's full potential.

### Demo Video

<video width="640" height="360" controls>
  <source src="video/theia_demo.mp4">
</video>

# Technologies

![React Logo](https://i.imgur.com/h5KBdWg.png){:width="240px" height="220px"}

**React**

React is a JavaScript library primarily used for building user interfaces (UIs) in web applications. Developed by Facebook, React allows developers to create reusable UI components that efficiently update and render in response to data changes.


![Vite Logo](https://i.imgur.com/i7QXjdx.png){:width="240px" height="240px"}

**Vite**

Vite is a modern build tool for front-end development that aims to optimize the development experience by leveraging native ES Module support in modern browsers. It serves as a fast and efficient alternative to traditional bundlers like Webpack.

![Axios Logo](https://i.imgur.com/WM2EiDV.png){:width="400px" height="60px"}

**Axios**

Axios is a popular JavaScript library used for making HTTP requests from both the browser and Node.js environments. It provides a simple and elegant API for performing asynchronous operations, such as fetching data from a server or sending data to a server.

![Neo4j Logo](https://i.imgur.com/mrUIjk9.png){:width="417px" height="156.5px"}

**Neo4J**

Neo4j is a highly scalable and schema-free graph database management system. It is designed to store, manage, and query highly interconnected data, making it particularly suited for use cases involving complex relationships and network-like structures.

