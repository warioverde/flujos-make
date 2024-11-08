# Creadora de contenido V1
![creadora de contenido v1](https://github.com/user-attachments/assets/60bb930b-e055-4e86-b8a3-9765375a072c)

Este es un flujo de make (blueprint) que permite crear contenido a partir de una idea o concepto, la entrené para que se pueda usar en creación de contenido de skateboarding, 
pero puedes adaptarla para tus necesidades.


En caso que no sepas qué es make, es una herramienta que permite conectar aplicaciones en flujos, te invito a ver la página si deseas más detalles
https://www.make.com o si quieres ayudarme, puedes entrar por mi enlace de afiliados https://www.make.com/en/register?pc=sasvd
# Objetivo
El objetivo es crear un creador de contenidos para un blog en shopify

# Prerrequisitos
Los prerequisitos son:
- tener una sección de blog creada en una tienda de shopify![shopify](https://github.com/user-attachments/assets/54fc8a2e-e49e-4509-9a3c-cbf62408fb21)

- crear un archivo de google sheets con las siguientes cabeceras de columna: | Tema | Status | Fecha y hora | Link |![google sheets](https://github.com/user-attachments/assets/2ec55627-3f1b-4584-bf47-5343fe53874e)

  
- tener un assitant con gt4-0-mini en openia para developers (https://platform.openai.com/) ![assistant](https://github.com/user-attachments/assets/649ba50b-e803-4e13-a7bf-510e20502784)


# Configuración
Para configurarlo se requiere:
- insertar las instrucciones (instrucciones_assitant.txt) que dejaré en el repositorio dentro de System instructions en la configuración del assistant de openia
![assistant_SI](https://github.com/user-attachments/assets/31c97f0f-35ac-49e1-8ebf-a1f3f0fbc7cf)

- cargar el blueprint en un escenario en make
![import_blueprint](https://github.com/user-attachments/assets/de5eaceb-26bf-4cf1-a4d8-8ef3b45d01c7)

- configurar o crear las conexiones hacia google sheets, openia (assistant) y shopify

![conexiones](https://github.com/user-attachments/assets/1b06926d-4ae3-446c-bafa-c23e385f5d03)


# Uso
Una vez configurado todo, el flujo irá a buscar las nuevas filas que se agreguen a la hoja de google sheets de la primera columna (Tema) a las 9PM o haciendo una ejecución manual
![gif_uso](https://github.com/user-attachments/assets/23a52d6a-5406-470a-a7c7-c6cbc539e4db)


