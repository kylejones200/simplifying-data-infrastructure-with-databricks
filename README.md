# Simplifying Data Infrastructure with Databricks

Published: 2025-08-18
Medium: [https://medium.com/@kyle-t-jones/simplifying-data-infrastructure-with-databricks-8322ca0dc090](https://medium.com/@kyle-t-jones/simplifying-data-infrastructure-with-databricks-8322ca0dc090)

## Business context

Most enterprises live with fragmented data infrastructure. They rely on multiple ingestion tools, orchestration layers, query engines, and governance solutions stitched together in ways that create more friction than value. The "as-is" environment --- illustrates this problem clearly. Data moves through Kafka, Fivetran, EMR, Athena, MySQL, TensorFlow, and a mix of AWS services like Glue, IAM, Lambda, and Airflow. Each tool plays its part, but together they form a maze of dependencies. Teams spend more time keeping the system alive than using it. Data scientists and engineers are left fighting the plumbing instead of building models, creating insights, or delivering applications.

- Ingestion relies on Kafka, Fivetran, and custom connectors. - Transformation is handled by Amazon EMR and Athena. - Querying spans MySQL, Athena, and TensorFlow pipelines. - Governance uses AWS Glue and IAM. - Orchestration requires Airflow and Lambda triggers.

Each tool solves part of the problem, but the result is a complex system with multiple points of failure. Data scientists and engineers spend more time stitching together infrastructure than building models or insights. Worse, serving models and connecting them to business applications is often left undefined or ad hoc.



## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).