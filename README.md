# Sistema de seguridad para el control de acceso a una vivienda mediante el reconocimiento de voz utilizando coeficientes cepstrum MFCC Y DTW

## Resumen

El presente trabajo busca desarrollar un sistema de seguridad para el control de acceso a una vivienda mediante el reconocimiento de voz del locutor dependiente del texto, donde el principal objetivo es identificar a cada miembro del hogar, quienes tendrán el acceso. El sistema permitirá que un usuario grabe una palabra clave a través del micrófono de un dispositivo móvil y este sea reconocido o no de la base de datos, permitiéndole o denegándole el acceso a la vivienda. El sistema estará conformado por 2 fases, la primera es la fase de extracción de características de la señal, para esto se usará una adaptación de los MFCC (Coeficientes Cepstrales en la Frecuencia de Mel) y la segunda fase es la del reconocimiento automático del locutor que estará basada en la técnica DTW (Alineamiento Temporal Dinámico), además de una lógica para la toma de decisióne para la identificación o no, o falsa identificación de un usuario. En relación a la configuración de los experimentos, los patrones de voz serán evaluados en 2 diferentes escenarios, uno con ruido y otro sin ruido. Para poder comprobar que el sistema sea confiable se harán 2 tipos de pruebas, una entre los usuarios del sistema tratando de acceder uno con el usuario del otro y otra donde personas ajenas a las almacenadas en la base de datos (usuarios no registrados) trataran de acceder.

## Abstract

The present work seeks to develop a security system for the control of access to a home by means voice recognition of the speaker dependent on the text, where the main objective is to identify each member of the household, who will have access. The system will allow a user to record a keyword through the microphone of a mobile device and this is recognized or not from the database, allowing or denying access to the home. The system will consist of 2 phases, the first is the phase of extraction of characteristics of the signal, for this an adaptation of MFCC (Mel Frequency Cepstral Coefficients) will be used and the second phase is the automatic recognition of the speaker which will be based on the technique of DTW (Dynamic Time Warping), in addition to a logic for the decision making of the identification or not, or a false identification of a user. In relation to the configuration of the experiments, the speech patterns will be evaluated in 2 different scenarios, one with noise and the other without noise. In order to verify that the system is reliable, 2 types of tests will be done, one between the users of the home trying to access one with the user of the other and another where people other than those stored in the database (unregistered user) will try to access it.

## General Scheme of the Project
<p align="center">
  <img src=Imagenes/Cap2/image059.png></img>
</p>

## Architecture Design
<p align="center">
  <img src=Imagenes/Cap3/image069.jpg></img>
</p>

## Architecture Implementation
<p align="center">
  <img src=Imagenes/Cap3/image070.jpg></img>
</p>
