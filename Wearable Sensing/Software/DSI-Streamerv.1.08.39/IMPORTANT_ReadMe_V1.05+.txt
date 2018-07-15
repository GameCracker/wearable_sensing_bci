IMPORTANT NOTE:

Change in Version 1.05+ affects data output

In adding support for the new wireless trigger hub, DSI-Streamer now automatically corrects for  EEG data timing offset with reference to trigger timing.  This 53ms timing offset was previously reported in the .csv file header but left to the user to manually adjust for. With the wireless trigger hub, the trigger timing offset is only 41ms instead of 53ms, if the trigger was sent through wire. (this does not have to do with whether the EEG data is being sent via wire or via bluetooth, just if the trigger is wired or wireless)

To simplify matters for the user, DSI-Streamer now forces the user to select whether they are using Wired or Wireless Triggers, and adjusts timing automatically. The saved data files now correct for time offset between EEG data and trigger data.

This only affects you, if you were using this adjustment in your analysis, in that in data collected with DSI-Streamer version 1.05+ you should not do that anymore.

Please email support@wearablesensing.com if you have any questions or concerns about this change.

