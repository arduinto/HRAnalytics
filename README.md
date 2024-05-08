﻿# HrAnalytics
### Dataframe

<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Performance_Review</th>
      <th>City</th>
      <th>Last_Promotion_Date</th>
      <th>Salary</th>
      <th>Overdue_Vacation</th>
      <th>Employee</th>
      <th>Gender</th>
      <th>Birth_Date</th>
      <th>Hire_Date</th>
      <th>Termination_Date</th>
      <th>Termination_Reason</th>
      <th>Education</th>
      <th>Position</th>
      <th>Department</th>
      <th>Manager</th>
    </tr>
    <tr>
      <th>ID</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>10</td>
      <td>Alabama</td>
      <td>NaT</td>
      <td>4539</td>
      <td>No</td>
      <td>Harley Matthews</td>
      <td>Female</td>
      <td>1989-08-17</td>
      <td>2011-10-02</td>
      <td>NaT</td>
      <td>NaN</td>
      <td>Higher Certificate</td>
      <td>Administrator</td>
      <td>Finance / Accounting</td>
      <td>Phelipp</td>
    </tr>
    <tr>
      <th>2</th>
      <td>10</td>
      <td>Arizona</td>
      <td>NaT</td>
      <td>3698</td>
      <td>Yes</td>
      <td>Aliyah Thomas</td>
      <td>Female</td>
      <td>1988-03-27</td>
      <td>2012-03-22</td>
      <td>2015-05-01</td>
      <td>Unfair Dismissal</td>
      <td>Higher Certificate</td>
      <td>Lawyer</td>
      <td>Legal</td>
      <td>Anna</td>
    </tr>
    <tr>
      <th>3</th>
      <td>8</td>
      <td>Colorado</td>
      <td>NaT</td>
      <td>4157</td>
      <td>Yes</td>
      <td>Madeleine Bradley</td>
      <td>Female</td>
      <td>1981-04-18</td>
      <td>2012-08-24</td>
      <td>2016-06-19</td>
      <td>Resignation</td>
      <td>Bachelor's Incompleted</td>
      <td>Administrative Analyst</td>
      <td>Finance / Accounting</td>
      <td>Phelipp</td>
    </tr>
    <tr>
      <th>4</th>
      <td>10</td>
      <td>Missouri</td>
      <td>NaT</td>
      <td>4360</td>
      <td>Yes</td>
      <td>Gabrielle Gardner</td>
      <td>Female</td>
      <td>2002-10-31</td>
      <td>2012-11-12</td>
      <td>NaT</td>
      <td>NaN</td>
      <td>Bachelor's Completed</td>
      <td>Accounting Analyst</td>
      <td>Finance / Accounting</td>
      <td>Phelipp</td>
    </tr>
    <tr>
      <th>5</th>
      <td>7</td>
      <td>New York</td>
      <td>NaT</td>
      <td>4144</td>
      <td>Yes</td>
      <td>Molly Owen</td>
      <td>Female</td>
      <td>1979-10-22</td>
      <td>2013-09-18</td>
      <td>NaT</td>
      <td>NaN</td>
      <td>Bachelor's Completed</td>
      <td>Database Analyst</td>
      <td>Strategy</td>
      <td>Antonella</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>86</th>
      <td>10</td>
      <td>Alabama</td>
      <td>NaT</td>
      <td>4430</td>
      <td>No</td>
      <td>Aryan Reynolds</td>
      <td>Male</td>
      <td>1963-11-21</td>
      <td>2018-12-17</td>
      <td>2019-03-17</td>
      <td>Resignation</td>
      <td>Higher Certificate</td>
      <td>Commercial Assistant</td>
      <td>Sales</td>
      <td>Gabriela</td>
    </tr>
    <tr>
      <th>87</th>
      <td>9</td>
      <td>Arizona</td>
      <td>NaT</td>
      <td>4183</td>
      <td>No</td>
      <td>Grayson Lowe</td>
      <td>Male</td>
      <td>1986-04-15</td>
      <td>2019-05-05</td>
      <td>NaT</td>
      <td>NaN</td>
      <td>Bachelor's Incompleted</td>
      <td>Developer</td>
      <td>Development</td>
      <td>Leyla</td>
    </tr>
    <tr>
      <th>88</th>
      <td>10</td>
      <td>Colorado</td>
      <td>NaT</td>
      <td>4308</td>
      <td>No</td>
      <td>Antonio Ball</td>
      <td>Male</td>
      <td>1984-08-17</td>
      <td>2019-07-25</td>
      <td>NaT</td>
      <td>NaN</td>
      <td>Bachelor's Completed</td>
      <td>Pogrammer Analyst</td>
      <td>Development</td>
      <td>Leyla</td>
    </tr>
    <tr>
      <th>89</th>
      <td>7</td>
      <td>Maryland</td>
      <td>NaT</td>
      <td>3920</td>
      <td>No</td>
      <td>Ethan Simpson</td>
      <td>Male</td>
      <td>1969-07-14</td>
      <td>2019-08-04</td>
      <td>NaT</td>
      <td>NaN</td>
      <td>Bachelor's Completed</td>
      <td>Salesperson</td>
      <td>Sales</td>
      <td>Gabriela</td>
    </tr>
    <tr>
      <th>90</th>
      <td>7</td>
      <td>Hawaii</td>
      <td>NaT</td>
      <td>4001</td>
      <td>Yes</td>
      <td>Blake Barker</td>
      <td>Male</td>
      <td>1982-06-13</td>
      <td>2019-10-10</td>
      <td>NaT</td>
      <td>NaN</td>
      <td>Doctoral</td>
      <td>Developer</td>
      <td>Development</td>
      <td>Leyla</td>
    </tr>
  </tbody>
</table>
<p>90 rows × 15 columns</p>
</div>

### __Gender Frequency (PCT)__

![gender freq](https://github.com/arduinto/HRAnalytics/assets/142419799/c3c0a85d-7811-4689-9661-052ecbb3cecc)

### __The Distribution of Age of Our Employees__

![dist age employees](https://github.com/arduinto/HRAnalytics/assets/142419799/93c8dd75-a32c-48cf-9041-0e40c6d9d12c)

### __Education Level Frequency (PCT)__

![edu level freq](https://github.com/arduinto/HRAnalytics/assets/142419799/c4aac6bf-9b12-47ed-a9cd-ceca8370138c)

### __Performance 5-Summary__

![perf 5 summary](https://github.com/arduinto/HRAnalytics/assets/142419799/870dfe8a-48ed-49ed-adee-6bc520b33e0f)

### __Hired Employees Through Years__

![hired employees through year](https://github.com/arduinto/HRAnalytics/assets/142419799/d7c228e3-f2d2-4453-be05-100369c79b51)

### __WordCloud__

![wordcloud](https://github.com/arduinto/HRAnalytics/assets/142419799/ff5dbea7-b674-4cb4-8086-7e6a48b61aea)

### Question & Insights
##### __What is the average salary for each department?__

![avg salary each dept](https://github.com/arduinto/HRAnalytics/assets/142419799/e0f06e41-29c7-4460-ac91-96c6e9477371)

##### __What is the average performance for each department?__

![avg perf each dept](https://github.com/arduinto/HRAnalytics/assets/142419799/46d20c9f-1e69-4182-84f7-e68502a2d02e)

##### __What is the average salary for each jon position?__

<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Salary</th>
    </tr>
    <tr>
      <th>Position</th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Administrator</th>
      <td>4,539.0</td>
    </tr>
    <tr>
      <th>Commercial Assistant</th>
      <td>4,361.7</td>
    </tr>
    <tr>
      <th>Communication Analyst</th>
      <td>4,333.5</td>
    </tr>
    <tr>
      <th>Administrative Analyst</th>
      <td>4,325.0</td>
    </tr>
    <tr>
      <th>Financial Analyst</th>
      <td>4,304.0</td>
    </tr>
    <tr>
      <th>Marketing Analyst</th>
      <td>4,294.0</td>
    </tr>
    <tr>
      <th>Administrative Assistant</th>
      <td>4,234.0</td>
    </tr>
    <tr>
      <th>Developer</th>
      <td>4,200.1</td>
    </tr>
    <tr>
      <th>Accounting Analyst</th>
      <td>4,183.0</td>
    </tr>
    <tr>
      <th>Business Intelligence Analyst</th>
      <td>4,140.6</td>
    </tr>
  </tbody>
</table>
</div>

##### __For each department, what is the popularity of each gender?__

![pupolarity gender each dept](https://github.com/arduinto/HRAnalytics/assets/142419799/87ac39ad-1726-437e-b052-f6c9ab220eae)

##### __Important KPI : What is the Performance Review Completion Rate?__

Performance Review Completion Rate: 17.78%

##### I think 17.78% is low. So the recommendation is:
* Offer training for Employees
* Reward and Punishment : To Encourage all employees to get high performance reviews
* Visual Performance Tracking : We can share the performance tracking for all employees which will be extremely effective in motivating them
