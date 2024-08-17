# problem-solving

```
Procedure ConcurrentRunningAverage
    Initialize sum <- 0
    Initialize count <- 0
    Initialize lock <- new Lock()

    Function ProcessNumber(number)
        lock.acquire()
        sum <- sum + number
        count <- count + 1
        average <- sum / count
        lock.release()
        Print(average)
    End Function
End Procedure
```

```
Procedure ExtractUniqueAlphabets(word)
    Initialize uniqueAlphabets <- new Set()

    word <- word.toLowerCase()

    For each character in word
        If character is an alphabet
            uniqueAlphabets.add(character)
        End If
    End For

    uniqueAlphabetsList <- uniqueAlphabets.toList()

    Print(uniqueAlphabetsList)
End Procedure

```
