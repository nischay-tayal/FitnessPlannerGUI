Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
COMPLETE DESCRIPTION OF WORK
Fitness Planner System
Diary Number: 31857/2021-CO/SW
Name, Address of the Applicant: -
Alakh Mehta, B. Tech Student, University of Petroleum and Energy Studies, Dehradun,
Nischay Tayal, B. Tech Student, University of Petroleum and Energy Studies, Dehradun,
Rudraksh Sharma, B. Tech Student, University of Petroleum and Energy Studies, Dehradun,
Umesh Kumar Nagar, B. Tech Student, University of Petroleum and Energy Studies,
Dehradun,
Dr Tanupriya Choudhury, University of Petroleum and Energy Studies - [UPES], Dehradun
Dr Thipendra Pal Singh, University of Petroleum and Energy Studies - [UPES], Dehradun
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
TABLE OF CONTENTS: -
1. ABSTRACT
2. INTRODUCTION (LIERATURE SURVEY)
3. OBJECTIVE
4. EXPLANATION
5. DIAGRAM
6. SCREENSHOT
7. APPLICATION
8. CONCLUSION
9. FUTURE SCOPE
10. REFERENCES
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
ABSTRACT
In today’s modern era, people all around the globe are becoming more interested in their health
and lifestyle. This can’t be done only by avoiding junk food or doing exercise, we require a
balanced diet. We are developing an interactive solution for our users that can help them
achieve their fitness related goals by designing their meal plan and maintaining their exercise
records. It plays an important role in day-to-day life for athletes, fitness enthusiasts, people
who are planning to do fat loss or maintain weight. On the user end they can enter their height,
weight, gender, age, goal, activity level/number of hours of workout per week and number of
meals per day based on that they will get their BMI, BMR, and complete meal plan consisting
of required amount of protein, carbohydrates and fats per day and per meal as well. Users can
also use 1RM calculator to calculate next weight to be lifted in the particular range of
percentage based on their goal to minimize risk of injury.
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
INTRODUCTION
Nutritious counseling plays an important role in prevention of many diseases. Proper
nutrition supplies the body with certain quantity of products containing appropriate does of
minerals, vitamins and other nutrients. The Project is aimed to keep track and analyze the
nutrition of the users in order to provide them and manage their macro nutrients based on
their goal and number of meals.
This application will provide central repository to maintain a log file of exercises of a user so
that user can see on which date user performed which exercise with how many numbers of
repetitions and with which weight. All this log file will be maintained through SQL server.
There are many current applications available that calculate the user’s daily calories intake
based on their current weight and the goal weight and their activity level, but they suffer from
few disadvantages, for which we will provide an effective solution to understand needs of
user and provide them more effective solution based on their goals.
Technique: The techniques (Algorithms) we are implementing are:
 Maintenance calorie algorithm
 Gaining phase algorithm
 Cutting/ fat loss phase algorithm
 1RM algorithm
LITERATURE SURVEY
1. Calories are the single most powerful nutritional variable influencing body weight, body
composition, and performance. An individual might use 2000 calories a day to meet all
their daily needs on average. [2]
2. Calories indirectly affect performance via their influence on body size, depending on
the sport, our body needs,etc[2]
3. If we talk about calculating macro-nutrients for an individual then it can depend on the
sports, activity level, etc. On the basis of different sports and circumstances
recommended range of protein, carbohydrate and fat is as follows.
Table 1: Recommended ranges of macronutrient intake for performance and sports [3], [4]
PERFORMANCE PROTEIN CARBOHYDRATE Minimum FAT
Best health 0.3 -2 gm/lb 0.3-0.5 gm/lb 0.3gm/lb
Endurance sport 0.5-1 gm/lb 1.5-5 gm/lb 0.3 gm /lb
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
In the maintenance phase, individual wants to maintain weight as well as muscle So, to
calculate maintenance calories we can calculate BMR by
Miffin and St Jeor BMR equation that is:
For men: 5 + (4.536 * weightInPounds) + (15.88 * heightInInches) - (5 * age)
For women: (4.536 * weightInPounds) + (15.88 * heightInInches) - (5 * age) - 161;
Now, we can calculate TDEE based on the activity/ no of hours of exercising per week.[2]
If hours of exercise per week =n
• If 1<=n<=3: TDEE = 1.2 *BMR(basal metabolic rate)
• If 4<=n<=6: TDEE = 1.35 *BMR
• If 7<=n<=8: TDEE = 1.55 *BMR
• If n>=8: TDEE = 1.7 *BMR
Or we can also estimate the calories in maintenance phase by using isocaloric chart based on
hard, moderate, light or no training.[2]
Protein in the Maintenance phase can be calculated as:[2],[3]
 0.3gm/lb if person is going to gym 0 to 4 hours per week.
 0.5gm/lb if person is going to gym 4 to 7 hours per week.
 1gm/lb if person is going to gym 7 to 10 hours per week.
 1.1gm/lb if person is going to gym 10 to 12 hours per week.
 1.2gm/lb if person is going to gym 12 to 14 hours per week.
 1.3gm/lb if person is going to gym 14 to 16 hours per week.
Carbohydrate in the Maintenance phase can be calculated as: [5]
 0.5gm/lb if it is a non-training day
 1.0gm/lb if it is a light training day (hours of workout<60 min)
Team sport 0.6-1.5 gm/lb 1.5-3 gm/lb 0.3 gm/lb
Strength/power sport 0.7- 2 gm/lb 1 -2.5 gm/lb 0.3 gm/lb
Hypo caloric diet 1–1.5 gm/lb 1 gm/lb 0.3gm/lb
Hyper caloric diet 1 gm/lb 1 gm – 5 gm/lb 0.3 gm/lb
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
 1.5gm/lb if it is a moderate-training day (hours of workout<120 min)
 2.0gm/lb if it is a hard-training day (hours of workout>120 min)
We can calculate fat by subtracting calories from carbohydrate and fat from total calories. In
the gaining phase, we will increase the calorie intake by certain amount depending upon Goal
weight. As 1 pound of tissue is equal to 3500 calories, so to gain weight by 1 pound that is 0.45
kg per week, we have to increase 500 calories per day. To increase the weight, we have to be
in hypercaloric condition in which we will increase our carbohydrates intake mainly by 40 –
55 %, fat by 30 to 45 % and protein by 0 to 15 %. Similarly in Cutting phase, we have to be in
hypocaloric condition in which we will increase protein by 20 to 35%, and decreasing the
carbohydrate and fat.[2]
Nutrient timing manipulations is also an important factor when we talk about performance,
strength and getting fit. Based on the number of meals we will divide protein equally in every
meal and carbohydrate can be divided based on number of meals like this:
Table 2: Suggested percentages of daily carbs are listed for different daily meal number
options [2]
4 meals per day:
Pre – workout meal: 25% daily carbs
Post – workout meal: 35% daily carbs
Bedtime Meal: 25% daily carbs
Remainder: 15% carbs to remaining one meal
5 meals per day:
Pre – workout meal: 20% daily carbs
Post – workout meal: 30% daily carbs
Bedtime Meal: 20% daily carbs
Remainder: 30% carbs to remaining two meals
6 meals per day (1 X daily
workout):
Pre – workout meal: 18% daily carbs
Post – workout meal: 25% daily carbs
Bedtime Meal: 18% daily carbs
Remainder: 30% carbs to remaining three meals
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
1RM, one repetition maximum or one execution maximum, is operationally defined as the
heaviest load that can be moved over a specific range of motion, one time and with correct
performance. Even though 1RM is a key measurement in order to generate a well-founded
training protocol for athletes, training prescription is typically based in a predetermined number
of repetitions as further research is needed in this area. [7]
Table 3: 1RM Prediction Equations [7]
 Author 1 RM prediction equation
 Brzeski (1993)
 1 RM = 100 𝜔
102.78−2,78𝑟
 Epley (1985) 1 𝑅𝑀 = (1 + 0.333𝑟)𝜔
 Lander (1985)
 1 RM = 100 𝜔
101.3−2.67123𝑟
 Lombardi (1989) 1 𝑅𝑀 = 𝜔𝑟
0.1
 Mayhew et al (1992)
 1 RM = 100 𝜔
52.2+41.9exp(−0.055𝑟)
 O’Connor (1989) 1 𝑅𝑀 = 𝜔(1 + 0.025𝑟)
 Wathen (1994)
 1RM = 100 𝜔
48.8+53.8exp(−0.075𝑟)
OBJECTIVE
In this project we will implement the following:
• To find the macro-nutrients and calculate calories intake of user in maintenance phase,
gaining phase and cutting phase/ fat loss phase and prepare the meal chart on the basis
of number of meals per day and goal of the user.
• To give users a diary to maintain their activity record and track the previous record
through log file.
• Allowing the users to use 1RM based calculator on basis of which they can find the
percentage of 1 rep max depending upon their goals.
• Allowing the gym manager to maintain record of all users and see the record of exercise
performed by all clients on particular date along with time of login of each user.
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
EXPLANATION
Explanation for Objetive 1:
Macro nutrients are calculated based on goal:
Goal can be:
1. Maintenance phase: Used for maintaining weight and muscle mass by clients.
2. Gaining phase: Used for gaining muscle mass and weight by clients.
3. Cutting phase: Used for loosing weight and maintain muscle mass as well.
Clients will get complete meal plan depending upon the no. of meals per day and client will be
given an option to print the meal plan.
Clients can use Mind Fitness option that have a playlist of meditations and option of
padamsadhna that will direct client to youtube from where client can practice meditation
regularly.
Explanation for Objetive 2:
Give users a diary to maintain their activity record and track the previous record through log
file to:-
 Be consistent.
 Be accurate.
 Try to keep different logs, based on time and activities. Determine what works best
for them.
 Do not wait too long to note down activities.
 Also keep track of the time in which there are no activities.
 For each activity, note whether or not it was planned in advance.
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
Explanation for Objetive 3:
1 RM is the maximal weight an individual can lift for only one repetition with correct
technique. Lifting weight according to 1RM in a specific exercise for more experienced
lifters, attempting the 80 to 90 % of 1 rep by the third work set. As the max effort approaches,
the number of reps in working sets would drop dramatically. This conserves energy for the
all-out effort and also "trains" the neural system to lift large weight. Our application will
provide clients all the 7 equations that can be choosen depending on exercise.
Explanation for Objetive 4:
Gym manager can see the record of all users enrolled in gym and can see the activities like
exercise record of every client and time of login of users on particular date. Gym manager can
also add new client or modify client details(if asked by client) and delete the reord of client
when client had left the gym or when client have not given the fees of gym.
If the client forgets the password then gym manager will log in through admin’s account and
search for the users registeration id and then client can modify their password.
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
DIAGRAM
 Figure 1: Flow chart of Proposed System
Screenshots
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
Figure 2: Log In Screen Activity
Figure 3: Admin Screen Activity
Figure 4: Client- Side Activity
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
Figure 5: Enter Details Activity
Figure 6: Users Goal Activity
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
Figure 7: Gaining Phase Activity
Figure 8: Maintain Exercise Record Activity
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
APPLICATION
 GYM owner/manager and trainers can use application to manage their data of clients.
 Athletes, fitness enthusiasts can use this application for their exercise records and as
meal planner.
 Establishing a workout plan reduces the risk of straying into the "I'll do it tomorrow"
mentality and holds you accountable for sticking to the daily schedule.
 Our application will tell you which exercises to do, how many reps to do, and how
many sets to do, among other things. Everything has been set out in front of you.
 A training plan with a fixed number of weeks (like the four, six, or twelve weeks we
have) gives you an automatic goal — to finish the workout plan.
CONCLUSION
A user-friendly application is created that can be accessed by clients in gym, personal trainers,
Gym manager, etc through there computer/laptop, user -id will be set as registration number
given at the time of adding new user by the admin. Admin can add/modify user details and see
the details of exercise record of all the clients.
Client will find this application very useful as they can find the macro-nutrients and calculate
calories intake of user in maintenance phase, gaining phase and cutting phase/ fat loss phase
and hence prepare a meal chart based on number of meals, maintain their activity record and
track the previous record through log file and use 1RM calculator.
FUTURE SCOPE
To use it in my own gym and then taking one step further, setting a database and admin for
all other gym and fitness centers in my region. Adding more functionality time to time like
machine -learning, collecting nutrition value of all food items, etc. after testing and getting
reviews from clients.
Alakh Mehta, Nischay Tayal, Rudraksh Sharma, Umesh Kumar Nagar, Tanupriya Choudhury,
Thipendra Pal Singh
Diary Number: 31857/2021-CO/SW
REFERENCES
[1] DAS, R. K. (2013). CORE JAVA FOR BEGINNERS , 3rd EDITION . VIKAS
PUBLISHING HOUSE PVT LTD.
[2] THE RENAISSANCE DIET 2.0 BY Dr. Mike Israetel, Dr. Melissa Davis, Dr. Jen
Case, Dr. James Hoffmann
[3] Pasiakos SM. Metabolic advantages of higher protein diets and benefits of dairy foods
on weight management, g lycemic regulation, and bone. J Food Sci. 2015 Mar;80
Suppl 1: A2-7.
[4] Pasiakos SM. Metabolic advantages of higher protein diets and benefits of dairy foods
on weight management & 1:A2-7.)Pedersen, A. N., Kondrup, J., & Børsheim, E.
(2013). Health effects of protein intake in healthy adults: a systematic literature
review. Food & Nutrition Research, 57, 10.3402/fnr. v57i0.21245.
[5] Montfort-Steiger, V., & Williams, C. A. (2007). Carbohydrate Intake Considerations
for Young Athletes. Journal of Sports Science & Medicine, 6(3), 343–352
[6] Manore, M. M. (2015). Weight Management for Athletes and Active Individuals: A
Brief Review. Sports Medicine (Auckland, N.z.), 45(Suppl 1), 83–92.
[7] 1RM prediction: a data mining case study Adri´an Santos Parrilla Supervised by
Aurora P´erez P´erez Master of Science Thesis Facultad Inform´atica Universidad
Polite´cnica de Madrid June 30, 2014.
Communication Address
Name: Tanupriya Choudhury
Email-Id: tanupriya1986@gmail.com
Address: Dept of Informatics, School of CS, University of Petroleum and Energy Studies,Via
Prem Nagar, Bidholi Campus, Dehradun, Uttarakhand-248007
Phone Number: 09910803601, +91 97119 38087


 
