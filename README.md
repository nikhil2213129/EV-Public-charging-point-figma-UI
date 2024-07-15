# EV-Public-charging-point-figma-UI
**1.Introduction**
This project designs a user-friendly touch interface for public EV charging points. It prioritizes simplicity, efficiency, and safety for all users, regardless of their tech knowledge or familiarity with EV charging. It leverages established HCI principles from ACM SIGCHI, JBIT, case studies, and ISO 9241 for optimal user experience. 

**2.Problem Research and Design Description**
2.1. Problem Research
Electric vehicle charging stations are becoming increasingly essential as the adoption of electric vehicles rises. A user interface is the critical component which is must to be intuitive and efficient to ensure a friendly user experience. We have gone through different real resources and references for completing this task. Some of the major references which are also provided in the academic instructions are also specified. 

References:
ACM SIGCHI (Special Interest Group on Computer-Human Interaction) provides extensive research on user interface design and usability principles. This research is crucial in understanding how to create interfaces that are accessible and user-friendly.
JBIT (Journal of Business and Information Technology) includes case studies and articles on the latest trends and challenges in interface design for various applications, including EV charging stations.
ISO 9241-11:2018 outlines the principles of usability, emphasizing effectiveness, efficiency, and satisfaction in use, which are directly applicable to the design of EV charging interfaces.

The Real case studies:
A study on the usability of public EV charging stations in urban areas highlighted common issues such as complex authentication processes and unclear instructions (Smith, J., & Brown, L., 2020).
Another case study by Anderson, R., and Lee, K. (2019) on EV charging behavior revealed that users prefer interfaces that provide real-time feedback and simple navigation.

2.2 Design Description
The design made should follow classical approach that focuses on simplicity and usablility, providing a clear and straight forward process for electronic users for charging their vehicles.
The main functions specified in the design are :
1.Autheticate:
User can authenticate using their account number or a QR code , since this is a touch screen design , users should have the access of virtual keyboard on screen. A QR scanner code for an account card of the user is enabled in the authentication page of the interface. After recognition of their identity , user needed to enter their pin number which is about 6 numbers which was directed from either account number screening or QR code scanning.
2.Charging details
After authentication of the user , he/she is directed to a new interface called charging details where user can navigate seamlessly to all the features present in the interface. Some of the majorly used charging details are choosing the vehicle type, choosing the charging bay, choosing the charging duration. This could be done on each of the interface options selected by the user initially, user needed to select the vehicle type, other options like charging bay, charge duration is specified respectively in their own interfaces.

3. Payment details
After selecting their specified options for their electric vehicle in the charging details by the user, the user is directed to a payment page. It has multiple payment options , including contactless payments.

4.Start charging
 A new interface is obtained after payment, where user can able to see all the appropriate information of their charging. The information that use could be seen in the screen are
Date
Charging station name
Time of charging
Cost of charging
Power using
Remaining Time for charging 
Current charging status 
Cancel charging button

5.Cancle charging
A button specified in the screen to ensure if we want to cancel the charging. This is authenticated using the users pin number which was specified during authentication. PIN authentication is not same as the PIN authentication of the first authentication page.

4.Error handling:
A clear error messages with guidance on resolving the issues made by the user. This will help the user to correct their mistakes done while authentication or in payment

5. Prototype design
The prototype design for EV public charging point has different screens for managing and showing a seamless transition between the screens and make it user friendly. The below are the screens used in this prototype for creating an interface. The interface is designed using a tool called figma, which is used for creating high fidelity and seamless transitions. Figma is a UI/UX designing tool used here to create a EV public charging point interface according to the given instructions. As per the previous response, I have mentioned the different screens used in my design for creating this project.
The screens used in the design:
Attractor screen – Initial page or a greeting page
Authentication screen – It includes both the account authentication and QR code authentication.
QR scanner screen – screen consisting a QR code for scanning, so that user can proceed.
QR not recognized screen – screen consists error message about “not” recognizing the QR 
PIN screen – PIN screen is designed for managing the flow between the next screen from the authentication screen
Charging details screen – screen consisting of the type of vehicle choose by the user.
Charging bay screens – selection of available charging bays in the station
Charging bay error screen – screen which helps user to select the working / available bay.
Charge duration screen – A default screen where user selects time for charging the vehicle.
Payment details screen – consists of total amount to be paid , and also include their payment methods like account transaction and contactless transaction.
Payment error screen – screen helps user to select the payment method before transacation
Account transaction screen – Navigated from payment details screen in to this for completing the payment process.
Contactless screen – consisting of contactless transaction methodologies where user just places their card for making the payment
Payment success screen – a screen gives info to user about payment success.
Payment Failed screen – screen represents the failure of the payment.
Start charging screen – screen consisting of details of charging and also its analysis.
Cancel charging screen – screen consists the final charging percentage and other options like continue charging or close .
PIN 2 screen – another PIN authentication screen for closing or cancelling the charging

