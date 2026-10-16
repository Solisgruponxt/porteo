# Porteo NXT

Dashboard del histórico de porteo por permisionario. Lee los archivos de la carpeta de Drive "Porteo Dashboard" mediante un Apps Script y cruza cada servicio (RPU) con el Registro de Permisionarios y Clientes para saber si lo portea NXT.

- `index.html`: dashboard (la constante `API_URL` apunta al Apps Script).
- `registro_nxt.json`: índice del Registro (ID, RPU, permisionario, cliente, portea NXT), generado desde el CSV del Registro.
