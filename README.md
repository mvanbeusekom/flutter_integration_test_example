This project is an example on how to setup Flutter integration testing separate
from the application under test.

The project contains the following folders:

- `counter`: this folder contains the standard Flutter counter application.
- `counter_e2e`: this folder contains the integration test code that is used to
drive the screens in the counter application and verify it's behaviour.

To run the end-to-end tests take the following steps:

1. Change into the `counter_e2e` folder.
2. Run the `flutter test integration_test/counter_e2e.dart` command.


Note, to run the end-to-end tests on an emulator make sure the desired emulator
is started before running the `flutter test` command. To run the tests on an 
real device make sure it is connected to the development machine. In case of 
testing on a real iOS device make sure to setup the appropriate signing 
certificates.
