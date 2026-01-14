
# DesignBuilder

- Uses EnergyPlus
# EnergyPlus

- EnergyPlus™ is a whole building energy simulation program that engineers, architects, and researchers use to model both energy consumption—for heating, cooling, ventilation, lighting and plug and process loads—and water use in buildings.
- Calculates loads using the [[HVAC Load Calculations#Heat Balance Method (HBM)|Heat Balance (HB) Method]] and, so, follows the current best practice per ASHRAE Handbook Fundamentals and meets the requirements of [[Title 24]].
- [EnergyPlus](https://energyplus.net/)

# eQUEST

- For [[HVAC Load Calculations]], eQUEST uses the DOE-2 calculation engine which does not use the ASHRAE [[HVAC Load Calculations#Heat Balance Method (HBM)|Heat Balance Method]] and, so, is not [[Title 24]]-compliant for load analysis. eQUEST relies on a pre-calculated, simplified weighting factor approach derived from ASHRAE principles, not the direct, hourly heat balance method that defines newer programs like EnergyPlus. 

# IES Virtual Environment
- [IES Virtual Environment | Design Sustainably with Ease](https://www.iesve.com/software/virtual-environment)

# OpenStudio

- Conceptually, OpenStudio SDK provides an Application Programming Interface (API) to access the ==EnergyPlus== modeling engine. This interface provides many benefits such as a stable, version-controlled interface, space typology abstractions that make it easier for end-users to model buildings, and language bindings in Ruby, Python and C-Sharp to make it more accessible to users familiar with these languages. The CLI is a powerful, cross-platform tool that allows users to run OpenStudio based workflows on supported architectures such as Linux, Windows and Mac.
# Trane Trace 3D Plus

- [TRACE® 3D Plus Full Energy & Economics/Load](https://shop.trane.com/ccrz__ProductDetails?sku=16XX&cartID=&store=&cclcl=en_US)


---
# Title 24 Compliance Software

Approved for the 2025 version of Title 24 as of January 2026:
## CBECC

- CBECC: California Building Energy Code Compliance (for Nonresidential and Multifamily buildings) software
- Built on top of EnergyPlus
- [Title 24 Nonresidential Compliance Software](https://bees.noresco.com/)

## EnergyPro

- [EnergySoft](https://www.energysoft.com/)
- Available for purchase are modules to perform HVAC load calculations for residential and commercial buildings

---
# See Also
- [[HVAC Load Calculations]]
- [[Operating Hours]]