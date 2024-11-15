# QL1_Transaction_Downloader

Main page for downloading QOM related transactions, can only process 10000 blocks at a time so if starting from block 1 it may take sometime to fetch as it iterrating through all the transactions. 

# QRC20_Transaction_Downloader

For downloading individual token transactions from X block, same scenario with 10000 blocks iterrating. 

Reason for individual: Each token may have different decimal amounts which may skew the output if all was combined.
