# aprsd
Amateur radio APRS client which listens for APRS messages and replies.  This is essentially a way for you to send commands to your PC from your Amateur radio and have it respond with something interesting.  Perhaps you could make a bot?  Like WXBOT?  It currently just "echoes" what it receives.

Please change callsign and aprs password throughout code (not just at top).

Example usage:

```

craiger@pc:~/ham/aprsd$ ./aprsd.py
# aprsc 2.1.4-g408ed49
# logresp KM6LYW-9 unverified, server T2TEXAS
# aprsc 2.1.4-g408ed49 31 Oct 2017 17:07:02 GMT T2TEXAS 205.209.228.93:14580
KM6LYW>APY01D,ALDER*,WIDE2-1,qAR,N6VUD-15::KM6LYW-9 :Test - please reply{19
Received message______________
From       : KM6LYW
Message    : Test - please reply
Ack number : 19
Sending ack __________________
To         : KM6LYW
Ack number : 19
Sending message_______________
To         : KM6LYW
Message    : Echo: Test - please reply
# aprsc 2.1.4-g408ed49 31 Oct 2017 17:07:22 GMT T2TEXAS 205.209.228.93:14580
# aprsc 2.1.4-g408ed49 31 Oct 2017 17:07:42 GMT T2TEXAS 205.209.228.93:14580
# aprsc 2.1.4-g408ed49 31 Oct 2017 17:08:02 GMT T2TEXAS 205.209.228.93:14580

```
