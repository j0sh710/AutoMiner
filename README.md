# Overview
AutoMiner is a C# WPF algo switching application used in conjunction with MiningRigRentals. Depending on the Profit Selection you have selected AutoMiner will algo switch between the most profitable algos and also manage availablility of your rig on MiningRigRentals. If you rig is rented algo switching stops until the rental is complete.

# Community
https://discord.gg/dqASSme

# Features
1. Mines the most profitable coin according to selected pools api and profit selection used. (BlazePool, Nicehash, and ZergPool currently)
2. Monitors miner crashes and automatically restarts crashed miners.
3. Monitors GPU Temperatures and Utilization. If GPU Utilization drops too low miner restart is attempted. After 6 failures automatic reboot will occur. (Only if "Monitor GPU" is checked)
4. Manages rig availability on MiningRigRentals.com while algo switching.
5. Launch a "Pre-Run Process" prior to starting miner. Useful for overclocking per algo or running other files prior to starting your miner.
6. Easily edit and change miners. Miners are not built in so you are free to use any miner you like.
7. Manage MiningRigRentals.com pricing with MRR Minimum Limit and % Increase from algo switching pools estimate or MRR suggested pricing.
8. Auto closes detached miners that should not be open.
9. Make all of your MiningRigRentals.com rigs available at once to increase odds of being rented and automatically disable when rented.

# Set Up

***For Detail Setup Please View AutoMiner_Setup.pdf***

1. Unzip All Files from latest release and run installer.
2. Obtain MRR API Key and Secret with "Manage Rigs" rights and update Config/Settings.xml file with API keys and Address (BTC).
3. Launch WpfAppAutoMiner.exe and Update the Miner Configuration.
4. After you have enabled and configured the miners you would like select your "MRR Prefered Pool" and click "Create MRR Rigs". The software will create your rigs on the MRR website.
5. Save config and start mining.

# Dev Fee
1. There is a 8 minute per day dev fee (0.5%). Dev fee will not activate when rented.
