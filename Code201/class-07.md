# HTML Tables; JS Constructor Functions

There are several types of information that need to be displayed in a grid or table. For example: sports results, stock reports, train timetables.

![  ](https://assets.hongkiat.com/uploads/html-table-building-30-beautiful-examples-and-useful-javascripts/table-jquery-snippets.jpg)

photo by [hongkiat](https://assets.hongkiat.com/uploads/html-table-building-30-beautiful-examples-and-useful-javascripts/table-jquery-snippets.jpg)

## Basic Table Structure

```<table>```

The ```<table>``` element is used to create a table. The contents of the table are written out row by row

```<tr>```

You indicate the start of each row using the opening ```<tr>``` tag. (The tr stands for table row.) It is followed by one or more ```<td>``` elements (one for each cell in that row). At the end of the row you use a  closing ```</tr>``` tag.

```<td>```

Each cell of a table is represented using a ```<td>``` element. (The td stands for table data.)At the end of each cell you use a closing ```</td>``` tag.

~~~
<table>
  <tr>    
    <td>15</td>    
    <td>15</td>    
    <td>30</td>  
  </tr>
  <tr>
    <td>45</td>
    <td>60</td>
    <td>45</td>
   </tr>
   <tr>
     <td>60</td>
     <td>90</td>
     <td>90</td>
    </tr>
</table>
~~~

Result:

 15    15    30

 45    60    45

 60    90    90

- The ```<table>``` element is used to add tables to a web page.

- A table is drawn out row by row. Each row is created with the ```<tr>``` element.

- Inside each row there are a number of cells represented by the ```<td>``` element (or ```<th>``` if it is a header).

- You can make cells of a table span more than one row or column using the rowspan and colspan attributes.

- For long tables you can split the table into a ```<thead>```, ```<tbody>```, and ```<tfoot>```. 