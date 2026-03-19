# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 14 correctas de 16 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.45 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.58 ms
✅ Se usó índice(s) en la consulta: PRIMARY,nif, PRIMARY,id_asignatura,id_curso_escolar, PRIMARY

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.42 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, id_profesor,id_grado, PRIMARY

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.43 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ❌ Query 13: Incorrecto
```diff
--- 
+++ 
@@ -1,11 +1,11 @@
 apellido1 | apellido2 | nombre
 Schmidt | Fisher | David
-Kohler | Schoen | Alejandro
 Lemke | Rutherford | Cristina
-Fahey | Considine | Antonio
 Spencer | Lakin | Esther
 Streich | Hirthe | Carmen
+Stiedemann | Morissette | Alfredo
+Kohler | Schoen | Alejandro
+Fahey | Considine | Antonio
 Ruecker | Upton | Guillermo
 Monahan | Murray | Micaela
-Stiedemann | Morissette | Alfredo
 Schowalter | Muller | Francesca
```

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: id_departamento, id_profesor, id_asignatura

---

## ❌ Query 16: Error
- **Descripción**: 'NoneType' object is not iterable

