ภาพที่ 1
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuIfEhL2mgT7LLKZAJwa4ywmKSXFpD3IXxFByt5GG3oGDv085esCLuBpCgbIWd4DgNWhGB000) 
```
@startuml
sex <|-- body
sex : man()
sex : women()
body : sex()
body : size()
@enduml
```
ภาพที่ 2
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKfEB5AmgT7LLKZDIy_CImNphHGoylDI4ZKqkRWWea0HtQJyp9pK8WrD1IInzDH4e0YNGsfU2j0i0000)
```
@startuml
car <|-- engine
car : honda()
car : toyota()
engine : -boiler()
engine : -gear()
@enduml
```
ภาพที่ 3
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhEIImkLYX9hCZaSYdAB4ijKj05ynIi5590_685EoumNqjN8JmZDJK7AA6h2nC4if9BYqloSu7wh1Hi5FBByugv75BpKa160m00)
```
@startuml
class taxi
Driver - taxi : drives >
taxi *- kmitl : -- >
taxi -- customer : < owns
@enduml
```
ภาพที่ 4
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuSfCIKuiIb6mgT7LLG2nO09M2dc9kQaQcWX-Ic99ga9-ca9IPb591b02AgnTd5eH7Ql0nUMGcfS2D140)
```
@startuml
idcard <|-- card
idcard : identification number()
idcard : name()
idcard : last name()
idcard : date of birth()

card : +sex()
card : +identification number()
card : +name()
card : +last name()
@enduml
```
ภาพที่ 5
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuShDprLGCbHIqDMrKr3AKr98IaogLB1Io4WiI-NYSaZDIm4g0W00)
```
@startuml
mom "1" --> "n" baby : have
@enduml
```
