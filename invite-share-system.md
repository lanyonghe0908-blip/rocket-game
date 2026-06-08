# Invite & Share System

## Overview
Players earn rewards by inviting friends and sharing achievements. 

## Invite System

### Reward Tiers
| Tier | Trigger | Inviter Gets | Invitee Gets |
|------|---------|-------------|-------------|
| Basic | Friend joins via link | +3🎮 +1🆓 | +5🎮 startup |
| Active | Friend plays 10+ rounds | +5🎮 | - |
| Paid | Friend buys miner (USDT) | +10🎮 +50⚡ | - |

### Invite Link
```
t.me/rocket_bot?start=ref_<USER_ID>
```

### Anti-abuse
- Same device: reject duplicate registrations
- Same IP: max 3 invites per 24h  
- Activity check: invitee must play 10 rounds for "Active" tier
- Telegram ID binding: one invite per user

## Share System

### Triggers & Rewards
| Trigger | Reward |
|---------|--------|
| Win 5x+ multiplier | +2🎮 |
| Miner boost activated | +1🆓 |
| Top 10 leaderboard | +5🎮 |

### Auto-generated Share Text
```
"🚀 I just won {multiplier}x on Rocket Crash! Try your luck → {link}"
"⛏ My {tier} miner just boosted! Free to play → {link}"
"🏆 I'm #{rank} on the leaderboard! Beat me? → {link}"
```

## Weekly Invite Leaderboard
| Rank | Reward |
|------|--------|
| #1 | 50🎮 + 200⚡ |
| #2 | 30🎮 + 100⚡ |
| #3 | 15🎮 + 50⚡ |

Resets every Monday. Top 3 get bonus rewards.
