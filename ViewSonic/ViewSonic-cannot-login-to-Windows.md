# ViewSonic: cannot login to Windows

## ISSUE

User cannot login to Windows on ViewSonic. The user is entering their full name (i.e. Greg Doud) rather than the Google email without the domain (i.e. gdoud).

Another problem is that if the domain is not showing `STCS0`, no login will work.

## RESOLUTION

The username should be the Google email without the domain information (i.e. `gdoud`)

To change the domain when logging in, place the `STCS0` at the beginning of the Google email followed by a backslash:

    STCS0\gdoud

You should see the domain change to STCS0.