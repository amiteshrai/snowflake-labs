# Snowflake Practice Labs

Practice ground for features offered by Snowflake

## Features

### Snowflake CLI

#### Batch Ingestion Using COPY INTO Command:
- Define target table
- Define a file format
- Define an external stage
- Use the COPY INTO command to load data from the external stage into the target table

#### Additional Resources On Batch Ingestion:

- [Overview of data loading | Snowflake Documentation](https://docs.snowflake.com/en/user-guide/data-load-overview)
  - Unless you're interested, feel free to skip any sections that refer to continuous or streaming data loading.

- [Data loading considerations | Snowflake Documentation](https://docs.snowflake.com/en/user-guide/data-load-considerations)
  - I recommend reading all of the topics within this "Considerations" section. Feel free to skip any sections that refer to continuous or streaming data loading.

- [Snowflake Batch Data Loading | Best Practices in 2024](https://select.dev/posts/snowflake-batch-loading)
  - Outside of Snowflake's official documentation, I highly recommend this resource.

- [Deep dive into the internals of Snowflake Virtual Warehouses | by Samartha Chandrashekar](https://medium.com/snowflake/deep-dive-into-the-internals-of-snowflake-virtual-warehouses-d6d9676127d2)
  - An incredible, technical deep dive on Snowflake's compute resources: virtual warehouses. Highly recommended. This resource will really level you up.

- [Summary of data loading features | Snowflake Documentation](https://docs.snowflake.com/en/user-guide/intro-summary-loading)
  - Technical reference of the supported features for using the COPY INTO command. Handy information that you should keep in mind when using this command.


#### Get Deeper Insights About:

1. Snowflake Streams
    - [Streaming with Snowflake](https://www.youtube.com/watch?v=zH5umveQW_c) – An excellent technical demo directly from the product manager who helped build Dynamic Tables.
2. Snowflake Dynamic Tables
    - [Best practices for dynamic tables | Snowflake Documentation](https://docs.snowflake.com/en/user-guide/dynamic-tables-best-practices)
    - [Getting Started with Snowflake Dynamic Tables](https://quickstarts.snowflake.com/guide/getting_started_with_dynamic_tables/) – (Optional) For more hands-on practice with Snowflake Dynamic Tables.
3. Snowpark APIs
    - [Query Data in Snowflake](https://docs.snowflake.com/en/guides-overview-queries) – You don't need to read everything in this section, but it does a good job of laying out common ways of querying data in Snowflake.
    - [Snowpark for Python | Snowflake Tutorial](https://youtu.be/udcFnIvXFnE?si=prrOJZd41LO3ITvh) by Christopher Marland, Snowflake Data Superhero.
        - In the video, Christopher uses Jupyter Notebooks, but you can also use Snowflake Notebooks.
    - [Snowpark Developer Guide for Python | Snowflake Documentation](https://docs.snowflake.com/en/developer-guide/snowpark/python/index) – Everything under this section is great. The "Using DataFrames" section is especially helpful and relevant. Browse the Java or Scala sections if those are your preferred programming languages.
    - [Using other Python Packages in Snowpark | by Jeff Hollan | Snowflake Builders Blog](https://medium.com/snowflake/using-other-python-packages-in-snowpark-a6fd75e4b23a) – How to bring in Python packages into a Snowpark development environment.
4. Stored Procedures and how to automate them
