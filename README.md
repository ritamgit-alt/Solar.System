## Visualize The Solar System

First thought to simply use the 3D Scatter plot by creating custom size markers for the Sun and planets. However, this was not ideal as the markers stayed the same size when zoomed in or out.

This led to unwanted effects such as Saturn’s rings inside the planet and the Sun engulfing all rocky inner planets once zoomed out. This meant that I had to find a different solution to display the Sun and the planets.

Fortunately, Plotly also offers a 3D surface plot that I could use for my celestial objects. However, this required drawing several spheres, each different in size and colour.
