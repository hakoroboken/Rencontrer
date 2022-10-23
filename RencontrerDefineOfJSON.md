# Rencontrer define of JSON

## Connection initialize
```json
[
    {
        "tag": "CI1",
        "pin": PIN_INT,
        "app_ver":VERSION_INT,
        "app_type":"APP_TYPE",
    }
]
```

```json
[
    {
        "tag": "CI2",
        "robo_ip": "IP_ADDRESS",
        "robo_ver":VERSION_INT,
        "robo_type":"ROBOT_TYPE",
    }
]
```

```json
[
    {
        "tag": "CI3",
        "app_token": "APP_TOKEN",
    }
]
```

```json
[
    {
        "tag": "CI4",
        "robo_token": "ROBO_TOKEN",
    }
]
```

## Data transform (DT)
```json
[
    {
        "tag": "DT1",
        "payload": "USR_DATA",
        "robo_token": "ROBO_TOKEN",
    }
]
```
```json
[
    {
        "tag": "DT2",
        "payload": "xxxx",
        "app_token": "APP_TOKEN",
    }
]
```

## Connection check (CC)
```json
[
    {
        "tag": "CC1",
        "app_token": "APP_TOKEN",
    }
]
```
```json
[
    {
        "tag": "CC2",
        "robo_token": "ROBO_TOKEN",
    }
]
```