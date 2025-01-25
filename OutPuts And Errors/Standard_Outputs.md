The outputs shown on terminals directly after entering any command


```ls > a.txt```

writes ls command output in a file. redirects the output in a file
if files is already created it over writes its output

```echo "hello" > a.txt```
writes hello in a file , if content already exists it over writes it.

```echo "hello" >> a.txt```
it doesnot over writes the output. but it appends i existing output.

```echo "hello" 2> a.txt```
it writes the error message in a file.

1> -> where to return standard ooutput (1 is by default written)
2> -> where to return standard error




