# Challenge Specification

Working on their own, a senior developer can write an entire application in five hours.
A mid-level developer would take ten hours to get the same amount of work done.
A junior developer would need twenty hours to write the same app.

Developers working together can combine their expertise, so two mid-level engineers can each do half the work, completing the app in five hours.

By default, a team consists of one senior dev, two mid-level devs, and four junior devs.

Write a function called calculate_development_time which takes the following parameters:
num_senior_devs
num_mid_devs
num_junior_devs

If no arguments are supplied, your function should return the time in hours it takes for a default-sized team to complete the app. If arguments are supplied, the function should return the time it would take the specified team to complete the app. For example:

calculate_development_time() returns 3.3333...
calculate_development_time(1, 4, 4) returns 2.5