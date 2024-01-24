***Entrega 3***

Ejecución del DAG con Docker Compose y Apache Airflow
Este repositorio contiene un DAG (Directed Acyclic Graph) para ejecutar el ETL desarrollado en la entrega anterior, que puedes desplegar y ejecutar utilizando Docker Compose y Apache Airflow.

Pasos para ejecutar el DAG:
1. Clona el Repositorio
  git clone https://github.com/DanisaAltamirano/Entrega_3.git
  cd Entrega_3
2. Ejecuta Docker Compose
   docker-compose up -d

Este comando levantará los contenedores necesarios para ejecutar Apache Airflow y configurará el entorno.

3. Accede a la Interfaz de Airflow
   Abre tu navegador web y accede a la interfaz de Apache Airflow en http://localhost:8080. Utiliza las siguientes credenciales:
        Usuario: airflow
        Contraseña: airflow
   
4. Configura el DAG
Dentro de la interfaz de Airflow, navega a la pestaña "DAGs" y activa el DAG haciendo clic en el interruptor.

Adjunto capturas:
![image](https://github.com/DanisaAltamirano/Entrega_3/assets/149590620/92394790-eda1-4144-b602-a481bb56b3cf)
![image](https://github.com/DanisaAltamirano/Entrega_3/assets/149590620/d1070d82-af25-4fe7-913c-8867009524fc)
![image](https://github.com/DanisaAltamirano/Entrega_3/assets/149590620/f111eeeb-46e7-4793-840a-2a87e084ebc8)


