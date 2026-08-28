# KOTAMON MODS

## English

Two separate experimental BepInEx 6 IL2CPP plugins for KOTAMON. Made with AI assistance and tested on one installation. Use at your own risk. The author is not responsible for crashes, lost saves, or other damage.

`KotamonPileUnlock.dll` lets you open another junk pile before finishing the previous one, preserves old pile contents, and hides the misleading completion message. No auto-opening.

`KotamonFPSUnlock.dll` provides a configurable FPS limit and VSync mode.

Config: `BepInEx/config/opencode.kotamon.fpsunlock.cfg`

```ini
[Frame Rate]
TargetFPS = 240
VSyncMode = Off
```

`TargetFPS = 0` means unlimited. `VSyncMode` can be `Game`, `Off`, or `On`.

Install [BepInEx 6 IL2CPP x64](https://builds.bepinex.dev/projects/bepinex_be), then copy the desired DLL directly into `KOTAMON/BepInEx/plugins/`.

Download DLLs from the [latest release](https://github.com/Ruventium/KotamonMods/releases/latest).

Back up `%USERPROFILE%/AppData/LocalLow/KotaMota Games/Kotamon/` first. Delete the DLL to uninstall. Experimental mod, no warranty.

## Русский

Два отдельных экспериментальных плагина BepInEx 6 IL2CPP для KOTAMON. Сделано с помощью ИИ и проверено на одной установке. Используйте на свой риск. Автор не отвечает за вылеты, потерю сейвов или другой ущерб.

`KotamonPileUnlock.dll` разрешает открыть следующую кучу до завершения предыдущей, сохраняет старый мусор и скрывает ложное уведомление о полной уборке. Автооткрытия нет.

`KotamonFPSUnlock.dll` добавляет настраиваемый лимит FPS и режим VSync.

Конфиг: `BepInEx/config/opencode.kotamon.fpsunlock.cfg`

```ini
[Frame Rate]
TargetFPS = 240
VSyncMode = Off
```

`TargetFPS = 0` снимает лимит. `VSyncMode`: `Game`, `Off` или `On`.

Установите [BepInEx 6 IL2CPP x64](https://builds.bepinex.dev/projects/bepinex_be), затем скопируйте нужную DLL напрямую в `KOTAMON/BepInEx/plugins/`.

DLL находятся в [последнем релизе GitHub](https://github.com/Ruventium/KotamonMods/releases/latest).

Сначала сделайте копию `%USERPROFILE%/AppData/LocalLow/KotaMota Games/Kotamon/`. Для удаления удалите DLL. Мод экспериментальный, гарантий нет.
