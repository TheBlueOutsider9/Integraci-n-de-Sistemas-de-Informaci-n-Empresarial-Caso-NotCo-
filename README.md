Integración de Sistemas de Información Empresarial en NotCo 🚀🌱

Descripción del Proyecto

Este proyecto presenta una propuesta integral para el diseño e implementación de un Sistema de Planificación de Recursos Empresariales (ERP) en NotCo, una compañía global del rubro FoodTech.

Actualmente, NotCo basa su principal ventaja competitiva en "Giuseppe", un avanzado algoritmo de inteligencia artificial capaz de formular recetas vegetales en tiempo récord. Sin embargo, la organización enfrenta una profunda fricción operativa: mientras el núcleo de Investigación y Desarrollo (I+D) opera a una velocidad computacional avanzada, los departamentos de adquisiciones, logística y finanzas trabajan de forma desconectada. Esta dependencia de sistemas fragmentados y procesos manuales genera silos de información. Como consecuencia directa, la empresa sufre de alta latencia transaccional, riesgo de quiebres de stock en plantas maquiladoras (co-packers) y pérdida de trazabilidad en su cadena de suministro. Este proyecto busca resolver dicha asimetría tecnológica.

Objetivos

Objetivo General

Proponer el diseño e implementación de un Sistema de Información Empresarial (ERP) integrado para NotCo, con el fin de eliminar los silos operativos y alinear la gestión administrativa, logística y financiera con la velocidad de su innovación tecnológica en I+D.

Objetivos Específicos

Analizar el macroentorno y los procesos operativos actuales de NotCo para diagnosticar los cuellos de botella en el flujo de información de su cadena de suministro.

Levantar los requerimientos funcionales y no funcionales necesarios para sostener la trazabilidad, calidad y expansión global de la compañía.

Diseñar una propuesta tecnológica y económica basada en un ERP de clase mundial que automatice y sincronice los procesos operacionales y estratégicos.

Definir indicadores clave de éxito (KPIs) para monitorear y controlar el impacto de la implementación tecnológica propuesta.

Análisis y Diseño

Estado Actual (AS-IS)

El análisis del modelo AS-IS evidencia un flujo de información manual y reactivo:

Desconexión I+D - Adquisiciones: Las fórmulas creadas por la IA pierden su automatización al salir del departamento, requiriendo traspasos manuales mediante correo electrónico y ofimática.

Opacidad Financiera y Logística: Las cotizaciones se gestionan en repositorios aislados, la trazabilidad de inventarios se pierde entre sistemas no conectados, y Finanzas opera bajo una contabilidad diferida, lo que imposibilita el cálculo del costo real en tiempo real.

Estado Objetivo (TO-BE)

El modelo TO-BE reestructura el ciclo operativo hacia un ecosistema transaccional unificado (Single Source of Truth):

Sincronización Transparente: Transferencia automática de datos desde I+D hacia el módulo de compras mediante APIs, eliminando la redigitación.

Control y Trazabilidad Activa: Validación presupuestaria Ex-Ante al cotizar, trazabilidad integral con bloqueos automáticos por calidad en bodega, y un cruce contable automatizado (Match de 3 vías) para habilitar los pagos.

Solución Propuesta

Se propone la implementación estratégica de SAP S/4HANA Cloud bajo el modelo de adopción RISE with SAP.

La solución destaca por su capacidad de In-Memory Computing, lo que permite procesar en milisegundos las complejas variables logísticas y financieras. El pilar de esta arquitectura es la integración nativa a través de APIs (REST/OData) entre el motor predictivo de inteligencia artificial "Giuseppe" y los módulos empresariales del ERP:

MM (Materials Management): Para automatizar el abastecimiento.

EWM (Extended Warehouse Management): Para la logística y calidad.

FI/CO (Financial Accounting / Controlling): Para el control de costos y rentabilidad.

Beneficios Esperados

Aceleración del ciclo de adquisición: Reducción drástica del time-to-market al eliminar los canales de traspaso manual entre I+D y Adquisiciones.

Trazabilidad integral de lotes: Visibilidad en tiempo real del origen, estado aduanero, inspección de calidad y costo financiero de cada ingrediente, mitigando riesgos operativos.

Control financiero ex-ante: Validación automática de presupuestos antes de emitir cualquier orden de compra, protegiendo la liquidez y evitando compras reactivas.

Conciliación automática: Sincronización perfecta entre la Orden de Compra, la recepción física y la factura del proveedor (Match de 3 vías), otorgando a la directiva una visión clara de los costos.

Equipo de Desarrollo

Felipe Madariaga

Alonso Olmedo

Juan Rivera

Johann Urcia
