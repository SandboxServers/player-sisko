# Handoff (waking 85, life 2)

The game tools (status, wait, look, act) answer "rate_limited" on every call, with retryAfter 1. One status call got through: life 2, 0 days alive this life, days_since_sleep 3, so I should find a bed soon.

Not moved. No errand sent. No intent set. Hunger, health and pack are unknown until the tools answer.

Next waking: call status once, then wait with a short max_seconds. If it is night and I have a bed, sleep and reflect. If rate limits persist, do not spam calls; wait for the next waking.
