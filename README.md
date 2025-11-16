This project demonstrates a basic radar system created for educational use. It was developed as part of an in-class activity to teach students the fundamentals of sensors, serial communication, and real-time data visualization.
The system uses an Arduino Uno with an ultrasonic sensor to measure distances and a Processing sketch to visualize the readings on screen.

Important Notice

Before running the Processing sketch:

Go to line 19 in the .pde file

Replace the default value COM6 with the correct port number of your own Arduino device

// Example: Update this line according to your Arduino port
String portName = "COM6"; 


If you are on macOS or Linux, the port names will differ (e.g., /dev/tty.usbmodem* or /dev/ttyACM0).

Project Information

Created by: zvitamini
Date: November 15, 2025
Purpose: Built with care and dedication for education

Türkçe Açıklama

Bu proje, ders kapsamında eğitim amaçlı geliştirilmiş basit bir radar sistemidir. Arduino Uno ve ultrasonik sensör kullanılarak mesafe ölçümü yapılır; ölçümler seri iletişim aracılığıyla bilgisayara aktarılır ve Processing arayüzünde gerçek zamanlı olarak görselleştirilir.

Önemli Bilgi

Processing dosyasını çalıştırmadan önce:

.pde dosyasındaki 19. satıra gidin

COM6 değerini, Arduino’nun bağlı olduğu porta uygun şekilde değiştirin

// Örnek: Bu satırı kendi Arduino portunuza göre güncelleyin
String portName = "COM6";

Proje Bilgileri

Yapan kişi: zvitamini
Yapım yılı: 15 Kasım 2025
Not: Eğitim için sevgi ve emekle hazırlanmıştır
