# Tech's Gmail login doesn't have admin privileges

## ISSUE

The account used to log into the school laptops works fine but does not have admin privileges. For example, when trying to start SYSTEM INFORMATION in ADMIN, the credentials are rejected.

Working with Peter Prieto (Xerox) to give my credentials admin privileges, Service Request #05683396 asked me to power down the laptop then start it, log in, then try to use my credentials on an admin dialog. I did this on the SYSTEM INFORMATION (ADMIN), but my credentials failed.

## RESOLUTION

Peter called and said he has elevated my gdoud@saintcolumbanschool.org to admin privilege. we tested it on two different laptops and it worked on both.

If this does not work, start cmd and run the command `gpupdate /force` then restart the laptop.

After the restart, the Microsoft account should have admin privileges.