# RitoPls
#### The ultimate toolkit to debug League of Legends (client, not gameclient)

## FinalesFunkeln
This tool allows you to read and see all of the RTMP packets being sent by the client or the server

Extermly useful tool; however, the src has not been updated. The compiled beta has fixed some of the bugs with the first versions and does not crash as often. 

SRC: https://github.com/frostycpu/FinalesFunkeln

Compiled Beta: https://github.com/eddy5641/RitoPls/releases/tag/ToolKit

## Burp
I am using Burp as a HTTPS proxy for the league of legends client. This uses a local MITM attack. I utilize a custom tool for forcing the http requests to go though the Burp proxy.

Burp no longer works, I am now using a specialized attack (code injection) to analyzes https packets. See FakRiotLCU
