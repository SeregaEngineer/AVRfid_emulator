# AVRfid_emulator
AVR rfid emulator. Attiny13A

Сделал себе пропуск.\
Код взят от сюда: https://github.com/aurelient/TUIsla \
Low fuse bit для attyni13a: lfuse = 0x70 \
После прошивки фьюзов для переперошивки МК необходимо внешнее тактирование, я собрал на NE555,\
F > 200kHz. \
[NE555 designer](https://radioaktiv.ru/loads/softf/calc/27942-555-timer-designer-free-programma-dlya-rascheta-shem-na-555-taymere.html)


 ![Фото платы](https://github.com/VillageEngineer/AVRfid_emulator/tree/main/foto/front.jpg) \
 ![Фото платы](https://github.com/VillageEngineer/AVRfid_emulator/tree/main/foto/rear.jpg) 


 
 P.S Если за основу брать мою схему то: 
 1. Рекомендую сделать  отверстие в верхней части 
 2. Не срабатывает на маленьких считывателях , типа CP-Z-2
