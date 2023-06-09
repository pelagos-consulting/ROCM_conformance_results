# ROCM conformance test results

This repository is just to provide some general information on the state of HIP support for different GPU archiectures.

# Generating a test result

* Install and run [hip-tests](https://github.com/ROCm-Developer-Tools/hip-tests).
* Get the percentage pass rate from the test.
* Put the architecture and ROCM version into the table if an entry doesn't already exist for your architecture and ROCM version.
* Generate a pull request to insert your test result into the table.

# Test results

Architecture | ROCM version | hip-test branch | Total tests | Tests failed | Pass rate (%) |
|:--:|:--:|:--:|:--:|:--:|:--:|
|gfx906 | 5.4.3 |  rocm-5.4.x | 1022 | 28 | 97 |
|gfx1035 | 5.4.3 |  rocm-5.4.x | 1022 | 42 | 96 |
| compute_86 | 5.4.3 | rocm-5.4.x | 915 | 6 | 99 |
