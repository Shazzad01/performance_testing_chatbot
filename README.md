# performance_testing_chatbot
I will do performance testing on 10 different user journeys. The user journeys will be run with 15k concurrent users, The site will be load tested for 20k users.


## How to run this project
- Save the .jmx file in bin foulder
- Create a report foulder 
- Open with JMeter
- Run Command:  
```console 
jmeter -n -t filename.jmx -l report\filename.jtl
```
- Run Command for Report: 
```console 
jmeter -g report\filename.jtl -o report\filename.html
```

## Technology used:
- Jmeter
- Blazemeter

## Prerequisite:
- JVM
- Java SE Development Kit
- JMeter
- Blazemeter

## Creating JMeter test :
- Start JMeter
- Test plan creation
- Thread group
- Sampler (http)
- Listener
- Run

## Listener :
- view results in tree
- Aggregate report
- Graph results
- Simple data writer

## Assertions :
- Response assertion
- Duration assertion
- size assertion
- html assertion
- XML JSON assertion
- XPATH Assertion

## Newman Report Summary:
![Screenshot_1](https://user-images.githubusercontent.com/112342961/233830438-8b323218-5695-4754-a1ce-32ae7f9a8f33.png)

![Screenshot_2](https://user-images.githubusercontent.com/112342961/233830448-51564387-afc0-4880-a2dc-7f83bfed54c3.png)
![Screenshot_3](https://user-images.githubusercontent.com/112342961/233830461-3b0232e8-7b40-4c2a-8f2e-0803d586d495.png)
![Screenshot_4](https://user-images.githubusercontent.com/112342961/233830469-02699f90-6af2-475f-8981-a3514adf4b3c.png)
![Screenshot_5](https://user-images.githubusercontent.com/112342961/233830523-2c85f538-5240-4a1d-9bb7-9eaf07991a0d.png)
![Screenshot_6](https://user-images.githubusercontent.com/112342961/233830533-de83a452-84af-4863-a44f-49df90a12993.png)
