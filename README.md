<h1> Projectile Motion — Slingshot Physics Simulation</h1>

<p>
An interactive projectile motion simulation inspired by slingshot-based mechanics,
implemented from scratch using <strong>HTML5 Canvas</strong> and custom numerical solvers.
The project compares integration schemes while modeling gravity, quadratic drag,
wind interaction, and collision dynamics.
</p>

<hr/>

<h2> Features</h2>

<ul>
  <li><strong>Numerical Integrators</strong>
    <ul>
      <li>Semi-Implicit (Symplectic) Euler</li>
      <li>Velocity Verlet</li>
      <li>RK4 (4th-order Runge–Kutta)</li>
    </ul>
  </li>
  <li><strong>Physics Modeling</strong>
    <ul>
      <li>Constant gravitational acceleration</li>
      <li>Quadratic aerodynamic drag</li>
      <li>Wind-relative velocity effects</li>
      <li>Impulse-based collision response</li>
      <li>Material-based structural damage</li>
    </ul>
  </li>
  <li><strong>Real-Time Diagnostics</strong>
    <ul>
      <li>Kinetic, Potential, and Total Energy tracking</li>
      <li>Flight time measurement</li>
      <li>Adjustable physical parameters (g, ρ, Cd, mass)</li>
    </ul>
  </li>
  <li><strong>Gameplay System</strong>
    <ul>
      <li>Multi-level progression</li>
      <li>Trajectory preview</li>
      <li>Score and shot tracking</li>
    </ul>
  </li>
</ul>

<hr/>

<h2>🧮 Governing Equation</h2>

<p>
The projectile dynamics are governed by:
</p>

<p>
<em>m dv/dt = mg − (1/2) ρ Cd A |v<sub>rel</sub>| v<sub>rel</sub></em>
</p>

<p>
where v<sub>rel</sub> = v − v<sub>wind</sub>. Drag is quadratic in velocity,
making the system non-conservative and suitable for integrator comparison.
</p>

<hr/>

<h2>🚀 Run Locally</h2>



<h2>📄 License</h2>

<p>MIT License (or your preferred license)</p>
