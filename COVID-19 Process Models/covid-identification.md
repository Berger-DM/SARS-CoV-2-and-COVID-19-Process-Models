## COVID-19 Identification

The *Identification of COVID-19 Disease* process starts when the patient or person suspects an infection (*Start Event: Infection suspected by patient*). Then, they determine the severity of their symptoms (*Task: Determine symptom severity*). They may either be experiencing difficulty to breathe, or not. If they are, they seek professional medical help (*Task: Seek professional medical help*), and then professional help is sought out (*Message End Event: Professional help sought out*). 

<p align="center">
<img src="https://github.com/Berger-DM/berger-dm.github.io/blob/gh-pages/COVID-19%20Process%20Models/COVID-19%20Identification.jpg" width=50% height=50%>
</p>


If they are not, they then begin self-isolation (*Subprocess: Self-Isolation*). Self-isolation starts when the patient or person decides to self-isolate. They then avoid physical contact with other people (*Task: Avoid physical contact with other people*), at the same time as they stay home (*Task: Stay home*) for 14 days. After that, self-isolation ends. After self-isolation, the patient or person's symptoms can either have
subsided, or not. If they have, whatever illness they had is over, and the process ends with the case not evaluated for COVID-19 disease (*End Event: Case not evaluated for COVID-19 disease*). If they have not, then the person repeats their evaluation of difficulty breathing and continues the process from that point.

After professional help is sought by the patient or person, a medical professional receives that patient (*Message Start Event: Patient with difficulty breathing arrived*), then gathers their information (*Task: Gather patient information*), and subsequently determines the patient’s status (*Task: Determine patient status*), checking for signs of respiratory illness. There may either be signs of acute respiratory illness, which is defined as fever and at least one other sign/symptom of respiratory disease, or of severe acute respiratory illness, which is defined as fever and at least one other sign/symptom of respiratory illness AND necessity of hospitalization.

If there are signs of acute respiratory illness, the patient may either have travelled to or reside in a location reporting spread of COVID-19, or not. If they have, the patient is a suspect case of COVID-19 disease. If they haven’t, the patient may either have had contact with a confirmed or probable COVID-19 case, or not. If they haven’t, the process ends with COVID-19 disease being less probable (*End Event: COVID-19 less probable*). If they have, then the patient is a suspect case of COVID-19 disease.

If there are signs of severe acute respiratory illness, the medical professional checks for other alternative diagnosis for the patient other than COVID-19 disease (*Task: Check for alternative diagnosis*). Such a diagnosis may either exist, or not. If it exists, the process ends with COVID-19 disease being less probable (*End Event: COVID-19 less probable*). If there is no alternative diagnosis, then the patient is a suspect case of COVID-19 disease.

If the patient is a suspect case, testing for COVID-19 disease may either be possible, or not. If it is not possible, then the process ends with the patient being a probable case of COVID-19 (*End Event: Probable case*). If it is possible, the medical professional tests the patient for COVID-19 disease (*Task: Test patient for COVID-19 disease*). The test may either be conclusive, or not. If it is, then the process ends with the patient being confirmed as a case of COVID-19 disease (*End Event: Confirmed COVID-19 case*). If the test is inconclusive, then the process ends with the patient being a probable case of COVID-19 (*End Event: Probable case*). 
