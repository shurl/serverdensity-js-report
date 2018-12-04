# serverdensity-js-report
A javascript based report showing core metrics and averages of those metrics over a selected time period.

## Usage - Device Report
1. Clone this repo
2. Open [device_report.html](device_report.html) with your web browser (You don't need to serve it locally)
3. Enter your Server Density API Token, Device ID and your required dates. JS does the rest.

## Usage - Service Status Report
1. Clone this repo
2. Open [service_status_report.html](service_status_report.html) with your web browser (You don't need to serve it locally)
3. Enter your Server Density API Token and your required dates. JS does the rest.

## Usage - Service Response Time Report
1. Clone this repo
2. Open [service_time_report.html](service_time_report.html) with your web browser (You don't need to serve it locally)
3. Enter your Server Density API Token and your required dates. JS does the rest.

## Demo
You can test this out online, thanks to GitHub Pages
#### Device
[https://shurl.github.io/serverdensity-js-report/device_report.html](https://shurl.github.io/serverdensity-js-report/device_report.html)
#### Service Status
[https://shurl.github.io/serverdensity-js-report/service_status_report.html](https://shurl.github.io/serverdensity-js-report/service_status_report.html)
#### Service Response TIme
[https://shurl.github.io/serverdensity-js-report/service_time_report.html](https://shurl.github.io/serverdensity-js-report/service_time_report.html)

## Security
As this report uses your Server Density API token which is considered a secret it is reccomended that you review the code before use.

## Dependencies
Makes use of:
* [jQuery](https://jquery.com/)
* [Google Charts](https://developers.google.com/chart/)
* [flatpickr](https://flatpickr.js.org/)
