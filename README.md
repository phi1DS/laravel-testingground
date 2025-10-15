## Testing github actions

Path to action config: .github/workflows/run-tests.yml

To run localy :

1. Install act (https://github.com/nektos/act).

2. Ensure docker is running.

3. Run the following command to trigger a push on main simulation:
```
./bin/act push
```
