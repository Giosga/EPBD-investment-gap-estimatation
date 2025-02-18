# EPBD-investment-gap-estimatation
This repository contains the methodology and the background files for the paper titled "EPBD investment gap estimation".

The Energy Performance of Buildings Directive (EPBD, EU/2024/1275) indicates energy savings to be obtained in both the residential and non-residential sectors. For the expected energy savings by country (Table A3) we used the split indicated in the EPBD (Article 9), prescribing that by 2030 average primary energy use across residential buildings needs to decrease by at least 16 percent compared to 2020, with 55 percent of this reduction to happen in the 43 percent worst-performing buildings. For non-residential buildings (both public and private), the goal is to renovate 16% of the worst energy-performing stock. This difference is significant because the worst-performing buildings consume around twice as much energy as average buildings (European Commission, 2021). Despite non-residential buildings representing about a third of the EU building stock, the projected final energy savings  are 440 TWh in non-residential buildings, 255 TWh in the worst-performing residential buildings, and 208 TWh in the rest of the residential building stock, resulting in a 21% reduction in energy consumption across the entire EU building stock.

Using Eurostat’s figures on final energy consumption by households (2,893 TWh in 2020) and commercial and public sector (1,412 TWh in 2020), together with EPBD targets and our estimates on the energy consumption of worst-performing buildings allows computing the implicit energy savings and emission reductions prescribed by the EPBD by 2030 (Table A.3) . The figure of 903 TWh from 2024 to 2030 is in line with the European Scientific Advisory Board on Climate Change (ESABCC) assessment of required energy savings of 98 to 113 TWh/y in the residential sector and 36 to 47 TWh/y in the tertiary sector by 2030. 

To compute emissions savings, first we took the fuel mix of space heating and cooling and water heating, computing the share of each fuel for households (Figure 3) and extended it to all buildings. Then we weighed energy savings to the different fuels and multiplied by the emission factors for natural gas, diesel oil and kerosene and coal in Koffi et al, 2017 .

Weighting potential energy savings by the fuel mix for heating and cooling in all countries results in fuel-specific energy and emission savings.

Our estimate on the EPBD’s emission savings imply emission reductions for 133 Mt of CO₂eq between 2024 and 2030 at the EU level. While sizable, the emission reductions would fall short of the ESABCC’s recommendation of 29 Mt CO₂eq/y. However, if firewood was to be consider not to be carbon neutral and its emission factor was to be estimated at 0.420 (please see Koffi et al, 2017 ), then the potential emission reductions would be as high as 218 Mt CO₂eq or 31Mt CO₂eq/y, in line with the Advisory Board’s recommendations.


For costs, we used the 2019 report titled “Comprehensive study of building energy renovation activities and the uptake of nearly zero-energy buildings in the EU” (Ipsos and Navigant, 2019) published by the European Commission. The type of works considered under the umbrella of energy renovations cover both thermal insulation improvements and fuel switching (for the complete list please refer to the annex).  The report contains tables on primary energy savings obtained between 2012 and 2016 by country and relative average investment costs. The investment cost per lifetime energy saving of 1kWh was then calculated as investment/energy savings, inflating the investment costs with a synthetic price index - obtained from the average between the two Eurostat price indices "Construction producer prices or costs, new residential buildings" and “Maintenance and repair of the dwelling” for the 2015-2023 period. The average between the two indices was taken as there is no statistical price index for deep energy renovations. The type of works involved in deep renovations generally require interventions beyond the general repair and maintenance of dwellings but follow different dynamics than the price for construction works for new buildings.

The investment costs for deep renovations  are then multiplied per the EPBD-prescribed energy savings, while the current investments in energy renovations are assumed to be half the overall needs, in line with the Renovation Wave requirement for countries to double their renovation rate. So, for example, the estimated German energy savings for non-residential buildings are of 88 TWh by 2030 and the estimated investment cost for deep renovations per kWh is of €3.1, then the total investment need for non-residential buildings is of €273 bn or €39bn/y. Assuming that the current investments in energy renovations are half that figure we obtain the additional investment need of €19.5bn/y. The same computation is done for all types of buildings and countries. The EU figure is the sum of all countries.

Potential energy savings were computed from 2021 country-specific energy prices for gas, diesel oil and electricity. Firewood prices were assumed to be geographic-area specific. A uniform coal price of €0.032/kWh - the 2021 retail price in Poland - was assumed, while the price of district heating was assumed to the be minimum among all other country-specific fuel prices.  The fuel-mix of final energy consumption for space heating and cooling and water heating by county was used to weigh the energy savings. A uniform carbon price of €60/tCO₂ was also assumed, the price was multiplied by the relative potential emission reductions of the fossil fuels to be included in the ETS2. Multiplying the energy and carbon savings by the assumed prices gives the estimated energy savings in billion euros.



