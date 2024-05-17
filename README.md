# NHS Project
As part of my L.S.E. assessment I completed an analysis project analysing the effect of missed appointments on NHS GP practices. 

Tools: Python - Pandas, Matplotlib, Seabon, Plotly, R, PowerPoint

Skills: data cleaning & wrangling, problem statement refinement, structured thinking frameworks, exploratory & descriptive analysis, stakeholder considerations, visualisations, data story-telling

### **Project Brief:**
"The NHS incurs significant, potentially avoidable, costs when patients miss general practitioner (GP) appointments. The reasons for missed appointments need to be better understood as explained by The British Medical Association (BMA) chair Professor Philip Banfield:

"While it is frustrating when patients do not attend, the reasons why this happens should be investigated rather than simply resorting to punishing them. Financially penalising patients inevitably impact the poorest and most vulnerable in the community."

(GP Practice News 2022)

Therefore, reducing or eliminating missed appointments would be beneficial financially as well as socially. The government needs a data-informed approach to decide how best to handle this problem."

I assessed the issue, utlising two structured thinking approaches; a fishbone diagram and the 5-whys method
![image 1](https://github.com/JonathanMinto/NHS/blob/main/Fishbone%20Diagram.png)

This lead to the refining of the business problem and the formulation of two guiding questions for the project following a 5-whys analysis
![image 2](https://github.com/JonathanMinto/NHS/blob/main/5-whys-NHS.png)

### **Guiding Questions:**
1. Are ‘DNA’ appointment rates affected by 'appointment mode'. If so, how do they vary across ICB locations?
2. Do longer booking lead times lead to more ‘DNA’ statuses? and does it vary across ICB locations?

### **Insights and Recommendations:**
I found a huge discrepancy in the range of appointments missed when filtering by booking lead time across different regions and recommended the service assess strong/weak performing regions to affect change.

This chart shows the upward trend of missed appointments (DNA - did not attend), a key insight suggesting resources utlisation is getting worse.

![Image1](https://github.com/JonathanMinto/NHS/blob/main/DNA%20Trend.png)
#
This chart shows that DNA appointments increase in linear fashion the longer the lead time from booking to appointment.

![image2](https://github.com/JonathanMinto/NHS/blob/main/DNA%20Lead%20Time.png)
#
This chart shows the lack of utilation of video/online services. I recommended further analysis into the causes for this as linked from the Fishbone diagram.

![image3](https://github.com/JonathanMinto/NHS/blob/main/Appointment%20Mode.png)
#
This final chart is a static image of a dynamic chart made in Python's Plotly library. It outlines my main recommendation to NHS stakeholders that different ICB location have a huge discrepancy in DNA rates and that high/low performing locations be investigated for their effective or inneffective procedures.

![image4](https://github.com/JonathanMinto/NHS/blob/main/NHS%20Appointments%20F2F.png)
