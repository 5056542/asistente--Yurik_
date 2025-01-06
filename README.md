#el asistente virtual Yurik Asistant
Yurik ASistant es un proyecto de código abierto y gratuito, de un pequeño sistente virtual, programado en el lenguaje de programación Python.
##¿cuales su objetivo?
el objetivo de este asistente es un poco avanzado. en simples explicaciones, poder controlar casi todo el dispositivo, hasta donde se permita. sin emvargo, avanzar despacio, enfocando en hacer el asistente conocido, y después implementar. apolla esta idea, que el creador del proyecto es menor de edad.
##errores en el código.
puede aver barios errores, devido a que este código está vasado en algunas explicaciones de IA, y es casi completa copia de un proyecto, el cual su repositorio en esta misma plataforma sigue disponible. si quieres corregir estos errores, puedes hacer una pull request al repositorio, con tus observaciones o colaboraciones.
##¿cuales el proyecto original?
el proyecto original, es de un canal en YouTube. este es el enlace al video de ese proyecto: (https://youtu.be/-0tIy8wWtzE)
##¿qué posibles errores puede aver?
el proyecto original usa Eleven Labs para la voz. sin emvargo, esta api es de costo, y como no hay con que financiar estos gastos, bamos a usar GTTS. y otra cosa. la api de la IA, en el proyecto original, usava chat GPT, que también es de costo. y como casi no hay apis de IAS gratuitas, no toca más que entrenar al asistente desde 0. si alguno de ustedes desarrolla una IA, gratuita eso si, por favor colaborar a este proyecto. igualmente, en el proyecto original, se usa un archivo .HTML, para la interfáz gráfica. pero aquí no bamos a combinar mucho los lenguajes de programación, así que bamos a hacer la interfáz en Python, con la biblioteca WX (WX Python) ya que es la más acesible de programar para las presonas ciegas o con discapacidad visual, como lo es el creador de este proyecto.
##¿cómo el asistente transcribe el pedido del usuario?
el pedido del usuario, se graba en un audio .wav, que se guarda temporalmente en la carpeta del asistente. ahora, en la lógica del proyecto original, se transcribía con la biblioteca Open AI, la cual ya no se usa, por que no hay api de chat GpT, así que se tiene que inventar otra manera.
##¿cómo responde el asistente al usuario?
el programa usa la respuesta dada por la api de chat GPT, y la envía a la api de Eleven labs. ahora, el programa crea un archivo .mp3, con lo que envíe la api de Eleven labs, en la carpeta static, que es de donde la interfáz de HTML, obtiene sus recursos. todo este proseso ya no es funcional, por que ya no tendremos interfáz en HTML, ni api de Eleven labs, ni api de chat GPT, ni nada de eso. a parte, los archivos .mp3 son los peores en calidad, así que necesitamos .wav. todo esto cambiará, así que colaboranos en esto por favor.
##¿por qué hay una carpeta llamada Games?
la carpeta Games (juegos) es una carpeta con juegos básicos en Python. el archivo Games Funtionality.py que está basío, es donde se puede colaborar, a la lógica de llamada a los juegos, para que el asistente juegue con el usuario.
