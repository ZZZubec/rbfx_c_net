# rbfx_c_net

Здравствуйте!
Меня зовут ZZZubec (aka Salamandr), здесь будет серия коротких уроков по тому как применять rbfx (Rebel Framework game engine).
Сам rbfx находиться тут https://github.com/rbfx/rbfx, он написан на с++ и у меня компилируется через cmake в VS Code, но вы можете делать это и через другие инструменты.
Rbfx это ветка Urho3D ныне находящегося в архиве, а сам rbfx развивается семимильными шагами.

## список официальных каналов
Основной форум - https://discourse.urho3d.io/

Основной русский форум - https://gamedev.ru/community/urho3d/forum/

Дискорд - https://discord.gg/3uW2aK8

Русский telegram: https://t.me/urho3d

Прелесть движка заключается в том что на нём можно писать как на с++, так и на c#. Он поддерживает множество платформ и ничто не мешает подключить вам различные SDK.


## С чего начать
**Здесь будет рассматриваться только C#**

Для того чтобы начать на нём делать игры или приложения на C# Вам необходимо:

ИЛИ установить шаблон для Visual Studio 2022, который содержит в себе платформы: PC, Android, Windows (Universal Windows Platform) и скоро появится web. https://marketplace.visualstudio.com/items?itemName=GlebLebedev.Urho3DNet

ИЛИ начать новый пустой проект и установить через nuget https://www.nuget.org/packages/unofficial.Urho3DNet/

Об этом чуть расскажу чуть позже.

Так же есть 
## Примеры кода которые уже созданы (хоть здесь их соберу)
https://github.com/rbfx/sample-project

https://github.com/gleblebedev/Urho3DNet.Samples/tree/main/src/Urho3DNet.Samples


## Редактор rbfx
для его установки понадобиться установить пакет из nuget или написать в консоли

`dotnet tool install unofficial.Urho3DNet.Editor -g --version 0.3.7.602`
> вместе с редактором идут отладочные заголовки, установка редактора может занять дительное время - не пугайтесь.


После этого Вам достаточно написать в консоли `rbfx` и он запустится
