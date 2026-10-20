# Supercharger Boost Calculator

Mobile-first, single-file web calculator (`index.html`, no build step, no dependencies).
Open the file in a browser or host it with GitHub Pages.

Inputs: engine displacement (cc/ci), supercharger displacement (cc/ci), pulley size (in).
Outputs: engine air requirement per rev, pulley ratio (7" / pulley), free-air displacement,
theoretical boost, pressure ratio, a tachometer (engine RPM inside, supercharger RPM outside)
and an airflow gauge in m^3/hr.

Pressure ratio is computed as (boost + 14.7) / 14.7 (absolute manifold pressure over atmospheric).
