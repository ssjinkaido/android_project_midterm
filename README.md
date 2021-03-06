# Covid-19 Tracker App

# Mobile application midterm project group 15
## Members:
Nguyễn Xuân Tùng BI10-188 (leader)\
Nguyễn Quang Anh BI10-012\
Trần Hồng Quân BI10-149\
Lữ Khánh Huyền BI10-083\
Vũ Đức Chính BI10-024

## Data
The data comes from Open Disease Data API (https://corona.lmao.ninja/)

## Features
This project is a Covid-19 tracker app made in Java. The main function is to keep tracks of covid cases and vaccinated numbers
- [x] Global cases, active, deaths, recovered 
- [x] Search country based on their name
- [x] View specific country with its covid number
- [x] Pie chart to display covid cases and line chart to display vaccinated numbers
- [x] Map for someone who wants to visualize covid cases. We use google map API
- [x] Covid-19 information: what is covid? symptoms, precautions.
- [x] Login, logout using OTP (Firebase)
- [x] News related to covid
- [x] Report covid cases(map, address)
- [x] Sort death, recovered, total cases

## Libraries
* [Retrofit](https://github.com/square/retrofit): For fetching Api.
* [Volley](https://github.com/google/volley): Another way for fetching Api
* [Pie Charts](https://github.com/PhilJay/MPAndroidChart): A powerful 🚀 Android chart view / graph view library.
* [Google Maps Clustering for Android](https://github.com/sharewire/google-maps-clustering): display clustering on maps
* [Glide](https://github.com/bumptech/glide): For images loading
* [Android Navigation Component](https://github.com/android/architecture-components-samples/tree/master/NavigationBasicSample): For navigation between fragments
* [Pin Code](https://github.com/ChaosLeung/PinView): To display 6 number code OTP
* [Country Code Picker](https://github.com/hbb20/CountryCodePickerProject): Country code picker, default Vietnam +84
* Firebase and google services for map, OTP, captcha

## UI
![DashBoard](https://github.com/ssjinkaido/android_project_midterm/blob/master/screenshots/DashBoard.PNG)
![Global Cases](https://github.com/ssjinkaido/android_project_midterm/blob/master/screenshots/Global%20Cases.PNG)
![Country List](https://github.com/ssjinkaido/android_project_midterm/blob/master/screenshots/CountryList.PNG)
![Specific Country](https://github.com/ssjinkaido/android_project_midterm/blob/master/screenshots/SpecificCountry.PNG)
![Country Map](https://github.com/ssjinkaido/android_project_midterm/blob/master/screenshots/CountryMap.PNG)
![Detailed Corona](https://github.com/ssjinkaido/android_project_midterm/blob/master/screenshots/Corona.PNG)
![Corona Info](https://github.com/ssjinkaido/android_project_midterm/blob/master/screenshots/Info.PNG)
![News](https://github.com/ssjinkaido/android_project_midterm/blob/master/screenshots/News.PNG)
![Profile](https://github.com/ssjinkaido/android_project_midterm/blob/master/screenshots/Profile.PNG)
![Login](https://github.com/ssjinkaido/android_project_midterm/blob/master/screenshots/Login.PNG)
![Register](https://github.com/ssjinkaido/android_project_midterm/blob/master/screenshots/Register.PNG)
![Report Cases](https://github.com/ssjinkaido/android_project_midterm/blob/master/screenshots/ReportCases.PNG)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.