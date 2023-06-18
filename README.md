- 👋 Hi, I’m @jhardy1216
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
jhardy1216/jhardy1216 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import matplotlib.pyplot as plt
import numpy as np

# Generate values for t
t = np.linspace(0, 50, 100)

# Calculate p(t) values
p = -0.0033*t**2 + 0.48*t + 34

# Plot the graph
plt.plot(t, p)
plt.title("Percentage of Total Workforce that is Female")
plt.xlabel("Years Past 1970 (t)")
plt.ylabel("Percentage (%)")
plt.grid(True)
plt.show()
