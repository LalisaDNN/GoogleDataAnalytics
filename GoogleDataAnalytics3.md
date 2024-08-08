# Course 3: Prepare Data for Exploration

This course focuses on the 2nd phase of the data analysis process: **Prepare**. This course includes:
- How data is generated 
- Different formats, types, and structures of data
- Analyze data for bias and credibility
- What "clean data" means
- Databases
- Extract your own data using spreadsheets and SQL
- The basics of data organization
- The process of protecting data

----
## Module 1: Data types and structures

How data is created and how to decide which data to use for analysis. This module also covers structured and unstructured data, data types and data formats.

### Collecting data
- **How data is generated:**
    - **Every digital interaction**, from sending texts to watching videos, generates data.
    - **Traditional methods** like surveys and interviews also contribute to the generation of data.
- **How data is collected:**
    - Interviews
    - Observations
    - Forms
    - Questionnaires
    - Surveys
    - Cookies (small files stored on computers that contain information about users)

### Data collection considerations
- How the data will be collected
- Choose data sources:
    - First-party data: Data collected directly by an individual or group using their own resources
    - Second-party data: Data collected by a group directly from its audience and then sold (collected by another group and purchased)
    - Third-party data: Data collected from outside sources who did not collect it directly (obtained from various sources).
    - It's important to consider the reliability and trustworthiness of each source.
- Decide what data to use
- How much data to collect:
    - Sample: A part of a population that is representative of the population.
- Select the right data type

### Select the right data

Data colleection planning:
- **Source Identification:** Determine whether to gather data directly (first-party) or acquire it from second-party or third-party providers.
- **Relevance to the problem:** Select datasets that directly address your business problem, ensuring they contain the necessary information for analysis.

Data collection logistics:
- **Sample Size Determination:** If collecting your own data, decide on an appropriate sample size, considering whether a random sample or a more focused approach is suitable.
- **Time Frame Considerations:** Establish the data collection duration, especially for trend analysis. If time is limited, leverage existing historical data.
![alt text](image-1.png)

### Discover data formats
- **Quantitative & Qualitative Data**:
    - Quantitative data can be measured and expressed numerically (like a movie's budget), while qualitative data describes qualities and characteristics (like a movie's title).
    - Quantitative data can be further classified as discrete (countable, with a limited number of values, like box office revenue) or continuous (measurable on a continuous scale, like a movie's runtime).
- **Other data types**:
    - Nominal data is qualitative data without a set order (like "yes" or "no" responses), while ordinal data has a set order (like ranking a movie on a scale of 1 to 5).
    - Internal data comes from within an organization (like a movie studio's own data), while external data comes from outside sources.
    - Structured data is organized in a specific format (like in a spreadsheet), while unstructured data is not (like audio or video files).

### Structured data vs unstructured data
- Structured data is information organized neatly into rows and columns, making it easily understandable by computers.
- Structured data is easily searchable and ready for analysis, visualizations, and generating insights.
- Unstructured data has no established rule about how to compare two different pieces of data. On the other hand, structured data conforms to organizational rules.
![alt text](image-2.png)

### Data modeling
- **Data modeling** is the process of creating diagrams that visually represent how data is organized and structured.  These visual representations are called **data models**. 
- Levels of data modeling:
    - **Conceptual data modeling** gives a high-level view of the data structure without technical details, such as how data interacts across an organization. 
    - **Logical data modeling** focuses on the technical details of a database such as relationships, attributes, and entities.
    - **Physical data modeling** depicts how a database operates. A physical data model defines all entities and attributes used. 
    ![alt text](image-3.png)

### Data types
- A data type tells you what kind of information a piece of data represents, which influences how it can be used.
- Example: Number, Text/String, Boolean.

### Tables
- Data tables, also known as tabular data, are structured in a simple row and column format, similar to a playlist, calendar, or email inbox.
- In data analytics, rows are often referred to as "records" and columns as "fields," although the terms "rows" and "columns" are more common in spreadsheets.

### Wide Data and Long Data
- **Wide data:** Wide data represents each subject in a single row, with multiple columns holding different attributes or time points, making it suitable for comparing attributes across subjects.
- **Long data:** Long data uses multiple rows to represent different observations for each subject, with each row dedicated to a specific attribute or time point. This format is ideal for analyzing trends over time or comparing subjects across multiple variables.

### Transforming data
- **Data transformation** is the process of changing the data’s format, structure, or values. 
- Data transformation usually involves:
    - Adding, copying, or replicating data 
    - Deleting fields or records 
    - Standardizing the names of variables
    - Renaming, moving, or combining columns in a database
    - Joining one set of data with another
    - Saving a file in a different format. For example, saving a spreadsheet as a comma separated values (.csv) file.
- Goals for data transformation:
    - Data organization: better organized data is easier to use
    - Data compatibility: different applications or systems can then use the same data
    - Data migration: data with matching formats can be moved from one system to another
    - Data merging: data with the same organization can be merged together
    - Data enhancement: data can be displayed with more detailed fields 
    - Data comparison: apples-to-apples comparisons of the data can then be made 

----
## Module 2: Data responsibility
### Unbiased and objective data
- **Bias** is a preference for or against something, influenced by personal experiences and beliefs. It can be conscious or subconscious, impacting our judgments and decisions.
- In data analysis, bias can skew results and lead to inaccurate conclusions, with potentially serious consequences in fields like healthcare and business.
- **Data bias:** A type of error that systematically skews results in a certain direction.
- **Unbiased sampling:** When a sample is representative of the population being measured.

### Types of bias
- **Sampling bias:** When a sample isn't representative of the population as a whole.
- **Observer bias (experimenter bias/ research bias)**: when individuals perceive and interpret data differently based on their subjective viewpoints.
- **Interpretation bias:** The tendency to always interpret ambiguous situations in a positive or negetive way. Interpretation bias arises from personal experiences and backgrounds, leading to differing interpretations of the same data.
- **Confirmation bias:** The tendency to research for or interpret information in a way that confirms pre-existing beliefs while disregarding contradictory evidence.
----
## Module 3: Database essentials

----
## Module 4: Organize and protect data

----
## Module 5: Engage in the data community