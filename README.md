## Hi there 👋

Soy Achraf El k (aka Asfelk), un apasionado de la ciberseguridad y Des. Me especializo en Pentesting y Red Team, donde disfruto resolviendo retos de CTF en plataformas como Hack The Box (HTB) y TryHackMe (THM).
Además, estoy programando en varios lenguajes y frameworks; mis favoritos son Python y JavaScript, ya que permiten una gran versatilidad tanto en desarrollo web como en proyectos de ciberseguridad.

# 👀 My blog: 

### [CyberAchrafBlog](https://cyberachraf.vercel.app/)

---

```python

import requests

proxies = {"http": "http://127.0.0.1:8080"}
url=https://cyberachraf.vercel.app/


def presentar_certificaciones():
    certificaciones = {
        "SMR": 1,       # Sistemas Microinformáticos y Redes
        "eJPT": 1,      # Junior Penetration Tester
        "DAW": 1,       # Desarrollo de Aplicaciones Web
        "eCPPT": 0,     # Certified Professional Penetration Tester
        "eWPT": 0,      # Web Application Penetration Tester
        "OSCP": 0,      # Offensive Security Certified Professional
    }
    
    response = requests.post(url, data=certificaciones, proxies=proxies)
    if response.status_code == 200:
        print("Certificaciones enviadas exitosamente.")
    else:
        print(f"Error en el envío: {response.status_code}")

if __name__ == '__main__':
    presentar_certificaciones()


``` 
--- 

