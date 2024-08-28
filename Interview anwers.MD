OOPS Concepts:

Encapsulation involves restricting direct access to some of the object's components. I had a project called grower portalit has a class called FieldBoundary that encapsulates the properties of a field and the operations that can be performed on it.FieldBoundary class encapsulates all details about a field's boundary, such as its ID, grower's name, and boundary coordinates, and only exposes relevant methods to interact with this data.

Inheritance allows a class to inherit the attributes and methods of another class Real Time example Grower Portal had different types of sensors, such as water level sensors or weather sensors, that share common characteristics. These can be represented using inheritance. In this example, WaterLevelSensor inherits from the base class Sensor, reusing its attributes and methods while adding specific functionalities like displaying water level.

const is for compile-time constants and must be assigned at declaration, while readonly can be set at declaration or in the constructor, allowing runtime assignment. const is static by nature, but readonly allows more flexibility for instance data.


ToString() can throw a NullReferenceException if the object is null, as it's a method called on the object instance itself.
Convert.ToString() handles null gracefully by returning an empty string ("") instead of throwing an exception.
ToString() can be overridden for custom string representations, while Convert.ToString() uses the default conversion logic.
