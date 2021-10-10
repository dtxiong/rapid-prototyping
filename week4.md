## [Home](https://dtxiong.github.io/rapid-prototyping/)

### Energy Capture

Our end goal is to determine a method to cook food and heat water using solar energy. One possible method will directly heat the food/pan using solar rays which are passed through a lens or reflected by a mirror. Another method would be to indirectly heat the food and water by converting the power into electricity first, then using the electricity to heat the water and food. 

This week, we did research in preparation for the pin-up, where we presented our thoughts to the other groups.  

The sun provides power to the Earth through radiation. The sun can be modeled as a black body, and the power it radiates at a given frequency follows the Planck formula closely. The atmosphere absorbs some of the light which hits the planet, especially at frequencies close to the resonant frequencies of water and CO2 molecules in the atmosphere. At the earth's surface, the average irradiance is 21.6 MJ/m^2 per day. (Research by Josh)

![Solar Radiation Spectrum](https://upload.wikimedia.org/wikipedia/commons/e/e7/Solar_spectrum_en.svg)

Using this figure, we adopted several approaches- from a Fresnel lens, to a parabolic mirror approximated by flat plates, to a linear Fresnel reflector.

For a traditional Fresnel lens, the sunlight would pass through the lens with an efficiency of about 0.82 [2]. Multiplying this by the average daily insolation and an area of 0.627m^2 (the size of a commercially available Fresnel lens) [3] gives a daily energy collection of approximately 11.1MJ. There are two main benefits to this design. First, the collection is very simple and requires little adjustment, which means more time can be spent optimizing the collection surface and heat transfer to the other systems in the project. Second, the collection surface can be positioned such that there is relatively even energy deposition across the surface, reducing losses. (Research and sketch by Calvin)

![Fresnel lens](https://calvinjc01.github.io/rapid-prototyping/week-4/fresnel_lens.png)

A parabolic trough solar concentrator would focus energy onto a beam situated above the trough. The general structure of this model would be a stretched out parabola, and the beam passes through the focal point. A possible concern we discussed is if the intensity of light is too high and could possible damage the collector. There would also be significant thermal losses at high temperatures from radiation (T^4), but this design would ideally minimize these losses by having the collection spread out rather than concentrated at a point. (Research and sketch by Haeri)


![Diagram](https://calvinjc01.github.io/rapid-prototyping/week-4/trough2.jpg)


The path of light focused by a parbolic lens is shown [here](https://www.desmos.com/calculator/e9mzko4wk1) (Developed by Joseph)

We also looked at the idea of tracking the sun. This will let us focus the sun rays on our target throughout the day. One possibility is a manual hinge that could be adjusted in the morning and afternoon. Other possibilities include open source libraries. 

Solar power vs time of day:

![Energy vs time of day, depending on orientation, tilt, tracking](https://www.eia.gov/todayinenergy/images/2014.11.19/main.png)

Tracking will help about 50 W at peak hours, 100 W before and after. The tracking does not need to be too accurate, because of the cosine dependence: 5 degrees of offset will still capture 99.6% energy. 

We looked at absorptive surface treatments specially designed for solar collection purposes to maximize the energy collected and minimize the energy lost from radiation as well as heat pipes to transfer energy from our collection surface to the storage and cooking systems. One initial thought is to use the number heat pipes to control how much energy is allocated to each system, which could allow for more collection during the day and cooking at a range of temperatures.

Separating the solar cooking surface from the collection surface would allow for more flexibility. That way, the sun rays would not have to go directly to the cooking surface, but instead to a collection surface, where the heat will be transferred to the cooking location. The energy storage team is looking into storage salts for this. They want to have temperatures of up to 450 degrees celsius. 

Next steps include:
- Given the numbers from the cooking and energy storage teams, figure out how large the energy collection system should be. 
- Figure out the cost of such a device. 
- Form a team to look into solar tracking. 
- Look into the heat collection surface, such as material, cost, and power transfer. 

