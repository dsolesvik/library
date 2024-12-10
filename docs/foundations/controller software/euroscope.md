# EuroScope
## What is EuroScope?  
EuroScope is a software application that allows members to provide air traffic control on the VATSIM network. It is the primary ATC client used by controllers worldwide.

### How to Download Euroscope

- **Download EuroScope**  
     - Visit the official EuroScope website: [https://www.euroscope.hu/](https://www.euroscope.hu/).  
     - Download the latest **public release version 3.2.9**.  

- **Optional: Beta Version**  
     - You may install the latest beta version at your discretion. Be aware that some beta builds may contain bugs that could affect controlling. Follow the recommendations in this guide to determine which beta version to use.  

## Setting up Euroscope
### Initial Setup

- **Initial Setup (First Launch)**  
     - Open EuroScope for the first time without loading any profiles.  
     - Navigate to **Other Set** (next to the Zulu clock).  
     - Untick the following options:  
         - **Auto load last profile on startup**  
         - **Auto save profile on exit**  
     - This ensures you can select a profile each time you start EuroScope instead of defaulting to the Hungary profile. You may now close Euroscope and proceed to the Sector File Installation.

<figure markdown="span">
  ![Euroscope: Disabling Automatic Profile Loading & Saving](img/euroscope_auto_settings.png)
  <figcaption>Euroscope: Disabling Automatic Profile Loading & Saving</figcaption>
</figure>

### Sector File Installation  
- **Download the Sector Files**  
     - Sector files for the Arabian vACC are hosted on the AeroNav Association website ([files.aero-nav.com](https://files.aero-nav.com)):  
       - **OMAE** - U.A.E ([files.aero-nav.com/OMAE](https://files.aero-nav.com/OMAE))  
       - **OTDF** - Doha ([files.aero-nav.com/OTDF](https://files.aero-nav.com/OTDF))  
       - **OOMM** - Muscat ([files.aero-nav.com/OOMM](https://files.aero-nav.com/OOMM))  

- **Install the Sector Files**  
     - For first-time installation, download the **Install-Package**.  
     - Extract the files to a dedicated sector file folder (e.g., `Documents/Euroscope/Sector Files`).  
     - Create a new folder inside that directory with the FIR code (e.g., `OMAE`).  

<figure markdown="span">
  ![Euroscope: Storing your Sector Files](img/euroscope_sector_location.png)
  <figcaption>Euroscope: Storing your Sector Files</figcaption>
</figure>

- **Explore the Extracted Files**  
     - **Profile Files (.prf):** Found for each aerodrome, terminal, and enroute sector.  
     - **Alias.txt File:** Located in `FIR CODE/Alias`, containing shortcut commands for text communication.  
     - **vATIS Profiles:** Located in `FIR CODE/Plugins/vATIS` for the specific FIR.  

### Using the Sector Files  
- **Load a Profile**  
     - The sector file is "plug and play." Once extracted, open the desired profile to start observing.  
     - Profiles are organized by position:  
         - **Aerodrome Profiles:** For Delivery, Ground, and Tower controllers. Includes AIR Radar and GMC Surface Movement Guidance and Control (SMGCS) displays.  
         - **Terminal Profiles:** For Departure and Arrival controllers. Includes radar views for the terminal area and SMGCS displays for relevant aerodromes.  
         - **Area Profiles:** For enroute controllers. Covers the entire FIR and SMGCS displays for all aerodromes.  
         - **Military Profiles:** For military aerodromes in the FIR.  

- **Switch Between Views**  
     - Upon loading a profile, you will see the **AIR Aerodrome View** centered on the aerodrome you selected.  
     - To open the **SMGCS Ground Display**, press ++f1+2++. This view shows the airport’s ground layout.  
     - To return to the **AIR Aerodrome View**, press ++f1+1++.

<figure markdown="span">
  ![Euroscope: AIR Aerodrome View](img/euroscope_air.png)
  <figcaption>Euroscope: AIR Aerodrome View F1+1</figcaption>
</figure>

<figure markdown="span">
  ![Euroscope: SMGCS Aerodrome View](img/euroscope_smgcs.png)
  <figcaption>Euroscope: SMGCS Ground View F1+2</figcaption>
</figure>

You’re now ready to start using EuroScope for observing or controlling on the VATSIM network. For further assistance, ask your questions in the Arabian vACC Discord in the Training-Text channel or the mentoring/instructor team.

## Observing on the VATSIM Network with EuroScope
Before starting, ensure you have installed and set up an **Audio for VATSIM** client. Refer to the **Audio Section** in the **Controller Software Setup section** for details.

### Connecting to the Network  

- **Load a Profile**  
     - Open the EuroScope profile for the position you want to observe (e.g., Aerodrome Dubai, Aerodrome Abu Dhabi, or Aerodrome Doha).  

- **Connect to the Network**  
     - Click the **Connect** button in the top-left corner of the screen.  
     - Fill out the connection dialog:  
         - Replace `<INITIALS>` with your own initials (e.g., "CK" for Chriss Klosowski). Keep the **_OBS** suffix to indicate observer status.  
         - Enter your **Real Name** as per the VATSIM Code of Conduct A4(b).  
         - Input your **VATSIM Certificate** and **Password**.  
         - Set **Facility & Rating** to **Observer**.  
         - Select **Server** as **Automatic**.  
     - Click the **Connect** button at the bottom-left of the dialog.  

<figure markdown="span">
  ![Euroscope: Connecting as an Observer](img/euroscope_connect_obs.png)
  <figcaption>Euroscope: Connecting as an Observer</figcaption>
</figure>

- **Post-Connection**  
       - Once connected, the connection dialog will disappear, and the **Voice Communication Setup** window will open. Close this window.  
       - If there is traffic in the area, aircraft will begin populating on your screen. You are now connected!  

### Listening to Active Frequencies  

To listen to an active position, you must connect to the Audio for VATSIM service using either **Audio for VATSIM** or **Track Audio**.  

#### Using Audio for VATSIM  
- Open **Audio for VATSIM** and click **Connect**.  
- Your active callsign (e.g., **CK_OBS**) will appear above the **+** button with a frequency of **199.998**.  
- To select a frequency:  
      - Click the **+** button below your active callsign.  
      - Enter the callsign of the station you want to listen to (e.g., **OMDB_1_GND**) and press **Enter**.  
      - The frequency will appear below your active callsign.  
- Press the **RX** button to start listening to the selected frequency.  
-  When a transmission occurs:  
      - The **RX** button will turn orange.  
      - The last transmitting callsign will display at the top of your window.  
- To add another frequency, click the **+** button and repeat the process.

<figure markdown="span">
  ![Audio for VATSIM Client: Connecting Online](img/afv_connect.png)
  <figcaption>Audio for VATSIM Client: Connecting Online</figcaption>
</figure>

<figure markdown="span">
  ![Audio for VATSIM Client: Adding a Position](img/afv_add_pos.png)
  <figcaption>Audio for VATSIM Client: Adding a Position</figcaption>
</figure>

<figure markdown="span">
  ![Audio for VATSIM Client: Receiving on a Frequency](img/afv_rx_pos.png)
  <figcaption>Audio for VATSIM Client: Receiving on a Frequency</figcaption>
</figure>

#### Using Track Audio  
- Open **Track Audio** and click **Connect**.  
- Your active callsign (e.g., **CK_OBS**) will display at the top of the window.  
- To listen to a frequency:  
       - Under **Add a Station**, enter the callsign of the station you want to monitor (e.g., **OMDB_1_GND**) and click **Add**.  
       - The frequency will appear in the list.  
       - Press the **RX** button to begin listening.  
- When a transmission occurs:  
       - The **RX** button will turn orange.  
       - The last transmitting callsign will display at the top of the window.  
- To monitor another frequency, click the **+** button in the top-left corner and repeat the process.

<figure markdown="span">
  ![Track Audio Client: Connecting Online](img/trackaudio_connect.png)
  <figcaption>Track Audio Client: Connecting Online</figcaption>
</figure>

<figure markdown="span">
  ![Track Audio Client: Adding a Position](img/trackaudio_add_pos.png)
  <figcaption>Track Audio Client: Adding a Position</figcaption>
</figure>

<figure markdown="span">
  ![Track Audio Client: Receiving on a Frequency](img/trackaudio_rx_pos.png)
  <figcaption>Track Audio Client: Receiving on a Frequency</figcaption>
</figure>

!!! important
    - Ensure the station you wish to monitor is active and online.  
    - If you do not hear transmissions, it may mean there are no active transmissions on the frequency at that time.  

You’re now set up to observe and listen to live ATC on the VATSIM network!