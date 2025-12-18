Hello,world.



今日は１１月２７日です。

こんにちは世界

@startuml
left to right direction
actor "Student" as fc
rectangle el-Campus {
  usecase "課題提出" as UC1
  usecase "お知らせ閲覧" as UC2
  usecase "小テスト" as UC3
}
fc --> UC1
fc --> UC2
fc --> UC3
@enduml