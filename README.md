# matrix-send

Send messages to matrix from command line. Usage example:

```
$ ./matrix-send.py "Hello world!"
```

## Configuration

Copy the config.ini.template file to ```~/.config/matrix-send/config.ini``` and fill the fields:

```
[DEFAULT]
endpoint=https://matrix-server:8448/_matrix/
access_token=
channel_id=
msgtype=m.notice
```

### Getting the access_token and channel_id values

Please, refer to matrix' documentation:
https://matrix.org/docs/guides/client-server.html
