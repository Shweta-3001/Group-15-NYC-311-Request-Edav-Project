The project is divides into 5 parts
1. Introduction

NYC’s 311 service request data captures non-emergency complaints reported by residents across the five boroughs. These requests reflect issues such as noise, sanitation, housing, and public safety. This project analyzes complaint patterns, agency involvement, and borough-level differences, and visualizes the end-to-end flow of complaints.

2. Data

Key variables include:

borough – location of the complaint
complaint_bucket – grouped complaint type
agency_name – agency responsible
status – current resolution stage
latitude/longitude – geolocation

Missing values were checked, with incomplete or low-frequency categories grouped as “Other” or removed for clarity. Overall, the data is clean and suitable for categorical and flow-based analysis.

3. Results

Boroughs show distinct complaint patterns (e.g., Noise in Manhattan/Brooklyn, Sanitation in outer boroughs).

A few major agencies handle most of the requests (e.g., NYPD, DOT).

Status distribution shows many cases resolved quickly, while some categories remain open longer.

Interactions among borough × complaint × agency reveal clear clusters and workload concentrations.

4. Interactive Plot

An interactive parallel categories plot visualizes the flow:

Borough → Complaint Type → Agency → Status

It allows users to explore complaint pathways, identify dominant complaint types per borough, see which agencies handle specific issues, and observe how complaints are resolved.

5. Conclusion

NYC 311 complaints provide insight into resident concerns and agency performance. The analysis highlights borough differences, agency workloads, and common complaint pathways. The interactive flow plot offers an intuitive way to explore how complaints move through the system. Future work could examine trends over time or model response patterns.
