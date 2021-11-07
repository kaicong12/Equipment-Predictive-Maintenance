# EQ Major Down Summary README

NLP Approach for sequence classification. Unsatisfactory model precision and recall becasue the input data seems to be too random and there is no clear relationship between input data and output label (as proven by further EDA based on intuition) <br>


Best Results when using different data sources: <br/>

| Data source   | Test Precision | Test Recall  |
| ------------- |:----:|:---:|
| Alarm         | 78 | 44 |
| Eq Status and its respective duration | 49 | 47 |


-Model used <br/>

- Alarm Sequence LSTM  
![AlarmSeq_Model](alarm_seq.png)
- State Name & Duration Sequence LSTM  
![AlarmSeq_Model](statename_seq.png)
- Combined features LSTM




