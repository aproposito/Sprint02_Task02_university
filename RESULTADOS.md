# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 14 correctas de 16 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.49 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.36 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.50 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.59 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY, PRIMARY,nif

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.49 ms
✅ Se usó índice(s) en la consulta: id_profesor,id_grado, PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.40 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_curso_escolar

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.47 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ❌ Query 13: Incorrecto
```diff
--- 
+++ 
@@ -1,11 +1,11 @@
 apellido1 | apellido2 | nombre
-Schmidt | Fisher | David
+Fahey | Considine | Antonio
 Kohler | Schoen | Alejandro
 Lemke | Rutherford | Cristina
-Fahey | Considine | Antonio
+Monahan | Murray | Micaela
+Ruecker | Upton | Guillermo
+Schmidt | Fisher | David
+Schowalter | Muller | Francesca
 Spencer | Lakin | Esther
+Stiedemann | Morissette | Alfredo
 Streich | Hirthe | Carmen
-Ruecker | Upton | Guillermo
-Monahan | Murray | Micaela
-Stiedemann | Morissette | Alfredo
-Schowalter | Muller | Francesca
```

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.41 ms
✅ Se usó índice(s) en la consulta: id_departamento, id_profesor, id_asignatura

---

## ❌ Query 16: Error
- **Descripción**: 'NoneType' object is not iterable

