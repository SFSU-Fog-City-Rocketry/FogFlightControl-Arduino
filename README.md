# FogFlightControl-Arduino

This is the code that runs onboard the vehicle during flight. The flight control system is designed to control rockets, drones, and any other vehicle we may want to pilot.

For the frontend/backend parts that get run offboard, see [FogFlightControl-Base](https://github.com/SFSU-Fog-City-Rocketry/FogFlightControl-Base)

## Project Structure:
- ``assets``
  - Things like images, JSON files, and other non-code elements that go into our system.
- ``src``
  - ``libraries``
    - Various shared code files.
  - ``utilities``
    - Things that do specific tasks for us, like math related functions.
  - ``Main``
    - Contains the main ``ino`` file that gets compiled to the target.
- ``.gitignore`` - Files to be ignored by Git to prevent merge hell.
- ``LICENSE``
- ``README``