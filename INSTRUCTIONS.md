# 🛠️ Cronograma de Circuitos Secuenciales / Zirkuitu Sekuentzialen Kronograma / Sequential Circuit Timing Diagram

| **Alumnos** | **Curso** | **Módulo** |
|-------------|-----------|------------|
| 2ME         | 1º        | EEM (Equipos Microprogramables) |

---

## 📌Ariketa



**Ariketa (EU): (ZENBAKIA IDATZI)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                           |  
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
| RS| 4044            | ? | ? |  


## Tabla de la verdad

| Entrada A | Entrada B | Entrada C | Salida    | Salida |
|-----------|-----------|-----------|-----------|--------|
| 0         | 0         | 0         | ░0░       | ░0░    |
| 0         | 0         | 1         | ░1░       | ░1░    |
| 1         | 1         | 0         | ░1░       | ░1░    |
| 1         | 1         | 1         | ░0░       | ░0░    |

----

## 🔲Simulatzeko Zirkuituak

*(Añade aquí la captura de proteus)*

---

## 🔲Kronogramaren Emaitza
<img width="616" height="135" alt="Captura de pantalla 2026-01-20 094958" src="https://github.com/user-attachments/assets/21834841-d2dd-480d-afa4-0a3f4df37966" />


---

## 🔲Kronogramaren Kodea
Ejercicio 2: RS asíncrono (sin reloj)

{
 
  "signal": [
    
    { "name": "Set", "wave": "l.h.l.h.lhlhl..hl" },
    
    { "name": "Reset", "wave": "hl.h.lhl.h...l..h" },
   
    { "name": "", "wave": "" },
    
    { "name": "Q", "wave": "0.1.0.1..X..1...." },
    
   { "name": "-Q", "wave": "1.0.1.0..X..0...." }
  
  ]

}

Ejercicio 2: RS síncrono flanco ascendente


{signal: [
  
  {name: 'clk',   wave: 'P................'},
 
  {name: 'Set',   wave: '1...0..1.0..1..01'},
 
  {name: 'Reset', wave: '0101..0..1.0..1.0'},
  
  {},
  
  {name: 'Q',     wave: '1.x1x0.x1.0.x1.x0'},
  
  {name: '-Q',    wave: '0.x0x1.x0.1.x0.x1'},

]}

Ejercicio 2: RS flanco descendente


signal: [

  {name: 'clk', wave: 'N................'},
 
  {name: 'Set', wave: '1...0..1.0..10.1.'},
 
  {name: 'Reset', wave: '0101..0..1.01.010'},
  
  {},
  
  {name: 'Q', wave: '1.x1x0.x1.0..x0x.'},
 
  {name: '-Q', wave: '0.x0x1.x0.1..x1x.'},

]}


Ejercicio 2: RS nivel alto

{signal: [

  {name: 'clk', period:2, wave: 'p................'},
 
  {name: 'Set', wave: '1...0..1.0..10.1.'},
  
  {name: 'Reset', wave: '0101..0..1.01.010'},
 
  {},
  
  {name: 'Q', wave: '1...0...1.0.1.0.1'},
  
  {name: '-Q', wave: '0...1...0.1.0.1.0'},

]}

Ejercicio 2: RS nivel bajo

{signal: [

  {name: 'clk', wave: 'n................'},
  
  {name: 'Set', wave: 'h...l..h.l..hl.h.'},
  
  {name: 'Reset', wave: 'lhlh..l..h.lh.lhl'},
  
  {},
  
  {name: 'Q', wave: '1.......0....1...0......1.0...1...'},
 
  {name: '-Q', wave: '0.......1....0...1......0.1...0...'},

]}








## 📤Igo
- **EU:** Igo hurrengo fitxategiak. Igotako fitxategi guztiek zure izena eduki behar dute.  
  - Sinboloaren argazki bat.  
  - Proteus fitxategia eta zirkuitu bakoitzaren irudia (captura) Proteusen.  
  - Wavedrom bakoitzaren emaitzaren kaptura (grafikoa bakarrik).  
  - **KONTUZ:** Kronogramaren kodea kodea izan behar da, ez irudi bat.



