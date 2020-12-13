<table>
  <tr>
<th>Golang</th><th>GraphQL</th><th>TypeScript</th>
    </tr>
   <tr>
<td>x:="hello"</td><td>x: String</td><td>let x:string="hello"</td>
    </tr>
    <tr>
  <td>string</td><td>String</td><td>string</td>
  </tr>  <tr>
   <td>bool</td><td>Boolean</td><td></td>
  </tr>  <tr>
   <td></td><td>ID</td><td></td>
  </tr>  
  <tr>
<td>x:=4 <br/>z:= string(x)</td><td></td><td>let y:any=5 <br/>
          let z = &lt;number&gt; y <br/>
          let a = y as number
</td>
    </tr>
</table>


In GraphQL we wont assign values to fields it is done by resolvers 
we can force a field as required by adding ! ex: x: String!
