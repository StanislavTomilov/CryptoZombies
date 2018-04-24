# CryptoZombies
Игра написанная на языке Solidity, предполагается размещение логики игры в блокчейне Ethereum.

[ZombieFactory.sol](https://github.com/StanislavTomilov/CryptoZombies/blob/master/ZombieFactory.sol) - основной контракт, в контракте находятся методы для создания зомби, мапы для хранения зомби-токенов для определенных адресов.

[ZombieFeeding.sol](https://github.com/StanislavTomilov/CryptoZombies/blob/master/ZombieFeeding.sol) - контракт для кормления (размножения) зомби. Добавлена возможность кормить зомби криптокотятами. Добавлен кулдаун на корпление (размножение)

[ZombieHelper.sol](https://github.com/StanislavTomilov/CryptoZombies/blob/master/ZombieHelper.sol) - в данном контракте содержатся функции для вывода полученных средств владельцем DApp, повышения уровня за вознаграждение, для изменения имени зомби, изменения внешнего вида зомби, получение списка зомби по адресу владельца

[ZombieAttack.sol](https://github.com/StanislavTomilov/CryptoZombies/blob/master/ZombieAttack.sol) - в контракте описана логика боевых действий в отношении других зомби

[ERC721.sol](https://github.com/StanislavTomilov/CryptoZombies/blob/master/ERC721.sol) - интерфейс для ERC721 токенов

[SafeMath.sol](https://github.com/StanislavTomilov/CryptoZombies/blob/master/SafeMath.sol) - библиотека SafeMath из OpenZeppelin

[ZombieOwnership.sol](https://github.com/StanislavTomilov/CryptoZombies/blob/master/ZombieOwnership.sol) - контракт для реализации логики токена в отношении зомби, т.е. зомби можно обмениваться, одобрять передачу, сообщать владельца по ID зомби, узнавать общее кол-во зомби по адресу.

[Ownable.sol](https://github.com/StanislavTomilov/CryptoZombies/blob/master/Ownable.sol) - вспомогательный контракт для реализации собственных модификаторов типа onlyOwner
