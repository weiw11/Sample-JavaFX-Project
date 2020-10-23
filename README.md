# Sample-JavaFX-Project
Sample JavaFX project with Java 11 using IntelliJ

This can be used as a template to kick start your own JavaFX Project.

## When creating from scratch
`.fxml` files must be in resources folder and be loaded with the following code in `Main.java` extending Application

```Java
FXMLLoader loader = new FXMLLoader(getClass().getResource("/SAMPLE.fxml"));
```
