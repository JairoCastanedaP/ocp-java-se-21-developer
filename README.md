<div align="center">

# ☕ Preparación OCP: Java SE 21 Developer (1Z0-830)

**Mi ruta de estudio hacia la certificación *Oracle Certified Professional: Java SE 21 Developer*: ejercicios, apuntes y ejemplos de cada tema del examen.**

![Estado](https://img.shields.io/badge/Estado-En%20progreso-F2A900?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Oracle](https://img.shields.io/badge/Examen-1Z0--830-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)

</div>

---

## 📖 Sobre este repositorio

Este repositorio documenta mi preparación para el examen **1Z0-830**, que otorga la certificación
**Oracle Certified Professional: Java SE 21 Developer**.

Cada carpeta es un proyecto de IntelliJ IDEA con ejemplos pequeños y enfocados en un tema. Los ejemplos incluyen
**comentarios en español** que explican el concepto y los detalles que suelen aparecer en el examen.

> [!NOTE]
> **🚧 Certificación en progreso.** El repositorio avanza por etapas. Mientras tanto, refuerzo los temas
> con otros programas de Java que complementan esta preparación (ver
> [Formación complementaria](#-formación-complementaria)).

## 📊 Avance frente a los temas del examen

| Tema del examen 1Z0-830 | Estado |
|---|:---:|
| Fundamentos: estructura de un programa, entrada y salida, comentarios | ✅ |
| Tipos primitivos, números, variables y *casting* | ✅ |
| Operadores y precedencia | ✅ |
| Control de flujo: condicionales, ciclos, `break` / `continue` / etiquetas | ✅ |
| Arreglos: multidimensionales, búsqueda y ordenamiento | ✅ |
| Métodos, sobrecarga y *varargs* | ✅ |
| Programación orientada a objetos: clases, herencia, polimorfismo, `static`, `final`, clases anidadas | ✅ |
| Clases selladas (`sealed`, `permits`) y *records* | ✅ |
| Inferencia de tipos con `var` y *autoboxing* | ✅ |
| `String`: igualdad, inmutabilidad y métodos útiles | ✅ |
| `StringBuilder`, *text blocks* y `switch` con *pattern matching* | ⏳ |
| Interfaces, clases abstractas y enumeraciones | ⏳ |
| Manejo de excepciones | ⏳ |
| Genéricos y colecciones | ⏳ |
| Expresiones lambda, interfaces funcionales y *Streams* | ⏳ |
| API de fecha y hora (`java.time`) | ⏳ |
| E/S de Java (`java.io` y NIO.2) | ⏳ |
| Concurrencia e **hilos virtuales** | ⏳ |
| Módulos (*JPMS*), empaquetado y despliegue | ⏳ |
| Localización e internacionalización | ⏳ |

✅ Visto y practicado · ⏳ Pendiente

## 📘 Formación complementaria

Además de esta preparación, estoy cursando programas de Java que refuerzan los temas del examen y los llevan a
la arquitectura de software y al desarrollo web empresarial.

### Galaxy Training

*Centro de entrenamiento y certificación de alto rendimiento en Tecnologías de Información.*

<table>
  <thead>
    <tr><th align="left">Programa</th><th align="left">Módulo</th><th align="left">Avance</th></tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="3"><b>Especialización: Java Software Architecture</b><br/><sub>Java 26</sub></td>
      <td>Layered Architecture with Java &amp; Spring</td>
      <td><img src="https://img.shields.io/badge/100%25-Completado-2EA44F?style=flat-square" alt="100 %"></td>
    </tr>
    <tr>
      <td>Hexagonal Architecture with Java &amp; Spring</td>
      <td><img src="https://img.shields.io/badge/5%25-En%20curso-F2A900?style=flat-square" alt="5 %"></td>
    </tr>
    <tr>
      <td>Clean Architecture with Java &amp; Spring</td>
      <td><img src="https://img.shields.io/badge/0%25-Pendiente-8B949E?style=flat-square" alt="0 %"></td>
    </tr>
    <tr>
      <td><b>AI-Assisted Software Development with Java</b><br/><sub>Build modern applications using AI-assisted development</sub></td>
      <td>Programa completo</td>
      <td><img src="https://img.shields.io/badge/100%25-Completado-2EA44F?style=flat-square" alt="100 %"><br/>🏅 <b>Distinción por mérito a la excelencia</b></td>
    </tr>
    <tr>
      <td rowspan="2"><b>Java Web Developer</b><br/><sub>JDK 26</sub></td>
      <td>Java Core</td>
      <td><img src="https://img.shields.io/badge/100%25-Completado-2EA44F?style=flat-square" alt="100 %"></td>
    </tr>
    <tr>
      <td>Servicios Web RESTful</td>
      <td><img src="https://img.shields.io/badge/5%25-En%20curso-F2A900?style=flat-square" alt="5 %"></td>
    </tr>
  </tbody>
</table>

### Zuncode Solutions

| Programa | Avance |
|---|---|
| **Arquitectura de Microservicios con Spring Boot** | ![84 %](https://img.shields.io/badge/84%25-En%20curso-F2A900?style=flat-square) |

### Cómo se relacionan con el examen

- **Java Core** refuerza directamente el núcleo del lenguaje, que es la base del examen.
- **Las arquitecturas por capas, hexagonal y limpia** y los **microservicios con Spring Boot** ponen en práctica
  los conceptos de POO del examen (interfaces, polimorfismo, encapsulamiento) en diseños de aplicaciones reales.
- **AI-Assisted Software Development with Java** aporta un flujo de trabajo moderno para escribir, revisar y probar código Java.

## 📚 Contenido actual

<details open>
<summary><b>1. Primeros pasos</b> · <code>MyFirstProject/</code> · <code>MyFirstJavaProject/</code></summary>

- Instalación del JDK 21 y configuración del entorno en IntelliJ IDEA.
- Estructura de una clase, el método `main` y el primer *Hola Mundo*.

</details>

<details>
<summary><b>2. Fundamentos del lenguaje</b> · <code>Exercise/</code></summary>

| Paquete | Temas |
|---|---|
| `inputoutput` | Entrada con `Scanner` y salida con `print`, `println` y `printf` |
| `comments` | Comentarios de línea, de bloque y de documentación |
| `datatype` | Los 8 tipos primitivos y conversión de tipos (*casting* implícito y explícito) |
| `numbers` · `variable` | Literales numéricos, declaración, instanciación e inicialización de variables |
| `operator` | Operadores de asignación, unarios, a nivel de bits y desplazamiento, y precedencia |
| `branching` · `LabeledLoops.java` | `continue`, `return` y ciclos con etiquetas |
| `array` | Arreglos uni y multidimensionales, `Arrays.sort()` y `Arrays.binarySearch()` |
| `method` | Métodos, sobrecarga y *varargs* |
| `Fibonacci` | Ejercicio de práctica con la serie de Fibonacci |

</details>

<details>
<summary><b>3. Modificadores de acceso y convenciones</b> · <code>AccesModifier/</code> · <code>NamingConventions/</code></summary>

- `public`, `protected`, *default* y `private` entre clases del mismo paquete y de paquetes distintos.
- Convenciones de nombres de Java para clases, métodos, variables, constantes y paquetes.

</details>

<details>
<summary><b>4. Programación orientada a objetos</b> · <code>ObjectOrientedProgramming/</code></summary>

| Paquete | Temas |
|---|---|
| `oopconcept` | Clases, objetos y constructores |
| `examplethis` · `examplesuper` · `superthis` | Uso de `this`, `super` y encadenamiento de constructores |
| `statickeyword` | Miembros `static` |
| `finalkeyword` | Variables, métodos y clases `final` |
| `polymorphism` | Herencia, sobrescritura y polimorfismo |
| `nestedclasses` | Clases internas y clases anidadas estáticas |
| `sealedclasses` | Jerarquías cerradas con `sealed` y `permits` |
| `recordclasses` | *Records*: constructor compacto, *records* que implementan interfaces y *records* anidados |
| `varexamples` | Inferencia de tipos con `var` y sus restricciones |
| `boxing` | *Autoboxing* y *unboxing* con las clases envoltorio |
| `testsUnit9` | Ejercicios de repaso tipo examen |

</details>

<details>
<summary><b>5. La clase String</b> · <code>String/</code></summary>

- Igualdad de cadenas: `==` frente a `equals()` y el *String pool*.
- Inmutabilidad de `String`.
- Métodos más usados en el examen.

</details>

## 🚀 Cómo usar este repositorio

### Requisitos

- **JDK 21**.
- **IntelliJ IDEA**: cada carpeta es un proyecto independiente con su archivo `.iml`.

### Pasos

```bash
git clone https://github.com/JairoCastanedaP/oracle-certified-proffesional-java-se-21-developer-certification.git
```

1. Abre en IntelliJ IDEA la carpeta del tema que quieras repasar (por ejemplo `ObjectOrientedProgramming/`).
2. Configura el **JDK 21** como SDK del proyecto.
3. Ejecuta la clase que contiene el método `main`.

También puedes compilar un ejemplo suelto desde la terminal:

```bash
cd Exercise/src
javac datatype/TypeCasting.java && java datatype.TypeCasting
```

## 📂 Estructura del repositorio

```text
.
├── MyFirstProject/              # Primer proyecto y configuración
├── MyFirstJavaProject/          # Hola Mundo
├── Exercise/                    # Fundamentos: tipos, operadores, control de flujo, arreglos, métodos
├── AccesModifier/               # Modificadores de acceso entre paquetes
├── NamingConventions/           # Convenciones de nombres
├── ObjectOrientedProgramming/   # POO, sealed, records, var, boxing
└── String/                      # Clase String
```

## 👤 Autor

**Jairo Alejandro Castañeda Pedraza**

[![GitHub](https://img.shields.io/badge/GitHub-JairoCastanedaP-181717?style=flat&logo=github)](https://github.com/JairoCastanedaP)

---

<div align="center">

⭐ Si también te estás preparando para el OCP de Java 21, este repositorio puede servirte como guía.

</div>
