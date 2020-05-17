### Unique string characters Kata

https://www.codewars.com/kata/5a262cfb8f27f217f700000b/train/ruby

In this Kata, you will be given two strings a and b and your task will be to return the characters that are not common in the two strings.

For example:

solve("xyab","xzca") = "ybzc" 

--The first string has 'yb' which is not in the second string. 

--The second string has 'zc' which is not in the first string. 

Notice also that you return the characters from the first string concatenated with those from the second string.

More examples in the tests cases.

Good luck!


```
describe "Unique String Characters" do
  it "Basic tests" do    
    Test.assert_equals(solve("xyab","xzca"),"ybzc")
    Test.assert_equals(solve("xyabb","xzca"),"ybbzc")
    Test.assert_equals(solve("abcd","xyz"),"abcdxyz")
    Test.assert_equals(solve("xxx","xzca"),"zca")
  end
end
```
