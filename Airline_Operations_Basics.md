## Introduction to Airline Operations:

Airline operations are complex, heavily regulated, and severely constrained. In 1947, there was an international conference in Montreal, where aviation leaders gathered and decided to standardize airline operations. Every manual chapter, for example, Chapter 36, must be about landing gear. This is how it was rationalized globally. Laws were created, including maintenance laws, safety laws, pilot regulations, and engineering standards. All of this was formulated in Montreal by a body called ICAO - the **International Civil Aviation Organization**. ICAO is the governing body for civil aviation, much like the United Nations for civil aviation.

Some people even say that while anyone, even God, can make mistakes, Boeing and Airbus cannot—that's how reliable these aircraft are. You have to trust the processes set by these organizations to understand the "magic" of aviation.

The **Schedule Management System** & **Operations Solutions** can assist airlines by automating and integrating key operational functions, which can help improve efficiency and reduce costs.

You might have seen an aircraft standing still many times when you board. However, if you go down to the ground, the one hour of activity, chaos even, takes place when everything comes together. The aircraft is fueled, the aircraft and engine are inspected, the pilot boards the plane, the catering truck provides food, and the toilet cleaning truck takes care of the toilets—all happening in this one hour. After this, the plane is ready for its next flight.

When you see the flight take off, it’s just the aircraft lifting off the ground. After the pilot, it’s the **Movement Manager System** that updates to confirm the aircraft has taken off. This information is tracked using OOOI Times (Out Of On It), which tracks key phases like when the chocks (blocks under the wheels) are removed, and the aircraft is "out" of the gate.

When the pilot is ready to push back on the tractor and removes the chocks, and releases the parking brake, a signal is triggered from the cockpit. This signal goes to a computer located under the aircraft, in the avionics compartment. The **Digital Flight Data Recorder (DFDR)** receives this signal. Through that signal, it is transmitted via the **SITA Link** to the **Aircom** system. The message is then sent to the Movement Manager system to notify that the aircraft has taken off. This is possible because of a switch in the landing gear; when the landing gear hangs beyond a certain angle, the switch gets activated and sends this signal. It’s fascinating how this entire system functions.

---

### Departments and Systems:

- **Operations Control (OCC/IOCC)** (CAE: **Movement Manager**) (CAE: **Recovery Manager Ops**)
- **Network Planning & Scheduling** (Sabre **Schedule Manager**)
- **Maintenance & Engineering** (AMOS: **MRO**)
- **Flight Dispatch** (CAE: **Flight Plan Manager**)
- **Load Management** (Netline **Load**: Load & Trim)
- **Crew Management** (CAE: **Crew Manager**) (CAE: **Crew Planner**) (CAE: **Crew Recovery Manager Crew**)
- **Revenue Management** (Vendor/In-house: **Revenue Manager**)

These departments have been running long before computer systems were introduced. Over time, applications were developed to support their functions.

### How do these departments work?

- **Network Planning & Scheduling:** This is run by **Sabre Schedule Manager**. It optimizes schedules for better aircraft utilization.

Let's say we have started a new airline with $10 million in funding and 10 aircraft. Each aircraft costs $600 million, and we’ve already spent all the money as a down payment. These planes cannot sit idle on the ground. They need to be in the sky, or else we won’t earn any money. This is why aircraft utilization is the most important Key Performance Indicator (KPI). How does the system work? It's quite simple, similar to what American Airlines did 20 years ago. They planned a route from Dallas to New York that took 3 hours, with 1 hour of ground time, then back in 3 hours, followed by another hour of ground time before heading to Los Angeles. This is the foundation of network planning. 

However, network planning also involves profit analysis, identifying the exact routes the aircraft should fly. With the **Sabre Schedule Manager**, the system builds the schedule for all 10 aircraft. The system operates on a philosophy that focuses only on the aircraft and sub-fleet; it doesn’t consider anything else. This is where the **Movement Manager** comes in. While **Schedule Manager** is responsible for setting the schedule, the **Movement Manager** is responsible for assigning the actual physical aircraft to operate that schedule. Even though there are 10 aircraft, a specific one must be selected for each flight.

Once the signal comes in, and **Movement Manager** takes over operations control, the first thing it does is a tail assignment. For all the flights the **Schedule Manager** provides, **Movement Manager** assigns an aircraft to each. This is how, when you arrive at the airport, you see the aircraft ready to operate.

**Schedule Manager** is the master of scheduling within an airline. However, with an operations window of 72 hours (3 days), the ownership of the schedule shifts from **Schedule Manager** to **Movement Manager**. Within this 3-day window, **Movement Manager** makes decisions about which aircraft will go where, based on factors such as operational constraints, issues, breakdowns, engineering problems, etc. This shift in ownership of the schedule is what ultimately determines whether an airline is considered "connected" or not, in terms of its ability to manage disruptions and maintain operations smoothly.

---

- **Movement Manager System/OCC:** This is run by **CAE: Movement Manager**. It optimizes aircraft utilization, increases on-time performance, improves dispatch reliability, and carries the commercial responsibility of operations.

Let’s say your aircraft utilization is 14 hours, which is quite good. One reason this is achievable is that the aircraft are new, so breakdowns are minimal, and the reliability and integrity of flights are maintained due to high dispatch reliability.

**Schedule Manager** continuously sends schedules to **Movement Manager**, but **Movement Manager** must check for potential issues. For instance, it must ensure that the fuel is available, whether passengers can be transferred between terminals, or if any changes are needed at the gate. For example, the **Movement Manager** might say, "Change the gate from 53 to 56." The ground crew must then bring the pushback tractor, assemble a team, push the aircraft, and transfer passengers to the new gate.

**Movement Manager** not only focuses on airport utilization but also plays a key role in on-time performance. Why is on-time performance important? It’s not just for passenger satisfaction but also for the airline’s bottom line. Research has shown that "if an aircraft is delayed by just 1 minute, it costs the airline $100." This amount adds up significantly over the course of a year, resulting in substantial losses.

A study was conducted to analyze how many inputs and outputs come into the **Movement Manager** system. It was found that the Movement Manager receives flight plans, passenger boarding numbers, and fuel data, but there was a gap in engineering information, which the **Ops controllers** had to manually input.

The **Ops Controller** doesn’t directly operate the aircraft; instead, they focus on managing the incoming data from various systems. Their goal is simple: how can they get the aircraft on time? If an incoming aircraft is delayed, the **Ops Controller** may need to hold another aircraft on the ground until the delayed one arrives, in order to deal with connecting passengers. They are constantly adjusting aircraft assignments, swapping flights, and making decisions to minimize delays. This is why we say that the **Ops Controller** wears the "commercial hat" of operations, balancing the airline's operational and financial needs.

