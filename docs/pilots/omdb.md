# OMDB - Dubai
## Airport Overview
### Information

<figure markdown>
![OMDB - Dubai International](img/omdb/omdb_header.jpg)
</figure>

| IATA | ICAO | Charts | NOTAM(s) |
|:----:|:----:|:------:|:----------:|
| DXB  | OMDB | [U.A.E eAIP (Account Required)](https://www.gcaa.gov.ae/en/ais/Pages/default.aspx)    | [U.A.E FIR - NOTAM(S) ](https://www.gcaa.gov.ae/en/ais/notice-to-airmen-notam)      |

Dubai International Airport is the primary gateway for Dubai and the United Arab Emirates. It ranks as the world's busiest airport by international passenger traffic and is also the largest airport in the Middle East. Globally, it is the second busiest by total passenger volume and the leading airport for Airbus A380 and Boeing 777 operations.

Located 2.54 nautical miles east of Dubai's city center in the Al Garhoud district, the airport is home to Emirates Airline and low-cost carrier FlyDubai.

!!! Tip
    Dubai International is one of the busiest globally and the most active in the Middle East. Due to the high volume of traffic during peak hours and the airport's operational complexity, **it is essential that you prepare thoroughly**, as any professional crew would. Be sure to review this brief and the corresponding charts carefully.

    **If you are new to the VATSIM Network**, we strongly recommend avoiding this airport until you have gained more experience flying on the network. During peak times, controllers are often too busy to offer additional assistance. Instead, consider flying to other airports within the Arabian vACC, where the traffic is lighter and procedures are less complex, allowing for a more accommodating experience.

### Charts & Scenery
Pilots can access the latest charts through the following sources: [Chartfox (Free, VATSIM login required)](https://chartfox.org/), [the U.A.E eAIP (Free, account required)](https://www.gcaa.gov.ae/en/ais/Pages/default.aspx), or [Navigraph (Subscription required)](https://navigraph.com/). **VFR charts in Navigraph are listed under the "APP" category with "Runway Unspecified."**

| Simulator      | Freeware                    | Payware                            |
|----------------|-----------------------------|------------------------------------|
| MSFS           | [flightsim.to](https://flightsim.to/file/35295/omdb-dubai-international-general-enhancement) | [IniBuilds](https://inibuilds.com/products/inibuilds-dubai-omdb-msfs) |
| X-Plane        | X-Plane Default             | [TAIMODELS](https://orbxdirect.com/product/taimodels-omdb-xp11-xp12?srsltid=AfmBOopPtBA3ju1rhXF6pIfYWByGIDgNMhirnOKCRLb3wASSzRvsEaeI) |
| Prepar3D V4/V5 | [AVSIM](https://library.avsim.net/search.php?SearchTerm=OMDB&CatID=fsxscen&Go=Search) | [FlyTampa](https://www.flytampa.org/omdb.html) |

!!! Warning
    The latest airport layout is reflected in MSFS, X-Plane, and the freeware Prepar3D sceneries. However, the payware Prepar3D scenery from FlyTampa features the 2012 airport layout, which lacks Concourse D and some taxiways/rapid-exits. Pilots using the FlyTampa scenery must inform the controller of this on initial contact.


### Stand Allocation

|       Area       |        Stand Allocation       |                                                      Operator                                                     |
|:----------------:|:-----------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| Concourse A      | Stands A1 to A10, D1 to D10   | ACA, QFA, UAE, UAL                                                                                                |
| Concourse B      | Stands B14 to B27, F16 to F27 | ACA, QFA, UAE, UAL                                                                                                |
| Concourse C      | Stands B1 to B12, F2 to F13   | FDB (Stands: F2, B1 to B10), UAE                                                                                  |
| Concourse D      | Stands C48 to C64             | International Operators                                                                                           |
| Apron C (Remote) | Stands C18 to C47             | UAE (Stands: C24 to C40), FDB (Stands: C18 to C23, C27 to C40), KAM (Stands: C36 to C40), International Operators |
| Apron E (Remote) | Stands E1 to E45              | Someone figure this one out its complicated lmao                                                                  |
| Apron G (Remote) | Stands G1 to G22              | UAE (Overflow)                                                                                                    |
| Apron H          | Stands H1 to H4               | AUH, DUB                                                                                                          |
| Apron Q (Remote) | Stands Q1 to Q11              | FDB                                                                                                               |
| Apron S (Remote) | Stands S1 to S15              | UAE (Overflow)                                                                                                    |

!!! Info
    All arriving aircraft will be assigned stands by our stand assigner using the Ground Radar Plugin. Virtual Airlines can expect to be directed to park at Concourse D.

### Air Traffic Control positions
| Login Code |  Radio Callsign  | Frequency | Area of Responsibility                                            |
|:----------:|:----------------:|:---------:|-------------------------------------------------------------------|
| OMDB_DEL   | Dubai Delivery   | 120.350   | - All IFR & VFR Clearances                                        |
| OMDB_1_GND | Dubai Ground     | 118.350   | - Primary Ground Position - Concourse A, B, C, Apron G, Apron H   |
| OMDB_2_GND | Dubai Ground     | 121.650   | - Concourse C, Apron C, Apron E, Apron Q, Apron S                 |
| OMDB_1_TWR | Dubai Tower      | 118.750   | - Primary Tower Position - Runway 12L/30R                         |
| OMDB_2_TWR | Dubai Tower      | 119.550   | - Runway 12R/30L                                                  |
| OMDB_1_DEP | Dubai Departures | 121.025   | - Primary Departure Position                                      |
| OMDB_2_DEP | Dubai Departures | 124.675   | -                                                                 |
| OMDB_APP   | Dubai Arrivals   | 124.900   | - Primary Arrivals Position - Services for: OMDB, OMSJ, OMDW      |
| OMDB_F_APP | Dubai Director   | 127.900   | - Final approach sequencing - Call with callsign only!            |

!!! Warning
    It's crucial that you pay close attention to the frequency you're being transferred to. Do not attempt to guess the next frequency, and never switch frequencies without explicit instructions from the controller. Auto-handoffs are not used at Dubai International. If you're unsure, don’t hesitate to ask for the frequency again!

#### Ground Movement Control Area of Responsibility

## Departing Traffic
### Flight Planning: Route(s)
Pilots can find valid routes for most flights departing from Dubai on SimBrief by choosing the "Preferred Route" option. Our operations department updates the "Preferred Route" on SimBrief with every AIRAC cycle, ensuring compliance with Air Traffic Flow Management (ATFM) regulations in the Middle East and Eurocontrol IFPS validation.

<figure markdown>
![Simbrief Preferred Route](img/simbrief_preferred_route1.png){ width="600" }
  <figcaption>Figure 1-1: Simbrief Preferred Route</figcaption>
</figure>

<figure markdown>
![Simbrief Preferred Route](img/simbrief_preferred_route2.png){ width="600" }
  <figcaption>Figure 1-2: Simbrief Preferred Route</figcaption>
</figure>

### Flight Planning: Standard Instrument Departure (SID)
Controllers will assign a Standard Instrument Departure (SID) based on the first waypoint in your flight plan, guiding you out of the Dubai Terminal Maneuvering Area (TMA). Refer to the table below to see which SID you can expect. If your waypoint isn't listed in the table, ensure your AIRAC cycle is up to date. If your AIRAC is outdated, please inform the controller promptly so we can arrange an omnidirectional departure for you.

| Waypoint |  12L/R  |  30L/R  |
|----------|:-------:|:-------:|
| ANVIX    |   5G    |   7F    |
| DAVMO    |   4G    |   4F    |
| EMERU    |   2G    |   2F    |
| IVURO    |   1G    |   1F    |
| KUTLI    |   4G    |   4F    |
| MIROT    |   3G    |   3F    |
| NABIX    |   3G    |   3F    |
| RIDAP    |   3G    |   2F    |
| SENPA    |   3G    |   2F    |

!!! Note
    Please be aware that the departures listed above apply to both the left and right runways. At Dubai International, there are no runway-specific SIDs, so your clearance will not include a designated runway. You can determine your departure runway by checking the Automatic Terminal Information Service (ATIS).

### Getting your clearance
Departing aircraft shall contact Dubai Delivery **10 minutes prior to start-up** and pass the following information:
<ul>
    <li>Aircraft Callsign</li>
    <li>Aircraft Type</li>
    <li>Parking Stand</li>
    <li>Requested Flight Level</li>
    <li>Destination</li>
    <li>Standard Instrument Departure (and departure speed if unable to comply with SID minimum speed restrictions)</li>
    <li>Aircraft routing via M318 to report crossing level for GABKO if below FL150</li>
</ul>