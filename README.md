# problem-solving-algorithmic-questions

![1st 20 Marker](https://github.com/user-attachments/assets/596b996d-645e-4c01-b510-258ddb55a0f0)

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
![2nd 20 Marker](https://github.com/user-attachments/assets/91d8d3c0-4685-46fa-9294-f23bc277369f)

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
