+++
date = '2026-05-19T20:00:58+02:00'
draft = true
title = 'Rain Gauge Truth'
+++

{{< katex >}}

### You had how many mils?

So, there was rain last night. You check your gauge like everyone else at 06:00, 13 millimeters, great! Then, like any normal suburban resident, you log the evening's catch on your rain watchers group.

Now, how did someone 800m away get 12mm and how did someone else another 100m from them record 15mm?

Rain gauges come in all forms from myriad suppliers. Most will be a round opening feeding into a conical cylinder; convenient for handling and for more accurately being able to read the first few millimeters of a light shower scaling to the ability to capture a more torrential downpour, albeit with less accuracy.

Are they accurate? Have years of diligent data capture been soiled by the bum tooling of a less than standards compliant manufacturer in Jiujiang?

Let's seek to dust off the relevant sector of the brain, and maybe an old physics text book and see if we can clear things up.

---

### The Science: Why the Shape Doesn't Matter

Why do we measure rainfall in millimeters anyway? In a given area, it's the height water would rise during rainfall provided none was lost to the likes of run off, soaking or evaporation. What's important for us watchers is then the area of the top of our rain gauges. For this post I'll be assuming that the most common gauges have round openings.

![Rain gauge with condom container](/rain-gauge-truth-condom.webp)

Whether your rain gauge is a cylinder, a cone, or ...the above, a rainfall of \(R\) millimeters means that a volume of water equal to \(R\text{ mm}\) times the top aperture area (\(A_{\text{top}}\)) has entered the gauge. 

> [!TIP]
> For the sake of accuracy, let's use a kitchen scale. In the metric system, **\(1\text{ milliliter (mL)}\) of water weighs exactly \(1\text{ gram}\)**. Measuring volume with a kitchen scale is far more precise than trying to read a plastic measuring jug.

Therefore, to test if your gauge is accurate, you need to:
1. Measure the diameter (\(D\text{ mm}\)) of the top opening, maybe in 2 directions for an average in case it's not symmetrical. Then the radius is \(R = \frac{D}{2}\)
2. Fill your gauge to a marked level (e.g., \(10\text{ mm}\), \(20\text{ mm}\)).
3. Pour the contents of your gauge into a waiting container on a zeroed kitchen scale and record the mass in grams.

---

### The Calculations

We'll be using the formula for the volume of a cylinder (volume = base area x height):

$$V = (\pi \times R^2) \times H$$

This answer will be in cubic millimeters. 1 millilitre = 1000 cubic millilitres so,

$$V(\text{mL}) = V(\text{mm}^3) / 1000$$

Our go to formula can thus become:

$$V = \frac{(\pi \times R^2) \times H}{1000}$$

And, for millimeters:

$$H = \frac{V \times 1000}{\pi \times R^2}$$

Where:

* \(V\) = volume in **millilitres (ml)**
* \(R\) = radius in **millimeters (mm)**
* \(H\) = height in **millimeters (mm)**

---

### Let's crack on with an example


My test went as follows: I filled my gauge to it's markings of 5, 10, 14 and 30 millimeters, pouring the contents at each into a container zeroed on a scale. The mass from each level was recorded and the numbers were crunched using our go to formula for \(H\) (millimeters).

My gauge opening has a diameter of 129mm and thus a radius of 64.5mm.

At my gauge's 10mm mark I got, coincidentally, 100g on the scale. So, the true reading in millimeters is: 

$$H = \frac{100 \times 1000}{3.14159 \times 64.5^2} = 7.65\text{mm}$$

Oh dear! That's a 31% error. The results for all my measurements were as follows:

| Gauge (mm) | Volume (ml) | True Reading (mm) | Error (%) |
| :---:      | :---:       | :---:             | :---:     |
| 5          | 47          | 3.60              | 39        |
| 10         | 100         | 7.65              | 31        |
| 14         | 140         | 10.71             | 31        |
| 20         | 206         | 15.76             | 27        |

### Conclusion

Our gauges are not accurate. Far from it in fact. Maybe there's an accepted error for typical household gauges, but from what I could find, these errors might be around the 5% mark, accounting for gauge placement and wind.

What are we going to about this? Using the above formula, we can mark out true levels on our gauges and sleep easily once again.

Happy rain watching folks!