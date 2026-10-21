# Supercharger Boost Calculator

**Live demo:** https://jtdyal.github.io/fluffy-system/

Mobile-first, single-file web calculator (`index.html`, no build step, no dependencies).
Open the file in a browser or host it with GitHub Pages.

Inputs: engine displacement (cc/ci), supercharger displacement (cc/ci), pulley size (in).
Outputs: engine air requirement per rev, pulley ratio (7" / pulley), free-air displacement per revolution,
theoretical boost, pressure ratio, a tachometer (engine RPM inside, supercharger RPM outside)
and an airflow gauge in m^3/hr.

Theoretical boost = 14.7 x (free-air displacement per revolution / engine air requirement per revolution) - 14.7. Pressure ratio = 14.7 / boost (shown as a dash when boost is 0 or negative).
