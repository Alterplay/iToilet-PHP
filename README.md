# Back-end iToilet

## In params (GET)
- port - Sensor port. Default 2 (optional)

## Out (JSON)
- light_value - Sensor value (int)
- light_status - Light On/Off (bool)
- light_change - Last light status change (timestamp)
- sensor_status - Sensor works Yes/No (bool)


```
{
  "light_value": 3408,
  "light_status": false,
  "light_change": 1394187631,
  "sensor_status": true
}
```