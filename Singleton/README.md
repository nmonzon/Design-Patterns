# Singleton

DEFINICION:

Asegura que exista una unica instancia de una clase concreta. 
Permite una accesibilidad global a esa instancia, teniendo acceso desde cualquier parte del proyecto.

DESVENTAJAS:
No son facil de testear

EJEMPLO DE USO:
![image](https://user-images.githubusercontent.com/19937843/114795534-2997bd00-9d65-11eb-8707-cf864f62c9c4.png)

OTRO EJEMPLO
Public class DatabaseManager{
    static let shared = DatabaseManager()
}
