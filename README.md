# Trabajo Fin de Máster - Ingenieria Informatica - Universidad de Cantabria
## Resumen

La transformación digital llevada a cabo en prácticamente todas las empresas u organismos para
conseguir sus propósitos supone un aumento de la superficie susceptible de ciberataques. La infraestructura y dispositivos tecnológicos que sostienen la tecnología de información, así como los propios
datos, se han convertido en activos esenciales cuyo fallo o robo puede implicar daños irreparables. Para
mejorar la ciberseguridad es de vital importancia disponer de conocimiento sobre un peligro existente
que afecte a los activos para poder valorarlo y tomar las medidas oportunas, lo que se conoce como
inteligencia de amenazas.

Este trabajo presenta el diseño y despliegue de una herramienta de ciberseguridad basada en tecnología Elasticsearch con la finalidad de mejorar la inteligencia de amenazas de una organización
apoyándose en plataformas abiertas de información de amenazas. Esta herramienta permite enriquecer la información de amenazas proveniente de fuentes y sensores de ciberseguridad, tales como IPS
(Intrusion Prevention System) o tráfico de red para dar una información de mayor calidad a los operadores y analistas de ciberseguridad.

Desde el punto de vista tecnológico, se ha construido una infraestructura en clúster con alta disponibilidad empleando virtualización en sistemas Linux donde se ha desplegado el motor Elasticsearch,
un componente de ELK (Elasticsearch, Logstash y Kibana) que permite almacenar y buscar entre una
gran cantidad de datos de manera muy eficiente. La herramienta permite una recolección masiva y
cercana al tiempo real de diferentes fuentes de información, el filtrado, visualización y búsqueda ágil
de información a través de un interfaz web disponiendo de medidas de autenticación.

## Abstract

Digital transformation carried out in practically all companies or organizations to achieve their
purposes involves an increase in the area susceptible to cyber attacks. The infrastructure and technological devices that support information technology, as well as the data itself, have become essential
assets whose failure or theft may involve irreparable damage. In order to improve cybersecurity, it is
vital to have knowledge about an existing danger that affects assets in order to assess it and take the
appropriate measures, known as threat intelligence.
This work presents the design and deployment of a cybersecurity tool based on Elasticsearch
technology with the aim of improving the threat intelligence of an organization by relying on open
threat information platforms. This tool enriches the threat information from cybersecurity sources
and sensors, such as IPS (Intrusion Prevention System) or network traffic, to provide higher quality
information to cybersecurity operators and analysts.
From a technological point of view, a clustered infrastructure with high availability has been built
using virtualization in Linux systems where the Elasticsearch engine has been deployed, an ELK component (Elasticsearch, Logstash and Kibana) that allows to store and search among a big data very
efficiently. The tool allows a massive and close to real-time collection of different information sources,
the filtering, visualization and agile search of information through a web interface with authentication
measures.
