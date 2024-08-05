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

### Module conclusion

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

### Module conclusion

----
## Module 3
### Spreadsheets and data life cycle
- **Plan:** Establish *clear organizational standards* for your spreadsheets to ensure consistency, improve communication, and boost efficiency. This includes *formatting, headings, color schemes, and data order*.
- **Capture:** Connect your spreadsheets to *external data sources*, such as online surveys or databases, to automatically *capture and update data,* ensuring accuracy and relevance.
- **Manage:** Utilize spreadsheets to *manage various data types* effectively. This includes *storing, organizing, filtering, updating, and controlling access and security*.
- **Analyze:** Leverage *spreadsheet analysis tools* like formulas and pivot tables to *gain insights from your data, create reports, and make informed decisions*.
- **Archive:** Archive spreadsheets containing data you *don't frequently use but may need to reference in the future.* This is particularly useful for *preserving historical data.*
- **Destroy:** Destroy spreadsheets that are no longer needed, have been replaced by backups, or require disposal due to legal or security reasons. Remember to follow proper data destruction procedures.

### Fomulas and Functions in Spreadsheets
- In spreadsheets, formulas and functions begin with an equal sign (=) followed by cell references, values, and operators.
- Differences between formulas and functions:
    - A formula is a set of instructions used to perform a calculation using the data in a spreadsheet.
    - A function is a preset command that automatically performs a specific process or task using the data in a spreadsheet.

### Spreadsheet errors
|Error|Description|Example|
|--------|---------|---------|
|**#DIV/0!**|A formula is trying to divide a value in a cell by 0 (or an empty cell with no value)|=B2/B3, when the cell B3 contains the value 0|
|**#ERROR!**|(Google Sheets only)  Something can’t be interpreted as it has been input. This is also known as a parsing error.|=COUNT(B1:D1 C1:C10) is invalid because the cell ranges aren't separated by a comma|
|**#N/A**|A fomula can't find the data|The cell being referenced can't be found|
|**#NAME?**|The name of a fomula or function used isn't recognized|The name of a function is misspelled.|
|**#NUM!**|The spreadsheet can't perform a formula calculation bacause a cell has an invalid numeric value|=DATEDIF(A4, B4, "M") is unable to calculate the number of months between two dates because the date in cell A4 falls after the date in cell B4|
|**#REF!**|A formula is referencing a cell that isn't valid|A cell used in a formula was in a column that was deleted|
|**#VALUE!**|A general error indicating a problem with a formula or with referenced cells|There could be problems with spaces or text, or with referenced cells in a formula; you may have additional work to find the source of the problem.|

### Structured thinking
- **Definition:** The process of recognizing the current problem or situation, organizing available information, revealing gaps and opportunities, and identifying the opinions.
- Helps save time and effort by providing a clear understanding of the problem to be solved.
- Starts with defining the **problem domain** and laying out all requirements and hypotheses.
- **Problem domain**: The specific area of analysis that encompasses every activity affecting or effected by the problem.

### Scope of work (SOW)
- **Definition:** An agreed-upon outline of the work you're going to perform on a project.
- A scope of work is *project-based* and *sets the expectations and boundaries of a project*. 
- For data analysts, it includes *data preparation, validation, analysis, and reporting*.
- **Usually, projects don’t start until an SOW is approved**

### Why SOW?
- **The point of data analysis projects is to complete business tasks that are useful to the stakeholders**. Creating an SOW helps to **make sure that everyone involved**, from analysts and engineers to managers and stakeholders, **shares the understanding** of what those business goals are, and the **plan for accomplishing** them.
- An SOW helps **formalize all the questions** (to clarify requirements, goals, data sources, stakeholders, and any other relevant info) by **recording all the answers and details.**
- SOWs also contain information specific to **what is and isn’t considered part of the project**. 

[**Scope Of Work Template**](https://docs.google.com/document/d/1zqfGwpjZyPAyERNPXNfIUM78YuBxYYj0atIE6_YopLA/template/preview?resourcekey=0-o9cjeaxYBBm7ZyYe4bpImw)

### A good SOW includes:
- **Deliverables:** **What work** is being done, and **what things** are being created as a result of this project? **When** the project is complete, **what are you expected to deliver** to the stakeholders? **Be specific** here. Will you collect data for this project? How much, or for how long?
- **Milestones:** This is closely related to your timeline. What are the **major milestones for progress** in your project? How do you know when a given part of the project **is considered complete**? 
- **Timeline:** Your timeline will be closely tied to the milestones you create for your project. The timeline is a way of **mapping expectations** for **how long** each step of the process should take. The timeline should be specific enough to help all involved decide if a project is on schedule. When will the deliverables be completed? How long do you expect the project will take to complete? If all goes as planned, how long do you expect each component of the project will take? When can we expect to reach each milestone?
- **Reports:** Good SOWs also set boundaries for how and when you’ll **give status updates** to stakeholders. How will you **communicate progress** with stakeholders and sponsors, and how often? Will progress be reported weekly? Monthly? When milestones are completed? What information will status reports contain?

[**An example of a good SOW**](https://docs.google.com/document/d/16x-E04Nr48Ww1Nlxwa0PNOXyaytKbVCxrF5yRJy6Y70/template/preview?resourcekey=0-X1a531fuUVbtlNKdIA11dQ)

### The importance of context
- **Context** in data analytics is the condition and circumstances that surround and give meaning to the data.
-  **Context can turn raw data into meaningful information.** It is very important for data analysts to contextualize the data.
- To give meanings to the data or contextualize the data, these aspects need to be identified:
    - **Who**: The person or organization that created, collected, and/or funded the data collection
    - **What**: The things in the world that data could have an impact on
    - **Where**: The origin of the data
    - **When**: The time when the data was created or collected
    - **Why**: The motivation behind the creation or collection
    - **How**: The method used to create or collect it


### Module conclusion

The module concludes with the following:
- Spreadsheet:
    - The module starts with how spreadsheets help in each phase of data life cycle.
    - This module also introduces some popular formulas and functions used in spreadsheets.
    - Then, some common errors and their fixes are addressed

- Structured thinking and scope of work (SOW):
    - This module introduces structured thinking and SOW. How they help in understanding, clarifying and gaining insights from the data.
----
## Module 4
### Working with team and stakeholders
This section focuses on the importance of understanding and managing the stakeholders' expectations as a crucial aspect of a data analyst.

Effective communication with stakeholders:
- Stakeholders rely on analyst's work to fulfill their own objectives.
- Regular communication with stakeholders helps build trust and ensures everyone is aligned on project goals, needs and potential challenges.
- Collaborating effectively with team members (project managers, fellow data analysts,...) is crucial for project success.

### Types of stakeholders

- Executive team:
    - The executive team provides strategic and operational leadership to the company. They set goals, develop strategy, and make sure that strategy is executed effectively. 
    - These stakeholders think about decisions at a very high level and they are looking for the headline news about the  project first. They are less interested in the details. 
    - Time is very limited with them, so make the most of it by leading the presentations with the answers to their questions.
- Customer-facing team:
    - The customer-facing team includes anyone in an organization who has some level of interaction with customers and potential customers.
    - Typically they compile information, set expectations, and communicate customer feedback to other parts of the internal organization.
    - It is important to let the data tell the story itself. Make sure that the analysis and presentations focus on what is actually in the data, not on what the stakeholders hope to find.
- Data science team:
    - Organizing data within a company takes teamwork. There's a good chance you'll find yourself working with other data analysts, data scientists, and data engineers. 
    - A big part of your job will be collaborating with other data team members to find new angles of the data to explore.
    - Here's a view of how  different roles on a typical data science team support different functions:
![alt text](image.png)

### Working effectively with stakeholders
The following tips help communicate clearly, establish trust, and deliver the findings across groups:
- Discuss goals
- Feel empowered to say 'no'
- Plan for the unexpected
- Know your project
- Start with words and visuals
- Communicate often

### Staying focused on objectives
- Working with diverse teams and stakeholders can be challenging, but staying focused on the project objective is crucial.
- 3 key questions to ask yourself to maintain focus:
    - **Who are the primary and secondary stakeholders?:** Identifying stakeholders and their goals early on is essential for successful project completion.    
    - **Who is managing the data?:** Understanding data ownership and collaborating with colleagues can save time and enhance analysis.
    - **Where can you go for help?:** Knowing where to seek assistance when facing obstacles ensures smoother project progression.
- **A focused approach leads to better outcomes!**

### Clear communication is key
Before communicating anything, think about:
- Who the audience is
- What they already know
- What they need to know
- How you can communicate that effectively to them

Thinking about your audience and their needs demonstrates respect and fosters better working relationships.

### Tips for affective communication
- Learn as you go and ask questions
- Practice good writing habits
- Read the emails out loud
- Answer in a timely manner

### The importance of clear communication with stakeholders
Throughout a data analysis project, especially when encountering data limitations or potential roadblocks, clear communication with stakeholders is really important. To accomplish that, we need:
- **Setting realistic expectations:** Begin by communicating a clear timeline with stakeholders. Avoid overpromising by setting realistic deadlines.
- **Navigating challenges & Communicating changes:** Inform project manager when encountering data issues or roadblocks.

### The data tradeoff: Speed vs Accuracy

Balancing Speed and Accuracy
- While stakeholders may expect immediate answers, data analysts need time to provide accurate insights.
- Cutting corners can lead to flawed data and misinterpretations, making communication crucial.

Effective Communication Strategies
- Start with a clear understanding of stakeholder expectations and develop a realistic scope of work.
- Use this scope to set timelines, milestones, and manage expectations, confidently addressing out-of-scope requests.

The Power of Reframing and Deeper Analysis
- Instead of providing rushed answers, reframe questions and delve deeper into the problem.
- Taking time to gather context and insights leads to more informed decisions and effective solutions.

### Limitations of data
Understanding the limitations of data is crucial for data analysts.

Data limitations to consider:
- **Incomplete or Nonexistent Data:** You might discover during analysis that your data is insufficient to draw a conclusion. Always acknowledge the limitations of your analysis based on the available data.
- **Inconsistent Data:** Data obtained from different teams might have inconsistencies due to varying business rules and definitions. Establishing standardized measurement methods early in the process can enhance data reliability and accuracy.

Best Practices for Reliable Data Analysis:
- Compare the same types of data
- Visualize with care
- Leave out needless graphs
- Test for statistical significance
- Pay attention to sample size

### Best practices for successful meetings
- **Preparation is key:** Come prepared to contribute by reviewing the agenda, bringing necessary materials, and being ready to share updates on your work.
- **Respect everyone's time:** Arrive on time, stay attentive during presentations and discussions, and ask clarifying questions to avoid misunderstandings.

### Leading great meetings
