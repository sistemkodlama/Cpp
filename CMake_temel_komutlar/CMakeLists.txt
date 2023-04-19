# Bu bir yorum satırı 

# Kesinlikle her CMake dosyası minimum cmake versiyonunu tanımlamalı 
cmake_minimum_required(VERSION 3.10)    # eğer sistemde yüklü cmake versiyonu 3.10 ve üstü değil ise derleme başlatılmaz 

# Kesinlikle her CMake dosyasında derlemenin yapılacağı projenin ismi girilmeli 
project(hello_cmake)

# Derlenecek dosyaların belirlendiği kısımdır 
add_executable(output main.cpp)     # ilk argüman derleme sonucunda oluşacak binary dosyanın ismini belirler 
                                    # diğer argümanlar ise derlenecek dosyaları belirtir, bu örnekte sadece main.cpp dosyası derlenecek

