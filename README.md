# 📘 Práctica de Estructuras de Datos - Grafos

**Universidad Técnica de Ambato**  
Ingeniería en Sistemas, Electrónica e Industrial  
Software - Tercero  

**Nombre:** Alina Ortiz  

---

##  Objetivos

### General
Desarrollar habilidades en el trabajo con estructuras de datos tipo grafo.

### Específicos

1. Implementar grafos usando listas de adyacencia en Java.
2. Aplicar algoritmos BFS y Dijkstra para búsqueda de rutas.
3. Analizar rutas dentro de un entorno universitario.

---

##  Descripción

Este proyecto implementa un grafo en Java donde los nodos representan lugares del campus universitario y las aristas representan conexiones entre ellos con un peso asociado.

Se utilizan dos algoritmos principales:

- **BFS:** encuentra la ruta con menos nodos.
- **Dijkstra:** encuentra la ruta con menor peso total.

---

## 📁 Estructura del proyecto
Guia_Ape4_Grafos
└── APE4_Grafos.java

---

## 🧠 Algoritmos

| Algoritmo | Función |
| ---------- | ------- |
| BFS        | Busca la ruta con menos pasos |
| Dijkstra   | Busca la ruta más corta según peso |

---

## 🏫 Nodos del grafo

UTA, Contabilidad, Complejo Universitario, Civil, Facultad de Alimentos, Comedor.

---

## 🛣️ Ejemplo de ruta

UTA → Contabilidad → Complejo Universitario → Civil → Facultad de Alimentos

---

## 📈 Conclusiones

- Los grafos permiten modelar rutas reales.
- BFS trabaja por niveles sin considerar pesos.
- Dijkstra calcula la ruta óptima con pesos.
- Java facilita su implementación con estructuras dinámicas.

---

## 💻 Ejecución

```bash
javac APE4_Grafos.java
java APE4_Grafos
