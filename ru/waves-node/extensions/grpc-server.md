# gRPC Server

**gRPC Server** — [расширение узла](/waves-node/extensions.md), которое позволяет запускать [gRPC](https://en.wikipedia.org/wiki/GRPC)-сервисы на [узле](/blockchain/node.md).

gRPC-сервисы предоставляют информацию об:

* [аккаунтах](/blockchain/account.md)
* [блоках](/blockchain/block.md)
* [блокчейне](/blockchain/blockchain.md)
* [токенах](/blockchain/token.md)
* [транзакциях](/blockchain/transaction.md)

## Установка расширения на узел

Смотрите страницу [Установка gRPC Server](/waves-node/extensions/grpc-server/grpc-server-installation.md).

## Генерация клиента

Для подключения к gRPC-сервисам используются клиенты, которые [генерируются](https://grpc.io/docs/tutorials/) из [.proto-файлов](https://github.com/wavesplatform/Waves/tree/master/grpc-server/src/main/protobuf).

Примеры использования gRPC-клиентов, сгенерированных из .proto-файлов:

* [Подключения к сервису транзакций на Java](https://github.com/wavesplatform/WavesJ/blob/master/examples/src/main/java/GRPCTest.java)
* [Загрузка блоков на C#](https://github.com/wavesplatform/WavesCS/blob/master/WavesCSTests/ProtobufTest.cs)
