# Terra-Data-Globe
🌍 3D Globe Viewer using NASA Terra Satellite Data

This project is a 3D interactive globe that visualizes real satellite imagery from NASA's Terra satellite, using WebGL and Three.js
. Terra's data provides high-resolution, near-real-time views of Earth — including snow cover, land changes, vegetation, and more.

🛰️ Why Terra?

The Terra satellite is part of NASA’s Earth Observing System and captures crucial global data across land, atmosphere, and oceans. This globe uses imagery from Terra’s MODIS sensor to display features like:

True-color Earth surface imagery

Snow and ice cover

Environmental overlays (e.g., night lights, vegetation)

🌐 Why a 3D Globe?

A 3D globe offers a more intuitive and accurate way to explore Earth data than flat maps:

Preserves geographic proportions (no map distortion)

Enables real-world navigation with zoom and rotation

Makes global datasets easier to understand spatially and temporally

🛠 How to Use

1. Clone/download the repo

2. Run with a local HTTP server:

    python -m http.server


3. Open .html in your browser

Use the interface to:

Change date and imagery layers

Add overlays with opacity controls

Hover to read latitude and longitude

Export snapshots

⚠️ Note: Requires a local or hosted HTTP server (not file://) due to NASA GIBS CORS policy.
