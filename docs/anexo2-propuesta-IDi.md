# ANEXO 2. DOCUMENTO TÉCNICO DE LA PROPUESTA DE INVESTIGACIÓN, DESARROLLO TECNOLÓGICO Y/O INNOVACIÓN

## Convocatoria "Becas para el Cambio" — Formación en Maestrías y Doctorados
## Modalidad 1: Maestría Nacional

---

## Título de la propuesta

**De Microrredes a Infraestructura Autónoma: Un Sistema Operativo de Agentes para la Transición Energética en Zonas Remotas de Colombia**

---

## Resumen ejecutivo

Esta propuesta investiga dos preguntas escalonadas. Primero: ¿puede un agente autónomo persistente, regulado y desplegado en el borde computacional gobernar una microrred como infraestructura física crítica? Segundo: cuando múltiples agentes operan microrredes en una misma región, ¿emerge coordinación cooperativa que un agente individual no puede lograr? Las microrredes renovables en las Zonas No Interconectadas (ZNI) de Colombia proveen las restricciones de diseño más exigentes: 1.664 localidades donde 1,9 millones de personas sobreviven con menos de 6 horas diarias de electricidad generada en un 78% por diésel (IPSE, 2025; OCDE, 2023), con datos escasos, conectividad intermitente y consecuencias humanas inmediatas cuando las decisiones fallan.

Colombia invierte $349.375 miles de millones COP en infraestructura renovable para las ZNI, pero el hardware sin inteligencia fracasa silenciosamente: plantas solares en Puerto Nariño (COP $30.000 millones) llevan ocho años sin generar un kWh; proyectos en La Guajira (COP $43.000 millones) no mostraban paneles un año después del contrato (Portafolio, 2023; Vorágine, 2024). El 88% de las localidades ZNI se monitorean mediante llamadas telefónicas (IPSE, 2025). La primera capacidad que se necesita no es optimización — es observabilidad.

La propuesta plantea cuatro capas de inteligencia agéntica acumulativas: *observabilidad* (detección de anomalías y monitoreo continuo), *predicción* (modelos Transformer ligeros que reducen el ciclado innecesario de baterías mediante despacho consciente de degradación; Ouedraogo et al., 2021), *optimización* (despacho multi-objetivo con mejoras estimadas del 25-40% sobre líneas base sin controlador), y *coordinación de flota* (aprendizaje federado personalizado que reduce costos y acelera despliegues en sitios nuevos; Yang et al., 2025).

La pregunta de investigación opera en dos niveles. Aplicado: ¿cuánta inteligencia sobrevive la transferencia desde microrredes industriales con datos abundantes hacia ZNI con datos escasos? Fundamental: ¿puede un agente persistente y regulado operar como capa de decisión acotada y trazable sobre infraestructura crítica?

La arquitectura separa inteligencia y protección: la seguridad eléctrica permanece en relés y controladores dedicados; el agente opera por encima como capa supervisada y degradable. Si falla, la microrred vuelve a su comportamiento base. El agente se distingue por cuatro propiedades: *persistencia* event-sourced, *regulación homeostática* (Mineault et al., 2024; Eslami & Yu, 2026), *situatedness* (ejecuta en hardware alimentado por la microrred que gestiona), y *degradación segura*. La comunicación inter-agente utiliza protocolos federados que operan bajo conectividad intermitente.

La contribución de las ZNI es epistémica: proveen un banco de pruebas adversarial para la autonomía agéntica donde la infraestructura crítica impone consecuencias irreversibles, recursos restringidos y requisitos de seguridad. Si esta arquitectura opera de forma segura en estas condiciones, se convierte en base validada para infraestructura autónoma en otros dominios remotos. El proyecto se enmarca en la Maestría en Inteligencia Artificial (MAIA) de la Universidad de los Andes, se articula con el grupo TICSw (A1, Minciencias) y se alinea con la Misión de Transición Energética de las PIIOM.

---

## Palabras clave

1. Autonomía agéntica para infraestructura crítica
2. Sistemas operativos de agentes (Agent OS)
3. Microrredes de energía renovable en borde computacional
4. Adaptación de dominio para sistemas energéticos
5. Regulación homeostática de agentes autónomos

---

## Articulación de la propuesta con las Misiones de la Política de Investigación e Innovación Orientada por Misiones (PIIOM) del Ministerio

La presente propuesta se articula directamente con la **Misión 3: Transición Energética — Energía sostenible, eficiente y asequible**, cuyo objetivo es "garantizar el acceso y uso de energías seguras y sostenibles para todos los colombianos, a través del desarrollo, adopción y adaptación de tecnologías para la transición energética" (Resolución 1452 de 2024, Minciencias).

La articulación se manifiesta en tres dimensiones:

**Dimensión tecnológica.** La propuesta desarrolla tecnología de inteligencia artificial aplicada directamente a la operación de sistemas de energía renovable. Los sistemas multi-agente propuestos constituyen una innovación en la forma de gestionar infraestructura energética distribuida, transitando de un modelo centralizado y dependiente de operación humana hacia un modelo autónomo y coordinado. Esto responde al mandato de la misión de "desarrollo, adopción y adaptación de tecnologías para la transición energética."

**Dimensión territorial y de justicia social.** Al enfocarse en las Zonas No Interconectadas — territorios históricamente excluidos del sistema eléctrico nacional — la propuesta aborda la brecha de acceso energético como un problema de justicia social y convergencia regional. Esto se alinea con el Plan Nacional de Desarrollo 2022-2026 "Colombia Potencia Mundial de la Vida" (Ley 2294 de 2023) y con el marco normativo de comunidades energéticas (Decreto 2236 de 2023, CREG Resolución 101 072 de 2025).

**Dimensión de apropiación social del conocimiento.** La propuesta integra la construcción de grafos de conocimiento que capturan saberes territoriales y condiciones locales, permitiendo que el sistema responda a la realidad de cada comunidad. Los talleres de apropiación social previstos buscan que las comunidades no sean solo beneficiarias pasivas, sino co-constructoras del conocimiento que alimenta los agentes inteligentes.

**Dimensión de competitividad industrial y reindustrialización.** La Misión 3 incluye entre sus objetivos "impulsar los procesos de reindustrialización y transición energética" (Resolución 1452 de 2024). La propuesta contribuye al desarrollar tecnología de IA transferible entre contextos industriales y comunitarios, alineándose con el CONPES 4129 (Política Nacional de Reindustrialización) y el convenio Ecopetrol-Minciencias para CTeI en transición energética.

Adicionalmente, la propuesta presenta conexiones con la **Misión 1: Bioeconomía y territorio**, en la medida en que la electrificación sostenible de zonas rurales es condición habilitante para el desarrollo territorial sostenible y las cadenas de valor de la bioeconomía.

---

## Articulación de actores de Ciencia, Tecnología e Innovación durante la ejecución de la propuesta

La propuesta contempla la articulación de los siguientes actores del Sistema Nacional de Ciencia, Tecnología e Innovación (SNCTeI):

**1. Grupo de Investigación TICSw — Tecnologías de Información y Construcción de Software (Clasificación A1, Minciencias).** Grupo de investigación adscrito al Departamento de Ingeniería de Sistemas y Computación de la Universidad de los Andes. Clasificado en la categoría A1 (máxima clasificación) por Minciencias. El grupo aporta la capacidad investigativa en inteligencia artificial, sistemas multi-agente, grafos de conocimiento y procesamiento de lenguaje natural. La línea de investigación en tecnologías de información y su aplicación a dominios específicos provee el marco metodológico para el proyecto. El director propuesto, Profesor Rubén Francisco Manrique (PhD), miembro activo del grupo, ha publicado recientemente sobre resiliencia cooperativa en sistemas multi-agente de IA (IEEE Transactions on Artificial Intelligence, 2025) y sobre sistemas de recuperación aumentada por generación (RAG) y grafos de conocimiento, temas directamente aplicables al componente de inteligencia territorial de la propuesta.

**2. Instituto de Planificación y Promoción de Soluciones Energéticas para las Zonas No Interconectadas (IPSE).** Entidad adscrita al Ministerio de Minas y Energía, responsable de planificar y promover soluciones energéticas para las ZNI. El IPSE constituye el actor institucional clave para la validación de la propuesta, dado que administra datos sobre la operación energética de las ZNI, incluyendo información de generación, demanda, infraestructura instalada y condiciones territoriales. La articulación con el IPSE permitirá acceder a datos reales para la calibración y validación de los modelos propuestos, así como explorar rutas de transferencia tecnológica hacia implementación real. El IPSE ha identificado públicamente la inteligencia artificial como oportunidad para la optimización de soluciones energéticas en ZNI (IPSE, 2025).

**3. Sector productivo: Empresas del sector energético colombiano.** La estrategia de validación de doble vía de la propuesta requiere articulación con el sector energético para la obtención de datos operacionales de microrredes bien instrumentadas. Se contemplan tres actores principales:

- **Ecopetrol**, con 381 MW de capacidad renovable en operación al cierre de 2025 — un aumento del 94% respecto a 2024 — y un portafolio total de 951 MW que superó cinco años antes la meta original de 900 MW para 2030 (Ecopetrol, Resultados 4T 2025). Las granjas solares operativas incluyen Castilla y San Fernando (Meta, ~82 MW), La Cira Infantas (Santander, 56 MW), Portón del Sol (Caldas, 128 MW), La Iguana (Antioquia, 26 MW) y Brisas (Huila, 26,8 MW), además de una planta de hidrógeno verde en la refinería de Cartagena (USD 28,5M). Ecopetrol ha suscrito convenios de cooperación con Minciencias por $73 mil millones COP para CTeI en transición energética. La diversidad geográfica y de escala de estas instalaciones constituye un caso ideal para la validación de coordinación multi-agente a escala de flota.
- **Celsia** (Grupo Argos), líder en generación solar distribuida en Colombia con un portafolio de más de 197 MWp en proyectos de techos solares a través de su filial Atera, y un modelo de negocio que combina generación industrial con proyectos de energía comunitaria, lo que lo convierte en puente natural entre la validación industrial y la transferencia a comunidades.
- **EPM**, que además de la central Ituango (2,4 GW hidroeléctrica), cuenta con más de 800 instalaciones solares en 20 departamentos con más de 47 MWp vendidos y 88.500 paneles instalados, y ha manifestado interés en la optimización de activos renovables distribuidos.

La articulación con estas empresas permitirá acceder a datos operacionales reales de microrredes industriales y comerciales para la fase de calibración de modelos, así como validar la transferibilidad de los agentes hacia contextos comunitarios.

**4. Comunidades de las ZNI.** Los beneficiarios finales del proyecto participan como actores de co-creación y validación. Los talleres de apropiación social previstos permiten retroalimentar el diseño del sistema con conocimiento local y validar su pertinencia territorial.

---

## Área OCDE

- **Gran Área:** 2. Ingeniería y Tecnología
- **Área:** 2.B. Ingenierías Eléctrica, Electrónica e Informática
- **Disciplina:** 2B03 Automatización y sistemas de control

---

## Identificación y descripción del problema

Las microrredes de energía renovable en Colombia — desde las plantas solares industriales hasta las instalaciones fotovoltaicas en ZNI — comparten un problema estructural: operan sin inteligencia autónoma. Esta limitación se manifiesta con distinta severidad según el contexto, pero se amplifica en proporción a la vulnerabilidad del territorio. La presente propuesta aborda el problema en su forma más severa: las Zonas No Interconectadas, donde las restricciones de conectividad, datos escasos y acceso limitado hacen que la autonomía del agente sea una necesidad existencial. La validación en entornos de datos abundantes establece la línea base; la evaluación en ZNI demuestra la robustez bajo las condiciones más adversas.

El Instituto de Planificación y Promoción de Soluciones Energéticas para las Zonas No Interconectadas (IPSE) identifica 1.664 localidades clasificadas como ZNI, distribuidas en 18 departamentos y 76 municipios, que abarcan el 52% del territorio nacional y albergan a cerca de 1,9 millones de personas con una densidad poblacional de 3 habitantes/km² (IPSE, 2025). Estas comunidades, predominantemente rurales, indígenas y afrodescendientes, dependen de una capacidad instalada de 335.271 kW, de los cuales el 78% (262.056 kW) corresponde a generación diésel, con una participación renovable de apenas el 22% (IPSE, 2025). La mayoría de las localidades ZNI cuenta con servicio eléctrico limitado a menos de 6 horas diarias (OCDE, 2023). Los costos de generación superan en 3 a 5 veces el costo de la energía en el Sistema Interconectado Nacional (SIN).

En los últimos años, el gobierno colombiano ha impulsado la instalación de sistemas de energía renovable en estas zonas — el Fondo FENOGE ha comprometido $349.375 miles de millones COP para implementar hasta 500 comunidades energéticas focalizadas y priorizadas por el Ministerio de Minas y Energía (MinEnergía, 2024). Sin embargo, la experiencia ha evidenciado que la mera instalación de infraestructura renovable es insuficiente: en el departamento de Amazonas, tres plantas solares construidas con recursos públicos nunca generaron un solo kWh de energía por fallas de gobernanza y coordinación institucional (Siemens-Stiftung, 2023). La operación de estos sistemas presenta seis problemas estructurales que limitan severamente su impacto:

**0. Ausencia de observabilidad y fracaso silencioso de la inversión pública.** El problema fundacional de las soluciones energéticas en ZNI no es la falta de optimización — es la falta de observabilidad. El IPSE monitorea 188 de 1.664 localidades ZNI mediante telemetría; las restantes 1.476 se monitorean mediante llamadas telefónicas a "informantes de energía" (IPSE, 2025). Esta ceguera operativa permite que inversiones de miles de millones de pesos fracasen silenciosamente durante años: las plantas solares de Puerto Nariño (COP $30.000 millones) estuvieron ocho años sin generar un solo kWh antes de que el fracaso fuera reportado públicamente. La investigación en sistemas fotovoltaicos no monitoreados documenta pérdidas significativas de potencia por fallas no detectadas — degradación de paneles, inversores averiados, conexiones corroídas — que se acumulan hasta hacer inviable la instalación. El costo de desplegar agentes de monitoreo en hardware de borde (~$300-500 USD/nodo) en las 1.664 localidades ZNI equivaldría a USD $500.000-830.000 — menos del 0,1% de lo invertido en el proyecto fallido de Puerto Nariño. La primera capacidad que necesitan la mayoría de las microrredes en ZNI no es optimización ni predicción — es *información*: alertas de falla, reportes de rendimiento, recomendaciones de mantenimiento. Un agente cuya salida primaria es un informe diario de estado ya transforma la ecuación de gestión. Sin observabilidad, toda inversión posterior — en predicción, optimización o coordinación — carece de fundamento sobre el cual construirse.

**1. Fragmentación operativa.** Cada sistema de generación opera de manera aislada, sin coordinación con sistemas vecinos ni con la demanda comunitaria. No existen mecanismos de balanceo regional ni de intercambio energético entre comunidades cercanas, lo que genera redundancias y desperdicio de capacidad instalada.

**2. Ausencia de predicción.** Los sistemas actuales no incorporan capacidades de predicción de generación renovable (inherentemente intermitente y dependiente de condiciones climáticas locales) ni de demanda (que varía según ciclos productivos, festividades y estacionalidad). Sin predicción, los operadores no pueden anticipar excedentes ni déficits, lo que resulta en sub-utilización de energía renovable y dependencia continuada de respaldo diésel.

**3. Desconexión del conocimiento territorial.** Las decisiones de operación energética no integran el conocimiento local sobre condiciones climáticas, calendarios productivos agrícolas, restricciones sociales ni dinámicas comunitarias. El resultado es un sistema técnicamente funcional pero socialmente desacoplado de la realidad territorial que pretende servir.

**4. Inescalabilidad del modelo de operación humana.** La operación y mantenimiento de las soluciones energéticas en ZNI depende de técnicos especializados que deben desplazarse a zonas de difícil acceso. Este modelo no escala a 1.664 localidades dispersas en geografías complejas (Amazonía, Pacífico, Orinoquía, zonas insulares). El IPSE monitorea 188 localidades vía telemetría y las restantes 1.476 mediante llamadas telefónicas (IPSE, 2025). Se requiere un paradigma de operación que permita autonomía local con supervisión remota eficiente.

**5. Fragilidad institucional y fracasos documentados.** Tres plantas solares en Puerto Nariño, Amazonas (COP $30.000 millones) llevan ocho años sin generar un solo kWh, con siete suspensiones, 17 ampliaciones y un proceso penal activo ante la Corte Suprema contra el exgobernador responsable (Portafolio, 2023; El Tiempo, 2025); la comunidad energética de Bahía Málaga opera con diésel pese a estar diseñada 70/30 solar/diésel (El Espectador, 2025); y proyectos solares en La Guajira (COP $43.000 millones) acumulaban 169 días de retraso y 13 modificaciones contractuales sin entregar paneles a las comunidades Wayúu (Vorágine, 2024). Un sistema de monitoreo inteligente habría detectado estas fallas en días, no años — la inteligencia operativa no previene la corrupción, pero sí provee transparencia en tiempo real que hace los fracasos visibles y corregibles.

El problema, en síntesis, no es la disponibilidad de tecnología renovable — que ya se está instalando — sino la ausencia de una **arquitectura de capacidades graduadas** que proteja y amplifique la inversión en hardware. La brecha no se cierra con un solo sistema de "software inteligente", sino con cuatro capas de inteligencia desplegadas incrementalmente: *observabilidad* primero — para que las fallas sean visibles antes de convertirse en abandonos; *predicción* segundo — para anticipar generación y demanda y reducir el desgaste de baterías; *optimización* tercero — para maximizar el aprovechamiento de la energía renovable disponible y minimizar el respaldo diésel; y *coordinación de flota* cuarto — para que los patrones aprendidos en un sitio aceleren el despliegue en los demás. Cada capa protege la inversión de la anterior y amplifica su valor. Sin la primera capa (observabilidad), las demás no tienen datos sobre los cuales operar. Esta arquitectura graduada es la contribución central que esta propuesta desarrolla.

Este problema es de interés nacional prioritario, inscrito en la agenda de transición energética del país (CONPES 4075 de 2022, Ley 2099 de 2021) y de pertinencia directa para la Misión de Transición Energética de las PIIOM. Su solución requiere la convergencia de capacidades de inteligencia artificial, ingeniería de sistemas y conocimiento territorial que esta propuesta articula.

---

## Antecedentes

La gestión inteligente de microrredes mediante técnicas de inteligencia artificial ha sido objeto de investigación creciente a nivel global. A continuación se describen los antecedentes más relevantes:

**Sistemas multi-agente para gestión energética.** La aplicación de sistemas multi-agente (SMA) a la gestión de microrredes ha sido objeto de intensa investigación. Mahela et al. (2022) presentaron una revisión comprensiva de arquitecturas SMA para control distribuido, comercio energético y restauración de redes en *CSEE Journal of Power and Energy Systems*. Altin et al. (2023) consolidaron el estado del arte de controladores multi-agente para microrredes en *Energies*. Más recientemente, Muszynski et al. (2025) propusieron EnergyTwin, un gemelo digital basado en agentes donde cada activo energético es modelado como un agente autónomo que interactúa con un coordinador central mediante planificación de horizonte rodante. En el ámbito del aprendizaje por refuerzo multi-agente (MARL), Ye et al. (2021) desarrollaron un algoritmo multi-actor-attention-critic (MAAC) para comercio P2P en *IEEE Transactions on Smart Grid*, logrando mejoras del 15-25% en eficiencia de utilización renovable. Li et al. (2026) demostraron la aplicación de MARL con redes GRU para resiliencia de microrredes ante eventos climáticos extremos en *Expert Systems with Applications*.

**Predicción de generación renovable y demanda.** Los modelos de predicción de series temporales energéticas han evolucionado en tres generaciones: modelos estadísticos (ARIMA, Prophet), redes recurrentes (LSTM/GRU, MAPE 3-8% con datos abundantes; Wang et al., 2019), y arquitecturas Transformer ligeras. PatchTST (Nie et al., 2023) segmenta la serie temporal en parches semánticos y aplica atención sobre ellos, logrando una reducción del 21% en MSE respecto a arquitecturas Transformer previas y, crucialmente, representaciones que transfieren mejor entre dominios que las de LSTM. En paralelo, los modelos fundacionales de series temporales — Chronos-Bolt (Ansari et al., 2024), TimesFM (Das et al., 2024), Moirai-2 (Liu et al., 2025) — permiten predicción zero-shot en sitios sin datos históricos, superando modelos entrenados localmente en hasta un 70% (SPIRIT, 2025). Sin embargo, los modelos fundacionales grandes (>200M parámetros) no son viables en hardware de borde; solo las variantes compactas (Chronos-Bolt Tiny, 9M parámetros) pueden ejecutarse en computadores de placa única. Investigaciones recientes sobre LLMs como predictores de series temporales (Gruver et al., 2023) mostraron competitividad inicial, pero Park et al. (2025) demostraron que son frágiles ante ruido — modelos lineales simples los superan bajo perturbaciones mínimas, descartando su uso como predictores primarios en sistemas de misión crítica. Estos modelos han sido desarrollados y validados predominantemente en contextos de datos abundantes — su adaptación a contextos de datos escasos como las ZNI colombianas constituye un vacío identificado por Bodewes et al. (2024).

**Grafos de conocimiento para sistemas energéticos.** La aplicación de grafos de conocimiento al sector energético es un campo emergente. Chun et al. (2020) propusieron el Energy Knowledge Graph (EKG) como esquema integrador de recursos de conocimiento energético. Wang et al. (2021) revisaron el estado de desarrollo y perspectivas de grafos de conocimiento en redes inteligentes en *IET Generation, Transmission & Distribution*, identificando el potencial de la interoperabilidad semántica de datos energéticos mediante técnicas de NLP. Liu et al. (2023) desarrollaron un sistema de preguntas-respuestas basado en grafos de conocimiento eléctricos. Sin embargo, ningún trabajo publicado integra conocimiento territorial y social (patrones productivos, calendarios comunitarios, restricciones de gobernanza) en grafos de conocimiento energéticos para la gestión de microrredes.

**Agentes LLM para sistemas energéticos.** Una frontera emergente (2024-2025) es la aplicación de modelos de lenguaje de gran escala (LLM) como razonadores en agentes energéticos. Zhang, C. et al. (2026) publicaron en *Applied Energy* una revisión de trece roles de LLMs en sistemas energéticos. Wen & Chen (2025) presentaron X-GridAgent, un sistema multi-agente potenciado por LLM para análisis de redes eléctricas, y Wu et al. (2025) propusieron GridMind, integrando LLMs con solvers determinísticos para flujo óptimo de potencia. Sin embargo, toda esta literatura se enfoca en redes de gran escala en países desarrollados — la aplicación de agentes inteligentes (con o sin LLM) a microrredes comunitarias en contextos de acceso energético limitado no ha sido explorada.

**Contexto colombiano.** En Colombia, Colmenares-Quintero et al. (2023) propusieron una arquitectura centrada en datos para microrredes renovables inteligentes específicamente diseñada para ZNI colombianas en *Energies*, constituyendo el antecedente más directo para esta propuesta. Ceron et al. (2025) analizaron las oportunidades de microrredes y fuentes renovables no convencionales para la transición energética en regiones off-grid colombianas. El IPSE ha publicado análisis sobre el potencial de la inteligencia artificial para la optimización de soluciones energéticas en ZNI (IPSE, 2025), y su Centro Nacional de Monitoreo (CNM) provee telemetría en tiempo real de 188 localidades — infraestructura de datos sobre la cual pueden construirse modelos predictivos. Desde la perspectiva del grupo TICSw, Chacón-Chamorro, Manrique et al. (2025) publicaron en *IEEE Transactions on Artificial Intelligence* un marco para resiliencia cooperativa en sistemas multi-agente — definida como la capacidad de un colectivo de agentes de anticipar, preparar, resistir, recuperar y transformar ante disrupciones — validado con agentes de aprendizaje por refuerzo y agentes aumentados con LLM en el entorno Melting Pot 2.0. Mosquera, Manrique et al. (2026) publicaron en *IEEE Transactions on Artificial Intelligence* una evaluación de capacidades cooperativas de agentes LLM, y Chacón-Chamorro, Giraldo y Quijano (2026) propusieron un framework para aprender funciones de recompensa guiadas por métricas de resiliencia cooperativa. Esta línea de investigación provee el marco teórico directo para la coordinación inter-agente que esta propuesta requiere.

**Control industrial de microrredes y sus limitaciones.** Los sistemas SCADA convencionales para microrredes, organizados según la jerarquía ISA-95 y comunicados vía IEC 61850, Modbus RTU/TCP y OPC-UA, fueron "construidos para monitoreo y control básico, no para analítica predictiva, optimización dinámica ni participación en mercados en tiempo real" (Microgrid Knowledge, 2025). La plataforma VOLTTRON (DOE/PNNL) representa el antecedente más cercano a un sistema multi-agente para gestión energética: arquitectura de agentes con bus publicar-suscribir, ejecutable en Raspberry Pi, validada en el proyecto CETC. Sin embargo, VOLTTRON carece de coordinación de flota, grafos de conocimiento y adaptación de dominio — las tres brechas que esta propuesta aborda.

**Valor cuantificado de la predicción vs. reglas en microrredes.** La literatura reciente permite cuantificar el valor incremental de la predicción inteligente sobre controladores basados en reglas. Mazzola et al. (2017) evaluaron el valor del despacho basado en pronósticos en microrredes rurales off-grid (600 hogares), encontrando ahorros de costos operativos del 2-7% respecto a despacho heurístico — un beneficio modesto pero significativo en el contexto de comunidades con recursos limitados. En microrredes conectadas a la red con tarifas complejas, los ahorros pueden alcanzar 20-79% (Xendee/UCSD, 2024), pero este rango no aplica al contexto off-grid de las ZNI. Ouedraogo et al. (2021) evaluaron en *Solar Energy* el impacto de estrategias de gestión energética conscientes de la degradación sobre el ciclado de baterías en microrredes PV, mostrando que la inclusión de degradación en la función objetivo reduce significativamente los ciclos de carga/descarga — extendiendo la vida útil de las baterías, el componente más costoso de las microrredes en ZNI. Sin embargo, Pinter et al. (2025) advierten que las metodologías de evaluación típicas sobreestiman las ventajas del control predictivo (MPC) en aproximadamente un 69% debido a artefactos de promediado temporal. En el ámbito de la coordinación de flota, Yang et al. (2025) demostraron que el aprendizaje federado personalizado para microrredes interconectadas logra reducciones adicionales de costo y acelera la convergencia de nuevos sitios respecto al entrenamiento aislado. La evidencia indica que el valor de la predicción no es transformador por sí solo para sistemas off-grid, sino que se compone en capas: monitoreo + predicción + gestión de degradación de baterías + coordinación de flota generan un efecto compuesto estimado del 25-40% de mejora total respecto a la línea base sin controlador.

**Transferencia de aprendizaje para sistemas energéticos.** Sarmas et al. (2022) demostraron que la transferencia de aprendizaje reduce la necesidad de datos históricos en un 80% para predicción solar, con mejoras del 12,6% en RMSE. Gao et al. (2024) lograron transferencia sin etiquetas entre regiones climáticas mediante adaptación adversarial de dominio. Paletta et al. (2024) mostraron que la normalización informada por modelos físicos permite transferencia competitiva sin datos del sitio objetivo — técnica directamente aplicable usando datos de irradiancia de cielo despejado disponibles para cualquier coordenada colombiana (NSRDB, NASA POWER). El framework de aprendizaje federado Flower (Beutel et al., 2020) ha sido demostrado en Raspberry Pi, validando el entrenamiento colaborativo en hardware de borde. Sin embargo, ningún trabajo ha evaluado la degradación de rendimiento al transferir modelos desde microrredes bien instrumentadas hacia microrredes comunitarias con datos escasos, ni ha propuesto grafos de conocimiento como mecanismo complementario de transferencia.

**Monitoreo remoto y el costo de la ceguera operativa.** Estudios en sistemas fotovoltaicos no monitoreados demuestran pérdidas significativas de potencia por fallas no detectadas — degradación de paneles, inversores averiados y conexiones corroídas que se acumulan hasta comprometer la viabilidad de la instalación. La literatura sobre monitoreo remoto de mini-redes en países en desarrollo documenta reducciones sustanciales en costos de operación y mantenimiento, con períodos de recuperación de inversión inferiores a un año, debido a la reducción de visitas técnicas de emergencia y la detección temprana de fallas (ESMAP/World Bank, 2019). En el contexto colombiano, el IPSE monitorea 188 de 1.664 localidades ZNI vía telemetría; las restantes 1.476 se monitorean mediante llamadas telefónicas a "informantes de energía" — un modelo que no detectó el fracaso de Puerto Nariño durante ocho años. El costo de desplegar agentes de monitoreo en las 1.664 localidades (~USD 500.000-830.000 en hardware) equivale a menos del 0,1% de lo invertido en el proyecto fallido de Puerto Nariño (COP $30.000 millones). Esta evidencia fundamenta la decisión arquitectónica de la propuesta de priorizar la observabilidad como la primera capa de inteligencia, sobre la cual se construyen las capas de predicción, optimización y coordinación.

**Brechas identificadas.** La revisión de la literatura permite identificar las siguientes brechas convergentes que esta propuesta aborda: (i) no existe un sistema que integre grafos de conocimiento como sustrato semántico para la toma de decisiones de agentes autónomos en microrredes; (ii) los marcos de resiliencia cooperativa multi-agente no han sido aplicados a sistemas energéticos; (iii) los modelos de predicción energética no han sido evaluados sistemáticamente en su transferibilidad desde entornos de datos abundantes hacia entornos de datos escasos típicos de ZNI; (iv) la arquitectura multi-agente VOLTTRON, el referente más cercano, carece de coordinación de flota, grafos de conocimiento y adaptación de dominio; (v) América Latina está severamente subrepresentada en la literatura de MARL para microrredes; (vi) no existe implementación alguna de un agente autónomo persistente y regulado para la gestión de microrredes en ZNI colombianas; y (vii) no existe evidencia publicada de monitoreo inteligente a escala de flota para microrredes en países en desarrollo — las plataformas comerciales existentes (SparkMeter, SteamaCo, SolarAssistant) proveen monitoreo pero carecen de predicción basada en ML, despacho autónomo y coordinación multi-agente. Esta propuesta aborda precisamente esa convergencia.

---

## Justificación

La pertinencia de esta propuesta se fundamenta en cuatro pilares:

**Pertinencia nacional y oportunidad temporal.** La convergencia en 2025-2026 de tres factores crea una ventana de oportunidad única: (i) un marco regulatorio recién aprobado para comunidades energéticas (Decreto 2236 de 2023; CREG 101 072 de 2025), (ii) inversión masiva en infraestructura renovable en ZNI (FENOGE, $349 mil millones COP para hasta 500 comunidades energéticas; MinEnergía, 2024), y (iii) avances en IA de borde que permiten ejecutar modelos en hardware de $80 con menos de 0,5 GB de memoria. Sin embargo, el marco normativo avanza más rápido que la capacidad tecnológica: existe el mandato de crear comunidades energéticas autónomas, pero no las herramientas de software inteligente para operarlas. Esta propuesta contribuye a cerrar esa brecha, alineándose con la Ley 2099 de 2021, el CONPES 4075 de 2022 y el Plan Nacional de Desarrollo 2022-2026.

**Pertinencia científica.** La convergencia de sistemas multi-agente, grafos de conocimiento contextual y predicción renovable en contextos de datos escasos constituye un vacío en la literatura. La propuesta genera nuevo conocimiento en: (i) arquitecturas multi-agente agnósticas al dominio para microrredes con restricciones severas de conectividad; (ii) cuantificación de la degradación al transferir modelos predictivos desde entornos de datos abundantes hacia datos escasos; (iii) modelos de predicción calibrados para condiciones tropicales colombianas; y (iv) grafos de conocimiento contextual para gestión energética. La estrategia de validación de doble vía convierte la brecha entre datos abundantes y escasos en pregunta de investigación explícita, contribuyendo a la frontera de domain adaptation en sistemas energéticos.

**Pertinencia social y enfoque diferencial.** Las ZNI concentran poblaciones históricamente excluidas: cerca del 78% de las localidades se concentra en el Pacífico (Nariño: 600, Chocó: 509, Cauca: 189), donde el 82,1% de la población en Chocó es afrodescendiente y el 53% de los municipios de mayoría afrodescendiente presentan pobreza multidimensional (DANE, 2023). La dependencia de diésel perpetúa vulnerabilidades económicas y de seguridad, y la contaminación del aire doméstico por cocción con leña causa 2,9 millones de muertes prematuras anuales a nivel global (WHO, 2023). La propuesta incorpora apropiación social del conocimiento con talleres que incluyen líderes comunitarios, mujeres cabeza de hogar y autoridades étnico-territoriales.

**Factibilidad técnica e institucional.** La arquitectura desacopla inteligencia de protección: la seguridad eléctrica permanece en relés y controladores dedicados; la inteligencia se despliega en hardware de borde (~$300-500 USD/nodo). A este costo, incluso mejoras del 2-7% (Mazzola et al., 2017) amortizan la inversión en el primer año, comparado con controladores comerciales a $155.000 USD/MW promedio (NREL, 2018). La viabilidad de IA de borde cuenta con evidencia convergente: Huang et al. (2025) lograron 30% más utilización renovable con Raspberry Pi; VOLTTRON (DOE/PNNL) reduce consumo pico en 15%; SolarAssistant opera en miles de instalaciones en países en desarrollo. Un prototipo funcional con 155 pruebas automatizadas valida la viabilidad arquitectónica, construido sobre un runtime Rust con persistencia event-sourced, regulación homeostática y comunicación federada — diseño inherentemente fail-safe donde la falla degrada al statu quo, nunca a un estado inseguro. El candidato aporta experiencia en IA para el sector energético; el grupo TICSw (A1) provee respaldo institucional y expertise en grafos de conocimiento y sistemas multi-agente, con colaboración activa de los profesores Manrique, Giraldo y Quijano (IEEE TAI, 2025).

---

## Marco teórico

La propuesta se fundamenta en siete cuerpos teóricos:

**1. Sistemas multi-agente (SMA).** Un sistema multi-agente es un sistema compuesto por múltiples agentes de software que interactúan entre sí para lograr objetivos individuales o colectivos (Wooldridge, 2009). En el contexto de microrredes, cada agente representa una unidad de generación-consumo que toma decisiones autónomas de despacho mientras coopera con otros agentes para maximizar el bienestar del sistema completo. Los enfoques de coordinación multi-agente relevantes incluyen: negociación distribuida (Smith, 1980), aprendizaje por refuerzo multi-agente (MARL) (Zhang et al., 2021), y protocolos de consenso (Olfati-Saber et al., 2007). La reciente publicación de Chacón-Chamorro, Manrique et al. (2025) define la resiliencia cooperativa — la capacidad de un colectivo de agentes de anticipar, preparar, resistir, recuperar y transformar ante disrupciones — y provee una metodología cuantitativa para su medición, directamente aplicable a la evaluación de coordinación de agentes en microrredes bajo condiciones adversas.

**2. Predicción de series temporales energéticas: arquitectura híbrida de tres niveles.** La predicción de generación renovable y demanda energética se modela como un problema de pronóstico de series temporales multivariadas. La propuesta adopta una arquitectura de predicción de tres niveles diseñada para operar en el borde computacional:

*Nivel 1 — Predictor de borde (cada nodo RPi):* Modelos Transformer ligeros tipo PatchTST (Nie et al., 2023), que segmentan la serie temporal en parches semánticos y aplican atención sobre ellos. PatchTST logra una reducción del 21% en MSE respecto a arquitecturas Transformer previas en benchmarks de series temporales (Nie et al., 2023) y, crucialmente, sus representaciones basadas en parches transfieren mejor entre dominios que las de LSTM, porque capturan patrones locales generalizables. Cuantizado a INT8, un PatchTST ocupa ~250-500 KB con inferencia estimada <2 ms en RPi 5 (basado en benchmarks de modelos TFLite de tamaño comparable en ARM Cortex-A76; la validación específica en RPi 5 se realizará en Fase 2). Como respaldo, se mantiene un LSTM cuantizado (~800 KB, <0,5 ms) para escenarios donde PatchTST no converge. Ambos modelos incorporan normalización por cielo despejado (clear-sky normalization) usando datos de irradiancia teórica (NSRDB, NASA POWER o PVLib), que transforma la predicción solar de un problema dependiente del dominio a uno cuasi-invariante (Nie et al., 2024). Los intervalos de predicción se obtienen mediante predicción conforme (conformal prediction), que no requiere supuestos distribucionales y provee al optimizador de despacho intervalos calibrados para decisiones conservadoras bajo incertidumbre.

*Nivel 2 — Inteligencia de flota (coordinador):* Modelos fundacionales de series temporales (Chronos-Bolt, 9M parámetros, viable en RPi; Ansari et al., 2024) para predicción zero-shot en sitios nuevos sin datos históricos — el escenario de arranque en frío de cada ZNI. El aprendizaje federado (Flower; Beutel et al., 2020) permite mejora colaborativa entre agentes agrupados por clúster climático, sin compartir datos crudos.

*Nivel 3 — Razonamiento causal (el agente):* El módulo de razonamiento del agente NO produce pronósticos numéricos — la literatura reciente demuestra que los LLM son frágiles ante ruido en predicción de series temporales, con modelos lineales simples que los superan (Park et al., 2025). En cambio, el agente razona sobre los pronósticos: interpreta anomalías ("la generación cayó 40% — ¿nubosidad o degradación de panel?"), consulta el grafo de conocimiento para contexto causal, y toma decisiones de despacho que integran predicciones + restricciones + conocimiento territorial. La implementación primaria de este módulo utiliza heurísticas basadas en reglas (árboles de decisión sobre umbrales de los modelos predictivos); como extensión de investigación, se evaluará la viabilidad de modelos de lenguaje ternarios (BitNet 1.58-bit, 2B parámetros, ~0,4 GB) como razonadores flexibles en el borde.

**3. Grafos de conocimiento.** Un grafo de conocimiento es una representación formal de entidades y sus relaciones en un dominio específico, expresada como un conjunto de tripletas (sujeto, predicado, objeto) (Hogan et al., 2021). En esta propuesta, el grafo de conocimiento energético-territorial integra: (i) recursos energéticos (paneles solares, turbinas, baterías, generadores diésel), (ii) condiciones ambientales (irradiancia, régimen de lluvias, temperatura), (iii) patrones de consumo (ciclos productivos agrícolas, horarios comunitarios, festividades), y (iv) restricciones sociales (prioridades de uso, gobernanza comunitaria). La construcción del grafo emplea técnicas de extracción de información de textos técnicos y reportes mediante procesamiento de lenguaje natural, siguiendo la línea de investigación del grupo TICSw en organización automática de recursos mediante grafos de conocimiento (Manrique et al., 2018).

**4. Optimización de despacho energético.** El problema de despacho óptimo de una microrred se formula como un problema de optimización multi-objetivo que busca minimizar simultáneamente el costo operativo, las emisiones de CO₂ y la energía no servida, sujeto a restricciones de balance energético, capacidad de almacenamiento, límites de generación y restricciones de rampas. Los enfoques de solución incluyen programación lineal mixta entera (MILP), metaheurísticas (algoritmos genéticos, optimización por enjambre de partículas), y aprendizaje por refuerzo profundo (Deep RL) que aprende políticas de despacho directamente de la experiencia operativa (François-Lavet et al., 2018).

**5. Transferencia de aprendizaje y adaptación de dominio para sistemas energéticos.** La transferencia de aprendizaje (transfer learning) permite reutilizar modelos entrenados en un dominio fuente con datos abundantes para mejorar el rendimiento en un dominio objetivo con datos escasos (Pan & Yang, 2010). En el contexto de esta propuesta, el dominio fuente son microrredes bien instrumentadas (industriales o de bases de datos abiertas) y el dominio objetivo son las ZNI colombianas. Las técnicas relevantes incluyen: pre-entrenamiento en dominio fuente seguido de ajuste fino (fine-tuning) con datos limitados del dominio objetivo, alineación de características (feature alignment) para reducir la discrepancia entre distribuciones de datos, y aprendizaje federado (federated learning) que permite mejorar modelos de forma colaborativa entre múltiples sitios sin compartir datos crudos — relevante tanto para privacidad de datos industriales como para restricciones de ancho de banda en ZNI. La compresión de modelos mediante cuantización (TensorFlow Lite), destilación de conocimiento y poda permite transferir la capacidad de modelos entrenados en servidores industriales hacia hardware de borde con recursos limitados, con degradaciones típicas de MAPE inferiores al 5% absoluto (Jacob et al., 2018). Los grafos de conocimiento constituyen un mecanismo complementario de transferencia: al codificar relaciones causales entre variables (e.g., estacionalidad → irradiancia → generación solar), permiten que un agente en un sitio nuevo con datos escasos aproveche la estructura causal aprendida en sitios con datos abundantes, reduciendo la necesidad de datos históricos extensos.

**6. Arquitecturas de agentes autónomos y gobernanza mediante teoría de control.** La propuesta adopta un enfoque de agente nativo de IA (AI-native agent) en el que el núcleo de razonamiento del sistema es un módulo de toma de decisiones capaz de ejecutar herramientas (invocación de funciones) para interactuar con el entorno físico de la microrred — un paradigma emergente formalizado recientemente en "A Control-Theoretic Foundation for Agentic Systems" (Eslami & Yu, arXiv:2603.10779, marzo 2026). En esta arquitectura, el agente utiliza herramientas (lectura de sensores vía Modbus, optimización LP, consultas al grafo de conocimiento) para tomar decisiones situadas en contexto. El módulo de razonamiento admite dos implementaciones: (a) heurísticas basadas en reglas como línea base determinista, y (b) un modelo de lenguaje ligero como razonador flexible, cuya viabilidad en el borde será evaluada como pregunta de investigación. La gobernanza del agente se implementa mediante un controlador homeostático inspirado en mecanismos biológicos de regulación (Mineault et al., 2024; "NeuroAI for AI Safety"), que define puntos de operación (setpoints), puertas de seguridad (safety gates) y lazos de retroalimentación evaluador-gobernado (EGRI: Evaluator-Governed Recursive Improvement) donde el agente evalúa sus propias predicciones contra los resultados observados y ajusta sus parámetros operativos. Los avances recientes en modelos de lenguaje ternarios de 1.58 bits (BitNet; Ma et al., 2024) sugieren que estos razonadores podrían operar en hardware de borde con menos de 0,4 GB de memoria no embebida y 0,028 J por token de inferencia, abriendo la posibilidad de desplegar agentes con capacidad de razonamiento en computadores de placa única alimentados por energía solar. Sin embargo, la calidad de razonamiento de modelos de 2B parámetros es limitada y su madurez para aplicaciones de misión crítica aún no está demostrada (Microsoft, 2025), por lo que la arquitectura prioriza las heurísticas deterministas como mecanismo primario de decisión y evalúa el modelo de lenguaje como extensión experimental. Esta convergencia entre teoría de control, IA agentiva y modelos eficientes de borde constituye una frontera de investigación activa que esta propuesta contribuye a explorar en un dominio de aplicación concreto.

**7. Sistemas operativos agénticos y computación autónoma de borde.** El concepto de "sistema operativo para agentes" (Agent OS) ha emergido como un paradigma diferenciado en 2024-2026, distinguiéndose tanto de los frameworks de agentes (LangChain, CrewAI — herramientas para construir agentes) como de las plataformas de agentes (infraestructura en la nube para hospedar agentes). Un Agent OS provee primitivas a nivel de kernel: gestión del ciclo de vida de procesos, memoria basada en eventos, ejecución de herramientas con seguridad basada en capacidades, comunicación inter-agente y políticas de gobernanza (Mei et al., COLM 2025). Esta distinción es fundamental para el contexto de las ZNI: los frameworks y plataformas existentes asumen conectividad permanente a la nube y recursos computacionales abundantes — supuestos que no se cumplen en el borde.

La arquitectura de esta propuesta se fundamenta en un runtime de agentes basado en Rust que provee tres primitivas distintivas no presentes en los frameworks de agentes existentes:

(a) *Persistencia basada en eventos (event sourcing).* Cada lectura de sensor, predicción, decisión de despacho y anomalía detectada se registra como un evento inmutable en un diario de solo-adición (append-only journal). Este diseño provee trazabilidad completa de cada decisión del agente, reproducibilidad determinista del comportamiento (cualquier estado puede reconstruirse reproduciendo la secuencia de eventos), y conformidad con los requisitos emergentes de auditoría de sistemas de IA (Reglamento (UE) 2024/1689, en vigor pleno a partir de agosto de 2026). En el contexto de las ZNI, donde la falta de transparencia ha permitido que plantas solares de COP $30.000 millones permanezcan abandonadas durante años sin detección, la trazabilidad inmutable constituye un mecanismo de rendición de cuentas por diseño.

(b) *Regulación homeostática.* El agente se autorregula a través de tres dimensiones: operacional (transiciones de modo entre estados explorar/ejecutar/verificar/recuperar, determinadas por las condiciones del entorno y la confianza en las predicciones), cognitiva (gestión de la presión de contexto y los recursos computacionales disponibles — el agente reduce la complejidad de sus modelos cuando el hardware está bajo estrés térmico o energético), y económica (adaptación del comportamiento según el presupuesto de recursos disponibles — si la batería está por debajo de un umbral crítico, el agente prioriza funciones esenciales sobre optimización). Este paradigma, inspirado en la homeostasis biológica (Mineault et al., 2024), representa un enfoque de seguridad distinto de las restricciones rígidas: el agente se regula naturalmente bajo escasez de recursos en lugar de fallar abruptamente.

(c) *Comunicación federada.* Los agentes descubren y se comunican con pares mediante una capa de mensajería distribuida, habilitando coordinación a nivel de flota sin servidor central — una propiedad crítica para sitios ZNI con conectividad intermitente. Cuando la conectividad se pierde, cada agente opera de forma autónoma con su modelo local; cuando se restablece, los agentes sincronizan aprendizajes acumulados mediante protocolos de almacenamiento y reenvío, sin requerir que todos los nodos estén simultáneamente en línea. Yang et al. (2025) demostraron que el aprendizaje federado personalizado para microrredes interconectadas logra reducciones adicionales de costo y acelera significativamente la convergencia de nuevos sitios respecto al entrenamiento aislado.

El contexto de despliegue de esta arquitectura genera una propiedad autorreferencial singular: el agente ejecuta en un dispositivo de borde (Raspberry Pi) alimentado por energía solar, que a su vez forma parte de la microrred que el propio agente gestiona. La calidad de las decisiones de despacho del agente afecta directamente sus propios recursos computacionales — un agente que desperdicia energía no puede sostener su propia inferencia. Esta topología crea una presión de selección natural hacia un comportamiento conservador y energéticamente eficiente: el agente que optimiza mal, se apaga a sí mismo. La gestión autónoma de energía en naves espaciales (desde la década de 1980) constituye el análogo más cercano en la literatura, pero las naves espaciales no utilizan razonamiento basado en aprendizaje automático ni sirven a consumidores externos — la combinación de autonomía energética, aprendizaje adaptativo y servicio a comunidades humanas no tiene precedente directo.

La implicación de investigación trasciende el dominio energético: si esta arquitectura logra gestionar infraestructura física bajo las restricciones de las ZNI (sin conectividad, datos escasos, clima extremo), valida la computación autónoma de agentes para cualquier sistema crítico remoto — tratamiento de aguas, agricultura de precisión, telecomunicaciones, gestión de edificios — donde las mismas restricciones de autonomía, robustez y auditabilidad aplican.

---

## Objetivos

### Objetivo general

Diseñar, implementar y evaluar un agente autónomo persistente, regulado y desplegable en el borde computacional para la gestión de microrredes de energía renovable como infraestructura física crítica, basado en un sistema operativo agéntico con persistencia event-sourced y regulación homeostática, que integre capas incrementales de observabilidad, predicción, optimización de despacho y coordinación de flota. La evaluación cuantificará tanto el valor marginal de cada capa de inteligencia sobre la operación de la microrred, como las propiedades que definen la viabilidad de la autonomía agéntica sobre infraestructura crítica — persistencia, regulación acotada, degradación segura, trazabilidad longitudinal y adaptación bajo transferencia de dominio — validando el sistema bajo las restricciones extremas de las Zonas No Interconectadas de Colombia.

### Objetivos específicos

0. **Observabilidad como primera capa de inteligencia.** Implementar un módulo de detección de anomalías que procese flujos de datos simulados de sensores de microrredes (generación PV, estado de carga de batería, demanda, estado de generador diésel), con latencia de detección inferior a 1 hora para fallas críticas, tasa de falsos positivos inferior al 5% y tasa de detección superior al 90% sobre un conjunto de al menos 20 tipos de falla inyectados. La evaluación se realizará contra la línea base actual del IPSE (monitoreo telefónico) para fundamentar la viabilidad económica del despliegue de agentes de borde.

1. **Grafo de conocimiento energético-contextual.** Construir un grafo de conocimiento con ontología energético-territorial, instanciado para al menos dos perfiles climático-operacionales representativos de ZNI (alta irradiancia tipo Orinoquía y alta nubosidad tipo Pacífico), con al menos 100 entidades, 500 relaciones y tiempo de consulta inferior a 100 ms, a partir de fuentes abiertas (IPSE, NSRDB, NASA POWER, datos.gov.co). La extensión con conocimiento territorial y social se realizará de forma contingente a la articulación institucional lograda durante el programa.

2. **Predicción con cuantificación de adaptación de dominio.** Desarrollar y validar modelos de predicción de generación renovable y demanda (PatchTST cuantizado, Chronos-Bolt zero-shot) en dos regímenes de datos: entornos abundantes (MAPE objetivo <10%) y entornos de datos escasos representativos de ZNI (MAPE objetivo <15% en alta irradiancia, <25% en alta nubosidad). Documentar la curva completa de adaptación de dominio — MAPE(zero-shot) → MAPE(7 días) → MAPE(30 días) → MAPE(365 días) — cuantificando explícitamente la degradación y las estrategias que la mitigan (transferencia de aprendizaje, compresión de modelos, normalización por cielo despejado, grafos de conocimiento como sustituto de datos históricos).

3. **Arquitectura de agente autónomo con propiedades verificables.** Implementar el agente con seis propiedades verificables mediante pruebas automatizadas: (a) *persistencia* — 100% de estados reconstruibles desde el journal de eventos; (b) *regulación homeostática* — transición de modo observada en al menos 3 escenarios de estrés simulados; (c) *degradación segura* — cero estados inseguros en toda la suite de pruebas; (d) *situatedness* — decisiones de inferencia condicionadas al estado de carga de batería; (e) *aprendizaje longitudinal* — MAPE(día 30) < MAPE(día 7); y (f) *accountability* — cualquier decisión reconstruible desde el log de eventos. El agente se desplegará en un prototipo urbano autónomo (Raspberry Pi + panel solar + batería + carga simulada) operando de forma aislada durante al menos 2 semanas continuas para validar las propiedades en hardware real. La coordinación de flota mediante aprendizaje federado entre 2+ agentes se evaluará como extensión contingente al cronograma.

4. **Evaluación comparativa en simulación y validación en hardware.** Ejecutar una estrategia de validación en cuatro fases: (F-Sim) simulación con perfiles representativos de al menos 3 zonas climáticas de ZNI usando pymgrid, comparando cuatro configuraciones (sin controlador, controlador basado en reglas, agente con predicción ML, agente con coordinación de flota) bajo al menos 1.000 escenarios climáticos por configuración, con significancia estadística (p<0,05) en al menos 3 de 5 métricas (fracción de energía renovable, ciclos de batería, consumo diésel, energía no servida, costo operativo); (F-Proto) validación de las 6 propiedades agénticas en el prototipo urbano autónomo; (F-Industria) exploración de validación en modo sombra con un actor del sector energético, contingente a la articulación lograda durante el programa; y (F-Comunidad) validación de pertinencia mediante talleres con actores del ecosistema energético ZNI (IPSE, operadores, comunidades), contingentes a la articulación institucional.

---

## Alcance de la propuesta

La propuesta se inscribe en el marco de la Maestría en Inteligencia Artificial (MAIA) de la Universidad de los Andes y se articula con la Misión de Transición Energética de las PIIOM del Ministerio de Ciencia, Tecnología e Innovación. El programa MAIA provee formación directamente aplicable al proyecto: MAIA4342 (Sistemas de Decisión y Control Inteligente) cubre control clásico, lógica difusa y teoría de juegos para sistemas multi-agente; MAIA4212 (Aprendizaje por Refuerzo) provee las bases para políticas de despacho adaptativas; MAIA4332 (NLP Avanzado) habilita la integración de modelos de lenguaje como razonadores en los agentes autónomos; y MAIA4371 (Web Semántica) fundamenta la construcción de grafos de conocimiento.

El alcance del proyecto comprende:

**Alcance técnico:** Diseño, implementación y validación en simulación de un agente autónomo de borde para la gestión de microrredes como infraestructura crítica, con arquitectura edge-first que no depende de conectividad permanente a internet — requisito crítico dado que más del 67% de hogares rurales colombianos carece de acceso a internet (DANE, Encuesta Nacional de Calidad de Vida, 2022). La arquitectura es agnóstica al dominio: el núcleo del agente (ciclo percibir → predecir → optimizar → actuar), la formulación de despacho y los protocolos de coordinación son matemáticamente idénticos para una planta de 10 MW y una microrred de 100 kW. Lo que varía es el hardware (servidores vs. computadores de placa única), la disponibilidad de datos, la conectividad y la complejidad del grafo de conocimiento. Esta separación entre núcleo invariante y capas de adaptación habilita la validación de doble vía.

El prototipo incluirá: (i) un módulo de predicción de generación/demanda con arquitectura híbrida de tres niveles — PatchTST cuantizado como predictor primario de borde (~500 KB, inferencia estimada <2 ms), LSTM cuantizado como respaldo (~800 KB, <0,5 ms), y modelo fundacional (Chronos-Bolt, 9M parámetros) para arranque en frío zero-shot en sitios nuevos — con normalización por cielo despejado (NSRDB/NASA POWER/PVLib), intervalos de predicción conforme, y evaluación explícita de degradación MAPE al transferir entre dominios; (ii) un módulo de despacho óptimo por agente basado en programación lineal que consume los intervalos de predicción para decisiones conservadoras bajo incertidumbre; (iii) un protocolo de transferencia de conocimiento inter-agente basado en aprendizaje federado por clúster climático, que opera tanto en conectividad confiable como intermitente; y (iv) un grafo de conocimiento ligero instanciable para diferentes contextos operativos. El módulo de razonamiento del agente interpreta pronósticos y anomalías pero no produce predicciones numéricas directamente, separando la inferencia estadística (especializada, eficiente) del razonamiento causal (flexible, contextual). Este módulo se implementa como heurísticas basadas en reglas (línea base determinista) y, como extensión de investigación, se evaluará la viabilidad de modelos de lenguaje ternarios (BitNet 1.58-bit) como razonadores de borde. La validación se realizará en ambiente de simulación comparando contra controladores basados en reglas convencionales (el estándar de facto en controladores comerciales como Victron Cerbo GX), evaluando el rendimiento en dos regímenes: datos abundantes (línea base) y datos escasos de ZNI (evaluación de transferibilidad). El despliegue de campo constituiría una fase posterior de transferencia tecnológica.

**Alcance geográfico y estrategia de validación por fases.** La validación del sistema sigue una progresión de cuatro fases con niveles crecientes de realismo y complejidad:

*Fase 1 — Simulación (comprometido, Semestres 1-3):* Evaluación en simulación utilizando tres perfiles climático-operacionales representativos de la diversidad de ZNI colombianas, con datos satelitales de coordenadas reales: (i) **Perfil Orinoquía** (alta irradiancia solar, 5,0-5,5 kWh/m²/día — referencia: Inirida, Guainía, donde opera la mayor planta solar en ZNI con 2,47 MWp); (ii) **Perfil Pacífico** (baja irradiancia, 3,0-3,5 kWh/m²/día, alta nubosidad — referencia: Coquí, Nuquí, Chocó, comunidad energética con 101 kVA solar + 150 kVA diésel + 430 kWh almacenamiento); (iii) **Perfil Insular** (potencial híbrido eólico-solar, 7,0 m/s viento — referencia: Providencia, programa "Santa Catalina Verde"). Los datos de irradiancia se obtienen de NSRDB/NASA POWER para las coordenadas de cada sitio de referencia; los perfiles de demanda se generan con RAMP calibrado para comunidades rurales colombianas. La selección de sitios específicos para fases posteriores se realizará durante el programa, informada por los resultados de simulación y las articulaciones institucionales logradas.

*Fase 2 — Prototipo urbano autónomo (comprometido, Semestres 3-4):* Despliegue de un nodo agéntico completo (Raspberry Pi + panel solar 100W + batería LiFePO4 + carga simulada) operando de forma aislada y autónoma en Bogotá durante al menos 2 semanas continuas. Este prototipo valida las 6 propiedades agénticas en hardware real: el agente gestiona su propia energía, se regula ante variabilidad climática urbana, persiste sus decisiones, y degrada de forma segura ante condiciones adversas.

*Fase 3 — Validación industrial (esperado, Semestre 4 y posterior):* Despliegue en modo sombra (shadow deployment) junto a un controlador existente en una instalación del sector energético, donde el agente observa el sistema real, genera recomendaciones, y su desempeño se compara contra las decisiones del controlador convencional — sin intervenir en la operación. Los actores potenciales incluyen Ecopetrol, Celsia, EPM, microrredes de campus universitario, o instalaciones del IPSE. La articulación se desarrollará durante el programa mediante la red de TICSw y MAIA.

*Fase 4 — Despliegue en sitio remoto (futuro, post-tesis):* Implementación operativa del agente en una microrred en territorio ZNI, con inversión multi-actor (universidad, programas gubernamentales como IPSE/FENOGE, sector productivo, inversionistas externos). Esta fase requiere articulación institucional, validación regulatoria y coinversión que exceden el alcance temporal de la maestría, pero constituyen la ruta natural de transferencia tecnológica de los resultados de las Fases 1-3.

**Alcance temporal:** Cuatro (4) semestres académicos, ejecutados en paralelo con la carga académica del programa MAIA — cuyas asignaturas (MAIA4342 Control Inteligente, MAIA4212 Aprendizaje por Refuerzo, MAIA4332 NLP Avanzado, MAIA4371 Web Semántica) alimentan directamente los componentes del proyecto. Las fases se distribuyen así:

- **F1 — Fundamentos (Semestre 1):** Revisión sistemática de literatura, construcción del grafo de conocimiento técnico-energético a partir de fuentes abiertas, configuración del entorno de simulación (pymgrid + NSRDB + RAMP + PVLib), y desarrollo del módulo de detección de anomalías.
- **F2 — Modelos (Semestre 2):** Entrenamiento y evaluación de modelos predictivos (PatchTST, Chronos-Bolt), cuantización a TFLite, evaluación de adaptación de dominio entre perfiles climáticos, documentación de la curva de degradación.
- **F3 — Agente (Semestre 3):** Integración de la arquitectura agéntica en RPi (persistencia event-sourced, regulación homeostática, despacho LP, grafo de conocimiento), verificación de las 6 propiedades mediante pruebas automatizadas, ejecución de la comparación de 4 configuraciones en simulación, montaje del prototipo urbano autónomo.
- **F4 — Validación y publicación (Semestre 4):** Operación autónoma del prototipo urbano (≥2 semanas), análisis de resultados de simulación, redacción de artículo y tesis, exploración de validación industrial en modo sombra (contingente), talleres de validación con actores del ecosistema (contingente).

**Estructura de compromisos:**

| Nivel | Entregables | Estado |
|-------|-------------|--------|
| **Comprometido** | Módulo de detección de anomalías, grafo de conocimiento técnico (2 perfiles), modelos predictivos con curva de degradación, agente con 6 propiedades verificadas, prototipo urbano autónomo operando ≥2 semanas, comparación de 4 configuraciones en simulación (1.000+ escenarios), código abierto, tesis | Entrega garantizada |
| **Esperado** | Artículo sometido a revista indexada Scopus, ponencia en conferencia internacional, modelos TFLite para 3 perfiles climáticos | Alta confianza, sujeto a cronograma |
| **Contingente** | Aprendizaje federado entre 2+ agentes, validación industrial en modo sombra, extensión social del grafo de conocimiento, talleres con comunidades o actores ZNI | Sujeto a articulación institucional durante el programa |
| **Futuro (post-tesis)** | Despliegue en sitio remoto ZNI, certificación regulatoria, despliegue a escala de flota, producto comercial u open-source sostenible | Requiere coinversión multi-actor |

**Estrategia de acceso a datos — doble vía.** *Vía 1 (datos abundantes):* bases de datos abiertas NSRDB/NREL (resolución 30 min para coordenadas colombianas), IEEE Distribution Test Systems, Pecan Street Dataport; datos del operador XM (generación, demanda, precios horarios); y se explorará acceso a datos de Ecopetrol/Celsia/EPM mediante convenio TICSw. *Vía 2 (datos escasos):* datos abiertos IPSE (datos.gov.co), irradiancia NSRDB/IDEAM/NASA POWER, perfiles sintéticos de demanda (PVLib/RAMP); y se buscará telemetría del CNM del IPSE. La Vía 1 se sustenta en fuentes abiertas de acceso garantizado; la brecha entre Vía 1 y Vía 2 constituye la medición central de transferibilidad.

**Articulación con la PIIOM:** La propuesta contribuye al objetivo de la Misión de Transición Energética al desarrollar tecnología de inteligencia artificial que habilita la operación autónoma y eficiente de infraestructura de energía renovable en los territorios más excluidos del sistema energético nacional. Los resultados son directamente transferibles a la política pública de comunidades energéticas (Decreto 2236 de 2023) y al programa de electrificación de ZNI del IPSE.

---

## Lugar de ejecución de la propuesta

Universidad de los Andes, Maestría en Inteligencia Artificial (MAIA), Bogotá D.C., Colombia. El programa MAIA se imparte en modalidad virtual (SNIES 116021, Registro Calificado Resolución 2565 de 2023). La investigación (desarrollo de software, entrenamiento de modelos, simulaciones) se realizará de forma remota. El prototipo urbano autónomo (Fase 2) se desplegará en Bogotá. La validación industrial en modo sombra (Fase 3) se realizará en las instalaciones del actor que se articule durante el programa. El despliegue en sitio remoto ZNI (Fase 4) constituye una fase posterior de transferencia tecnológica que requiere coinversión multi-actor.

---

## Resultados esperados y productos I+D+i

### 1. Productos resultados de actividades de generación de nuevo conocimiento

| Producto | Descripción | Semestre |
|----------|-------------|----------|
| Artículo científico | "Bounded Autonomous Agents for Critical Infrastructure: Domain Adaptation and Agentic Properties in Renewable Microgrid Management" — artículo sometido a revista indexada Scopus (target: Applied Energy, Energies, o Applied Intelligence) | Sem 3-4 |
| Ponencia en conferencia indexada | "From Simulation to Solar-Powered Prototype: Validating Agent Autonomy on Edge Hardware for Renewable Microgrids" — artículo sometido a conferencia internacional (target: IEEE PES General Meeting, AAMAS, o IEEE ANDESCON) | Sem 3-4 |
| Trabajo de grado (proyecto de capstone) | Documento de trabajo de grado que consolida los resultados de la investigación: arquitectura de agente autónomo con propiedades verificables, evaluación de adaptación de dominio para predicción energética, y validación en prototipo urbano autónomo. Incluye defensa ante panel evaluador conforme al formato MAIA (MAIA4401 + MAIA4402) | Sem 4 |

### 2. Productos resultados de actividades de desarrollo tecnológico e innovación

| Producto | Descripción | Semestre |
|----------|-------------|----------|
| Prototipo de software | Agente autónomo de borde para gestión de microrredes como infraestructura crítica, con arquitectura agéntica (persistencia event-sourced, regulación homeostática, coordinación federada) desplegable en hardware de borde (Raspberry Pi), publicado como software de código abierto (licencia MIT/Apache 2.0) en repositorio GitHub | Sem 3-4 |
| Prototipo físico | Prototipo urbano autónomo: nodo agéntico completo (RPi 5 + panel solar 100W + batería LiFePO4 + carga simulada) operando de forma aislada y autónoma durante al menos 2 semanas continuas en Bogotá, con las 6 propiedades agénticas verificadas en hardware real | Sem 3-4 |
| Modelo predictivo | Modelos entrenados de predicción de generación solar y demanda local, calibrados para tres perfiles climáticos representativos de ZNI (Orinoquía, Pacífico, Insular), exportados a TensorFlow Lite para ejecución en borde, con curva de adaptación de dominio documentada | Sem 2-3 |
| Grafo de conocimiento | Grafo de conocimiento energético-contextual instanciado para al menos dos perfiles climático-operacionales, implementado en formato ligero (SQLite + extensiones de grafos), con al menos 100 entidades y 500 relaciones, disponible para investigación posterior | Sem 1-2 |

### 3. Productos resultados de actividades de apropiación social del conocimiento y divulgación pública de la ciencia

| Producto | Descripción | Semestre |
|----------|-------------|----------|
| Talleres de validación | Al menos 1 taller de validación con actores del ecosistema energético ZNI (IPSE, operadores, comunidades, sector productivo) para evaluar la pertinencia del sistema y retroalimentar el diseño. Modalidad preferente presencial; virtual/híbrida como alternativa. La articulación con comunidades específicas se desarrollará durante el programa y dependerá de las redes institucionales establecidas | Sem 3-4 |
| Ponencia de divulgación | Presentación oral de resultados en congreso nacional (target: Congreso Colombiano de Ingeniería Eléctrica o Encuentro Nacional de Investigación de Uniandes) — diferente de la ponencia indexada en Sección 1 | Sem 4 |
| Publicación de divulgación | Artículo de divulgación en medios de comunicación científica colombiana (portal institucional de Uniandes, Pesquisa Javeriana, o medios de Minciencias) | Sem 4 |

### 4. Productos de actividades relacionadas con la formación de recurso humano para CTeI

| Producto | Descripción | Semestre |
|----------|-------------|----------|
| Trabajo de grado | 1 trabajo de grado (proyecto de capstone MAIA) en Inteligencia Artificial | Sem 4 |
| Documentación técnica | Documentación completa del sistema (guía de despliegue, manual de operación, especificación de la arquitectura agéntica) publicada en el repositorio open-source, orientada a operadores, investigadores y actores institucionales | Sem 4 |

---

## Bibliografía

Ansari, A. F., et al. (2024). Chronos: Learning the Language of Time Series. *arXiv:2403.07815*. https://arxiv.org/abs/2403.07815

Bodewes, W., de Hoog, J., Ratnam, E. L., & Halgamuge, S. (2024). Exploring the Intersection of Artificial Intelligence and Microgrids in Developing Economies: A Review of Practical Applications. *Current Sustainable/Renewable Energy Reports*, 11, 10–23. https://doi.org/10.1007/s40518-024-00233-w

Chacón-Chamorro, M., Giraldo, L. F., Quijano, N., Vargas-Panesso, V., González, C., Pinzón, J. S., Manrique, R., Ríos, M., Fonseca, Y., Gómez-Barrera, D., & Perdomo-Pérez, M. (2025). Cooperative Resilience in Artificial Intelligence Multiagent Systems. *IEEE Transactions on Artificial Intelligence*, 6(12), 3430–3440. https://doi.org/10.1109/TAI.2025.3567371

Chacón-Chamorro, M., Giraldo, L. F., & Quijano, N. (2026). Learning Reward Functions for Cooperative Resilience in Multi-Agent Systems. *arXiv:2601.22292*. https://arxiv.org/abs/2601.22292

Colmenares-Quintero, R. F., et al. (2023). A Data-Driven Architecture for Smart Renewable Energy Microgrids in Non-Interconnected Zones: A Colombian Case Study. *Energies*, 16(23), 7900. https://doi.org/10.3390/en16237900

CREG. (2025). Resolución 101 072 de 2025 — Regulación del modelo de comunidades energéticas. Comisión de Regulación de Energía y Gas. Bogotá.

François-Lavet, V., Henderson, P., Islam, R., Bellemare, M. G., & Pineau, J. (2018). An Introduction to Deep Reinforcement Learning. *Foundations and Trends in Machine Learning*, 11(3-4), 219-354.

Ceron, J. A., Gómez-Luna, E., & Vásquez, J. C. (2025). Driving the Energy Transition in Colombia for Off-Grid Regions: Microgrids and Non-Conventional Renewable Energy Sources. *Energies*, 18(4), 1010. https://doi.org/10.3390/en18041010

Wang, J., Wang, X., Ma, C., & Kou, L. (2021). A survey on the development status and application prospects of knowledge graph in smart grids. *IET Generation, Transmission & Distribution*, 15(3), 383–407. https://doi.org/10.1049/gtd2.12040

Hogan, A., Blomqvist, E., Cochez, M., et al. (2021). Knowledge Graphs. *ACM Computing Surveys*, 54(4), 1-37. https://doi.org/10.1145/3447772

Chun, S., Jung, J., Jin, X., Seo, S., & Lee, K.-H. (2020). Designing an integrated knowledge graph for smart energy services. *The Journal of Supercomputing*, 76, 8058–8085. https://doi.org/10.1007/s11227-018-2672-3

Ramírez, D. [Director IPSE]. (2025, 13 de mayo). Columna del Director: Inteligencia Artificial y Energías Renovables, Una Oportunidad para las Zonas No Interconectadas de Colombia. *IPSE*. Recuperado de: https://ipse.gov.co/blog/2025/05/12/inteligencia-artificial-y-energias-renovables-una-oportunidad-para-las-zonas-no-interconectadas-de-colombia/

IPSE. (2025). 11 municipios se suman al sistema de medición de energía del Centro Nacional de Monitoreo. Recuperado de: https://ipse.gov.co/blog/2025/03/04/11-municipios-se-suman/

Altin, N., Eyimaya, S. E., & Nasiri, A. (2023). Multi-Agent-Based Controller for Microgrids: An Overview and Case Study. *Energies*, 16(5), 2445. https://doi.org/10.3390/en16052445

Zhang, Y., Saber, A. M., Youssef, A., & Kundur, D. (2025). Grid-Agent: An LLM-Powered Multi-Agent System for Power Grid Control. *arXiv:2508.05702*. https://arxiv.org/abs/2508.05702

Zhang, C., Zhang, J., Lu, J., & Zhao, Y. (2026). Large Language Models Meet Energy Systems: Opportunities, Challenges, and Future Perspectives. *Applied Energy*, 403, 127076. https://doi.org/10.1016/j.apenergy.2025.127076

Wu, Y., Chiu, W.-Y., Tsai, Y.-P., Liu, S., & Hua, W. (2026). Multiagent Reinforcement Learning in Enhancing Resilience of Microgrids under Extreme Weather Events. *Expert Systems with Applications*, 267, 129145. https://doi.org/10.1016/j.eswa.2025.129145

Mahela, O. P., et al. (2022). Comprehensive Overview of Multi-agent Systems for Controlling Smart Grids. *CSEE Journal of Power and Energy Systems*, 8(1), 115-131. https://doi.org/10.17775/CSEEJPES.2020.03390

Manrique, R., Grevisse, C., Marino, O., & Rothkugel, S. (2018). Knowledge Graph-Based Core Concept Identification in Learning Resources. *Joint International Semantic Technology Conference (JIST 2018)*, 36-51. https://doi.org/10.1007/978-3-030-04284-4_3

Ministerio de Ciencia, Tecnología e Innovación. (2024). Políticas de Investigación e Innovación Orientadas por Misiones (PIIOM): Resolución 1452 de 2024. Bogotá: Minciencias.

Mosquera, M., Pinzón, J. S., Ríos, M., Fonseca, Y., Giraldo, L. F., Quijano, N., & Manrique, R. (2024). Can LLM-Augmented autonomous agents cooperate? An evaluation of their cooperative capabilities through Melting Pot. *arXiv:2403.11381*. https://arxiv.org/abs/2403.11381

Muszynski, J., et al. (2025). EnergyTwin: A Multi-Agent System for Simulating and Coordinating Energy Microgrids. *arXiv:2511.20590*. https://arxiv.org/abs/2511.20590

OCDE. (2023). Distributed renewable energy in Colombia. *OECD Environment Working Paper No. 213*. https://doi.org/10.1787/deda64ff-en

Olfati-Saber, R., Fax, J. A., & Murray, R. M. (2007). Consensus and Cooperation in Networked Multi-Agent Systems. *Proceedings of the IEEE*, 95(1), 215-233.

República de Colombia. (2021). Ley 2099 de 2021 — Por medio de la cual se dictan disposiciones para la transición energética. *Diario Oficial*.

República de Colombia. (2022). Documento CONPES 4075 — Política de Transición Energética. Departamento Nacional de Planeación.

República de Colombia. (2023). Decreto 2236 de 2023 — Por el cual se reglamentan las Comunidades Energéticas. *Diario Oficial*.

República de Colombia. (2023). Ley 2294 de 2023 — Plan Nacional de Desarrollo 2022-2026 "Colombia Potencia Mundial de la Vida". *Diario Oficial*.

Siemens-Stiftung. (2023). Non-Interconnected Zones in Colombia: A Hidden Natural Paradise Where Renewable Energy Systems Face Threats from Fossil Fuels, Isolation, and Corruption. Recuperado de: https://empowering-people-network.siemens-stiftung.org/non-interconnected-zones-in-colombia-a-hidden-natural-paradise-where-renewable-energy-systems-face-threats-from-fossil-fuels-isolation-and-corruption/

Wang, H., Lei, Z., Zhang, X., Zhou, B., & Peng, J. (2019). A review of deep learning for renewable energy forecasting. *Energy Conversion and Management*, 198, 111799.

Wooldridge, M. (2009). *An Introduction to MultiAgent Systems* (2nd ed.). John Wiley & Sons.

Jin, H., Kim, K., & Kwon, J. (2025). GridMind: LLMs-Powered Agents for Power System Analysis and Operations. *SC'25 Workshops*. https://doi.org/10.1145/3731599.3767409

Ye, Y., et al. (2021). A Scalable Privacy-Preserving Multi-Agent Deep Reinforcement Learning Approach for Large-Scale Peer-to-Peer Transactive Energy Trading. *IEEE Transactions on Smart Grid*, 12(6), 5185–5200. https://doi.org/10.1109/TSG.2021.3103917

Zhang, K., Yang, Z., & Başar, T. (2021). Multi-Agent Reinforcement Learning: A Selective Overview of Theories and Algorithms. *Handbook of Reinforcement Learning and Control*, 321-384.

Eslami, A., & Yu, J. (2026). A Control-Theoretic Foundation for Agentic Systems. *arXiv:2603.10779*. https://arxiv.org/abs/2603.10779

Liu, Z., Li, L., Fu, L., Li, J., Sun, T., & Wang, X. (2023). Knowledge Graph for Low Carbon Power and Energy Systems. *Energy Proceedings*, 2023. https://doi.org/10.46855/energy-proceedings-10361

Ecopetrol. (2026). Resultados financieros cuarto trimestre 2025. Recuperado de: https://www.ecopetrol.com.co/wps/portal/Home/es/noticias/detalle/resultados-2025-cuarto-trimestre

Beutel, D. J., et al. (2020). Flower: A Friendly Federated Learning Framework. *arXiv:2007.14390*. https://arxiv.org/abs/2007.14390

Gao, Y., Hu, Z., Shi, S., Chen, W.-A., & Liu, M. (2024). Adversarial discriminative domain adaptation for solar radiation prediction: A cross-regional study for zero-label transfer learning in Japan. *Applied Energy*, 359, 122685. https://doi.org/10.1016/j.apenergy.2024.122685

Jacob, B., et al. (2018). Quantization and Training of Neural Networks for Efficient Integer-Arithmetic-Only Inference. *Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2704-2713. https://arxiv.org/abs/1712.05877

Nie, Y., et al. (2023). A Time Series is Worth 64 Words: Long-term Forecasting with Transformers (PatchTST). *ICLR 2023*. https://arxiv.org/abs/2211.14730

Paletta, Q., Nie, Y., Saint-Drenan, Y.-M., & Le Saux, B. (2024). Improving cross-site generalisability of vision-based solar forecasting models with physics-informed transfer learning. *Energy Conversion and Management*, 309, 118398. https://doi.org/10.1016/j.enconman.2024.118398

Park, J., et al. (2025). Revisiting LLMs as Zero-Shot Time-Series Forecasters: Small Noise Can Break Large Models. *Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025)*.

Pan, S. J., & Yang, Q. (2010). A Survey on Transfer Learning. *IEEE Transactions on Knowledge and Data Engineering*, 22(10), 1345-1359. https://doi.org/10.1109/TKDE.2009.191

PNNL. (2023). VOLTTRON™ Agent Execution Platform for Electric Power System. Pacific Northwest National Laboratory. https://www.pnnl.gov/available-technologies/volttrontm-agent-execution-platform-electric-power-system

República de Colombia. (2023). Documento CONPES 4129 — Política Nacional de Reindustrialización. Departamento Nacional de Planeación.

Sarmas, E., Dimitropoulos, N., Marinakis, V., Mylona, Z., & Doukas, H. (2022). Transfer learning strategies for solar power forecasting under data scarcity. *Scientific Reports*, 12, 14643. https://doi.org/10.1038/s41598-022-18516-x

Ma, S., Wang, H., Ma, L., et al. (2024). The Era of 1-bit LLMs: All Large Language Models are in 1.58 Bits. *arXiv:2402.17764*. https://arxiv.org/abs/2402.17764

Mineault, P., et al. (2024). NeuroAI for AI Safety: An Agenda for Neuroscience and AI. *arXiv:2411.18526*. https://arxiv.org/abs/2411.18526

Portafolio. (2023, 3 de junio). Amazonas: el proyecto solar que aún no entra en funcionamiento. *Portafolio*. Recuperado de: https://www.portafolio.co/economia/infraestructura/amazonas-el-proyecto-solar-que-aun-no-entra-en-funcionamiento-583834

El Tiempo. (2025, 4 de junio). A juicio Carlos Arturo Rodríguez, exgobernador de Amazonas, acusado por la Corte por presunta corrupción. *El Tiempo*. Recuperado de: https://www.eltiempo.com/justicia/cortes/a-juicio-carlos-arturo-rodriguez-exgobernador-de-amazonas-acusado-por-la-corte-por-presunta-corrupcion-3460386

Vorágine. (2024, 2 de junio). Gobierno Petro: contrato en La Guajira, paneles solares que no llegaron. *Vorágine*. Recuperado de: https://voragine.co/historias/investigacion/gobierno-petro-contrato-en-la-guajira-paneles-solares-que-no-llegaron/

El Espectador. (2025). Las fallas de la comunidad energética que prometió energía 24 horas en Bahía Málaga. Recuperado de: https://www.elespectador.com/ambiente/las-fallas-de-la-comunidad-energetica-que-prometio-energia-24-horas-en-bahia-malaga/

Huang, J., Zhou, S., Li, G., & Shen, Q. (2025). Real-time monitoring and optimization methods for user-side energy management based on edge computing. *Scientific Reports*, 15, 24890. https://doi.org/10.1038/s41598-025-07592-4

Mazzola, S., et al. (2017). Assessing the value of forecast-based dispatch in the operation of off-grid rural microgrids. *Renewable Energy*, 108, 116-125. https://doi.org/10.1016/j.renene.2017.02.040

Mei, K., et al. (2025). AIOS: LLM Agent Operating System. *COLM 2025*. https://arxiv.org/abs/2403.16971

NREL. (2018). Phase I Microgrid Cost Study — Data Collection and Analysis of Microgrid Cost in the United States. *NREL/TP-5D00-67821*. https://docs.nrel.gov/docs/fy19osti/67821.pdf

Yang, T., Xu, Z., Ji, S., Liu, G., Li, X., & Kong, H. (2025). Cooperative optimal dispatch of multi-microgrids for low carbon economy based on personalized federated reinforcement learning. *Applied Energy*, 378(A), 124641. https://doi.org/10.1016/j.apenergy.2024.124641

DANE. (2023). Censo Nacional de Población y Vivienda — Indicadores territoriales de pobreza multidimensional.

DANE. (2023). Encuesta Nacional de Calidad de Vida (ECV) 2022 — Indicadores básicos de TIC en hogares. Boletín Técnico. Recuperado de: https://www.dane.gov.co/index.php/estadisticas-por-tema/tecnologia-e-innovacion/tecnologias-de-la-informacion-y-las-comunicaciones-tic/indicadores-basicos-de-tic-en-hogares

Das, A., Kong, W., Sen, R., & Zhou, Y. (2024). A decoder-only foundation model for time-series forecasting. *Proceedings of the 41st International Conference on Machine Learning (ICML)*, PMLR 235, 10148–10167. https://arxiv.org/abs/2310.10688

Gruver, N., Finzi, M., Qiu, S., & Wilson, A. G. (2023). Large Language Models Are Zero-Shot Time Series Forecasters. *Advances in Neural Information Processing Systems 36 (NeurIPS 2023)*. https://arxiv.org/abs/2310.07820

Liu, C., Aksu, T., Liu, J., Liu, X., Yan, H., Pham, Q., Savarese, S., Sahoo, D., Xiong, C., & Li, J. (2025). Moirai 2.0: When Less Is More for Time Series Forecasting. *arXiv:2511.11698*. https://arxiv.org/abs/2511.11698

Ma, S., Huang, S., et al. (2025). BitNet b1.58 2B4T Technical Report. *arXiv:2504.12285*. https://arxiv.org/abs/2504.12285

Microgrid Knowledge. (2025). Beyond SCADA: Managing Operational Complexity in the Data Center Era. Recuperado de: https://www.microgridknowledge.com/infrastructure/controllers-amp-software/article/55337655/beyond-scada-managing-operational-complexity-in-the-data-center-era

MinEnergía. (2024). MinEnergía y FENOGE abren proceso de contratación para la implementación de 500 Comunidades Energéticas en Colombia. Ministerio de Minas y Energía. Recuperado de: https://www.minenergia.gov.co/es/comunidades-energeticas/

Mishra, A., Ravindra, T., Iyengar, S., Kalyanaraman, S., & Kumaraguru, P. (2025). SPIRIT: Short-term Prediction of solar IRradIance for zero-shot Transfer learning using Foundation Models. *arXiv:2502.10307*. https://arxiv.org/abs/2502.10307

Ouedraogo, S., Faggianelli, G. A., Pigelet, G., Notton, G., & Duchaud, J. L. (2021). Performances of energy management strategies for a Photovoltaic/Battery microgrid considering battery degradation. *Solar Energy*, 230, 654–665. https://doi.org/10.1016/j.solener.2021.10.067

Parlamento Europeo y Consejo de la Unión Europea. (2024). Reglamento (UE) 2024/1689 por el que se establecen normas armonizadas en materia de inteligencia artificial (Ley de Inteligencia Artificial). *Diario Oficial de la Unión Europea*, L series. https://eur-lex.europa.eu/eli/reg/2024/1689/oj/eng

Pinter, J., Beichter, M., Mikut, R., Zahn, F., & Hagenmeyer, V. (2025). Averaging favors MPC: How typical evaluation setups overstate MPC performance for residential battery scheduling. *arXiv:2510.25373*. https://arxiv.org/abs/2510.25373

Smith, R. G. (1980). The Contract Net Protocol: High-Level Communication and Control in a Distributed Problem Solver. *IEEE Transactions on Computers*, C-29(12), 1104–1113. https://doi.org/10.1109/TC.1980.1675516

Wen, Y. & Chen, X. (2025). X-GridAgent: An LLM-Powered Agentic AI System for Assisting Power Grid Analysis. *arXiv:2512.20789*. https://arxiv.org/abs/2512.20789

WHO. (2023). Household air pollution and health — Fact sheet. World Health Organization. Recuperado de: https://www.who.int/news-room/fact-sheets/detail/household-air-pollution-and-health

Xendee Corporation. (2024). Xendee's Adaptive Microgrid Control Technology Achieves 79.4% Operational Cost Savings. *Business Wire*. Recuperado de: https://www.businesswire.com/news/home/20240723669119/en/Xendees-Adaptive-Microgrid-Control-Technology-Achieves-79.4-Operational-Cost-Savings
