in the latex paper when we used the reference of this review we integrated beside it the word (TEX)--->>> important.

AC MICROGRID PROTECTION CHALLENGES
As discussed earlier, the microgrid is a cluster of DERs and
loads within a specific electrical boundary [3], [75]. DERs are
based on renewable and non-renewable energy sources. The
non-renewable-based DERs are providing constant power.
But renewable-based DERs such as solar and wind are
intermittent. These are relying on environmental conditions.


AC Microgrid protection challenges can be generally
separated into two types; protection challenges when the
grid-connected operational mode of microgrid and protection
problems when the operational mode of a microgrid is
islanded

1) DYNAMICS IN FAULT CURRENT MAGNITUDE
As discussed earlier, some renewable-based DERs are
intermittent. The fault current contribution by that DERs is
also intermittent. The fault current depends on the nature of
DERs, size, and location of integration to the microgrid. The
DER connection in the LV network shifts the fault level to a
significant level generally in two primary operational modes
that are grid-connected and islanded. In grid-connected
operational mode, the fault current is significantly high due to
both DERs and utility grid contribution within the microgrid


2) FAULTS/EVENTS DURING GRID-CONNECTED MODE
During grid-connected mode, when the fault occurs on the
utility grid side, PDs of DERs should not trip before PCC
PDs and DERs must keep operational activity during fault
detection and tripping of PCC PDs. To recognize such a
situation all DERs must have fault ride-through capacity [85].
When the fault occurs in the microgrid side during the
grid-connected mode, the feeder/line protection must isolate
the faulty part from the network as fast as possible. The
action time of protecting devices depends upon the microgrid
complexity, protection scheme used, and features of the
microgrid. Some non-fault events occur in LV at PCC i.e open
phases non-fault and voltage unbalance conditions w


3) FAULTS/EVENTS DURING ISLANDED MODE
The sort of problems in microgrids operated during islanded
mode become disparate from the grid-connected microgrid [87]. During the grid-connected operational mode of
microgrid, the fault current has a high magnitude which is
obtained from the utility-grid to trip traditional OC protection
relays/devices. In contrast, microgrid operated in islanded
mode has a fault current of almost 5 times the normal current
is obtainable.


4) ISLANDING CONDITION DETECTION
Islanding detection helps the smooth and safe transition of
the grid-connected operational mode of the microgrid to
the islanding mode [90]. Islanding is a state in which the
VOLUME 10, 2022 38903
M. W. Altaf et al.: Microgrid Protection Challenges and Mitigation Approaches
FIGURE 9. Schematic diagram of the test system for islanding condition
detection.
microgrid is detached from the utility grid when any fault
occurs on the utility grid side or LOM condition occurs [91].
The LOM is a condition when the utility grid supply is
isolated and still the part of the utility load is connected
with a microgrid. The schematic diagram of the islanding
detection scenario is shown in Figure 9. On the left side
of the PCC in Figure 9, the utility grid can be seen and


5) BLINDING OF PROTECTION
In a conventional radial power system, the pickup value of
the OC relay has been configured according to the total
impedance value of the feeder. The pickup value of the
OC relay is set in such a way that its value is always
greater than feeder rated current and smaller than the lowest
value of short-circuit current. With the integration of DER
into this conventional radial power system, this power
system act as a microgrid. Blinding of protection occurs

6) PROTECTION DEVICES(PDS)/SWITCH SELECTION
The selection of PDs depends on the requirement of
operational speed, fault current availability, and voltage level;
it can range from the conventional CB to fast speed solid state
switch. As the switching speed of PDs depends on the system
current and voltage specifications, the switching speed of PDs
increases as the fault current level increases [38], [45].
The needed response speed by the PCC switch of
microgrid depends upon the sensitivity of loads connected
in microgrid [23]. Loss of microgrid stability occurs when a
fault arises on the utility-grid area or inside the microgrid then
a high-speed protection switch is required, especially when

7) FALSE TRIPPING/SPURIOUS SEPARATIONS
False trips may occur as a result of the PCC switching
devices’ failure to recognize whether the fault is inside the
microgrid or on the utility grid area. Spurious separation
occurs due to electromechanical relays and sophisticated
microprocessor PDs which are operated based on the
real-time frequency and voltage values at PCC. Currently,
transfer trip is the only suitable method to dodge false tripping
and fast tripping is produced at PCC breaker from breaker of
utility substation [112], [113].
The utility and microgrid operations are lesser impacted
due to false tripping as microgrids can recover their normal
activity after isolation. The false tripping at PCC becomes
costly because of decreasing the lifetime of PDs and

8) RE-SYNCHRONISATION
The accessibility of equipment for re-synchronization of a
microgrid at PCC should be considered then microgrid can
reconnect with the utility grid as long as the utility grid is fit to
reconnect entire loads formerly disconnected during islanding. The process of reconnection and re-synchronization can
either be automatic or manual and it can need a few seconds
to a few minutes depending upon the characteristics of the
system. Different types of re-synchronization schemes have
also been discussed in [118], [119] and there are three major


9) AUTO RECLOSER PROBLEMS
Auto recloser is a PD as the CB. In CB, once switching
occurs, it does not come to the original state unless changed
manually or by the control system. But in auto-recloser, once
switching occurs, it comes to the original state automatically
after pre-defined time by the auto-recloser control system
action [121]. The schematic diagram of the auto-recloser
problem is shown in Figure 32. For example, if the fault
occurs in the system, the CB of the auto-recloser opens, then
after some predefined interval, it again closed and checks
whether the fault was removed or not. If the fault is removed
then it continues to supply, otherwise, it trips again for a larger
time than previous trips. It continues to return to its closed
state after every trip and check for the fault is automatically
removed or not. If the fault persists after a few auto-recloser
trips, the auto-recloser turns to a permanently open state. The
ANSI standard device number for the controller is 79 [122].
Auto-recloser is needed at the power system location



<!-- the chatGpt summery for the challegnes -->
Certainly, let's summarize the AC Microgrid Protection Challenges highlighted in the provided section:

1. **Dynamics in Fault Current Magnitude:**
   - Intermittent fault current contribution from renewable-based DERs, shifting fault levels during grid-connected and islanded modes.

2. **Faults/Events During Grid-Connected Mode:**
   - Challenges during grid-connected mode, emphasizing the need for fault ride-through capacity in DERs and rapid isolation of faulty parts.

3. **Faults/Events During Islanded Mode:**
   - Disparate challenges during islanded mode, with fault currents up to five times the normal current, requiring different protection strategies.

4. **Islanding Condition Detection:**
   - Importance of detecting islanding conditions for a smooth transition, with a specific mention of LOM (Loss of Mains) conditions and the need for safe disconnection.

5. **Blinding of Protection:**
   - Issues arising from configuring protection relays in traditional radial power systems, leading to blinding of protection in microgrids with DER integration.

6. **Protection Devices/Switch Selection:**
   - Selection of protection devices based on operational speed, fault current, and voltage levels, considering a range from conventional circuit breakers to fast solid-state switches.

7. **False Tripping/Spurious Separations:**
   - Challenges related to false trips and spurious separations due to the failure of switching devices to distinguish faults within the microgrid or on the utility grid.

8. **Re-Synchronization:**
   - Considerations for the re-synchronization process, which can be automatic or manual, impacting the time required for the microgrid to reconnect with the utility grid.

9. **Auto Recloser Problems:**
   - Issues with auto recloser devices, which automatically close after a predefined interval, checking for fault removal. Persistent faults lead to permanent opening, with implications for system reliability.

Your research and project likely address several of these challenges by proposing mitigation approaches and innovative solutions. Highlighting how your work contributes to overcoming these challenges will strengthen the significance of your research in the field of AC Microgrid Protection.

<!-- suumerey two chatgpt -->

Certainly, here's a concise summary of the AC Microgrid Protection Challenges outlined in the provided section:

1. **Intermittent Fault Currents:** Renewable-based DERs contribute intermittently to fault currents, affecting fault levels during both grid-connected and islanded modes.

2. **Challenges During Grid-Connected Mode:** Ensuring fault ride-through capacity in DERs and rapid isolation of faulty parts are crucial during grid-connected mode.

3. **Challenges During Islanded Mode:** Islanded microgrids face different challenges, with fault currents up to five times the normal current, necessitating unique protection strategies.

4. **Islanding Condition Detection:** Detecting islanding conditions is essential for a smooth transition, particularly concerning Loss of Mains (LOM) conditions.

5. **Blinding of Protection:** Configuration issues in traditional radial power systems can lead to protection blinding in microgrids with DER integration.

6. **Protection Devices/Switch Selection:** Selecting appropriate protection devices is vital, considering operational speed, fault current, and voltage levels.

7. **False Tripping/Spurious Separations:** Challenges arise from devices failing to distinguish faults within the microgrid or on the utility grid, leading to false trips.

8. **Re-Synchronization:** Re-synchronization processes, whether automatic or manual, impact the time required for microgrids to reconnect with the utility grid.

9. **Auto Recloser Problems:** Issues with auto recloser devices, including automatic closure after a predefined interval and the risk of permanent opening due to persistent faults.

Your research likely addresses several of these challenges, proposing mitigation approaches and innovative solutions to enhance AC Microgrid Protection.