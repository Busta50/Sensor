# Pantalla LED 
# Por: Jesus Bustamante

**En el siguiente material apreciaremos la diferencia de las pantallas.**
**Para ello iniciaremos con:**
![](titulo.png)

Las pantallas OLED se destacan por su gran contraste, mínimo consumo de energía y buena calidad de imagen. El display oled 0.96" SPI SSD1306 posee una resolución de 128*64 píxeles, permitiendo controlar cada píxel individualmente y mostrar tanto texto como gráficos. Además por ser de tipo OLED no necesita de retroiluminación (Backlight) como los LCD, lo que hace que su consumo de energía sea mucho menor y aumenta su contraste.

Para manejar la pantalla es necesario utilizar un microcontrolador con al menos 1K de RAM, este espacio cumple la función de buffer para el display. El driver de la pantalla es el SSD1306, con una librería lista para usarse en Arduino. La librería permite mostrar texto, mapas de bits, píxeles, rectángulos, círculos y líneas. A pesar de usar 1K de RAM, el funcionamiento es muy rápido y el código es fácilmente portable a distintas plataformas de microcontroladores.

![](Display.png)
![](Display2.png)

**APLICACIONES DE LA PANTALLA OLED**
| **-Smartwatch (Reloj Inteligente)** |
|-------------------------------------|
| **-Equipos médicos portátiles**     |
| **-Equipos industriales**           |
| **-Equipos de Audio**               |

**PANTALLA EN USO**

![](Display4.png)

![](AA.jpg)

**Caracteristicas**

|          **Módelo**          | **Pulgadas** | **Costo** | **Píxeles** |  **Voltaje** |
|:----------------------------:|:------------:|:---------:|:-----------:|:------------:|
|            SSD1306           |     0.96"    |    $135   |   128 X 64  | 1.65V a 3.3V |


| **Fuentes de información**                                                        |
|-----------------------------------------------------------------------------------|
| _https://www.adafruit.com/product/1770_                                           |
| _https://naylampmechatronics.com/oled/83-display-oled-096-spi-12864-ssd1306.html_ |
| _https://elecan3d.com/lcd-tft/499-lcd-tft-28plg-touch-ili9341.html_               |

