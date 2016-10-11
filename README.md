# gostrassen

Strassen's algorithm for matrix multiplication implementation in go

I built a simple implementation of Strassen's algorithm to test out the supposedly "better than n^3" matrix multiplication.

And let me tell you, **it works** !

Here is a sample output:

```
2016/10/11 08:21:38 matrices are 1024x1024, with values ranging from 0 to 99
2016/10/11 08:21:38 generation took 48.196168ms
2016/10/11 08:21:49 n^3 multiply took 10.584138743s
2016/10/11 08:21:51 divide and conquer took 2.233388127s
2016/10/11 08:21:51 matrices are the same
```

To get the code and test it out for yourself, you first need to make sure you have [golang](https://golang.org/) installed.

Then clone the repository

```
git clone https://github.com/louismerlin/gostrassen
```

and run the project!

```
cd gostrassen
go run gostrassen.go
```
