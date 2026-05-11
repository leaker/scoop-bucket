# leaker/scoop-bucket

Multi-product [Scoop](https://scoop.sh) bucket for [leaker](https://github.com/leaker)'s projects.

## Available manifests

| App   | Description                                                                | Upstream                                  |
|-------|----------------------------------------------------------------------------|-------------------------------------------|
| pouch | Desktop webview wrapper for web games with MITM proxy and script injection | https://github.com/leaker/pouch           |

## Install

```pwsh
scoop bucket add leaker https://github.com/leaker/scoop-bucket
scoop install pouch
```

## Update

```pwsh
scoop update pouch
```

## Uninstall

```pwsh
scoop uninstall pouch
```

## Notes

- Pouch is shipped as a portable `.zip` containing `pouch.exe`, `hook.conf.toml`, and the `inject/` directory.
- The executable is **not Authenticode-signed**, so Windows SmartScreen may block it on first launch. To run anyway:
  right-click `pouch.exe` -> **Properties** -> tick **Unblock** -> **OK**. Alternatively, click **More info** -> **Run anyway** in the SmartScreen dialog.
