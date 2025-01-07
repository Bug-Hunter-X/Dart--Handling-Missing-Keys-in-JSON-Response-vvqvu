# Dart: Handling Missing Keys in JSON Response

This repository demonstrates a common error in Dart when handling JSON responses from APIs: attempting to access a key that may not exist.  The `bug.dart` file shows the problematic code, while `bugSolution.dart` provides a solution.

The issue arises when the JSON response doesn't contain the expected key.  The provided solution uses the `containsKey` method to check for the existence of the key before accessing it, preventing runtime errors.  This ensures more robust error handling in your Dart applications.
