# bloc_tutorial_simple

A bloc tutorial with one feature

## Overview

The application uses a feature-driven directory structure. This project structure enables the ability to scale the project by having self-contained features. In this example there is a single feature (the counter itself) but can scale to more complex applications which can have hundreds of different features.

### Key Tech Areas
- BlocObserver: used to observe all state changes in the application.
- BlocProvider: Flutter widget which provides a bloc to its children.
- BlocBuidler: Flutter widget that handles building the widget in response to new states.
- Cubit: for simple use cases - define state and methods to expose to change the state.
- Bloc: advanced use cases - define the states, events and the EventHandler.
- Barrel: a file used to organize and export a group of related classes, functions and variables to make them accessible to the other parts of the code.
- context.read: used for retrieving a bloc instance in order to add an event within onPressed callbacks.