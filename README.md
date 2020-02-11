# weather_forecast
To get input from user about his location and display the weather there using the concept of data scraping from the web!

**Project by Gargi Das**
Hello!

Given below is a detailed description of how I am planning to execute my code and why I choose the particular elements I using.
Language: C
        1. I have learnt C in just my last semester, so it's syntax is fresh in my mind and I am comfortable with it.
        2. I wanted to enhance my knowledge of C to further levels.
    

Creating a command line prompt:
          I am using a do while loop here so that the CLI is executed at least once where the user is able to enter his command.
          The commands to be used are:
              1. begin--> to start the system
              2. exit--> to end the CLI
              3. The user should enter the serial number given aginst his choice from the displayed menu. 
              4. The user needs to enter the name of his city **_only_** when the he is prompted for "city".
              5. The user needs to enter his country when/if prompted.
              6. He can know about the metadata of weather forecast.

Scraping weather data:
          I plan to use tools from Openweathermaps API. To use this we need to create an account in it. It provides data using JSON file             endpoints.
          I plan to collect data in a JSON file from openweathermaps and then deserialize the JSON file into Python strings.
          Then I will check if the string for the code key of city is not 404, then I will proceed to print the description, temperature,           humidity and timezone of the string.(I assume that the conditions of temperature, humidity and description are mentioned                   specifically.)

   Collecting metadata:
          The Website and it's URL should work as the metdata.( I still need to look up this part!)

          
          
