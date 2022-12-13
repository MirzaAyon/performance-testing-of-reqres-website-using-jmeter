## Performance testing of [reqres](https://reqres.in/)

demo website : [reqres](https://reqres.in/)
- https://reqres.in/

### Steps of creating JMeter test
- Start JMeter
- Test plan creation
- Thread group
- Sampler(http)
- Listener
- Run
### Steps of creating thread properties
- 1,00000 users will use this website within 12 hours
- So total users 1,00000 and total time - 12*60*60 = 43,200 second
- now number of threads(users) - 1,00000 / 43,200 = 2.31 per second
- in 2 seconds it will be 4.63 users
- so I fixed it as 5 users in 2 seconds
- with 1 loop count
- so our number of users - 5
- numbers of second is - 2
- number of loop count - 1

### Some GUI report elements
- View Results Tree
- Summary Report
- Aggregate Report
### Some Assertions
- Response assertions
- Duration assertions
- Size assertions

### Final Test Report
I’ve completed performance test on frequently used API for [reqres](https://reqres.in/).

- Concurrent Request - 10
- Avg TPS for Total Samples - 
- Total Concurrent API requested - 10
- Average time - 4043.50 milliseconds
### Live site of the report

https://visionary-druid-41f410.netlify.app/





