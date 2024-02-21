# Fizzbuzz
# FizzBuzz
//when the number is divisible by 3 return the word fizz

//when the number is divisible by 5 return the word buzz

//when the number is divisible by both, return the word fizzbuzz

public static string FizzBuzz(int num)
{
    var answer = "";

if (num %3 == 0)
{
    answer = "fizz";
}
if (num %5 == 0)
{
    answer += "buzz";
}

return answer;

}