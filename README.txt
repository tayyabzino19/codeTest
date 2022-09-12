Ok thanks for shortlisting me.
The code is looking awesome for me because I have not used the repo pattern, and literally, this code is awesome at my level. But some suggestions are from my side.
Instead of using hardcoded role names in .env file why we are not using the laravel recommended package for roles and permissions which is spatie?
We can also apply laravel queues to emails
In the below-listed methods, most code is repeated we can do these things in one or two methods by adding if else statements the methods are
    - isNeedToDelayPush
    - isNeedToSendPush
    - changeCompletedStatus
    - changeStartedStatus
    - ignoreExpiring
    - ignoreExpired
    - ignoreThrottle