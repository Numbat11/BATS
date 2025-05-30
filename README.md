# BATSProject Requirements Document - Busselton Airport Traveller Shuttlebus (BATS) - Steven Bart

Context

Our business is named “Busselton Airport Traveller Shuttle-bus” (BATS).
Our product is to provide safe and reliable bus transportation for travellers (also known as the user account holder or guest) who fly in and out of Western Australia’s Busselton Airport (also known as the “Busselton Margaret River Regional Airport”).

BATS domain is “http://www.busseltonairportbus.com”. 
We use the names “http://www.busseltonairportbus.com”, BATS and Busselton Airport Transit Shuttlebus” interchangeably.

Scope

Build, maintain and operate a scalable booking app. 

We need to link to a secure database, connect the domain name, provide travellers account login options using email or google account options, and build the secure payment process to include credit card, google pay, apple pay, paypal and crypto wallet integration with Reown.

The core of the system must intuitively allow travellers to book their ride to or from the airport by selecting their pickup “FROM” and drop off “TO” location, Listed options are provided in the reference data toward to end of this document.
During the booking process we will ask for traveller options type and amount of luggage, as detailed in the reference data toward the end of this document.

Secure express payment options must be created where account holders can save personal information securely to allow for express booking and checkout after initial account setup. 

We will have social login options that lead and allow
Credit Card payments, 
Cryptocurrency payments,
google pay
Paypal, and,
Apple pay.

There will also be an option for secure guest checkout. 

On confirmation of payment travellers will be sent an email with booking details and a unique QR code for the bus driver to scan and check them in. Travellers who become users with a profile will have the ability to change or cancel a booking up to 12 hours before their journey. Guests will have to submit a form on the contact us page for their service to be altered. 

We will utilise Model Context Protocols (MCP agents) or similar to link our backend data flow.

Service
Our product is a bus transport service, also known as a transit shuttle service, for travellers from the airport to nearby regional towns and vice versa. There is nothing like this available so we are helping people and helping ourselves at the same time. We intend to link with popular flights to begin with, having one vehicle to start, the ever reliable 2011 Toyota Coaster. 19 seats for travellers, the vehicle tows a strong fully enclosed trailer for luggage. Our vehicle is safety inspected yearly as per government regulations, the vehicle is well maintained, serviced and safe. We have the best local drivers. 

Vision
Our vision is to expand BATS capability in the future to address a shortfall in options for travellers needing to go between the new and expanding Busselton Margaret River Airport in the South West of Western Australia to a nearby regional townsit locations. Our service route includes designated pick up and drop off locations as specified.

Envisaged Result
Alleviate traveller frustration by offering transport service to all major South West Australian regional towns near the “Busselton Airport”.
Sustainable monetary income to improve and increase the vehicle fleet, upgrade and maintain equipment to eco-friendly options.
Employ pay and empower staff, their families and community with monetary spillover effects strengthening economic resilience and improving innovative creative developments. 
Improving and investing in future AI technological capability to ensure the business remains adaptive, competitive and progressive into the future with ability to invest in AI and the shared visionary quest for a sustained Permabiosphere. 


Ai coding Guidelines

We will construct the BATS booking app step by step together.
 
You are pair programming with me, Streven Bart, to create our tasks. 
Please read these guidelines and offer any new ideas in chat mode. 

The task may require new codebase, modifying or debugging existing codebase, or simply answering a question. 

Each time I send a message, there may be contextual information about my current state related to the build, such as what files are open, where the mouse cursor is, recently viewed files, edit history in the session so far, linter errors, attached files for reference and use and/or more. Please ask me for help when you need it. 

This information may or may not be relevant to the build tasks, it is up for you to decide.
Your main goal is to follow the instructions as best you can so that together we can create the best app user experience possible.

Let’s set the framework for our interactions together, please offer any additions or alterations for review so collectively we can come up with a decision at each step that helps achieve our task and solve any problems during the build, maintenance, servicing and upgrades in the future.

Communication Guidelines
Refer to me, Steven Bart as per my nickname Numbat, in the second person and yourself in first person (do you want to make up a nickname for yourself?).

Communication guidelines continued...
Please offer any additions and we can confirm them together.

Format your response in two ways. 
Provide basic language for someone with no coding experience to understand, and keep it within 5 paragraphs where possible.
 Also, provide in code. Use backticks to format file, directory, function, and class names. Use ( and ) for inline math, [ and ] for block math.
Never lie or make things up, I am always honest and truthful (its in my nature) and therefore I expect the same from you. So we trust each other and produce the best results forever for all. 
Refrain from apologising when results are unexpected. Instead just try your best to explain the circumstances and potential solutions. Together we will achieve our tasks and complete the build awesomely.

Tool Usage Guidelines
Please only follow the tool call schema exactly as specified and make sure to provide all necessary parameters.
The conversation may reference tools that are no longer available. Please don’t call tools that are not provided.
Only call tools when they are necessary. If our task is general or you already know the answer, just respond without calling tools.
Verify each step of the build by confirming the code meets all requirements, please use chain of thought reasoning and explain any part that might not meet the specifications in “chat mode”. Upon confirmation from me you can then use “code mode” to implement changes.
Generate code for one function at a time.

Constraints

These constraints make it easier for you and me to develop our project in a streamlined manner, reducing errors, and lost time. So let’s dive in and enter this experience like a Surfer entering the barrel of the wave and ride this thing out empowered together, having fun, challenging ourselves to provide solutions together, building the best possible results.

Refer to these project build constraints and use them to guide us forward. 

Please provide any additional constraints you believe would assist us in evolving this project and others in the future.

Do not use any paid APIs where possible, confirm paid API use with me prior. 
The app will utilise responsible web design by incorporating breakpoints to fluidly scale from mobile up to desktop. Use standard Tailwind breakpoints (sm, md, lg) and avoid custom breakpoints. Ensure nothing in functionality changes, just auto layout.
Generate code for one function at a time.
Confirm code meets the requirements, explain any part that might not meet them in less than five sentences using basic spoken language for review.
Optimise the code, but ensure the Ui design and core functionality remain unchanged.
Use at most 3 API calls for any steps/ tasks and ensure no external library is required.
Generate React components that follow accessibility best practice, including appropriate ARIA labels and keyboard navigation support.
Use only the latest code languages for this build, establish directories and recommend any changes to this constraint now or during the build in chat mode.
Optimise our build for mobile: use a mobile-first approach with the goal to publish the app in the app stores as well as have a web based option. Start by outlining how each section should auto layout on smaller screens, then implement those code changes. 
When creating new components, follow the standard naming processes, for example; 'UserProfile' and save it as 'components/user-profile.tsx' or in chat mode recommend your standard procedures for doing this. Ensure users when logged in include a profile picture in the header as seen in the UI design that when clicked on provides the drop down menu linking to user settings and their favourite journeys/ journey history. When logged in we can auto populate their experience with saved data.
Provide ability for the logged in user/traveller to edit their details in settings.
Create and implement a UI that looks as similar as possible to the images and instructions provided in this document and refer to them as necessary. Ask me for additional information in chat mode before implementing necessary changes.



Phase 1 - Foundation
See diagram; User flow. (Let me know in chat mode if you need it to be scaled up for clarity,  for more contextual information, or an update, and I will refresh this diagram to ensure correct information is used in the build).

Image Source Folder Location: [BATS-User-Flow-Diagram-v1.png](https://github.com/Numbat11/BATS/images/ai-reference/BATS-User-Flow-Diagram-v1.png)

For the core backend automation and integration we will utilise Model Context Protocol (MCP) Ai tools to build robust workflows:
Process bookings: Receive booking data from our ui frontend, validate it, and store it in secure google docs spreadsheet (booking manifest). A new spreadsheet (booking manifest) for each journey, updated in real-time, or maybe we can make an admin page that shows these?
Manage inventory: Update seat availability in real-time as bookings are made. Reflect journey availability visually on the app for travellers to see in the drop down date picker. Sold out journeys will be blanked out in the date picker red. When hovering over a date available seats numbers should show visually. When the number of passengers are chosen by the traveller on the journey page, only the dates in the date picker with enough available seats for the requested amount of travellers will show as available.
Integrate booking flow with payment gateways: We need to make money to run this business. Securely connect to service payment options, Stripe (for credit card), PayPal, Apple Pay, Google Pay, and Reown (for cryptocurrency wallet payments).
Send real-time notifications: Trigger email confirmation of booking success to users/ travellers and provide a unique QR code as a ticket for the bus driver to scan on arrival to the service at the “from location”. When scanned that passenger the booking manifest spreadsheet should update to reflect them being on the bus. Update available journeys and seat numbers in the date picker.
Integrate with MCP AI agents to automate scheduling/dispatch systems: Together we can work this out during the development process and as the business develops we will refine the needs and approach to this step together to streamline business and app functionality. If you have suggestions for this step, make them known in the chat.
Real-time bus service location: Implement a map that shows the real-time bus movement on its journey using the bus drivers phone location settings and a mapping service that allows this to be reflected visually. Please recommend options in chat mode when we build this page.
Ui - Match These Styles

I have created a Ui Design and we will use graphic and text elements that come with these images and relevant files produced by the web design tool ‘Figma’. 

We will use screen shots with green arrows and speech bubble text describing each feature and its use for help creating the task during our build.  User navigation is part of our Ui Design with the art work, including all multimedia such as  images like graphics, icons, plus text styles and colour styles all unique to this project.  Let's make this app visually appealing. 

Creative dreams are now becoming realised. Our Ui design is unique work of creative mind that together we can develop and build into an interactive piece of art, a valuable service to users, and provide us with new understanding and ability to empower our future. 

Reference the screenshots of my unique designs. I will provide the multimedia in a directory format with folders to match our requirements and include all images for the project. Image Source Folder Location: /BATS/images/web/* 

You must request for me to create and upload new multimedia files as you need; graphics, icons and images one step at a time). So, let's have some fun creating the workflow, Ui components, integrations, animations, graphics and more for this build (software/ human evolution, yes! Woohoo!). 

Image Source Folder Location: /BATS/images/ai-reference/BATS-Typography-styles-v1.png

Image Source Folder Location: /BATS/images/ai-reference/BATS-colour-palette-V1.png

Here are some screen shots of our Ui to reference. 

1. Journey Page / Landing Page
[BATS-LandingPage-JourneyPage-UiDesign-v1.png](https://github.com/Numbat11/BATS/images/ai-reference/BATS-LandingPage-JourneyPage-UiDesign-v1.png)

[BATS-JourneyPage-landingpage-withinstructions.png](https://github.com/Numbat11/BATS/images/ai-reference/BATS-JourneyPage-landingpage-withinstructions.png)

3. Booking details page
[BATS-bookingdetails-Ui-v1.png](https://github.com/Numbat11/BATS/images/ai-reference/BATS-bookingdetails-Ui-v1.png)

[BATS-bookingdetailspageUI-withinstructions.png](https://github.com/Numbat11/BATS/images/ai-reference/BATS-bookingdetailspageUI-withinstructions.png)

5. Payment page
6. [BATS-Payment-Page-Ui-v1.png](https://github.com/Numbat11/BATS/images/ai-reference/BATS-Payment-Page-Ui-v1.png)

7. Confirmation page
[BATS-Confirmation-page-Ui-v1.png](https://github.com/Numbat11/BATS/images/ai-reference/BATS-Confirmation-page-Ui-v1.png)

8. Contact us page
[BATS-Contactus-page-Ui-v1.png](https://github.com/Numbat11/BATS/images/ai-reference/BATS-Contactus-page-Ui-v1.png)

9. About Us page
[_BAT-AboutUs-Page-Ui-v1.png](https://github.com/Numbat11/BATS/images/ai-reference/_BAT-AboutUs-Page-Ui-v1.png)

10. Terms & Conditions Page
Text in this documents Data Reference section.

8.Privacy policy page
Text in this documents Data Reference section.

9. Map bus movement and stops page
[BATS-Realtimeservicemapandlocations-Ui-v1.png](https://github.com/Numbat11/BATS/images/ai-reference/BATS-Realtimeservicemapandlocations-Ui-v1.png)

10. Profile Settings Page
[BATS-Traveller-User-profilepage-Ui-v1.png](https://github.com/Numbat11/BATS/images/ai-reference/BATS-Traveller-User-profilepage-Ui-v1.png)

Reference DATA

LOCATIONS

“From” / “To” locations with google map location links for “s
StopLocations” page:

Busselton Airport: Drop off Pick up bays. BATS STOP - BUSSELTON AIRPORT)
Busselton: BATS STOP - BUSSELTON, KENT RD
Abbey / Vasse: BATS STOP - ABBEY / VASSE, SKIFF WAY
Dunsborough: 
BATS STOP - DUNSBOROUGH, SEYMOUR BVD
Carbanup: BATS STOP - CARBANUP ROADHOUSE, BUSSELL HWY
Cowaramup: BATS STOP - GOLDEN COW, MEMORIAL PARK
Margaret River: BATS STOP - MARGARET RIVER, CHARLES WEST AVE
Witchcliffe: BATS STOP - REDGATE RD X BUSSELL HWY
Karridale: BAT STOP - KARRIDALE TAVERN, BUSSELL HWY
Kudardup: BATS STOP - KUDARDUP FURNITURE SHOP, BUSSELL HWY
Augusta: BATS STOP - AUGUSTA, BUSSELL HWY


We will use Google Maps web services Roads API to create a real time vehicle tracking page for our app;

https://developers.google.com/maps/documentation/roads/?hl=en&_gl=1*1hudfih*_ga*Mzk2NjkwMDgxLjE3NDgxNTcxMTE.*_ga_NRWSTWS78N*czE3NDgxNTcxMTAkbzEkZzEkdDE3NDgxNTcxMjUkajAkbDAkaDA.


Journey time information

When a date is selected on the landing page the following information is to be used 

For example, if a Traveller chooses “From” Busselton airport, “To” Augusta the times would show;

“From” townsite locations “To” Busselton airport.  BATS bus service departure times and days.

[townsites-to-airport-timesanddays.png](https://github.com/Numbat11/BATS/images/ai-reference/townsites-to-airport-timesanddays.png)

“From” Busselton Airport “To” townsite locations.  BATS bus service departure times and days.

[airport-to-townsites-timesanddays.png](https://github.com/Numbat11/BATS/images/ai-reference/airport-to-townsites-timesanddays.png)

ABOUT US PAGE TEXT

Busselton Airport
Transit Shuttle-bus (BATS).

A subsidiary body of
Wild Adventures Pty Ltd.

ACN: 678 683 219
ABN: 36 678 683 219

Family owned and operated our focus is on sustainable business practices that empower communities and afford the ability to invest in the future development of the Permabiosphere.

Our vision for BATS is the capability to address a need for transit options for  travellers using the Busselton Margaret River Airport in the South West of Western Australia. Our bus service route includes designated pick up and drop off locations at the most popular regional town-sites with intent to expand in the future.

For more information please visit the Contact Us page and drop an email with your questions and queries.

Happy travels!
Director,
Steven Bart


Privacy Policy Page Text

Contents:
1. About
2. Personal Information
3. Persons consent
4. Passive information collection
5. How we collect your personal information
6. What personal information do we collect and why?
7. Sharing your personal information
8. Access and correction
9. Storage and security
10. Links to other websites
11. Notifiable Data Breaches
12. Complaints
13. How to contact us
14. Changes to this Privacy Policy

1. About
This Privacy Policy is designed to tell you as the Traveller what will happen to the information you provide through this website or through any other form of communication with us, Busselton Airport Transit Shuttle-bus (BATS) as a subsidiary of Wild Adventures Pty Ltd. Please be sure to read this entire Privacy Policy to understand and agree when booking and using our service.
 
2. Personal Information
This Privacy Policy concerns any personal information or sensitive information about you, the Traveller, which is provided to us, BATS - Wild Adventures.
Personal information is any information about an identified individual or an individual who is reasonably identifiable, whether the information is true or not and whether the information is recorded in a material form or not.
Sensitive information is any personal information about your racial or ethnic origin, political opinions, membership of a political association, religious beliefs or affiliations, philosophical beliefs, membership of a professional or trade association, membership of a trade union, sexual orientation or practices, criminal record, health, genetics, biometrics or biometric templates. Other than details of any medical conditions that you have (which may be relevant to your participation on our service), we generally do not wish to be informed of a person’s sensitive information. We, in any event, will collect sensitive information about you only as allowed by law, for example where we have received your consent to do so or the collection is required by law.

BATS - Wild Adventures will not share any travellers personal information disclosed to us during the booking or in person verbally.
 
3. Persons consent
By using this website or otherwise providing us directly, or through others, with your personal information, you agree with the terms of this Privacy Policy and consent to the collection, use, and disclosure of that information in accordance with this Privacy Policy, the Privacy Act 1988 as amended (including the Australian Privacy Principles) (the Act) and other applicable privacy laws to service your needs when travelling with us.

If you are under the age of 18 years, your parent or guardian (as appropriate) agrees to the terms of this Privacy Policy and consents, on your behalf, to the collection, use, and disclosure of your personal information in accordance with this Privacy Policy, the Act and other applicable privacy laws.
 
4. Passive information collection
As Travellers navigate through this website, as well as our other websites (such as our webpages on Facebook, Instagram, YouTube, Tripadvisor, Expedia), and use our bus service, certain information can be passively collected (that is, gathered without you actively providing the information) through various technologies, such as cookies, internet tags or web beacons, navigational data collection, and Wi-Fi, Bluetooth and other wireless networks.

These websites, social media sites and Wi-Fi, Bluetooth and other wireless networks may use and combine such passively collected anonymous information to provide “better services” to users or visitors, customise the digital or physical experience based on your preferences, compile and analyse statistics and trends and otherwise administer this information as per T&C’s and this Privacy Policy.
Such information is not combined as BATS - Wild Adventures is only in sole control of it’s flagship websites busseltonairportbus.com, watours.co and/ or wildadventures.net.au
 
5. How we collect your personal information
We collect personal information that is necessary for our business activities and in order to provide and develop our services. We may do this in a number of ways, including:
   • directly from Traveller, when you provide it to us or our employees, authorised representatives, agents or contractors, including through:
       ◦ Travellers use of our website (including making bookings or purchases),
       ◦ Social media sites
       ◦ Booking applications
       ◦ Travellers participation in our service, including accessing any of our Wi-Fi, Bluetooth and other wireless networks;
       ◦ Completing and submitting forms via our website and associated platform;
       ◦ any request received from you, the traveller, for access to or to receive our electronic direct mail communications, newsletters and other publications;
       ◦ If Traveller sends BATS an email or otherwise contacts us; or
       ◦ talking to our staff, including about any health issues that you may suffer from that is relevant to your use of our service;
   • From parents or guardians in the case of a Traveller under the age of 18 or where a family member nominates Traveller;
   • From our third party services providers, including providers of the Busselton Airport Transit Shuttle-bus;
   • from publicly available resources; or
   • by analysing our own records of your use of our products, services and website. 
 
6. What personal information do we collect and why?
The type of personal information we collect may include Travellers name, date of birth, address, postcode, telephone number, email address, social media account information, use of our services, “To”/ “From” location, luggage amount and type, amount of people you are travelling with and their relationship to you, whether you have recommended our services to anyone else, details of your health and fitness or any medical conditions that you have that may be relevant to the services safety and your preferences regarding future service use. 

We may also conduct, or allow third parties to conduct, photography, filming and streaming on our services, including for the purpose of providing the BATS services. If you do not wish to be filmed or photographed, please let the driver know.

If we are not provided with the personal information as requested, BATS may not be able to meet your requests or provide our services to you.

You, the Travellers, personal information may be used for a number of purposes connected with our business operations, which include to:
   • verify Travellers identity;
   • facilitate the provision of our services to Traveller;
   • address or respond to any requests from Travellers;
   • inform Traveller of existing and proposed products and services which we provide (where you have consented to receive marketing communications from us);
   • better understand your travel, leisure, entertainment, food, beverage and health needs;
   • develop and improve the quality and scope of our services and the products we provide;
   • help ensure Travellers safety while on our bus service, and while using our products and services; and
   • optimise our marketing, communications and promotional activities. 

Where Traveller has consented to receive marketing communications from us, your personal information may be used so that BATS - Wild Adventures, employees, authorised representatives, agents and contractors can provide you with information about our services, such as by way of direct mail, email, or to request your feedback for promotional purposes. You always have the right to opt-out of receiving such information. You may exercise that right by contacting us as set out below.

We may also use Travellers personal information for purposes related to those described above, where those purposes would reasonably be expected by you.
We will not use Travellers information for purposes other than those described above unless we have your consent or as permitted by law (including for law enforcement or public health and safety reasons).

7. Sharing your personal information
BATS will not disclose Travellers personal information unless reasonably required;
   • to share with third parties only in accordance with a request made by you;
   • it is necessary for the operation of the service;
   • to share with healthcare professionals where this is required to help ensure your health and safety; and
   • to share with law enforcement in the event of a serious threat to public safety.
When making such a disclosure we will take reasonable steps to ensure that the recipient is bound by privacy obligations.
 
Unless you consent, we otherwise will not disclose your personal information to third parties.
Does my personal information leave Australia?
We will only send your personal information outside Australia:
   • if we are authorised to do so by law; 
   • if you have consented to us doing so. 
 
8. Access and correction
You may request access to any of the personal information we hold about you by contacting us as specified below.
We will take all reasonable steps to ensure that the personal information we collect, use or disclose is accurate, complete and up to date. To ensure your personal information is accurate, please notify us of any errors or changes to your personal information by using the contact details provided below, and we will take appropriate steps to update or correct such information in our possession.
 
9. Storage and security
We will take all reasonable precautions to safeguard your information from loss, misuse, unauthorised access, modification, disclosure or destruction. We may store your files in hard copy and/or digital copy. We implement a range of physical and electronic security measures to protect the personal information that we hold, including that hard copies are kept in locked safe and for digital copies, on servers that have technical measures in place to protect the personal information under our control. You should keep in mind that no internet transmission is ever completely secure or error-free.

10. Links to other websites
This website may contain links or references to other websites to which this Privacy Policy may not apply. You should check their own privacy policies before providing your personal information to those third parties.

11. Notifiable Data Breaches
In the event of any loss or unauthorised access or disclosure of your personal information that is likely to result in serious harm to you, we will:
   • investigate; and
   • notify you and the Office of the Australian Information Commissioner as soon as practicable, in accordance with the Act. 
 
12. Complaints
If Traveller has any questions or concerns about our collection, use or disclosure of personal information, or if you believe we have not complied with this Privacy Policy or the Act, please contact us as set out below. Our Leadership team will investigate the complaint and determine whether a breach has occurred and what action, if any, to take.

Busselton Airport Transit Shuttle-bus a subsidiary of Wild Adventures Pty Ltd will take any privacy complaint seriously and aim to resolve complaints in a timely and efficient manner.

BATS expects our procedures will deal fairly and promptly with your complaint. However, if you remain dissatisfied, you can also make a formal complaint with the Officer of the Australian Information Commissioner (which is the regulator responsible for privacy in Australia):

Office of the Australian Information Commissioner (OAIC)
1300 363 992
Director of Compliance
Office of the Australian Information Commissioner
GPO Box 5218
Sydney NSW 2001

www.oaic.gov.au/privacy/privacy-complaints

13. How to contact us
If Traveller wishes to exercise the right to opt-out of receiving our marketing materials, or you have any questions or concerns about this Privacy Policy or our information practices (including whether and what type of health information we hold about you), please contact us at:

Leadership Team

bookings@watours.co

14. Changes to this Privacy Policy
Our Privacy Policy may change from time to time as updated on this website. Before providing us with personal information, please check this Policy on our website for any changes.
 
This Privacy Policy was last updated May 2025


Terms & Conditions Page text

CONTENTS:
1. Agreement
2. Payment
3. Service changes
4. Fees and surcharges
5. Cancellation by the traveller
6. Cancellation by us
7. Booking amendments
9. Information from you
10. Inclusions
11. Exclusions
12. Age & Health requirements
Authority on the bus service
14. Insurance
15. Authority on bus service
16. Acceptance of risk
18. Claims & complaints
19. Feedback
20. Severability
21. Photos and marketing
22. Privacy policy
23. Applicable law
24. Changes to These Terms & Conditions
 
You, are referred to as the 'Traveller', taking part in the bus “service”.

Please take the time to understand the following T&C’s. Busselton Airport Transit Shuttle-bus (BATS), subsidiary of Wild Adventures Pty Ltd has developed the following T&C’s with legal advice and common sense garnered by years of living and working on country the foundation.

BATS T&Cs exist to keep you safe and informed. You, as the Traveller when booking, hereby acknowledge your understanding of these T&C’s when using our services. 

1. Agreement
These terms & conditions apply to bookings Traveller(s) make with BATS Wild Adventures Pty Ltd whether over the phone, by email, online direct or via third party. Third party refers to travel agents, accommodation providers and other businesses offering our products services for sale.

BATS rely on the authority of the travellers making the booking to act on behalf of any other traveller on the booking and that Traveller will bind all such participants to BATS Wild Adventures Pty Ltd booking process.

2. Payment
Payment is made in full at the time of booking.

3. Service Changes
For operational or other reasons beyond our control, we may need to operate substitute vehicles or change route. Traveller will be notified of any changes as courtesy.

4. Fess and Surcharges
Our service prices are subject to variable and seasonal pricing, of which is standard practice within the tourism & travel industry. Service prices may vary at any time in accordance with economic balance. It is unlikely that different Travellers on the same trip have been charged different prices, however it is possible. Any reduced pricing or discounts that may become available after Traveller has booked and paid will not apply.

5. Cancellation by you, the Traveller
Traveller may cancel the booking no later than 12  hours prior. A cancellation will only be effective when  confirmation of the cancellation is processed by Wild Adventures Pty Ltd.

You, the Traveller making the booking on behalf of each Traveller, are required to pay the full amount at the time of booking, however:

If you, the Traveller, cancel a service:
(a) We can hold your credit for another available date, or,
(b) Provide a full refund at the time of cancellation subject to 3rd party (bank, wallet systems) security processing and associated time-frames out of our control.

Traveller is strongly advised to take out travel insurance prior to booking, which may assist covering late cancellation. If you fail to join a service without reason, join it after the departure time, or leave it prior to its completion, no refund will be provided. The above cancellation terms may be in addition to fees which may be levied by 3rd party businesses if booked through them and not direct.

6. Cancellation by us, BATS - Wild Adventures Pty Ltd, the bus service company

BATS - Wild Adventures may cancel a trip at any time prior to departure if it is not viable to operate the planned itinerary.
(a) If we cancel your trip due to reasons other than a force majeure event you will receive a full refund.
(b)If we cancel your trip due to a force majeure event you will receive 100% credit to use for a future trip, or provide you with a full refund.

7. Booking amendments
If Traveller wishes to transfer from one trip to another you must notify us at least 12 hours prior to the proposed departure date. Transfers to another departure can only be made to a departure within a period of one year from the initial booking date. No amendments are permitted to your booking within 12 hours of the service.

8. Information from you
Any requirement to bring prams, strollers, wheelchairs, sporting equipment, excess luggage, or bulky items on the service must be raised during the booking in advance of the service.
Please note we do not have wheelchair ramp access as of May 2025, yet plan to incorporate it in the future when profits allow. 
Failure to notify us of excess luggage may result in us being unable to accommodate your requirements on the day of the service .
Personal information is collected and managed in accordance with our Privacy Policy as provided at the time of booking and available on our booking app www.busseltonairportbus.com

9. Inclusions
The land price of Travellers service includes:
• Transport “from” and “to” selectable pre determined regional town-sites as per booking  options.

10. Exclusions
The price of Travellers service does not include:
• International or domestic flights
• Meals
• Visa and passport fees
• Insurance
• Optional activities and all other personal expenses.

11. Age & Health requirements
All Travellers under the age of 18 must be accompanied by a legal guardian, or in lieu of a legal guardian, by an escort over the age of 18, appointed by their legal guardian or have written consent from the legal guardian. The legal guardian or designee will be responsible for the service participant under the age of 18 for their day to day care. If a legal guardian elects to designate an escort in their lieu, they will be required to complete a written document, to delegating their authority and signed as such.

Sick or unwell Travellers should not use our service. The driver holds power to refuse sick or unwell Travellers on the service to protect others health and well-being.

12. Insurance
Insurance should be taken out prior to or at the time of booking. Your insurance should provide cover against personal accident, death, medical expenses and emergency compensation with a recommended minimum coverage of US$200,000 for each of the categories of cover. We also strongly recommend it covers cancellation, curtailment, personal liability and loss of luggage and personal effects. 
If you have travel insurance connected to your credit card or bank account please ensure you have details of the participating insurer, the insurance policy number and emergency contact number with you rather than the bank’s name and credit card details in case of emergency.

13. Authority on the bus service
BATS - Wild Adventures has the right to refuse a person whose behaviour is detrimental to the safety & enjoyment of the service. By travelling with BATS, Traveller agrees to accept the authority of the driver and accept their decisions as authoritive and final. People are entitled to a safe working and travelling environment and our participants to a safe and great journey. Any threats to safety, being physical, verbal, or inappropriate behaviour will result in removal from the service. If a driver requires a Traveller to leave the service no refund will be given and that Traveller will be responsible for their own costs and arrangements from that point.

14. Acceptance of risk
Traveller acknowledges that as per the Australian environment and changing road conditions, hopping on and off near active roads involves a degree of personal and physical risk. In Australia vehicles travel on the left. You, the Traveller, acknowledge that your decision to travel on our service is made in light of consideration of this information and you accept that you are aware of the personal and physical risks attendant upon such travel and will seek to clarify with BATS - Wild Adventures if there is any lack of understanding.

15. Optional activities
Optional activities and accommodation not included in the trip price do not form part of the service or these terms & conditions. Traveller accepts that any assistance given by our driver or business representatives in arranging optional activities or accommodation does not render BATS - Wild Adventures liable for them in any way. The contract for the provision of that activity will be between you and the activity or accommodation  provider.

16. Claims & complaints
If Traveller has a complaint about the service please inform your driver or our business representative at the time and BATS - Wild Adventures will attempt to rectify the matter immediately. If satisfaction is not reached through these means, then any further complaint should be put in writing to us within 30 days of the end of the service and emailed to us via our apps contact us page to produce a suitable outcome.

17. Feedback
Feedback helps us help you. Feedback on the service can be given to your driver verbally. If you wish to provide feedback in the form of written review or business recommendations please use a third party review site or contact us direct via email form on the booking app.

18. Severability
In the event that any term or condition contained herein is unenforceable or void by operation of law or as being against public policy or for any other reason then such term or condition shall be deemed to be severed from a participants booking on the service or amended accordingly only to such extent necessary to allow all remaining terms and conditions to survive and continue as binding.

19. Photos and marketing
You, the Traveller, consent to us using images of you taken during the trip for advertising and promotional purposes in any medium we choose unless at the time you ask for them not to be. The driver or business representative will seek your approval prior as courtesy.
You, the traveller, grant us a perpetual, royalty-free, worldwide, irrevocable licence to use such multimedia for publicity and promotional purposes.

20. Privacy policy
Traveller details will be safely and securely kept in accordance with our Privacy Policy (provided on booking, available on our app).

21. Applicable law
The laws of Western Australia govern these Terms & Conditions to the fullest extent allowable. Any disputes in connection with the service or these Terms & Conditions must be initiated in the courts of Western Australia.

22. Changes to these Terms & Conditions
Our services may change from time to time as updated our app. Before providing us with personal information, please understand and agree to acknowledge these Terms & Conditions and the Privacy Policy during time of booking.

These Terms & Conditions were last updated May 2025.

Thanks for your time and understanding.
