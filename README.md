# C Palindrome Checker

A function is required to checks strings to see if they are a palindroms. A palindrome string that reads the same, backwards, or forwards. 
This example looks at whether a number is Palindrome 

pseudo code 

number = 123
temp = number 

while(temp!=0){
  remainder = temp%10;
  reverse = reverse*10+remainder;
  temp = temp/10;

}
if(number == reverse){
  Palindrome
}
else (number != reverse){
  not palindrome 
}
