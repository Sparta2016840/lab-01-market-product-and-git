# Telegram
### https://web.telegram.org/
This is messanger for people communicating. Telegram allows to send messages, videos, files, create your own programmed bots and have fun.

![Telegram Component Diagram](diagrams/out/telegram/component-diagram/Component%20Diagram.svg)

[Telegram Component Diagram Code](diagrams/src/telegram/component-diagram.puml)


Bot API server is need for making connection between telegram bots and users.

Media & file service is need for storing and rendering media content

Secret chat relay is uses another encryption protocols and rules and prodives possibility to make your chat sequre.

Message handling serive handls all requests to send and get messages between users and bots

Notification and updates service prodives notification on the users computer and keeps actual updates.

![Telegram sequence](diagrams/out/telegram/sequence-diagram/Sequence%20Diagram.svg)

[Telegram sequence](diagrams/src/telegram/sequence-diagram.puml)

In uploading message process user choose and send photo. It gets unique file id and saves it on servrs and mobile phone, chechs sums, saves metadata

![deployment telegram](diagrams/out/telegram/component-diagram/Component%20Diagram.svg)

[deploy telegram](diagrams/src/telegram/deployment-diagram.puml)

Mobile app deployed on the users mobile phones or desktope app on the computer or in web browser. All codes and connections are on server.

- Telegram: "I assume the cloud storage system implements deduplication to optimize storage costs for shared media files."

How secret chats are differ from common chats in keeping data?

How secret chats are saved on servers and what happens when users delete them.

