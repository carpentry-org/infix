# infix

A sketch for an infix-to-prefix transformer in Carp (used for match).

It’s based on my sketchy recollection of something I’ve maybe seen in SICP,
and something I implemented years ago for zepto’s standard library.

It’s mostly instructional and I don’t recommend you actually use it.

## Usage

After loading `infix.carp`, you’ll be able to use it like this:

```clojure
(infix 10 * 5 + 3 / 12 pow 2)
; will transform into (+ (* 10 5) (/ 3 (pow 12 2)))
```

<hr/>

Have fun!
