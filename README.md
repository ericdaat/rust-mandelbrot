# Plotting the Mandelbrot set

This is implemented from the [O'Reilly Book "Programming Rust"](http://shop.oreilly.com/product/0636920040385.do).

Usage:

``` shell
cargo build --release
./target/debug/mandelbrot mandel.png 1000x750 -1.20,0.35 -1.0,0.2
```

This will produce an image like this one:

![mandel.png](mandel.png)
