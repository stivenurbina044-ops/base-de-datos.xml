# Primero
Quiero que generes un CASO DE ESTUDIO completo y realista para el dominio de un sistema de biblioteca con el objetivo de usarlo como base para diseñar una base de datos relacional.
El caso de estudio debe incluir:
1. CONTEXTO GENERAL
   - Nombre de la organización/negocio (ficticio).
   - Descripción del giro del negocio y su tamaño (pequeña, mediana o grande empresa).
   - Problemática actual que motiva la necesidad de una base de datos
     (ej. información dispersa en hojas de cálculo, duplicidad de datos, etc).
2. REGLAS DE NEGOCIO
   - Lista de al menos 10 reglas de negocio relevantes, numeradas.
   - Deben cubrir relaciones entre entidades (uno a uno, uno a muchos, muchos a muchos),
     restricciones (ej. "un cliente no puede tener más de X pedidos activos"),
     y procesos clave del negocio.
3. ENTIDADES PRINCIPALES
   - Lista de entidades identificadas (mínimo 6).
   - Para cada entidad, describe sus atributos principales y su tipo de dato sugerido.
   - Indica cuál sería la llave primaria y posibles llaves foráneas.
4. RELACIONES ENTRE ENTIDADES
   - Explica cómo se relacionan las entidades entre sí (cardinalidad y descripción).
5. REQUERIMIENTOS FUNCIONALES
   - Al menos 8 requerimientos que el sistema/base de datos debe soportar
     (ej. "el sistema debe permitir registrar pagos parciales de un pedido").
6. CONSULTAS DE EJEMPLO
   - 5 preguntas de negocio que la base de datos debería poder responder
     (ej. "¿Cuáles son los 10 clientes con mayor gasto en el último año?").
7. RESTRICCIONES Y CONSIDERACIONES ADICIONALES
   - Reglas de integridad, normalización esperada (mínimo 3FN),
     y cualquier consideración especial (auditoría, historial de cambios, etc).
# Segundo
El resultado debe ser lo suficientemente detallado como para pasar directamente a la fase de diseño
del modelo entidad-relación (MER) y luego al modelo relacional.
Usa la respuesta generada como insumo para:
   - Diseñar el Diagrama Entidad-Relación (DER).
   - Definir el esquema relacional (tablas, PK, FK, tipos de datos).
   - Escribir los scripts SQL (CREATE TABLE, restricciones, etc).
Genera también el esquema relacional en notación estándar
  (NombreTabla(campo1 PK, campo2, campo3 FK -> OtraTabla)).`
hazlo con NoSQL