# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
~~~
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
    alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("RA Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
~~~


## OUTPUT
![01![02](https://github.com/Sandhiyachittibabu/Ex06_Web-Design/assets/127816323/618b7e21-27ef-422a-bc6f-0c6fd069c325)
![02](https://github.com/Sandhiyachittibabu/Ex06_Web-Design/assets/127816323/abdb20ce-037a-4d52-b10a-96e33d952b6f)
![03](https://github.com/Sandhiyachittibabu/Ex06_Web-Design/assets/127816323/e1a4a1c2-dad4-42e4-87e5-46ef95eaca87)
![04](https://github.com/Sandhiyachittibabu/Ex06_Web-Design/assets/127816323/a6140912-8d63-44d9-ab40-7d5cd57c79e3)
![05](https://github.com/Sandhiyachittibabu/Ex06_Web-Design/assets/127816323/076a14b0-e3b6-4dcb-8da6-4865669bb4df)
![06](https://github.com/Sandhiyachittibabu/Ex06_Web-Design/assets/127816323/f18d3a70-86ac-45c4-9cd0-8e3955e8bc47)
## RESULT
  Student result using JavaScript is created successfully.
