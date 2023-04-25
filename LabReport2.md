# Lab Report 2 - Servers and Bugs (Week 3)

## Part 1
![Image](StringServer.PNG)
* Once our code is complete, the next step is to run it inside the terminal with commands.
* Open the terminal with ```Ctrl + ~```
* Type the following commands:
```javac Server.java StringServer.java```
```java StringServer 4005```
* This would be the ideal output shown below. 
![Image](shown.png)
* Here is me testing two test cases, named test1 and test2 respectively.
![Image](test1.PNG)
* Which methods in your code are called?
  In terms of the method, the part that is called is the ```String[] parameters = url.getQuery().split("=");
            String y;
            if(x != null)
                {
                    y = x + "\n" + parameters[1];
                    return y;
                }
            x = parameters[1];
            return x;
        } ```
* What are the relevant arguemnts to those methods, and the value of any relevant fields of the class?
   In terms of this class, the most relevant field for the argument is the ```<string>``` part of the ```/add-message?s=<string>```
* How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why?
   I believe that in terms of this specific example, as shown by the ```y = x + "\n" + parameters[1];```, the added messages are added onto the previous string in order to maintain the previous string as an output.
![Image](test2.PNG)
* Which methods in your code are called?
  In terms of the method, the part that is called is the ```String[] parameters = url.getQuery().split("=");
            String y;
            if(x != null)
                {
                    y = x + "\n" + parameters[1];
                    return y;
                }
            x = parameters[1];
            return x;
        } ```
* What are the relevant arguemnts to those methods, and the value of any relevant fields of the class?
   In terms of this class, the most relevant field for the argument is the ```<string>``` part of the ```/add-message?s=<string>```
* How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why?
   I believe that in terms of this specific example, as shown by the ```y = x + "\n" + parameters[1];```, the added messages are added onto the previous string in order to maintain the previous string as an output.

**Part 2**
