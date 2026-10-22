Creación de una Model-driven App en Power Platform 

FASE 1 CONFIGURACION

### **1\. Creación y activación de la cuenta de usuario**

* **Qué verificamos:** Que tu cuenta de usuario (por ejemplo, `camilo@m365x44950794.onmicrosoft.com`) estuviera creada correctamente y activa dentro del Centro de administración de Microsoft 365\.  
* **Cómo comprobarlo:** Ve al Centro de administración de Microsoft 365 \> **Usuarios activos** y busca tu nombre de usuario para confirmar que aparece habilitado.

### **2\. Asignación de la licencia de Office 365 E5**

* **Qué verificamos:** Que tu cuenta tuviera asignada la licencia adecuada (`Office 365 E5`).  
* **Por qué es importante:** Esta licencia es un requisito indispensable porque aprovisiona y habilita de forma automática el buzón de Exchange Online necesario para todas las integraciones de correo.  
* **Cómo comprobarlo:** Dentro del perfil de tu usuario en *Usuarios activos*, revisa la pestaña **Licencias y aplicaciones** y asegúrate de que la casilla de Office 365 E5 esté marcada.

### **3\. Verificación y conexión del buzón (Mailbox)**

* **Qué verificamos:** Que el buzón de Exchange Online estuviera aprobado, conectado y habilitado correctamente (lo cual se confirmó al recibir el correo interno de bienvenida de Microsoft Dynamics 365 que indicaba *"Your mailbox is now connected to Dynamics 365"*).  
* **Cómo comprobarlo:** Puedes ir al Centro de administración de Power Platform \> tu entorno (`CustomerService Trial`) \> configuración de correo / buzones para validar que el estado del buzón de tu usuario esté aprobado y probado con éxito.

### **4\. Acceso al entorno de trabajo (Customer Service Trial)**

* **Qué verificamos:** El acceso correcto a la consola de administración de Power Platform ([admin.powerplatform.microsoft.com](https://www.google.com/search?q=https://admin.powerplatform.microsoft.com)) para gestionar específicamente el entorno de pruebas donde operan las aplicaciones de Dynamics 365\.  
* **Cómo comprobarlo:** Entrar a la sección de **Entornos** y verificar que el entorno `CustomerService Trial` esté activo y disponible para tus prácticas.

### **5\. Configuración de Dynamics 365 App for Outlook**

* **Qué verificamos:** La habilitación e incorporación automática de la aplicación de Outlook en el entorno.  
* **Cómo comprobarlo:** En el Centro de administración de Power Platform \> *Recursos* \> *Aplicaciones de Dynamics 365* \> **Dynamics 365 App for Outlook**, asegurarte de que la opción de "Agregar automáticamente para todos los usuarios aptos" esté guardada para que tu buzón reciba el complemento y aparezca integrado en Outlook Web.

FASE 2

