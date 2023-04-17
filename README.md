#Laboratorio 2

##Letra:

Con el objetivo de mejorar la comunicación entre estudiantes, docentes y otros usuarios de una 
determinada institución educativa, se le ha encomendado la importante tarea de desarrollar una 
aplicación de mensajería instantánea. Esta aplicación debe manejar la información de usuarios y 
las conversaciones que estos mantienen entre sí, incluyendo mensajes y otros contenidos.
En primer lugar, interesa recabar información sobre los usuarios de la aplicación. De los usuarios 
se conoce su número de teléfono celular el cual lo identifica, el nombre, la fecha de registro en la 
aplicación, una imagen de perfil, una descripción y cuando se conectó por última vez. Además, 
cada usuario tiene una lista personal de contactos, compuesta por los contactos de su dispositivo 
inteligente que también utilizan la aplicación.
Los usuarios de la aplicación se envían mensajes, estableciendo de esta forma conversaciones. 
Interesa conocer para un usuario su lista de conversaciones y para cada conversación el contacto 
con el cual se estableció la misma y la lista de mensajes intercambiados en la conversación. A su 
vez, una conversación puede ser activa o estar archivada.
Un mensaje puede ser simple cuando se trata de un texto, multimedia si contiene una foto o video, 
y contacto cuando contiene los datos de un contacto que se quiere compartir. De los mensajes se
conoce un código que lo identifica y la fecha y hora en que fue enviado. Adicionalmente, se conoce 
si un mensaje fue visto o no por su receptor. Para el caso de los mensajes simples, interesa saber 
el texto que fue enviado en el mensaje. Para el caso de los mensajes multimedia, si contiene una 
imagen se conoce su formato, tamaño y un texto que puede ser opcional. Si contiene un video se 
conoce la duración de este. Por último, de los mensajes que contienen un contacto se conoce el 
nombre y teléfono de contacto.
Cuando dos o más usuarios quieren mantener una conversación entre ellos, pueden crear un 
grupo. De cada grupo se conoce un nombre que lo identifica, una imagen y la fecha y hora de 
creación. Adicionalmente se conoce la lista de usuarios que integra el grupo. Por último, en un 
grupo los usuarios pueden ser miembros o administradores. Los usuarios miembro pueden 
enviar/recibir mensajes en el grupo y a la vez pueden editar las propiedades básicas del grupo 
como el nombre y la imagen. Por otro lado, los usuarios administradores adicionalmente pueden 
agregar/sacar usuarios del grupo. Todo grupo tiene al menos un usuario administrador, el cual 
es por defecto el usuario que crea el grupo.
Por último, cuando un usuario quiere compartir un pensamiento con todos sus contactos utiliza 
lo que se llama estado. Un estado es una publicación del usuario que se comparte con todos sus 
contactos, por un tiempo limitado. Al pasar 24 horas desde la publicación de un nuevo estado, 
este desaparece de la plataforma. De un estado se conoce un texto y la fecha y hora en que fue 
publicado. A su vez un usuario puede tener varios estados activos al mismo tiempo.
