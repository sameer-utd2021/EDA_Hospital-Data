# EDA_Hospital-Data


With this project we'll be anyalyzing the dataset for hospital appointments which has information on 100,000 medical appointments in Brazil and is focused on the questions as to what are the factors which affect patients showing up for appointments.

A number ofcharacteristics about the patient are included in each row:

‘ScheduledDay’ tells us on what day the patient set up their appointment
‘Neighborhood’ indicates the location of the hospital
‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família [Bolsa Família (Family Allowance) is a social welfare program of the Government of Brazil, part of the Fome Zero network of federal assistance programs. Bolsa Família provides financial aid to poor Brazilian families; and if they have children, families must ensure that the children attend school and are vaccinated. If they exceed the total of permitted school absences, they are dropped from the program and their funds are suspended. The program attempts to both reduce short-term poverty by direct cash transfers and fight long-term poverty by increasing human capital among the poor through conditional cash transfers. It also works to give free education to children who cannot afford to go to school to show the importance of education.] - taken from Wikipedia
'No-show' says ‘No’ if the patient showed up to their appointment,and ‘Yes’ if they did not show up
Appointment ID,Gender,Schdedule Day,Appointment Day,Age, Neighbourhood,Hipertension,Diabetes, Alcholism, Handicap, SMS are other self explanatory obesrvations availbale for each patient
Dependent Variable for analysis:
'No-show'
We want to predict based on the rest of the data whether the patient will show up for the appointment

Independent Variables for analysis:
Scholarship , SMS_recieved,Handcap, Alcoholism, Gender, Neighbourhood and Age
