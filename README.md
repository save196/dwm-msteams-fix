!!! MS Teams in its most recent versions started to use the default notification system, so this patch is not needed anymore.

Tested fixed versions of MS Teams > 1.3.00.25560

# dwm-msteams-fix
Patch to fix Microsoft Teams notifications problems in dwm window manager.

Microsoft Teams uses its own notification system that vanilla dwm do not handle properly.
This patch do not want to encourage the use of Microsoft Teams since it is proprietary software. 
However, in many working environments it is the main teams communication software, so in the case you must use Microsoft Teams, this patch can be handy.

## Installation

To apply this patch, run:
```bash
  curl https://raw.githubusercontent.com/save196/dwm-msteams-fix/master/dwm-msteamsnotificationsfix-20200912-3857c41.diff | git apply --reject
```
from your dwm folder, then rebuild and reinstall dwm.
