# T2F
Create features (Gherkin) from Trello User Stories
<br>
Trello API REST. Gherkin language
<br>
<br>
- Command Line in verbose mode
<br>
<br>
<img src="/img/Command_line.png">
<br>
- Feature File Example
<br>
<br>
<img src="/img/feature_file_example.png">
<br>
- Properties File template
<br>
File_name = conf.ini
<br>
[trello_conf]
<br>
url = https://api.trello.com/1/members/
<br>
username = your_Trello_user_name
<br>
key = your_Trello_key
<br>
token = your_Trello_token
<br>
[gherkin_conf]
<br>
path = /usr/shared/
<br>
feature = Feature: 
<br>
scenario = Scenario:
<br>
given = Given
<br>
other = and 
<br>
when = When 
<br>
then = Then
<br>
language = #language en,es,fr
<br>
size = @small @medium @large
<br>
freq = @checkin @hourly @daily
<br>
scale = @local @database @network
<br>
ambit = @functional @system @smoke
<br>
