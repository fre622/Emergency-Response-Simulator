# BY [FIREHIWOT TESFAYE  ID: 1501207]
#Emergency Response Simulator
Overview
The Emergency Response Simulator is a console-based C# application where players act as emergency dispatchers. Over a series of turns, incidents occur randomly around the city, and the player must assign the correct emergency unit to handle each situation.

Good decisions earn points, while mistakes cost points!

How to Play
Each turn, a random incident (Crime, Fire, or Medical emergency) will appear at a random location.

Available Emergency Units (Police, Firefighters, Ambulance) will be listed if they can handle the incident.

The player chooses which unit to dispatch.

Points are gained for correct choices and lost for mistakes or unavailable units.

Project Structure
Program.cs — Main game logic: sets up incidents, units, scoring, and player interaction.

EmergencyUnit.cs — Abstract base class defining common properties and behaviors of all emergency units.

Police.cs — Handles Crime incidents.

Firefighter.cs — Handles Fire incidents.

Ambulance.cs — Handles Medical incidents.

Incident.cs — Represents an emergency incident with a type and location.

Key Classes

Class	Description
EmergencyUnit	Abstract base class for all units.
Police	Handles crime-related incidents.
Firefighter	Handles fire-related incidents.
Ambulance	Handles medical emergencies.
Incident	Represents an incident needing response.
How to Run
Open the project in Visual Studio or your favorite C# editor.

Build the solution to restore any necessary dependencies.

Run the program.

Follow the console prompts to dispatch emergency units!

Sample Gameplay
kotlin
Copy
Edit
--- Turn 1 ---
Incident: Fire at Market
1. Firefighter Unit 1
Choose a unit (1 - 1): 1
Firefighter Unit 1 is putting out fire at Market.
Current Score: 10
Future Improvements (Optional Ideas)
Add more unit types (e.g., SWAT, Rescue Helicopter).

Introduce incident severity levels (e.g., minor, major).

Time-based scoring (faster responses earn more points).

Multi-unit responses for large incidents.

Author
Developed for the Emergency Response Simulation assignment.

C# Console Application using Object-Oriented Programming principles.
