# Project Proposal

 
### **Client:** <br>

I will be presenting my findings to the two sole owner/operators of a local wedding consignment shop. <br>

***

### **Question/Need:**<br>

The owners have not analyzed or looked at any analytics for their shop before. We have started with the question: *What products sell more? How do the categories of products contribute to their total profits?*<br>

The goal is two-fold. First, we aim to introduce the owners to analytics. This will hopefully inspire them to find ways to leverage their data more in the future. Second, I hope to provide the owners insights on their inventory management. These insights will inform their decision making on terms and markdowns.
<br>

***

### **Data Description:**<br>

The data I will be using is inventory data generated from the software the shop uses. An individual inventory unit will be a single item listing with description, date received, date sold.<br>
***

### **Solution Path:**<br>

- Dashboard
  - Static with data provided
  - Reusable so the client can connect current data
- Model
  - A regression model estimating how much a given item will sell for.
  - A regression model estimating time to tell for a given item.
<!-- - Classification Model (Logistic Regression)
  - Will a cosignor forfeit? -->
<!-- - Comparison of cosignors
  - Bar Chart
- Cosignors grouped 
  - Bar Chart
  - Clustering -->

**A Dashboard** is the most probable solution path. The client does not have a need for advanced methods and will not have large amounts of data to make a robust model. The owner/operators will need a product that they can easily consume and interpret as needed.
<br>

***

### **Criteria for Success:**<br>

We will be able to see what categories of items produce the most profits. 
<br>

The less inventory will need to be donated.
***

### **Assumptions and Risks:**<br>

We are assuming the store will have enough historical data to train a model. If a model were to be used in a business impactful way, it could have a large impact on the business (good or bad).
<br>

We are assuming the data is consistent. Changing trends or market needs may make simple product comparisons more difficult. 

Covid could have affected data.

We are using private data therefore privacy will be a concern.
<br>
***

### **Tools:**<br>
The data will be stored and explored in Sheets. 

Python may be used for joining data or scraping external dta.

Visualizations and dashboards will be developed with Tableau. (*Will Data Studio be an acceptable alternative to keep client data private?*)
<br>
***

### **MVP Goal:**<br>

An MVP for this project would consist of descriptive statistics for the stores different product categories and a bar chart to reflect profits per category.

