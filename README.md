# A cool complex number proof that uses cosine identity!

## Proof:<br><br> $$\ z + \frac{1}{z} = 2\cos(\theta) \$$

### Step 1: Multiply both sides by $\ z \$
$$\
z \left( z + \frac{1}{z} \right) = z \cdot 2 \cos(\theta)
\$$
<br>
$$\
z^2 + 1 = 2 \cdot z \cos(\theta)
\$$

### Step 2: Completing the square
Rearrange the terms to complete the square:

$$\
z^2 - 2\cos(\theta)z + \cos^2(\theta) = -1 + \cos^2(\theta)
\$$

<br>

$$\
(z - \cos(\theta))^2 = -(1 - \cos^2(\theta))
\$$

<br>

Since  $$\ 1 - \cos^2(\theta) = \sin^2(\theta) \$$ , we have:

<br>

$$\
(z - \cos(\theta))^2 = -\sin^2(\theta)
\$$

### Step 3: Take the square root
Taking the square root of both sides, we get:

$$\
z - \cos(\theta) = \pm i \sin(\theta)
\$$

Thus:

$$\
z = \cos(\theta) + i \sin(\theta) \quad \text{or} \quad z = \cos(\theta) - i \sin(\theta)
\$$

### Step 4: Add $$\ z \$$ and $$\ \frac{1}{z} \$$
We know that $$\ z = \cos(\theta) + i \sin(\theta) \$$ and its reciprocal is $$\ \frac{1}{z} = \cos(\theta) - i \sin(\theta) \$$ because:

<br>

$$\ \frac{1}{a + bi} = \frac{a - bi}{a^2 + b^2} = {a - bi} \quad \text{if} \quad a^2 + b^2 = 1 \$$

<br>

Therefore:

<br>

$$\
z + \frac{1}{z} = \left( \cos(\theta) + i \sin(\theta) \right) + \left( \cos(\theta) - i \sin(\theta) \right)
\$$

$$\
z + \frac{1}{z} = 2\cos(\theta)
\$$

<br>

Thus, we have proven:

$$\
z + \frac{1}{z} = 2\cos(\theta)
\$$

### This proof uses the case where $$\ z = \cos(\theta) + i \sin(\theta) \$$, and it only holds true when the modulus(length) of the complex number is one.


## Visualization Proof:

[![visualization](https://raw.githubusercontent.com/OssieLin/complex-numbers-with-cosine-identity/main/visualization.gif)](https://www.geogebra.org/m/ajssj52s)[![visualization](https://raw.githubusercontent.com/OssieLin/complex-numbers-with-cosine-identity/main/visulization_different_modulus.gif)](https://www.geogebra.org/m/pn5jwprt)

