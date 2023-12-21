# 留学生日常作业/课程设计/代码辅导/CS/DS/商科，仅为漂洋过海的你❥
标签：Computer Science、Data Science、Business Administration，留学生编程作业代写&&辅导

## 个人介绍:
本人是一名资深码农，酷爱投资。

[为您提供 CS , DS , 商科 编程作业代写](http://dzuoye.work "编程代写")

<img src="design2023866.jpg"  width="200" />


# Business Data Analyzer
The goal of this assignment is to demonstrate your understanding of lists in the collection framework in
Java.
# Background
The data Analyzer should analyze data available at (open dataset) and answer queries given by the
user about the data set.
# Requirements
Your implementation must satisfy a number of requirements, including each of the following:
● Use of the data exported from SF Businesses Dataset
● Executing the user commands provided as arguments and make the output
accordingly
● Switch implementation to use different collection data structures of your
implementation - LinkedList and ArrayList based on a flag passed as argument
● Use generics in your implementation
● Use of your implementation of ListIterator (LinkedList and ArrayList)
● Remember all the commands entered by the user and execute them all in order of
command entry
# Requirement 1: Reading the data
Your implementation should use the exported format as CSV. You should read all the data into
objects of a proper class structure for business entities.
The application should be run as below using ArrayList and LinkedList implementation
respectively based on the flag passed as second argument.
java BusinessAnalyzer Registered_Business_Locations_-_San_Francisco.csv
AL
java BusinessAnalyzer Registered_Business_Locations_-_San_Francisco.csv
LL
Use proper collection data structures for loading the data.
# Requirement 2: Processing the contents
Once the content is loaded, keep the data in a separate list for each NAICS code. Use your own
implementation of ArrayList and LinkedList based on the arguments provided. The NAICS code is
provided as a range in the dataset (eg. 4400-4599). In the next section the user can ask for a
particular NAICS code summary and you should be able to determine which range the code falls
under. Arrange your data structure to answer the questions
You’ll use the data processed to provide summary data as output. The summary is by zip code or
NAICS code or general. The next section has examples for these commands and outputs.
# Requirement 3: Executing user commands
After reading the contents and analyzing it, you’ll ask the user to enter commands. The sample
commands are given below. The program will exit when the user enters command quit.
Example 1: (bold text the command)
Command: Zip 94108 Summary
Will produce the following output:
94018 Business Summary
Total Businesses: 3238
Business Types: 37
Neighborhood: 38
Example 2:
Command: NAICS 4855 Summary
Will produce the following output:
Total Businesses: 3255
Zip Codes: 5
Neighborhood: 38
Example 3:
Command: Summary
Will produce the following output:
Total Businesses: 303118
Closed Businesses: 30000
New Business in last year: 2000
# Requirement 4: Remembering user commands
As the user enters commands, place them in a queue and show them to the user when they want to see it
with a command “history”. Use java collection framework Queue implementation for this purpose.
Here is an example of this command working:
Example 4:
Command: History
Will produce the following output:
Zip 94108 Summary
NAICS 4855 Summary
Summary
# Code Style
Your implementation must use self-documenting names for variables and functions. You may choose
either camel case or snake case as long as you use one style consistently. Your implementation must use
Javadoc comments — example below — for each function. It may also be useful to use in-line comments
for code doing something that is not obvious or that is otherwise noteworthy.
/** fibonacci method recursively calculates and returns
* the fibonacci value of a given integer.
* @param integer n to calculate
* @return integer fibonacci value at n
*/
int fibonacci(int n){
if (n <= 1) return n; // Base case
else return fib(n-1) + fib(n-2);
}
# Submission
Submit the source code for your implementation through Github. You may also add any comments in a
README.md in Github repo to help the grader understand or execute your implementation. Submit your
Github repo URL to Canvas. The source code for your implementation must be in Java.
The submission should also include a reference to the URL that was tested and the summary /
commands that got executed on that page with results. Keep this result in the root folder of your github
repository with name - sample-result.pdf

## 作业代写价格:
|类型|美元|人民币|
|-----:|-----:|-----:|
|Assignment|$40-$120|¥400-¥800|

### 为了方便快速定价和确定是否代做，麻烦提供私聊的时候提供以下信息：
如果是作业，提供本次作业要求文档；如果是考试，提供考试范围和考试时间
一两句话概括一下作业任务或者考试任务，比如”可以帮忙实现一个决策树算法吗？”、”网络安全选择题考试，范围是内网横向移动知识点”
### 作业定价有两种方式：
    - 根据定价标准进行
    - 通过微信我们一起协商
## 联系方式
[为您提供 CS , DS , 商科 编程作业代写](http://dzuoye.work "编程代写")
微信（WeChat）：design2023866

<img src="design2023866.jpg"  width="200" />
