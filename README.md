# Mission-2030-Hackathon-Project

## Brief Introduction
Mission 2030 is a hackathon conducted by Ministry of Youth and Sports for solving problems meeting SGD - Sustainable Development Goals in Karabakh. We as a team of SunFace proposed the way of determining the best locations that are suitable for agrivoltaic solar panel construction. We introduced two Multi Criteria Decision Making (MCDM) methods - Analytic Hierarchy Process (AHP) and Technique for Order Preference by Similarity to Ideal Solution (TOPSIS). During two-months preparation, we collected some data from external resources (more details in the research paper) and manipulated to fit to a decision problem (or decision matrix) containing 985 alternatives - possible locations in Karabakh - with data of 6 criteria, namely Solar Potential, Landcover, Soil Texture, Soil Moisture, Slope, and Aspect.
## Installation
It is recommended to have necessary libraries - NumPy, Pandas, and MatPlotLib.

Use the package manager [pip](https://pip.pypa.io/en/stable/) to start installation.

```bash
pip install numpy pandas matplotlib
```
## Data Description
* Solar Potential - The power estimated with Direct Normal Irradiance, Diffuse Horizontal Irradiance, Wind Speed, Air Temperature, and Solar Azimuth Angle. Monthly average was taken for each location to formalize the whole data as one instance.
