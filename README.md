# ABC-Tech


ML for ITSM. Machine learning looks prospective to improve ITSM processes through prediction and automation. They came up with 4 key areas, where ML can help ITSM process in ABC Tech.
Predicting High Priority Tickets: 
- To predict priority 1 & 2 tickets, so that they can take preventive measures or fix the problem before it surfaces.
- Forecast the incident volume in different fields , quarterly and annual. So that they can be better prepared with resources and technology planning.
- Auto tag the tickets with right priorities and right departments so that reassigning and related delay can be reduced.
- Predict RFC (Request for change) and possible failure/ misconfiguration of ITSM assets.

## Analysis Points
- If reassignments are more, then ticket solving time will be more
-If no. of related incidents are available then ticket solving time might decrease
- If description are available for all the tickets then we can do auto tag for all the upcoming tickets
- Alert status as 'open' can help in tracing the impact. Alert_status 'open' is directly porportional to impact
- Priority is deduce form urgency [category + subcategory] and impact[Alert status = open]
- Cat and sub_cat are the heart of the problem
- Category wise we can predict the second requirement
- Time on a particular issue[category + subcategory] shoud decrease as we move ahead. If its not decreasing then we can give an advice to the company
- Alert_status and NLP can be helpful in 3rd requirement

## 4th requirement
- Track the issues open with respect to the time period can help in deducing the peak period

## 3rd august 2018 4 pm
Requirement 1: Predict p1 and p2 tickets.
Pile up
Direct Issue from urgency and impact
Task for 4th Aug 2018
- Identifying the sub-category
- Deducing the urgency 
- deduce the impact 
