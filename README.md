# TQK MD Reader

Trình đọc Markdown cho Windows: **mục lục bên trái, nội dung ở giữa**, hỗ trợ tiếng Việt/Anh, mở file `.md` bằng double-click.

[English below](#english)

## Tải & cài đặt

- File cài: `dist/TQK-MD-Reader-Setup-0.1.0.exe` (trong repo này)
- Cài per-user, không cần quyền admin. Lần đầu SmartScreen có thể hỏi → More info → Run anyway.
- Sau khi cài, double-click bất kỳ file `.md` nào trong Explorer để mở thẳng trong app.

## Tính năng

- Mục lục tự động theo heading, click để nhảy tới, có ô lọc
- Sáng/tối (dark mode), ghi nhớ ngôn ngữ + file mở gần đây
- Không cần mạng, đọc file local 100%

## Dev (dành cho dev)

```
npm install
npm test
npm start
npm run dist   # build installer vào dist/
```

---

<a id="english"></a>
## English

Elegant Markdown reader for Windows: **TOC on the left, content centered**, EN/VI i18n.

- Installer: `dist/TQK-MD-Reader-Setup-0.1.0.exe` in this repo
- Per-user install, no admin needed. Double-click any `.md` file to open it in the app.
- Auto TOC with filter, dark mode, recent files, 100% offline.
