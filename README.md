# datatable search each header plus filter
this is datatable from https://github.com/DataTables/DataTables with my edit
<p>
  in this reposotory we have two html file
</p>
<p>
  1- index.html
 </p>
<p>
i use datatable + jquery for made a table that can filter each culomn if you whant dont have search box on specefic header you should add class="nosearch"
</p>
<p>
  2- tables.html
</p>
<p>
microsoft office word table template are coped here i use same name as microsoft use   
  </p>
  
## how this work
<p>we need </p>
<p>
datatables.min.css
  </p>
  <p>
datatable-init.css
  </p>
  <p>
jquery-3.6.0.min.js
  </p>
    <p>
datatables.min.js
  </p>
  <p>
  all this resorses are in this reposetory you can click on green code button add click on download zip or use git bash for clone this
  </p>
```
$ git clone https://github.com/samanbalahang/table.githttps://github.com/samanbalahang/table.git
```
<p>
  in thml file you have to create table with this structure
```
   <table class="datatable">
        <thead>
            <tr>
                <th class="nosearch">title</th>
                <th>title</th>
                <th>title</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td></td>
                <td>data</td>
                <td>data</td>
            </tr>
            <tr>
                <td></td>
                <td>data</td>
                <td>data</td>
            </tr>
            <tr>
                <td></td>
                <td>data</td>
                <td>data</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <th>title</th>
                <th>title</th>
                <th>title</th>
            </tr>
        </tfoot>
    </table>
  ```
  <p>
  attention to th in thead and empty frist td tn tbody(its replaced by a number auto generated by script
