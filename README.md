
* NO SCCM, NO INTUNE, NO PROBLEM.
* Winget PlayBook for EUC.
* No support Servers OS.
* This will show you how to install Software from Winget Package repository.

1) Step 1 create your YAML file. With the list of software you need.
2) Step 2 run your YAML file to install your default software
winget configure .\install.yaml  --accept-configuration-agreements
3) Step 3 if requirements are met, no actions will be performed.
