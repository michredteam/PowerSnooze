#![212750155-3ceddfbd-19d3-40a3-87af-8d329c8323c4](https://github.com/michredteam/PowerSnooze/assets/168865716/4c030ba4-414c-4071-a9e7-204aa2128ac2)
# PowerSnooze
esta aplicación surgió de un problema personal que tuve. Solía ​​pasar mucho tiempo programando hasta altas horas de la noche y había momentos en los que me quedaba dormido y dejaba mi computadora todavía encendida.

## Uso ✨
Esta es una aplicación sencilla que te permite programar acciones basadas en un temporizador. Simplemente elige una acción en un menú desplegable y establece el lapso de tiempo deseado. Cuando el contador llega a cero, la acción seleccionada se ejecutará.

Si eliges apagar, la aplicación cerrará cualquier programa en ejecución para asegurar un apagado sin interrupciones. Sin embargo, esto podría resultar en pérdida de datos si algún programa está realizando operaciones importantes en ese momento. Para evitar esto, puedes seleccionar un período de tiempo más largo o elegir acciones como suspender o hibernar, que no forzarán el cierre de aplicaciones.

La ventana del temporizador estará siempre visible por defecto, pero se puede ocultar seleccionando la opción "Ejecutar en segundo plano". Además, puedes minimizar la ventana haciendo clic derecho en ella y luego restaurarla desde la bandeja del sistema.

# Colores 🎨
![221352989-518609ab-b4d1-459e-929f-a08cd2bd9b3c](https://github.com/michredteam/PowerSnooze/assets/168865716/8359d1a0-4d44-42f4-9e55-54ed71f36b03)

cuenta regresiva tiene 4 estados de fondo diferentes para visualizar el tiempo restante y una animación para llamar tu atención cuando el tiempo está a punto de acabarse, en caso de que te olvides del temporizador de apagado.
Aquí hay una descripción general rápida:

| Time left     | Color         | Animated  |
| ------------- | ------------- | --------- |
| > 30 min.     | Verde         | No        |
| 30 - 10 min.  | Amarillo      | No        |
| 10 - 1 min.   | Naranja       | No        |
| < 1min.       | Rojo /Negro   | Yes       |

#CLI💻

También puede utilizar la línea de comando para iniciar el temporizador de apagado con argumentos y configuraciones específicos.
hasta la carpeta donde se encuentra el ejecutable.

Luego escriba `.\PowerSnooze.exe` y agregue los argumentos que desee después de esto:

```
Descripción del argumento

/SetTime <tiempo> Establece el tiempo de la cuenta regresiva. Escriba los segundos, use HH:mm:ss o HH:mm.

/SetAction <acción> Establece la acción de potencia que se ejecutará después de que la cuenta regresiva llegue a cero.
                          Escriba el nombre exacto tal como se ve en la interfaz de usuario (por ejemplo: Apagar, Reiniciar o Suspender)

/Graceful Esto significa que su computadora realizará un apagado normal e interrumpible.
                    
/AllowSleep Permite que su computadora entre en suspensión mientras la cuenta regresiva está activa.

/Background Ejecuta la cuenta regresiva en segundo plano.

```

![212898774-0a96dc1d-c908-4ce8-9dd7-a71aab6e1c2b](https://github.com/michredteam/PowerSnooze/assets/168865716/a8b3c36b-f7f2-49f8-bfeb-4465b21aa204)

# Comportamiento 📄

## Secuencia de apagado

La secuencia de apagado asegura que todas las ventanas se cierren al ejecutar un apagado, garantizando que el proceso no pueda ser detenido por otros programas. Sin embargo, esto significa que cualquier trabajo no guardado se perderá.

## Cancelando el apagado

Si decides cancelar el apagado antes de que el temporizador llegue a cero, puedes hacerlo fácilmente presionando el botón de cerrar. Aparecerá un cuadro de diálogo para confirmar tu elección. También puedes cancelar desde el área de notificación si la aplicación se está ejecutando en segundo plano.

![octocat-1715539389811](https://github.com/michredteam/PowerSnooze/assets/168865716/9a78c582-c586-4ef4-8f1b-0a2117d19807)

# Instalador
su instalacion es sencilla solo sigue los pasos que te solicita esto para tener la aplicacion como parte de una aplicacion y se pueda eliminar de forma sencilla

(https://github.com/michredteam/PowerSnooze/releases/tag/Windows)


![image](https://github.com/michredteam/PowerSnooze/assets/168865716/cf2f74aa-4a82-4564-97bb-8908ca6eb9fd)

