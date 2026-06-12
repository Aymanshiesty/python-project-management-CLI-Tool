Project Tracker CLI 
An enterprise-grade Command-Line Tool built in Python to track structural user allocations, milestones, and task matrices.

Installation and Activation Protocol
Initialize Virtual Container Matrix via Pipenv:
pipenv install --dev
Execute Automated Verification Tests:
pipenv run pytest
Command Execution Examples
Register a New User:
pipenv run python main.py add-user --name "Alice" --email "alice@dev.com"
Bind a New Project:
pipenv run python main.py add-project --title "API Gateway" --user "Alice" --due "2026-11-20"
Inject a Dependent Task:
pipenv run python main.py add-task --project "API Gateway" --title "Configure CORS Policies" --assignee "Alice"
Flag a Task as Complete:
pipenv run python main.py complete-task --id "1"
View All Projects:
pipenv run python main.py list-projects
