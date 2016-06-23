# say_day
Returns the day of the week from a Python 3.5 datetime objects as a string. ('Monday')

```python
from datetime import datetime

def say_day(x=datetime.now()):
    """Return the day of the week as a string."""
    if x.weekday() == 0:
        return 'Monday'
    elif x.weekday() == 1:
        return 'Tuesday'
    elif x.weekday() == 2:
        return 'Wednesday'
    elif x.weekday() == 3:
        return 'Thursday'
    elif x.weekday() == 4:
        return 'Friday'
    elif x.weekday() == 5:
        return 'Saturday'
    elif x.weeday() == 6:
        return 'Sunday'
        ```
Like this:

```python
say_day(datetime.now())
```
>>> Monday
