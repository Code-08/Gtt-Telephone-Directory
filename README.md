# Gtt-Telephone-Directory (Guyana)

This app is designed to export data from the 2018 Gtt Telephone Directory to excel/pdf/xml format. 

You can download the windows application here: [Click here to download](https://github.com/JerryBerryJW/Gtt-Telephone-Directory/raw/main/Gtt%20Telephone%20Directory%20Setup.msi). Download and Install the msi file. Don't worry, it's completely safe.


## Advanced Filter Examples

You can mix and match the filters to suit your needs. However, I wouldn't suggest you use this feature if you're not a developer!

- ```Number.StartsWith("258")```
> Result: Everyone who has a number that starts with "258" will be exported.
<br />

- ```Number.EndsWith("07")```
> Result: Everyone who has a number that ends with "07" will be exported.
<br />

- ```Name.Contains("22")```
> Result: Everyone who has a number that contains with "22" will be exported.
<br />

- ```Number == "232-1234"```
> Result: Everyone who has a number that is "232-1234" will be exported.
<br />

- ```Number == "232-1234" && Address.Contains("Line Street")```
> Result: Everyone who has a number that is "232-1234" AND Lives in "Line Street" will be exported.
<br />

- ```Number == "232-1234" || Number == "256-4321"```
> Result: Everyone who has a number that is "232-1234" OR "256-4321" will be exported.
<br />

- ```(Number == "232-1234" || Number == "256-4321") && (Number.StartsWith("456") || Number.EndsWith("55"))```
> Result: Everyone who has a number that is "232-1234" OR "256-4321"   AND   has a number that starts with "456" OR ends with "55" will be exported.
<br />
<br />

I guess you have an idea by now how this works. These are just a few examples of using different filters. You can do your own experimenting.
