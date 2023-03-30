Advance JavaScript
MODULE: 1

Name : Mohmad Mohasin

1. Write a program to Show an alert
Ans. <script>
function showAlert()
{ alert("Hello, World!"); }
</script>

2. What will be the result for these expressions?
1. 5 > 4 = true
2. "apple" > "pineapple" = false
3. "2" > "12" = false
4. undefined == null = true
5. undefined === null = false
6. null == "¥n0¥n" = false
7. null === +"¥n0¥n" = false

3. Will alert be shown?
if ("0") { alert( 'Hello'); }

Ans. Yes alert function() will be shown.

Q4. What is the code below going to output? alert( null || 2 || undefined );
Ans. 2

5. The following function returns true if the parameter age is greater than 18. Otherwise it asks
for a confirmation and returns its result:
function
checkAge(age)
{
if (age> 18) { return true; }
else { // ...return confirm (‘did parents allow you?');
}
}

6. Replace Function Expressions with arrow functions in the code below: Function
ask(question, yes, no)
{ if (confirm(question))yes();
else
no();
}
ask("Do you agree?", function()
{ alert("You agreed."); },
function() {

alert("You canceled the execution."); }
}
Ans. const ask = (question, yes, no) => {
if (confirm(question)) {
yes();
} else {
no();
}
};
ask(
"Do you agree?",
() => {
alert("You agreed.");
},
() => {
alert("You canceled the execution.");
}
);

Thank you
