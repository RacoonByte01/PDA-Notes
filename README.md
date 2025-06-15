# 📒 PDA - Notes

Aplicación móvil que permite a múltiples usuarios crear, editar y gestionar eventos y notas de forma local, con enfoque en la privacidad y seguridad de los datos.

## 📝 Descripción

Esta aplicación permite la gestión de notas y eventos personales o compartidos en un mismo dispositivo, con múltiples cuentas de usuario. Todos los datos se almacenan localmente y se cifran utilizando el algoritmo **AES**, mientras que las contraseñas se almacenan de forma segura utilizando **MD5**.

## 🚀 Características

- ✅ Creación y edición de **eventos** y **notas**
- 👥 Soporte **multiusuario**
- 📱 Funcionamiento completamente **offline**
- 🔐 **Cifrado AES** para proteger los datos locales
- 🧠 Almacenamiento de contraseñas usando **MD5**
- 📂 Sin necesidad de base de datos en la nube

## 🛠️ Tecnologías utilizadas

- **Lenguaje**: Java
- **Cifrado**: AES (Advanced Encryption Standard)
- **Hash de contraseñas**: MD5
- **Almacenamiento local**: SQLite

## 📦 Instalación

1. Clona este repositorio:

```bash
git clone https://github.com/RacoonByte01/PDA-Notes.git
```

2. Compilar la aplicación

- Para sistemas **UNIX**

```bash
./gradlew
```

- Para sistemas DOS

```CMD
gradlew.bat
```
