# SFC /SCANNOW to fix Windows

## ISSUE

Sometimes a Windows laptop will fix issues that may cause problems like:

    * Corrupted files that may cause Windows updates to stall during download

## RESOLUTION

- A shutdown and restart may be required
- Open CMD as ADMINISTRATOR
- Type `sfc /scannow`

You hope to see a message like this:

    Windows Resource Protection found corrupte files and successfully reparied them.
    For online repairs, details are included in the CBS log file located at windir\Logs\CBS\CBS.log. For example C:\Windows\Logs\CBS\CBS.log. For offline repairs, details are included in the log file provided by the /OFFLOGFILE flag.