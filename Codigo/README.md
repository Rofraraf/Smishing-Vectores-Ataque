# Carpeta de Código

## Descripción
Esta carpeta contiene el script `zphisher.sh` modificado para la simulación del ataque de smishing.

Cambios realizados:

- Se corrigió un problema con la integración de **Ngrok**, añadiendo las siguientes líneas de código en el script:
 
  echo -e "${RED}[${WHITE}04${RED}]${ORANGE} Ngrok"
  4 | 04)
      /usr/local/bin/ngrok.exe http 8080 ;;
	  
Esto permite que Zphisher reconozca correctamente Ngrok como una opción de tunelización y lo ejecute de manera automática.
El archivo original no detectaba Ngrok correctamente, lo que impedía exponer el servidor local al público.
