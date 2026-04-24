# FlightHub 2 Task ID Revealer
 
Chrome extension that reveals task IDs in the DJI FlightHub 2 Task Plan Library so you can match completed tasks to their S3 upload folders without opening the Network tab.
 
## Why
 
FlightHub 2's Task Plan Library shows task names and status but not task IDs. When S3 sync is enabled, completed flights upload to folders named by `flight_task_id` — which means finding a task's S3 folder normally requires opening DevTools, inspecting the `/flight-tasks` API response, and manually matching the task in the JSON to the row in the UI.
 
This extension does that match for you. It listens to the same API response the page is already loading and displays a floating panel on the right edge of the Task Plan Library with the Task ID for every task. One click copies the ID to your clipboard.
 
## Privacy
 
The extension does not transmit, store, or share any data. See the [privacy policy](./privacy-policy.html).
 
## License
 
MIT
