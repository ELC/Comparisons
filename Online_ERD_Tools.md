# Description
Entity Relationship Diagram is a tool to visualize how the relation between entities are, check integrity and serve as the basis for Data Base Design

Do not forget to read the contributing file before create issues and pull requests

## Index
1. [Scenario](#scenario)
1. [Evaluated Features](#evaluated-features)
1. [IDEs Index](#ides-index)
1. [Disqualified](#disqualified)
1. [Evaluation](#evaluation)
1. [Sumary Table](#sumary-table)
1. [Conclusion](#conclusion)

## Scenario
Entity relationship diagram tools are used mainly in educational context or in some specific situation in professional life. Since education is one of the main areas of usage, the scenario will be a University.

## Evaluated Features:

- Web Based: Can be executed with nothing more than a web broser
- Number of Diagrams: Amount of diagrams that a free user can create
- No trial: Should have no limit of time for free use
- Chen: Uses chen notation to make diagrams
- Crow's Foot: uses Crow's Foot notations to make diagrams
- GDrive: Integration with Google Drive for storage
- Flexibility: Being useful in other areas besides the needed for this subject
- Interface: Having an user-friendly interface
- Convert: Being able to convert the diagram into relational schema

### Restrictions

    Only tools with free account option will be consider, not necessarily being them open-source or free software

## IDEs Index:
Click to open the official webpage

1. [Cacoo](https://cacoo.com)
1. [Creately](https://creately.com)
1. [Draw.io](https://www.draw.io)
1. [Dia](https://wiki.gnome.org/Apps/Dia)
1. [ERDPlus](https://erdplus.com)
1. [Gliffy](https://www.gliffy.com)
1. [Grapholite](https://grapholite.com/)
1. [LovelyCharts](http://lovelycharts.com/)
1. [LucidChart](https://www.lucidchart.com)
1. [Pony](https://ponyorm.com/)
1. [Smart Draw Cloud](https://www.smartdraw.com)

## Disqualified
The following candidates weren't included in the list for several reasons:

### Non-Free
- [Grapholite](https://grapholite.com/): Does not have free account option
- [Smart Draw Cloud](https://www.smartdraw.com): Does not have free account option

### Limited time for free accounts
- [LovelyCharts](http://lovelycharts.com/): The free account is for a limited time

### Discontinued
- [Dia](https://wiki.gnome.org/Apps/Dia): The app has beenn discontinued


## Evaluation
After filter by the prior requirement the final candidates are:
1. [Cacoo](https://cacoo.com)
1. [Creately](https://creately.com)
1. [Draw.io](https://www.draw.io)
1. [ERDPlus](https://erdplus.com)
1. [Gliffy](https://www.gliffy.com)
1. [LucidChart](https://www.lucidchart.com)
1. [Pony](https://ponyorm.com/)

## Sumary Table

|             Name             	| [LucidChart](https://www.lucidchart.com) 	| [Creately](https://creately.com) 	| [Cacoo](https://cacoo.com) 	| [Gliffy](https://www.gliffy.com) 	| [ERDPlus](https://erdplus.com) 	| [Pony](https://ponyorm.com/) 	| [Draw.io](https://www.draw.io) 	|
|:----------------------------:	|:----------------------------------------:	|:--------------------------------:	|:--------------------------:	|:--------------------------------:	|:------------------------------:	|:----------------------------:	|:------------------------------:	|
|             Price            	|                 Free/Paid                	|             Free/Paid            	|          Free/Paid         	|             Free/Paid            	|              Free              	|             Free             	|              Free              	|
|        No of Diagrams        	|                     3                    	|                 5                	|             15             	|                 5                	|            Unlimited           	|           Unlimited          	|            Unlimited           	|
|          Share Link          	|                     ✔                    	|                 ✔                	|              ✔             	|                 ✔                	|               :x:              	|               ✔              	|                ✔               	|
|       User Friendly UI       	|                     ✔                    	|                 ✔                	|             :x:            	|                 ✔                	|                ✔               	|               ✔              	|                ✔               	|
|            GDrive            	|                     ✔                    	|                :x:               	|              ✔             	|                 ✔                	|               :x:              	|              :x:             	|                ✔               	|
|             Chen             	|                    :x:                   	|                 ✔                	|              ✔             	|                 ✔                	|                ✔               	|              :x:             	|                ✔               	|
|          Crow's Foot         	|                    :x:                   	|                :x:               	|              ✔             	|                 ✔                	|                ✔               	|              :x:             	|                ✔               	|
|       Relational Schema      	|                     ✔                    	|                :x:               	|             :x:            	|                :x:               	|                ✔               	|               ✔              	|                ✔               	|
|     Automatic Connection     	|                    :x:                   	|                :x:               	|             :x:            	|                :x:               	|                ✔               	|               ✔              	|               :x:              	|
| Convert to Relational Schema 	|                    :x:                   	|                :x:               	|             :x:            	|                :x:               	|                ✔               	|              :x:             	|               :x:              	|
|        Convert To Code       	|                    :x:                   	|                :x:               	|             :x:            	|                :x:               	|                ✔               	|               ✔              	|               :x:              	|

## Reduced Sumary Table
Since the number of diagrams is key, just tools with no restrictions are consider, additionally, redundant features are omited

|             Name             	| [ERDPlus](https://erdplus.com) 	| [Pony](https://ponyorm.com/) 	| [Draw.io](https://www.draw.io) 	|
|:----------------------------:	|:------------------------------:	|:----------------------------:	|:------------------------------:	|
|          Share Link          	|               :x:              	|               ✔              	|                ✔               	|
|            GDrive            	|              :x:*              	|             :x:*             	|               ✔**              	|
|             Chen             	|                ✔               	|              :x:             	|                ✔               	|
|          Crow's Foot         	|                ✔               	|              :x:             	|                ✔               	|
|     Automatic Connection     	|                ✔               	|               ✔              	|               :x:              	|
| Convert to Relational Schema 	|            ✔ (Beta)            	|              :x:             	|               :x:              	|
|        Convert To Code       	|            ✔ (Beta)            	|             ✔\***            	|               :x:              	|

(\*) Files are storage in the cloud

(\**) Files have to be storaged in a third party services, the options are: GDrive, GitHub, Dropbox, OneDrive or Locally

(\***) Can convert to Python, SQLite, MySQL, PostgreeSQL and Oracle

## Conclusion
It seems to me that depending on the situation the three last candidates are suitable but since convertion to code and to relational schema can be provided from third party software such as data base engines. The most general and open candidate is [Draw.io](https://www.draw.io)
