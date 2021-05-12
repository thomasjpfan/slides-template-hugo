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

# Fragments

- {{< frag c="One" >}}
- {{< frag c="Two" >}}
- {{< frag c="Three" >}}

---

# Fragments v2

{{% fragment %}} One {{% /fragment %}}
{{% fragment %}} Two {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

---

# This is a title

Both `fragment` and `frag` accept two additional parameters:

- `class`: sets the class of the wrapping `span` element
- `index`: controls the order in which sections will appear

---

## Cool equations

Displayed equations are wrapped in double-\$

$$\frac{n!}{k!(n-k)!} = \binom{n}{k}$$

Inline equations like $E=mc^2$ are wrapped in single-\$

---

# Closing

{{% grid middle %}}

{{< g 1 >}}
{{< figure src="images/icon.png" height="140px" >}}

```python
print("Hello world")
```

{{< /g >}}

{{< g 2 >}}

Thomas J. Fan
{{< social >}}
{{< talk-link slides-template-hugo >}}

{{< /g >}}

{{% /grid %}}
