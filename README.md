# Test: Bad Index Configuration

## Overview
This test project contains a `pyproject.toml` with an invalid PyPI index URL to verify error handling.

## Test Scenario
- Invalid PyPI index URL configuration
- Tests dependency tree builder's handling of custom index failures
- Expects clear error messages about index connectivity

## Expected Behavior
The dependency tree builder should:
- Detect the invalid index URL
- Provide a clear error message indicating index failure
- Suggest checking the index URL and network connection
- Not hang or crash on index resolution failure

## Part of Test Suite
This is part of the Phase 3 Broken Source Configurations test suite.