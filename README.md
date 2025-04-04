# The Issues Surrounding Aging Populations in Rural Communities in Nova Scotia
:sparkles: *Lindsay Gorman* :sparkles: 


## Executive Summary

Nova Scotia’s rural communities face significant aging-related challenges. Some of these challenges include limited access to healthcare, social isolation, lack of public transportation, and a shortage of accessible housing and long-term care facilities. Seniors often travel long distances for medical care, experience mental health impacts due to isolation, and struggle with costly, insufficient transit options. Many rural homes lack accessibility features, while long-term care waitlists force seniors to remain in unsuitable housing or relocate.

READ MORE: https://github.com/lindsaygorman1/bsad482project/blob/52730c463446de9061aaa17e29fe4c731ad1add8/Background

## Key Performance Indicators (KPIs)

1. Healthcare Accessibility: Percentage of seniors  with access to healthcare facilities within a 30-minute drive. Studies show that better access to healthcare is associated with improved health outcomes. If seniors can reach facilities quickly, they are more likely to attend regular check-ups, follow-ups, and preventive care. This reduces emergency visits and improves long-term health management (Andersen & Davidson, 2013).

    Technical details:
    
    * Range: 1-100
    * Frequency: Annually

2. Social Isolation Rate: Percentage of seniors in rural communities who report feeling socially isolated or lonely. Social isolation has been linked to increased risks of cognitive decline, mental health disorders, and chronic illnesses. Seniors with strong social connections tend to live longer, healthier lives and have lower rates of hospitalization (Holt-Lunstad et al., 2015).

3. Long-Term Care Facilities: Average wait times and availability for placement in long-term care facilities in rural Nova Scotia. Long wait times for long-term care facilities can lead to increased strain on hospitals and family caregivers. Timely access to long-term care improves quality of life for seniors and ensures they receive appropriate medical and personal care support (CIHI, 2023).

4. Access to Public Transportation: Percentage of seniors in rural communities with access to public or community-based transportation services. Reliable transportation is crucial for seniors to access medical care, grocery stores, and social activities. Studies show that seniors without transportation options are at a higher risk of social isolation and reduced healthcare access, leading to poorer health outcomes (Shergold & Parkhurst, 2012).

5. Accessible Housing Availability: Percentage of homes in rural communities with accessibility features for aging in place.  Housing that accommodates aging in place can significantly improve seniors' independence and reduce falls and hospitalizations. Features like wheelchair ramps, stairlifts, and walk-in showers enable seniors to remain in their communities longer and reduce the demand for long-term care facilities (Sixsmith & Sixsmith, 2008).


## Analysis 
### Accessible Homes
From my datasets, I have created formulas that give me the % of accessible homes in their respective regions. This was calsulted by dividing the number of homes that have an elevator or chair lift by the number of homes with more than one level of floors. I calculated this by county. See results below. 

<img width="805" alt="Screenshot 2025-04-04 at 10 25 06 AM" src="https://github.com/user-attachments/assets/ccb63556-99e9-4b2c-8631-cc52a432f402" />

The low percentage of accessible homes for seniors in rural Nova Scotia is a significant concern, with no county surpassing 80% accessibility and some areas as low as 14%. This lack of accessible housing severely limits seniors’ ability to live independently and safely. Without features like ramps, stair lifts, or walk-in showers, seniors are at greater risk of falls and injuries, leading to increased reliance on caregivers or early admission into long-term care facilities. This places additional strain on healthcare services and contributes to overcrowding in hospitals and long-term care systems. Moreover, poor housing accessibility reduces quality of life, often resulting in isolation, depression, and a loss of dignity. It also hinders seniors’ ability to age in place—something most prefer—forcing many to relocate away from their communities and support systems. In rural areas where access to healthcare, transportation, and social services is already limited, the lack of accessible housing further deepens inequality and vulnerability among older adults. Addressing this issue is essential to support aging populations and reduce long-term systemic costs.

## Analysis 
### Distance to Hospital 
For part 2 of my analysis, I created a map of Nova Scotia highlighting the locations of care homes and hospitals. Each care home is color-coded based on its proximity to the nearest hospital. If a care home is within 10 km of a hospital, it is considered to have good access and is marked in green. Locations that are between 10 and 25 km away are considered to have moderate access and are shown in orange. Any location more than 25 km from the nearest hospital is deemed to have limited access and is marked in red.
<img width="617" alt="Screenshot 2025-04-04 at 12 44 00 PM" src="https://github.com/user-attachments/assets/cf77e773-4efa-44d4-afb9-5fc7dae91d9f" />

The average distance of 20.11 km to the nearest hospital places most care home locations within a moderate range of accessibility. According to the healthcare accessibility KPI—defined as the percentage of seniors with access to healthcare facilities within a 30-minute drive—this distance is generally acceptable, particularly in rural and semi-rural areas of Nova Scotia. It suggests that a majority of seniors are likely able to reach a hospital within a reasonable time, which is associated with improved health outcomes. Research by Andersen & Davidson (2013) emphasizes that better access to healthcare increases the likelihood of attending regular check-ups, follow-ups, and preventive care appointments. This, in turn, reduces reliance on emergency services and supports long-term health management. However, while the average is promising, it may mask regional disparities. Some locations exceed 25 km from the nearest hospital, potentially limiting access for seniors without reliable transportation. Therefore, while the data indicates that many seniors meet the KPI target, additional attention may be needed to support those in more remote areas.

## Analysis 
### Corelation Matrix Heatmap
Combining KPI's 1 - Healthcare Accessibility and 5 - Accessible Housing Availability, I have created a heatmap to see if there is any coreltaion between my findings above. 

<img width="799" alt="Screenshot 2025-04-04 at 1 38 20 PM" src="https://github.com/user-attachments/assets/39c41fa3-a236-41f3-8ec0-cebf0bad59a9" />

The correlation matrix heatmap reveals insights into the relationships between housing accessibility and proximity to healthcare in rural Nova Scotia. There is a strong positive correlation (0.90) between the number of accessible homes and total homes, indicating that counties with more housing overall tend to also have more accessible options. Interestingly, a moderate negative correlation (-0.20) between the percentage of accessible homes and total homes suggests that smaller counties may prioritize accessibility at a higher rate relative to their size. When examining the connection between accessibility and healthcare proximity, there is only a very weak positive correlation (0.09) between the percentage of accessible homes and average distance to the nearest hospital, implying that accessibility improvements are not strongly influenced by healthcare access. Additionally, the average distance to hospital shows moderate negative correlations with both total homes (-0.43) and accessible homes (-0.31), highlighting that more remote areas tend to have fewer housing options overall, including accessible units. These findings suggest that while housing availability plays a role in accessibility, geographic distance from healthcare remains a potential barrier in rural communities.



