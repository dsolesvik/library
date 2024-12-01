# 2. Ground Movement Planner ("Doha Ground")
## 2.1 General provisions
Ground Movement Control (GMC) is responsible for validating routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure to the aircraft based on the first point that is filled on the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMC shall ensure that the error is corrected before the aircraft is given its clearance.

GMC is also responsible for managing aircraft movements on all aerodrome movement areas except for runways and their associated taxiways. Departing aircraft are given pushback instructions and instructions to taxi to the runway holding point. Arriving aircraft are assigned a stand and instructed to taxi as appropriate.

## 2.2 Departure clearance
### 2.2.1 General
GMC is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact: 

- Callsign;
- Aircraft type;
- Parking Stand;
- Destination;

### 2.2.2 Information contained in a departure clearance
An IFR clearance shall be in the following format:

- Callsign;
- Destination;
- Departure procedure;
- Initially cleared altitude;
- Assigned SSR code

GMC shall obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMC shall pass the current ATIS letter and QNH.

!!! example
    **Pilot**: "Doha Ground, good evening, QQE990, Gulfstream 650ER, stand A6, clearance to Miami, with information W on board."

    **Controller**: "QQE990, information W correct, cleared to Nice via the PATOM3N departure, climb via the SID altitude 5000ft, squawk 2613."

    **Pilot**: "Cleared to Nice, PATOM3N departure, climb via the SID altitude 5000ft, squawk 2613."

    **Controller**: "QQE990, readback correct, QNH 1004, report ready for pushback."

### 2.2.3 Datalink clearance (DCL)
Aircraft clearance may also be delivered by DCL. This type of clearance reduces controller workload and frequency congestion. For suitably equipped aircraft, this will be through the ACARS system on board the aircraft.

!!! info
    Controllers shall ensure that DCL is available to be used at all times.

### 2.2.4 Aircraft requiring a reroute
Aircraft requiring a reroute shall not be given a DCL. Instead, a voice clearance must be used. This shall be communicated by ACARS datalink message or on frequency.

### 2.2.5 Voice clearance
Aircraft requesting clearance via voice shall be given a voice clearance as per the format in 2.2.2.

## 2.3 Departure Procedures
### 2.3.1 RNAV Standard instrument departures
Doha primarily uses RNAV standard instrument departures (SIDs) and is the preferred departure type for IFR aircraft. Departing aircraft shall be assigned an appropriate RNAV departure according to the first fix in the flight plan and runways in use. 

Doha RNAV Standard Instrument Departures (SIDs) operate independently from those at Hamad. Both airports conduct simultaneous departures.

SIDs which have an identifier ending in **S** are valid for **runway 15**. SIDs which have an identifier ending in **N** are valid for **runway 33**. All departures from **runway 15** have an initial climb of **6,000 feet**. In contrast, most departures from **runway 33** have an initial climb of **5,000 feet**, except for the **DATRI1N** and **ULIKA1N** procedures, which are set at **6,000 feet**.

All IFR departures shall be instructed to contact Doha Approach (West) once airborne.

| First Fix |    15   |    33   |
|:---------:|:-------:|:-------:|
|   ALSEM   |    3S   |    3N   |
|   ALVEN   |    3S   |    3N   |
|   DATRI   |    1S   |    1N   |
|   KUPRO   |    1S   |    1N   |
|   LUBET   |    2S   |    2N   |
|   PATOM   |    3S   |    3N   |
|   TULUB   |    2S   |    2N   |
|   ULIKA   |    1S   |    1N   |
|   VAXIN   |    3S   |    3N   |
<figure markdown>
  <figcaption>Table 2-1: RNAV SIDs</figcaption>
</figure>

### 2.3.2 Radar vectors departure
The radar departure procedure shall be used when aircraft are unable to accept an RNAV departure, such as one with outdated nav data. Whereas RNAV departures follow a prescribed track until leaving the Doha Approach airspace, radar departures are given radar vectors to the first fix.

A radar departure clearance shall contain the following information:

- Callsign;
- Destination;
- Departure instructions;
- Initial climb;
- Assigned SSR code

Aircraft on a radar vectors departure shall have the text VCTRS inserted to the scratchpad section of their entry on the departure list and have an initial climb set to **2,000 feet**.

All radar vectors departures shall be instructed to contact Doha Approach (West) once airborne.

!!! example
    **Pilot**: "Doha Ground, good evening, TCM1TM, Airbus A320, stand A15, clearance to Jeddah, unable RNAV, with information Z on board."

    **Controller**: "TCM1TM, information Z correct, cleared to Jeddah, fly runway heading, expect radar vectors after departure, maintain altitude 2000ft, squawk 2610."

    **Pilot**: "Cleared to Jeddah, fly runway heading, expect radar vectors after departure, maintain altitude 2000ft, squawk 2610."

    **Controller**: "TCM1TM, readback correct, QNH 1014, report ready for pushback."

## 2.4 Rerouting aircraft
An aircraft shall be issued a reroute by GMC if the pilot’s route doesn’t comply with the standard routes laid out in Table 2-2. 

Several routing restrictions exist within Qatari airspace and are detailed in the Qatari Route Manual which must be complied with when issuing a departure clearance. 

If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged.

The Arabian vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the "User Submitted Routes" option, highlighted in purple, when planning a flight.

!!! example
    **Controller**: "QQE650, cleared to Dubai, runway 15 via ALSEM3S, ALSEM - L305 - ITBUL, flight planned route. Climb via the SID altitude 6000ft, squawk 2612."

<table><thead>
  <tr>
    <th>Destination</th>
    <th>Level Restriction</th>
    <th>Routing</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Northern Emirates (OMDB, OMDW, OMFJ, OMFJ, OMRK, OMDM)</td>
    <td>FL210</td>
    <td>ALSEM L305 ASTOG</td>
  </tr>
  <tr>
    <td>Transiting Tehran FIR (FL200- @ ALKAN)</td>
    <td>FL230</td>
    <td>VAXIN T800 DASUT</td>
  </tr>
  <tr>
    <td>Transiting Tehran FIR (FL190 @RAGAS)</td>
    <td>FL190</td>
    <td>ALVEN T430 RAGAS</td>
  </tr>
  <tr>
    <td>Southern Emirates (OMAA, OMAD, OMAM, OMAL)</td>
    <td>FL270</td>
    <td>KUPRO</td>
  </tr>
  <tr>
    <td>Bahrain (OBBI, OBBS, OBKH)</td>
    <td>12,000ft</td>
    <td>TULUB B457 / M444 / T444 KINID</td>
  </tr>
  <tr>
    <td>Transiting Bahrain FIR onwards landing Kuwait FIR</td>
    <td>FL430</td>
    <td>TULUB M444 KINID</td>
  </tr>
  <tr>
    <td>Transiting Jeddah FIR onwards landing Kuwait FIR</td>
    <td>FL280</td>
    <td>TULUB B457 KINID</td>
  </tr>
  <tr>
    <td rowspan="2">Transiting Kuwait FIR</td>
    <td>FL430</td>
    <td>LUBET T934 IMLAD</td>
  </tr>
  <tr>
    <td>FL320</td>
    <td>LUBET L934 IMLAD</td>
  </tr>
</tbody></table>
<figure markdown>
  <figcaption>Table 2-2: Standard routes</figcaption>
</figure>

## 2.5 Requested cruising level
### 2.5.1 Level restrictions
Aircraft routes out of the aerodrome must comply with all routing and level restrictions as described in section 3.1 of Arabian MATS P1, Arabian Route Manual and Table 2-2. This is based on direction and type of flight. 

Should an aircraft file an invalid cruise level, GMC shall advise the aircraft of this when delivering the clearance. In all cases, the next lowest valid cruise level shall be assigned, and the aircraft advised.

## 2.6 Delay mitigation
### 2.6.1 Target off-block time (TOBT)
When A-CDM procedures are active, pilots must report their confirmed TOBT on vacdm.vatsim.me, which is then displayed in the controller's client on the departure list. A fully green time indicates a confirmed TOBT. If a pilot has not confirmed their TOBT, the controller should request it on frequency and update the departure list accordingly.

The TOBT system allows aircraft to push back, taxi to the runway holding point, and depart on schedule without extended delays in the departure queue. If an aircraft reports ready for pushback before its assigned TOBT, it will be instructed to hold position and will be given its place in the pushback sequence, unless aerodrome conditions permit and a slot is available. If an aircraft is cleared for push and start but does not begin pushing within 2-5 minutes, the pushback clearance is canceled, and a new TOBT is assigned.

!!! example
    **Controller**: "QQE101, hold position. Number 2 for startup, expect pushback at time 45."

## 2.7 Runway change procedure
Runway changes must be coordinated between Doha AIR, Hamad AIR, and Doha APP due to the interdependencies outlined in section 3.2. AIR must give GMC sufficient notice before altering the runway configuration. 

Coordination between AIR, GMC, and approach/departure is required for the final departure using the previous configuration. 

Aircraft already cleared for departure under the old configuration must be re-cleared if they have not yet requested pushback.

## 2.8 VFR aircraft
VFR traffic clearances are managed by AIR at the holding point. When an aircraft first contacts the ground frequency, it must provide the following information:

- Callsign;
- Aircraft type;
- Current position;
- Person(s) on board;
- Current ATIS;
- Intentions;

After the initial call with all required information, GMC will taxi the aircraft to the active runway and relay the details to AIR for coordination.

!!! example
    **Pilot**: "Doha Ground, A7DDD, Diamond DA40, at the civil aviation college apron, 2 POB, with information C, for local flight to the west, request taxi."

    **Controller**: "A7DDD, Doha Ground, information C is correct, taxi via Q and hold short runway 15."

    **Pilot**: "taxi via Q and hold short runway 15, A7DDD."

    **Controller**: "ADD, contact Doha Tower on 118.900."

    **Pilot**: "Doha Tower on 118.900, ADD."

## 2.9 Departure pushback procedures
### 2.9.1 General pushback procedures
Assuming no obstructions, aircraft shall be instructed to push back immediately. 

Aircraft requesting pushback without squawking their assigned transponder code or having their transponder turned on will be instructed to hold position and set the correct code. They must not be cleared to move until this is done.

Pushback direction is based primarily on aircraft location and runway configuration.

!!! example
    **Pilot**: "Doha Ground, QQE101, at stand A8 request push and start."

    **Controller**: "QQE101, stand A8, push and start approved face south."

    **Pilot**: "Push and start approved face south, QQE101."

Conditional pushback instructions may also be issued if an aircraft is taxiing behind another waiting for pushback.

!!! example
    **Pilot**: "Doha Ground, TCM4TM, on stand A3 request pushback."

    **Controller**: "TCM4TM, behind the Qatar Executive Gulfstream 650 passing right to left, push and start approved, face south."

    **Pilot**: "After the Qatar Executive Gulfstream 650 passes from right to left, push and start approved, face south, TCM4TM."

### 2.9.2 Pushback restrictions
Simultaneous pushback operations are not permitted into the same alleyway for stands G1 to G4 and W6 to W7.

For all other stands, aircraft shall be separated by at least two aircraft stands before they are given simultaneous pushback.

## 2.10 Departure taxi procedures
### 2.10.1 General departure taxi procedures
Where aircraft are taxied to runway holding points, transfer of control to AIR shall be made early enough such that the aircraft is not required to stop its taxi.

To deconflict traffic, and to reduce the length of taxi clearances, hold short instructions shall be used wherever possible.

!!! example
    **Pilot**: "Doha Ground, TCM4TM, request taxi."

    **Controller**: "TCM4TM, taxi via D, hold short of B."

    **Pilot**: "Taxi via D, hold short of B, TCM4TM."

### 2.10.2 Runway 33 departure taxi procedures
When departing from runway 33, aircraft taxiing from the west side of the aerodrome will be instructed to taxi via taxiway D to holding points F or G. 

Aircraft on the east side will be directed to taxi to holding point B1 for crossing, then proceed via taxiway D to holding points F or G. 

Extreme caution must be exercised between taxiways D and C, as this area is a rapid exit taxiway for vacating aircraft. The same caution applies between taxiways C1 and D1.

### 2.10.3 Runway 15 departure taxi procedures
When departing from runway 15, aircraft taxiing from the west side of the aerodrome will be directed to taxi via taxiway D to holding point A. 

Aircraft on the east side will be instructed to taxi to holding point B1 for crossing, then continue via taxiway D to holding point A. 

If an aircraft requires a full-length departure and backtracking, it can request this after being handed over to the tower.

## 2.11 Arrival taxi procedures
### 2.11.1 General arrival taxi procedures
GMC shall assign an arrival stand to the aircraft when they are on final approach.

Once the aircraft is handed off to GMC, they shall be taxied to their stand in accordance with the procedures laid down in 2.11.4.

(See 4.2)

### 2.11.2 Runway 33 arrival taxi procedures
Aircraft shall vacate on the respective rapid exit taxiways such as C or C1 and are then handed off to GMC.

Aircraft shall be taxied via D or D1 to the appropriate stand.

### 2.11.3 Runway 15 arrival taxi procedures
Aircraft shall vacate via E1 or utilize the turning loop available to then vacate via C1 or C when able. Once they have vacated the runway they are then handed off to GMC.

Aircraft shall be taxied via D or D1 to the appropriate stand.

### 2.11.4 Stand allocation procedures
Aircraft shall be assigned stands automatically using Ground Radar Plugin Stand Assigner. If this is not possible, aircraft shall manually be assigned a stand in accordance with the following procedure:

|  Stand(s)  |               Operator               |
|:----------:|:------------------------------------:|
|  A1 to A6  |                 VIP(s)               |
|  A9 to A18 |             Low-cost, QTR            |
|  G1 to G4  | General Aviation, Corporate Aviation |
|  W6 to W7  | General Aviation, Corporate Aviation |
|  C1 to C9  |               QTR, QQE               |
|  E1 to E24 |                  QTR                 |
| E32 to E37 |                  QTR                 |
| E25 to E27 |                  QQE                 |
| E29 to E31 |              Maintenance             |
<figure markdown>
  <figcaption>Table 3-1: Stand allocation procedure</figcaption>
</figure>

### 2.11.5 Stand restrictions
Stands A1 to A18 can accommodate aircraft up to code E. Stands with an "N" or "S" designator have specific handling limitations and are restricted to aircraft up to code C. 

Stands G1 to G4, as well as W6 and W7, are limited to code A. 

Stands E1 to E37 support aircraft up to code E, while those with an "L" or "R" designator have handling restrictions up to code C. 

Stands C1 to C9 are suitable for aircraft up to code C.

## 2.12 Low visibility operations (LVO)
### 2.12.1 LVO taxi routes
When Low Visibility Operations (LVO) are in effect, all taxiways are approved for LVO, with no restrictions.

Runway 33 is the only CAT II/III approved runway and must be used during LVO conditions (4.6.2).

## 2.13 Designated areas of responsibility
### 2.13.1 GMC positions
GMC is responsible for all aprons and associated taxiways.

(See 6.1)

### 2.13.2 Handoff procedure
Where transfer of control is to be made between controllers, aircraft shall not be cleared to a point beyond the current controller’s designated zone of responsibility unless there has been prior coordination with the next controller. Hold short instructions may be used to satisfy this requirement.