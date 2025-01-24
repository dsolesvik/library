#  # 2. Ground Movement Planner ("Muscat Delivery")
## 2.1 General provisions
Airway clearance delivery (CLD) is responsible for validation of routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure depending on the runway configuration. 
Where the flight plan contains an invalid route, level or procedure, CLD must ensure that the error is corrected before the aircraft is given its clearance..
CLD is also responsible for minimising taxiway delays and congestion for departing aircraft. During time of increased departure activity, aircraft are held at the gate to save fuel and lessen taxiway congestion.
Muscat airport does not operate datalink clearance (DCL).

## 2.2 Departure procedures
Muscat has many published instrument departures, including RNAV and conventional navigation SIDs. However, at the time of writing (January 2025), these are currently not in use due to aerodrome and airspace restructuring. Only two temporary SIDs are currently in use and therefore, only these shall be assigned.

| Runway | SID     |
|:------:|:-------:|
| 08L    | MURMA1N |
| 26R    | ITLAK1N |

The initial climb is 3000ft in all cases. When a radar controller is online, aircraft will receive radar vectors enroute after MURMA or ITLAK respectively. Thus, it is wise to know that if aircraft are departing on UNICOM, they will be responsible for self-vectoring themselves to join their cleared airway. 

## 2.3 Departure clearance
### 2.2.1 General
CLD is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact:
- Callsign;
- Aircraft type;
- Parking stand;
- Destination;
- Requested flight level;

### 2.2.2 Information contained in a departure clearance
An IFR clearance shall be in the following format:
- Callsign;
- Airway and Muscat FIR exit point;
- Departure procedure;
- Initially cleared altitude;
- Assigned SSR code

!!! example
    **Pilot**: "Muscat Delivery, OMA478, Boeing 777-300ER, information X, stand 215, request clearance to Dubai."
    **Controller**: "OMA478, Muscat Delivery, information X correct, cleared to Dubai via T508 SOLUD, ITLAK1N departure, maintain altitude 3000ft, squawk 2613."
    **Pilot**: "Cleared to Dubai via T508 SOLUD, ITLAK1N departure, maintain altitude 3000ft, squawk 2613, OMA478."
    **Controller**: "OMA478, readback correct, QNH 1016, report ready for pushback."

## 2.4 Aircraft routing
An aircraft shall be issued a reroute by GMP if the pilot’s route doesn’t comply with standard route, compliant with Oman AIP.

All aircraft must follow airway routes and fly on valid airways out of Omani airspace. The first waypoint of an aircraft's route out of Muscat must start at the Muscat VOR (MCT), followed by a valid airway route out of Omani airspace/to the flight's destination. 

If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged.

The Arabian vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the "User Submitted Routes" option, highlighted in purple, when planning a flight. These routes also appear as "blue" routes, that are Eurocontrol IFPS compliant. 


!!! example
    **Controller**: "FDB615, cleared to Dubai, via T508 SOLUD, P574, IMPED. ITLAK1N departure, maintain altitude 3000ft, squawk 2613,

<table><thead>
  <tr>
    <th>Destination</th>
    <th>Level Restrictions</th>
    <th>Routing</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Landing Dubai TMA Airports (OMDB,DW,SJ)</td>
    <td>Max FL200</td>
    <td>MCT T508 SOLUD P574 IMPED</td>
  </tr>
    <tr>
    <td>Landing OTHH, OTBD</td>
    <td>-</td>
    <td>MCT Q978 ITRAX P899 TOVOX</td>
  </tr>
</tbody></table>
<figure markdown>
  <figcaption>Table 2-2: Mandatory routes</figcaption>
</figure>

## 2.5 Requested cruising level
### 2.5.1 Level restrictions
Aircraft routes out of the aerodrome must comply with all routing and level restrictions as described in section 3.1 of Arabian MATS P1. This is based on direction and type of flight.

Should an aircraft file an invalid cruise level, GMP shall advise the aircraft of this when delivering the clearance. In all cases, the next lowest valid cruise level shall be assigned, and the aircraft advised.
## 2.6 Delay mitigation
### 2.6.1 Target off-block time (TOBT)
When A-CDM procedures are active, pilots must report their confirmed TOBT on vacdm.vatsim.me, which is then displayed in the controller's client on the departure list. A fully green time indicates a confirmed TOBT. If a pilot has not confirmed their TOBT, the controller should request it on frequency and update the departure list accordingly.

The TOBT system allows aircraft to push back, taxi to the runway holding point, and depart on schedule without extended delays in the departure queue. If an aircraft reports ready for pushback before its assigned TOBT, it will be instructed to hold position and will be given its place in the pushback sequence, unless aerodrome conditions permit and a slot is available. If an aircraft is cleared for push and start but does not begin pushing within 2-5 minutes, the pushback clearance is canceled, and a new TOBT is assigned.

!!! example
    **Controller**: "OMA102, hold position. Number 3 for startup, expect pushback at time 45."

## 2.7 Runway change procedure
AIR shall provide ample notice to GMP before changing runway configuration. The last departure using the old configuration shall be coordinated between AIR, GMP, GMC and approach/departure.

Aircraft that have already been cleared to depart using the old configuration shall be re-cleared if they have not already requested pushback.

## 2.8 VFR aircraft


### 2.8.1 VFR departures into uncontrolled airspace
VFR traffic shall be cleared via the most appropriate VFR route towards their destination. If
necessary, the clearance may be amended by TWR prior to departure.
All VFR departures shall be assigned a discrete SSR code so that they may be identified on the radar.

!!! example 
    **Pilot**: ”Muscat Delivery, A4O-DD, C172, requet clearance to Sohar, Information Charlie”
    
    **Controller**: ”A4O-DD, Muscat Delivery, Cleared to Sohar on the Northwest departure, altitude 1500 feet VFR, squawk 7025.”

    **Pilot**: “Cleared to Sohar on the Northwest departure, altitude 1500 feet VFR, squawk 7025, A-DD.”
    
    **Controller**: ”A-DD [Readback] Correct. Information Charlie correct, report ready for start-up.”
    
### 2.8.2 VFR departures into controlled airspace
VFR aircraft requesting clearance to climb into approach airspace (above 5500ft) shall only be
cleared after prior coordination with TMA control. Otherwise, they shall be instructed to remain
outside controlled airspace after leaving the control zone.
All VFR departures shall be assigned a discrete SSR code so that they may be identified on the radar.

!!! example 
    **Pilot**: ”Muscat Delivery, A4O-DD, request departure to the south on track Salalah, altitude 10,000 feet.”
    
    **Controller**: ”A4O-DD, Muscat Delivery, Cleared on track Salalah, altitude 10,000 feet VFR, squawk 7025.”

    **Pilot**: “Cleared on track Salalah, altitude 10,000 feet VFR, squawk 7025, A-DD.”
    
    **Controller**: ”A-DD [Readback] Correct. Information Sierra correct, report ready for start-up.”







