# OTA_ESP32
Para el uso de OTA se debe:
- Verificar si se tiene la flash particionada para OTA
- Actualizar el código de la ESP32 en el PC (se asume la raspi esta lejos con su power bank o algo asi)
- Copiar y pegar el archivo .bin
- Cambiar siempre un archivo txt que tenga solo la versión, la ESP descarga el firmware si ve un cambio aca
- Eso, ser feliz subiendo los cambios con push. Voy a dejar un hello world de OTA aca para que lo usen si quieren
