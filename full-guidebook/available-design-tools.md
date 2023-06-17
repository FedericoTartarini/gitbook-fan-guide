# Available design tools

## CBE Thermal Comfort Tool <a href="#_toc137735028" id="_toc137735028"></a>

A helpful tool to find comfort zones at elevated air speeds according to ASHRAE 55 methodology is the [CBE Thermal Comfort Tool](https://comfort.cbe.berkeley.edu/), an online tool.

The user enters temperature, air speed, humidity, metabolic rate and clothing level into the tool to calculate results including PMV, SET, and ASHRAE 55 compliance as well as generating the graph below in Figure 57. The blue shaded area represents the ASHRAE 55 compliance comfort zone while the red mark shows where the user inputs are relative to the comfort zone. The tool also supports compliance to the European thermal comfort standard EN 16798; however, this standard does not include the calculation adjustment for convection effect included on ASHRAE 55, being less favorable to estimate increased air speed effect.

![Figure 57. Example of the CBE Thermal Comfort Tool, showing user inputs, psychometric chart, and results.](<../.gitbook/assets/0 (41).png>)

The CBE Thermal Comfort Tool also takes into account elevated air speeds. As the air speeds increase, the range of acceptable temperatures increases, and the blue shaded area shifts to the right. Using higher air speeds allows the user to ASHRAE 55 compliance at higher cooling temperature setpoints. Note that Standard 55 has a maximum average air speed permitted in the case that occupants do not have control over the system (0.8 m/s \[160 fpm]). This can be specified as an input in the Thermal Comfort Tool as well. To support this functionality, users can also select the “air speed vs. operative air temperature” mode from the drop-down menu above the chart to view the comfort range and results in terms of air speed and temperature (see Figure 58).

![Figure 58. Example of the CBE Thermal Comfort Tool showing air speed vs. operative air temperature mode.](<../.gitbook/assets/1 (11).png>)

## CBE Ceiling Fan Design Tool <a href="#_toc137735029" id="_toc137735029"></a>

To help determine optimal ceiling fan arrangements, you can use the free online [CBE Ceiling Fan Design Tool](https://centerforthebuiltenvironment.github.io/fan-tool/). The tool allows users to input room dimensions, design air speed ranges, and other parameters to determine optimal ceiling fan placement. The tool includes characteristics for a range of default ceiling fan options, or users can input specific details of other ceiling fan models to determine appropriate layouts. In addition to providing recommended fan layouts, the tool provides estimates for air speeds (minimum, average, and maximum), cooling effect (minimum and maximum), and air speed uniformity for each proposed layout (see Figure 59). The tool also provides visualizations for the overall ceiling fan plan for the space, as well as ceiling fan “cell” plan (see Figure 60) and section showing details on air speeds within each fan cell, and ideal mounting heights (see Figure 61).

The CBE Ceiling Fan Design Tool takes into account many of the design factors discussed in the previous sections. For more details on how the tool functions, please consult the online [User Guide](https://github.com/CenterForTheBuiltEnvironment/fan-tool/wiki/User-Guide). However, it is important to highlight that the tool is mainly applicable for uniform design intent and does not consider the room layout or non-uniform demands that should be taken into consideration by the designer.

![Figure 59. Example CBE Ceiling Fan Design Tool outputs.](<../.gitbook/assets/2 (7).png>)



![Figure 60. Example cell plan from CBE Ceiling Fan Design Tool.](<../.gitbook/assets/3 (16).png>)

![Figure 61. Example cell section from CBE Ceiling Fan Design Tool.](<../.gitbook/assets/4 (18).png>)

## Modelling, simulation, and energy saving estimation <a href="#_toc137735030" id="_toc137735030"></a>

To demonstrate the energy savings potential of fans in a whole building energy model, simply increase the cooling setpoint based on the estimated cooling effect for the considered scenario, while maintaining the same heating setpoint. Models will generally show approximately a 10 % reduction in total HVAC savings per 1 °C increase in cooling setpoint \[5 % per 1 °F], through a combination of cooling and associated transport energy savings (e.g., fan), as well as heating energy savings. The reason for heating energy savings is that when the cooling setpoint is higher, temperatures in the space tend to be warmer during the day than without fans, and this reduces morning warmup (and sometimes reheat) energy consumption. For rapid estimates, the [CBE Setpoint Savings Calculator](https://energy-calc-2wmjqjatpa-uc.a.run.app/) will estimate the energy savings for a particular location in the USA for a commercial office building based on EnergyPlus models. Figure 62 presents an example of the calculation.

![Figure 62. Example of the Setpoint Energy Saving Calculator](<../.gitbook/assets/5 (18).png>)
