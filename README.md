<<<<<<< HEAD
# ARYControlAccess
=======
# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo
- npm install @react-navigation/native @react-navigation/stack react-native-gesture-handler react-native-reanimated react-native-screens

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
>>>>>>> 32bc8e6 (Creacion)


## Estructura del proyecto
/aryaccesscontrol
│── /app                  # Configuración y punto de entrada de la app
│── /assets               # Recursos estáticos (imágenes, íconos, etc.)
│── /components           # Componentes reutilizables (botones, inputs, etc.)
│── /constants            # Variables y configuraciones globales
│── /hooks                # Hooks personalizados
│── /node_modules         # Dependencias de npm
│── /scripts              # Scripts auxiliares
│── /src                  # Código principal de la app
│   │── /components       # Componentes específicos de las páginas
│   │── /contexts         # Contextos de la aplicación (autenticación, temas, etc.)
│   │── /hooks            # Hooks específicos para lógica de negocio
│   │── /pages            # Páginas principales de la app
│   │   │── Home.tsx                # Página de inicio
│   │   │── Profile.tsx             # Página de perfil de usuario
│   │   │── EmployeeCRUD.tsx        # CRUD de empleados
│   │   │── SearchExpedient.tsx     # Consulta de expedientes
│   │   │── NotFound.tsx            # Página 404
│   │── /routes          # Configuración de navegación
│   │   │── AppNavigator.tsx  # Definición de StackNavigator o TabNavigator
│   │── /services        # Comunicación con la API (fetch, axios, etc.)
│   │   │── authService.ts  # Autenticación
│   │   │── employeeService.ts # CRUD de empleados
│   │   │── expedientService.ts # Consultas de expedientes
│   │── /utils           # Funciones utilitarias (formatos de fecha, validaciones, etc.)
│── .gitignore
│── app.json
│── bd_ary.sql          # Base de datos
│── expo-env.d.ts
│── package-lock.json
│── package.json
│── README.md
│── tsconfig.json

## Dependencias necesarias para el correcto desarrollo

```bash
npm install @react-navigation/native @react-navigation/stack react-native-gesture-handler react-native-reanimated react-native-screens
```

