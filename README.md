- š Hi, Iām @Vindhya91
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Vindhya91/Vindhya91 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

from windrose import WindroseAxes
import matplotlib.pyplot as plt

theta = [0, 60, 120, 180, 240, 300]
speed = [10, 0, 10, 40, 50, 40]

ax = WindroseAxes.from_ax()
ax.bar(theta, speed)
plt.show()
