Aon Win 10 Pro i had to set vi group editor:

Computer Configuration > Administrative Templates > Windows Components > Remote Desktop Services > Remote Desktop Session Host > Connections.

From here, first set the Restrict Remote Desktop Services user to a single Remote Desktop Services session parameter to Disabled.

Next, double-click on Limit number of connections and then set the RD Maximum Connections allowed to 999999.


