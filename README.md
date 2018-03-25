# vrp_bars

This script will change the bars of life, vest, hunger and thirst

# Tutorial

First you need to go to vrp> modules> survival.lua
Put this on top ---> HUDclient = Tunnel.getInterface("vrp_bars")

Now where you have vRPclient._setProgressBar you need to comment

Ex:
if data.hunger >= 100 then
  --vRPclient._setProgressBarText(source,"vRP:hunger",lang.survival.starving())
else
  --vRPclient._setProgressBarText(source,"vRP:hunger","")
end
