# learningNVM

1.	ทำการ load nvm version Latest release (current version 1.1.5): https://github.com/coreybutler/nvm-windows/releases

2.	ทำการติดตั้งนะครับ  และทดสอบผ่าน command line ว่าใช้งานได้หรือเปล่าตามรูป  โดยพิมพ์คำสั่งว่า 
    ```
    nvm --version
    ```
    ![](https://i.imgur.com/3w41H5xg.png)

3.	ทำการลง node  version ที่ต้องการ  โดยใช้คำสั่ง 
    ```
    nvm install <node version>
    ```
    
4.	ทำการเช็ค version node ทั้งหมดที่มีอยู่ในเครื่อง โดยใช้คำสั่ง 
    ```
    nvm list
    ```
    ![](https://i.imgur.com/g4HomRr.png)

5.	ทำการเลือก version node ที่ต้องการใช้งาน
    ```
    nvm use [node version]
    ```
    
    ![](https://i.imgur.com/09CLlhK.png)

6.	ทำการเช็ค version node ที่ใช้งานอยู่
    ```
    node -v
    ```
    
    ![](https://i.imgur.com/FkGMtRd.png)
