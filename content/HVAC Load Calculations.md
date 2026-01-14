> [!summary]
> To perform load calculations in compliance with Title 24, generally, you should:
> - Use a calculation methodology from the ASHRAE Fundamentals Handbook (Heat Balance (HB method or Radiant Time Series (RTS) method). These are "the most current and scientifically derived means for estimating cooling load for a defined building space".
> 	- The HB method is suited to iterative software calculations
> 	- The RTS method is a simplified version of the HB method and can be performed with a spreadsheet
> - Use 68F and 75F for indoor design conditions
> - Use outdoor [[HVAC Outdoor Design Conditions|design conditions]] no more extreme than the 1st percentile for cooling (commercial buildings can use 0.5%) and 99th percentile for heating (in the Joint Appendix the 99th percent is not published and, so, you would need to use the Heating Winter Median of Extremes) 
> - A 10% safety factor is allowed for commercial buildings
> - In certain scenarios, there are other approaches - particularly for healthcare facilities. See Title 24 requirements below and read the code directly for exact information.

> [!tip]
> ASHRAE makes a strong argument that the type of load calculation methodology is still secondary in importance to the expertise and judgement of the engineer. So, at work, maybe don't sacrifice a large amount of time to [[corporate jargon|"reinventing the wheel"]] by developing a "better" calculation template than the one your employer provides you. It's a smart career move to "get with the program" when your employer indicates what they consider to be [[Engineering Judgment and Acceptable Accuracy|acceptable accuracy]]. If you feel strongly about it, you can conduct your independent study and develop an alternative on your own time - many people do this and it's a good sign of enthusiasm.

---
# Title 24 Requirements

## Commercial Buildings

### Section 140.4
PRESCRIPTIVE REQUIREMENTS FOR SPACE CONDITIONING SYSTEMS

(a) Sizing, equipment selection and type. 

1. Sizing and equipment selection. Mechanical heating and mechanical cooling equipment serving healthcare facilities shall be sized to meet the design heating and cooling loads as calculated according to the Subsection (b). Mechanical heating and mechanical cooling equipment serving hotel/motel buildings and nonresidential buildings other than healthcare facilities shall be the smallest size, within the available options of the desired equipment line, necessary to meet the design ==heating and cooling loads of the building, as calculated according to Subsection (b). ==

- Exception 1 to Section 140.4(a)1: Where it can be demonstrated to the satisfaction of the enforcing agency that oversizing will not increase building LSC. 
- Exception 2 to Section 140.4(a)1: Standby equipment with controls that allow the standby equipment to operate only when the primary equipment is not operating. 
- Exception 3 to Section 140.4(a)1: Multiple units of the same equipment type, such as multiple chillers and boilers, having combined capacities exceeding the design load, if they have controls, that sequence or otherwise optimally control the operation of each unit based on load.

(b) Calculations. In making equipment sizing calculations under Subsection (a), all of the following rules shall apply: 

1. Heating and cooling loads. Heating and cooling system design loads shall be determined in accordance with the procedures described in Subsection A or B below:

	- A. For systems serving hotel/motel buildings and nonresidential buildings other than healthcare facilities, ==the method in the 2017 ASHRAE Handbook, Fundamentals shall be used== or as specified in a method approved by the Commission. 
	- B. For systems serving healthcare facilities the method in the California Mechanical Code shall be used.

2. Indoor design conditions. Indoor design temperature and humidity conditions for comfort applications shall be determined in accordance with Subsection A or B below: 
	- A. For systems serving hotel/motel buildings and nonresidential buildings other than healthcare facilities, ==ASHRAE Standard 55 or the 2017 ASHRAE Handbook, Fundamentals Volume==, except that winter humidification and summer dehumidification shall not be required.
	- B. For systems serving healthcare facilities the method in the California Mechanical Code shall be used.

3. Outdoor design conditions. Outdoor design conditions shall be selected in accordance with Subsection A or B below: 
	- A. For systems serving hotel/motel buildings and nonresidential buildings other than healthcare facilities the design conditions shall meet the following: 
		- i. Outdoor design conditions shall be selected from Reference Joint Appendix JA2, which is based on data from the ASHRAE Climatic Data for Region X or the ASHRAE Handbook, Fundamentals Volume. 
		- ii. ==Heating design temperatures== shall be no lower than the 99.0 percent Heating Dry Bulb or the ==Heating Winter Median of Extremes values.== 
		- iii. ==Cooling design temperatures shall be no greater than the 0.5 percent Cooling Dry Bulb== and Mean Coincident Wet Bulb values. 
	- B. For systems serving healthcare facilities the method in Section 320.0 of the California Mechanical Code shall be used.

4. Safety factor. Calculated design loads based on 140.4(b)1 through 10 ==may be increased by up to 10 percent== to account for unexpected loads or changes in space usage.

---
## Residential Buildings (Single Family)

SUBCHAPTER 7 ==SINGLE-FAMILY RESIDENTIAL BUILDINGS== – MANDATORY FEATURES AND DEVICES 
### Section 150.0 
MANDATORY FEATURES AND DEVICES

(h) Space-conditioning equipment. 
1. Building cooling and heating loads. ==Building heating and cooling loads shall be determined using a method based on any one of the following==:
	- A. The ASHRAE Handbook, Equipment Volume, Applications Volume and Fundamentals Volume; or 
	- B. The SMACNA Residential Comfort System Installation Standards Manual; or
	- C. The ACCA Manual J. 

- Exception 1 to Section 150.0(h)1: Block loads, the total load for all rooms combined that are served by the central equipment, may be used for the purpose of system sizing for additions. 

1. Design conditions. Design conditions shall be determined in accordance with the following: 
	- A. For the purpose of sizing the space-conditioning (HVAC) system, ==the indoor design temperatures shall be 68°F for heating and 75°F for cooling. ==
	- B. Outdoor design conditions shall be selected from one of the following: 
		- i. Reference Joint Appendix JA2, which is based on data from the ASHRAE Climatic Data for Region X; or 
		- ii. The ASHRAE Handbook, Fundamentals Volume; or 
		- iii. The ACCA Manual J. 
	- C. The outdoor ==design temperatures for heating== shall be no lower than the 99.0 percent Heating Dry Bulb or the ==Heating Winter Median of Extremes values.== 
	- D. The outdoor ==design temperatures for cooling shall be no greater than the 1.0 percent Cooling Dry Bulb== and Mean Coincident Wet Bulb values.

---
## Multifamily Buildings
### Section 160.3
Mandatory Requirements for Space Conditioning Systems in Multifamily Buildings

(b) Dwelling unit space-conditioning and air distribution systems. 
1. Building cooling and heating loads. Building heating and cooling loads shall be determined using a method based on any one of the following, using cooling and heating loads as two of the criteria for equipment sizing and selection: 
	- A. The ASHRAE Handbook, Equipment Volume, Applications Volume and Fundamentals Volume; or
	- B. The SMACNA Residential Comfort System Installation Standards Manual; or 
	- C. The ACCA Manual J. 

	- Exception to Section 160.3(b)1: Block loads, the total load for all rooms combined that are served by the central equipment, may be used for the purpose of system sizing for additions. 
	- Note: Heating systems are required to have a minimum heating capacity adequate to meet the minimum requirements of the CBC. 
2. Design conditions. Design conditions shall be determined in accordance with the following: 
	- A. For the purpose of sizing the space-conditioning (HVAC) system, ==the indoor design temperatures shall be 68°F for heating and 75°F for cooling.==
	- B. Outdoor design conditions shall be selected from one of the following: 
		- i. Reference Joint Appendix JA2, which is based on data from the ASHRAE Climatic Data for Region X; or 
		- ii. The ASHRAE Handbook Fundamentals Volume; or 
		- iii. Reserved; or 
		- The ACCA Manual J 
	- C. The outdoor ==design temperatures for heating== shall be no lower than the 99.0 percent Heating Dry Bulb or the ==Heating Winter Median of Extremes values. ==
	- D. The outdoor ==design temperatures for cooling shall be no greater than the 1.0 percent Cooling Dry Bulb== and Mean Coincident Wet Bulb values.

### Section 170.2
Prescriptive Approach

(c) Space-conditioning systems. All space heating, space cooling and ventilation equipment shall comply with minimum Appliance Efficiency Regulations as specified in Sections 110.0 through 110.2 and the applicable requirements of Subsections 1 through 4. 

1. Sizing and equipment selection—common use areas. Mechanical heating and mechanical cooling equipment serving common use areas of multifamily buildings shall be the smallest size, within the available options of the desired equipment line, necessary to meet the design heating and cooling loads of the building, as calculated according to Subsection 2 below. 
	- Exception 1 to Section 170.2(c)1: Where it can be demonstrated to the satisfaction of the enforcing agency that oversizing will not increase building LSC energy use.
	- Exception 2 to Section 170.2(c)1: Standby equipment with controls that allow the standby equipment to operate only when the primary equipment is not operating. 
	- Exception 3 to Section 170.2(c)1: Multiple units of the same equipment type, such as multiple chillers and boilers, having combined capacities exceeding the design load, if they have controls that sequence or otherwise optimally control the operation of each unit based on load. 
2. Calculations—common use areas. In making equipment sizing calculations under Subsection (c)1, all of the following rules shall apply: 
	- A. Heating and cooling loads. Heating and cooling system design ==loads shall be determined in accordance with the method in the 2017 ASHRAE Handbook, Fundamentals Volume==, or as specified in a method approved by the Commission. 
	- B. Indoor design conditions. Indoor design temperature and humidity conditions for comfort applications shall be determined using ASHRAE Standard 55 or the 2021 ASHRAE Handbook, Fundamentals Volume, except that winter humidification and summer dehumidification shall not be required. 
	- C. Outdoor design conditions. Outdoor design conditions shall be selected from Reference Joint Appendix JA2, which is based on data from the ASHRAE Climatic Data for Region X or the ASHRAE Handbook Fundamentals Volume. ==Heating design temperatures shall be no lower than the 99.0 percent Heating Dry Bulb or the Heating Winter Median of Extremes values. Cooling design temperatures shall be no greater than the 0.5 percent Cooling Dry Bulb and Mean Coincident Wet Bulb values. ==
	- Exception to Section 170.2(c)2C: Cooling design temperatures for cooling towers shall be no greater than the 0.5 percent Cooling Design Wet Bulb values.

---
# Load Calculation Methods

> [!NOTE]
> Load calculation methods are presented in Chapter 18 of the ASHRAE Handbook Fundamentals. The following are key excerpts:
> 
> - This chapter presents ==two load calculation methods== that vary significantly from previous methods.
> - The first of the two methods is the heat balance (HB) method; the second is radiant time series (RTS), which is ==a simplification of the HB procedure.==
> - All load calculation inputs should be as accurate as reasonable, ==without using safety factors. Introducing compounding safety factors at multiple levels in the load calculation results in an unrealistic and oversized load.==
> - Variation in heat transmission coefficients of typical building materials and composite assemblies, differing motivations and skills of those who construct the building, unknown infiltration rates, and the manner in which the building is actually operated are some of the variables that make precise calculation impossible. Even if the designer uses reasonable procedures to account for these factors, ==the calculation can never be more than a good estimate of the actual load.==
> - ==Load estimating requires proper engineering judgment== that includes a thorough understanding of heat balance fundamentals.
> - ==This chapter is primarily concerned with a given space or zone in a building.== When estimating loads for a group of spaces (e.g., for an air-handling system that serves multiple zones), the assembled zones must be analyzed to consider:
> 	1. The simultaneous effects taking place; 
> 	2. Any diversification of heat gains for occupants, lighting, or other internal load sources; 
> 	3. Ventilation; and/or 
> 	4. Any other unique circumstances. 
> 	- With large buildings that involve more than a single HVAC system, simultaneous loads and any additional diversity also must be considered when designing the central equipment that serves the systems. 
> - All calculation procedures involve some kind of model; all models require simplifying assumptions and, therefore, are approximate.
> - ASHRAE research project RP-942 compared HB and RTS results over a wide range of zone types and input variables (Rees et al. 2000; Spitler et al. 1998). In general, ==total cooling loads calculated using RTS closely agreed with or were slightly higher than those of the HB method with the same inputs==. The project examined more than 5000 test cases of varying zone parameters. The dominating variable was overall thermal mass, and results were grouped into lightweight, U.S. medium-weight, U.K. medium-weight, and heavyweight construction. RTS does not account for energy transfer out of the space to the environment, and thus predicted higher cooling loads.
> - The ideal heating system provides enough heat to match the structure’s heat loss. However, weather conditions vary considerably from year to year, and heating ==systems designed for the worst weather conditions on record would have a great excess of capacity most of the time.== A system’s ==failure to maintain design conditions during brief periods of severe weather usually is not critical.== However, close regulation of indoor temperature may be critical for some occupancies or industrial processes. ==Generally, the 99% temperature values given in the tabulated weather data are used.== However, caution is needed, and ==local conditions should always be investigated==. In some locations, outdoor temperatures are commonly much lower and wind velocities higher than those given in the tabulated weather data.
> - The heat balance (HB) or radiant time series (RTS) methods are used to determine cooling loads of rooms within a building, but they ==do not address the plant size necessary to reject the heat.==
> - Procedures described in this chapter (ASHRAE Fundamentals Chapter 18) are the most current and scientifically derived means for estimating cooling load for a defined building space, but methods in earlier editions of the ASHRAE Handbook are valid for many applications. These earlier procedures are simplifications of the heat balance principles, and their use requires experience to deal with atypical or unusual circumstances. In fact, ==any cooling or heating load estimate is no better than the assumptions used== to define conditions and parameters such as physical makeup of the various envelope surfaces, conditions of occupancy and use, and ambient weather conditions. Experience of the practitioner can never be ignored.
> - - Although the TFM, TETD/TA, and CLTD/CLF procedures are not republished in this chapter, ==those methods are not invalidated or discredited. Experienced engineers have successfully used them in millions of buildings around the world.== 
> - The ==accuracy of cooling load calculations in practice depends primarily on the availability of accurate information and the design engineer’s judgment in the assumptions made in interpreting the available data. Those factors have much greater influence on a project’s success than does the choice of a particular cooling load calculation method.==
> - The primary benefit of HB and RTS calculations is their somewhat reduced dependency on purely subjective input. However, ==using the most up-to-date techniques in real-world design still requires judgment on the part of the design engineer== and care in choosing appropriate assumptions, just as in applying older calculation methods.
## Contemporary Cooling Load Calculation Methods
### Heat Balance Method (HBM)

- **History**: The heat balance procedure is not new. Many energy calculation programs have used t in some form for many years. The first implementation that incorporated all the elements to form a complete method was NBSLD (Kusuda 1967). The heat balance procedure is also implemented in both the BLAST and TARP energy analysis programs (Walton 1983).
- **Description**: Double-iterative calculation process for calculating the peak load on a single "design day". 
	- Loop 1 (The Hourly Loop): The computer looks at Hour 1. It guesses the surface temperatures, checks the heat balance, adjusts the guess, and repeats until Hour 1 balances. Then it moves to Hour 2.
	- Loop 2 (The Daily Loop): Once it finishes Hour 24, it checks: "Did the wall temperature at midnight match the wall temperature at the start of the day?" If not, it runs the entire 24-hour day again.
	- This continues until the temperature change between the start and end of the day is within a tiny tolerance (e.g., 1%). Generally, four or six surface iterations are sufficient to provide convergence.
- **Current Status**: ASHRAE's primary recommended method for computer-based calculations. Published in current ASHRAE Fundamentals Handbook as the foundational approach.
- **Applicability**: Required for detailed energy modeling and complex buildings. Forms the calculation engine for modern building simulation software.
- **Title 24 Use**: This is what approved compliance software (CBECC-Com, EnergyPlus-based tools) uses under the hood. Essential for performance-based compliance.
- **Best For**: Compliance modeling, detailed energy simulation, complex buildings, performance-based design.

---

### Radiant Time Series (RTS) Method

The radiant time series (RTS) method is a simplified method for performing design cooling load calculations that is derived from the heat balance (HB) method.

It effectively replaces all other simplified (non-heat-balance) methods, such as the transfer function method (TFM), the cooling load temperature difference/cooling load factor (CLTD/CLF) method, and the total equivalent temperature difference/time averaging (TETD/TA) method.

This method was developed to offer an approach that is rigorous, yet does not require iterative calculations, and that quantifies each component’s contribution to the total cooling load.

The RTS method is suitable for peak design load calculations, but it should not be used for annual energy simulations because of its inherent limiting assumptions. Although simple in concept, RTS
involves too many calculations for practical use as a manual method, although it can easily be implemented in a simple computerized spreadsheet, as shown in the examples. For a manual cooling load calculation method, refer to the CLTD/CLF method in Chapter 28 of the 1997 ASHRAE Handbook—Fundamentals.

- **History**: Introduced by ASHRAE in 2001 as a simplified derivative of the Heat Balance Method, specifically designed for manual calculations.
- **Description**: Uses time series to account for thermal mass and radiant/convective split of heat gains. Simplified enough for hand calculations while maintaining reasonable accuracy.
- **Current Status**: ASHRAE's recommended manual calculation method. Published in current ASHRAE Fundamentals Handbook as the preferred approach for non-computerized calculations.
- **Applicability**: Suitable for preliminary sizing, simpler buildings, and educational purposes. More accurate than legacy methods for manual calculations.
- **Title 24 Use**: Acceptable for prescriptive compliance calculations and preliminary equipment sizing.
- **Best For**: Equipment sizing estimates, understanding load calculation concepts, smaller projects, educational demonstrations.

---
### ACCA Manual J (Residential)

- **History**: Developed by the Air Conditioning Contractors of America (ACCA) as the industry standard for residential load calculations. Now in its 8th Edition and designated as ANSI/ACCA 2 Manual J.
- **Description**: Comprehensive room-by-room residential load calculation method that accounts for building envelope characteristics, insulation levels, window types and orientation, infiltration, occupancy, internal loads, and local climate conditions. Calculates both sensible and latent cooling loads as well as heating loads.
- **Current Status**: Required method for residential buildings under Title 24, Part 6. The code specifies "ACCA Manual J or an equivalent calculation method." Widely adopted as the residential industry standard.
- **Applicability**: Specifically designed for single-family homes, townhomes, and low-rise residential buildings. Used in conjunction with Manual S (equipment selection) and Manual D (duct design) for complete residential HVAC system design.
- **Title 24 Use**: Mandatory for sizing residential HVAC equipment in California. Required for building permits when installing new or replacement residential HVAC systems. Many California municipalities require Manual J reports as part of permit applications.
- **Best For**: All residential HVAC applications, single-family homes, residential equipment sizing, ensuring proper system capacity to avoid oversizing or undersizing issues.

---
## Historical Cooling Load Calculation Methods

The primary difference between the HB and RTS methods and the older methods is the newer methods’ direct approach, compared to the simplifications necessitated by the limited computer capability available previously.

- Transfer Function Method (TFM)
	- **History**: Developed in the 1970s as the first rigorous heat balance approach. Used in early energy modeling software like DOE-2.
	- **Description**: Applied transfer functions (mathematical series) to calculate heat transfer through building components over time. Computationally intensive, requiring computer calculation.

- Total Equivalent Temperature Difference (TETD) Method
	- **History**: Used from the 1960s through 1970s. One of the earliest systematic approaches to cooling load calculations.
	- **Description**: Applied weighted temperature differences to account for thermal storage effects. Manual calculation method that was cumbersome for complex buildings.

- CLTD/SCL/CLF Method 
	- (Cooling Load Temperature Difference/Solar Cooling Load/Cooling Load Factor)
	- **History**: Popular from the 1980s through early 2000s. Published in ASHRAE Fundamentals through the 2001 edition, then removed.
	- **Description**: Used pre-calculated factors and tables for different building components, orientations, and schedules. Simplified manual calculations but based on fixed assumptions.


> [!quote]
> Although the TFM, TETD/TA, and CLTD/CLF procedures are not republished in this chapter, those methods are not invalidated or discredited. Experienced engineers have successfully used them in millions of buildings around the world.

## Heating Load Calculation Methods

> [!quote]
> Calculation of design heating load estimates has essentially become a subset of the more involved and complex estimation of cooling loads for such spaces. The 1989 ASHRAE Handbook Fundamentals was the last edition to contain a chapter dedicated only to heating load.

Techniques for estimating design heating load for commercial, institutional, and industrial applications are essentially the same as for those estimating design cooling loads for such uses, with the following exceptions:
- Temperatures outdoor conditioned spaces are generally lower than maintained space temperatures.
- Credit for solar or internal heat gains is not included
- Thermal storage effect of building structure or content is ignored.

This simplified approach is justified because it evaluates worst-case conditions that can reasonably occur during a heating season. Therefore, the near-worst-case load is based on the following:
- Design interior and exterior conditions
- Including infiltration and/or ventilation
- No solar effect (at night or on cloudy winter days)
- Before the periodic presence of people, lights, and appliances has an offsetting effect

See ASHRAE Fundamentals Chapter 18 for complete details

---
# Software Tools

- Commercial Buildings
	- Load Calculation Software
		- Carrier [Block Load](https://www.carrier.com/commercial/en/us/software/hvac-system-design/))
			- Uses Radiant Time Series (RTS) method and Transfer Function Method (TFM)
		- Carrier [System Design Load](https://www.carrier.com/commercial/en/us/software/hvac-system-design/))
			- Uses Radiant Time Series (RTS) method and Transfer Function Method (TFM)
		- Chvac by Elite Software
			- Uses Radiant Time Series (RTS) method and Cooling Load Temperature Difference method (CLTD)
		- Right-CommLoad by Wrightsoft
			- Uses Radiant Time Series (RTS) method and Cooling Load Temperature Difference method (CLTD)
			- May require purchase of a larger commercial software bundle. Unknown.
		- [[Whole-Building Energy Simulation Software#Trane Trace 3D Plus|Trane Trace 3D Plus - Load Design Only]]
			- Built on top of [[Whole-Building Energy Simulation Software#EnergyPlus|EnergyPlus]] which uses the Heat Balance (HB) method
	- [[Whole-Building Energy Simulation Software]] with load calculation capabilities
		- Carrier [HAP]([HVAC Software: Streamline System Design with eDesign Suite | Carrier](https://www.carrier.com/commercial/en/us/software/hvac-system-design/))
			- Uses the heat balance method
		- [[Whole-Building Energy Simulation Software#DesignBuilder|DesignBuilder]]
			- Uses EnergyPlus and, by extension, the heat balance method
		- [[Whole-Building Energy Simulation Software#EnergyPlus|EnergyPlus]]
			- Uses the heat balance method
		- [[Whole-Building Energy Simulation Software#EnergyPro|EnergyPro]] 
			- Allegedly uses the Transfer Function Method (TFM).
		- [[Whole-Building Energy Simulation Software#IES Virtual Environment|IES Virtual Environment]]
			- Uses the heat balance method
		- [[Whole-Building Energy Simulation Software#OpenStudio|OpenStudio]]
			- Uses EnergyPlus and, by extension, the heat balance method
		- [[Whole-Building Energy Simulation Software#Trane Trace 3D Plus|Trane Trace 3D Plus - Whole Design Full Energy & Economics / Load]]
			- Built on top of [[Whole-Building Energy Simulation Software#EnergyPlus|EnergyPlus]] which uses the Heat Balance (HB) method


**11. Wrightsoft Right-Suite Universal**

- **Method**: ACCA Manual N (commercial) or ASHRAE methods (RTS, traditional)
- **Vendor**: Wrightsoft
- **Features**: Graphical interface, commercial and residential, integrated with CAD floor plans
- **Notes**: Better suited for small-to-medium commercial buildings
​

> [!NOTE]
> Design load calculations which follow the Heat Balance or Radiant Time Series methods may also be available as functionality included in [[Whole-Building Energy Simulation Software]].

---
# See Also
- [[HVAC Outdoor Design Conditions]]
- [[San Diego Weather Data]]
- [[Whole-Building Energy Simulation Software]]

**ASHRAE Technical Committee 4.1**

Ongoing development of load analysis is facilitated by ASHRAE Technical Committee 4.1: Load Calculation Data and Procedures 

- Scope: TC 4.1 is concerned with the identification and compilation of engineering data and the development of procedures for calculating heating, cooling, refrigeration, and ventilating loads of structures. 
- Mission Statement: To serve practitioners by advancing the data and procedures of load calculations.