# Web Turtle Commander

Turtle robot tele-operation via a web application


---

### Presentation topics

- Architecture presentation
- MVP Demonstration
  - Setup and running
  - Web Application
  - REST interface
  - ROS interface
- Questions


---

### Architecture - Objectives

Turtle robot tele-operation via a web application

- Web application
  - Real time position and attitude
  - Historic position
  - Tele-operation
  - Assign goals
  - Pause/Resume movement towards goal


---

### Architecture - Objectives

- REST Endpoints
  - Assign goals
  - Pause/Resume movement
  - Tele-operation
- ROS
  - Simulator
  - turtle_commander_node
    - Goals
    - Pause/Resume
    - Speed control


---

### Architecture - High Level

![Architecture](https://raw.githubusercontent.com/gonzodepedro/turtle_commander_presentation/master/images/all.png)


---

### Architecture - ROS

![Ros Architecture](https://raw.githubusercontent.com/gonzodepedro/turtle_commander_presentation/master/images/ros.png)


---

### Architecture - REST

- Endpoints:
  - POST /goal/x/y
  - PUT  /pause     {'pause' : true}
  - POST /teleop/x/z


---

### Architecture - WEBAPP

- WebSockets
  - Handle realtime position and attitude
  - REST to send commands


---

### MVP

- MVP Demonstration
  - Setup and running
  - Web Application
  - REST interface
  - ROS interface

---

### Presentation topics

- Architecture presentation
- MVP Demonstration
  - Setup and running
  - Web Application
  - REST interface
  - ROS interface
- Questions

---

### Questions

?
