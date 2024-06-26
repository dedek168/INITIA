### Claim Rewards
If you are Validator, you will get commission (maybe 10% from transaction) , and this commission can be withdrawed with following command
```
initiad tx distribution withdraw-rewards $(initiad keys show YOUR_WALLET_NAME --bech val -a) --commission --from YOUR_WALLET_NAME --fees 563000move/944f8dd8dc49f96c25fea9849f16436dcfa6d564eec802f3ef7f8b3ea85368ff --gas=auto --chain-id initiation-1 -y 
```
