# Performance Load Testing Using jemeter 
## Project Summary:
This project involves performance testing using **Apache JMeter** . The test simulates a load of up to **120,000 users over 12 hours**, covering:

- User login
- Booking creation
- Booking search

Due to server limitations, some errors were observed under high stress. Both **Load Testing** and **Stress Testing** were conducted, and reports are included.


## Technologies Used
- Apache JMeter
- Java 
- HTML Extra Report plugin
- Excel

---


## Prerequisites
- Java installed and added to PATH
- Git installed
- JMeter (v5.5 or higher)
- Excel for opening `.xlsx` report

---

## How to Run This Project

- bash
- git clone https://github.com/rifat/booking-performance-test.git
- cd booking-performance-test
- jmeter -n -t booking.jmx -l booking.jtl -e -o Reports

## Load Testing Report
# 5 minutes
![image](https://github.com/user-attachments/assets/a362ecf5-8d58-4321-b070-e53b3ad5ed97)
# 10 Minutes
![image](https://github.com/user-attachments/assets/09dc06b4-d8b5-4f14-b05c-dc0e8650925a)
# 20 Minutes
![image](https://github.com/user-attachments/assets/6a2298de-36ff-40db-a3dc-7e0c19f56844)
## Stress Testing Report
# test3.1
![image](https://github.com/user-attachments/assets/24d7b0c8-d578-4062-a47f-74941c3ca855)
# test 3.2
![image](https://github.com/user-attachments/assets/6d781212-cea6-4c5f-b621-400a7fc6c1c4)





