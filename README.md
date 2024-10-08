# Commodity-Export-Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiZmU2YWZhYTQtNjc1Mi00NzA5LWIxYTEtYWIxZDExODMxNjc3IiwidCI6ImZlZTNiOTE2LTAxYzEtNDk4Ny1hNjQ2LWUxOTM0MzJiOWVhYSIsImMiOjl9

<img width="705" alt="Commodity Export Dashboard" src="https://github.com/user-attachments/assets/d3fc4efc-807c-4753-b295-2d840e1b401f">

## Problem Statement

Objective: The aim of this project is to develop a Commodity Export Dashboard to analyze and visualize export data, enabling stakeholders to track key metrics such as export quantities, prices, top import/export countries, and key agents. The dashboard provides insights into trade trends, helping to identify profitable export partners and regions. This, in turn, assists businesses in optimizing trade strategies and decision-making processes.

Context: Export businesses need to constantly analyze their trading activities, understanding who their key partners are, what commodities are being traded, and how market prices and quantities fluctuate. Manually analyzing such vast datasets can be overwhelming, leading to missed opportunities and potential inefficiencies.

Problem: Manual data analysis across multiple countries, buyers, sellers, and commodities is complex and time-consuming. Exporters need to monitor trends in global markets, shifting prices, and the performance of different agents. Without a streamlined view, decision-making can be delayed, potentially impacting profits and trade efficiency.

# Solution

This Commodity Export Dashboard provides a solution by offering:

    - A consolidated view of export quantities and prices by country, seller, buyer, and agent, allowing for quick analysis of market trends.
    - Breakdown of commodity types (e.g., rice varieties, wheat), helping to identify the most exported goods.
    - Visualization of export price trends over time, allowing businesses to track fluctuations in market prices and adjust strategies accordingly.
    - Insights into top buyers and sellers, giving visibility into the partners who are contributing the most to the business.
    - Demographic and agent analysis, breaking down export quantities by agent, buyer, and seller, to identify top performers and areas for improvement.

# Main Page - Key features

    - Top Countries by Quantity and Price: Displays countries that have imported the most (quantity) and paid the most (price), offering a clear view of the most profitable and high-volume markets.
    - Top Buyers and Sellers by Quantity and Price: Highlights the biggest buyers and sellers in terms of export volume and the prices they’ve negotiated. This helps in identifying key players in the market and optimizing trade relations.
    - Commodity Types: A breakdown of the most commonly exported commodities (e.g., White Rice, Pakistan Rice, Brown Rice), offering insights into which goods are in highest demand.
    - Quantity and Price Over Time: Trend analysis showing how export volumes and prices have fluctuated over the selected period, helping to understand market dynamics.
    - Agent Performance: A breakdown of export activities by agents, including both quantity and price, to assess their contribution to the business.

# Data Sources & Tools

Data Sources: Export data collected over a specified period, covering multiple countries, commodities, and agents involved in the trade.

Tools Used:

- Power BI: For creating visualizations and designing the dashboard.
- Excel: For organizing and cleaning raw export data.
- DAX: For calculating key metrics such as average prices, quantities, and export trends in Power BI.

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard:

### [1] Top Countries by Quantity and Price Highlight Major Export Partners

    - Kenya leads in the export quantity of commodities, while Senegal leads in terms of price paid for exports.
    - This could indicate that while Kenya imports larger volumes, Senegal may be importing higher-value commodities.
           
### [2] Top Buyers Concentrated in a Few Key Players

    - The top buyers such as Padibreas N. and Perum Bulog je. purchase the most in terms of quantity (MT), but their price per unit seems to be lower.
    - Louis Dreyfus and Gmfc Commodit. balance both higher prices and significant quantities, reflecting a trend where larger buyers might be more price-sensitive or purchase more expensive goods.
  
  ### [3] Quantity and Price Over Time Reflects Seasonal Export Trends
  
    - The graph shows a peak in both Quantity (MT) and Price (PKR) in January followed by a decline in March.
    - This could suggest that exports tend to surge early in the year before tapering off, possibly due to seasonal demand fluctuations or economic factors.

 ### [4] Top Types of Exports Dominate by Specific Varieties
 
    - White Rice and Pakistan Rice are among the top types by quantity, reflecting high demand for these particular commodity types.
    - Brown Rice and IRRI-6 are also popular, showing that the demand is spread across multiple varieties, though some are more dominant.

 ### [5] Top Sellers Focus on Volume Rather Than High Prices

    - Sellers such as Gambisons Ltd. and Hassan Ali Rice lead the pack in terms of quantity (MT), indicating they are major players in terms of volume.
    - However, the price they command does not increase proportionately, suggesting that these companies may be focusing on volume rather than premium pricing.

 ### [6] Agents Play a Key Role in Quantity, But Few Command High Prices

    - Javaid Brothers and A.K. Shippers dominate in terms of the quantity exported, but their price per MT is significantly lower compared to other agents.
    - This could suggest that these agents are focusing on volume deals rather than niche or premium markets.

# Page 2 - Overview

<img width="707" alt="Commodity Export Dashboard P2" src="https://github.com/user-attachments/assets/786a709a-d83c-4298-82e3-1df6f46fd600">

Key Metrics:
    Total Quantity (MT): 1.87M metric tons
    Average Price (PKR): 33.43M PKR
    Total Exporters: 560
    Total Importers: 1,598
    Total Types (Commodities): 17

Visual Representation:
    The map below shows Export Destinations around the world, with regions labeled by continent (North America, South America, Europe, Africa, Asia, Australia). Each country/region is colored to represent different export areas.

# Page 3 - Detail

<img width="705" alt="Commodity Export Dashboard P3" src="https://github.com/user-attachments/assets/3271cf09-0a2d-466c-a509-62e33f0f2bd6">

Left Panel Filters:

    Exporter: Filter option for selecting specific exporters.
    Importer: Filter option for selecting specific importers.
    Type: Filter to choose different types of commodities.
    Month: Filter to display data by month.

Type-wise Breakdown:

    Various types of rice and their corresponding Average Price (PKR) and Total Quantity (MT) are listed, including:
    - 1121 Rice: Avg Price PKR 27,497M, Total Qty 90,871.02 MT
    - Basmati Rice: Avg Price PKR 22,824M, Total Qty 70,958.84 MT
    - IRRI-6: Avg Price PKR 16,097M, Total Qty 99,775.96 MT
    - White Rice: Avg Price PKR 152,850M, Total Qty 960,403.98 MT
    - And more varieties such as Broken Rice, Brown Rice, Parboiled Rice, and Steamed Rice.

Exporters and Monthly Breakdown:

    - A table on the right shows exporters like A.J. Niazi, A.R. International, A.B Enterprises, A.K. Enterprises, etc.
    - Each exporter has columns for February, January, and March export quantities (in metric tons).
    - Total quantity for each exporter across these months is displayed.

Grand Total:

    - The total exports across all exporters for each month:
    - February: 527,541.95 MT
    - January: 674,424.95 MT
    - March: 666,135.62 MT
    - Total quantity (MT): 1,868,102.51 MT

# Conlusion

The Commodity Export Dashboard effectively centralizes all critical export metrics into a user-friendly format, allowing businesses to quickly assess trading activities, track market trends, and identify key buyers and sellers. This enables data-driven decision-making, optimizing export strategies and improving profitability.
