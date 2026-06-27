# -Health-Facilities-Analytics-Dashboard
## Project Overview  This project presents an end-to-end Power BI analytics solution for evaluating healthcare facilities across multiple African countries.  The dashboards provide executive insights into healthcare infrastructure, facility performance, staffing, disease burden, vaccination coverage, and healthcare accessibility.  The objective is to enable data-driven decision-making for policymakers, healthcare administrators, and public health organizations.

## Dataset Used
[Access Power BI File](https://github.com/Innocent634/-Health-Facilities-Analytics-Dashboard/raw/refs/heads/main/Health%20Sector%20Mid%20Assignment.pbix)

[Access Excel File](https://github.com/Innocent634/-Health-Facilities-Analytics-Dashboard/raw/refs/heads/main/Health%20Data%20-%20Assignment%201.xlsx)

## Business Problem

Healthcare systems require timely insights to allocate resources effectively.

This project answers questions such as:

• Which countries have the highest patient visits?

• How are healthcare facilities distributed?

• Which countries have staffing shortages?

• How many facilities provide emergency care?

• What diseases account for the highest mortality?

• Which countries have the highest vaccination coverage?

• How does healthcare capacity compare across countries?

## Dashboards

Health Facilities Overview Dashboard
<img width="1001" height="552" alt="Health Facilities Overview Dashboard" src="https://github.com/user-attachments/assets/110a3942-fb72-4991-90cd-9c96c5e4feb7" />

Hospital Capacity & Performance Dashboard
<img width="1110" height="551" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/35e6b93d-b7ab-4e4f-890b-2ad0753bfa5b" />

## DAX Measures
Total Patients = SUM(Facilities[Annual Patients])

Total Staff = SUM(Facilities[Staff Count])

Total Bed Capacity = SUM(Facilities[Bed Capacity])

Vaccination Coverage % = AVERAGE(Facilities[Vaccination Coverage])

Recovery Rate = DIVIDE(SUM(Facilities[Recoveries]), SUM(Facilities[Cases Reported]))

Mortality Rate = DIVIDE(SUM(Facilities[Deaths]), SUM(Facilities[Cases Reported]))

## Key Insights

- Nigeria recorded the highest annual patient visits, indicating the greatest healthcare demand among the countries analyzed.

- Specialist hospitals and diagnostic centres account for a substantial share of healthcare facilities, while primary healthcare centres remain essential for broad community access.

- Public ownership represents the largest proportion of facilities, highlighting the government's role in healthcare delivery.

- Emergency units are available in approximately half of the facilities, suggesting opportunities to improve emergency preparedness.

- Vaccination coverage varies considerably between countries, indicating differences in public health outreach and healthcare accessibility.

- COVID-19 and malaria contribute significantly to the disease burden and mortality observed in the dataset.

- Countries with higher hospital bed capacity generally also have larger healthcare workforces, suggesting a relationship between infrastructure investment and staffing levels.

## Recommendations

Increase investment in emergency care facilities.

Expand vaccination programmes in lower-performing countries.

Improve staffing levels in underserved regions.

Strengthen disease surveillance systems.

Increase diagnostic and testing infrastructure.

Prioritise funding for countries with high patient-to-staff ratios.

Develop predictive analytics for disease outbreaks.

## Contact

[Email](egbeinnocent634@gmail.com)

[LinkedIn](www.linkedin.com/in/innocent-egbe-016a1015a)

[Chat on Whatsapp](https://wa.me/2348135342038)
