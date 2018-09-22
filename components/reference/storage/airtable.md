# Airtable

Airtable is a non-visible component that is a spreadsheet-database hybrid, with the features of a database but applied to a spreadsheet. Airtable can store information in a spreadsheet that's visually appealing and easy-to-use, but it's also powerful enough to act as a database that businesses can use for customer-relationship management \(CRM\), task management, project planning, and tracking inventory.

AppyBuilder has component and blocks to access and manipulate your Airtable spreadsheets. To start using Airtable:

1. create an account [HERE](https://airtable.com/invite/r/eHgwOBFW) or simply log into Airtable. Next, create a spreadsheet using "Add a base" and then selecting "Start from scratch"

![](../../../.gitbook/assets/image%20%2853%29.png)

2. After assigning a name, you'll be brought to a screen like below. I

* Item 1 is the name of your spreadsheet \(also **referred to as base-id**\). 
* Item 2 is the name of your table **\(store away this table name\)**
* Item 3 is the name of your view **\(Store away this grid name\)**
* Click item 4 \(+ sign\) to add column. 
* Click on each header \(item 5\) to either change default column name, or delete column or add a new column. 
* Click on Account \(item 6\) to retrieve your account API Key **\(store away this API Key\)**

![](../../../.gitbook/assets/image%20%288%29.png)

Generating API key is by going to your account \(item 6 above\) and then generating \(or viewing\) an API Key:

![](../../../.gitbook/assets/image%20%2831%29.png)

4. Finally, you'll need to retrieve an id \(BaseId\) that is a unique id for the selected table. Goto [https://airtable.com/api](https://airtable.com/api) and then select the spreadsheet that was just created. When the page opens, scroll down to "AUTHENTICATION" and on right hand side select "node.js".  Take note of this BaseID.

![](../../../.gitbook/assets/image%20%2862%29.png)

To manipulate \(Add, Read, Update, Delete\) data, goto your AppyBuilder project and fro Storage category, select Airtable and drop onto layout:

![](../../../.gitbook/assets/image%20%2816%29.png)

 

![](../../../.gitbook/assets/image%20%2829%29.png)

  
The properties section of Airtable component will now have the properties shown below. Paste your Airtable API key and Base ID into properties above. Also change the TableName and ViewName to match your Airtable names \(use defaults if you haven't changed them\)

![](../../../.gitbook/assets/image%20%2818%29.png)

In blocks-editor, you can find may blocks to retrieve rows or add, delete, update row / cell data:

![](../../../.gitbook/assets/image%20%289%29.png)

There are also event-handler blocks that are associated with the blocks. For example, to retrieve row data, you'll use Airtable.GetRow block. Once result is retrieved, it will trigger Airtable1.GotRow event-handler:

![](../../../.gitbook/assets/image%20%2844%29.png)

AppyBuilder contains may other blocks for handling single or multiple rows or columns or even single cell:

![](../../../.gitbook/assets/image%20%2858%29.png)

