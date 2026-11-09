# MP08_Bloc1_A04 – Hola mundo

## Descripción

He creado una aplicación sencilla con **Flutter y Dart** a partir del ejemplo facilitado por el profesor. La aplicación muestra un mensaje de bienvenida centrado en la pantalla:

> Hola a todos, me llamo Jorge Calvo, y este es mi Hello World

El proyecto Flutter se llama `myhelloworld`.

## Estructura principal

- `lib/main.dart`: punto de entrada de la aplicación y definición de la interfaz.
- `test/widget_test.dart`: prueba automática que comprueba que el mensaje de bienvenida aparece exactamente una vez.
- `pubspec.yaml`: configuración y dependencias del proyecto Flutter.

La interfaz utiliza los widgets `MaterialApp`, `Scaffold`, `Center` y `Text`. Como el contenido es fijo, la clase principal hereda de `StatelessWidget`.

## Ejecución

Con Flutter instalado, abre una terminal en la carpeta del proyecto y ejecuta:

```bash
flutter pub get
flutter run
```

Selecciona uno de los dispositivos disponibles cuando Flutter lo solicite.

## Pruebas

Para ejecutar la prueba automática:

```bash
flutter test
```

El test comprueba que el texto de bienvenida está presente en la interfaz.

## Autor

Jorge Calvo

