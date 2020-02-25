# plantuml-diagram

 ## การติดตั้ง plantuml  เพื่อสร้าง diagram

1.ดาวน์โหลดและติดตั้ง [graphviz](https://graphviz.gitlab.io/_pages/Download/Download_windows.html)

1.1 ใช้ตัว graphviz- x.xx.msi

2.ดาวน์โหลดและติดตั้ง [plantuml.jar](http://sourceforge.net/projects/plantuml/files/plantuml.jar/download)

3.รันโปรแกรม plantuml.jar

3.1 เลือก folder ทำงาน

4.ทดสอบการทำงาน โดยสร้างไฟล์ class.puml

4.1 ในไฟล์ class.puml  ให้พิมพ์เนื้อหาต่อไปนี้

``` puml
@startuml
Class01 <|-- Class02
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 -- Class10
@enduml
```

