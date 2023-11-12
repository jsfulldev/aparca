# APARCA - Tu Solución de Gestión de Parqueaderos

## Descripción
APARCA es una aplicación de gestión de parqueaderos que ofrece una solución integral para administradores, empleados y usuarios finales. Permite el registro de vehículos, seguimiento de ingresos y salidas, así como estadísticas detalladas para una gestión eficiente.

## Tecnologías Utilizadas
- **Lenguaje de Programación:** Dart
- **Framework:** Flutter
- **Base de Datos:** Firebase

### Paquetes Flutter
- [cupertino_icons](https://pub.dev/packages/cupertino_icons): ^1.0.2
- [flutter_svg](https://pub.dev/packages/flutter_svg): ^2.0.7
- [get](https://pub.dev/packages/get): ^4.6.5
- [qr_code_scanner](https://pub.dev/packages/qr_code_scanner): ^1.0.1
- [ionicons](https://pub.dev/packages/ionicons): ^0.2.2
- [image_picker](https://pub.dev/packages/image_picker): ^1.0.4
- [provider](https://pub.dev/packages/provider): ^6.0.5
- [firebase_core](https://pub.dev/packages/firebase_core): ^2.19.0
- [firebase_auth](https://pub.dev/packages/firebase_auth): ^4.11.1
- [cloud_firestore](https://pub.dev/packages/cloud_firestore): ^4.11.0
- [animated_notch_bottom_bar](https://pub.dev/packages/animated_notch_bottom_bar): ^1.0.0
- [google_sign_in](https://pub.dev/packages/google_sign_in): ^6.1.5
- [flutter_spinkit](https://pub.dev/packages/flutter_spinkit): ^5.2.0
- [firebase_storage](https://pub.dev/packages/firebase_storage): ^11.4.1
- [syncfusion_flutter_charts](https://pub.dev/packages/syncfusion_flutter_charts): ^23.1.44
- [google_mlkit_text_recognition](https://pub.dev/packages/google_mlkit_text_recognition): ^0.11.0
- [image_cropper](https://pub.dev/packages/image_cropper): ^5.0.0

## Perfiles de Usuario

### Administrador
El perfil de administrador tiene las siguientes funciones:
- Cambio de Rol.
- Visualización de todos los vehículos y usuarios registrados.
- Estadísticas a través de gráficas circulares y de barras.

### Empleado
El perfil de empleado cuenta con las siguientes funciones:
- Registro de ingreso de vehículos por medio de la placa.
- Marcado de salida por lectura del código QR.
- Modificación del campo de la placa en caso de error de lectura.

### Usuario
El usuario final puede:
- Registrar y eliminar vehículos, evitando duplicados de placas.
- Consultar un historial de ingresos y salidas.
- Personalizar su perfil modificando datos personales.

## Soporte
Para cualquier pregunta o asistencia, por favor contacta con nosotros en [aparcaaplication@gmail.com](mailto:aparcaaplication@gmail.com).

## Instalación
1. Clona este repositorio.
2. Ejecuta `flutter pub get` para instalar las dependencias.
3. Ejecuta `flutter run` para iniciar la aplicación.

## Contribución
¡Contribuciones son bienvenidas! Si deseas contribuir a APARCA, sigue los pasos de [contribución](CONTRIBUTING.md).

## Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

¡Gracias por utilizar APARCA! Si tienes alguna pregunta o problema, no dudes en contactarnos.
