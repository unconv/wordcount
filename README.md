# Word Counter in C

This is a simple C program that counts the number of occurences of unique words in a text file. I made it for a YouTube video while learning C.

## How to use
```console
$ gcc -o wordcount wordcount.c
$ ./wordcount test.txt
'very' occurs 3 times
'test' occurs 2 times
'counter' occurs 2 times
'This' occurs 1 time
'is' occurs 1 time
'a' occurs 1 time
'simple' occurs 1 time
'to' occurs 1 time
'the' occurs 1 time
'cool' occurs 1 time
'word' occurs 1 time
```

Note that the amount of data the code can process is limited by the following lines of code:

```c
#define MAX_WORDS 1024
#define MAX_TEXT_LENGTH 20000
```

You can tweak the numbers if you want to process more words.
