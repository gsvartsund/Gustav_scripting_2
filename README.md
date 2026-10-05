# Assignment for scriping 2 autumn 2026

**Repository for the asssignment 2**

**Preface**
I made this program a little bit more advanced than the first since i think i know python a little bit better, it is still not perfect and it could probably be solved faster and more efficient. All of the code is explained by comments over each code block in the code. I decided not to reuse my old code that much because it was way to simple and did not really work the way i wanted to, therefore i just took some of the code from main.py and reused but it is mostly new code. The only Ai i used was Claude and the built in vscode agent for debugging and help with testing. 

**How to run:**
Either just run the main.py file or it should work with this command if you want to do it from the terminal: "python3 main.py --profiles data/participants.csv \ --sessions data/fitness_sessions.csv data/fitness_sessions_invalid.csv --output output".

**Why its the way it is**
I built the code so it reads the given CSVs makes sure every piece of data is validated, disregards invalid data and runs valid data against, lastly it write it in reports. One report for text, one report for CSV and a report for invalid data. I decided not to write the invalid data in the CSV format, i could have i just did not find it relevant. 


- The data folder holds the given CSVs.
- Fitness analyzer holds the files necessary:
- -init.py is a normal initiation file
- -analysis.py summarizes and classfies the data.
- -exceptions.py handles the error types
- -loader.py reads CSVs and makes them into objects.
- -reports.py is made to write the outputs
- -validators.py helps make sure that the ID matches the reading pattern
- -main.py runs the whole program and loads participants.
- Tests is a folder containing the unit tests for testing that everything works as it should.
