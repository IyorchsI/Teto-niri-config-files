# Ryzenadj

The config fixes the strange behavior of the mobile ryzen 5 2500u znver1, when the gpu load reaches the 100%, the cpu will be locked at 400 mhz.

For the correct execution you need to follow the [Ryzenadj installation](https://github.com/FlyGoat/RyzenAdj/tree/master), specially the [RyzenSMU kernel driver](https://github.com/amkillam/ryzen_smu) being necesary by the RyzenAdj command. 

The ryzenadj command

```
ryzenadj --stapm-limit=25000 --fast-limit=25000 --slow-limit=20000 --tctl-temp=90 --vrm-current 35000
```
