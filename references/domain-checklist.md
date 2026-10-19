# Domain review checklist

Apply only relevant checks. Record missing information as questions, not invented facts.

## Gear dynamics and dynamic contact

- Define geometry, tooth counts, module convention, pressure/helix angles, face width,
  modifications, materials, loads, speed, and boundary/initial conditions.
- Define degrees of freedom, coordinate frames, signs, mesh excitation, mesh stiffness,
  damping, backlash, transmission error, friction, contact loss, and load sharing.
- State contact formulation and applicability (Hertz/non-Hertz, elastic/plastic),
  contact pressure, stresses, penetration, convergence and discretization sensitivity.
- Distinguish static/dynamic transmission error and static/dynamic contact response;
  give spectral conventions, sampling, transient removal, and mesh-frequency definitions.
- Separate verification, validation, calibration, and sensitivity analysis.

## Multiphysics and thermal lubrication

- Specify coupling direction, transferred quantities, time scales, numerical scheme,
  convergence criteria, and mass/energy consistency across interfaces.
- Distinguish EHL, TEHL, mixed and boundary lubrication; justify regime assumptions.
- Document lubricant viscosity-pressure-temperature and density laws, rheology,
  cavitation treatment, starvation, inlet/outlet and thermal boundary conditions.
- Report film thickness definition, roughness and lambda-ratio convention, heat
  generation/partition, flash/bulk temperature distinction, and material dependence.
- Discuss limitations from rigid/isothermal/Newtonian/fully flooded assumptions
  when those assumptions are actually used.

## Surface texturing

- Define shape, depth, size, spacing, area fraction, orientation, placement and scale
  relative to contact dimensions and film thickness, including manufacturing feasibility.
- Compare against a matched untextured baseline under consistent operating conditions.
- Discuss discretization, cavitation/mass conservation, stress concentration, friction,
  film formation, thermal response, and competing effects where supported by evidence.
- Limit optimum-design claims to the sampled design space and operating envelope.

## Reporting

Use consistent SI units and a nomenclature table; identify dimensional/dimensionless
quantities. Quantify improvements with a stated baseline and denominator. Report
uncertainty/repeatability or explain its absence. Cite only verified sources; separate
correlation from causation and avoid unsupported claims of universal superiority.
