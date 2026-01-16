# [L4D2] coop save weapon
Сайт: [forums.alliedmods.net](https://forums.alliedmods.net/showthread.php?t=263860)
===========

Основные функции плагина (ru):
* Предназначен для кооперативного режима (Coop и Realism) Left 4 Dead 2.
* Имеет компактный исходный код.
* Кэширует основные игровые модели.
* Сохранение и восстановление внешности выжившего (модели персонажа).
* Выдача SMG с глушителем новым игрокам, если у них нет сохранённого основного оружия (опционально).
* Корректно возвращает сохранённое оружие ближнего боя после использования на игроке дефибриллятора.
* Исправляет ошибку сохранения оружия при переходе между картами в кампании (5-26 слотов).
* Распространяется под лицензией GPL-3.0.

Консольные переменные (ConVars)
* l4d2_hx_health - Восстанавливает 100 HP в конце главы (0 - выключено, 1 - включено)
* l4d2_hx_noob - Выдает silenced SMG при отсутствии сохраненного оружия (0 - выключено, 1 - включено)
* l4d2_hx_skin - Сохраняет и восстанавливает модель персонажа (0 - выключено, 1 - включено)

Отладка
* #define HX_DEBUG 1

#

Main functions of the plugin (en):
* Designed for the cooperative modes (Coop and Realism) in Left 4 Dead 2.
* Has a compact source code.
* Caches core game models.
* Saves and restores the survivor’s appearance (character model).
* Provides new players with a suppressed SMG if they do not have a saved primary weapon (optional).
* Correctly restores a saved melee weapon after a player is revived using a defibrillator.
* Fixes the weapon-saving bug that occurs when moving between maps in a campaign (5–26 save slots).
* Distributed under the GPL-3.0 license.

Console Variables (ConVars)
* l4d2_hx_health - Restores 100 HP at the end of a chapter (0 - off, 1 - on).
* l4d2_hx_noob - Gives a silenced SMG if no saved weapon exists (0 - off, 1 - on).
* l4d2_hx_skin - Saves and restores the character model (0 - off, 1 - on).

Debugging
* #define HX_DEBUG 1
