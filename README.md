
# access airtable.com
## Motivation
For some hobby webpage projects I want to have a easy to use data entry system to generate and manage content of the webpages to be generated as HTML5 page.

I use the free account of [Airtable] and like to spread the word about their great software.

## About this File (README.md)
This file serves as introduction to the basics and aims to create a basic understanding to use [Airtable] and the [python] module that is hosted here.


## Requirements
If you want to know what this projects aims at see [access-airtable.feature](access-airtable.feature)

## Tools
### airtable.com
- [Airtable] is a web service and web application that "makes it easy to organizse stuff, people, ideas and anything else you can image with your team".
- It gives the user a structured input for data sets in multiple registers.
- It also implements a colaboration function, so many people can work with the same data.
- Furthermore id allows the user to access data via an webbased API
- There are apps for mobile operating systems - at the moment without local storage - this means an online connection is needed.
- See [Airtable] for all the features and integrations.

#### Questions
What is Airtable or what does Airtables slogan "Spreadsheet, meet database." mean

|         Comparision         |        Remark        |
| --------------------------- | --------------------- |
| Is it like table-calculation [^apps1]? | Airtable could be compared to a table calculaction tool. Its bases do have a comparable structure those applications and can be used in a similar way. There are some major **benefits**:  *data-types* of cells are defined - data can be *linked* easily - *colaboration* is build in. |
| Is it like a Database[^apps2]       | Airtable falls more in this group of applications, working with standard database-functionality. But the **benefits** are very low *entry* level - integrated *user interface* and *account management* - managed *hosting* - *commenting* function baked in. |

#### Wording / Glossary
To create a basic understanding and a common wording, here the elements and their possible aliases:

|      Element       |                                                                           Description                                                                            |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| author / account   | As for the most webbased application you will need a account on airtable.com (or login with your google-account). The account gives you access to your workspace |
| field / cell       | the most basic unit of the data. It will always define a type and will be embedded in a record / set                                                             |
| type               | airtable defines rich datatypes from a number, a text-entry (string) or a url up to complex ones like attachments, date with timestamps and even links to other airtable-records (of the same base).                                                                                                                                                                  |
| record / set / row | a record is the defined combination of fields to one unit or set of data. It will be displayed as a row in the table view.                                                                                                                                                                 |
| table / sheet      | a table is the combination of many records that manage together. As for spreadsheets it is comparable to a sheet in a document.                                                                                                                                                                  |
| base               | a base is a collection of tables and could be compared to a document in a classical spreadsheet application. Bases define a border in airtable for functions like internal linking.                                                                                                                                                                 |
| groups             | Groups are sets of bases to one unit. This is great of creating structure or easily share many bases with a team.                                                                                                                                                                 |
| team              | a team is a collection of authors that could access the same group or base.                                                                                   |
| workspace          | The topmost structure and landing page when you are logged in. You will see all your bases inside there groups from there.                                                                                                  |
| views              | A definition how your records are displayed. You can choose from table, calender, kanban view, embedded view, forms and apply filters and sorting.                                                                                                              |

#### Setup Process

- It is free for the basic usage and can be accessed by a standard account (like gmail.com) or with a own login.
### JSON
[JSON] stands for JavaScript-Object-Notation. It is "a lightweight data-interchange format" that has won great popularity over the older [XML] data definition. [JSON] was defined for the usage in JavaScript but has long outgrown its first habitat and is now widley used in many languages. In my opinion it might be named as a integral part of the HTML5 family with HTML, CSS and JavaScript.

### Python (v3)
[Python] is a interpreter based programming language. I use it for many of my hobby projects because there are so many libraries out there (batteries included).

[Python] works very well with web content and can be easily used on many platforms. There are great ressources available on the web like [Dive Into Python 3] if you whant to learn more. Or if you prefer a [basic video course].

**I will focus the development on the actual python version 3 only**.


## Links

|         Link         |                                  Remark                                   |
| -------------------- | ------------------------------------------------------------------------- |
| [Airtable]           | The application to be accessed via its api.                               |
| [JSON]               | the format in which the data of airtable will be accessed.                                                                          |
| [Python]             | The programming language to be used (in the first step)                   |
| [Dive Into Python 3] | a freee online book / tutorial about python 3                             |
| [basic video course] | a free online training for a basic introduction to programming and python |

[Airtable]: https://www.airtable.com
[JSON]: https://www.json.org
[XML]: https://www.wikipedia.org/wiki/xml
[Python]: https://www.python.org
[Dive Into Python 3]: https://www.diveintopython3.net
[basic video course]: https://www.coursera.org/learn/python
[^apps2]: Databases you might know: MySQL, PosgresSQL, SQLite, MongoDB, Microsoft Access
[^apps1]: Table-calculations you might know and use: Microsoft Excel, iWorks Numbers, Openoffice Calc
