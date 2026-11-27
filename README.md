# SigmaOS themes-loops

> Forked from AaryanSinghChauhan09/SigmaOS-themes-loops (MIT). See `SIGMAOS_FORK.md`.

The live background loops for the built-in SigmaOS themes: a quiet version of a theme's still that keeps moving, which OWE plays in the still's place while animations are on. They ship as the `sigmaos-themes-loops` package, which installs `<theme>/<name>.mp4` here to `/usr/share/omarchy/themes/<theme>/backgrounds/loops/<name>.mp4`.

A loop plays in place of the still with the same name in that theme's `backgrounds/` in [AaryanSinghChauhan09/SigmaOS](https://github.com/AaryanSinghChauhan09/SigmaOS), so `lumon/01-united-in-severance.mp4` belongs to `themes/lumon/backgrounds/01-united-in-severance.webp`. Its first frame is that still and its last frame leads straight back into it. See `docs/theming.md` there for how loops play.

`bin/check` holds every loop to the format `docs/theming.md` asks for, so the hand-over from the still and each restart stay seamless: H.264 with no B-frames, one keyframe, colour tags, twenty seconds or less, and its still's shape at no larger than its size.

To add or change a loop, open a pull request here. Once it merges, cut a release tagged with the date, `vYYYY.MM.DD` (or `vYYYY.MM.DD.1` for a second one that day). [AaryanSinghChauhan09/SigmaOS-pkgs](https://github.com/AaryanSinghChauhan09/SigmaOS-pkgs) picks the release up and updates `sigmaos-themes-loops` to it.
## Documentation

Wiki documentation is available in the SigmaOS Wiki Staging repository:

- [SigmaOS Wiki Staging](https://github.com/AaryanSinghChauhan09/sigmaos-wiki-staging#SigmaOS-themes-loops) - Full Wiki documentation for all SigmaOS components

## See Also

Related SigmaOS **Desktop** repositories:

- [SigmaOS-shell](../SigmaOS-shell/README.md) — SigmaOS desktop shell
- [SigmaOS-shell-config](../SigmaOS-shell-config/README.md) — SigmaOS shell configuration
- [SigmaOS-deskland](../SigmaOS-deskland/README.md) — SigmaOS Deskland desktop environment
- [SigmaOS-hyprland-titlebars](../SigmaOS-hyprland-titlebars/README.md) — SigmaOS Hyprland titlebars
- [SigmaOS-sddm](../SigmaOS-sddm/README.md) — SigmaOS display manager theme & config
- [SigmaOS-ui](../SigmaOS-ui/README.md) — SigmaOS UI toolkit
- [SigmaOS-theme-registry](../SigmaOS-theme-registry/README.md) — SigmaOS theme registry
- [SigmaOS-theme-marketplace](../SigmaOS-theme-marketplace/README.md) — SigmaOS theme marketplace
- [SigmaOS-themes-intros](../SigmaOS-themes-intros/README.md) — SigmaOS boot & login theme intros
