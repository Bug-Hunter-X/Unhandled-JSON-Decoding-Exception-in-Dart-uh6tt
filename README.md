# Unhandled JSON Decoding Exception in Dart

This repository demonstrates a common error in Dart applications: neglecting to handle exceptions that may occur during JSON decoding. The `jsonDecode` function can throw a `FormatException` if the JSON data is malformed or invalid.

The `bug.dart` file showcases code that lacks proper exception handling. The `bugSolution.dart` file provides a corrected version that addresses this issue by using a `try-catch` block to handle potential `FormatException` exceptions.  The improved code logs the error and prevents the application from crashing.