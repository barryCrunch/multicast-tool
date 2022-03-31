# Multicast-Tool
A small multicast tool that can be used to test communication. It has the ability to both send and receive data

## General Usage
```
$> python multicast_tool.py -h

usage: multicast_tool.py [-h] --group GROUP --port PORT [--source SOURCE] [--send] [--ttl]

optional arguments:
  -h, --help       show this help message and exit
  --group GROUP    Multicast Group Address
  --port PORT      Multicast Port
  --source SOURCE  Source Address
  --send           Use to send multicast data.
  --ttl            Set TTL (Default=1)
```

## Receive Data
```
python multicast_tool.py --group 224.0.0.34 --port 10000
```

## Send Data
```
python multicast_tool.py --group 224.0.0.34 --port 10000 --send
```
