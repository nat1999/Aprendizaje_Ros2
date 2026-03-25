# 🤖 ROS 2 (Robot Operating System 2)

## 📌 ¿Qué es ROS 2?

ROS 2 (Robot Operating System 2) es un conjunto de herramientas, bibliotecas y frameworks diseñados para el desarrollo de aplicaciones robóticas.

No es un sistema operativo tradicional, sino un *middleware* que facilita la comunicación entre los diferentes componentes de un sistema robótico llamados **nodos**.

ROS 2 utiliza un middleware llamado **DDS (Data Distribution Service)**, el cual permite la transmisión eficiente de datos entre nodos, ofreciendo comunicación en tiempo real, mayor confiabilidad y escalabilidad.

---

## ⚙️ ¿Qué es un Middleware?

Un middleware es una capa de software que proporciona servicios y herramientas para facilitar el desarrollo de aplicaciones complejas.

En ROS 2, el middleware:
- Permite la comunicación entre nodos.
- Proporciona bibliotecas y herramientas.
- Facilita la integración de sistemas robóticos distribuidos.

---

## 🔄 Diferencias entre ROS 1 y ROS 2

### 🏗️ Arquitectura

- **ROS 1:**
  - Utiliza una arquitectura centralizada.
  - Depende de un nodo maestro (*ROS Master*) que gestiona la comunicación entre nodos.

- **ROS 2:**
  - Utiliza una arquitectura distribuida basada en grafos de nodos.
  - La comunicación entre nodos se realiza mediante DDS, sin necesidad de un nodo maestro.

---

### 💻 Soporte de plataformas

- **ROS 1:**
  - Principalmente compatible con sistemas Linux.

- **ROS 2:**
  - Multiplataforma: compatible con Linux, Windows y macOS.

---

### 🧑‍💻 Lenguajes de programación

- **ROS 1:**
  - Principalmente C++ y Python.

- **ROS 2:**
  - Soporta C++ y Python.
  - Amplía compatibilidad con otros lenguajes como Java y Rust.

---

## 🚀 Ventajas de ROS 2

- Comunicación en tiempo real gracias a DDS.
- Mayor escalabilidad en sistemas distribuidos.
- Mejor soporte multiplataforma.
- Mayor robustez y seguridad en comparación con ROS 1.
- No depende de un nodo maestro central.

---

## 📚 Conclusión

ROS 2 representa una evolución de ROS 1, orientada a mejorar la comunicación, escalabilidad y compatibilidad en sistemas robóticos modernos, siendo ideal para aplicaciones complejas y distribuidas.
