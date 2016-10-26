# T2F
Create features (Gherkin) from Trello User Stories
<br>
Trello API REST. Gherkin language
<br>
<br>
- Command Line in verbose mode
<br>
<img src="/img/Command_line.png">
<br>
- Feature File Example
<br>
<img src="/img/feature_file_example.png">
<br>
- Properties File template
File_name = conf.ini
<br>
[trello_conf]
url = https://api.trello.com/1/members/
username = <your_Trello_user_name>
key = <your_Trello_key>
token = <your_Trello_token>
[gherkin_conf]
path = /usr/shared/
feature = Feature: 
scenario = Scenario:
given = Given  
other = and 
when = When 
then = Then
language = #language en,es,fr
size = @small @medium @large
freq = @checkin @hourly @daily
scale = @local @database @network
ambit = @functional @system @smoke
