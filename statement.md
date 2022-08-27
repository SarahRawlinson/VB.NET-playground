# h1 **Find my other projects on**
* [**GitHub**](https://github.com/SarahRawlinson) <br>
* [**itch.io**](https://sarahrawlinson.itch.io) <br>
* [**YouTube**](https://www.youtube.com/channel/UCZzctauCe1sxTTCsK93Tlmw) <br>

---
HELLO WORLD
```vb.net runnable
Imports System

Public Module modmain
   Sub Main()
     Console.WriteLine ("Hello World!")
   End Sub
End Module
```
IF

```vb.net runnable
Imports System

Public Module modmain
   Sub Main()

        DIM CONDITION AS BOOLEAN: CONDITION = TRUE
        IF CONDITION THEN
            Console.WriteLine ("THIS IS " & CONDITION)
        END IF
   End Sub
End Module
```

?[What is the variable 'CONDITION' in the code above?]
-[ ] Integer
-[ ] Double
-[x] Boolean
-[ ] Long


ELSE

```vb.net runnable
Imports System

Public Module modmain
   Sub Main()

        DIM CONDITION AS BOOLEAN: CONDITION = TRUE
        IF CONDITION THEN
            Console.WriteLine ("THIS IS " & CONDITION)
        ELSE
            Console.WriteLine ("THIS IS " & (CONDITION = TRUE))
        END IF
   End Sub
End Module
```

SELECT CASE

```vb.net runnable
Imports System

Public Module modmain
   Sub Main()

        DIM VALUE AS STRING: VALUE = "RED"
        SELECT CASE VALUE
            CASE "GREEN"
                Console.WriteLine ("VALUE IS GREEN")
            CASE "YELLOW"
                Console.WriteLine ("VALUE IS YELLOW")
            CASE "RED"
                Console.WriteLine ("VALUE IS RED")
            CASE "BLUE"
                Console.WriteLine ("VALUE IS BLUE")
            CASE ELSE
                Console.WriteLine ("VALUE NOT THE DEFAULT COLOUR")
        END SELECT
        
   End Sub
End Module
```

WHILE

```vb.net runnable
Imports System

Public Module modmain
   Sub Main()
        DIM NUMBER AS INTEGER: NUMBER = 10
        DIM COUNTER AS INTEGER: COUNTER = 1
        WHILE COUNTER <= NUMBER
            Console.WriteLine ("COUNTING - " & COUNTER)
            COUNTER = COUNTER + 1
        END WHILE
   End Sub
End Module
```
FOR

```vb.net runnable
Imports System

Public Module modmain
   Sub Main()
        DIM NUMBER AS INTEGER: NUMBER = 10
        FOR COUNTER AS INTEGER = 1 TO NUMBER STEP 1 'STEP 1 IS NOT NEEDED
            Console.WriteLine ("COUNTING - " & COUNTER)
        NEXT
   End Sub
End Module
```

FOR EACH

```vb.net runnable
Imports System

Public Module modmain
   Sub Main()
        DIM NUMBERS(10) AS INTEGER: NUMBERS = NEW INTEGER() {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
        FOR EACH I AS INTEGER IN NUMBERS
            Console.WriteLine ("COUNTING - " & I)
        NEXT 
   End Sub
End Module
```


# Advanced usage

If you want a more complex example (external libraries, viewers...), see the [official documentation](https://tech.io/playgrounds/408/tech-io-documentation).
