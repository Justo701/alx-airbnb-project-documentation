# Data Flow Diagram (Level 0 / Context + main flows)

![Data Flow Diagram](data-flow.png)

Main entities → processes → data stores:

- Users ↔ Authentication ↔ Users DB
- Guests/Hosts ↔ Property Management ↔ Properties DB
- Guests ↔ Search Engine ↔ Properties DB
- Guests ↔ Booking Process ↔ Bookings DB
- Booking Process ↔ Payment Gateway ↔ Payments DB
- Guests ↔ Review System ↔ Reviews DB
