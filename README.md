# unidad_4
Realizacion de una aplicacion utilizando flutter

Primero que nada comence con mi programacion buscando mi libreria

![image](https://user-images.githubusercontent.com/79875834/115592741-381c3200-a299-11eb-8e91-611f9a04e8b3.png)

despues de descargarla de la manera en la que se realizaron la clase procedi a rewalizar lo demas que es mi programacion declarando y comenzando a probgramar

![image](https://user-images.githubusercontent.com/79875834/115593034-9c3ef600-a299-11eb-8ed9-15e4f62f2804.png)

Aqui declaro mis objetos y les doy una funcion a cada uno de ellos

![image](https://user-images.githubusercontent.com/79875834/115593258-ea53f980-a299-11eb-8d61-a52a21126d3f.png)

y de esta manera finalizo mi programaciòn 

![image](https://user-images.githubusercontent.com/79875834/115594099-f7251d00-a29a-11eb-890b-7ca8a1ab9d3d.png)

Aqui se encuentra todo el programa que se utilizo en visual estudio 

import 'package:flutter/material.dart';
 
void main() {
  runApp(MyApp());
}
 
class MyApp extends StatefulWidget {
  @override
  _MyAppState createState() => _MyAppState();
}
 
class _MyAppState extends State<MyApp> {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
          appBar: AppBar(
            title: Text('Flutter RaisedButton - tutorialkart.com'),
          ),
          body: Center(
            child: Column(children: <Widget>[
              Text(
                'Raised Buttons with Different Properties',
                style: TextStyle(fontSize: 16),
              ),
              RaisedButton(child: Text('Disabled Button')),
              RaisedButton(
                child: Text('Default Enabled'),
                onPressed: () {},
              ),
              RaisedButton(
                child: Text('Text Color Changed'),
                textColor: Colors.red,
                onPressed: () {},
              ),
              RaisedButton(
                child: Text('Color Changed'),
                color: Colors.green,
                onPressed: () {},
              ),
              RaisedButton(
                child: Text('Button with Padding'),
                padding: EdgeInsets.all(20),
                onPressed: () {},
              ),
              RaisedButton(
                child: Text('More Rounded Corners'),
                color: Colors.purpleAccent,
                shape: RoundedRectangleBorder(
                    borderRadius: BorderRadius.all(Radius.circular(16.0))),
                onPressed: () {},
              ),
              RaisedButton(
                child: Text('Elevation increased'),
                elevation: 5,
                onPressed: () {},
              ),
              RaisedButton(
                child: Text('Splash Color as red'),
                splashColor: Colors.red,
                onPressed: () {},
              ),
              RaisedButton(
                child: Text('Zero Elevation'),
                elevation: 0,
                onPressed: () {},
              ),
              RaisedButton(
                onPressed: () {},
                textColor: Colors.white,
                padding: const EdgeInsets.all(0.0),
                child: Container(
                  decoration: const BoxDecoration(
                    gradient: LinearGradient(
                      colors: <Color>[
                        Color(0xFF0D47A1),
                        Color(0xFF1976D2),
                        Color(0xFF42A5F5),
                      ],
                    ),
                  ),
                  padding: const EdgeInsets.all(10.0),
                  child: const Text('Gradient Color'),
                ),
              ),
          ]))),
    );
  }
}
  
  Y de esta manera se ve mi aplicacion en fisico en el celular 
  ![image](https://user-images.githubusercontent.com/79875834/115595387-79621100-a29c-11eb-8ece-b4fc151553b8.png)

![image](https://user-images.githubusercontent.com/79875834/115595418-83840f80-a29c-11eb-8f01-411121c0cb9c.png)

![image](https://user-images.githubusercontent.com/79875834/115595449-8c74e100-a29c-11eb-858f-a840d9c77dc7.png)
![image](https://user-images.githubusercontent.com/79875834/115595473-94348580-a29c-11eb-8cf2-58baad32dafb.png)


