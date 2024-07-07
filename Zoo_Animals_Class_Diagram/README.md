# Zoo Animals System Class Diagram

## Description
You are designing a system to keep track of information about animals in a zoo.

### Animals:
- **Horses** (horses, zebras, donkeys, etc.),
- **Felines** (tigers, lions, etc.),
- **Rodents** (rats, beavers, etc.)

### Characteristics:
Animals are characterized by species with most of the information stored being the same across all groupings:
- Species name
- Weight
- Age
- etc.

### System Requirements:
The system should also be able to:
- Get the dosage of specific medications for each animal => `getDosage()`
- Calculate feeding schedules => `getFeedSchedule()`

The logic to perform these functions will be different for each grouping. For example, the feeding algorithm will be different for horses and tigers.

## Class Diagram
Design a class diagram to address the situation described above using the polymorphism model.

![Zoo Animals Class Diagram](https://github.com/MeNasy/UML_Diagram_Projects/blob/main/Zoo_Animals_Class_Diagram/Screenshot%20from%202024-07-07%2013-33-00.png)
