# project_dashboard
A project of mine based on my server and an old tablet ive found.
I basically want to create a Website that i show on my Tablet that im gonna hang on the wall with which i can do multiple things around my room / monitor some things.

## Features

### Must have Features
- Show outside weather
- Show the telemetry of my server
- Alarmclock && Normal Clock
- Calendar (Maybe linked to my Apple calender)

### Nice to have Features
- Voice assistant (but im not quite sure how I would implement that)
- Temperature and humidity inside (would need a separate inside sensor that would talk to my server probably via an ESP32)
- Smart room control (would need apropriate lights and other things)
- network monitor (show ping, internet speed)
- change brightness if its day/night (the tablet is not rooted so i will probably implement it by just lowering the brightness of the website {idea from ChatGPT because idk how})

### non features
- be connected outside of my house
- control other rooms

## interface idea

### Main Dashboard
The main dashboard should show the most important things at one look
Weather, show if my server is OK, tell the time and if an alarm is set. Show the appointments on my calender for the day.
I will do it in tiles excluding the time, this will be shown at the top of the screen. If you click on a tile you will see the more specific dashboard of each feature

### Weather dashboard
Show more specific things like sunrise/sunset, Weather Radar and so on

### Server dashboard
Show the telemetry eg. CPU / RAM / Storage usage, but also if my containers / VMs are running

### Alarm dashboard
Set, edit and delete alarms

### Calender dashboard
show a week calender where i can see all appointments of mine and set new ones

### Note to the NTH Features
if I implement them, i will edit this README so you can see where they are shown in the dashboard