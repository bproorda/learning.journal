[Home](https://bproorda.github.io/learning.journal/)

**Operators and Loops**

-   *Comparison and Logical Operators*

    -   *Comparison Operators*

        -   Used to compare the value in the script to what you expect or want
            it be.

        -   Returns a Boolean value of true or false

        -   == is equal to: examines to see if the two values are the same.

        -   != is not equal to: compares the two values to see if they are not
            the same

            -   This operator is not as specific as the strict version

            -   “1” == 1 would be true

            -   These operators ignore data type

        -   === strict equals to: compares values and data types to see if the
            two are the same

        -   **!==** strict not equals to: compares values and data types to see
            if the two are same

        -   \> greater than and \< less than

        -   \>= greater than or equal to and \<= less than or equal to

    -   *Logical Operators*

        -   Allow you to compare the result of more than one comparison operator

        -   Also returns a Boolean value.

        -   && Logical and: returns true only if both are true

        -   \|\| logical or: returns true as long as one is true

        -   ! logical not: this inverts the value of comparison operator

            -   (5\>2) = true

            -   !(5\>2) = false

-   *Loops*

    -   Loops check a condition, if it is true, then it will run a code block.

    -   The loop will continue indefinitely until the condition returns false

    -   Three main types

        -   For: used when you need the loop to run for a specific number of
            times, includes a counter.

        -   While: if you do not know the number of runs the loop need, using a
            while loop will use a condition. As long as the condition is true,
            it will keep running.

        -   Do While: the same as the while loop, but it will always run the
            code at least once.

        -   For loop example

            -   “\`\`\`for (var i = 0; i \< 10; i++) {document.write(i);\`\`\`”

            -   for(declare counter; counter condition; condition increment)

        -   While loop example

            -   “\`\`\`var i = 0; while (i \< 10) {document.write(i);
                i++;}\`\`\`”
