![BrightCoders Logo](assets/images/logo-bc.png)

# Scorecard

El propósito de esta actividad es tener un perfil completo de nuestros BrightCoders.

## Pre-requisitos
Antes de iniciar debes contar con una evaluación oficial de tu nivel de inglés. Si ya la tienes sube el resultado de tu evaluación en la carpeta [certificate](/certificate)

Si no lo tienes [realiza está evaluación de manera gratuita](https://www.efset.org/ef-set-50/) y una vez que termines sube tu certificado. Requeriras de 50 minutos para realizarla.

## Instrrucciones

Actualiza el archivo [_data/data.yml](_data/data.yml) con tu información, siguiendo las indicaciones que a continuación se presentan.

Puedes modificar el archivo directamente desde aquí en GitHub o descargarlo en tu computadora local y subir la actualización (utilizando git).

**NOTA** los archivos [yaml (.yml)](https://circleci.com/blog/what-is-yaml-a-beginner-s-guide/) son muy especiales en cuanto a su indentado así que al editarlo ten cuidado de respetar y conservar el indentado que tiene definido.

## Habilitar GitHub Pages

Este oasi es necesario para publicar tu scorecard

1. Ve al apartado de `settings` de este repositorio.
2. Ubica el apartado  `Github Pages`
3. En `source` selecciona la rama `master`
4. En el archivo `_config.yml` modifica el campo `baseurl:` con la dirección que tu GitHub Pages generó.

Con esto se publicará tu repositorio y en esa dirección podrás revisar las actualizaciones que hagas. Es importante que cada que hagas una modificación revises como se actualiza tu página ya que podrías generar algunos errores.

# Edición de data.yml

## Nombre

1. Ubica el apartado `name` y escribe tu primer nombre y apellido, por ejemplo: Juan Pérez

## Programa

1. Ubica el apartado `tagline` y escribe según corresponda:
   - Ruby on Rails Web Developer
   - React Native Mobile Developer

## Datos de contacto

1. Ubica el apartado `email` y completa todos los datos de contacto que quieras registrar.
  
## Idiomas

1. Ubica el apartado `languages`.
2. Incluye todos lo idiomas que sabes así como el nivel de dominio. Para el nivel utiliza:
   - Si es tu lengua nativa puedes indicarlo como Native.
   - Indica el resultado de una evaluación oficial como IELTS, TOEFL, [EF-SET](https://www.efset.org/ef-set-50/) e indica el nivel o puntos obtenidos.
   - Para otros idiomas (diferente al inglés), si **no** tienes alguna evaluación oficial utiliza el modelo **Dreyfus** (este modelo se explica al final de este documento).

## Soft skills

1. Ubica el apartado `interests`.
2. Agrega un soft skill en cada `item`.
  
Los Soft Skills son competencias o habilidades sociales que son fundamentales para relacionarse con otras personas ya sea en la vida diaria o en el trabajo, como por ejemplo la comunicación, el trabajo en equipo, adaptabilidad, creatividad, pensamiento creativo, solución de problemas, confianza, administración del tiempo, personas o tareas, colaboración, etc.

Estas son algunas de las soft skills que más valoran los empleadores:

- [Soft Skills for Developers – The Ultimate Guide](https://pointjupiter.com/soft-skills-software-developer-need-ultimate-guide/)
- [10 Soft Skills Every Developer Needs](https://hackernoon.com/10-soft-skills-every-developer-needs-66f0cdcfd3f7)
- [Top Soft Skills for Developers and Programmers in 2021](https://medium.com/aslisachin/top-soft-skills-for-developers-and-programmers-in-2020-62b8d663df01)
- [Important Soft Skills for Information Technology (IT) Jobs](https://www.thebalancecareers.com/top-information-technology-it-soft-skills-2063781)
- [Critical soft skills for software developers](https://medium.com/swlh/critical-soft-skills-for-software-developers-6845545f6dbd)

## Acerca de Mí (About Me)

1. Ubica el apartado `career-profile`.
2. En el campo `summary` escribe un resumen de tu perfil, por ejemplo:

>I am a person passionate about technology and I love programming, I am fascinated by areas such as robotics, IoT, artificial intelligence, and its application in agriculture. I am an autodidact programmer, I like to learn new things. I love nature and coffee.

>I am a Computer Systems Engineering student. I love learning about programming and improving my work through the use of best practices and logical thinking. I am a proactive, diligent person with a great disposition for teamwork. Sharing knowledge and self-learning are things that I enjoy. My biggest passion is technology, which I think can help us all to become a better person, friend, worker, and a productive member of society. Currently, I want to become a Senior Developer at an innovative company here, in Mexico, where I can get the opportunity to be creative and solve problems people struggle with every day.

## Educación

1. Ubica el apartado `educationcomplete`.
2. Registra los estudios realizados más relevantes, pueden ser formales o informales.

## Experiencia

1. Ubica el apartado `experiences`.
2. Registra los puestos o trabajos en los que has tenido

Para un perfil Jr. es completamente normal que no tengas mucha experiencia.

## Proyectos

1. Ubica el apartado `projects`
2. Registra los nombres de los proyectos (`title`), un enlace al proyecto si es que existe (`link`) y una breve descripción (`tagline`)

No es necesario que sean proyectos profesionales o pagados. Pueden ser proyectos personales, escolares, de retos, hackatones, etc. El propósito es mostrar el uso de tus habilidades técnicas.

## Technical Skills

1. Ubica el apartado `skills`.
2. Registra las tecnologías que conoces así como el nivel de experiencia queue tienes. Por ejemplo, HTML, CSS, Javascript, Heroku, Linux, etc.
3. Para indicar el nivel de experiencia utilizaremos el **modelo Dreyfus** el cual define los siguientes niveles:

- 20% Novice
- 40% Advanced beginner
- 60% Competent
- 80% Proficient
- 100% Expert

## El modelo Dreyfus

Para entender el modelo Dreyfus e identificar en que nivel te encuentras utiliza los siguientes recursos:

- [How To Evaluate Expertise: the Dreyfus Model](https://www.solcept.ch/en/blog/dreyfus-model/)
- [Building Software Development Expertise – Using The Dreyfus Model](https://skorks.com/2009/08/building-software-development-expertise-using-the-dreyfus-model/)
- [Software Engineer Qualification Levels: Junior, Middle, and Senior](https://hackernoon.com/software-engineer-qualification-levels-junior-middle-and-senior-f2229591df1c)

**NOTA** Este template fué tomado de [https://github.com/sharu725/online-cv](https://github.com/sharu725/online-cv)  y adaptado para BrightCoders.
