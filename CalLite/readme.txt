This model is CalLite_SacSJR_021213, plus various fixes and code cleanup by Nancy

-Need to update so it has changes DWR made in CalLite in model CL_SharingFix_Shortage_040413_W2.  DONE

-Need to update with changes Jun made for GUI results viewing purposes.  This model is CalLite_SacSJR_021213_Jun_GUI_changes.  DONE

-Need to update with any more changes to make consistent with CalSim_Future_May2013_SA model.  DONE except for:

-American River deliveries may need changes to make consistent with CVO preferences.
-In COA files, some conditional statements in CalSim have this condition, but CalLite doesn't: MRDO_final < C406[PRESETUP] + 0.1
-Wheelcap.wresl doesn't have fixes re C407_whlcv  and C407_whljp that the BOR CalSim model had, to prevent wheeling carriage water when no wheeling
-VAMP export cap is not turned off yet.  Need to think about how to do this, since we have a switch already for this (though in conjunction with D-1641 export cap).
-How to handle OID/SSJID cut variables when VAMP is in the model, but the OID Fall purchase is not.  This occurs for CalLite when a Future run is done with VAMP turned on.





