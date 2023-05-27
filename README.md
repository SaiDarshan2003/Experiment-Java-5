# Experiment-5

# To Create a Table

## Aim:
  To create a table using HTML 
  
## Algorithm

Step 1 : Open Visual Studio Code application or any other code editor.

Step 2 : Create an Header for your table with desirable amount of columns of your choice.

Step 3 : Using <tr> and <th> create rows and headers respectively.

Step 4 : Using style attribute,add colors and fonts to your table.

Step 5 : Display the timetable in the webpage.

## Program

```
  <!DOCTYPE html>
<html>

<body>
	<h1>TIME TABLE</h1>
	<table border="5" cellspacing="0" align="center">
		<!--<caption>Timetable</caption>-->
		<tr>
			<td align="center" height="50"
				width="100"><br>
				<b>Day/Period</b></br>
			</td>
			<td align="center" height="50"
				width="100">
				<b>I<br>9:30-10:20</b>
			</td>
			<td align="center" height="50"
				width="100">
				<b>II<br>10:20-11:10</b>
			</td>
			<td align="center" height="50"
				width="100">
				<b>III<br>11:10-12:00</b>
			</td>
			<td align="center" height="50"
				width="100">
				<b>12:00-12:40</b>
			</td>
			<td align="center" height="50"
				width="100">
				<b>IV<br>12:40-1:30</b>
			</td>
			<td align="center" height="50"
				width="100">
				<b>V<br>1:30-2:20</b>
			</td>
			<td align="center" height="50"
				width="100">
				<b>VI<br>2:20-3:10</b>
			</td>
			<td align="center" height="50"
				width="100">
				<b>VII<br>3:10-4:00</b>
			</td>
		</tr>
		<tr>
			<td align="center" height="50">
				<b>Monday</b></td>
			<td align="center" height="50">Eng</td>
			<td align="center" height="50">Mat</td>
			<td align="center" height="50">Che</td>
			<td rowspan="6" align="center" height="50">
				<h2>L<br>U<br>N<br>C<br>H</h2>
			</td>
			<td colspan="3" align="center"
				height="50">LAB</td>
			<td align="center" height="50">Phy</td>
		</tr>
		<tr>
			<td align="center" height="50">
				<b>Tuesday</b>
			</td>
			<td colspan="3" align="center"
				height="50">LAB
			</td>
			<td align="center" height="50">Eng</td>
			<td align="center" height="50">Che</td>
			<td align="center" height="50">Mat</td>
			<td align="center" height="50">SPORTS</td>
		</tr>
		<tr>
			<td align="center" height="50">
				<b>Wednesday</b>
			</td>
			<td align="center" height="50">Mat</td>
			<td align="center" height="50">phy</td>
			<td align="center" height="50">Eng</td>
			<td align="center" height="50">Che</td>
			<td colspan="3" align="center"
				height="50">LIBRARY
			</td>
		</tr>
		<tr>
			<td align="center" height="50">
				<b>Thursday</b>
			</td>
			<td align="center" height="50">Phy</td>
			<td align="center" height="50">Eng</td>
			<td align="center" height="50">Che</td>
			<td colspan="3" align="center"
				height="50">LAB
			</td>
			<td align="center" height="50">Mat</td>
		</tr>
		<tr>
			<td align="center" height="50">
				<b>Friday</b>
			</td>
			<td colspan="3" align="center"
				height="50">LAB
			</td>
			<td align="center" height="50">Mat</td>
			<td align="center" height="50">Che</td>
			<td align="center" height="50">Eng</td>
			<td align="center" height="50">Phy</td>
		</tr>
		<tr>
			<td align="center" height="50">
				<b>Saturday</b>
			</td>
			<td align="center" height="50">Eng</td>
			<td align="center" height="50">Che</td>
			<td align="center" height="50">Mat</td>
			<td colspan="3" align="center"
				height="50">SEMINAR
			</td>
			<td align="center" height="50">SPORTS</td>
		</tr>
	</table>
</body>

</html>


```

## Output

![timetableimage](https://github.com/SaiDarshan2003/Experiment-Java-5/assets/94692595/b2b26ef7-c949-4189-9507-64f5303d7fd8)



## Result 
  We have successfully created a table using HTML.
  
  
