
| **`Documentation`** |
|-----------------|

**DHCPv6 is not enabled in Ubuntu by default.** Using ipv4 to connect the vm, follow the instructions https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-ipv6-for-linux to get IPv6.

Created from the discussion initially.
https://social.msdn.microsoft.com/Forums/azure/en-US/610b92b0-986c-410b-b915-8417b687b265/how-can-i-make-my-vm-ipv6-available65311?forum=WAVirtualMachinesforWindows

New-AzureRmResourceGroupDeployment -Name Bichong -ResourceGroupName Default-Japan -TemplateUri ..\vm.json

Thanks.