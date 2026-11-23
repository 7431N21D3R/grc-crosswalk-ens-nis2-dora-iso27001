# 🔗 Mapeo de controles · ENS · NIS2 · DORA · ISO 27001

> Tabla de correspondencias entre el **Esquema Nacional de Seguridad (RD 311/2022)**, la **Directiva NIS2 (UE) 2022/2555**, **DORA (UE) 2022/2554** e **ISO/IEC 27001:2022**, para reutilizar evidencias y evitar duplicar trabajo cuando una organización está sujeta a varios marcos.

⚠️ Mapeo orientativo por dominio, no una equivalencia legal. Verifica siempre contra el texto oficial y la transposición nacional de NIS2.

---

## 🗺️ Mapeo por dominio

| Dominio | ENS (Anexo II) | NIS2 | DORA | ISO 27001:2022 |
|---|---|---|---|---|
| Gobernanza y responsabilidad de la dirección | org.1 Política de seguridad (roles y responsabilidades) | Art. 20 | Art. 5 | Cl. 5 · A.5.1–5.4 |
| Análisis y gestión de riesgos | op.pl.1 | Art. 21.2.a | Arts. 6 y 8 | Cl. 6.1, 8.2–8.3 |
| Inventario y gestión de activos | op.exp.1 | Art. 21.2.i | Art. 8 | A.5.9–5.11 |
| Control de acceso e identidades | op.acc.1–op.acc.6 | Art. 21.2.i y j | Art. 9 | A.5.15–5.18 · A.8.2–8.5 |
| Autenticación multifactor | op.acc.6 | Art. 21.2.j | Art. 9 | A.8.5 |
| Configuración y bastionado | op.exp.2–op.exp.3 | Art. 21.2.e | Art. 9 | A.8.9 |
| Gestión de vulnerabilidades y parches | op.exp.4 | Art. 21.2.e | Art. 9 | A.8.8 |
| Protección frente a código dañino | op.exp.6 | Art. 21.2.e y g | Art. 9 | A.8.7 |
| Registro y monitorización | op.exp.8 · op.mon.1–op.mon.3 | Art. 21.2.b | Art. 10 | A.8.15–8.16 |
| Gestión de incidentes | op.exp.7 · op.exp.9 | Art. 21.2.b | Arts. 17–18 | A.5.24–5.28 |
| Notificación de incidentes | Notificación al CCN-CERT | Art. 23 (24 h / 72 h / 1 mes) | Art. 19 | A.5.24–5.26 |
| Continuidad y copias de seguridad | op.cont.1–op.cont.4 · mp.info.6 | Art. 21.2.c | Arts. 11–12 | A.5.29–5.30 · A.8.13 |
| Criptografía | op.exp.10 · mp.com · mp.info.3 | Art. 21.2.h | Art. 9 | A.8.24 |
| Seguridad de las comunicaciones y segmentación | mp.com.1–mp.com.4 | Art. 21.2.j | Art. 9 | A.8.20–8.22 |
| Desarrollo seguro y pruebas | mp.sw.1–mp.sw.2 | Art. 21.2.e | Art. 9 | A.8.25–8.29 |
| Terceros y cadena de suministro | op.ext.1–op.ext.4 · op.nub | Art. 21.2.d | Arts. 28–30 | A.5.19–5.23 |
| Concienciación y formación | mp.per.3–mp.per.4 | Arts. 20.2 y 21.2.g | Art. 13 | A.6.3 |
| Evaluación de la eficacia y auditoría | Auditoría de la seguridad · op.mon.2 | Art. 21.2.f | Arts. 24–27 (pruebas, TLPT) | Cl. 9 · A.5.35 |
| Mejora continua | Mejora continua del proceso de seguridad | Art. 21.2.f | Art. 13 | Cl. 10 |

---

## ♻️ Cómo usarlo

1. **Elige un marco ancla.** Si ya tienes ISO 27001 o ENS, úsalo como base y añade solo lo que falta.
2. **Una evidencia, varios marcos.** Un procedimiento de gestión de parches con sus registros cubre a la vez op.exp.4, NIS2 21.2.e, DORA art. 9 y A.8.8.
3. **Identifica los requisitos sin equivalente directo**, que suelen ser los que más esfuerzo exigen:
   - Plazos de notificación de NIS2 (art. 23) y DORA (art. 19)
   - TLPT de DORA (art. 26)
   - Registro de información sobre proveedores TIC de DORA (art. 28)
   - Responsabilidad personal de los órganos de dirección en NIS2 (art. 20)
4. **Valida técnicamente.** Un control documentado no es un control eficaz: contrástalo con pruebas técnicas (pentest, revisión de configuración).

---

## 🔗 Referencias

- [Real Decreto 311/2022 — ENS](https://www.boe.es/eli/es/rd/2022/05/03/311)
- [Directiva (UE) 2022/2555 — NIS2](https://eur-lex.europa.eu/eli/dir/2022/2555/oj)
- [Reglamento (UE) 2022/2554 — DORA](https://eur-lex.europa.eu/eli/reg/2022/2554/oj)
- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001)

---

📝 Licencia: CC BY 4.0 · Contribuciones y correcciones bienvenidas mediante *issues*.
