# Cờ vua “Mỡ & Mè vs AI” (mobile/tablet friendly)

## Chạy local

Windows:

```powershell
cd dist\chess-mo-me-ai
python -m http.server 8000
```

Mở:
- `http://localhost:8000/index.html`
- Trên điện thoại/tablet cùng Wi‑Fi: `http://<IP-máy-tính>:8000/index.html`

## Ghi chú
- Tap-to-move (chạm quân → chạm ô đến) tự bật trên thiết bị cảm ứng.
- AI dùng Stockfish WASM chạy local trong trình duyệt.
