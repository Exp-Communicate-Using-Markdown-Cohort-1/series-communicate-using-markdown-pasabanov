# Header 1 example
## Header 2 example
### Header 3 example
#### Header 4 example
##### Header 5 example
###### Header 6 example

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

```julia
function mandelbrot(a)
    z = 0
    for i = 1:50
        z = z^2 + a
    end
    return z
end

for y = 1.0:-0.05:-1.0
    for x = -2.0:0.0315:0.5
        abs(mandelbrot(complex(x, y))) < 2 ? print("*") : print(" ")
    end
    println()
end
```

- [x] List syntax is required
- [x] This item is complete
- [ ] This item is not complete
