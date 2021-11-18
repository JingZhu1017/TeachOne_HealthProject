# TeachOne_HealthProject
# Introduction
TEACH ONE project is the personal project as part of my graduate program in the Department of Health Administration and Policy at George Mason University. This project relies on a method typically used in training of medical residents: "Learn one, do one, teach one." 
In this project, I selected two topics what I want to teach, as well as use Python to solve my Teach One assignment. Then I was expected to teach by preparing a brief video and posted them to YouTube platform.
# Presentation 1 Time to Adverse Events
The data shows the speed with which Alabama medical center's emergency room provides a patient who has fractured long bone with pain medication. The main task of the project is to construct a time between chart for examining if the organization has been able to reduce the response time to less than 73 minutes.
The steps as following:
1) check if the data types of measure start date and measure end date are datetime. If they are not, I need to use function pd.to_datetime to convert them.
2) calculate the midpoint date because I need a midway point between the period of start date and end date. 
3) convert to binary to determine if minutes to pay medication with fractured long bone is above or below the benchmark 73 mins. 
4) calculated ratio.
5) create a time between chart that midpoint date on the x-axis and the consecutive below benchmark values on the y-axis.
We can find the consecutive below benchmark are below the upper control limit. Therefore, my conclusion is hospital is not below the benchmark of 73 minutes. 
The YouTube link as below: https://www.youtube.com/watch?v=YGGGIKAU0gs&t=1s
# Presentation 2 Benchmarking Clinicians
This presentation was focused on bench marking clinicians. The original data shows patients with 10 Diagnostic Related Groups and 3 HCC indices cared for by a clinician and his peer group. I need to use Python to determine if the clinician is more efficient than his peer group. 
The steps as following: 
1) created a binary column to convert clinician or peer group to 1/0. 
2) calculated the number of patients in a different severity group and different DRG group. 3) calculated probability for clinician and peer group. 
4) calculated to make sure the overlap percentage is 100 after calculating the synthetic cases. 
5) finally, percent efficient was calculated for clinician and peer group. 
Based on these calculations, we conclude that on average, and on the same set of patients, the clinician group was 2.78% more efficient than peer group in comparing the length of stay. 
The codes and other related materials could also be found on:https://www.youtube.com/watch?v=ZMSub05wiRk&t=315s
