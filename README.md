
### **1. Control de Ventilación Automatizada**
- **Actuadores:** Servo (control de compuerta) y buzzer (alarma).  
- **Sensor:** DHT22 (temperatura y humedad).  
- **Descripción:** Si la temperatura supera los 30°C, el servo abre la compuerta de ventilación y activa el buzzer.  
- **Interfaz:**  
  - QLabel para mostrar temperatura y humedad.  
  - QPushButton para activar/desactivar el sistema.  

---

### **2. Indicador de Distancia con Luz**
- **Actuadores:** LEDs RGB (indicador) y buzzer (alarma sonora).  
- **Sensor:** HC-SR04 (distancia).  
- **Descripción:** Los LEDs cambian de color según la distancia detectada; el buzzer se activa si la distancia es menor a 10 cm.  
- **Interfaz:**  
  - QLabel para mostrar la distancia actual.  
  - QPushButton para calibrar el sensor.  

---

### **3. Medidor de Iluminación Ambiental**  
- **Actuadores:** LEDs RGB (intensidad) y buzzer (advertencia).  
- **Sensor:** LDR (intensidad lumínica).  
- **Descripción:** Los LEDs se atenúan según la luz ambiente detectada, y el buzzer se activa si la luz es muy baja.  
- **Interfaz:**  
  - QLabel para mostrar el nivel de iluminación.  
  - QPushButton para ajustar el brillo manualmente.  

---

### **4. Sistema de Riego Automático**  
- **Actuadores:** Servo (válvula) y buzzer (alarma).  
- **Sensor:** LDR (luz solar como indicador de horario).  
- **Descripción:** El servo controla la apertura de la válvula según la hora del día (luz). El buzzer se activa si el sistema falla.  
- **Interfaz:**  
  - QLabel para mostrar el estado del riego.  
  - QPushButton para iniciar/parar el riego.  

---

### **5. Detector de Obstrucción**  
- **Actuadores:** Buzzer (alarma sonora) y LEDs RGB (advertencia visual).  
- **Sensor:** HC-SR04 (distancia).  
- **Descripción:** Si se detecta una obstrucción menor a 5 cm, el buzzer y los LEDs se activan para alertar.  
- **Interfaz:**  
  - QLabel para mostrar la distancia medida.  
  - QPushButton para reiniciar la medición.  

---

### **6. Control de Puertas Automáticas**  
- **Actuadores:** Servo (apertura de puerta) y buzzer (advertencia).  
- **Sensor:** HC-SR04 (presencia).  
- **Descripción:** El servo abre la puerta al detectar movimiento a menos de 50 cm; el buzzer se activa si alguien intenta forzar la puerta.  
- **Interfaz:**  
  - QLabel para mostrar el estado de la puerta.  
  - QPushButton para abrir/cerrar manualmente.  

---

### **7. Termómetro Visual**  
- **Actuadores:** LEDs RGB (indicador de temperatura).  
- **Sensor:** DHT22 (temperatura).  
- **Descripción:** Los LEDs cambian de color según el rango de temperatura detectado: azul (frío), amarillo (cálido), rojo (calor extremo).  
- **Interfaz:**  
  - QLabel para mostrar la temperatura.  
  - QPushButton para configurar los rangos de color.  

---

### **8. Indicador de Niveles con Servo**  
- **Actuadores:** Servo (representa el nivel) y LEDs RGB (advertencia).  
- **Sensor:** HC-SR04 (nivel de agua o líquido).  
- **Descripción:** El servo apunta al nivel detectado por el sensor, y los LEDs se activan si el nivel es crítico.  
- **Interfaz:**  
  - QLabel para mostrar el nivel.  
  - QPushButton para calibrar el sensor.  

---

### **9. Iluminación Controlada por Potenciómetro**  
- **Actuadores:** LEDs RGB (brillo).  
- **Sensor:** Potenciómetro.  
- **Descripción:** El brillo de los LEDs se ajusta según la posición del potenciómetro.  
- **Interfaz:**  
  - QLabel para mostrar el nivel del potenciómetro.  
  - QPushButton para alternar colores.  

---

### **10. Alarma de Sobrecalentamiento**  
- **Actuadores:** Buzzer (alarma) y LEDs RGB (advertencia).  
- **Sensor:** DHT22 (temperatura).  
- **Descripción:** Si la temperatura supera los 35°C, el buzzer y los LEDs se activan para emitir una alerta.  
- **Interfaz:**  
  - QLabel para mostrar temperatura y estado de la alarma.  

---

### **11. Simulación de Faro Marítimo**  
- **Actuadores:** Servo (giro de la luz) y LEDs RGB (faro).  
- **Sensor:** LDR (luz ambiental).  
- **Descripción:** El servo hace girar los LEDs como un faro. Se activa solo si la luz ambiental es baja.  
- **Interfaz:**  
  - QPushButton para iniciar/parar el faro.  

---

### **12. Sistema de Parqueo Asistido**  
- **Actuadores:** LEDs RGB (indicador de distancia) y buzzer.  
- **Sensor:** HC-SR04 (distancia).  
- **Descripción:** Los LEDs y el buzzer ayudan a medir la distancia al estacionar un vehículo.  
- **Interfaz:**  
  - QLabel para mostrar la distancia.  

---

### **13. Reloj de Sol Automatizado**  
- **Actuadores:** Servo (posición del reloj) y buzzer.  
- **Sensor:** LDR (luz solar).  
- **Descripción:** El servo ajusta la posición del reloj según la luz solar detectada.  
- **Interfaz:**  
  - QLabel para mostrar la posición del servo.  

---

### **14. Monitor de Humedad para Plantas**  
- **Actuadores:** LEDs RGB (estado del suelo) y buzzer.  
- **Sensor:** Potenciómetro (simula humedad).  
- **Descripción:** Los LEDs cambian de color según la humedad simulada; el buzzer alerta si es muy baja.  
- **Interfaz:**  
  - QLabel para mostrar el nivel de humedad.  

---

### **15. Termostato Inteligente**  
- **Actuadores:** Servo (control del flujo de aire) y buzzer.  
- **Sensor:** DHT22 (temperatura).  
- **Descripción:** El servo regula el flujo de aire según la temperatura detectada.  
- **Interfaz:**  
  - QLabel para mostrar temperatura y posición del servo.  

---

### **16. Detector de Intrusos**  
- **Actuadores:** Buzzer (alarma) y LEDs RGB.  
- **Sensor:** HC-SR04 (presencia).  
- **Descripción:** El buzzer y los LEDs se activan si se detecta movimiento inesperado.  
- **Interfaz:**  
  - QLabel para mostrar la distancia medida.  

---

### **17. Indicador de Consumo Energético**  
- **Actuadores:** LEDs RGB (indicador) y buzzer.  
- **Sensor:** Potenciómetro (simula consumo).  
- **Descripción:** Los LEDs muestran niveles de consumo y el buzzer alerta si es excesivo.  
- **Interfaz:**  
  - QLabel para mostrar el consumo.  

---

### **18. Control de Persiana Inteligente**  
- **Actuadores:** Servo (control de persiana) y buzzer.  
- **Sensor:** LDR (luz ambiental).  
- **Descripción:** La persiana se ajusta automáticamente según la luz detectada.  
- **Interfaz:**  
  - QLabel para mostrar el estado de la persiana.  

---

### **19. Indicador de Velocidad en Máquinas**  
- **Actuadores:** LEDs RGB (indicador) y buzzer.  
- **Sensor:** Potenciómetro (simula velocidad).  
- **Descripción:** Los LEDs cambian de color según la velocidad simulada, y el buzzer alerta si es excesiva.  
- **Interfaz:**  
  - QLabel para mostrar la velocidad.  

---

### **20. Iluminación Reactiva al Movimiento**  
- **Actuadores:** LEDs RGB y buzzer.  
- **Sensor:** HC-SR04 (distancia).  
- **Descripción:** Los LEDs se encienden según la distancia, y el buzzer se activa si alguien se acerca demasiado.  
- **Interfaz:**  
  - QLabel para mostrar la distancia.  

---
