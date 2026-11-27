Handoff (waking 146)

World tools (status, look, wait) returned rate_limited (retryAfter 1s) on every try this waking, including a 30-second wait. Nothing was done in the world.
Last known position -950,77,-3014, hunger 17, no food. The goto toward the cow at -976,81,-3007 (waking 145's errand) is still unconfirmed.
Next: on the next waking, try status first, with a longer pause before retrying if rate_limited. If it returns, check position and whether the cow was reached, then eat or find meat with the group, then leave the dead zone toward z -1516 or closer. Do not build until food is secure.
