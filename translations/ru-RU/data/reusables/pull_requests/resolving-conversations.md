---
ms.openlocfilehash: 1447b6a0f63bcfd6e54954545541808debcb3091
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/05/2022
ms.locfileid: "147062373"
---
### Разрешение бесед

Вы можете разрешить беседу в запросе на вытягивание, если вы открыли запрос на вытягивание или у вас есть доступ на запись в репозиторий, где был открыт запрос на вытягивание.

Чтобы указать, что беседа на вкладке **Измененные файлы** завершена, нажмите кнопку **Разрешить беседу**.

![Беседа по запросу на вытягивание с кнопкой "Разрешить беседу"](/assets/images/help/pull_requests/conversation-with-resolve-button.png)

Вся беседа будет свернута и помечена как разрешенная, что упрощает поиск бесед, которые все еще требуют разрешения.

![Разрешенная беседа](/assets/images/help/pull_requests/resolved-conversation.png)

Если предложение в комментарии выходит за пределы области вашего запроса на вытягивание, можно открыть новую проблему, которая отслеживает обратную связь и связывает ее с исходным комментарием. Дополнительные сведения см. в разделе [Открытие проблемы из комментария](/github/managing-your-work-on-github/opening-an-issue-from-a-comment).

{% ifversion fpt or ghes or ghae-issue-4382 or ghec %}
#### Обнаружение и навигация по беседам

Вы можете обнаружить все беседы и перейти к ним в запросе на вытягивание с помощью меню **Беседы**, которое отображается в верхней части вкладки **Измененные файлы**.

В этом представлении можно увидеть, какие беседы являются неразрешенными, разрешенными и устаревшими. Это упрощает обнаружение и разрешение бесед.

![Отображение меню бесед ](/assets/images/help/pull_requests/conversations-menu.png) {% endif %}
