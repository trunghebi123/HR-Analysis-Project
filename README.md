# HR ANALYTICS PROJECT

## REQUIREMENTS
- **Understanding Employee Work Preferences:** Compare In-Office vs WFH ratios, specifically focusing on Monday and Friday patterns to help HR optimize office policies.
- **Monitoring Sick Leave Trends:** Track daily sick leave percentages to detect potential outbreaks (like Covid) early, allowing HR to implement safety precautions and backup plans.

## DATA GATHERING & TRANSFORMATION
The [Raw Data](./Attendance-Sheet-2022-2023.xlsx) is an attendance sheet for 3 months (April - June 2022). It includes **_employee codes_**, _**names**_, and their daily attendance status (Present, Work From Home, Sick Leave,...) recorded in a wide matrix format.
- Unpivoting: Using Excel's Power Query to transform date columns into rows. This changes the data from a wide format to a long list (Employee - Date - Status).
- Adding a "Day of Week" column to help analyze working patterns on specific days like Mondays and Fridays.

## DASHBOARDING
- KPI Cards (Total Employees, Total Working Days, % Presence, % WFH , % Sick Leave): These provide an immediate "Health Check" of the company. HR can see at a glance if the overall attendance is stable or if there are unusual spikes in absences.
- Presence and Work From Home (WFH) Trend: This is an important insight that HR care a lot. By looking at the ratio, we can see that Friday (12.46%) has the highest remote work rate, confirming the need for flexible Friday policies.
- Sick Leave Trend with Alert Level: I added an Alert Level at 2.00%. This acts as an "Early Warning System." Any peak above this red line signals HR to investigate potential outbreaks or health issues immediately.
- Top 10 Employees by Sick Leave Rate: This table helps identify specific individuals who might need support or health intervention, ensuring no one is left behind in the wellness program.

## RECOMMENDATIONS
- Optimizing Hybrid Work Policy: Since Friday has the highest WFH rate (12.46%), HR should formalize a "Flexible Friday" policy. This ensures employees feel supported while maintaining office operations with a leaner onsite team.
- Health Alert Response: The 2.00% Alert Level in the Sick Leave trend should be integrated into an automated notification system. If this threshold is crossed (as seen in early June), HR should immediately trigger health safety protocols or internal surveys to check for potential outbreaks.
- Employee Support Program: For the Top 10 Employees with high Sick Leave rates, HR should conduct "Care Calls" or wellness check-ins. The goal is to understand if they are facing long-term health issues or burnout, providing support rather than just monitoring attendance.
- Space Management: Since presence drops significantly towards the end of the week (Thursday & Friday), the company can save energy costs (electricity, AC) by closing certain office zones on these days.
