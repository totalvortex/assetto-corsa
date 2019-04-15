wget  https://raw.githubusercontent.com/Winetricks/winetricks/master/src/winetricks
chmod +x winetricks
DXVK_HUD=1 ./winetricks corefonts vcrun2008 vcrun2010 vcrun2012 vcrun2013 d3dx11_43 d3dcompiler_43 faudio dinput8 xinput dxvk vulkanrt msxml3 msxml4 msxml6 vulkansdk devenum
DXVK_HUD=1 ./winetricks --force vcrun2017
DXVK_HUD=1 ./winetricks --force dotnet461
DXVK_HUD=1 ./winetricks --force dotnet472
