## Use Case

This automation manages reminders and tracking for putting out and bringing in wheelie bins based on collection schedules. It uses binary sensors to detect whether the green or blue bin is scheduled for collection today or tomorrow. Notifications are sent to specific devices with actionable options (e.g., "It's out" or "Dismiss") to confirm actions like putting bins out or bringing them back. Input booleans track the bin statuses (e.g., out or back), and daily resets ensure everything is initialized for the next schedule. The system also identifies user-specific actions using context IDs to log who performed the tasks, making the process seamless and efficient.


## Prerequisites 

 [hacs_waste_collection_schedule](https://github.com/mampfes/hacs_waste_collection_schedule) *OR* full day calendar entries can also be used

#### Helpers Needed
1. Input Booleans:
- input_boolean.blue_bin_out: Tracks whether the blue bin is out.
- input_boolean.green_bin_out: Tracks whether the green bin is out.
- input_boolean.blue_bin_back: Tracks whether the blue bin is back.
- input_boolean.green_bin_back: Tracks whether the green bin is back.

2. Input Datetimes:

- input_datetime.bin_put_out_time: Specifies the time by which bins should be put out.
- input_datetime.bin_take_in_time: Specifies the time by which bins should be brought back in.

## Notes 

This checks every day to verify if there is either a bin collection due the current day or the next, if there is then this will trigger a notification 
