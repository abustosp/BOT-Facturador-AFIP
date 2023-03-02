Archivos base para la Facturación Masiva en el Servicio de Comprobantes en Línea de AFIP mediante un BOT de UiPath
#
## El licenciamiento es con GPL (es decir que no se puede distribuir comercialmente, solamente GRATIS). y si se utiliza este el código, su derivado también debe ser distribuido abierta y gratuitamente. 
#
##
 Breve descripción del BOT

    ֎ Crearse una cuenta en UiPath (https://www.uipath.com/)
    
    ֎ Descargar el Uipath Studio (https://www.uipath.com/studio) en la versión Community (es gratuita)
    
    ֎ Una vez instalado el Studio, se debe abrir el project.json o archivo .xaml y ejecutarlo. (se puede ejecutar desde el Studio o desde la consola de comandos)

Para ejecutar desde la consola de comandos, se debe ejecutar el siguiente comando:

    UiPath.exe run -file "Directorio completo\Archivo.xaml" -input "Directorio Completo\proyect.json"


Obviamente no me hago cargo del uso indebido del bot (ej si haces cagada y si te llegan a bloquear tu CUIT porque detecten que usas un bot (salió en una RG que prohibe el inicio automatico con bots con la consecuencia de bloquear el CUIT))

y si lo compartís (hacelo gratis, mencioname también para que mas gente se meta en el mundo de RPA o mostrale mis videos para que vean que cosas pueden hacer)

Cualquier cosa pueden contactarme en:

    https://www.linkedin.com/in/agust%C3%ADn-bustos-piasentini-468446122/

    https://www.youtube.com/user/agustinbustosp

    whatsapp al https://wa.me/+5493764224695

### Particularidades del BOT

    ֎ Para poner la fecha tiene que ser en formato texto en el Excel, por ejemplo: '01/01/2023 (Es decir debe tener ' al principio)

    ֎ El bot Corre solamente en Firefox por el momento y en Windows (a partir de windows 10 en adelante)

    ֎ A veces es necesario tener la Extensión de Firefox instalada en modo de Current User (no en modo de All Users)
