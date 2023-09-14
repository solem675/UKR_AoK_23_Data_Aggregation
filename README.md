# UKR_AoK_23_Data_Aggregation
 Aggregating AoK Data Aggregation from KI to Settlement level

Combining data from KI-as-observation level to settlement-as-observation level.

### Aggregation rules:

**"Select multiple"** questions: if >= 40% of KIs within settlement have selected this option, it is treated as selected, otherwise - no.

**"Select one"** nominal-scale questions: prevailing option is selected. If the proportion is equal, marked as "unknown".

**"Select one"** ordinal-scale questions: the option, getting >= 50% is selected. If two options are 50 and 50, the option with higher "priority" is selected. If none of options >= 50%, the option with the priority, matching the average priority among selected ones is selected.
