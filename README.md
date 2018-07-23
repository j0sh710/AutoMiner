# Overview
AutoMiner is a C# WPF algo switching application used in conjunction with MiningRigRentals. Depending on the Profit Selection you have selected AutoMiner will algo switch between the most profitable algos and also manage availablility of your rig on MiningRigRentals. If you rig is rented algo switching stops until the rental is complete.


# Features
1. Mines the most profitable coin according to selected pools api and profit selection used. (BlazePool and ZergPool currently)
2. Monitors miner crashes and automatically restarts crashed miners.
3. Monitors GPU Temperatures and Utilization. If GPU Utilization drops too low miner restart is attempted. After 6 failures automatic reboot will occur. (Only if "Monitor GPU" is checked)
4. Manages rig availability on MiningRigRentals.com while algo switching.
5. Launch "Pre-Run Process" prior to starting miner. Useful for overclocking per algo.
6. Easily edit and change miners. Miners are not built in so you are free to use any miner you like.
7. Manage MiningRigRentals.com pricing with Minimum limit and % Increase from algo switching pools estimate or MRR suggested pricing.
8. Auto closes detached miners.
