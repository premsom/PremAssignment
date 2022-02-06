# Tfl Web API Assignment

This project Consumes Tfl GetRoad Web API and returns the given road status-
<ul>
  <li>How to build the code</li>
		- This project developed using .Net core 3.1 and Visual Studio 2019. Open the solution in Visual Studio 2019 or above version and build it.
		- The project will run in Visual Studio Code as well. Open the folder with source code in Visual Studio Code and build using "dotnet build" command.
  <li>How to run the output</li>
		- app_key and app_id is configurable in appsettings.json. Set these values before running the app.
		- Api_Url currently set with value "https://api.tfl.gov.uk/Road/" in appsettings.json. This can be changed as needed.
		- Press F5 or Ctr F5 to run the application in Visual Studio 2019.
		- Enter the Road in Console and then press enter. The Road details will display on console as per Road status.
		- For Visual Studio Code run with "dotnet run" command and follow same steps as above.
  <li>How to run any tests that you have written</li>
		- In Visual Studio, go to Test-> Run All Tests. All tests should show pass status in Test explorer. 
  <li>any assumptions that you’ve made</li>
		- The application input expecting just one road value. The application may not behave properly if pass multiple road values.
  <li>anything else you think is relevant</li>
		- The API response will always return one record in response object for given road.
		- Logging and exceptions handling has not been implemented.
</ul>
