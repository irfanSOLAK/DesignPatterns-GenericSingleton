# GenericSingleton-DesignPatterns
Generic Singleton Design Pattern for Unity

# Description
You can use the Singleton class as a base class. The Singleton class (child) inherits the fields and methods from the MonoBehaviour class (parent). It is an implementation of the Singleton Design Pattern. The singleton class ensures that there is only one instance of the child class(es).

# How to use
The GameBehaviour class is an example of how to use it. It is derived from the Singleton class and can be used as a GameManager. Usage: 

public class ScriptName : Singleton<ScriptName>
{
    // Class implementation
}

As many new classes as desired can be derived from the singleton class, such as AudioManager, NotificationManager, and so on.

# How to access GameBehaviour class
You can access the GameBehaviour class and its public methods, variables, etc. using the following code:

GameBehaviour.Instance.MethodName();

Please note that the code should be written in C# syntax for Unity, and make sure to replace "ScriptName" and "MethodName" with the appropriate names for your specific implementation.
