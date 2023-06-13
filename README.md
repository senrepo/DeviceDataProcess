# Device Data Processing - Homework

## Requirements
![Requirement Doc](https://github.com/senrepo/DeviceDataProcess/blob/main/Files/Cargo-%20DeviceDataTakeHomeAssignment.pdf)

![Json File 1](https://github.com/senrepo/DeviceDataProcess/blob/main/Files/DeviceDataFoo1.json)

![Json File 2](https://github.com/senrepo/DeviceDataProcess/blob/main/Files/DeviceDataFoo2.json)

## Tech Stack Details
    .NET Core 6.0 Class Libarary
    Nunit
    Moq
    Microsoft Visual Studio Community 2022 (64-bit)
    Nuget

## Test Results
![Test Results (unit & integration)](https://github.com/senrepo/DeviceDataProcess/blob/main/Files/TestResults.PNG)

![Integration Tests Output Files](https://github.com/senrepo/DeviceDataProcess/blob/main/Files/JsonOutputFiles.PNG)

## Output Json

 ```json
     [
        {
            "CompanyId": 1,
            "CompanyName": "Foo1",
            "DeviceId": 1,
            "DeviceName": "ABC-100",
            "FirstReadingDtm": "2020-08-17T10:35:00",
            "LastReadingDtm": "2020-08-17T10:45:00",
            "TemperatureCount": 3,
            "AverageTemperature": 23.149999999999995,
            "HumidityCount": 3,
            "AverageHumdity": 81.5
        },
        {
            "CompanyId": 1,
            "CompanyName": "Foo1",
            "DeviceId": 2,
            "DeviceName": "ABC-200",
            "FirstReadingDtm": "2020-08-18T10:35:00",
            "LastReadingDtm": "2020-08-18T10:45:00",
            "TemperatureCount": 3,
            "AverageTemperature": 24.149999999999995,
            "HumidityCount": 3,
            "AverageHumdity": 82.5
        },
        {
            "CompanyId": 2,
            "CompanyName": "Foo2",
            "DeviceId": 1,
            "DeviceName": "XYZ-100",
            "FirstReadingDtm": "2020-08-18T10:35:00",
            "LastReadingDtm": "2020-08-18T10:45:00",
            "TemperatureCount": 3,
            "AverageTemperature": 33.15,
            "HumidityCount": 3,
            "AverageHumdity": 91.5
        },
        {
            "CompanyId": 2,
            "CompanyName": "Foo2",
            "DeviceId": 2,
            "DeviceName": "XYZ-200",
            "FirstReadingDtm": "2020-08-19T10:35:00",
            "LastReadingDtm": "2020-08-19T10:45:00",
            "TemperatureCount": 3,
            "AverageTemperature": 43.15,
            "HumidityCount": 3,
            "AverageHumdity": 92.5
        }
    ]
```