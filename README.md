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

If the command passed as parameter for pepi runs succesfully, it will
create a nice notification. Otherwise, it will warn you with an error message.

## Setup

In Debian, you need to install the following packages:
* libnotify-bin
* sound-theme-freedesktop

If you want to install it from the source code, run the following script:
```
$ ./install
```

