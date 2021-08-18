# NR-JT-Packet_Decode
Node-Red &lt;-> *JT* Packet Decode Flow

Always check /Beta for newest update

08.18.21 - (Update) Fixed issue with --rig-name parameters passed in UDP packets. Optomized parsing of packets and matching Countries to callsigns, as well as default Lat/Lon coordinates. Optomized msg.payload data flow between functions/flows by reducing unneeded messages.

Latest version (08/09/21) of my Node-Red Decoding of WSJT/JTDX Packet Decodes, With Country Names for Origin Station and Destination Station in QSO Messages, as well as Grid Decode of Transmitting station, with bearing and distance. If no Grid given, default coords are used for bearing and distance based on included country location defaults.

Turn on message outputs to inspect parsed messages to inspect message payloads.

Set your Grid Square in the 'MY GRID Location function.

This works without internet access, all parsing of data, conversions of locations and distance calculation are done via functions. No other nodes are required to use this.

Enjoy!
