message ThaiProfile {
  required string role = 1; // Electrical engineer
  required Skills skills = 2;
  required Projects work = 3;

  message Skills {
    required string embedded = 1; // C, Arduino, STM32
    required string pcb = 2; // KiCad, Eagle
    required string control = 3; // Robotics, automation
    required string tooling = 4; // Git, CI, Makefiles
  }

  message Projects {
    required string automation = 1; // Sensor systems and motor drivers
    required string robotics = 2; // Small scale actuator control
    required string pcbs = 3; // Custom boards for prototypes
  }
}
