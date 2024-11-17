# Development of an Application for GPS Measurements Visualization

**Objective:**
To develop an application that reads data from an emulated GPS measurement unit provided as a Docker image and displays the position of the object and satellites on a graph in Cartesian coordinates.

# Theoretical Information

**Trilateration** is a method used to determine the position of an object in space by measuring its distance to three or more points with known coordinates. This method is widely applied in geodesy, navigation, and other fields where accurate location determination is essential.

*How It Works*

The principle of trilateration involves mathematically calculating the position of a point based on measured distances from it to three different points. In a two-dimensional space, at least three known points are required, while in three-dimensional space, at least four are needed. Each known distance is considered the radius of a sphere (in three-dimensional space) or a circle (in two-dimensional space) centered at a known point, and the position of the target object is determined by the intersection of these spheres (or circles).

![image](https://github.com/user-attachments/assets/a4dcb76d-c32a-4d6a-a67b-97cf39517f39)

To calculate the position of an object in two-dimensional space using trilateration, a system of equations representing circles around points with known coordinates is used. Each circle corresponds to the distance from a point to the object being sought.

# Tasks

**Develop an Application to Display Object and Satellite Positions:**

- Develop a web application that connects to a WebSocket server and reads data about the positions of satellites and the object.
- Display the received data on a graph in Cartesian coordinates. You can use the Plotly library or another graphing library.

**Data Processing and Visualization:**

- Process the data received through WebSocket and display the positions of the object and satellites on the graph.
- Add the ability to change GPS measurement parameters using API requests.

**Graph Configuration:**

- Display the coordinates of the satellites and the object in Cartesian coordinates.
- Use different colors or styles for points representing satellites and the object.

# Solution

**User interface of the application:**

![image](https://github.com/user-attachments/assets/3748abf9-4f8c-4a05-ba4c-a2d021551b36)



