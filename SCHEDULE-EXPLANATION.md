The initial cron expression of 0 3 * * * indicates that the job will be run once per day at 8 pm UTC.
This is because the cron fields from left to right are minute, hour, day (month), month, day (week).
Since we leave the day of the month, month, and day of the week as wildcards (any), 
the time expression (hour 3, minute zero) runs daily.
By the same logic, my new cron expression (59 23 * * *) runs daily at 11:59 PM.
