# Instructions for running all tests
To run all the tests, we can do this:
```bash
flutter test
```

To run integration app test:
```bash
flutter test integration_test/app_test.dart
```

To run app performance:
```bash
flutter drive \
  --driver=test_driver/perf_driver.dart \
  --target=integration_test/perf_test.dart \
  --profile \
  --no-dds
```

# Summary of test coverage and results
## Unit Tests
File: test/models/favorites_test.dart
Task: Adding and removing items in the Favorites model.
Result: All assertions pass.

## Widget Tests
File: test/home_test.dart
Task: Listview shows up, scrolling, tap icon buttons.
Result: All assertions pass.

## Integration Tests
File: integration_test/app_test.dart
Task: adds three items to favorites, Navigates to the favorites screen and Removes items.
Result: All assertions pass.


File: integration_test/perf_test.dart
Task: Measures performance.
Result: Performance metrics collected.

# Challenges you faced and how you overcame them
Overall there is no issue during making the test files and try run it all.