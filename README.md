# Frontend
Frontend - FLASK microservice application

# Running
Run `python app.py` then enter `localhost:5000` on your internet browser. (To work correctly you need to run it parallel with the Backend service).

To learn more about the application please check our Introduction to programming course on youtube:
https://www.youtube.com/watch?v=sCpVNizJbiE

## Run test

```python
python3 -m pytest --cov=. --cov-report xml:test-results/coverage.xml --junitxml=test-results/pytest-report.xml
# or 
pytest --cov=.
```

# Branches:
By selecting different branches you can get the sample code that you should have in you repository at the end of the selected block:

|Branches  | Block  | Description  | 
|---|---|---|
| main | CI/CD 1 | Basic application version |
| dockerfile | Docker 2 | Added docker container build files |


