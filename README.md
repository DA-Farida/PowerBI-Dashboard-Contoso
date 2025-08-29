# PowerBI-Dashboard-Contoso
***

Contoso Corporation is a multinational company headquartered in Paris. The company is a manufacturing, sales, and support organization with over 100,000 products.
<Figure 1 shows the headquarters in Paris and the satellite offices and regional hubs on different continents./>

 
<img width="917" height="465" alt="image" src="https://github.com/user-attachments/assets/3a7ba4cb-eded-437d-9ee6-d6652c4e71a2" />

Figure 1: Contoso offices worldwide.

Over the years, the company has accumulated a large amount of transactional data covering sales, product performance, distribution channels (online vs. retail), and profitability by region. However, this data remained underutilized in guiding business strategy.


**<ins/>Project objective<ins/>**: to conduct an in-depth analysis of Contoso's sales and highlight key trends to guide strategic decisions. To do this, a set of interactive visualizations was built using Power BI.  
🔑 Insights and areas of analysis:</br>

📈**1.Sales Trends Analysis**  
Study of sales and margins over 7 years (2016–2023).  
Monitoring of overall revenue growth vs. set targets.  
Analysis of variations by channel (Retail vs. Online).  
🛒**Product Performance**  
Identification of dominant categories (e.g., Computers, Cell Phones, TV & Video).  
Benchmarking of major brands (Adventure Works, Contoso, Fabrikam, etc.).  
Analysis of average basket size and contribution by product.  
🌍**Regional & Customer Insights**  
Comparison of sales by country (US, Canada, Germany, UK, etc.).  
Breakdown by store type (physical vs. digital).  
Highlighting areas of growth vs. decline.  
💡**Profitability & Efficiency**
Tracking profits by region and product.  
Evaluating profit margins and identifying “Top vs. Flop Stores.”  
 

📌 Project deliverables  
-An interactive Power BI dashboard with multiple views:  
-Global Sales Overview  
-Online Sales vs Retail Performance  
-Regional Comparison (map & table with conditional formatting)  
-Top vs Flop Stores 

# The Data struture

The dataset consisted of seven tables including informations about customer, sales, product, stores, stores country,target,dates. One table was added after crossing and using DAX functions in order to have in depth informations for our future dashboards: we named it Table_Target_Par_Annee_Pays.
<img width="1262" height="503" alt="image" src="https://github.com/user-attachments/assets/87cb075d-a40d-4a8e-bf54-63ac8d5e77d9" />


# RESLUTS

The given data was already cleared and organized so our main job was enssentially to produce the differents dashboards and make sure to highlight the most useful insights. 
To do so, we drew on our knowledge of the Power BI tool and the DAX functions to link and structure the data that would enable us to achieve our objectives listed above. 

Following the dashboards which were produced during this work:

<img width="1216" height="661" alt="image" src="https://github.com/user-attachments/assets/6bf18436-f222-4faf-88fb-246cbb39d915" /></br>

<img width="1204" height="675" alt="image" src="https://github.com/user-attachments/assets/f27cc7f9-79a1-4fd8-9708-54dc93415958" /> 
# Sales Overview Dashboard
This dashboard provides a global view of Contoso’s sales performance.

**Key insights & recommendations:**

- Revenue reached **$21.2bn** with a **14% YoY increase** → Contoso is on a positive trend.  
  -->Recommendation: Reinforce growth drivers by investing more in performing categories (Computers).  

- **Computers dominate sales (~$10bn)**, far above Cell Phones and Home Appliances → Overdependence on one category.  
  -->Recommendation: Diversify revenue sources by boosting marketing and R&D efforts on Cell Phones and Home Appliances.  

- **Adventure Works leads with $4bn+**, while Fabrikam lags below $2bn → Clear brand performance gap.  
  -->Recommendation: Reallocate shelf space and ad spend towards top brands while redesigning the strategy for underperforming ones.  

- **US and Canada largely drive revenue**, with retail outperforming online → Regional and channel concentration.  
  -->Recommendation: Expand online penetration in Europe and emerging markets to balance channel dependency.
</br>

<img width="1198" height="667" alt="image" src="https://github.com/user-attachments/assets/aa5966db-bc46-4e08-b451-ac20cddf047c" /> 
# Region Performance Dashboard</br>
This dashboard provides a regional breakdown of Contoso’s sales and profitability.</br>

**Key insights & recommendations:** </br>

- **Germany** , **Netherlands** , and **US** show strongest growth **(+23–24%)** , while Canada, France, and Italy lag (~12%);</br>
-->Recommendation: Prioritize expansion and promotions in high-growth countries while diagnosing structural issues in low-growth ones.</br>

- **Profit** highly **concentrated in** US states like **Kansas** and **New Brunswick**.</br>
-->Recommendation: Use best-practice benchmarking from top-performing states to uplift weaker regions.</br>

- **Desktops** and **Laptops contribute the most to profit**, while smaller categories bring marginal returns.</br>
-->Recommendation: Maintain desktops/laptops as cash cows but explore high-margin niches (e.g., Smart Phones, Touch Screens) to prepare future growth.</br>
</br>

<img width="1210" height="670" alt="image" src="https://github.com/user-attachments/assets/d40c9af9-e751-4833-99bb-afbb56a2be38" /> 
# Top vs Flop Dashboard</br>
This dashboard focuses on identifying Contoso’s best and worst performing stores.</br>

**Key insights & recommendations:** </br>

-**Sales total $3.55bn** but **profit attainment** is **only 58% vs target** → Major profitability gap.</br>
--->Recommendation: Review cost structures and pricing strategies in underperforming stores.</br>

-**Online outperforms physical retail** in volume and margin contribution.</br>
-->Recommendation: Accelerate online investment (UX improvements, logistics optimization).</br>

-**Top stores (Northwest Territories, Nunavut) generate up to $0.48bn**, while flops stagnate under $0.3bn.</br>
-->Recommendation: Close or restructure consistently underperforming locations, and replicate success drivers from top stores.</br>
</br>

<img width="1210" height="670" alt="image" src="https://github.com/user-attachments/assets/6d2fffa6-6d3d-4fc0-b2cc-1958b8090467" />
# Performances Dashboard</br>
This dashboard provides a performance snapshot by country, store type, manager, and product category.  

**Key insights & recommendations:**  

- **Revenue reached €3.55bn but fell -27.8% YoY**, despite being **+10% above target**.  
-->Recommendation: Investigate the structural causes of the YoY decline (market slowdown, pricing, churn) while maintaining the winning strategies that enabled target overperformance.  

- **Australia (+135%) and Online (+128%) exceed targets strongly**, while **France lags at 82.3%** and **US at 85.7%**.  
-->Recommendation: Replicate successful online campaigns in underperforming regions; conduct root-cause analysis in France to address persistent underperformance.  

- **North America generates €2.2bn sales vs only €0.6bn in Europe and €0.36bn in Australia** → clear regional imbalance.  
  -->Recommendation: Rebalance commercial investments and adapt product portfolios for Europe to unlock growth potential.  

- **Ivana drives €2.16bn sales, outperforming all other managers combined**.  
 -->Recommendation: Benchmark Ivana’s practices and roll them out as best practices across other sales managers.  

- **Computers dominate (€1.26bn), followed by Home Appliances (€0.61bn)**, while categories like Cameras, Audio and Gaming remain marginal.  
-->Recommendation: Keep Computers as a core driver, but design growth initiatives for mid-tier categories to avoid overreliance.

  # CONCLUSION

  This project explored **Contoso’s commercial performance** through a series of interactive dashboards built with Power BI.  
The analysis covered multiple dimensions: sales trends, regional performance, top vs flop stores, product categories, customer segments, and profitability.  

**Key contributions of this work:**  
- Provided a **clear, data-driven overview** of sales and profit evolution over 7 years.  
- Identified **growth drivers** (Computers category, Online channel, US market) and **weak points** (France, Retail underperformance, brand gaps).  
- Designed actionable recommendations to **diversify revenue streams**, **optimize underperforming regions**, and **leverage best practices** from top managers and products.  

Beyond descriptive analytics, this project emphasizes the importance of **data storytelling**: turning raw numbers into **business insights** and **strategic decisions**.  

🚀 **Next steps** could include:  
- Integrating **predictive analytics** (forecasting sales & churn).  
- Exploring **customer segmentation & cohort analysis** to refine marketing strategies.  
- Automating refresh pipelines for a fully operational BI system. 










  
