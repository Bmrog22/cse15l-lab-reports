<h2>Part One</h2>

For this lab report, I had to make a server called StringSearch that would accept strings as inputs to be added.

Here is the code that I used to create a server:

![Image](StringSearchCode.png)

Example of code running:

![Image](Test1.png)

In the above example, the method handleRequest is called. It is called with the argument add-message?s=Hello, which is important because this is the way the url must be written in order to print Hello. The field returnedString is updated to be "Hello\n", as in accordance with the add-message specification in the path.

Example of code running:

![Image](Test2.png)

In the above example, the method handleRequest is called again. The difference between this and the last one is that the returnedString is already "Hello\n" to start since it was changed the last time the method was called. Using the same logic as the previous example, the string is modified to be "Hello\nThis test was a huge success\n"

<h2>Part Two</h2>

The next part of the lab was to show one of the buggy codes that we fixed. I have chosen the following broken code because it was similar to a problem on my CSE12 quiz.
```
 static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
       newArray[arr.length - i - 1] = arr[i];
    }
    return arr;
  }
```

