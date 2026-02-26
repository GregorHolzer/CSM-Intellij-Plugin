# IntelliJ Plugin for Visualizing, Deploying, and Monitoring Collaborative State Machines

The goal of this project is to develop a plugin for IntelliJ IDEA that enhances the development of Collaborative State Machine (CSM) applications. The plugin integrates visualization, deployment, and runtime monitoring capabilities directly into the development environment.

## Features

### Visual Representation of State Machines

The plugin generates a graphical representation of Collaborative State Machines based on their source code.  
This visualization enables developers to better understand the structure, states, and transitions of a State Machine during development.

---

### Deployment to Cirrina Runtimes

The plugin supports the deployment of State Machine instances to existing Cirrina runtimes.  
It enables developers to transfer State Machine definitions from the IDE to configured runtime environments for execution.

To enable this functionality, the Cirrina Runtime must be modified to receive and execute 
State Machines during operation.

---

### State Machine Monitoring

The plugin can connect to a Cirrina Runtime to monitor active State Machine instances
and display their current state graphically.

To enable this functionality, the Cirrina Runtime must be modified to 

- provide a list of all running State Machines
- provide the current state of any running State Machine