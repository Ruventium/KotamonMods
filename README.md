# KOTAMON MODS

## English

Two separate experimental BepInEx 6 IL2CPP plugins for KOTAMON, made by AI. Tested on KOTAMON Unity `6000.4.1f1`. I do not know how the game may behave with these mods. Use at your own risk.

`KotamonPileUnlock.dll` lets you open another junk pile before finishing the previous one, preserves old pile contents, and hides the misleading completion message.

`KotamonFPSUnlock.dll` provides a configurable FPS limit and VSync mode.

Config: `BepInEx/config/opencode.kotamon.fpsunlock.cfg`

```ini
[Frame Rate]
TargetFPS = 240
VSyncMode = Off
```

`TargetFPS = 0` means unlimited. `VSyncMode` can be `Game`, `Off`, or `On`.

Install [BepInEx 6 IL2CPP x64](https://builds.bepinex.dev/projects/bepinex_be), then copy the desired DLL directly into `KOTAMON/BepInEx/plugins/`.

Direct downloads: [KotamonPileUnlock.dll](https://github.com/Ruventium/KotamonMods/releases/latest/download/KotamonPileUnlock.dll) and [KotamonFPSUnlock.dll](https://github.com/Ruventium/KotamonMods/releases/latest/download/KotamonFPSUnlock.dll).

Back up `%USERPROFILE%/AppData/LocalLow/KotaMota Games/Kotamon/` first. Delete the DLL to uninstall. I am not responsible for crashes, lost saves, or other damage.

## Русский

Два отдельных экспериментальных плагина BepInEx 6 IL2CPP для KOTAMON, сделанные ИИ. Проверено на KOTAMON Unity `6000.4.1f1`. Я не знаю, как игра может себя повести с этими модами. Используйте на свой риск.

`KotamonPileUnlock.dll` разрешает открыть следующую кучу до завершения предыдущей, сохраняет старый мусор и скрывает ложное уведомление о полной уборке.

`KotamonFPSUnlock.dll` добавляет настраиваемый лимит FPS и режим VSync.

Конфиг: `BepInEx/config/opencode.kotamon.fpsunlock.cfg`

```ini
[Frame Rate]
TargetFPS = 240
VSyncMode = Off
```

`TargetFPS = 0` снимает лимит. `VSyncMode`: `Game`, `Off` или `On`.

Установите [BepInEx 6 IL2CPP x64](https://builds.bepinex.dev/projects/bepinex_be), затем скопируйте нужную DLL напрямую в `KOTAMON/BepInEx/plugins/`.

Прямые ссылки: [KotamonPileUnlock.dll](https://github.com/Ruventium/KotamonMods/releases/latest/download/KotamonPileUnlock.dll) и [KotamonFPSUnlock.dll](https://github.com/Ruventium/KotamonMods/releases/latest/download/KotamonFPSUnlock.dll).

Сначала сделайте копию `%USERPROFILE%/AppData/LocalLow/KotaMota Games/Kotamon/`. Для удаления удалите DLL. Я не отвечаю за вылеты, потерю сейвов или другой ущерб.
