## M DU PLESSIS (19930259)


[GitHub Link](https://github.com/mikkkeldp/green.git)

**Explanation**

I ran the ant command followed by the ant test command. By examining the `build.xml` file, I noticed that the output directory was set to bin. This lead me to the `all-test.html` file where I was presented with the output

``` html
expected:<[1*v+-1<0]> but was:<[1*v+-1<=0]>
```

 This indicated that my condition for test20 was incorrect. I then modified the condition and all the tests passed.
