# Analisis-y-diseño-repo

# Planteamiento del problema

Actualmente, el aliado y distribuidor de **Alquería** se encuentra con serios problemas en su método de ventas y atención al cliente. El enfoque actual se basa en gran medida en la interacción cara a cara para manejar pedidos, lo cual resulta en elevados gastos operativos, demoras en las respuestas y poca independencia para los clientes al hacer sus decisiones de compra.

La ausencia de una plataforma digital restringe la capacidad del distribuidor para ofrecer un servicio eficiente y fácil de acceder. Los clientes que desean productos deben esperar a que el distribuidor procese las cotizaciones o los pedidos manualmente, lo que causa retrasos, ineficiencias y la posibilidad de perder oportunidades de venta. Además, la gestión de facturas y el control de usuarios se llevan a cabo de manera dispersa, complicando el seguimiento y la supervisión del negocio.

Este escenario no solo impacta en la eficacia operativa del distribuidor, sino que también perjudica la experiencia de los clientes finales, quienes requieren soluciones digitales que sean rápidas y accesibles, que les permitan explorar catálogos, solicitar cotizaciones, emitir facturas y realizar compras en línea usando cualquier dispositivo.

En consecuencia, la ausencia de una herramienta tecnológica integral genera:

- **Dependencia excesiva** de gestiones presenciales.  
- **Procesos de ventas** poco automatizados y lentos.  
- **Limitaciones** para escalar el negocio y atender una mayor cantidad de clientes.  
- **Menor satisfacción** de los clientes, al no contar con una experiencia digital moderna y eficiente.  

Por lo tanto, se requiere una solución tecnológica que modernice y digitalice el proceso de ventas, mejorando la autonomía de los clientes y optimizando la gestión del distribuidor. La implementación de una aplicación web permitirá superar las limitaciones actuales, aportando **eficiencia, trazabilidad y accesibilidad** a los procesos de compra y facturación.

# Contextualización de la necesidad

El distribuidor y micro aliado de **Alquería** requiere modernizar y optimizar su proceso de ventas, el cual actualmente depende en gran medida de interacciones presenciales y procedimientos manuales. Esta situación genera retrasos, mayores costos operativos y una experiencia limitada para los clientes, quienes deben esperar la gestión directa del distribuidor para realizar cotizaciones o compras.

La creciente demanda de soluciones digitales por parte de los consumidores, sumada a la necesidad del distribuidor de mejorar la eficiencia en su operación, hace indispensable la implementación de una **aplicación web** que permita a los clientes visualizar el catálogo de productos, generar cotizaciones y realizar compras en línea de manera autónoma, rápida y sencilla.

Desde la perspectiva del negocio, la digitalización permitirá:

- **Automatizar procesos de ventas.**  
- **Optimizar la gestión de pedidos.**  
- **Reducir la necesidad de desplazamientos.**  
- **Incrementar la productividad del distribuidor.**  
- **Fortalecer la relación con los clientes.**  

Por su parte, los clientes tendrán acceso a un **canal digital confiable, flexible y accesible** en cualquier momento y desde cualquier dispositivo.

En este contexto, la necesidad principal es disponer de una **plataforma tecnológica** que garantice eficiencia operativa, facilite la autogestión por parte de los clientes y se alinee con la **identidad de marca** y los **objetivos estratégicos de Alquería**.

---
s
# Restricciones del proyecto

- **Tiempo:** la primera versión de la aplicación debe entregarse en un plazo acordado con el cliente.  
- **Presupuesto:** limitado a las funcionalidades definidas como prioritarias.  
- **Tecnología:** solución desarrollada como aplicación web responsiva.  
- **Usuarios:** orientado a clientes y distribuidor, sin contemplar perfiles administrativos avanzados.  

---

# Criterios de aceptación del proyecto

- El sistema debe permitir registro, inicio y cierre de sesión de manera correcta.  
- El catálogo de productos debe estar disponible y navegable en cualquier dispositivo.  
- Los clientes deben poder generar cotizaciones y facturas..  
- El flujo de compras debe incluir carrito de compras y confirmación del pedido.  
- El diseño debe adaptarse adecuadamente a desktop, tablet y móvil.  
- El formulario de contacto debe enviar la información de manera exitosa.  

---

# Sustento metodológico – Design Thinking (Empatizar y Definir)

## Empatizar
Se identificaron las principales dificultades del distribuidor y los clientes:  

- Procesos manuales lentos y costosos.  
- Falta de independencia para el cliente.  
- Retrasos en cotizaciones y facturación.  
- Carencia de un canal digital moderno.  

## Definir
El problema central es la ausencia de una **plataforma digital integral** que modernice el proceso de ventas.  

La solución debe priorizar:  

1. Autonomía y autogestión para los clientes.  
2. Optimización de los procesos del distribuidor.  
3. Una experiencia digital clara, rápida y accesible.  

## Herramienta de Design Thinking: Mapa de Empatía

Se aplicó la fase **Empatizar – Definir** del Design Thinking, utilizando un **Mapa de Empatía** para comprender las necesidades de los principales actores: el distribuidor (micro aliado de Alquería) y los clientes finales.

### Mapa de Empatía

| Quadrante        | Distribuidor (Aliado)                                                                 | Cliente Final                                                                 |
|------------------|---------------------------------------------------------------------------------------|-------------------------------------------------------------------------------|
| **Piensa y siente** | Los procesos manuales son lentos y costosos. <br>Necesito modernizar la operación.   | No tengo independencia para comprar. <br>Me frustra esperar respuestas lentas. |
| **Ve**             | Otros negocios ya tienen plataformas digitales. <br>Falta de competitividad.         | Que el distribuidor tarda en procesar pedidos. <br>Opciones más modernas en otros proveedores. |
| **Oye**            | Reclamos constantes de clientes por demoras.                                         | Que siempre debe esperar para cotizar o comprar.                              |
| **Dice y hace**    | Necesito digitalizar mis ventas para crecer. <br>Quiero reducir costos y errores.    | Busca rapidez y autonomía. <br>Quiere explorar catálogo y comprar online.      |

---
## Sustento metodológico – Design Thinking (Empatizar y Definir)

### Empatizar

Durante esta fase se analizaron las necesidades, motivaciones y frustraciones de los principales actores involucrados en el proyecto: **el distribuidor (micro aliado de Alquería)** y los **clientes finales**.

El propósito fue comprender de manera profunda sus puntos de vista para orientar el diseño del producto hacia una solución que responda a sus expectativas reales.  
A partir de esta etapa, se identificaron los siguientes hallazgos clave:

- Los clientes sienten **frustración** por depender del distribuidor para cotizar o realizar pedidos.  
- El distribuidor **percibe altos costos operativos** y pérdida de tiempo por los procesos manuales.  
- Ambos actores **reconocen la necesidad de una plataforma digital**, pero temen la complejidad del cambio tecnológico.  
- El distribuidor **busca eficiencia**, mientras que los clientes **desean autonomía**.  

Esta información permitió definir los principales **problemas y oportunidades**, que sirvieron como base para delimitar el alcance inicial de la aplicación.

---

### Definir

Con base en la información obtenida en la fase de empatía, se procedió a estructurar el **alcance del proyecto** de forma realista y alineada con las necesidades detectadas.

El equipo determinó qué funcionalidades son **prioritarias** para responder al problema actual del distribuidor y ofrecer valor inmediato a los clientes.  
A partir de este análisis se estableció la siguiente estrategia de alcance:

- **Primera versión (MVP):** incluir funcionalidades básicas que habiliten la digitalización inicial (registro, inicio/cierre de sesión, catálogo, cotización y diseño responsivo).  
- **Exclusión del alcance inicial:** funcionalidades complejas o de integración externa (pasarelas de pago, reportes de ventas e inventarios).  
- **Justificación:** priorizar la rapidez en la entrega del producto mínimo viable, garantizando una adopción gradual y reduciendo riesgos técnicos y de resistencia al cambio.  

---

### Definición del Problema

- El distribuidor necesita **automatizar pedidos y cotizaciones** para reducir gestiones manuales.  
- Los clientes requieren **autonomía digital** para acceder a catálogos y compras en línea.  
- El negocio requiere **una plataforma responsiva y escalable** que permita crecer a futuro.  

---

### Relación con el Alcance

- **Funcionalidades incluidas en la primera versión (MVP):**  
  - Registro, inicio/cierre de sesión y consulta de datos de usuario.  
  - Diseño responsivo.  
  - Visualización de catálogo de productos.  
  - Cotización básica.  
  - Formulario de contacto.  

- **Funcionalidades excluidas de la primera versión:**  
  - Pasarelas de pago avanzadas.  
  - Reportes de ventas detallados.  
  - Módulos de inventario.  
  - Integraciones externas con otros sistemas.  
