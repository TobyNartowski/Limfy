

# <img src="/.misc/limfy_logo.png" height="27"> Limfy
Health tracker that processes your heart rate and physical activity in real time.

## Functionality
The solution consists of developed device based on ESP-32 microcontroller, mobile application written for Android-based smartphones, which displays and passes data between the device and the server and the server itself written in Java programming language analyzing and persisting data. The solution provides the user with information about his heart rate and physical activity, statistical probability of getting sick with particular types of diseases and allows to automatically send a rescue message with the user’s location, when dangerous fall is detected by the device. 

## What's inside
Project is based on Spring Boot and uses following technologies:


* Server
	* Java 11
	* Spring Framework
		* Spring Core
		* Spring Boot
		* Spring Data
		* Spring MVC
		* Spring Security
	    * Spring Cloud
	* Hibernate / MySQL
* Application
	* Android
	* Retrofit
	* MPAndroidChart
* Hardware
	* Arduino

## Media
Prototype of device and wireless charger
<div style="text-align:center;">
	<img src="/.misc/image_device.png" />
</div>

Application user interface
<div style="text-align:center;">
	<img src="/.misc/image_app1.png" />
</div>
<div style="text-align:center;">
	<img src="/.misc/image_app2.png" />
</div>

