запуск:

После клонирования репозитория, в папке запустить

yarn

npx hardhat node

сервер будет запущен на localhost:8545

Это параметры сети к которой нужно подключиться в Metamask 

Network Name: Localhost 8545

New RPC URL: http://localhost:8545

Chain ID: 1337

Currency Symbol: ETH

Нужно в расширении для Chrome Metamask создать аккаунты, путем импорта приватных ключей
(по умолчанию в консоли при запуске сервера выведет 20 учеток)

Вот можно эти 2 использовать

Account #0: 0xf39fd6e51aad88f6f4ce6ab8827279cfffb92266 (10000 ETH)
Private Key: 0xac0974bec39a17e36ba4a6b4d238ff944bacb478cbed5efcae784d7bf4f2ff80

Account #1: 0x70997970c51812dc3a010c7d01b50e0d17dc79c8 (10000 ETH)
Private Key: 0x59c6995e998f97a5a0044966f0945389dc9e86dae88c7a8412f4603b6b78690d

Там будет по 10000 ETH. 

Если сервер остановить, то все данные будут потеряны, и что бы все работало снова, нужно после перезапуска сервера зайти в расширение для Chrome Metamask => My Accounts => settings => advanced => Reset Account (и сделать сброс). Иначе при попытке перевода будет ошибка.




