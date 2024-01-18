<!-- tct -->

js

<!-- user -->

js
C#

<!-- invoice -->

java

<!-- report -->

java
C#

Create business einvoice management reporti

<!--  -->

module.ts = cần thêm vào app.module.ts

interface = interface.ts = phải thêm controllers
controllers = controller.ts = như CRUD bình thường
dto = dto.ts = như CRUD bình thường

core = application = CQRS
core = domain = entity, events, value,

infrastructure= infrastructure.ts = phải thêm repository
adapter.ts = thực hiện implements port.ts và như service
repository.ts = ngon lành ORM

<!-- Thông báo DDD -->

Notification
FindAllNotification

Hướng dẫn NestJS, TypeORM, Domain Driven Design, Clean Architecture, CQRS, Event Sourcing
Tạo và đọc thông tin

Notification ( notification_id, title, content, created_at )

<!--  -->
 
Create Notification
Sửa Notification
Xóa Notification

CreateNotificationCommand
EditNotificationCommand
DeleteNotificationCommand

NotificationCreateEvent
NotificationEditEvent
NotificationDeleteEvent
