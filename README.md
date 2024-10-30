## Hi there 👋

Soy Achraf El k (aka Asfelk), un apasionado de la ciberseguridad y Des. Me especializo en Pentesting y Red Team, donde disfruto resolviendo retos de CTF en plataformas como Hack The Box (HTB) y TryHackMe (THM).

Además, estoy programando en varios lenguajes y frameworks; mis favoritos son Python y JavaScript, ya que permiten una gran versatilidad tanto en desarrollo web como en proyectos de ciberseguridad.

## 👀 My blog: 

### [CyberAchrafBlog](https://cyberachraf.vercel.app/)

## 🔐 Script de Certificaciones de Ciberseguridad:

```python
import os
import requests


url = os.getenv("CERTIFICACIONES_URL", "https://cyberachraf.vercel.app/")
proxies = {"http": os.getenv("HTTP_PROXY", "http://127.0.0.1:8080")}


def obtener_certificaciones():
    return {
        "SMR": 1,       # Sistemas Microinformáticos y Redes
        "eJPT": 1,      # Junior Penetration Tester
        "DAW": 1,       # Desarrollo de Aplicaciones Web
        "eCPPT": 0,     # Certified Professional Penetration Tester
        "eWPT": 0,      # Web Application Penetration Tester
        "OSCP": 0,      # Offensive Security Certified Professional
    }


def enviar_certificaciones(certificaciones):
    try:
        response = requests.post(url, data=certificaciones, proxies=proxies)
        
        
        if response.status_code == 200:
            print("Certificaciones enviadas exitosamente.")
        else:
            print(f"Error en el envío: Código de respuesta {response.status_code}")
    
    except requests.RequestException as e:
        print(f"Error al conectar con el servidor: {e}")

# Ejecución del flujo principal
if __name__ == "__main__":
    certificaciones = obtener_certificaciones()
    enviar_certificaciones(certificaciones)


``` 
---

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/achrafelkadrani) 

## 💻 Tech Stack:


# 💻 Programming Languages

[![Python](https://img.shields.io/badge/Python-yellow?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=F7DF1E&labelColor=101010)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white&labelColor=101010)](https://www.java.com/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white&labelColor=101010)]()



# 🚀 Web Technologies

[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white&labelColor=101010)](https://www.djangoproject.com/)
[![Django REST Framework](https://img.shields.io/badge/Django_REST-092E20?style=for-the-badge&logo=django&logoColor=white&labelColor=101010)](https://www.django-rest-framework.org/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=101010)](https://reactjs.org/)
[![SAPUI5](https://img.shields.io/badge/SAPUI5-005B77?style=for-the-badge&logo=sap&logoColor=white&labelColor=101010)](https://sapui5.hana.ondemand.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=563D7C&labelColor=101010)](https://getbootstrap.com/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white&labelColor=101010)](https://tailwindcss.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=E34F26&labelColor=101010)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=1572B6&labelColor=101010)](https://www.w3.org/Style/CSS/Overview.en.html)



# 🛠️ Tools

[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=2496ED&labelColor=101010)](https://www.docker.com/)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=F05032&labelColor=101010)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=181717)](https://github.com/)
[![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=009639&labelColor=101010)](https://www.nginx.com/)
[![Apache2](https://img.shields.io/badge/Apache2-D22128?style=for-the-badge&logo=apache&logoColor=D22128&labelColor=101010)](https://httpd.apache.org/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=FCC624&labelColor=101010)](https://www.linux.org/)
