# **Diccionario de Datos de la Base de Datos**

## **1. Información General**
- **Nombre del Proyecto**: [Nombre del proyecto]
- **Nombre de la Base de Datos**: [Nombre de la base de datos]
- **Responsable**: [Nombre del responsable]
- **Fecha de Creación**: [Fecha]
- **Versión**: [Versión]

---

## **2. Estructura de la Base de Datos**
### **2.1 Diagrama Entidad-Relación (Opcional)**
[Incluir enlace o imagen del diagrama E-R.]

---

## **3. Tablas de la Base de Datos**
### **Formato General**
Cada tabla se describe incluyendo su propósito, columnas, tipos de datos, restricciones y relaciones.

---

### **3.1 Nombre de la Tabla: [Nombre de la tabla]**
- **Descripción**: [Propósito de la tabla.]
- **Llave Primaria (PK)**: [Nombre de la columna primaria.]

#### **Columnas:**
| Nombre de la Columna  | Tipo de Datos       | Longitud | Permite Nulos | Llave (PK/FK) | Descripción                           |
|-----------------------|--------------------|----------|---------------|---------------|---------------------------------------|
| [Columna 1]           | [Tipo de datos]    | [Longitud] | [Sí/No]      | [Sí/No]       | [Descripción breve de la columna.]    |
| [Columna 2]           | [Tipo de datos]    | [Longitud] | [Sí/No]      | [Sí/No]       | [Descripción breve de la columna.]    |

#### **Relaciones:**
- [Ejemplo: La columna `user_id` es una FK que referencia la tabla `users`.]

---

### **3.2 Nombre de la Tabla: [Nombre de la tabla]**
- **Descripción**: [Propósito de la tabla.]
- **Llave Primaria (PK)**: [Nombre de la columna primaria.]

#### **Columnas:**
| Nombre de la Columna  | Tipo de Datos       | Longitud | Permite Nulos | Llave (PK/FK) | Descripción                           |
|-----------------------|--------------------|----------|---------------|---------------|---------------------------------------|
| [Columna 1]           | [Tipo de datos]    | [Longitud] | [Sí/No]      | [Sí/No]       | [Descripción breve de la columna.]    |
| [Columna 2]           | [Tipo de datos]    | [Longitud] | [Sí/No]      | [Sí/No]       | [Descripción breve de la columna.]    |

---

## **4. Índices**
### **Formato General**
| Nombre del Índice       | Tabla              | Columnas Incluidas   | Tipo de Índice  | Descripción                       |
|-------------------------|--------------------|----------------------|-----------------|-----------------------------------|
| [Nombre del índice 1]   | [Tabla 1]          | [Columna 1, Columna 2] | [Único/No Único] | [Descripción breve del índice.]   |
| [Nombre del índice 2]   | [Tabla 2]          | [Columna 1]           | [Único]         | [Descripción breve del índice.]   |

---

## **5. Vistas**
### **Formato General**
| Nombre de la Vista      | Tablas Utilizadas  | Descripción                     |
|-------------------------|--------------------|---------------------------------|
| [Nombre de la vista 1]  | [Tabla 1, Tabla 2] | [Propósito de la vista.]        |
| [Nombre de la vista 2]  | [Tabla 1]          | [Propósito de la vista.]        |

---

## **6. Procedimientos Almacenados**
| Nombre del Procedimiento | Parámetros         | Descripción                     |
|--------------------------|--------------------|---------------------------------|
| [Nombre del procedimiento 1] | [Parámetros]       | [Propósito del procedimiento.]  |
| [Nombre del procedimiento 2] | [Parámetros]       | [Propósito del procedimiento.]  |

---

## **7. Restricciones**
| Nombre de la Restricción | Tipo de Restricción | Tabla Relacionada  | Descripción                     |
|--------------------------|---------------------|--------------------|---------------------------------|
| [Nombre de la restricción 1] | [Única, FK, Check] | [Tabla 1]          | [Propósito de la restricción.]  |
| [Nombre de la restricción 2] | [FK]              | [Tabla 2]          | [Propósito de la restricción.]  |

---

## **8. Seguridad**
### **Usuarios y Roles**
| Usuario/Rol             | Permisos           | Descripción                     |
|-------------------------|--------------------|---------------------------------|
| [Usuario/Rol 1]         | [SELECT, INSERT]   | [Acceso limitado a la tabla X.] |
| [Usuario/Rol 2]         | [ADMIN]            | [Acceso completo a la base de datos.] |

---

## **9. Referencias**
[Listar cualquier documento o enlace relacionado con el diseño de la base de datos.]
