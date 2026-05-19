# HADES Bot Premium vO

Bot-Agente hibrido de 4 capas. Telegram + Web Terminal + Turbosina ABI.

## Arquitectura
- Capa 0: Turbosina ABI — Motor C 195k tx/s HMAC-SHA256
- Capa 1: PUJ Engine — Protocolo Universal JSON
- Capa 2: Agente Supremo — Router + Memoria SQLite
- Capa 3: Telegram Bot + Web Terminal WebSocket

## Inicio rapido
export TELEGRAM_TOKEN="tu_token"
python3 core/bot.py
# Web: http://localhost:8888

## Acciones
ping | get_time | abi_status | system_info | ncpc_verify
compress | checksum | xor_cipher | echo | help

## Ecosistema
- https://github.com/jdjfkzlkdkclso-lang/HADES-CORE-vOmega
- https://github.com/jdjfkzlkdkclso-lang/AGENTE-GRU-HADES
- https://github.com/jdjfkzlkdkclso-lang/HADES-SUPREMO-vOmega

2026 Lara Systemic - Ocotlan, Jalisco
