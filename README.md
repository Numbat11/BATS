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

Image Source Folder Location: /BATS/images/web/ai-reference/BATS-User-Flow-Diagram-v1.png
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
/BATS/images/ai-reference/BATS-LandingPage-JourneyPage-UiDesign-v1
/BATS/images/ai-reference/BATS-JourneyPage-landingpage-withinstructions.png

2. Booking details page
/BATS/images/ai-reference/BATS-bookingdetails-Ui-v1.png
/BATS/images/ai-reference/BATS-bookingdetailspageUI-withinstructions.png

3. Payment page
/BATS/images/ai-reference/BATS-Payment-Page-Ui-v1.png

4. Confirmation page
/BATS/images/ai-reference/

5. Contact us page
/BATS/images/ai-reference/

6. About Us page
/BATS/images/ai-reference/

7. Terms & Conditions Page
/BATS/images/ai-reference/

8.Privacy policy page
/BATS/images/ai-reference/

9. Map bus movement and stops page
/BATS/images/ai-reference/BATS-Realtimeservicemapandlocations-Ui-v1.png

10. Profile Settings Page
/BATS/images/ai-reference/
