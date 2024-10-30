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

## 🌐 Socials:
