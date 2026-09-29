# Daily Weather App
 
**Framework:** Flutter  
**Programming Language:** Dart  
**Backend and frontend communication:** REST API  

## Introduction

We made an app giving importance to functionality more than User Interface. We were able to bring these features in our weather app.

## Features

### 1) Daily and Hourly Forecast

The data of daily and hourly forecast will be there in the app.

### 2) Search Bar

A search bar will be there from where we can know the weather information of various cities.

### 3) Celsius and Fahrenheit Conversion

If user doesn’t want to see weather information in Celsius unit then he or she can go to settings option to alter it to Fahrenheit scale.

### 4) Current Location Access

When the app will be installed for the first time, the app will require the data of user’s current location using geolocator plugins for which permission option will pop up. Then user can access to the home screen where information like temperature, division, city and others will be seen.

### 5) Five Days Weather Forecast

A horizontal ListView will be there which will give us information of every 3 hours of next 5 days.

### 6) City Suggestions

Initially there will be some suggestions of cities.

### 7) Animated Background

There will be usage of static images in the background which will be in motion to make the app more realistic.

## Why We Made Weather App?

Now the thing is why we made weather app whereas in every smartphone weather app is installed by default or it can be seen directly from site. Why would anyone bother to download app? Mainly our main focus was on REST API. Because now-a-days, software industry uses REST API a lot for their apps as they need to be connected with server. With REST API, we can send data to the server, retrieve data from the server, update existing data, delete data and perform authentication operations. Similar functionalities can be achieved using Firebase too. But not everyone uses Firebase. Many companies create their own backend systems and provide services through REST APIs. Many can buy a domain and then build backend with Laravel. For advanced level, backend can be created with Node.js or Spring Boot. But mobile app developers prefer using REST APIs because there is no extra hassle of creating backend infrastructure when a service provider has already created the backend system for us. We will just grab that data from there and show it into our app. There is no need to be concerned with handling the weather database directly. REST API will be provided to us and we will just call that to bring data.  
We used HTTP library. There are more popular libraries out there like Retrofit, Dio and other networking-related libraries.As HTTP library is Dart’s official package, we used it.

Learning Resource: Lead Academy

Know more information about the implementation in the pdf.
👉 **[View Live Demo](https://daily-weather-coral.vercel.app/)**
