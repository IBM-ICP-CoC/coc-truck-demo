# CoC's IEAM Truck Demo 

## Assets for IEAM truck demo

`dev3`: shutdown (shows as inactive in UI)

`dev8`: stop docker (shows as error in UI)


Node Properties:

`dev1` - `dev5` (policy-orig.json)
```
has-temperature-sensor=true
payload-type=standard
has-gps=true
vehicle-type-code=TR23
```

`dev6` - `dev10` (policy-refigerated.json)
```
has-temperature-sensor=true
payload-type=refrigerated
has-gps=true
vehicle-type-code=TR18
```

`dev11` - `dev15` (policy-simple.json)
```
has-temperature-sensor=false
vehicle-type-code=TR09
```

`dev16` - `dev20` (policy-minimal.json)
```
openhorizon.example=helloworld
```


