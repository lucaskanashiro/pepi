# Pepi

CLI to notify when what you are doing is done! Pepi provides a very simple
set of tools to configure ad-hoc alarms and to schedule task and notifications.

Pepi allows one to create both sound and visual notifications to warn you when
the job is done! For example, when you want to run a time-consuming command
you can use **pepi** to output a sound to warn you when it is finished,
similar to the **time** CLI:

```
$ pepi sudo apt-get update
```

## Dependencies

In Debian, you need to install the following packages:
```
$ sudo apt-get install libnotify-bin pulseaudio-utils
```
