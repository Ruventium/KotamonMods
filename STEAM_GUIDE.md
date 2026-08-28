# KOTAMON MODS / МОДЫ

## Русский

Два отдельных экспериментальных мода для KOTAMON, сделанные ИИ. Проверено на KOTAMON Unity `6000.4.1f1`. Я не знаю, как игра может себя повести с этими модами. Используйте на свой риск.

`KotamonPileUnlock.dll` разрешает вручную открывать следующую кучу до завершения предыдущей, сохраняет старый мусор и убирает ложное уведомление об уборке всего мусора.

`KotamonFPSUnlock.dll` меняет лимит FPS через `BepInEx/config/opencode.kotamon.fpsunlock.cfg`.

```ini
[Frame Rate]
TargetFPS = 240
VSyncMode = Off
```

`TargetFPS = 0` снимает лимит. `VSyncMode`: `Game`, `Off` или `On`.

Требуется [BepInEx 6 IL2CPP x64](https://builds.bepinex.dev/projects/bepinex_be). Скопируйте нужные DLL напрямую в `BepInEx/plugins/`.

Прямые ссылки: [PileUnlock DLL](https://github.com/Ruventium/KotamonMods/releases/latest/download/KotamonPileUnlock.dll) и [FPSUnlock DLL](https://github.com/Ruventium/KotamonMods/releases/latest/download/KotamonFPSUnlock.dll).

Перед установкой сделайте копию `%USERPROFILE%/AppData/LocalLow/KotaMota Games/Kotamon/`. Мод экспериментальный, гарантий нет.

## English

Two separate experimental KOTAMON mods. Built with some AI assistance and tested on one installation. Use at your own risk. The author is not responsible for crashes, lost saves, or any other damage.

`KotamonPileUnlock.dll` lets you manually open the next junk pile before finishing the previous one, preserves old pile contents, and hides the misleading all-junk-cleaned message. No auto-opening.

`KotamonFPSUnlock.dll` changes the FPS limit through `BepInEx/config/opencode.kotamon.fpsunlock.cfg`.

```ini
[Frame Rate]
TargetFPS = 240
VSyncMode = Off
```

`TargetFPS = 0` removes the limit. `VSyncMode`: `Game`, `Off`, or `On`.

Requires [BepInEx 6 IL2CPP x64](https://builds.bepinex.dev/projects/bepinex_be). Copy the desired DLL files directly to `BepInEx/plugins/`.

Direct links: [PileUnlock DLL](https://github.com/Ruventium/KotamonMods/releases/latest/download/KotamonPileUnlock.dll) and [FPSUnlock DLL](https://github.com/Ruventium/KotamonMods/releases/latest/download/KotamonFPSUnlock.dll).

Back up `%USERPROFILE%/AppData/LocalLow/KotaMota Games/Kotamon/` first. I am not responsible for crashes, lost saves, or other damage.
