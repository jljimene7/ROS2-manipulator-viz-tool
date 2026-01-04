# TODO

- Develop hardware interface for 6DoF manipulator
    1. create ./hardware/include/manipulator/manipulator.hpp
    2. declare ManipulatorHardwareInterface as subclass of `hardware_interface::SystemInterface`.
    3. override and implement 4 public functions of ManipulatorHardwareInterface class that return a `hardware_interface::CallbackReturn`:
        - on_init
        - on_configure
        - on_activate
        - on_deactivate
    4. override and implement 2 public functions of ManipulatorHardwareInterface class that return a `hardware_interface::return_type`:
        - on_init
        - on_configure
        - on_activate
        - on_deactivate



## Questions

- What should the robot do when it turns on?
- What safety does does the robot need to emulate to ensure safe operation?
- What should the robot do when the user logins to control it?
- What should the robot do when the user logs out?
