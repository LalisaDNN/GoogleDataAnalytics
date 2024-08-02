# Course 2: Ask Questions to Make Data-Driven Decisions
----
## Module 1
Data analysts are constantly asking questions in order to find solutions and identify business potential. In this part of the course, you’ll learn about effective questioning techniques that will help guide your analysis.
### Problem-solving and effective questioning
The six data analysis phases:
1. **Ask:**
> -  Define the problem
> - Understand the expectations
> - Focus on the problem, avoid distractions
> - Collaborate and communicate with stakeholders
> - See the whole context
2. **Prepare**: Decide what data to collect in order to answer the questions and how to oragnize it.
> - What metrics to measure
> - Locate data in the DB
> - Create security measures to protect data
3. **Process**: Clean data to get rid of errors, inaccuracies, inconsistencies.
> - Using spreadsheet functions to find incorrectly entered data
> - Using SQL functions to check for extra spaces
> - Removing repeated entries
> - Checking for bias in data
4. **Analyze**: Think analytically about the data.
> - Perform calculations
> - Combine data from multiple sources
> - Create tables with the results
> - What the story is the data telling?
> - How will data help solve the problem?
5. **Share**: Using tools to create visualization/summarization for the data
> - Make better and more informed decisions
> - Communication the findings
6. **Act**: 
> - Recognize current problem or situation
> - Organize available information
> - Reveal gaps and opportunities
> - Identify the opinions
### Common problem types with data
1. **Making predictions**: Using data to make predictions about the future.
2. **Categorizing things**: Organizing information into different groups based on shared traits.
3. **Spotting something unusual**: Identifying data that deviates from the norm.
4. **Identifying themes**: Grouping categorized informations into broader concepts.
5. **Discovering connections**: Finding shared challenges among different groups.
6. **Finding patterns**: Using historical data to identify recurring trends.
### Ask effective questions
Using the SMART framework: Specific, Measurable, Action-oriented, Relevant, Time-bound.
- **Specific**: The question should be focused on a single topic or a few closely related ideas. Avoid being overly broad or general.
- **Measurable**: Frame your question in a way that allows for quantification and assessment.
- **Action-oriented**: The goal is to formulate questions that encourage change and problem-solving.
- **Relevant**: Ensure your questions directly relate to the problem you're trying to solve. Each question should move you closer to a solution.
- **Time-bound**: Define a specific time frame for your question. This helps narrow down the scope and focus on the most relevant data. 
### Avoid asking these questions:
- **Leading questions**: questions that only have a particular response.
- **Closed-ended questions**: questions that ask for a one-word or brief response only.
- **Vague questions**: questions that aren't specific or don't provide context.
### Common topics for asking questions
- Objectives
- Audience
- Time
- Resources
- Security
----
## Module 2
### The power of data
- **Data-driven decisions:** use facts and figures to guide strategy, *relying heavily* on the available data's quality and quantity. While very effective with sufficient data, this approach can be *limited by biases or an overreliance on historical data*. 
- **Data-inspired decisions:** incorporate data analysis but also consider a wider context, including qualitative insights, feelings, experiences, and other less measurable factors.
### Types of data
- **Quantitative data**: Quantitative data deals with *measurable numerical facts*, answering "what," "how many," and "how often" questions. Think of it as the hard numbers behind a trend, collected through tools like surveys and polls.
- **Qualitative data**: Qualitative data dives into the "why" behind the numbers, exploring *qualities, characteristics, and opinions* that can't be easily quantified. It can be gathered through methods such as focus groups and interviews.
### Data visualization tools
- **Reports**: Reports present static data, offering a historical snapshot, often used for information delivered periodically.
> Pros:
> - High-level historical data
> - Easy to design 
> - Pre-cleaned and sorted data

> Cons:
> - Continual maintenance
> - Less visually appealing
> - Static
- **Dashboards**: Dashboards monitor live data, providing a dynamic view and allowing for interactive exploration through filters, making them suitable for tracking real-time trends.
> Pros:
> - Dynamic, automatic and interactive
> - More stakeholder access
> - Low maintenance

> Cons:
> - Labor-intensive design
> - Can be confusing
> - Potentially uncleaned data

### Metrics
- A metric is a quantifiable measurement used to track a specific data point, like revenue per salesperson. (ROI - Return on Investment, Customer retention rate, etc)
- **Metric goal**: A measurable goal set by a company and evaluated using metrics.

### Connect the data
- **Mathematical thinking**: The ability to break down problems logically to uncover patterns within data. This helps determine the best analysis tools by enabling a clear understanding of the problem's components.

|**Small Data**|**Big Data**|
|--------|---------|
|Describes a dataset made up of specific metrics over a short, well-defined time period|Describes large, less-specific datasets that cover a long time period|
|Usually organized and analyzed in spreadsheets|Usually kept in a database and queried|
|Likely to be used by small and midsize businesses|Likely to be used by large organizations|
|Simple to collect, store, manage, sort, and visually represent|Takes a lot of effort to collect, store, manage, sort, and visually represent|
|Usually already a manageable size for analysis|Usually needs to be broken into smaller pieces in order to be organized and analyzed effectively for decision-making|
- **Four V's of Big Data**: 
    - **Volume**: The amount of data
    - **Variety**: The different kinds of data
    - **Velocity**: How fast the data can be processed
    - **Veracity**: The quality and reliability of the data
----
## Module 3
### Spreadsheets and data life cycle
- **Plan:** Establish *clear organizational standards* for your spreadsheets to ensure consistency, improve communication, and boost efficiency. This includes *formatting, headings, color schemes, and data order*.
- **Capture:** Connect your spreadsheets to *external data sources*, such as online surveys or databases, to automatically *capture and update data,* ensuring accuracy and relevance.
- **Manage:** Utilize spreadsheets to *manage various data types* effectively. This includes *storing, organizing, filtering, updating, and controlling access and security*.
- **Analyze:** Leverage *spreadsheet analysis tools* like formulas and pivot tables to *gain insights from your data, create reports, and make informed decisions*.
- **Archive:** Archive spreadsheets containing data you *don't frequently use but may need to reference in the future.* This is particularly useful for *preserving historical data.*
- **Destroy:** Destroy spreadsheets that are no longer needed, have been replaced by backups, or require disposal due to legal or security reasons. Remember to follow proper data destruction procedures.

### Fomulas in Spreadsheets
- In spreadsheets, formulas begin with an equal sign (=) followed by cell references, values, and operators.

### Spreadsheet errors
|Error|Description|Example|
|--------|---------|---------|
|**#DIV/0!**|A formula is trying to divide a value in a cell by 0 (or an empty cell with no value)|=B2/B3, when the cell B3 contains the value 0|
|**#ERROR!**|(Google Sheets only)  Something can’t be interpreted as it has been input. This is also known as a parsing error.|=COUNT(B1:D1 C1:C10) is invalid because the cell ranges aren't separated by a comma|
|**#N/A**|A fomula can't find the data|The cell being referenced can't be found|
|**#NAME?**|The name of a fomula or function used isn't recognized|The name of a function is misspelled.|
|**#NUM!**|The spreadsheet can't perform a formula calculation bacause a cell has an invalid numeric value|=DATEDIF(A4, B4, "M") is unable to calculate the number of months between two dates because the date in cell A4 falls after the date in cell B4|
|**#REF!**|A formaula is referencing a cell that isn't valid|A cell used in a formula was in a column that was deleted|
|**#VALUE!**|A general error indicating a problem with a formula or with referenced cells|There could be problems with spaces or text, or with referenced cells in a formula; you may have additional work to find the source of the problem.|