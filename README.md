# rovservo
Rover with servo motor instances

# Limitations
- including a model with a plugin have no way to identify the plugin
- the name goes back to the global model's name
- adding a plugin does not override the original but results in plugins duplications
- Gazebo model editor cannot move included model as an entity but moves every block of it separately, while it has a different behaviour moving elements together when a model is inserted from the side pane
- Gazebo breaks the default position of the edited model and there is no way to move elements together
- due to these limitations including models is not feasible, so insertion resulting in content copy will be used
- Cannot insert a model in an orthogonal view, as it runs away to infinity
