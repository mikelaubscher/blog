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

Whether your rain gauge is a cylinder, a cone, or an irregular decorative bottle, a rainfall of \(R\) millimeters means that a volume of water equal to \(R\text{ mm}\) times the top aperture area (\(A_{\text{top}}\)) has entered the gauge. The gauge's graduation marks already account for its conical volume. 

Therefore, to test if your gauge is accurate, you only need to:
1. Measure the diameter of the top opening.
2. Calculate the expected volume for a specific rainfall level (e.g., \(10\text{ mm}\), \(20\text{ mm}\)).
3. Measure and pour that precise volume of water into the gauge and see if it aligns with the mark.

---

### What You Need

* **Your rain gauge** (clean and dry).
* **A ruler or caliper** (to measure in centimeters).
* **A digital kitchen scale** (highly recommended for precision, measuring in grams).
* **Water** (at room temperature).
* **A calculator**.

> [!TIP]
> Why a kitchen scale? In the metric system, **\(1\text{ milliliter (mL)}\) of water weighs exactly \(1\text{ gram}\)**. Measuring volume with a kitchen scale is far more precise than trying to read a plastic measuring jug.

---

### The Metric Formulas

#### 1. Measure the Top Inner Diameter (\(D\))
Measure the **internal diameter** of the top opening of your gauge in centimeters (\(\text{cm}\)). Do not include the thickness of the plastic rim. If the opening is slightly oval-shaped, measure it in two different directions and take the average.

#### 2. Calculate the Calibration Volume (\(V\))
To test a target rainfall reading of \(R\) millimeters, the required water volume \(V\) (in milliliters or grams) is:

$$V = \frac{\pi \times D^2 \times R}{40}$$

Or, using a simplified decimal approximation:

$$V \approx 0.07854 \times D^2 \times R$$

Where:
* \(V\) = Volume of water needed in **milliliters (mL)** (which equals **grams** on your scale).
* \(D\) = Inner diameter of the top opening in **centimeters (cm)**.
* \(R\) = The target rainfall reading you want to test in **millimeters (mm)**.

---

### Step-by-Step Testing Procedure

1. **Pick your test points:** Choose 3 or 4 points on the gauge scale to test (e.g., \(5\text{ mm}\), \(15\text{ mm}\), and \(30\text{ mm}\)).
2. **Calculate the water mass:** Run the formula for each test point. Let's do a quick example:
   * *Example:* If your gauge's top inner diameter (\(D\)) is \(10\text{ cm}\), and you want to test the \(15\text{ mm}\) mark (\(R = 15\)):
     $$V = 0.07854 \times 10^2 \times 15 = 117.81\text{ mL}$$
     You need exactly **\(117.8\text{ grams}\)** of water.
3. **Weigh the water:** Place a dry container on your kitchen scale, tare/zero the scale, and pour water in until the weight matches your calculated value (\(V\) grams).
4. **Pour and check:** Slow and steady, pour the water into your dry rain gauge. Make sure the gauge is standing perfectly level on a flat surface.
5. **Verify the reading:** Check the level of the water against the graduation marks on the gauge:
   * If it lines up perfectly with your target \(R\) value, that section of the scale is highly accurate.
   * If it reads higher or lower, your gauge is over-reporting or under-reporting.
6. **Repeat:** Empty and dry the gauge, then repeat the process for your other test points to verify accuracy across the entire scale.
