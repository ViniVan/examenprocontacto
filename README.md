# examenprocontacto
EJERCICIO 2
1.	¿Qué es un servidor HTTP? 
Es la aplicación que procesa las peticiones web de un cliente.

2.	¿Qué son los verbos HTTP? Mencionar los más conocidos  
i.	GET – Obtener data del servidor  
ii.	POST – Mandar datos al servidor  
iii.	PUT – Actualizar data ya existente en el servidor  
iv.	DELETE – Eliminar data del servidor  

3.	¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 
Un request es una petición por un recurso hecha por el cliente al servidor HTTP. La response es una respuesta con intención de proveer al cliente con el recurso pedido. Los headers transmiten información acerca del navegador cliente, el sistema del servidor, el recurso solicitado, etc.

4.	¿Qué es un queryString? (En el contexto de una url)
El querystring es la cadena opcional seguida después del path (ruta), con la cual se puede generar consultas a través de parámetros pasados a variables.

5.	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?
El código de estado enviado en la response.
      1.	1XX: Información
      2.	2XX: Éxito
      3.	3XX: Redirigir
      4.	4XX: Error del Cliente
      5.	5XX: Error del Servidor
      6.	Algunos errores comunes
      1.	200 – OK
      2.	201 – OK created
      3.	400 – Bad request
      4.	404 – Not found
      5.	500 – Internal server error
6.	¿Cómo se envía la data en un Get y cómo en un POST? 
GET envía a data a través en la query string. POST envía la data en el body.
7.	¿Qué verbo http utiliza el navegador cuando accedemos a una página?
GET.

8.	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.
JSON Y XML son formatos agnósticos a lenguajes de programación, usados para enviar datos. JSON tiene un sintáxis similar al dict de Python:
{"ARRAY_NOTES":[{"JSON_id":64,"JSON_text":"Pendientes de hoy","JSON_date":1627014142966,"JSON_category":4}, {"JSON_id":24,"JSON_text":"Shop list","JSON_date":1625621283812, ,"JSON_category":3}]}

9.	Explicar brevemente el estándar SOAP
Es un protocolo para acceder a servicios web basado en XML.

10.	Explicar brevemente el estándar REST Full
Es un estilo de arquitectura web que se basa en expresar la información a través de verbos de HTTP.

11.	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?
Los headers transmiten meta-información sobre el cliente, servidor o el mensaje que se envía. El header key content-type especifica el tipo de recurso (text [html, json,etc], image, video, etc)

EJERCICIO 3
¿Qué diferencias se observan entre las llamadas el punto 1 y 3?
El POST hecho ha modificado el recurso contacts.json.

EJERCICIO 4
https://trailblazer.me/id/vivandre

EJERCICIO 5
1.	Lead - El lead es un potencial cliente.
      FIELD LABEL  
      Address  
      Annual Revenue  
      Clean Status  
      Company  
      Company D-U-N-S Number  
      Created By  
      Current Generator(s)  
      D&B Company  
      Data.com Key  
      Description  
      Do Not Call  
      Email  
      Email Opt Out  
      Fax  
      Fax Opt Out  
      Individual  
      Industry  
      Last Modified By  
      Last Transfer Date  
      Lead Owner  
      Lead Source  
      Lead Status  
      Mobile  
      Name  
      No. of Employees  
      Number of Locations  
      Phone  
      Primary  
      Product Interest  
      Rating  
      SIC Code  
      Title  
      Website  


2.	Account – Una cuenta individual.
      FIELD LABEL  
      Account Name  
      Account Number  
      Account Owner  
      Account Site  
      Account Source  
      Active  
      Annual Revenue  
      Billing Address  
      Clean Status  
      Created By  
      Customer Priority  
      D&B Company  
      D-U-N-S Number  
      Data.com Key  
      Description  
      Einstein Account Tier  
      Employees  
      Fax  
      Industry  
      Last Modified By  
      Match Billing Address  
      NAICS Code  
      NAICS Description  
      Number of Locations  
      Ownership  
      Parent Account  
      Phone  
      Rating  
      Shipping Address  
      SIC Code  
      SIC Description  
      SLA  
      SLA Expiration Date  
      SLA Serial Number  
      Ticker Symbol  
      Tradestyle  
      Type  
      Upsell Opportunity  
      Website  
      Year Started  



3.	Contact – Representa un contacto asociado con una cuenta.
      FIELD LABEL  
      Account Name  
      Activated By  
      Activated Date  
      Billing Address  
      Company Signed By  
      Company Signed Date  
      Contract End Date  
      Contract Name  
      Contract Number  
      Contract Owner  
      Contract Start Date  
      Contract Term (months)  
      Created By  
      Customer Signed By  
      Customer Signed Date  
      Customer Signed Title
      Description  
      Last Modified By  
      Owner Expiration Notice  
      Price Book  
      Shipping Address  
      Special Terms  
      Status  


4.	Opportunity – Una oportunidad es una venta o cuenta pendiente.
      FIELD LABEL  
      Account Name  
      Amount  
      Close Date  
      Contract  
      Created By  
      Current Generator(s)  
      Delivery/Installation Status  
      Description  
      Expected Revenue  
      Forecast Category  
      Last Modified By  
      Lead Source  
      Main Competitor(s)  
      Next Step  
      Opportunity Name  
      Opportunity Owner  
      Opportunity Score  
      Order Number  
      Price Book  
      Primary Campaign Source  
      Private  
      Probability (%)  
      Quantity  
      Stage  
      Synced Quote  
      Tracking Number  
      Type  


5.	Product – Un producto o servicio.
      FIELD LABEL  
      Active  
      Created By 
      Display URL  
      External Data Source  
      External ID  
      Last Modified By  
      Product Code  
      Product Description  
      Product Family  
      Product Name  
      Product SKU  
      Quantity Unit Of Measure  


6.	PriceBook - Una lista de productos y sus precios.
      FIELD LABEL  
      Active  
      Created By  
      Description  
      Is Standard Price Book  
      Last Modified By  
      Price Book Name  


7.	Quote -  Representa una cotización.
      FIELD LABEL  
      Account Name  
      Additional To  
      Additional To Name  
      Bill To  
      Bill To Name  
      Contact Name  
      Contract  
      Created By  
      Description  
      Discount  
      Email  
      Expiration Date  
      Fax  
      Grand Total  
      Last Modified By  
      Line Items  
      Opportunity Name  
      Owner Name  
      Phone  
      Quote Name  
      Quote Number  
      Quote To  
      Quote To Name  
      Ship To  
      Ship To Name  
      Shipping and Handling  
      Status  
      Subtotal  
      Syncing  
      Tax  
      Total Price  


8.	Asset – Representa un active de la empresa.
        FIELD LABEL 
        Account  
        Asset Level  
        Asset Name  
        Asset Owner  
        Asset Provided By  
        Asset Serviced By  
        Competitor Asset  
        Contact  
        Created By  
        Current Amount  
        Current Lifecycle End Date  
        Current Monthly Recurring Revenue  
        Current Quantity  
        Description  
        Digital Asset Status  
        External Id  
        Has Lifecycle Management  
        Install Date  
        Internal Asset  
        Last Modified By  
        Lifecycle End Date  
        Lifecycle Start Date  
        Location  
        Manufacture Date  
        Parent Asset  
        Price  
        Product  
        Product Code  
        Product Description  
        Product Family  
        Product SKU  
        Purchase Date  
        Quantity  
        Root Asset  
        Serial Number  
        Status  
        Status Reason  
        Total Lifecycle Amount  
        Unique Identifier  
        Usage End Date  


9.	Case – Un caso de retroalimentación, ayuda o pregunta que provenga de un cliente.
FIELD LABEL  
Account    
Name   
Asset  
Business Hours  
Case Number  
Case Origin  
Case Owner  
Case Reason  
Closed When Created  
Contact Email  
Contact Fax  
Contact Mobile  
Contact Name  
Contact Phone  
Created By  
Date/Time Closed  
Date/Time Opened  
Description  
Engineering Req Number  
Entitlement Name  
Entitlement Process End Time  
Entitlement Process Start Time  
Escalated  
Internal Comments  
Last Modified By  
Milestone Status  
Parent Case  
Potential Liability  
Priority  
Product  
Product  
Service Contract  
SLA Violation  
Status  
Stopped  
Stopped Since  
Subject  
Type  
Web Company  
Web Email  
Web Name  
Web Phone  


EJERCICIO 6
Realizar las siguientes actividades sobre el Playground 1 del ejercicio 4:

A.	Consultar tu ID haciendo un GET con POSTMAN.
"-MllAUlom6A0OjBLJgPZ": {
        "email": "vandre.mm@gmail.com",
        "name": "Vinicius Vandré"
    }

EJERCICIO 7

A.	¿Qué es Salesforce? 
Es la primera compañía que llevo los sistemas Customer Relationship Management a la nube.

B.	¿Qué es Sales Cloud?
Es el sistema CRM de Salesforce.

C.	¿Qué es Service Cloud?
Es la Plataforma de servicio al cliente de Salesforce.

D.	¿Qué es Health Cloud?
Es un Sistema CRM que incorpora relaciones paciente-doctor, diseñado para la gestión de records de estas relaciones.

E.	¿Qué es Marketing Cloud?
Es la Plataforma de Marketing  de Salesforce.

Funcionalidades de Salesforce
A.	¿Qué es un RecordType?
Es una herramienta para recolectar y manejar data de un objeto para presentar conjuntos distintos de ella según el usuario. Controlan Business Processes, PageLayout y Picklist.

B.	¿Qué es un ReportType?
Es una colección de objetos para las que se desea crear un reporte.

C.	¿Qué es un Page Layout?
Controla la disposición de los botones y los campos relacionados a un objeto.

D.	¿Qué es un Compact Layout?
Es una presentación de los campos claves (que se escogan) de un record.

E.	¿Qué es un Perfil?
Define qué pueden los usuarios hacer dentro de la aplicación. Todo usuario requiere de un perfil.

F.	¿Qué es un Rol?
Define qué data pueden ver los usuarios limitando o abriendo el acceso a distintos records. Asignar un rol a cada usuario no es obligatorio.

G.	¿Qué es un Validation Rule?
Es una regla para verificar que la data ingresada a un record se conforme a los estándares especificados.

H.	¿Qué diferencia hay entre una relación Master Detail y Lookup?
La primera es una relación Parent-Child en la cual. Si se elimina el padre (Parent) también se eliminará al hijo (Child).

I.	¿Qué es un Sandbox?
Es un entorno copia de la base de datos donde se pueden hacer pruebas de manera segura.

J.	¿Qué es un ChangeSet?
Es un conjunto de cambios para enviar personalizaciones de una org a otra.

K.	¿Para qué sirve el import Wizard de Salesforce?
Es una herramienta para importar data de los objetos standard de Salesforce.

L.	¿Para qué sirve la funcionalidad Web to Lead?
Para obtener información de los visitantes de una página web en una forma y de esa manera crear un nuevo lead.

M.	¿Para qué sirve la funcionalidad Web to Case?
Para obtener una consulta de los clientes y convertirla en un record case a través de la página web.

N.	¿Para qué sirve la funcionalidad Omnichannel?
Para unificar la información recibida por todos los canales a través de los cuales el cliente se comunica. 

O.	¿Para qué sirve la funcionalidad Chatter?
Para comunicar en tiempo real a los miembros de la org sin importar cual sea su rol.
Conceptos generales
A.	¿Qué significa SaaS? 
Software as a Service (Software como Servicio)

B.	¿Salesforce es Saas?
Sí, sin embargo; también es un PaaS

C.	¿Qué significa que una solución sea Cloud?
Que la solución y sus recursos están alojados de manera remota (en la nube)

D.	¿Qué significa que una solución sea On-Premise?
Que la solución está alojada de manera local en los servidores de la empresa.

E.	¿Qué es un pipeline de ventas?
Es una herramienta visual para realizar seguimiento de clientes y ventas potenciales mientras 
progresan a través de etapas determinadas.

F.	¿Qué es un funnel de ventas?
Es una estructura donde se encuentran las etapas para que un potencial cliente compre el servicio o producto.

G.	¿Qué significa Customer Experience?
Es la experiencia subjetiva que tiene el cliente de la relación con la compañía.

H.	¿Qué significa omnicanalidad?
Es la estrategia de usar una variedad de canales para estar en contacto con el cliente.

I.	¿Qué significa que un negocio sea B2B?
Que el negocio conduce sus transacciones con otros negocios. Negocio a Negocio.

J.	¿Qué significa que un negocio sea B2C?
Que el negocio conduce sus ventas directamente con los clientes. Negocio a Cliente.

K.	¿Qué es un KPI?
Es un indicador clave que muestra que tan efectivamente un negocio se acerca a alcanzar sus objetivos.

L.	¿Qué es una API y en qué se diferencia de una Rest API?
Una interfaz para que aplicaciones cliente y servidor se comuniquen. Permiten que servicios presten su funcionalidad a terceros 

M.	¿Qué es un Proceso Batch?
Un proceso en el cual los resultados se regresan en tandas y no de manera continúa.

N.	¿Qué es Kanban?
Es un método visual para llevar a cabo flujo de trabajo.

O.	¿Qué es un ERP? 
Es el tipo de software para administrar las actividades empresariales diarias, como la producción, distribución, etc. Sistema de planificación de recursos empresariales.

P.	¿Salesforce es un ERP?
No, los sistemas CRM no cuentan con componentes ERP.



