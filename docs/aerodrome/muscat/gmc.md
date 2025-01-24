# 3. Ground Movement Control ("Muscat Ground")
## 3.1 General provisions
The Ground Movement Controller (GMC) is responsible for managing aircraft movements on all aerodrome movement areas except for runways and their associated taxiways. Departing aircraft are given pushback instructions and instructions to taxi to the runway holding point. Arriving aircraft are assigned a stand and instructed to taxi as appropriate.

## 3.2 Departure pushback procedures
### 3.2.1 General pushback procedures
When aircraft have been handed off from CLD, they shall be fully ready for pushback and have reached their TOBT. Assuming no obstructions, they shall be instructed to push back immediately. 

Aircraft requesting push that are not squawking their assigned transponder code shall be instructed to hold position and squawk the correct code. They must not be allowed to move until doing so.

Pushback direction is based primarily on aircraft location and runway configuration. Pushback from the main terminal shall occur onto T or L as appropriate. A pushback clearance must be a variant of those provided in 3.2.2 and include an instruction on which direction to face (e.g. “FACE WEST”).

!!! example
  **Controller:** "OMA613, Muscat Ground, Pushback Approved, Face West on T."

Conditional pushback instructions may also be issued if an aircraft is taxiing behind another, waiting for pushback.

!!! example
  **Controller:** "FDB3EF, Behind Oman Air A320 passing left to right, pushback approved, face east on T behind."

### 3.2.2 Pushback direction
When departing runway 26R, aircraft parked on the north side of the main terminal (stands 2xx and 3xx) shall be instructed to "FACE EAST" or "FACE NORTH", accordingly.

Aircraft departing runway 08L parked on 3xx stands shall be instructed to "FACE WEST". Such aircraft parked on stands 201-203 can either be instructed to "FACE NORTH" or "FACE SOUTH", at the discretion of the controller and the current traffic situation. 

Aircraft parked on the south sode of the main terminal (stands 4xx, 5xx and 6xx), as well as on the cargo apron, shall always be instructed to "FACE WEST", unless otherwise required for the efficient flow of traffic. 

### 3.2.3 Pushback types
#### 3.2.3.1 Standard pushback
This type will normally have the aircraft stop abeam the adjacent stand. The phraseology for this type of pushback is laid down in 3.2.1.

#### 3.2.3.2 Short pushback
A short pushback instruction shall require the aircraft to complete the pushback abeam the current stand such that the adjacent stand will not be blocked.

!!! example 
  **Controller:** "OMA51, short pushback approved, face West on L, to finish abeam stand 406."

### 3.2.4 Simultaneous pushback operations
Simultaneous pushbacks may be permitted from adjacent stands provided aircraft are instructed to manoeuver in accordance with 3.2.2 such that on completion of both aircraft’s pushback operation, they will be separated on the taxiway by two aircraft stands.

## 3.3 Departure taxi procedures
### 3.3.1 General departure taxi procedures
Except as specified in 3.6, departing traffic shall be taxied out using the taxiways closest to the aircraft stand (T, L, S, M, H). Where aircraft are taxied to runway holding points, transfer of control to TWR shall be made early enough, such that aircraft are not required to stop their taxi. 

### 3.3.2 Traffic at the main terminal

The south side and the north side of the terminal are connected via taxiways N and R.

Taxiway N is used for southbound aircraft, while taxiway R is used for northbound aircraft. Therefore, departing traffic will taxi via L, H, R to the runway. Traffic south of taxiway F will taxi via F, E4 and H, northbound.

### 3.3.3 Traffic south of runway 08R/26L
Traffic south of runway 08R/26L shall exit their apron at the respective apron exit, then taxi via A to cross runway 08R/26L at intersection D1, then continue via E1, H, etc. 

!!! warning
  Controllers shall exercise caution when taxiing aircraft to/from the aprons south of runway 08R/26L, as only a single intersection connects the apron to the rest of the aerodrome, increasing the risk of a nose-nose situation. 

Taxiway V shall be used by departing aircraft in all configurations.

These directions keep traffic flow organised and reduces the potential for conflict.

To deconflict traffic and to reduce the length of taxi clearances, intermediate holding points shall be used wherever possible. 

!!! example
  **Controller:** "OMA7R, Taxi via T, UE, V, holding point Y7 runway 26R"

!!! example
  **Controller:** "OMA7R, Taxi via T, hold UE"

## 3.4 Arrival taxi procedures
### 3.4.1 General arrival taxi procedures
Arriving aircraft shall not immediately be handed off by TWR. They must instead be given an initial taxi instruction onto W or V to keep traffic flowing. Therefore, GMC shall assign an arrival stand when they are on final approach.

Once the aircraft is handed off to GMC they may be taxied to their stand. Arrivals shall generally be taxied via the outside taxiways that are farthest away from stands.

In the 08L configuration, traffic vacating Y5 shall use taxiway W to their stand.

Arriving traffic headed to the south side of the terminal will taxi via N G and K to the stand.

Traffic going to the south side of the aerodrome (south of runway 08R/26L) will taxi via N H E1, D1. 

### 3.4.2 Stand allocation procedure
Aircraft shall be assigned stands automatically using the Ground Radar Plugin (GRplugin) system wherever possible. Muscat does not feature operator depended stands. So all passenger operators will get a random stand at the terminal assigned.

For cargo operators, there is a dedicated cargo apron on the east side of the airport at taxiway H. The south side of the airport is used by GA, VIP and military aircraft but not by commercial passenger airlines.

### 3.4.3 Stand restrictions
TBD

## 3.5 Low visibility operations (LVO)
As there are no active runway crossings necessary, there are no specific operational requirements during low visibility conditions. If the RVR falls below 550m, take-offs are not allowed.

## 3.6 Designated areas of responsibility
Muscat has recently introduced a second ground position, meaning ground can be split into two positions if necessary: Ground North (GMC North) and South (GMC South). 
These positions are split in a horizontal line between the north-civil apron. For example, stands 1xx, 2xx and 3xx and their adjacent taxiways are controlled by GMC North and stands 4xx, 5xx and 6xx and their adjacent taxiways are controlled by GMC South. 

When both GMC North and GMC South are online, departing aircraft taxiing from the south side of the aerodrome via R shall be instructed by GMC South to taxi via R to hold short at R2, before being transferred to GMC North.
Similarly, arriving traffic taxiing from the north to the south side of the aerodrome shall be instructed to taxi via N to hold short at N1, before being transferred to GMC South. 
These points signify the boundaries of the areas of responsibility for Muscat Ground.