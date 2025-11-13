> ｜ＣＳＳ｜<br />
> ｜ＩＳ　｜<br />
> ｜ＡＷＥ＄ＯＭＥ

```jasmin
invokestatic net/aurynj/Example.main:([Ljava/lang/String;)V
```

```typescript
const hrtsa = performance.now()
const afrId = window.requestAnimationFrame(hrtsb => { console.log(`${hrtsa} ${hrtsb}`) })
```

```html
<iframe frameborder="0" src="data:text/html;charset=utf-8,%3chtml%20contenteditable%3e"></iframe>
```

```rust
macro_rules! fizzbuzz_unit {
    ( $n:expr ) => {
        match ($n % 5, $n % 3) {
            (0, 0) => String::from("FizzBuzz"),
            (0, _) => String::from("Buzz"),
            (_, 0) => String::from("Fizz"),
            (_, _) => format!("{}", $n),
        }
    }
}

macro_rules! fizzbuzz {
    ( $m:expr, $o:expr ) => {
        for n in 1..=($m) {
            $o(fizzbuzz_unit!(n))
        }
    }
}

fn printer(s: String) {
    println!("{}", s)
}

fn main() {
    fizzbuzz!(100, printer)
}
```

:bookmark: :memo: :pushpin: :book: :books: :newspaper: :newspaper_roll: :label: :package: :gift: :card_file_box: :card_index_dividers: :card_index:
