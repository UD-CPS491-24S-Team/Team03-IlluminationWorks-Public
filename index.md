---
layout: default
---

# Project Overview

> The THEIA project tasks us with creating a UI for an application that is meant for searching and analyzing metadata. Theia aims to combine data processing, and Natural Language Processing. By combining these processes, Theia will facilitate extracting information from: documents, samples, system architectures, and even code conversion outputs so that they can be further processed and analyzed.

# Project Sponsor

**Illumination Works**

![alt text](https://i.imgur.com/qEQsNwh.png)

Illumination Works is a digital transformation firm focused on meeting the needs of users. They possess extensive knowledge and experience in creating robust infrastructures for managing large-scale data, conducting data science, advanced analytics, and visualization. Their expertise lies in adapting to the evolving landscape of data, including various sources like behavioral, social, sensor, and spatial data, as well as advancements such as personal devices, cloud computing, and wireless connectivity. Illumination Works specializes in tailoring data solutions to handle diverse data types and analytical demands. They construct scalable data platforms capable of accommodating growing data volumes and supporting unconventional data sources, ensuring flexibility and efficiency.

# Team Members

**Ignacio Abrams**

![alt text](https://i.imgur.com/Rm9bUwq.jpeg)

Ignacio Abrams is a senior at the university of dayton majoring in Computer Information Systems and minoring in Business Administration.

**Sam Jennes**

<img src="https://i.imgur.com/Hzn0xSp.jpeg" alt="alt text" width="300" height="300">

Sam Jennes is a senior at the University of Dayton majoring in Computer Science. Contact him on [LinkedIn](https://www.linkedin.com/in/samuel-jennes/).

**Quinn Hanley**<br>

<img src="https://i.imgur.com/9KUxWiO.jpeg" width="240" height="360" />

Quinn Hanley is a senior at the University of Dayton majoring in Computer Information Systems and minoring in Communcations. Contact him on [LinkedIn](https://www.linkedin.com/in/quinn-hanley-700708207/).


# Project Progress

## Month 1 Design
<div>
    <p1> During the first month of Theia project, our focus was on translating wireframes provided by the        Illumination Works Team into tangible designs while acquiring the necessary technological expertise. Given that the project was slated for React, a JavaScript library for UI development, we embarked on a learning journey. Despite having a clear end goal, our team initially grappled with the process of replicating the wireframes.<br>
    </p1><br> 
    <p3>
    To bridge this knowledge gap, we commenced by completing the React tutorial to gain a solid foundation in the technology. With growing confidence in our React skills, we commenced the construction of key components, namely the Article box and the Tag component. The latter proved particularly crucial as it pervaded various facets of the UI, laying a foundational aspect for the project's progression. 
    </p3>
    <p><br> These images below show our progress after month one with the bottom image being the wireframe that we were working towards.


<img src="https://i.imgur.com/Aoxa5cx.png" width="720" height="480" />

<img src="https://i.imgur.com/ZNz5dAs.png" width="720" height="480" />

<img src="https://i.imgur.com/g30sH0h.png" width="720" height="480" />


<div>
    <h2 id="month-2-development">Month 2 Development</h2>
    <p>In the second month of the Theia project, our focus shifted towards refining the wireframes to align our UI more closely with the initial designs. We made significant progress, particularly in implementing key features such as the "Save Article" button, accompanied by a sidebar to store saved articles. Additionally, we enhanced the functionality and aesthetics of the tag component, incorporating updated styling and enabling server-side filtering based on the selected tags.</p>
    <p>Moreover, we introduced the article view feature, providing users with a dedicated space to view articles. These advancements represent a substantial step forward in realizing our vision for Theia's user interface, bringing us closer to delivering a polished and functional product.</p>
    <h3 id="demo-video">Demo Video</h3>
    <video width="640" height="360" controls>
    <source src="video/video.mov" type="video/mp4">
    Your browser does not support the video tag.
    </video>
    <p></p>
    <h2 id="month-3-development">Month 3 Development</h2>
    <p>In the third month of Theia project's development, our focus honed in on several key areas crucial for the platform's functionality. One major aspect was the refinement of page routing, particularly with the integration of the new searchView page. Leveraging Neo4j packages such as neo4j-driver and use-neo4j, we delved into database interaction, laying the groundwork for data retrieval from our Neo4j database.</p>
    <p>Connecting our application to the Neo4j database was a pivotal step in our project's development journey. Through the use of Neo4j's powerful querying capabilities, we were able to seamlessly pull source data and tag names directly from the database, enriching the user experience.</p>
    <p>With the assistance of Neo4j's neo4j-driver package, we established a secure and efficient connection to our database, enabling seamless data retrieval processes. By leveraging the use-neo4j package, we streamlined data fetching operations, ensuring optimal performance and responsiveness throughout the application.</p>
    <p>Simultaneously, considerable efforts were dedicated to refining the user interface through meticulous CSS styling. Guided by the wireframes, we meticulously crafted the visual elements of Theia, ensuring alignment with the initial design concepts while also prioritizing responsiveness and usability. Key pages such as the searchView, browseView, and articleView underwent extensive styling enhancements, resulting in a cohesive and visually appealing user experience.</p>
    <p></p>
    <p>In summary, the third month of development marked a significant milestone in the evolution of Theia, wherein backend integration with Neo4j and frontend styling efforts converged to form a cohesive and polished product. By marrying technical functionality with aesthetic appeal, we laid a solid foundation for subsequent phases of development, setting the stage for further enhancements and feature expansions in the journey towards realizing Theia's full potential.</p>
    <h3 id="demo-video">Demo Video</h3>
    <video width="640" height="360" controls>
    <source src="video/theia_demo.mp4">
    </video>
    <p></p>
    <h2>Technologies</h2>
    <p></p>
    <img src="https://i.imgur.com/h5KBdWg.png" width="240" height="220" />
    <p></p>
    <strong>React</strong>
    <p>React is a JavaScript library primarily used for building user interfaces (UIs) in web applications. Developed by Facebook, React allows developers to create reusable UI components that efficiently update and render in response to data changes. It utilizes a declarative programming style, where developers describe how the UI should look at any given point in time, and React takes care of updating the DOM (Document Object Model) to match this desired state.</p>
    <img src="https://i.imgur.com/ygmHSeM.jpeg" width="240" height="240" />
    <p></p>
    <strong>Vite</strong>
    <p></p>
    <p>Vite is a modern build tool for front-end development that aims to optimize the development experience by leveraging native ES Module support in modern browsers. It serves as a fast and efficient alternative to traditional bundlers like Webpack.</p>
    <img src="https://i.imgur.com/7QdJ8LX.png" width="400"height="60"/>
    <p></p>
    <strong>Axios</strong>
    <p></p>
    <p>Axios is a popular JavaScript library used for making HTTP requests from both the browser and Node.js environments. It provides a simple and elegant API for performing asynchronous operations, such as fetching data from a server or sending data to a server.</p>
    <img src="https://i.imgur.com/mrUIjk9.png" width="417" height="156.5"/>
    <p></p>
    <strong>Neo4J</strong>
    <p></p>
    <p>Neo4j is a highly scalable and schema-free graph database management system. It is designed to store, manage, and query highly interconnected data, making it particularly suited for use cases involving complex relationships and network-like structures.</p>
</div>


