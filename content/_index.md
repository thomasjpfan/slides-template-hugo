+++
title = "This is a title for a presentation With more than one line"
outputs = ["Reveal"]
+++

# This is a title for a presentation With more than one line
Thomas J. Fan

{{< social >}}
{{< talk-link slides-template-hugo >}}

---

> Creativity is just connecting things. When you ask creative people how they did something,
> they feel a little guilty because they didn't really do it, they just saw something.
> It seemed obvious to them after a while. That's because they were able to connect
> experiences they've had and synthesize new things.
>
> <cite>Steve Jobs</cite>

---

```go{1|2|3-5}
package main
import "fmt"
func main() {
    fmt.Println("Hello world!")
}
```

---

# This is cool

- {{< frag c="One" >}}
- {{< frag c="Two" >}}
- {{< frag c="Three" >}}

---

{{% section %}}

# Vertical slide 1

---

# Vertical slide 2

{{% /section %}}

---

## Cool equations

Displayed equations are wrapped in double-\$

$$\frac{n!}{k!(n-k)!} = \binom{n}{k}$$

Inline equations like $E=mc^2$ are wrapped in single-\$

---

# Closing

{{% grid middle%}}

{{< g 1 >}}
{{< figure src="images/icon.png" height="140px" >}}
1. [Cross Validation](#validation)
1. [Parameter Tuning](#parameter-tuning)
1. [Missing Values](#missing-values)
1. [Pandas Interoperability](#pandas)

{{< /g >}}

{{< g 1 >}}

Thomas J. Fan
{{< social >}}
{{< talk-link slides-template-hugo >}}

{{< /g >}}

{{% /grid %}}