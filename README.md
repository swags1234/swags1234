<!-- ========== swags1234 • Profile README (Neo-Grid · Dark Neon, dark bg) ========== -->

<!-- Header: animated line -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=900&color=00F1A1&center=true&vCenter=true&width=720&lines=Nikita+(swags1);Builder+of+reliable+systems;DX-obsessed+%E2%80%A2+shipping+fast%2C+testing+faster" alt="typing animation">
</p>

<!-- Social: clean clickable badges (dark) -->
<p align="center">
  <a href="https://t.me/nikitosixs124"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-0B1220?logo=telegram&logoColor=00B0F4&labelColor=0B1220"></a>
  <a href="mailto:nikitosix1994@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-0B1220?logo=gmail&logoColor=EA4335&labelColor=0B1220"></a>
  <a href="https://x.com/nikitosixs124"><img alt="X (Twitter)" src="https://img.shields.io/badge/X-0B1220?logo=x&logoColor=FFFFFF&labelColor=0B1220"></a>
  <a href="https://discordapp.com/users/swags1"><img alt="Discord" src="https://img.shields.io/badge/Discord-0B1220?logo=discord&logoColor=5865F2&labelColor=0B1220"></a>
</p>

<!-- Thin neon divider -->
<p align="center">
  <img src="https://img.shields.io/badge/----------------------------0B1220?style=for-the-badge&labelColor=0B1220&color=0EA5E9" alt="">
</p>

## `$ whoami`

- **Nikita (swags1)** — делаю стабильные сервисы, держу DX простым и быстрым.  
- Контракты → предсказуемость релизов → наблюдаемость «из коробки».

## `$ selected-work`

<table>
  <tr>
    <td>
      <b>ETHLossTrap</b><br/>
      Detect & prevent risky ETH transfers (heuristics · policies · audit).<br/>
      <a href="https://github.com/swags1234/ETHLossTrap">
        <img alt="Open Repo" src="https://img.shields.io/badge/→%20open%20repo-0EA5E9?labelColor=0B1220">
      </a>
    </td>
    <td>
      <b>daily</b><br/>
      Zero-friction tracker of small wins; weekly markdown report.<br/>
      <a href="https://github.com/swags1234/daily">
        <img alt="Open Repo" src="https://img.shields.io/badge/→%20open%20repo-0EA5E9?labelColor=0B1220">
      </a>
    </td>
  </tr>
</table>

## `$ principles`

- Small, composable services → стабильные релизы и понятные откаты.  
- Strict typing; **CI как ворота**; воспроизводимые окружения.  
- **Observability-first**: обязательные трассировки критических путей.  
- Least-privilege; **никаких** long-lived secrets.

## `$ reference-arch`
```text
client → edge/router → api(s) → service layer → db
                     ↘ auth  ↘ async worker → queue
obs: traces(metrics, logs) · feature flags · progressive rollout
