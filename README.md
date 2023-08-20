- 👋 Hi, I’m @21CD023
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
21CD023/21CD023 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
GCD
In this script: echo "Enter two numbers with space in between") 
read a b) 
m=$a) 
if [ $b -lt $m ]) 
then) 
m=$b) 
fi) 
while [ $m -ne 0 ]) 
do) 
x=` expr $a % $m `) 
y=` expr $b % $m `) 
if [ $x -eq 0 -a $y -eq 0 ]) 
then) 
echo "GCD of $a and $b is $m") 
break) 
fi) 
m=` expr $m - 1 `) 
done) 
echo "Enter first number") 
read a) 
echo "Enter secong number") 
read b) 
p=` expr $a \* $b `) 
while [ $b -ne 0 ]) 
do) 
r=` expr $a % $b `) 
a=$b) 
b=$r) 
done) 
LCM=` expr $p / $a `) 
echo "LCM=$LCM") 




LOWER TO UPPER
var_name="THIS IS a TEST") 
echo $var_name|tr '[:upper:]' '[:lower:]') 
movie="The Matrix") 
echo $movie|tr '[:lower:]' '[:upper:]') 



PALINDROME
read -p "enter a string:" input_string) 
clean_string=$(echo $input_string|tr -dc '[:alnum:]'|tr '[:upper:]' '[:lower:]')) 
reverse_string=$(echo $clean_string|rev)) 
if [ "$clean_string" = "$reverse_string" ]) 
then) 
echo "the string $input_string is a palindrome") 
else) 
echo " the string '$input_string' is not a palindrome ") 
fi




REVERSING
#!/bin/bash) 
echo "Enter a number") 
read a) 
rev=0) 
sd=0) 
or=$a) 
while [ $a -gt 0 ]) 
do) 
sd=` expr $a % 10 `) 
temp=` expr $rev \* 10 `) 
rev=` expr $temp + $sd `) 
a=` expr $a / 10 `) 
done) 
echo "Reverse of $or is $rev") 
