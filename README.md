Task 1 Submission

When given a patients UUID, this allows a user to select a number of observations to automatically fill a letter to that patient (.docx).

Deployment manual

Clone repository and open in VS Code

Create a virtual environment (example at https://docs.python.org/3/tutorial/venv.html) to import all dependencies. If you are not using a virtual environment, install FHIR-Parser, python-docx and flask.

Run GOSH data on localhost:5000 or localhost:5001. Alternately, you can fill in the credentials required in FHIRworks_2020/dotnet-azure-fhir-web-api/appsettings.json and run command 'dotnet run'.

Use command 'flask run --port 8000' to run app.py