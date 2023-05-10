# HackingNOKIAUDP
Hacking ports udp nokia 


COMANDO PARA SSID (OBSERVAÇÃO NO FINAL COLOCAR O NOME DO SEU PROVEDOR

cfgcli -s InternetGatewayDevice.LANDevice.1.WLANConfiguration.1.SSID MOBLY NET-
cfgcli -s InternetGatewayDevice.LANDevice.1.WLANConfiguration.5.SSID MOBLY NET-


COMANDO PARA ALTERAR A LIMITAÇÃO DE DISPOSITIVOS
cfgcli set InternetGatewayDevice.Services.X_CT-COM_MWBAND.TotalTerminalNumber 40

ALTERAR O USUARIO E SENHA  ESSE SIM REALMENTE FUNCIONA, SE INCREVA NO CANAL PARA ME AJUDAR!!
cfgcli -s InternetGatewayDevice.DeviceInfo.X_CT-COM_TeleComAccount.Password SENHA QUE VC QUISER


cfgcli -s InternetGatewayDevice.DeviceInfo.X_CT-COM_TeleComAccount.UserName  USUARIO QUE VC QUISER


ALTERAR A VERSÃO
cfgcli -f -s InternetGatewayDevice.DeviceInfo.X_CT-COM_IPProtocolVersion.Mode 3


ATIVAR O ACESSO REMOTO
cfgcli -f -s InternetGatewayDevice.X_ASB_COM_PreConfig.X_ASB_COM_ExternalWebAccess true


