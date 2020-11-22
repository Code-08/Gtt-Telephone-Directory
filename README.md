# Gtt-Telephone-Directory

This app is designed to export data from the 2018 Gtt Telephone Directory to excel/pdf/xml format. 

You can download the windows application here: [Link to Application](http://google.com). Once the zip file is downloaded, unzip it and run the exe file. Don't worry, it's completely safe.


## Advanced Filter Examples

You can mix and match the filters to suit your needs. However, I wouldn't suggest you use this feature if you're not a developer!

- ```Number.StartsWith("258")```
> Result: Everyone who has a number that starts with "258" will be exported.


- ```Number.EndsWith("07")```
> Result: Everyone who has a number that ends with "07" will be exported.


- ```Name.Contains("22")```
> Result: Everyone who has a number that contains with "22" will be exported.


- ```Number == "232-1234"```
> Result: Everyone who has a number that is "232-1234" will be exported.


- ```Number == "232-1234" && Address.Contains("Line Street")```
> Result: Everyone who has a number that is "232-1234" AND Lives in "Line Street" will be exported.


- ```Number == "232-1234" || Number == "256-4321"```
> Result: Everyone who has a number that is "232-1234" OR "256-4321" will be exported.
