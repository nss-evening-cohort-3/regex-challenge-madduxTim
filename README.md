# REGEX Challenge

### Goal

This lite exercise will help you gain practice in using regular expressions. While all problems require you to provide the proper regex, some will require you to also provide additional information or research the internet.

### Directions

It's recommended that the stude uses https://regex101.com/ when attempting to solve the problem set. Copy & paste the provided text into the "TEST STRING" section of the regex101 url.

### Exercises

1. Provide two regexes that matches `yes yes yes` but not `no no no`
2. Provide a regex that matches valid phone numbers with the forms `678-123-1122` and `(678) 123-1122` while still allowing symbols to be optional. HINT: Research the rules around valid phone numbers.
3. Provide a regex that matches URLs like `https://regex101.com`, `http://facebook.com` and `https://www.godaddy.com` but not `https://msdn.microsoft.com`. (Trailing `/` should be allowed and optional)
4. Provide a regex that matches dates with the format: `Wed Aug 11, 2013`.
5. Provide a regex that matches dates with the format: `MM/DD/YYYY` and `DD/MM/YYYY`.
6. Provide a regex that matches `function returnOne() {return 1;}` and captures the value returned.
7. Provide a regex that matches `List<int> my_List = new List<int>();` and captures the variable name.
8. Provide a regex that matches `Billy Jean` but not `billy jean`
9. Provide two regexes that matches `NSS Evening Cohort 3` and captures "Cohort 3".
10. Provide a regex that matches the following C# code and captures the property names.

```c#
public class Part
{
    public string PartName { get; set; }
    public int PartId { get; set; }
}
```
