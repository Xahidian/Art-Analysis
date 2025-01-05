# Art-Analysis
A network analysis project exploring the influence and connections between artists, movements, institutions, and nationalities using Python libraries like NetworkX and Plotly
# Art Influence Network

## Author: Md Zahid  
## Student ID: 2302302  

---

### Project Description  
This project analyzes the flow of influence in the art world, focusing on connections between artists, movements, institutions, and nationalities. By creating a network graph using Python, we explore how influence spreads and identify the most impactful artists, movements, and communities. Interactive visualizations and centrality metrics help highlight key insights into the art world.

---

### Goals of the Project  
1. Identify the most influential artists.  
2. Determine the impact of key art movements.  
3. Explore the role of major institutions in shaping art.  
4. Analyze the representation of nationalities among artists.  
5. Detect closely connected groups of artists based on influence and style.

---

### Methodology  
- **Data Preparation**:  
  - Processed data from four datasets: artists, relationships, institutions, and schools.  
  - Handled missing values and analyzed key factors like nationality, total artworks, and institutional impact.  
  - Converted relationship data into a network-friendly format.  

- **Network Analysis**:  
  - Created a graph using `NetworkX` where:
    - **Nodes** represent artists, institutions, or schools.  
    - **Edges** represent connections or influences between them.  
  - Applied the following centrality measures to analyze influence:  
    - **Degree Centrality**: Identifies artists with the most connections.  
    - **Betweenness Centrality**: Finds artists acting as bridges between groups.  
    - **Closeness Centrality**: Highlights central artists with short paths to others.  
    - **Eigenvector Centrality**: Identifies artists connected to other important artists.  
  - Used **community detection** to group closely connected artists.

---

### Results and Insights  
1. **Most Influential Artists**:  
   - Artists like Pablo Picasso and Paul Cézanne emerged as the most connected and influential.  
2. **Influential Movements**:  
   - Movements such as Impressionism and Modernism formed distinct, highly connected groups.  
3. **Key Institutions**:  
   - Institutions like the École des Beaux-Arts played a major role in shaping influential artists.  
4. **National Representation**:  
   - The USA, France, and Italy were the most represented nationalities, reflecting their historical importance.  
5. **Communities of Artists**:  
   - Community detection revealed clusters of artists linked by style, geography, or institutional connections.

---

### Visualizations  
- **Top Influential Artists**: Interactive network views highlighting the most connected artists.  
- **Community Clusters**: Color-coded clusters showing groups of artists with shared characteristics.  
- **Edge Strengths**: Widths of edges indicating the strength of influence between nodes.

---

### Challenges and Solutions  
- **Visual Clutter**:  
  - Focused on the top nodes and used clear color coding to simplify complex graphs.  
- **Choosing Centrality Metrics**:  
  - Applied multiple metrics to provide a holistic view of influence and connections.

---

### Technologies Used  
- Python  
- NetworkX  
- Plotly  
- Pandas  

---

### Report  
A detailed report on the project is available [here](https://github.com/Xahidian/Art-Analysis/blob/main/Mini%20Project%203_Zahid.pdf). It provides an in-depth analysis of the dataset, methodology, and findings.

---

### Contact  
If you have any questions or would like to discuss the project further, feel free to reach out.  
Thank you for visiting my project!
