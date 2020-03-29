# Electricity_Control
Automatic Electricity Meter Reading Based on Image Processing and control electricity based on IOT.


Abstract—This idea introduces a system based on image processing to obtain efficiently and
accurately reading of the electricity digital meter. In this system the back camera of the mobile
phones is used to acquire the image of the electricity meter. The system then applies a
sequence of image processing functions to automatically extract and recognize the digits of the
meter reading image. This image goes through three main stages: preprocessing which ends up
with cropping the numeric reading area, segmentation of individual digits using horizontal and
vertical scanning of the cropped numeric area, and recognition of the reading by comparing
each segmented digit with the digits templates.
After comparing reading of electricity meter to check current reading with daily limit (unit of
electricity meter) .Suppose you set daily limit as 10 unit per day then our system captures image
of electricity meter and processing on it checks it near about daily limit. Suppose in a day 8 unit
is used then it will send a message to the user to control your home appliances. Your electricity
usage is near about the daily limit.
Then the user can control the home appliances by smart phone using application through IOT
control. In some cases users aren't able to see the message that your daily limit is crossed then
it will automatically off your home appliances as per set your priority.
This system will help you to control your electricity and save energy.
