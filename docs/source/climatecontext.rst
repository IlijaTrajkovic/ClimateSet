Climate Context
===


.. _climatemodels:

What are climate models?
------------
A climate model is a complex computational representation of the Earth's climate system. These models simulate the interactions between various components of the Earth, including the atmosphere, oceans, land surface, ice, and other factors, to predict and understand climate patterns and changes over time. Climate models are important tools for studying the Earth's climate, making predictions about future climate conditions, and assessing the potential impacts of various factors such as greenhouse gas emissions, land use changes, and atmospheric composition.
What do they include?
Atmospheric Model: Simulates the behaviour of the Earth's atmosphere, including temperature, pressure, humidity, and wind patterns.

Ocean Model: Represents the behaviour of the world's oceans, including ocean currents, temperatures, and sea ice.

Land Surface Model: Simulates processes on land, such as vegetation dynamics, soil moisture, and land-atmosphere interactions.

Sea Ice Model: Represents the formation, melting, and movement of sea ice in polar regions.

Biogeochemical Model: Incorporates biological and chemical processes, including the carbon cycle, to simulate interactions between the atmosphere, oceans, and land.
 
These models use mathematical equations to describe the physical, chemical, and biological processes that occur in each component of the Earth system. They are run on powerful supercomputers, which still take a long time, sometimes even several months to simulate climate conditions over time spans ranging from years to centuries and are validated against historical climate data to ensure their accuracy and reliability.
What is their purpose?
Understanding Climate Processes: Models help scientists understand the fundamental processes driving climate variability and change.

Predicting Future Climate: By inputting different scenarios of human activities and natural processes, models can project future climate conditions under different circumstances.

Assessing Climate Impact: Models are used to assess the potential impacts of climate change on ecosystems, agriculture, water resources, and human societies.

Policy Decision Support: Climate models provide information to policymakers to make informed decisions about climate mitigation and adaptation strategies.
Types
ESMs and GCMs
GCMs and ESMs are both types of climate models used in climate research. They stand for General Circulation Models (GCMs) and Earth System Models (ESMs).
 
GCMs, or Global Climate Models, are complex computer simulations that represent Earth's climate system. These models integrate physical, chemical, and biological processes to simulate climate patterns, allowing scientists to study and make predictions about future climate conditions.
 
ESMs typically refer to Earth System Models, which are an advanced form of climate models that incorporate not only the atmosphere but also interactions with oceans, land, ice, and other components of the Earth system. They aim to simulate a more comprehensive representation of the Earth's climate.
The main difference between GCMs (Global Climate Models) and ESMs (Earth System Models) lies in their scope. GCMs primarily focus on the atmosphere, whereas ESMs consider a broader range of components, providing a more holistic understanding of the Earth's climate by incorporating interactions between the atmosphere, oceans, land, and other elements. In essence, ESMs build upon GCMs by including a more integrated representation of the Earth system, which is why we exclusively use ESMs in ClimateSet.
 
It's important to note that while climate models are powerful tools, they have limitations and uncertainties. Improving the accuracy of models requires ongoing research, refinement, and validation against observed climate data. One of the recent improvements, and the one we focus on in ClimateSet, is using ML algorithms (ClimaX, U-Net, ConvLSTM, etc.) to emulate these models using much less computing power and hopefully achieving better accuracy.


.. autosummary::
   :toctree: generated

   lumache
