# check-labels-test
repo to test the check labels github action


Next steps:
Add check labels job to existing DBT pipeline workflow. Should go before the DBT jobs and we need to add
```needs: check-labels``` to the DBT jobs so that they only run if check-labels passes
