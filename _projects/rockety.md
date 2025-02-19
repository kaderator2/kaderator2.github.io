---
layout: page
title: Rockety
description: A sophisticated web application for analyzing Rocket League replay files, developed at the University of Arizona. This tool helps players and teams improve their gameplay through detailed statistical analysis and visualization of match data.
img: assets/img/rocket/analysispage.png
importance: 1
category: work
related_publications:
---

### Technologies Used

**Languages:**

- TypeScript
- JavaScript
- HTML/CSS

**Libraries & Tools:**

- React.js
- Node.js
- Express.js
- MongoDB
- Docker
- JWT Authentication

Before diving into development, I collaborated with my supervisor at the University of Arizona's Department of Esports to create a comprehensive design document. This planning phase was crucial in defining the project's scope and technical requirements, ensuring it would meet the department's needs for player development and statistical analysis.

Rockety is a web-based application that tackles a common challenge in competitive Rocket League: making sense of replay data. While the game provides replay files, extracting meaningful insights from them has always been a challenge for teams and players looking to improve their performance. The project serves multiple purposes: enhancing the Rocket League community's engagement through detailed replay analysis, providing essential statistics for the university's esports program, and helping casters stay updated with player performance data.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rocket/welcomepage.png" title="Welcome Page" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The welcoming landing page introduces users to Rockety's capabilities.
</div>

The project leverages a carefully selected tech stack outlined in our initial design phase: TypeScript and React power the frontend, while Node.js/Express handle the backend operations. MongoDB was chosen for its flexible schema, perfect for storing the variable and complex data from game replays. One of the most interesting technical challenges was parsing the binary replay files efficiently while maintaining a smooth user experience. The application implements secure user authentication with OAuth 2.0 and JWT, robust file upload handling, and real-time data processing through message brokers like RabbitMQ or Redis for optimal performance.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rocket/analysispage.png" title="Analysis Page" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The analysis page provides detailed insights into game statistics and player performance.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rocket/accountpage.png" title="Account Management" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Users can manage their profiles and access their uploaded replays.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rocket/replayupload.png" title="Replay Upload" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The intuitive upload interface makes it easy for users to submit their replay files for analysis.
</div>

### Technical Highlights & Future Improvements

- Implemented secure file upload and processing pipeline using AWS infrastructure
- Developed custom replay file parser with Python for efficient data extraction
- Created interactive data visualizations using Chart.js
- Established CI/CD pipeline with GitHub Actions
- Implemented containerization with Docker for consistent deployment
- Designed for scalability with message broker architecture

Fun fact you could add: "The project started as a simple replay parser but evolved into a full-fledged analysis platform after seeing how excited the Rocket League community was about the initial prototype!"

### Links

- [GitHub Repository](link-to-your-repo)
- [Live Demo](link-to-demo)
