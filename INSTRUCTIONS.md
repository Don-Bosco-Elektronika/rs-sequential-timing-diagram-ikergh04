# 🛠️ Cronograma de Circuitos Secuenciales / Zirkuitu Sekuentzialen Kronograma / Sequential Circuit Timing Diagram

| **Alumnos** | **Curso** | **Módulo** |
|-------------|-----------|------------|
| 2ME         | 1º        | EEM (Equipos Microprogramables) |

---

## 📌Ariketa



**Ariketa (EU): (ZENBAKIA IDATZI)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                           |  
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
| RS| 4044            | <img width="204" height="154" alt="Captura de pantalla 2026-01-20 122456" src="https://github.com/user-attachments/assets/2b010a3f-4688-4b47-a592-57fadb13522c" />   | 4 D motako flip-flop dituen zirkuitua. 4 bit gordetzeko (memoria). | 



## Tabla de la verdad

| Entrada A | Entrada B | Entrada C | Salida    | Salida |
|-----------|-----------|-----------|-----------|--------|
| 0         | 0         | 0         | ░0░       | ░0░    |
| 0         | 0         | 1         | ░1░       | ░1░    |
| 1         | 1         | 0         | ░1░       | ░1░    |
| 1         | 1         | 1         | ░0░       | ░0░    |

----

## 🔲Simulatzeko Zirkuituak

<img width="937" height="464" alt="Captura de pantalla 2026-01-20 122216" src="https://github.com/user-attachments/assets/2e362401-0945-4042-a1c1-e0b090baa862" />



---

## 🔲Kronogramaren Emaitza
<img width="616" height="135" alt="Captura de pantalla 2026-01-20 094958" src="https://github.com/user-attachments/assets/21834841-d2dd-480d-afa4-0a3f4df37966" />
<img width="800" height="203" alt="Captura de pantalla 2026-01-19 132421" src="https://github.com/user-attachments/assets/afb11db0-9aa3-4354-824a-8ab17de4915b" />
<img width="755" height="198" alt="Captura de pantalla 2026-01-19 132916" src="https://github.com/user-attachments/assets/2af41a39-def8-4461-8cd1-d75b7a9183e9" />
<img width="1363" height="221" alt="Captura de pantalla 2026-01-20 093926" src="https://github.com/user-attachments/assets/53eff665-50a7-4cce-aaae-50cac62cce5a" />
<img width="1352" height="240" alt="Captura de pantalla 2026-01-20 093904" src="https://github.com/user-attachments/assets/bf86a588-b5c8-4a9a-b5c3-9583916639ac" />



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



