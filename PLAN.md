# Telegram Tetris Port — Plan & Progress

## Status: Planning

## Plan

### Phase 1: Prepare the Game (✅ started)
- [x] Created `telegram_port/` folder
- [x] Copied `tetris.html` to `telegram_port/`
- [ ] Audit: game already has Telegram Web App SDK (`tg.ready()`, `tg.expand()`)
- [ ] Adapt: Telegram theme color integration (use `tg.themeParams`)
- [ ] Adapt: Add Telegram MainButton ("PLAY" / "RESTART")
- [ ] Adapt: Add BackButton for navigation
- [ ] Adapt: Haptic feedback on actions
- [ ] Adapt: Proper viewport / safe area handling for Telegram WebView

### Phase 2: Hosting
- [ ] Option A: GitHub Pages (free, permanent, needs git + repo)
- [ ] Option B: Local server + localtunnel (quick test, temporary)
- [ ] Decide and implement

### Phase 3: Telegram Bot Setup
- [ ] Bot already configured: `8699678610:AA...`
- [ ] Create `/play` command or MenuButton to launch Mini App
- [ ] Set Mini App URL in BotFather
- [ ] Test in Telegram

### Phase 4: Deploy & Share
- [ ] Send game to configured Telegram channel
- [ ] Verify it works

## Notes
- Game is a single HTML file, canvas-based, already mobile-friendly
- No external dependencies except Telegram Web App SDK (CDN)
- Audio uses Web Audio API (needs user gesture to start)
