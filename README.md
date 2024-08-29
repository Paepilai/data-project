# 1 Covid Data Analysis & Dashboard

### Covid Dashboard using Tableau
https://public.tableau.com/shared/NFQ9MW42Q?:display_count=n&:origin=viz_share_link

### Movie Correlation using Python (Pandas, NumPy, Seaborn, Matplotlib)
https://github.com/Paepilai/DataProject/blob/4b19b719ab171a83aa141148f92778437bfbca97/Movie%20Correlation%20Project%20v2.ipynb

# 2 CloudStream ETL

### Overview
This project demonstrates a complete data engineering pipeline that integrates data ingestion, transformation, and reporting using Azure services. It showcases the end-to-end process from extracting data from an on-premise SQL Server, processing it through Azure Data Factory, Azure Databricks, and finally visualizing it with Power BI. The solution is designed to be a robust and scalable architecture suitable for real-time data processing and analytics.

![copytable-pipeline]()

### Project Components
- **Data Source:** On-premise SQL Server Database
- **Data Ingestion:** Azure Data Factory
- **Data Transformation:** Azure Databricks (Bronze, Silver, Gold layers)
- **Data Storage:** Azure Data Lake Storage
- **Data Analysis & Reporting:** Azure Synapse Analytics, Power BI

### Tools & Technologies
- **Azure Data Factory:** Used for orchestrating and automating the data pipeline.
- **Azure Databricks:** Provides scalable data processing and transformation capabilities.
- **Azure Data Lake Storage:** Serves as the storage solution for raw and processed data.
- **Azure Synapse Analytics:** Enables advanced analytics and data warehousing capabilities.
- **Power BI:** Used for creating interactive and real-time visualizations.

### Key Features
- **Automated Data Pipeline:** Configured using Azure Data Factory to automatically trigger data ingestion and processing.
- **Multi-layer Data Transformation:** Utilizes Azure Databricks to transform data through Bronze, Silver, and Gold layers for optimized performance.
- **Real-Time Data Reporting:** Integrates with Power BI for up-to-date visual analytics and insights.
- **Scalable Architecture:** Designed to handle large volumes of data and provide scalable data processing.

### Setup & Execution
1. **Create a Trigger in Azure Data Factory:**
   - Configure a scheduled trigger to run the pipeline at specified intervals.
   - The pipeline performs data extraction, transformation, and loading operations.

2. **Add Data to On-Premise SQL Server:**
   - Insert new records into the source tables to test the pipeline.
   - Verify that data flows through the pipeline and is reflected in Power BI.

3. **Monitor Pipeline Execution:**
   - Use Azure Data Factory's monitoring tools to track the pipeline's progress.
   - Ensure data is processed and loaded correctly into the target systems.

4. **Update Visualizations:**
   - Refresh Power BI reports to verify that new data is accurately represented in the visuals.

### Learnings & Skills
- **ETL Processes:** Mastered end-to-end ETL (Extract, Transform, Load) processes using Azure tools.
- **Data Transformation:** Implemented multi-layer data transformation techniques with Azure Databricks.
- **Automation:** Configured automated triggers and schedules for data pipelines.
- **Data Integration:** Integrated data from various sources into a unified reporting solution with Power BI.

### Conclusion
This project highlights the ability to build a comprehensive data engineering pipeline using modern Azure technologies. It demonstrates practical skills in data ingestion, transformation, and visualization, providing a solid foundation for tackling real-world data engineering challenges.

### Future Enhancements
- **Advanced Analytics:** Integrate machine learning models for predictive analytics.
- **Data Quality Monitoring:** Implement monitoring and validation rules to ensure data accuracy.


