# Service Blueprint

Service is not just what users see in the front stage. Behind every visible moment, many invisible systems are working.

**G. Lynn Shostack** | 1984 HBR article *Designing Services That Deliver* | Service design / process optimization | Cross-functional work: 1-2 days | Level: beginner to expert

## When Should You Use It?

Service blueprints are best for journeys that cross multiple touchpoints and require front-stage and back-stage collaboration. They make the hidden service process visible so you can see pain points, redundancy, and opportunities for improvement.

### Common Use Cases

| Icon | Title | Description |
|------|-------|-------------|
| [Document icon] | Service Design | Build online experiences and cross-channel flows while aligning the backstage support, so the launch does not create experience breaks. |
| [Magnifier icon] | Customer Journey Pain Analysis | Visualize the experience path to identify touchpoints, backstage processes, and support systems. |
| [Phone icon] | Online-Offine Integration | In O2O scenarios, show how digital touchpoints and physical operations connect without friction. |
| [Gear icon] | Service Delivery Efficiency | Find waiting time, repeated work, and bottlenecks to improve delivery efficiency. |
| [Heart icon] | Cross-Functional Process Management | Define front-stage and back-stage boundaries and connect responsibility across teams to reduce coordination risk. |
| [Checkbox icon] | Digital Experience Planning | Identify human intervention points in digital service flows and decide what should be automated or intelligent. |

## Five Swimlanes, One Complete Service System

Service blueprints use a visibility line to separate what users can see from what they cannot. The five swimlanes, from top to bottom, cover user actions, front-stage touchpoints, backstage support, and support systems.

### Detailed Table

| Service Lane | Front Stage | Front Stage | Front Stage | Back Stage | Backstage Support | Support Systems |
|--------------|-------------|-------------|-------------|------------|------------------|-----------------|
| User Behavior | Book in the app | Pick up food at the store | Experience the meal | Pay the bill | Check order status | Look up reviews |
| Front-Stage Touchpoint | App interface, physical store | Staff interaction (order/serve) | Cashier (scan/card) | Finance system | Inventory management system | Product database, notifications |
| Backstage Support | Completed processes | Order processing | Food preparation | Food delivery | Logistics tracking | Supplier management |
| Support Systems | Payment platform, POS system | Member data sync | ERP system | Equipment maintenance, network monitoring | Data analysis |

## From Financial Services to a Common Service Design Language

Service blueprints were invented by G. Lynn Shostack, a banker who realized the service industry lacked a tool like an engineering drawing to describe service flow. She borrowed from industrial process diagrams and created a widely used front-stage/back-stage method.

### Timeline

**1982**
Shostack introduces the idea of service visualization

As vice president at Citibank, G. Lynn Shostack realized that service industries lacked a tool for describing customer experience and began exploring how to visualize service flow like industrial drawings.

**1984**
HBR publishes *Designing Services That Deliver*

Shostack formally introduced the front-stage/back-stage concept and showed how service blueprints can identify, visualize, and improve customer experience.

**1987**
Bitner and others extend the method

Mary Jo Bitner, Amy Ostrom, and others expanded the model by adding the "line of visibility" and "line of internal interaction," which made the blueprint easier to use in practice.

**2003**
IDEO adds it to the service design toolbox

IDEO used service blueprints heavily in service innovation and paired them with journey maps, helping the method spread as a core part of human-centered design.

**2019**
Digital service blueprint tools appear

Tools like Miro, Lucidchart, and Figma added service blueprint templates to support real-time remote collaboration and more technical layers such as API calls and data flow.

## Marriott Hotels - Redesigning the Digital Check-In Experience

After Marriott launched its mobile key feature, it found that app downloads were high but actual usage was under 30%. The team drew a complete service blueprint and discovered that the problem was not the app itself but the many breaks between back-end systems and front-stage flow.

### Marriott Hotels Interface

Marriott Hotels | Search | 2019

International hotel group digital mobile key experience

### Case Table

|  | Room Booking | Arrive at Hotel | Check-In | During Stay | Check-Out |
|---|-------------|----------------|----------|-------------|-----------|
| User Behavior | Book in app or on the website | Park, enter the lobby, and prepare to go straight upstairs | Walk past the front desk and take the elevator using the mobile key | Open the room and control room features from the phone | One-tap checkout in the app |
| Front-Stage Touchpoint | Booking confirmation email + app push | Lobby concierge, self-service kiosk | No interaction | Smart control panel in the room | Checkout confirmation push |
| Backstage Support | PMS assigns the room and generates the digital key token | IT staff checks app signal | Room status updates in the real-time room-status app | IoT device monitors room status | Generate the bill, close network access, trigger housekeeping |
| Support Systems | PMS + integrated APIs | RLS Bluetooth lock system | Housekeeping management system + app backend | IoT platform + customer service system | PMS + billing system |
| Pain Point | Digital key is available 24 hours early, but users do not know they need to claim it in advance | Signal is unstable; 30% of users cannot open the door right away | Room status and lock permissions are active, but users still wait for the front desk | Phone battery dies and there is no backup plan | Bill sometimes arrives 1-2 hours late, so users think something went wrong |

### Bottom Summary Box

Critical design mistakes led to at least three breaks:

1. The digital key was available early, but the reservation confirmation only showed a "claim key 24h later" message.
2. Bluetooth coverage had dead zones, so 6-7 users waited at the entrance trying repeatedly to unlock the door.
3. Room status did not sync in real time, so the app still showed the room as cleaned when it was not.

Result: mobile key usage rose from 28% to 41%, and front-desk wait time dropped by 45%.

## Five Steps to Draw a Service Blueprint

Service blueprints should be created by a cross-functional team. Front stage, backstage, technology, and operations all need to be included; a single perspective usually misses critical support flows.

### The Five Steps

**01 Map user behavior**
Start with the journey and define the user's action path and expected touchpoints.

**02 Identify front-stage touchpoints**
List the physical and digital touchpoints the user can see and interact with directly.

**03 Map backstage support**
For each front-stage step, identify the backstage process and system that support it.

**04 Define the support systems**
Confirm how IT systems, databases, and other technical components support the flow.

**05 Draw the key lines**
Add the line of visibility, the line of internal interaction, and the line of external interaction to mark the boundaries.

