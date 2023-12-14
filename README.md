# ChainLink-Oracle
1. chainLink Smart contract: CSC
2. User deployed smart contract: USC
3. Chainlink off-chain listen-event: CU
4. USer: U

U --getRN--> USC --getRN--> CSC --Emit Event() --Listen Event--> CU --FulfillRN()--> CSC --Callback()--> USC --getRN()-- U
