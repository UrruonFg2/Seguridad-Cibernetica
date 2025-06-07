## OSSTMM (Open Source Security Testing Methodology Manual)
### Información Básica
- **Última versión**: Al momento de escribir este curso, versión 3 con fecha de derechos de autor de 2010.
- **Organización desarrolladora**: ISECOM (Institute for Security and Open Methodologies)
- **Desempeño**: Proporciona un marco científico para pruebas de seguridad cuantificables y verificables
### Propósitos
- **Primario**: Proporcionar una metodología científica para la caracterización precisa de la seguridad operativa a través del examen y la correlación de los resultados del texto de manera uniforme y confiable.
- **Secundario**: Ofrecer pautas que permitan a un analista realizar una auditoría de OSSTMM certificada.
### Seis resultados garantizados
1. Que la prueba se realizó a fondo.  
2. Que la prueba incluyera todos los canales necesarios.  
3. Que la prueba cumpliera con la ley.  
4. Que los resultados de las pruebas sean medibles de forma cuantificable.  
5. Que los resultados de las pruebas sean uniformes y repetibles.  
6. Que los resultados de la prueba solo contengan hechos derivados de las pruebas en sí.
### Diez pasos para aplicar OSSTMM
(Combinando proceso de 4 puntos y Trifecta)
1. Recopilar pasivamente datos de operaciones normales para comprender el objetivo.  
2. Probar activamente las operaciones agitando las operaciones más allá de la línea de base normal.  
3. Analizar los datos recibidos directamente de las operaciones probadas.  
4. Analizar datos indirectos de recursos y operadores (es decir, trabajadores, programas).  
5. Correlacionar y conciliar la inteligencia de los resultados de las pruebas de datos directos (paso 3) e indirectos (paso 4) para determinar los procesos de seguridad operativa.  
6. Determinar y conciliar los errores.  
7. Derivar métricas de operaciones normales y agitadas.  
8. Correlacionar y conciliar la inteligencia entre las operaciones normales y agitadas (pasos 1 y 2) para determinar el nivel óptimo de protección y control que se implementaría mejor.  
9. Asignar el estado óptimo de las operaciones (paso 8) a los procesos (paso 5).  
10. Crear un análisis de brechas para determinar qué mejoras son necesarias para los procesos que rigen la protección y los controles necesarios (paso 5) para lograr el estado operativo óptimo (paso 8) del actual.

## PTES (Penetration Testing Execution Standard)
### Información Básica
- **Última versión**: 1.1 (aunque el sitio parece no estar actualizado recientemente)
### Siete secciones principales
1. Interacciones previas a la participación  
2. Recopilación de inteligencia  
3. Modelado de amenazas  
4. Análisis de vulnerabilidades  
5. Explotación  
6. Post explotación  
7. Informes
### Propósito declarado
“Proporcionar a las empresas y los profesionales de seguridad un lenguaje y un alcance comunes para realizar pruebas de penetración y evaluaciones de seguridad”.
### Documento de herramientas y técnicas
Las pautas técnicas de PTES.
## OWASP WSTG (Web Security Testing Guide)
### Información Básica
- **Última versión**: v4.2 (2021)
### Cinco fases del marco
Fase 1: antes de que comience el desarrollo  
Fase 2: durante la definición y el diseño  
Fase 3: durante el desarrollo  
Fase 4: durante la implementación  
Fase 5: durante el mantenimiento y las operaciones
### Propósito declarado
“Proporcionar una guía completa para probar la seguridad de las aplicaciones web. Describe técnicas, métodos, herramientas y recursos para probar los problemas de seguridad más comunes de las aplicaciones web ”.
### Doce categorías de pruebas activas
1. Recopilación de información  
2. Pruebas de administración de la configuración y la implementación  
3. Pruebas de gestión de identidad  
4. Prueba de autenticación  
5. Prueba de autorización  
6. Prueba de gestión de sesiones  
7. Prueba de validación de entrada  
8. Manejo de errores  
9. Criptografía  
10. Prueba de lógica empresarial  
11. Pruebas del lado del cliente  
12. Pruebas de API

## MITRE ATT&CK
### Información Básica
- **Última versión**: **ATT&CK v17.1** (2025)
### Razón de desarrollo
MITRE ATT & CK comenzó a documentar las tácticas, técnicas y procedimientos comunes (TTP) que utilizan las amenazas persistentes avanzadas contra las redes empresariales de Windows.
### Seis casos de uso comunes
Emulación de adversarios, Equipo rojo, Desarrollo de análisis de comportamiento, Evaluación de brechas defensivas, Evaluación de madurez de SOC, Enriquecimiento de la inteligencia sobre amenazas cibernéticas.
### Tres dominios tecnológicos
1. Enterprise (redes corporativas)
2. Mobile (dispositivos móviles)
3. ICS (Industrial Control Systems)
### Técnica: Recopilar información de identidad de la víctima
**Sub-técnicas**:
1. Credenciales
2. Direcciones de correo electrónico
3. Posiciones del empleado
### Grupo Lazarus
Lazarus Group es un grupo de amenazas cibernéticas patrocinado por el estado de Corea del Norte. Llevaron a cabo una campaña llamada Operación Trabajo de los Sueños en la que utilizaron ataques de suplantación de identidad para atraer trabajos falsos y otros ataques activos para recopilar direcciones de correo electrónico que luego se utilizaron en campañas de suplantación de identidad

## Preguntas de Reflexión
1. **Otras metodologías comunes**:
   - NIST SP 800-115
   - PCI DSS Penetration Testing Guide
1. **Importancia de seguir metodologías reconocidas**:
   - Asegura cobertura completa
   - Proporciona consistencia en los resultados
   - Facilita la comparación entre pruebas
   - Cumple con requisitos regulatorios
   - Establece un estándar profesional
   - Mejora la reproducibilidad de las pruebas