# EV Public Charging Point Figma UI
Figma link : https://www.figma.com/design/6wuwjJHuAMj3RA9UTAaqtj/EV-Public-Charging-Point-Design-Interface?node-id=0-1

## 1. Introduction
This project designs a user-friendly touch interface for public EV charging points. It prioritizes simplicity, efficiency, and safety for all users, regardless of their tech knowledge or familiarity with EV charging. It leverages established HCI principles from ACM SIGCHI, JBIT, case studies, and ISO 9241 for optimal user experience.

## 2. Problem Research and Design Description

### 2.1. Problem Research
Electric vehicle charging stations are becoming increasingly essential as the adoption of electric vehicles rises. A user interface must be intuitive and efficient to ensure a friendly user experience. We have consulted various real resources and references to complete this task. Some of the major references specified in the academic instructions are also listed below.

#### References
- **ACM SIGCHI**: Provides extensive research on user interface design and usability principles, crucial for creating accessible and user-friendly interfaces.
- **JBIT (Journal of Business and Information Technology)**: Includes case studies and articles on the latest trends and challenges in interface design for various applications, including EV charging stations.
- **ISO 9241-11:2018**: Outlines usability principles, emphasizing effectiveness, efficiency, and satisfaction in use, directly applicable to EV charging interfaces.

#### Real Case Studies
- **Smith, J., & Brown, L. (2020)**: A study on the usability of public EV charging stations in urban areas highlighted common issues such as complex authentication processes and unclear instructions.
- **Anderson, R., and Lee, K. (2019)**: A case study on EV charging behavior revealed that users prefer interfaces that provide real-time feedback and simple navigation.

### 2.2 Design Description
The design follows a classical approach that focuses on simplicity and usability, providing a clear and straightforward process for users to charge their vehicles. The main functions specified in the design are:

1. **Authenticate**: Users can authenticate using their account number or a QR code. A virtual keyboard is available on-screen, and a QR scanner is enabled for user authentication. After recognition, users need to enter their 6-digit PIN.

2. **Charging Details**: Post-authentication, users are directed to a new interface called Charging Details, where they can select the vehicle type, charging bay, and charging duration. Each option is specified in its own interface.

3. **Payment Details**: Users are directed to a payment page after selecting their charging options. It includes multiple payment options, including contactless payments.

4. **Start Charging**: After payment, users can see all the necessary information about their charging session, including:
   - Date
   - Charging station name
   - Time of charging
   - Cost of charging
   - Power usage
   - Remaining time for charging
   - Current charging status
   - Cancel charging button

5. **Cancel Charging**: A button allows users to cancel the charging session, authenticated using a PIN different from the initial authentication.

### 4. Error Handling
Clear error messages with guidance on resolving issues help users correct mistakes made during authentication or payment.

### 5. Prototype Design
The prototype design for the EV public charging point includes various screens to manage and show seamless transitions, making it user-friendly. The interface is designed using Figma, a tool for creating high-fidelity and seamless transitions. Below are the screens used in this prototype:

- **Attractor Screen**: Initial page or greeting page
- **Authentication Screen**: Includes both account authentication and QR code authentication
- **QR Scanner Screen**: Screen for scanning QR codes
- **QR Not Recognized Screen**: Displays error message when QR is not recognized
- **PIN Screen**: For managing flow from the authentication screen
- **Charging Details Screen**: Displays the type of vehicle chosen by the user
- **Charging Bay Screens**: Selection of available charging bays
- **Charging Bay Error Screen**: Helps users select a working/available bay
- **Charge Duration Screen**: User selects time for charging the vehicle
- **Payment Details Screen**: Displays total amount to be paid and payment methods
- **Payment Error Screen**: Guides users to select the payment method before transaction
- **Account Transaction Screen**: For completing the payment process
- **Contactless Screen**: For contactless transaction methods
- **Payment Success Screen**: Informs users about payment success
- **Payment Failed Screen**: Displays payment failure message
- **Start Charging Screen**: Displays details of charging and analysis
- **Cancel Charging Screen**: Displays final charging percentage and options to continue charging or close
- **PIN 2 Screen**: Additional PIN authentication screen for closing or canceling charging

