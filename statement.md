Hello World!
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
        IF (CONDITION) THEN
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
        IF (CONDITION) THEN
            Console.WriteLine ("THIS IS " & CONDITION)
        ELSE
            Console.WriteLine ("THIS IS " & (CONDITION = TRUE))
        END IF
   End Sub
End Module
```



# Advanced usage

If you want a more complex example (external libraries, viewers...), see the [official documentation](https://tech.io/playgrounds/408/tech-io-documentation).
