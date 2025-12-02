```protobuf

<img src="https://avatars.githubusercontent.com/u/106393765?v=4" alt="banner" width="100%"/>

message TranQuangThai {
  required string role = 1; // Electrical engineer
  required Projects work = 3;

  message Skills {
    required string embedded = 1; // C++, Arduino, STM32
    required string pcb = 2; // AutoCad, Proteus
    required string control = 3; // Robotics, Automation
  }

  message Projects {
    required string automation = 1; // Sensor systems and driver boards
    required string robotics = 2; // Actuator control
    required string pcbs = 3; // Custom boards
  }
}
