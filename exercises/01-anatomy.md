# Exercise 2 — Bug Hunt Write-Up

`src/BrokenHello.java` contains **four** deliberate errors. Fix them all, get the program running, then fill in this table.

Write the explanations **in your own words.** Copying the error message back is not an explanation.

| # | Error message Java gave you | What was actually wrong | How you fixed it |
|---|---|---|---|
| 1 |I fixed the mistakes without running thr program first|Line 12 was missing a semicolon at the end |I added a semicolon|
| 2 |I fixed the mistakes without running thr program first|The public class was missing a closing bracket|I added the closing bracket on line 15|
| 3 |I fixed the mistakes without running thr program first|Main on line 11 is capitalized|I made the word Main lowercase again|
| 4 |I fixed the mistakes without running thr program first|In the public class brokenHello, broken should be capitalized|I switched brokenHello to BrokenHello and capitalized both words in the class name|

---

## Reflection

**1. Which error was hardest to find? Why?**

public class ErrorResponseOne {
    public static void main(String[] args) {
        System.out.println("The missing curly bracket on line 15 because it was at the end and I did not pay much attention to it initially.");
    }
}

**2. Did fixing one error make others disappear? What does that tell you about how the compiler reports problems?**

public class ErrorResponseTwo {
    public static void main (String[] args){
        System.out.println("I fixed the mistakes without running thr program first so I don't know sorry.");
    }
}

**3. In your own words: what is the difference between a syntax error and a logic error?**

public class ErrorResponseThree {
    public static void main (String[] args){
        System.out.println("If this was part of the errors that I was supposed to check by initially running the code, I don't know but I'm guessing syntax would be a incorrect symbol added or subtracted like a missing semicolon or an added curly brace, while a logic error would be incorrect code like incorrect class names or missppelling of certain commands, etc.");
    }
}
