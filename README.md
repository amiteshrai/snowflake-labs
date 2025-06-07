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

#### Snowflake Native Apps and Marketplace

Here are some resources I recommend to learn even more about data product delivery with Snowflake:

##### Secure data sharing
Introduction to Secure Data Sharing | Snowflake Documentation
 – A strong overview of secure data sharing in Snowflake. The "Data Sharing & Collaboration" parent section also contains more detail about other aspects of data sharing.

##### Streamlit in Snowflake
Live — Under the Hood: Streamlit in Snowflake
 – An interview and demo with the product manager that helps build Streamlit in Snowflake.

##### Streamlit in Snowflake: Build Data and AI Apps on the Data Cloud with Python
 – Blog post from the product manager that helps build Streamlit in Snowflake.

##### Snowflake Native Applications
Snowflake Native App Framework
 – An overview of the Snowflake Native App framework by the product manager that helps build the framework.

How a fictional ski resort helped me understand Snowflake Native Apps | by Gilberto Hernandez
 – An article that I wrote that helped me build the mental model to understand Snowflake Native Applications (this was much needed for me after a decade of building managed applications).

Snowflake Native Apps: A New Way to Put Data to Work | by Frédéric L'Anglais
 – A great overview of the benefits of Snowflake Native Apps and the types of applications that can be built.

##### Snowflake Developer Ecosystem
These concepts were not covered in this specific course (but will be in a future course), but if you're interested in learning more about how to build applications with Snowflake, consider the following resources:

Native Programmatic Interfaces | Snowflake Documentation
 – A list (with links to documentation) of all of the native programmatic interfaces that can be used to build applications with Snowflake.

Live - Developer Experience with APIs & Tooling
 – An interview with the product manager on developer experience on how to build applications with Snowflake, along with a demo by yours truly, dressed as an avocado.

#### Orchestration With Snowflake Tasks

Here are some resources I recommend to learn even more about orchestration with Snowflake:

Introduction to tasks | Snowflake Documentation
 – A great resource on many different aspects of Snowflake tasks. Consider the section "Triggered Tasks", which outlines new capabilities for tasks.

The definitive guide to using Snowflake Tasks
 – Another great resource written by a Snowflake Data Superhero.

- [Managing Snowflake tasks and task graphs with Python](https://docs.snowflake.com/en/developer-guide/snowflake-python-api/snowflake-python-managing-tasks)
 – How to use the Snowflake Python APIs to programmatically manage tasks.
