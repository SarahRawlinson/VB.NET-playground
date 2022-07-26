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
        DIM NUMBER AS INTERGER: NUMBER = 10
        DIM COUNTER AS INTERGER: COUNTER = 0
        WHILE COUNTER < NUMBER
            Console.WriteLine ("COUNTING - " & COUNTER)
            COUNTER = COUNTER + 1
        END WHILE
   End Sub
End Module
```



# Advanced usage

If you want a more complex example (external libraries, viewers...), see the [official documentation](https://tech.io/playgrounds/408/tech-io-documentation).
