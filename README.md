1. Dataset Selection  
Selected Dataset 
Dataset Name: SEC 10-K Financial Reports Dataset (from Data.gov / SEC EDGAR) 
Format: PDF → processed into CSV + JSON (interoperable ) 
Source Example: NVIDIA 10-K report  
Dataset fits the requirement 
 Contains 30+ features 
 Available / convertible to CSV, JSON 
 High-dimensional (text + numerical + categorical) 
 Real-world financial dataset (used in Fin Sight architecture) 
2. Dataset Description  
This dataset consists of annual financial reports (10-K filings) submitted by companies to the 
SEC. 
From the NVIDIA report: 
 Company details (name, location, industry)  
 Financial metrics (revenue, expenses, assets)  
 Risk factors (business risks, competition)  
 Management discussion (growth, strategy)  
 Market data (stock info, valuation)  
Example (from the file): 
 “Market value: $434.37 billion”  
 “Segments: Data Center, Gaming, Automotive”  

Feature Breakdown  
Structured Features (Numerical) 
 Revenue  
 Net Income  
 Operating Income  
 R&D Expenses  
 Market Capitalization  
 Total Assets  
 Liabilities  
 Cash Flow  
 Earnings Per Share  
 Growth %  
Categorical Features 
 Company Name  
 Industry  
 Sector  
 Business Segment  
 Filing Year  
 Region  
 Risk Category  
 Product Type  
Text Features 
 Risk Factors (long text)  
 Business Description  
 Management Discussion (MD&A)  
 Strategy Statements  
 Future Outlook
