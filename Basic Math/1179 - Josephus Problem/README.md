## Key Idea
<b> Find out some solution manually and try to find the pattern</b><br>
Let's draw a table for n<=10 and k<=10<br>

<table>
  <tr>
 <th> N\k </th><th> 1 </th><th> 2 </th><th> 3 </th><th> 4 </th><th> 5 </th><th> 6 </th><th> 7 </th><th> 8 </th><th> 9 </th><th> 10 </th>
  </tr>
  <tr>
<th> 1 </th><td> 1 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> 1 </td>
  </tr>
  <tr>
<th> 2 </th><td> 2 </td><td> 1 </td><td> 2 </td><td> 1 </td><td> 2 </td><td> 1 </td><td> 2 </td><td> 1 </td><td> 2 </td><td> 1 </td>
  </tr>
  <tr>
<th> 3 </th><td> 3 </td><td> 3 </td><td> 2 </td><td> 2 </td><td> 1 </td><td> 1 </td><td> 3 </td><td> 3 </td><td> 2 </td><td> 2 </td>
  </tr>
  <tr>
<th> 4 </th><td> 4 </td><td> 1 </td><td> 1 </td><td> 2 </td><td> 2 </td><td> 3 </td><td> 2 </td><td> 3 </td><td> 3 </td><td> 4 </td>
  </tr>
  <tr>
<th> 5 </th><td> 5 </td><td> 3 </td><td> 4 </td><td> 1 </td><td> 2 </td><td> 4 </td><td> 4 </td><td> 1 </td><td> 2 </td><td> 4 </td>
  </tr>
  <tr>
<th> 6 </th><td> 6 </td><td> 5 </td><td> 1 </td><td> 5 </td><td> 1 </td><td> 4 </td><td> 5 </td><td> 3 </td><td> 5 </td><td> 2 </td>
  </tr>
  <tr>
<th> 7 </th><td> 7 </td><td> 7 </td><td> 4 </td><td> 2 </td><td> 6 </td><td> 3 </td><td> 5 </td><td> 4 </td><td> 7 </td><td> 5 </td>
  </tr>
  <tr>
<th> 8 </th><td> 8 </td><td> 1 </td><td> 7 </td><td> 6 </td><td> 3 </td><td> 1 </td><td> 4 </td><td> 4 </td><td> 8 </td><td> 7 </td>
  </tr>
  <tr>
<th> 9 </th><td> 9 </td><td> 3 </td><td> 1 </td><td> 1 </td><td> 8 </td><td> 7 </td><td> 2 </td><td> 3 </td><td> 8 </td><td> 8 </td>
  </tr>
  <tr>
<th> 10 </th><td> 10 </td><td> 5 </td><td> 4 </td><td> 5 </td><td> 3 </td><td> 3 </td><td> 9 </td><td> 1 </td><td> 7 </td><td> 8 </td>
  </tr>
</table>


this table proves that.
N<sub>n,k</sub> = (N <sub>n-1,k</sub> + k -1)% N + 1

for more detail's [click](https://cp-algorithms.com/others/josephus_problem.html)
