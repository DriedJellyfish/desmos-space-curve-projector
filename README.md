# Desmos Space Curve Projector

Welcome to the Desmos Space Curve Projector! This project enables the projection of 3D space curves into 2D, allowing users to explore different viewpoints and adjust the perspective of the projection.

## Live Demo

You can try out the project here: [Space Curve Projector](https://www.desmos.com/calculator/sfqittgikq)

## Features

- **3D Space Curve Projection**: Project 3D curves defined by the variable $r$, which is structured as:
  $r = [x(t), y(t), z(t)]$
- **Adjustable Viewpoints**: Change the angles $\phi_p$ and $\theta_p$ to alter the viewpoint in spherical coordinates.
- **Perspective Adjustment**: Modify the perspective factor $P$, where $P$ is defined as $\frac{1}{\rho}$. When $P=0$, the projection becomes parallel.

## Usage

1. Define your 3D space curve by specifying the functions for $x(t)$, $y(t)$, and $z(t)$.
2. Adjust $\phi_p$ and $\theta_p$ to explore the curve from different angles.
3. Set the perspective factor $P$ to modify how the curve is projected onto the 2D plane.

## Example

Here's an example of defining a space curve:

$r = [\cos(t), \sin(t), t]$

Then, you can adjust the angles and perspective as needed:

$\phi_p = \frac{\pi}{4}$
$\theta_p = \frac{\pi}{4}$
$P = 0.5$

## Contributing

Feel free to fork the repository and make improvements or modifications! Contributions are welcome.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
