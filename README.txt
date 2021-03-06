Integration with Tibber, with Pulse and Watty support.

New: Pulse and Watty now supports displaying current for phase 1, 2 and 3. In order to show new values in Homey you will need to remove and re-add Pulse/Watty device.
New: Home hourly and daily consumption report is now disabled by default. You can enable it in the Home device's advanced settings.

Flow cards

Device: Home
Triggers
- Price changed
- Temperature changed
- Current price is at today's lowest
- Current price is at today's highest
- Current price is at the lowest among the next [x] hours
- Current price is at the highest among the next [x] hours
- Current price is [x] percent below today's average
- Current price is [x] percent above today's average
- Current price is [x] percent below average of the next [y] hours
- Current price is [x] percent above average of the next [y] hours
- Consumption report (triggers when new data is available, normally once a week. Every hour if you have a Pulse device)
- You can use price level to make smart decisions based on the electricity price. These are local to the current day and include:
  VERY_EXPENSIVE
  EXPENSIVE
  NORMAL
  CHEAP
  VERY_CHEAP
  Please note that these are relative bands where VERY_EXPENSIVE can apply for several individual hours or continuous time slots for example.

Conditions
- Current price below/above
- Outdoor temperature below/above
- Current price is at today's lowest
- Current price is at today's highest
- Current price is at the lowest among the next [x] hours
- Current price is at the highest among the next [x] hours
- Current price is [x] percent below today's average
- Current price is [x] percent above today's average
- Current price is [x] percent below average of the next [y] hours
- Current price is [x] percent above average of the next [y] hours

Actions
- Send push notification (through Tibber app)

Device: Pulse and Watty
Triggers
- Power changed
- Current for phase 1, 2 or 3 changed
- Consumption since midnight changed
- Cost since midnight changed
- Daily consumption report
